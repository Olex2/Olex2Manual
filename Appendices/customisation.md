# Customisation
In the header toolbar click on `Tools|Options` to enable customisation of the appearance of Olex2. At the top of the pop-out window are orange arrows, << and >>, which allow you to move forwards and backwards through the options (Elements of the Gui, Fonts, Plugins, Skins, External Programs, Automatic Updates). These options are fully explained in the pop-up window so not discussed here. 

## Default Programs
Olex2 makes use of three programs that are already installed on the computer: notepad, internet browser and file explorer/chooser. It uses the default settings of your system, but you can define alternative programs if you wish.
To change default text editor, html editor or folder browser, you need to set the Olex2 variables associated with these programs. To keep the changes permanent, create the file 'custom.xld' in the Olex2 installation directory.
For example the following construct placed in that file sets programs for KDE:

`<user_onstartup help="Executes on program start"

<body 

  <args> 

    <cmd 

      <cmd1 "setvar(defeditor,'kate')">

      <cmd2 "setvar(defexplorer,'konqueror')">

      <cmd3 "setvar(defbrowser,'konqueror')">

    >

>

>`

This defines a function which is called when Olex2 starts up, please note if several functions with the same name are found in the files - the last one will be used. Please avoid overriding any functions in the macro.xld file as this may cause Olex2 to function incorrectly.