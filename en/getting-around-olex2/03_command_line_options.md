# Command-Line Options
> Olex2's powerful command line

As previously mentioned, Olex2 offers the opportunity to use a command-line approach if preferred. Although this manual focuses predominantly on the use of the GUI panel and graphics screen, it is worth remembering that the command-line offers a number of additional options and functionality. There are some command-line commands that are extremely useful for routine work, especially when you consider that the UP/DOWN arrow keys browse through your command-line history.
Frequently used command-line options

|Command  | Description|
|-------- | ----------------------------------------------------------------|
|refine   |Refines the structure. The number of cycles and peaks can be set e.g. `CODE refine 4 5` will ask for 4 cycles and return five peaks.|
|name     | Change the atom types of the selected atoms|
|compaq   | This will assemble a fragmented structure. Also `CODE compaq -a`|
|fuse     | Show the asymmetric unit only|
|grow     | Generate all missing symmetry equivalent atoms|
|reap     | Open a new structure|
|lines #  | Change the number of lines of text shown in the main graphics window to # where # is a number. `CODE lines -1`| will show all lines.|

The command-line is an enormously powerful tool in Olex2. There are only a few commands that are frequently used, but they are used again and again and it is well worth your time to get to know these.
Many -- if not most -- SHELX and/or XP commands can be used directly in Olex2. If you want the bond distances to be the same, simply select the two distances and type `CODE SADI`. If you want them to be the same with a very high weight, type `CODE SADI 0.001`. The same goes for almost all other SHELX commands. If you type such a command, and the atoms become deselected, then you know that it has worked. If you want to convince yourself that it has worked, click on one of the atoms you have modified and then type `CODE editatom`. You will find your instructions in the window that will pop up.

>OLEX2 You can also use the command-line to enter any general instructions. For example, if you want to add a remark to the instructions, you can type `CODE addins REM Atoms sel() are dodgy`. The `code sel()` bit will be expanded to the currently selected atom names. A shortcut for this is `CODE / MyInstruction` - i.e. a forward-slash followed by a space and then your instruction.
