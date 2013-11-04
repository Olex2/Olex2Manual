#Refinement

Now that initial atom assignments have been made, the next stage is to refine the structure to see how well your assignments fit the data and improve the model.

##Initial Atom Type Assignement

1.	Under the Work tab click on the arrow next to the Refine button so that it is pointing upwards and highlighted orange meaning that the refinement options are now displayed. 

2.	Click on the Refine button and Olex2 will refine your structure. Alternatively, you can type `CODE refine` or press CTRL+R.

> CRYST During a \index{refinement} Olex2 is calculating structure factors based on your current structural model and comparing them to the experimentally measured values. Adjustments are then made to the atomic parameters to try and improve the fit.

3.	If one of the atoms you assigned is now represented as a comparatively huge sphere (not just slightly larger than the others), it is not real, select it and press the DELETE key on your keyboard (or right-click and select Delete from the context menu). If you delete an atom by mistake, use CTRL+Z to undo.

	![Large Incorrect Atom](/images/large_incorrect_atom.png)

4.	If there are peaks larger than ~3 units in your difference map, then there are missing C or O atoms. Select these peaks and assign them to either C or O and refine again. Repeat this step until there are no more large Q-peaks left. 

5.	At this point, you can hide all remaining Q-peaks: in Toolbox Work click on the hide Q icon I_Q (or use CTRL+Q) to hide them.

6.	Rotate your structure and examine the size of the atom spheres, they should all be approximately the same size. If this is not the case some of your atoms have been incorrectly assigned. In this image, atoms 3 are correctly assigned atom types with similar sized spheres, 1 is too light atom type (should be heavier) and 2 is too heavy atom type (should be lighter).

	![Different Sized Atom Spheres](/images/different_sized_atom_spheres.png)

> OLEX2 The atoms are displayed as spheres when they are modelled isotropically (i.e. one parameter to define the atomic displacement parameter, ADP). The size of all atom spheres is approximately the same but there are exceptions to the rule, for example if there are long floppy chains (e.g. propyl or butyl) in your structure, the size of the spheres generally increases along the chain to the distal atom due to the increased libration. Atomic disorder can also cause changes in the size of the spheres.

7.	If a sphere is significantly smaller than the others, the atom type is too light e.g. assigned as a carbon atom but it should be an oxygen atom. If it is distinctively larger, it has been assigned as too heavy an atom. Select the offending spheres and change their atom types. If the sphere representing the atom has become too small to see, draw a rectangle (SHIFT+LEFT MOUSE) around the atom to select it. 

	>CRYST If an assigned atom type is too light, there is not enough electron density available to fit the experimental data so the refinement pulls the available electron density into a smaller volume to try and improve the fit to the experimental data. If the assigned atom type is too heavy it has more electron density that expected and the refinement increased the volume over which the electron density is spread to improve the fit to the experimental data.

8.	Carry out further refinement cycles (and adjust atom types!) until all atoms are approximately represented by spheres of the same size.

At this stage you should have R1 ~ 8-9%, wR2 ~25%, Difference map max ~0.7 e' '-3, min ~-0.6 e-3. 

## Anisotropic Refinement

1.	So far, we limited the shape in which we can place electron density to a sphere. The next stage is to model the atoms as ellipsoids: using `anisotropic displacement parameters` (ADP) requires 6 parameters to define the volume occupied by the electron density rather than the single one that was used to define the sphere during \index{isotropic refinement}.

2.	Click on the rugby-ball shaped blue icon I_ANIS on Toolbox Work at the top right. Olex2 will then automatically carry out an anisotropic refinement.

	>OLEX2 Atoms will now be displayed more like rugby balls, however if they appear like pancakes or are comparatively much larger than other atoms in the structure, this should be investigated. Common reasons for odd shaped ellipsoids include incorrect atom assignments, atomic disorder, incorrect space group assignment or poor data quality.

3.	Again, the atoms should be of roughly similar size and shape in similar environments. If you have incorrect atom assignments at this stage. Olex2 will might display tetraheders instead of the expected ellisoids. Such atoms have become `non-positive definite` and are in reality heavier (i.e. O not C). Very large ellipsoids indicate the atom type should be lighter (i.e. C not O). In the illustration: atoms 3 are correctly assigned atom types with similar sized spheres, 1 is non-positive definite (in this case too light atom type) and 2 is a large ellipsoid, i.e. assigned as too heavy atom type.

	![Incorrect Ellipsoids](/images/incorrect_ellipsoids.png)

	>OLEX2 It is generally good practice to re-set the atoms to be isotropic, click on I_ISOT in Toolbox Work at the top right. Select the relevant atoms and change the atom type in `@Toolbox Work`. Click on Refine, make sure your structure looks reasonable then click on   on Toolbox Work at the top right to re-refine in the anisotropic model.

	![Incorrect Ellipsoids](/images/incorrect_ellipsoids.png)

At this stage using olex2.refine you should have R1 ~ 7-8 %, wR2 ~ 20-21%, Difference map max ~0.7 e-3, min ~ -0.4 e-3.

## Add Hyrdogen Atoms

