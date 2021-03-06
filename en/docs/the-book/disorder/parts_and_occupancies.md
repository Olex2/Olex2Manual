# PARTs and Occupancy
The use of **PARTs** and **occupancy** are often linked.
The *PART number* \index{Part number} is used to define which atoms are considered to be bonded to each other. Atoms in PART 0 bond to everything within bonding distance, while those in PARTs other than 0 bond to all atoms in PART 0 and the same PART number as them.  For example, if some atoms are modelled in PARTs 1 and 2, the atoms in PART 0 within bonding distance, bond to atoms in PART 1 and 2. However, the atoms in PART 1 only bond to those in PART 0 and 1, not 2 (likewise for those in PART 2).

![50 The use of PARTs on a fragment to define bonding. The atoms in PART 0 within bonding distance, bond to atoms in PART 1 and 2. However, the atoms in PART 1 only bond to those in PART 0 and 1, not 2 (likewise for those in PART 2)](../part labelled.png)

The *occupancy* \index{occupancy} is used to define the fraction of an atom modelled in a particular location. In the image above, it would not be possible for atoms in PARTs 1 and 2 to be present in a particular asymmetric unit at the same time or the molecule would be very odd. The disorder model indicates that in some asymmetric units the molecule is in the orientation of PART 1 and in others it is in the orientation of PART 2. Therefore the total occupancy of the two sites cannot exceed 1 but in this case to have a complete molecule it must equal 1. In this case the occupancy of PART 1 was 0.8 and PART 2 was 0.2.

## Assigning PARTs
If more than one position of an atom or fragment of a molecule is being modelled in the unit cell, it is necessary to put the disordered atoms into separate PARTs. Otherwise, bonds appear between the disordered PARTs and only one option can be present at any point in a cell, at any one time.

- RIGHT CLICK on an atom and select the desired PART from the `@context menu|PART`.
- Using the GUI panel select the atoms to be put into a PART. In `@Tools|Disorder|Assign-selection-to-PART`, type the required PART number and click on the link.
- Select some atoms and type `CODE PART number` in the command-line where `number' is the PART number. Using the command-line you can also provide a second numerical value to the PART command - the selected atom's occupancy.

## Displaying PART Information
Displaying PART numbers - under `@Work|Toolbox-Work|Labels` either select PARTs from the drop down menu or click on PARTs. Alternatively, use `CODE showp X`, where X is a space separated list of PARTs, in the command-line.
Displaying atoms in particular PARTs - under both `@Work|Toolbox-Work|Show-PART` and `@Tools|Disorder|Show PART` are the options to display all atoms assigned to specific PARTs in combination e.g. 0 + 1 or 0 + 2 or all PARTs.
All atoms in PART 0 are normally 100% occupied. In other words they are at that position in every asymmetric unit, while those in other PARTs are not present in every asymmetric unit hence it is normally desirable to see things in combination with atoms in PART 0. This can be useful to check that each section of modelled disorder makes chemical and crystallographic sense.

## Assigning Occupancies
When refining occupancies, the thermal parameters of the atoms should be refined isotropically. If the sum of the occupancies of a pair of atoms is required to total one, their $U_{iso}$ values should be linked using EADP but allowed to refine until the occupancies are fixed. The reason for this is that strong correlations exist between occupancies and thermal parameters and not linking $U_{iso}$ while refining the occupancies may lead to incorrect occupancies. Very small occupancies should be examined with caution.

## Free Variables \index{free variables}
Free variables provide a simple and yet elegant mechanism to implement a number of linear constraints and restraints. They are found in the .ins file under an FVAR instruction. The first number on the FVAR line corresponds to the overall scale factor for the data and should not be edited. Subsequent numbers can be used as a link to parameters that are being refined e.g. if the occupancy of two atoms needs to be linked or the isotropic displacement parameter.
For example:

        FVAR 0.355153 0.75
        PART 1
        C1 C 0.36499 0.36561 0.32094 21.00000 0.03239
        PART 0
        PART 2
        C1a C 0.28806 0.36415 0.33164 -21.00000 0.0500
        PART 0
        PART 1
        C2 C 0.30722 0.29774 0.21191 21.00000 0.03333
        PART 0
        PART 2
        C2a C 0.39521 0.31781 0.21763 -21.00000 0.05000

`21.000` means 1 x free variable 2 (i.e. the 2nd number on the FVAR line, before refinement here 0.75). `-21.000` means 1 - (1 x free variable 2), in other words the occupancy of the two PARTs adds to 1.
`PART 1 / 2` means that the atoms have been grouped into different PARTS only one of which would be present at a position in the crystal structure at any one time. PART 0 is for atoms with one position.

## Change the Occupancy of an Atom or Group
Right click on the atom -- @@Chemical Occupancy@@ \index{chemical occupancy} will provide these options:

- *Select* a specific occupancy value e.g. $1/2$.
- *Fix* the occupancy to its current refined value. This is only applicable if the atom occupancy has been refining freely or associated with a free variable (FVAR in the .ins file).
- To refine the occupancy, select *Free*. This refines the occupancy freely but does not associate it with a free variable.
- Use `CODE fix` and `CODE free` in the command-line. For example, `CODE fix occu 1` fixes the occupancy of selected (or ALL atoms) to 1; `CODE free occu` will make occupancy of selected (or ALL) `refineable'.

