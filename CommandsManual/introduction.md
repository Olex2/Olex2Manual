\chapter{Olex2 Commands}

This document describes some of the commands that are available in Olex2. Many of these commands are also available directly from the Olex2 Graphical User Interface. Most items on the GUI have a small `info' symbol next to them, where you can find out more about any of these items.

#Introduction
There is no special console window in Olex2 -– the commands described in this document can be typed where ever you are in Olex2 and the text you type (as well as the program response) will appear in the bottom left hand corner of the main window. The text will then scroll up behind the displayed molecule. The number of lines of text that are visible can be set with the command `CODE lines n`. You can also toggle between showing the molecule only, showing the text only and showing both at the same time (default) using CTR+T. You can always examine the text output in your default text editor by typing `CODE text`.

Many commands in Olex2 are modelled on the syntax that may be familiar from SHELX: four letter commands, where the letters often provide a hint about the function of the command. Many commands that are available in ShelXP, for example, can be used in Olex2. Also, all commands of the ShelXL and ShelXS syntax are interpreted by Olex2 and used to construct the internal Olex2 structure model. This model is then used directly to carry out a smtbx-refine refinement, whereas a shelx.ins file is generated on the fly if ShelXL/XH is chosen for the refinement.
All commands in Olex2 will auto-complete when pressing the TAB key. If the completion is not possible, because there is more than one command starting with the letters that have been typed, a list of these commands will be printed. It is good practice to use the auto-complete feature!

\small