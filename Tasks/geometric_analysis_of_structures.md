# Geometric Analysis of Structures

## Overlaying Structures
It is frequently useful to be able to overlay structures either to compare the orientation of common fragments in the same structure (e.g. when Z'>1) or between two different structures (e.g. a different polymorph, structures before and after a phase transition or spin-crossover). Overlaying the structures makes it much simpler to identify differences.

> OLEX2 Before trying to overlay structures delete all Q-peaks, e.g. type `CODE ill $Q`.

### Automatically overlaying fragments in the same structure
In situations where there are two fragments in the structure with the same connectivity, under `@Tools|Overlay` click on Match All Fragments. Olex2 will overlay the structures on the screen and calculates a root mean square distance (RMSD) deviation for overlay of the fragments which is displayed on the graphics screen with and without inversion, alternatively type `CODE match`. To return to unmatched fragments click on UnMatch or type `CODE fuse`.

> OLEX2 The automatic matching does not always work if there is disorder in a molecule (try matching selected atoms) or it is of high symmetry. In the case of a high symmetry example, try hiding hydrogen atoms (Ctrl+H) or manually change an atom type to break the symmetry, this is because the graph matching algorithm does not use pattern recognition for the optimisation, and high symmetry can introduce a large number of possible permutations, e.g. a CH3 group increases the number of permutations by 6.

### Matching selected atoms in the same structure
If the automatic matching did not work or different atoms are required to be matched, it is possible to match selected atoms.
 
Select 3 atoms in the first fragment and then 3 atoms in the second fragment in the order to be matched and under `@Tools|Overlay` select Match Selected Atoms. To return to the unmatched structure, click on UnMatch or type `CODE fuse`.

`@Tools|Overlay|Mode Match` This mode enables interactive matching by a maximum of three pairs of atoms. The first pair of atoms are superimposed, the second one causes the rotation to minimize the distance between the atoms of the second pair, the third pair causes rotation around the line formed by the first and second pair to minimize the difference between the atoms of the third pair. Hit ESC to exit this mode. To return to the unmatched structures click on UnMatch or type `CODE fuse`.

### Overlaying molecules from different structures
Click on `@Tools|Overlay|Overlay Structure` to overlay a second structure. The two structures now appear on the right and left hand side of the graphics screen and the user-selected matching mode is automatically set up.

A maximum of three pairs of atoms from the two structures can be selected. The first pair of atoms are superimposed, the second one causes the rotation to minimize the distance between the atoms of the second pair, the third pair causes rotation around the line formed by the first and second pair to minimize the difference between the atoms of the third pair. Type ESC to exit this mode.

To remove the overlaid structure, select Remove Overlay from `@Tools|Overlay`.
Alternatively after clicking on `@Tools|Overlay|Overlay Structure`, press ESC and Match All Fragments, UnMatch or Match Selected Atoms can be used.

## Calculating Geometric Parameters
There are a variety of options to determine geometric parameters relating to the structure.

### Measuring bond distances

- Hovering over a bond with the mouse will display the bond length of that particular bond.
- Right click on the bond and the bond length will be displayed at the top.
- Select two atoms, then under `@View|Geometry` click on either Distance and Angles (of selection) or Distance and Angles with esd (of selection) to obtain the distance with or without an esd (the latter requires the use of `@View|Geometry|Refine` and save esd info first.)
- Right click over an atom, under BANG is a list of all bond lengths or distances to nearby Q-peaks.
- Select one/two atoms and type `CODE bang` to see associated geometric parameters (you can also supply atom names).
- Under Work click on Report to generate an html report containing the bond lengths in one of the tables.

### Measuring bond angles

- Right click on the central atom, under BANG the bond angle will be displayed.
- Select three atoms, then under `@View|Geometry` click on either Distance and Angles (of selection) or Distance and Angles with esd (of selection) to obtain the distance with or without an esd (the latter requires the use of `@View|Geometry|Refine` and save esd info first.)
- Select the central atom and type `CODE ang sel` to see associated geometric parameters (alternatively replace sel by an atom name).
- Under Work click on Report to generate an html report containing the bond lengths in one of the tables.

### Measuring torsion angles

- Right click on the central bond, under TANG any torsion angles associated with the bond will be displayed.
- Select four atoms, then under `@View|Geometry` click on either Distance and Angles (of selection) or Distance and Angles with esd (of selection) to obtain the distance with or without an esd respectively (the latter requires the use of `@View|Geometry|Refine` and save esd info first).
- To tabulate the torsion angles:

    - Click on the pencil icon I_EDIT to open the .ins file header.
    - Type CONF on a separate line somewhere below the UNIT line and refine.
    - Under Work click on Report to generate an html report containing the bond lengths in one of the tables.

## Analysing Interactions

### Hydrogen bonding
- Use Olex2's htab command to locate the hydrogen bonds; (use help htab to find more information). Type `CODE htab -g` to automatically calculate and generate the resulting hydrogen bonded structure. To return to just viewing the asymmetric unit type `CODE fuse` (note that Olex2 will display HTABs disregarding their validity). 

### pi-pi interactions
To analyse all pi-pi interactions associated with the asymmetric unit automatically type `CODE pipi -g`. Type fuse to return to the asymmetric unit. This is also available under `@View|Geometry|Analyse-pi-pi-Interactions`.

#### Locate pi-pi interactions manually

- If the potential pi-pi interaction is not within the asymmetric unit, grow the structure to display both parts of the interaction.
- Select all of the atoms of the first ring under `@View|Geometry` click on Mean Plane (of active selection). A plane will be displayed in the ring and a centroid generated, all symmetry related planes will automatically be added to any other molecules on the screen.
- Click on the two centroids under `@View|Geometry` click on either Distance and Angles (of selection) or Distance and Angles with esd (of selection), to obtain the distance with or without an esd respectively (the latter requires the use of `@View|Geometry|Refine-and-save-esd-info` first).

### Calculating the mean plane of a selection
Select four or more atoms through which to calculate a plane. Click on `@View|Geometry|Mean-Plane` (of active selection)`.

### Calculating the deviation of atoms from a plane
Select the atoms to be in a plane and type `CODE mpln` to create the plane. Olex2 to will then print information regarding the plane. If more information regarding this plane is needed -- select it and any other object (atom, bond, plane etc) and type sel (esd) to get the required information.

### Calculating the angle between planes
Create the required planes and select them. In `@View|Geometry` click on either Distance and Angles (of selection) or Distance and Angles with esd (of selection), to obtain the distance with or without an esd respectively (the latter requires the use of `@View|Geometry|Refine-and-save-esd-info` first). Alternatively:

- Click on the pencil icon I_EDIT to display the header of the .ins file. On a line below the UNIT instruction type:
- `CODE MPLA ##` followed by the ## atom names in plane 1
- `CODE MPLA ##` followed by the ## atom names in plane 2.
- The .lst file will contain information on each plane plus the angle between adjacent planes in the list.

## Growing Structures
Olex2 offers a lot of flexibility over the manner in which structures are grown, the majority of these options are found under  `@Symmetry-Generation|Growing` under which there are three options: Grow, Mode Grow and Assemble.

- Completing structures where Z'>1
- Grow - Grow All will display all symmetry equivalent atoms/fragments to display the complete structure. (This is the same as `@View|Symmetry-Generation|Grow-All`).

If the asymmetric unit does not consist of a complete molecule i.e. Z' < 1, this mode will generate the rest of the structure. It is not uncommon for Z' to be some fraction of a molecule if it is sat on or around a special position in which case the rest of the molecule is generated by one or more symmetry operation(s), e.g. if a molecule is sat on an inversion centre only half of the molecule will be contained within the asu, the other half is generated by the inversion centre. For polymeric structures growth of 1 asu fragment will occur at each attachment point each time Grow All is clicked on.

- Shells will grow incomplete fragments atom by atom, shell-by-shell from the currently displayed image.
- Complete will generate all missing symmetry equivalent atoms of an already grown structure, independent of whether these are bound to the main fragment or not. In other words: all solvent molecules and counter-ion will be generated according to what is already shown.

### User-controlled growing modes
These options are similar to grow, but the commands are only executed after you click on an object. When you enter a growing mode, clickable 'growing bonds' will sprout from atoms where the kind of growing you have asked for is applicable. There are various options in `@View|Symmetry-Generation|Growing|Mode-Grow`:

- Short Contacts displays growable 'bonds' to those atoms where 'short interactions' exist, alternatively type `CODE mode grow -s`. Press ESC to exit the mode. If an atom is selected first only short interactions to that atom are shown.
- Contacts near selected atoms - select an atom or atoms and then select Selection to display growable bonds from those atoms, alter-natively type `CODE mode grow -r`. Press ESC to exit the mode.
- Contacts within the Van der Waals radii will show grow-able 'bonds' which are within the Van der Waals radii of the atoms. Alternatively type `CODE mode grow -v` ## where ## represents a user specified distance away from atoms. Press ESC to exit the mode. If an atom is selected first only short interactions to that atom are shown.
- Atom by atom structures can be grown by selecting Shells. Press ESC to exit the mode. If an atom is selected first only short interactions to that atom are shown.
- Relocating atoms in the asu - it may be desirable to select different atoms to form the asymmetric unit. To do this select Move and click on an alternative location. Press ESC to exit the mode. If an atom is selected first only options relating to that atom are displayed.
> In order to grow all of the displayed clickable growing options in growing modes, type `CODE grow -b`.

### Reassembling structures
This tool does not strictly belong to the 'growing' family of tools, but it is frequently used together with the growing tools as it allows you to re-arrange the asymmetric unit contents into a different configuration. There are various options under `@View|Symmetry-Generation|Growing|Assemble`:

- Broken Fragments: a structure may become 'broken' - parts that should be bonded are shown as separate fragments. This tool will bring them back together, alternatively type `CODE ompaq -a`. 
- Atom-to-Atom is very similar to the 'Broken Fragments' tool, but a different algorithm is used, or type `CODE compaq -c`. 
- Metal Last In this tool, metal ions are ignored while attempts to re-assemble the ligand are made, the metal ion is placed at the shortest possible distance, or type `CODE compaq -m`. 
- Q-Peaks This will move all electron density peaks as close to existing atoms as possible, or type `CODE compaq -q`.
- Growing structure to display hydrogen bonding interactions
    - To view the hydrogen bonding interaction associated with the asymmetric unit type `CODE htab -g`. To return to just viewing the asymmetric unit type fuse.
    - Displaying the asymmetric unit only:
    - `@Grow|Asymm.-Unit-(fuse)` Removes all symmetry equivalent atoms and displays the asymmetric unit. Alternatively type `CODE fuse`.

## Packing Structures
Olex2 offers a range of options for packing structures in different ways in order to understand interactions or the lattice packing. These are found under `View|Symmetry Generation|Packing`:

- Short Contacts adjusting the slider bar under Expand Short Contacts (Hydrogen Bonds) allows short contacts or hydrogen bonding interactions to be displayed, click on a grow-able link in order to grow a structure. Press ESC to exit this mode.
- Packing within a defined distance
    - Can be achieved by moving the slider bar below Pack Radius to display all molecules within a certain distance. Complete fragments are displayed.
    -In order to pack in relation to the unit cell axes adjust the limits on a, b and c and click on Pack to limits. 
    - Displaying the unit cell contents, click on Fill Unit Cell this will display all atoms within the unit cell. To complete fragments click on Complete Fragments.

## Chemical Tools
Under `Tools|Chemical Tools` you will find these useful general tools:

- CHN Analysis calculates the expected CHN composition on the basis of the unit cell content.
- Molecular Isotope Pattern
- Molecular Volume - calculates the Molecular surface area and Mo-lecular volume of the current model.
- Volume of Polyhedron around Selected Atom calculates the sum of the angles of the selected atom and the tetrahedron volume. This does not apply to terminal atoms.
- Wrapping Box. Right-click on it and then select hide to delete it.
