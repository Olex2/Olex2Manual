# File Editing Options

If you are new to crystallography and Olex2 is the first crystallographic program you have come across, then you will find this section very odd indeed. If you are an expert crystallographer who has grown up with editing a SHELX .ins file before every refinement cycle, for example, then you have probably been wondering for a while how to edit the .ins.
Olex2 uses its very own model internally. All the information regarding your model is stored and managed by Olex2 transparently -- you don't need to worry about this (you can type `CODE describe` in the command-line to see what Olex2 knows about the refinement model, the same information is placed into the CIF when completing the structure). For somebody starting out their crystallographic career with Olex2, the question of editing files never arises. Olex2 provides all tools that are required to build models of any complexity using only the graphical interface. 
For those people who can't live without editing files (and also to safeguard against situations where the GUI might fail unexpectedly) we have provided the option to edit the Olex2 model using the SHELX syntax. In other words, Olex2 can export its current model in SHELX format in form of an .ins file for you to edit. While you edit this file, you can't make any changes in the model using the graphical interface, and once you save your edits, an updated Olex2 internal model will be created. As far as we know, all SHELX commands are fully supported by the Olex2 model.
The SHELX .ins file consists of several parts:

- At the beginning is the immutable information about the unit cell dimensions and the radiation used in the experiment.
- This is then followed by information about the symmetry (LATT/SYMM, i.e. the current space group) and the atom types and numbers present in the asymmetric unit.
- If there are constraints or restraints present, these will appear next. Note that some constraints can be very well hidden behind the FVAR instruction!
- And finally there is a list of all atoms (together with their coordinates and other information such as site occupancy).

If you want to examine a file-representation of the model, Olex2 offers the three options described below.

## Viewing the Instructions
This will display all the instructions for the refinement of the structure in a text editor. You can edit these instructions there and Olex2 will save these in its own model. These instructions relate to the overall refinement of the structure, but also show those instructions that are relevant for specific atoms only. Type 'CODE editins', or press I_EDIT .

##Viewing the Atom List
If you want to inspect or change properties of specific atoms, simply select the atoms you are interested in and you will only see the lines that are relevant to your selection. For each selected atom, you will see the atom line, but you will also see all lines of instructions related to your selection. Type 'CODE editatom', or press I_EDIT . All information belonging to the selected atoms will be displayed, including hydrogen atoms and restraints/constraints.

>OLEX2 Warning: Do not edit atom names in the .ins file or change the atom order when using the edit windows, as this can cause problems within Olex2 which keeps track of parameters in relations to each atom label. To change the atom name labels use `@Work|Naming` (or name command), and to change the order of the atoms in the list use `@Work|Sorting`.

##Viewing the Entire .ins File
To view the entire .ins file type `CODE edit ins` (note the space!) in the command-line to bring up a text editor. Save the file after making any changes in order to update the model in Olex2. Please be aware that you are 'on your own' in this mode: if you make mistakes or introduce invalid commands, Olex2 may not be able to load you updated file correctly, or you may find that some of your instructions do not appear in the Olex2 model. We do not recommend editing files in this way.
