#Understanding the Syntax
**Selection**: If one or more atoms are selected on the screen, then any command that acts on a selection will apply to the selected atoms only. If there is no selection, it will apply to all atoms. Instead of making a selection on the screen, a list of atom names can also be supplied. If a command has been successful, the selection will disappear. (Although there are a couple of exceptions to this rule).

**Mode**: If Olex2 is in a Mode, the chosen action will be applied to all subsequently clicked atoms. The mouse pointer will change from the default arrow symbol to signify that Olex2 is in a mode. To get out of a mode, simply press the ESC key.
Syntax used in this document:

**{a, b, c}**: choice of a, b or c. For example: fix {occu, xyz, Uiso} [atoms] means 'fix occu [atoms]', 'fix xyz [atoms]', 'fix Uiso [atoms]'.

**[val=2]**: optional parameter. This parameter is not required for the command to work, and if it is not supplied, the default value will be used.

**-k**: This is an option switch.

**i**: Italic characters are used for variables.

**[atoms]** means an optional list of atoms. Any atoms that are selected will automatically be present in this list. If there are no selected atoms, all atoms will be in this list. Alternatively, the atom names of the atoms that should appear in this list can be typed by hand. 

**atoms** means a compulsory list of atoms. Any atoms that are selected will automatically be present in this list. Alternatively, the atom names of the atoms that should appear in this list can be typed by hand.

**Capital Letters** are used for commands that will directly affect the structure model in the refinement. These commands will become part of the structure model and will appear in the ShelX input file. Please note that these commands can be typed either in upper or lower case.

**Example Commands** are represented in this format: 'CODE refine 4 20' and can be typed exactly as they are given. In this example, the structure will be refined with 4 refinement cycles and 20 electron density peaks will be returned from the electron density map integration.
