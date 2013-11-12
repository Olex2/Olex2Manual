# Quick Access Icons


------------------------------------------------------------------------
Icon        Function
-------     ---------------------------------------------------------------
LI_STOP     This icon is not normally visible. If it is, something bad has happened in Olex2 and we would like to know about it. Please click on the icon and e-mail us the text you get.

LI_PLATON   If Platon is installed on your system, and the platon.exe file is `on the system PATH', this icon will open Platon with the current *.ins* or *.cif*.

LI_EDIT     Opens a text editor containing the refinement instructions in SHELX .ins file format. You can edit these instructions in this window. Olex2 manages your edits.

LI_EDITATOM Displays atomic information including associated constraints and restraints in a text editor. If no atoms are selected all atoms are displayed, if atoms are selected only information relating to those atoms is shown.
 
LI_OPEN     This will open the folder for currently loaded structure. This folder should only contain ONE *.ins* and ONE *.res* file, but may contain many *.hkl* files. There will also be an .olex folder in this subdirectory -- this is where Olex2 keeps the details relating to the current structure.
 
LI_TEXT     Displays current console buffer - what is seen in the graphic screen e.g. relating to refinements, suggesting space groups, calculating geometry, studying intermolecular interactions (the buffer has limited size and can be cleared using `CODE clear` command). This is useful if you want to copy and paste any of this information into other documents. A full transcript of the entire session can be obtained by typing `CODE log`. Use PGUP and PGDN keys to scroll the buffer.
 
LI_CENTER   This will try and assemble a fragmented structure `CODE compaq -a`, adjust the zoom and `CODE centre` the structure on the screen. Structures should not normally fragment, but sometimes they do.

------------------------------------------------------------------------
