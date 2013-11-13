# Model Building

## Q-Peaks Options
The Q-peaks are displayed as brown spheres, the transparency of which is related to their relative intensity, in other words the peaks that appear darkest (and therefore most obvious) on the screen have the greatest relative intensity while the lighter, less obvious peaks have the lowest intensity. They are scaled by the peak height of the largest peak. If that is a very large peak (a heavy element), then all other peaks will appear very faint. Once the heavy peaks have been assigned, the next-highest peak will be lower and ALL peaks will appear more clearly.

### Displaying/Hiding/Deleting

- CTRL+Q toggles between no Q-peaks, show isolated Q-peaks, and show Q-peaks with bonds. Depending on what you are looking for, you will use this command a lot during a structure determination. The I_Q icon under `@Work|Toolbox-Work` has exactly the same effect.
- Type `CODE kill $Q` in the command-line to delete all of the Q-peaks. There is really never a real reason to do this!

### Changing the number of Q-peaks displayed

- Use the mouse wheel function
- Under `@Info|Electron-Density-Peaks` or `@Work|Toolbox-Work|Peaks` the slider bar by **peaks** sets the number of peaks displayed on the screen. When the bar is at the centre, 100% of the peaks are displayed: sliding to the left hides the weakest peaks first while sliding to the right hides the strongest peaks first.
- Under `@Work|Refine` change the number of residual peaks, click £Refine£ to re-calculate the number of peaks.
- Type `CODE refine 4 5`, which will refine with 4 cycles of refinement and return 5 peaks.

When a large number of atoms have not been located, it is advisable to use a larger number of residual peaks. As the refinement proceeds reducing the number can make it easy to see where the highest peaks are located.

### Changing a Q-peak to an atom type

- Select one or more Q-peaks and click on the desired atom type under `@Work|Toolbox-Work`.
- Select the atom type first (with nothing selected) and then click on the Q-Peaks you wish to assign in turn.
- Select one or more Q-peaks and right click on them, under **Type** select the desired atom type.
- Select one or more Q-peaks and then type `CODE name O` to make them into oxygen atoms. 

### Displaying Q-peak intensity labels

- Select Q-Peak intensities from `@Work|Toolbox-Work|Labels`. 

### Displaying negative Q-peaks

- Using ShelXL, under `@Work|Refine|Refinement-Settings-Extra` change FMAP 2 to -2. Negative Q-peaks are displayed as purple spheres.
- In general, type `CODE calcfourier -diff -i` to display negative Q-peaks.

### Adjusting the visual appearance of Q-peaks

- The relative scaling of the Q-Peak transparency can be adjusted under `@Info|Electron-Density-Peaks` using the Transparency slider. 

## Atom Manipulations

###Changing atom types

- RIGHT CLICK on an atom (or select multiple atoms and right click on one). Under **Type**, select the desired atom type.
- Select an atom or group of atoms, under `@Work|Toolbox-Work` click on the desired atom type.
- Select atoms(s) and use the name command, *e.g.* type `CODE name O` to make them into oxygen atoms.

### Selecting atoms or groups of atoms
Atom selections are very important in Olex2. When you need to address specific atoms (because you want to change their atom type, involve them in some restraints or want to delete them, for example), you do this by selecting them. When you work with Olex2, you never need to know the name of an atom, but you must know how to select them! Here are a few points about selections:

