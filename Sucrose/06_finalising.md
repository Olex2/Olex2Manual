#Finalising the Structure

Your structure is now finished and completed from the refinement point of view. If the structure is to be included in a thesis or scientific publication, then you probably need to come up with a naming scheme for its atoms. If it is not your own structure, it is worth liaising with the author to agree on a naming scheme -- structures are often part of a series of structures which should have consistent naming throughout.

1. The next stage is to label your structure to a sensible naming scheme \index{naming scheme}. In `@Toolbox-Work|Labels` select **Labels On/Off** until the atom labels are displayed (alternatively press **F3**). Hide the Q-peaks either using the **Q** square in `@Toolbox-Work` or use CTRL+Q.

	>CRYST Generally,  it is ideal to name atoms in order e.g. all of the carbon atoms around a benzene ring 1-6 with substituents numbered 7 onwards down a chain, then all of the oxygen atoms etc. Alternatively, simply number atoms in order irrespective of atom type. If there are a series of similar structures it is sensible to use the same numbering scheme so that comparisons between bond lengths can be easily made.

2.	Click on the `@Naming` header tab which is one of the options further down the GUI panel below `@Toolbox-Work`.
3.	Choose a starting number for your naming sequence, usually 1, and type it into the **Start** box. Click on **Name** on the right hand side of the Naming box. An orange box appears to tell you that you are now in mode Name.
4.	Now with the LEFT MOUSE button click on the atoms in a sensible order to name them sequentially from your chosen start number. The atom labels of the atoms that have been clicked on change from green to black.
5.	When finished press ESC. If you are labelling by atom types repeat the processes until all atoms are numbered. 

	>CRYST A number should only be used once in association with a particular atom type. If one appears more than once, the two atoms with the same name will be labelled in red. 

	By default, hydrogen atoms automatically take their name from the atom to which they are attached, if `@Work|Naming|Automatic-Hydrogen-Naming` is ticked, any changes to atom labels are reflected in changes to the attached hydrogen atoms (changes take place after the refinement). If not, the hydrogen atoms may need relabeling separately, use `CODE FixHL` to give you a good start -- this will rename H-atoms to fit a commonly acceptable scheme.
6.	Sort the atoms in the *.ins* file. Go to `@Work|Sorting`, which is one of the header options further down the GUI panel. Click on Mass & Label. Click on @@Refine@@ to update the model files.
7.	Identify and tabulate intermolecular interactions if present. 
8.	Generate a CIF and report for publication, and validate the CIF. 
9.	Produce relevant Figures.

## Structures to Try Next
The next structure you should try now is sucrose (again). Despite the seemingly large number of steps required to obtain the finished structure, it's actually not all that hard. The key here is repetition: we normally recommend solving and refining sucrose several times before proceeding to another structure. 
Having followed this procedure through it should be possible to solve the other sample structures. Most of these are relatively easy, but the disorder in structure `183' is a real challenge.
