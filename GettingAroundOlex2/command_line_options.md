# Command-Line Options

As already mentioned Olex2 offers the opportunity to use a command-line approach if preferred instead of or in combination with the GUI panel and graphics screen. This manual focuses predominantly on the use of the GUI panel and graphics screen, with only a limited number of command-line commands mentioned. It is worth remembering that along with the option available through the GUI panel, the command-line offers a number of additional options and functionality. There are some command-line commands that are extremely useful for routine work, especially when you consider that the UP/DOWN arrow keys browse through your command-line history.

Frequently used command-line options
refine	Refines the structure. The number of cycles and peaks can be set: refine 4 5 will ask for four cycles and return 5 peaks.
name	Change the atom types of the selected atoms
compaq	This will assemble a fragmented structure. Also com-paq -a
fuse	Show the asymmetric unit only
grow	Generate all missing symmetry equivalent atoms
fuse	Show only the asymmetric unit
reap	Open a new structure
lines #	Change the number of lines of text shown in the main graphics window. lines -1 will show all lines.

The command-line is an enormously powerful tool in Olex2. There are only a few commands that are frequently used, but they are used again and again and it's well worth your time to get to know these.
Many -- if not most -- SHELX and/or XP commands can be used directly in Olex2. If you want the bond distances to be the same, simply select the two distances and type SADI. If you want them to be the same with a very high weight, type SADI 0.001. The same goes for almost all other SHELX commands. If you type such a command, and the atoms become deselected, then you know it has worked. If you want to convince yourself that it has worked, click on one of the atoms you have modified and then type editatom. You will find your instructions in the window that will pop up.
You can also use the command-line to enter general instructions for your refinement. Most commonly used instructions (e.g. OMIT etc) are recog-nised straight off. If you need something more complex, you can type addins MyInstruction and ‘MyInstruction' will be added. A shortcut for this is / MyInstruction -- i.e. a forward-slash followed by a space and then your instruction. You can also pass a list of the currently selected atoms by using the sel() construct: / SADI 0.001 sel() the sel() will be replaced by a list of the selected atoms.