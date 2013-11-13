# Structure Refinement

## Refinement Method Options
The refinement method can be changed `@Work|Refine|Refinement-Method`. ShelXL offers two refinement methods; one is a full matrix least squares refinement and a conjugent gradient method. Olex2.refine also offers two refinement methods; one is a standard Gauss-Newton and the other, considered to be safer from pitfalls of the former, Levenberg-Marquardt method.
The final refinement cycles should always be carried out using a full matrix least squares method. However, a block refinement can be useful during early cycles of refinement in certain circumstances e.g. if a refinement is unstable, atoms are still being located or for speed with a very large structure (although this is less of a problem with modern computers).

## Additional Refinement Options
The most common refinement options can be set under `@Work|Refine`. Listed here are the most commonly used ones.

### Max. Refinement Cycles
Sets the number of refinement cycles. ShelXL refines up to the maximum number of cycles, regardless if the refinement has settled or not. Olex2.refine will stop earlier if the refinement has converged.
Early on in the refinement, when you know that your structure is far from correct, a few cycles of refinement is about right. If you ask for more cycles, you are not only wasting your time, but you are asking the program to find the minimum of something that you know is wrong. This can lead to unwanted and sometimes confusing shifts in your model.
A larger number of cycles can be useful towards the end of a refinement to ensure the **Max Shift** label I_MAXSHIFT reads 0.000 i.e. the refinement has converged. Click on the label to view the atom where the largest shift occurs. For a large structure early on in the refinement, this may slow the refinement. If the residual shift does not approach 0, there is something wrong with the model and you must figure out what that is before you can finalise the structure.

### Max. Refinement Peaks
Changing the number of Q-peaks displayed. A larger number of residual peaks may be useful earlier on during a refinement when a structure is incomplete in order to see new fragments more easily. As the refinement proceeds and most (or all) of the atoms are located you do not need so many Q-Peaks and can switch them off.

### Weights
Weights will automatically update once the R-factor for your structure goes below the chosen value and you have ticked the corresponding box.
Weights are normally added towards the end of the refinement. Keep refining, until the weights are no longer changing and have turned green.

Applying a weighting scheme will give a flat analysis of variance and GooF close to 1 - it should not be included in the refinement until the structure is essentially complete.

### Extinction Correction
Tick the box to include an extinction correction.
Extinction affects the intensity of reflections and can result in systematically absent reflections being observed under special conditions. This parameter accounts for the intensity changes associated with extinction, the method used is a compromise to cover primary and secondary extinction. In general this should not be included until all of the non-hydrogen atoms have been located.

### Refinement Settings Extra
If additional options are available for a refinement program, as in the case of ShelXL, these will be displayed.

## Assessing a Refinement
To monitor the progress of a refinement you can monitor the various R-factors and other refinement parameters. There are various ways to access these.

### Viewing the output from refinement cycles

- Typing `CODE lines n` where n is a number, will adjust the number of lines of text output behind the graphics screen. You can scroll though the output using the PAGEUP and PAGEDOWN keys.
- Type `CODE text` in the command-line or click on the notepad icon I_TEXT at the top of the GUI panel to open a text editor displaying the full output of everything that has been displayed on the graphics screen for a structure since it was last opened in Olex2.

### Viewing the list file
The list file (in the case of running ShelX programs) can be viewed by typing `CODE edit lst` in the command-line or clicking on I_OPEN and selecting the .lst file. The list file contains more detailed information on the refinement and is particularly useful when there are problems.

### Viewing statistics on refinements and reflections
A summary of the key refinement parameters that are particularly useful to monitor the progress of the refinement are available under `@Info|Refinement-Indicators`. There is also as summary about your data is under `@Info|Reflection-Statistics-Summary`.

- The statistics are colour-coded to provide a quick method to monitor a refinement, such that red=bad, dark=ok. 
- R1, wR2, GooF: Standard algorithms for measuring the quality of the agreement between Fo and Fc. When someone asks `What was the R-factor of your structure?', they are asking for R1 (R1 for reflections filtered by $F_{obs} > 4\sigma(F_{obs})$). A very large R-value suggests an incorrect solution and therefore a need to try more rigorous structure solution routines. The GooF (Goodness of Fit) value should converge to 1.0 at the end of the refinement.
- Highest peak/Deepest hole: Values indicate residual electron density peaks and holes in units of $e^{-}/\AA^{3}$. The closer to 0, the better. 
- Refs (total): the number of reflections read from the hkl file.
- Refs (uni) is the number of unique reflections, after merging equivalent reflections and rejecting systematic absence violations. 
- Refs (Fo> 4sig(Fo)): cutoff for defining `observed data'.
- R_{int}: measure of `equivalence' of symmetry equivalent reflections. Lower the R_{int}: is better. A high value indicates bad data, poor absorption correction, or wrong space group (i.e. Laue symmetry).
- R (sigma): measure of the precision of the resulting mean intensities. Large values indicate that the data is very weak and/or data were incorrectly processed.
- F000: This is the scattering factor (F) for the hkl = 000 reflection. The value is equal to the number of electrons in the unit cell.

## Omitting Reflections
Poorly fitting reflections are listed under `@Info|Bad-Reflections`. Those measured reflections that differ most from the equivalent calculated reflections are listed. If your data reduction step was carried out correctly, there should be none that are significant.

- To omit a reflection click on **omit** to the right of the reflection or type a specific hkl under **Exclude**.
- **Edit Reflections**. This displays the worst-fitting reflections, showing each equivalent occurrence of that reflection separately. You can omit only the offending separate reflections and do not need to throw the whole reflection out. In fact, Olex2 simply moves the flagged reflections to the end of the file (after the `0 0 0' line, indicating to the refinement program that these should be ignored.
- To omit a specific reflection manually, type `CODE OMIT h k l`.
- Use `CODE OMIT ##`, where ## is the minimum value of the $|(F_{calc}^{2}-F_{obs}^{2})/esd$ to omit all reflections where the value is above the threshold.
- In general most of the poorly fitting reflections should have similar values of $|(F_{calc}^{2}-F_{obs}^{2})/esd$ ideally all less than ~ +/- 0. One or two poorly fitting reflections with significantly different values of $|(F_{calc}^{2}-F_{obs}^{2})/esd$ can be removed, but if large numbers appear to be poorly fitting, the reasons for this should be investigated.

##Inverting a Structure
It should never be necessary to invert a structure, because Olex2 will do this automatically when it is required. This automatic inversion will only happen once. If you think we got it wrong and the stereochemistry of your structure is definitely wrong, you can invert a structure by typing `CODE inv -f`.