## Linking Atom Occupancies
Selecting `@Tools|Disorder|Link-Selected-Occupancies` will link the occupancies of the two selected atoms to a free variable and set their sum to equal 1. Subsequent selections will be linked to another free variable.
The free variable will be linked to a number in the FVAR instruction at the top of the .ins file, `21` links to the second FVAR number, 31 links to the third FVAR number etc. These number are then refined. Essentially, `21` means 1 x FVAR 2, while -21 means 1-(1 x FVAR 2)] i.e. if two atoms have occupancies of `21` and `-21` respectively the sum of their occupancies will equal one fully occupied atom.
Sometimes it quicker and easier to perform this using the command-line:

- Using the part occupancy command `CODE PART`, for example `CODE PART 1 21` or `CODE PART 2 -21`. In the case when new PARTs need to be created, one can select the atoms of different PARTs sequentially and issue `CODE PART -p=N -lo` command to create N new PARTs and link their occupancy. In the case when N is greater than 2, the occupancies will be linked through a restraint (SUMP) \index{restraint} represented by a linear equation, rather than by a constraint.
- Using the `CODE Fvar variable times` command, where *times* is the FVAR multiplier, typically 1. For example `CODE fvar 2 1` or `CODE fvar -2 1`.

## Displaying Occupancy Values \index{occupancy}
Under `@Work|Toolbox-Work|Labels` either select Crystallographic Occupancy or Chemical Occupancy from the drop down menu. Crystallographic occupancy - if an atom is on a symmetry element, then its crystallographic occupancy is no longer 1, even though chemically it is a fully occupied atom in that position. The chemical occupancy hides this complexity. If that number says 0.5, then that means there is half an atom in that position.

## Splitting Atoms
If an atom or group of atoms is associated with disorder, it can be useful to split the atom in order to model it over more than one position. Sometimes it is desirable to do this in association with a restraint, constraint or by linking the occupancies of the two PARTs. There are a number of options to achieve this within Olex2:

### `@Work|Toolbox-Work|Split-atoms-you-click-next-with-...`

- *No restraint* splits atoms with no restraints or constraints, putting them into two PARTs and associating the occupancy with a free variable. Press ESC when finished.
- *EADP* or *ISOR* or *SIMU* splits the atoms, applying either an EADP constraint or ISOR or SIMU restraint depending on what option is selected. Press ESC when finished. (See restraints/constraints) for more detail of these restraints.

>OLEX2 If you click on more than one atom to split it, it will be associated with the same free variable unless you press ESC and reopen the mode, in which case the occupancy will be linked to a new free variable. To edit the standard deviations associated with ISOR or SIMU click on the relevant atoms to select them, click on the open .ins icon I_EDIT and edit the .ins file directly. When atoms are split, Olex2 will automatically make them isotropic for the occupancies to be refined.

### `@Toolbox Work|Select-group-or-atom(s)-and-then...`
*Split* will split the pre-selected atom or group of atoms with no restraint: setting one atom to PART 1 with the occupancy linked to a free variable and the other to PART 2 with the occupancy linked to 1 free variable. Subsequently, holding down the SHIFT+LEFT MOUSE button and moving the mouse allows the new atom(s) to be moved e.g. onto a Q-peak. Press ESC when finished.

### Moving Incorrectly Located Atoms
It may be apparent that an atom would be better located on a different Q-peak rather than the initially assigned position. This can be useful when Add H is used for less well defined hydrogen atoms e.g. OH. Often multiple refinement cycles will lead to the hydrogen atom moving onto the Q-peak but the following may be a quicker method as only small shifts occur in each cycle of refinement.

### `@Toolbox-Work|Select-group-or-atom(s)-and-then...`

- *Fit* allows the pre-selected atoms to be moved by holding down the SHIFT KEY + LEFT MOUSE button and moving the mouse will move the group. Press ESC when finished.

## Splitting and Moving Atoms

### `@Toolbox-Work|Select-group-or-atom(s)-and-then...`

- *Split or Move with Shift key*: once in this mode any atoms that are clicked on will be split unless the Shift key is held down in which case the atoms can be moved by holding the LEFT MOUSE button down and moving the mouse. Press ESC when finished.
Releasing the SHIFT in these modes allows the structure to be rotated and zoomed to check the positions. These positions do not have to be perfect, just relatively close as the structure will be refined afterwards. In Split or Move with SHIFT key be careful not to click on an atom if you are changing the view or it will split. If extra split atoms are generated in any mode. Press ESC to get out of the mode. Using the left mouse button click on the new generated atom(s) to select it, press delete and the atom(s) will disappear and change occupancy of the original atoms back to 1 and reset its PART to 0.