- Selected atoms turn `green'
- Add to the current selection by clicking atoms
- Take atoms out of a selection by clicking on them again
- Double-click on a whole molecule to select it
- CTRL+I - inverts the selection
- CTRL+A - selects everything,
- DELETE - deletes selected atoms.
- ESC - deselects all atoms

For very many operations in Olex2 the following statement is true: If you have a selection, the operation will act on this selection. If you don not have a selection, the operation will be applied to ALL atoms. For example, if you have two isotropic atoms selected and type `CODE anis`, only these two atoms will be made anisotropic. If you have nothing selected and do the same, ALL atoms will become anisotropic.
Olex2 offers several options for selecting atoms individually:

- Left click with the mouse on an atom or multiple atoms in turn to select one or more atoms.
- Under `@Work|Select`:
    - **Exclusive** or **Additive** enable either C, H, N, O or all atoms to be selected either individually or additively.
    - **Selection**: the current atom selection can be Inverted, Deselected, Deleted or Previous returns to the previous atom selection.
    - **Select atoms where $U_{iso}$**... is greater than (>), less than (<) or equal (=) to a user-defined value. Click on **Select** to select defined atoms.
    - **Select Rings**: C6, C5N, C5 or C5O options are available. Type in the ring composition to be selected.
    - More options are available from `CODE help sel`.

### Naming Atoms
Olex2 offers a couple of useful features for naming, specifically; automatically adjusting hydrogen labelling if the parent atom name is changed and name matching for equivalent fragments if Z' > 1. These options are listed under `@Work|Naming`.
To name atoms enter the **Start** number, change the **Suffix** and **Type** if needed. Click on £Name£, then use the left mouse button to click on the atoms in the required order, they will be labelled sequentially. Press ESC when finished.

- To restart from a number select the appropriate number and click on £Name£ again. A number can only be used once in association with a particular atom type, if one appears more than once the two atoms with the same name will be labelled in red.
- **Automatic Hydrogen Naming** - if ticked, the hydrogen atom labels will automatically update to reflect changes in the parent atom name. Click £Refine£ for changes to the hydrogen atom labels to take effect (or type `CODE FixHL` in the command-line).
- **Equivalent Fragments (Z'>1)** - name matching for equivalent fragments. Select one atom from the correctly named fragment then one from the fragment to match the names. Add a **Suffix** letter and click on **Equivalent Fragments (Z' > 1)**. The second fragment will automatically be relabelled.

As with many options, name matching for equivalent fragments can be done in the command-line. After selecting the atoms in order, type `CODE match sel -n=suffix`, where suffix is the number required. Without selecting atoms, sel can be replaced by the two atom names in order, separated by a space. Two alternative naming approaches can be achieved using the command-line only:

- to replace the first number e.g. C101 becomes C201, and type `CODE match sel -n=$suffix` where suffix is the number required;
- to replace the last character type `CODE match sel -n=-suffix`. If no atoms are selected clicking on **Equivalent Fragments (Z'>1)** will show how the fragments will be matched. Type `CODE match -u` to return to the non-matched view.

## Sorting atoms in the .ins file
The atoms can be sorted in the .ins file under `@Work|Sorting` by seleting the preferred sort order (Suffix, Z vlaue etc) and clicking £Refine£. Click £Report£ to view the sorted atoms. Click on the info icon I_INFO in the beginning of the line to learn about more complicated sorting options (which can be accessed using the command-line only).

## Hydrogen Atoms

### Displaying hydrogen atoms
- CTRL+H toggles the hydrogen atoms through show H, show H with H-bonding interactions and hide H.
- Clicking on the I_H icon under `@Work|Toolbox-Work` achieves the same result.

### Adding hydrogen atoms
Hydrogen atoms can be added in a number of different ways within Olex2 either by locating them on Q-peaks or using AFIX/HFIX instructions to constrain their position automatically or manually.

#### On Q-peaks with no AFIX/HFIX instructions.
- Q-peaks can be turned into H using the H button under `@Work|Toolbox-Work` or by right-clicking on the peak and then selecting **Type|H**.
- Alternatively delete all Q-peaks which are not likely to be hydrogen atoms then click on the I_QH icon. All of the Q-peaks on the screen will be changed to hydrogen atoms.

#### Using AFIX/HFIX instructions: 
Automatic hydrogen atom positioning - Under `@Work|Toolbox-Work` is the **Add H** option after which Olex2 automatically locates and positions the hydrogen atoms and carries out some refinement cycles. 

- It is necessary to check whether the hydrogen atoms are in sensible positions, particularly for less well defined terminal groups such as -CH3 or -OH. If there appears to be Q-peaks that would be better positions for the hydrogen atoms, it may be necessary to carry out multiple refinement cycles or use `@Work|Toolbox-Work|Select-Group-or-atom(s)` and then **Split** or **Move** with SHIFT KEY to optimise the relevant positions.
- If you would like to manually add hydrogen atoms - under `@Tools|Hydrogen-Atoms` there are various options provided for adding hydrogen atoms:

The icons illustrate some commonly used hydrogen types, click on one to enter that mode (the HFIX instruction type will be displayed in the orange mode bar) then click on the atoms you wish to apply the HFIX to. It is possible to switch between modes by clicking on another icon. Press ESC to exit the mode.

- If the HFIX is inappropriate for an atom, an error message will appear in the console and hydrogen atoms will not be added. Otherwise, H atoms will appear on the screen. For more information HFIX instructions see the ShelXL manual.
- The appropriate HFIX can be typed into the box, then click on HFIX and select the atoms to apply the HFIX to. To change mode press ESC, change the HFIX and re-enter the mode.
- **Add Hydrogen** automatically adds the remaining hydrogen atoms but does not automatically undergo any cycles of refinement.
- The hydrogen atom labels can be displayed (**H Labels**), hidden (**No H Labels**) or the HFIX can be displayed (**Show AFIX**).

## Deleting Hydrogen Atoms

- Typing `CODE kill $H` in the command-line will delete all or selected hydrogen atoms.
- Click on the I_H icon under `@Work|Toolbox Work` will delete selected H.
- Select one or more hydrogen atom(s) and press DELETE.

>CRYST The hydrogen atoms are automatically added using a riding model with appropriate AFIX instructions. These are normally expressed as geometrical constraints on the X-H distances and/or H-X-(X neighbour(s)) angles depending on the pivot atom type and isotropic temperature factors being a fraction of that of the pivot atom. From X-ray data, hydrogen atoms are only refined isotropically as there are insufficient data to refine them anisotropically. Make the Q-peaks visible again by clicking I_Q in `@Toolbox-Work` (or **CTRL+Q**).