1.	The next stage is to add hydrogen atoms to your structure. In Toolbox Work click on Add H in the top right hand corner (or type `CODE hadd` in the console). Olex2 automatically adds hydrogen atoms and includes these in the subsequent refinement.

	>CRYST The hydrogen atoms are automatically added using a riding model with appropriate AFIX instructions; these are normally expressed as geometrical constraints on the X-H distances and/or H-X-(X neighbour(s)) angles depending on the pivot atom type and isotropic temperature factors being a fraction of that of the pivot atom. From X-ray data hydrogen atoms are only refined isotropically as there are insufficient data to refine them anisotropically. Make the Q-peaks visible again by clicking $$$$ in Toolbox Work (or CTRL+Q).

2.	In Toolbox Work clicking on the H square cycles through show H / show H with H-bonding interactions / hide H (alternatively use CTRL+H). Stop at show H with hydrogen bonding interactions.

	>OLEX2 Hydrogen bonding interactions are shown as red dashed lines between a hydrogen atom and the acceptor atom. 

3.	Check that there have been no extra hydrogen atoms generated. If there are any, delete all hydrogen atoms on the parent atom in question as the AFIX instruction will be incorrect. Select atoms by clicking on them with the left hand mouse button and then press DELETE. Refine the structure.
	
	>OLEX2 If you select some hydrogen atoms and use the Delete All H button I_KILLH  or type `CODE kill $H` in the command-line, only the selected atoms will be deleted. 
	
>The hydrogen atoms are automatically added using a riding model with appropriate AFIX instructions; these are normally expressed as geometrical constraints on the X-H distances and/or H-X-(X neighbour(s)) angles depending on the pivot atom type and isotropic temperature factors being a fraction of that of the pivot atom. From X-ray data hydrogen atoms are only refined isotropically as there are insufficient data to refine them anisotropically. Make the Q-peaks visible again by clicking the Q icon I_Q in Toolbox Work (or CTRL+Q).

4.	In Toolbox Work clicking on the H square cycles through show H / show H with H-bonding interactions / hide H (alternatively use CTRL+H). Stop at show H with hydrogen bonding interactions.
	
	>OLEX2 Hydrogen bonding interactions are shown as red dashed lines between a hydrogen atom and the acceptor atom.

5.	Repeat hydrogen atom addition as before. This time Olex2 will only add the missing hydrogen atoms. If for any reason, they are still incorrect, it will be necessary to add them manually. Similarly if hydrogen atoms were missing after Add H. 

6.	The first assignment of hydrogen atom positions is not always fully optimised, particularly for less well defined groups such as 'OH. If there are Q-peaks close to oxygen atoms that are not where the hydrogen is currently located, the hydrogen position may need adjusting. The image shows an incorrectly positioned hydrogen atom 1 which should be located at the Q-peak 2.

7.	To optimise the hydrogen atom positions if necessary there are two options: multiple refinement cycles using Refine may see the hydrogen atom(s) rotate onto the Q-peak (sometimes updating the weighting scheme, see below, helps the refinement escape the false minimum and to rotate the H-atom(s) into the correct position), alternatively select a hydrogen atom and then in Toolbox Work choose Fit option from the Select group or atom(s) and then ' tool. Once in Fit mode, holding the SHIFT key down and left mouse button whilst dragging the relevant hydrogen atom allows you to move the hydrogen atom into the desired position. Press ESC when finished. Repeat if more than one atoms needs to be relocated.

8.	Check that there have been no extra hydrogen atoms generated. If there are any, delete all hydrogen atoms on the parent atom in question as the AFIX instruction will be incorrect. Select atoms by clicking on them with the left hand mouse button and then press DELETE. Refine the structure.
	
	>OLEX2 Note that if you select some hydrogen atoms and use the Delete All H button or type `CODE kill $H` in the command-line, only the selected atoms will be deleted.

	>OLEX2 When in the Fit mode it is possible to rotate the structure to see if the relocated hydrogen atom is now on the Q-peak. Remove your finger from the mouse and SHIFT key, hold the LEFT MOUSE button down and move the mouse.

9.	Refine the structure.

	>CRYST The refinement engine will automatically adjust the position to maintain the appropriate geometric constraints dictated by the AFIX instruction.

10.	Rotate the structure and examine the hydrogen positions to make sure that the structure looks sensible, if required adjustments to the hydrogen atom positions. 

	![Incorrectly Positioned Hydrogen](/images/Incorrectly_positioned_hydrogen.png)

11.	It is now necessary to adjust the weighting scheme. Under the refinement options, there is a Weights option. Tick the box next to Auto Update Weights. Click Refine and repeat until the weights are no longer changing.

	>CRYST Applying a weighting scheme will give a flat analysis of variance and GooF close to 1, it should not be included in the refinement until the structure is essentially complete, refinement should continue until the values have converged or nearly converged. olex2.refine will stop the refinement when the refinement has converged which may not involve the number of the requested cycles, ShelXL will complete the number of requested cycles irrespective of whether the refinement has converged.

12.	The structure is now solved and refined.

At this stage R1 will be between 4% and 5%, wR2 around 10% and the largest peak will be about 0.3.
