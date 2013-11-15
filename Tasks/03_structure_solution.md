# Structure Solution 

The structure solution process \index{structure solution} identifies electron density maxima in the asymmetric unit of the electron density maps, which is calculated from the recorded diffraction data. Once you know the positions of these maxima, you can later assign atom types and proceed with building a structure model.
What solution programs actually do to "solve" the structure, is to solve the "crystallographic phase problem" \index{phase problem}(hence why this is called solution). Like all waves, X-rays have both a phase and amplitude associated with them, however during a diffraction experiment we are only able to measure the amplitude of a reflection ($\sqrt{I}$), not its phase. In order to solve a structure it is essential to determine the relative phase of each reflection in order to sum the waves together correctly.
Structure solution is largely a fully automated process, and in most routine cases it will simply work with default settings. But there are always cases where this step can become quite difficult and there are several things you can do to try and obtain a solution.

## Select a Structure Solution Program
To change the structure solution program go to `@Work|Solve` and examine the drop down menu by **Solution Program** \index{solution programs} to see the options available for use. If a program has more than one choice of method e.g. ShelXS these will be displayed in the drop down menu by @@Solution Method@@.
All structure solution programs work slightly differently, so trying different programs may help. Olex2 is supplied with Olex2.solve but, if present, ShelXS, ShelXM, SIR and Superflip can also be used from within Olex2.

### olex2.solve
This solution program is part of Olex2 and is always available. It uses the charge flipping algorithm \index{charge flipping} to solve structures which is currently considered one of the most powerful approaches for obtaining a structure solution. It also has the added advantage of not requiring knowledge of the correct expected atom types to work. Charge flipping is an iterative process that starts from a random point, therefore repeating the structure solution again (even with the same parameters) does not necessarily lead to the same result. Hence it can be beneficial to repeat a structure solution attempt.

### ShelXS \index{ShelXS}
This is the most widely used program for solving small-molecule structures. It runs faster than charge-flipping, but you must provide the correct space group and it might not work if you do not know the molecular configuration accurately. Within ShelXS, there are three structure solution methods:

- **Direct Methods**: are suitable for attempting a structure solution for any type of structure.
- **Patterson** \index{Patterson method}: this approach is suitable for locating heavy elements in the presence of much lighter ones. Since heavy elements make a significant contribution to the overall scattering location, these will normally give sufficiently good phases to enable the rest of the atoms to be located within a couple of cycles of refinement. 
- **Structure Expansion** \index{structure expansion}: from Olex2, we offer this third option: a Patterson solution is "fed into" the Direct Methods algorithm and this will often lead to a structure when other methods fail.

### ShelXD \index{ShelXD}
This dual-space method \index{dual-space method} is popular for solving macromolecular structures but it also will work for small molecules. It is slow, but if all else fails, it is worth a shot.

### Superflip \index{Superflip}
Superflip is the "heavy weight" implementation of the charge-flipping algorithm. It will almost always solve any structure, regardless of whether you knew the symmetry in advance or knew what atom types to expect. If your original symmetry was wrong, Superflip will return the solution in the correct space group for you.
Olex2 automatically recognises all solution programs from the ShelX suite, as well as Superflip and some versions of SIR, as long as the programs are "on the system PATH" (i.e. you, or the software installation, has set the PATH environment variable to point to these programs). If you absolutely don't want to fiddle with those, you can place the programs (*.exe* files) into the Olex2 directory -- something we do not recommend!

## Check the Space Group \index{incorrect space group}
Getting the space group right is an important condition for obtaining the correct final structures. Sometimes a structure will solve in the wrong space group and the refinement may proceed without obvious major problems. If the space group is wrong, there will always be *some* signs and it is essential to check for these.
A lot of these problems can be prevented by using Superflip as the solution program: it almost always gets the space group right (if the structure solves at all).
An incorrect space group can prevent a structure solution being obtained. However, just because a structure solution can be obtained in one space group, it does not necessarily mean that is the correct space group and checks should always be made for missed symmetry, e.g. by using Platon \index{Platon}. For various reasons beyond the scope of this manual, it can be more difficult to solve a crystal structure in a centrosymmetric space group hence trying a lower symmetry space group e.g. *P1* instead of P-1 can be more successful. Assuming that the higher symmetry space group is the correct one, it is then necessary to convert back to the higher symmetry space group after structure solution.

## Check the Chemical Composition
The chemical composition it displayed in the fixed top tab in the GUI panel. It can be changed under `@Work|Solve` and typing into the @@Chemical Composition@@ text box. For some structure solution programs to work, the correct formula is essential: or at least the correct element types that are present in the structure.
If a structure should contain heavy atoms and the chemical composition does not reflect this or vice versa, some structure solution programs (direct methods in particular) will be adversely affected. It is also worth considering whether the structure is what was expected or could it be a reactant, an intermediate or a by-product. And there is always the possibility that unexpected solvents and counter-ions might have crystallised witht he main molecule.

## Change the Settings Of Structure Solution Programs \index{structure solution settings}
Under `@Work|Solve|Solution-Settings-Extra` additional options specific to the structure solution method selected will be displayed. Adjusting these can help to yield a structure solution in more challenging cases. Please refer to the relevant manuals (specifically for ShelXS and Superflip) for explanations of these options. Here are a few tips for ShelXS:

- Increasing **np** (e.g. from 500 to 5000) increases the number of direct method attempts that are made.
- In cases of pseudo symmetry, try changing *Emin* under ESEL to 1.0/0.9.
- Try **Patterson Methods**: especially if there are heavy elements present in your structure, or **Structure Expansion** 
- Use `CODE tref n` where n is the number of the solution to try. This is normally available after a standard ShelXS structure solution. This way Olex2 will instruct ShelXS to investigate the top n higher probability solutions. You can traverse the solutions using Ctrl+Up/Down keys.

## Check for Signs of Twinning: See \ref{twinning} \index{twinning}

## Check the Cell and Integration
The unit cell dimensions and the integration should be checked prior to attempting a structure solution, but if all of the above methods have failed to yield a structure solution, it is always worth going back to the original data (the diffraction frames) to check whether an alternate cell or twinning has been missed. Rint which is a measure of how "equivalent" symmetry equivalent reflections really are (the lower the Rint, the better). A high value indicates bad data, poor absorption correction, or wrong space group (i.e. Laue symmetry).

## Additional Structure Solution Options
**Reflection File** \index{reflection file}: the file will have the same name as that of the .ins file but if you have more than one .hkl file in the project you can choose to use another file.

> CRYST You should always be careful to ensure that your .ins file corresponds to your .hkl. Olex2 saves the full path of the correct file in the header of the .ins file (in a REM line) and will use that file if it is present.

**Z and Z'**: Z is the number of formula units in the unit cell, Z' is the number of formula units in the asymmetric unit.
