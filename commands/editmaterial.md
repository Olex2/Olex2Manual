#editmaterial

>A {helpcmd, helptxt, execout, error, exception, any object name available with lstgo}

>B Brings up a dialog to change properties of the specified text section or graphical object.

>C helpcmd: material for the command name in the help window
helptxt: material for the body of the help item
execout: material for the output text printed in the console of external programs
error: material for reporting errors in the console
exception: material for reporting exception in the console
This command can be used to edit properties of any objects printed by 'lstgo' macro. An example of that could be editing material of the console text:
`CODE EditMaterial Console`
Note that the object name is case sensitive.
