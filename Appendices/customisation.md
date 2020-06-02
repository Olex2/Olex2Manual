# Customisation
> Olex2 can be intensively customised

In the header toolbar click on `@ Tools|Options` to enable customisation of the appearance of Olex2. At the top of the pop-out window are orange arrows, << and >>, which allow you to move forwards and backwards through the options (Elements of the Gui, Fonts, Plugins, Skins, External Programs, Automatic Updates). These options are fully explained in the pop-up window so not discussed here.

## Default Programs
Olex2 makes use of three programs that are already installed on the computer: notepad, internet browser and file explorer/chooser. It uses the default settings of your system, but you can define alternative programs if you wish.
To change default text editor, html editor or folder browser, you need to set the Olex2 variables associated with these programs. To keep the changes permanent, simply typle `emf` in Olex2. This will create a file called "custom.xld" in your data directory, which you can look at by typing `shell DataDir()`.

For example the following construct placed in that file sets programs for KDE:

>CODE <user_onstartup help="Executes on program start"
<body
  <args>
    <cmd
      <cmd1 "setvar(defeditor,'kate')">
      <cmd2 "setvar(defexplorer,'konqueror')">
      <cmd3 "setvar(defbrowser,'konqueror')">
    >
>

This defines a function which is called when Olex2 starts up, please note if several functions with the same name are found in the files - the last one will be used. Please avoid overriding any functions in the macro.xld file as this may cause Olex2 to function incorrectly.

## System Path
Olex2 uses the system path to locate various programs. If a particular program (ShelXL, PLATON etc) is in a folder that is not on the system path, or another instance of that same program is found on a folder that appears _first_ on the system path, then Olex2 will use the wrong program.

You can see which particular program is used by typing `echo file.which(program.exe)` if you ans to find which 'program.exe' is actually used.

In order to change the system path, you can either actually change the system path entry on your