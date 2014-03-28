#FUNCTIONS
#Alert

**Arguments**: [2, 3 or 4]

**Description**: title message [flags YNCO-yes,no,cancel,ok XHEIQ-icon:exclamation,hand,eror,information,question R-show checkbox] [checkbox message]

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#ATA

**Arguments**: [any]

**Description**: Test current structure against database. (Atom Type Assignment). Returns true if any atom type changed

**Options**: None

**States**: Loaded file is expected

**Parent**: None

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#Atoms

**Arguments**: [1]

**Description**:

**Options**: None

**States**: Loaded file is expected

**Parent**: None

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#BaseDir

**Arguments**: [none or 1]

**Description**: Returns the startup folder

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#CalcR

**Arguments**: [none or 1]

**Description**: Calculates R1, R1 for I/sig >2 and wR2. If \'print\' is provided - prints detailed info

**Options**: None

**States**: Loaded file is expected

**Parent**: None

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#CCrd

**Arguments**: [any]

**Description**: Returns center of given (selected) atoms in fractional coordinates

**Options**: None

**States**: Loaded file is expected

**Parent**: None

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#Cell

**Arguments**: [1]

**Description**: Returns value of teh given parameter: a, b, c, alpha, beta, gamma, volume

**Options**: None

**States**: Loaded file is expected

**Parent**: None

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#CheckState

**Arguments**: [1 or 2]

**Description**: Returns if true if given program state is active

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#ChooseDir

**Arguments**: [none, 1 or 2]

**Description**: Shows a dialog to pick a folder. Arguments [title=Choose directory], [default path=current directory].

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#ChooseElement

**Arguments**: [none]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#ChooseFont

**Arguments**: [none, 1 or 2]

**Description**: Brings up a font dialog. If font information provided, initialises the dialog with that font; the first argument may be just \'olex2\' or \'system\' to enforce choosing the Olex2/System font (the font information can be provided in the second argument then)

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#ChooseMaterial

**Arguments**: [none or 1]

**Description**: Brings up a dialog to edit default or provided material

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#Cif

**Arguments**: [1]

**Description**: Returns instruction value (all data after the instruction). In case the instruction does not exist it return \'n/a\' string

**Options**: None

**States**: CIF file is expected

**Parent**: None

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#CmdList

**Arguments**: [1]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#Color

**Arguments**: [none, 1 or 2]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#Crd

**Arguments**: [any]

**Description**: Returns center of given (selected) atoms in cartesian coordinates

**Options**: None

**States**: Loaded file is expected

**Parent**: None

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#Crs

**Arguments**: [1]

**Description**: Returns instruction value (all data after the instruction). In case the instruction does not exist it return \'n/a\' string

**Options**: None

**States**: CRS file is expected

**Parent**: None

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#CurrentLanguage

**Arguments**: [none or 1]

**Description**: Returns/sets current language

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#CurrentLanguageEncoding

**Arguments**: [none]

**Description**: Returns current language encoding, like: ISO8859-1

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#Cursor

**Arguments**: [none, 1, 2 or 3]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#DataDir

**Arguments**: [none]

**Description**: Returns the location of user data

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#Env

**Arguments**: [1]

**Description**: Returns immediate atom environment

**Options**: None

**States**: Loaded file is expected

**Parent**: None

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#ExtraZoom

**Arguments**: [none or 1]

**Description**: Sets/reads current extra zoom (default zoom correction)

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#FATA

**Arguments**: [any]

**Description**: Calculates the diff Fourier map and integrates it to find artifacts around atoms. (Fourier Atom Type Analysis). Returns true if any atom type changed

**Options**: None

**States**: Loaded file is expected

**Parent**: None

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#FileDrive

**Arguments**: [none or 1]

**Description**: Returns file drive. If no arguments provided - of currently loaded file

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#FileExt

**Arguments**: [none or 1]

**Description**: Returns file extension. If no arguments provided - of currently loaded file

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#FileFull

**Arguments**: [none]

**Description**: Returns full path of currently loaded file

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#FileLast

**Arguments**: [none or 1]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#FileName

**Arguments**: [none or 1]

**Description**: If no arguments provided, returns file name of currently loaded file, for one argument returns extracted file name

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#FileOpen

**Arguments**: [3 or 4]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#FilePath

**Arguments**: [none or 1]

**Description**: Returns file path. If no arguments provided - of currently loaded file

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#FileSave

**Arguments**: [3 or 4]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#Flush

**Arguments**: [2 or 3]

**Description**: Saves variables to a file. The second argument is a mask in the form \'*\' \'settings.*\' etc, if the 3rd argument [0] is specified the variable names used as substringFrom(3rd arg); note that if the name is shorter that the value of the 3rd argument - the value is not saved.

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#FPS

**Arguments**: [none]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#Freeze

**Arguments**: [none or 1]

**Description**: Gets/Sets display update status

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#FullScreen

**Arguments**: [none or 1]

**Description**: Returns/sets full screen mode (true/false/swap)

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#GetCompilationInfo

**Arguments**: [none or 1]

**Description**: Returns compilation info

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#GetEnv

**Arguments**: [none or 1]

**Description**: Prints all variables if no arguments is given or returns the given veariable value

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#GetFont

**Arguments**: [1]

**Description**: Returns specified font

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#GetMAC

**Arguments**: [none or 1]

**Description**: Returns simicolon separated list of computer MAC addresses. If \'full\' is provided as argument, the adoptor names are also returned as adapter=MAC;..

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#GetMaterial

**Arguments**: [1 or 2]

**Description**: Returns material of specified object

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#GetMouseX

**Arguments**: [none]

**Description**: Returns current mouse X position

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#GetMouseY

**Arguments**: [none]

**Description**: Returns current mouse Y position

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#GetUserInput

**Arguments**: [3]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#GetVar

**Arguments**: [1 or 2]

**Description**: Gets the value of the specified variable. If the variable does not exist and no default value is provided - an error occurs

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#GetWindowSize

**Arguments**: [none, 1 or 3]

**Description**: Returns size of the requested window, main window by default

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#GlTooltip

**Arguments**: [none or 1]

**Description**: Returns state of/sets OpenGL tooltip implementation for the main window (some old platforms do not have proper implementation of tooltips)

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#HasGUI

**Arguments**: [none]

**Description**: Returns if true if Olex2 is built with GUI

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#HKLSrc

**Arguments**: [none or 1]

**Description**: Returns/sets hkl source for currently loaded file

**Options**: None

**States**: Loaded file is expected

**Parent**: None

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#HtmlPanelWidth

**Arguments**: [none or 1]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#Ins

**Arguments**: [1]

**Description**: Returns instruction value (all data after the instruction). In case the instruction does not exist it return \'n/a\' string

**Options**: None

**States**: INS file is expected

**Parent**: None

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#IsCurrentLanguage

**Arguments**: [1]

**Description**: Checks current language

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#IsFileLoaded

**Arguments**: [none]

**Description**: Returns true/false

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#IsFileType

**Arguments**: [1]

**Description**: Checks type of currently loaded file [ins,res,ires,cif,cmf,mol,xyz]

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#IsOS

**Arguments**: [1]

**Description**: Returns true if current system Windows [win], Linux/GTK [linux], Mac [mac]

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#IsPluginInstalled

**Arguments**: [1]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#IsVar

**Arguments**: [1]

**Description**: Checks if the specified variable exists

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#LastError

**Arguments**: [none]

**Description**: Returns last error

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#LoadDll

**Arguments**: [1]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#LogLevel

**Arguments**: [none or 1]

**Description**: Returns/sets log level, default is \'m\' - for macro, accepts/returns \'m\', \'mf\' or \'f\'

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#LSM

**Arguments**: [none or 1]

**Description**: Return/sets current refinement method, L.S. or CGLS currently. The method can also be set using LS macro

**Options**: None

**States**: INS file is expected

**Parent**: None

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#Lst

**Arguments**: [1]

**Description**: returns a value from the Lst file

**Options**: None

**States**: INS file is expected

**Parent**: None

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#MatchFiles

**Arguments**: [2 or 3]

**Description**: Matches given files

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#P4p

**Arguments**: [1]

**Description**: Returns instruction value (all data after the instruction). In case the instruction does not exist it return \'n/a\' string

**Options**: None

**States**: P4P file is expected

**Parent**: None

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#Process

**Arguments**: [1]

**Description**: Processes a function passed as the argument and returns the result

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#RemoveSE

**Arguments**: [1]

**Description**: Returns a new space group name without provided element

**Options**: None

**States**: Loaded file is expected

**Parent**: None

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#RGB

**Arguments**: [3 or 4]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#Run

**Arguments**: [1]

**Description**: Same as the macro, executes provided commands (separated by >>) returns true if succeded

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#Sel

**Arguments**: [none or 1]

**Description**: Returns current selection. By default expands bonds and planes into the list of atoms. If the \'a\' argument is given, returns only selected atoms.

**Options**: None

**States**: Loaded file is expected

**Parent**: None

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#SetVar

**Arguments**: [2]

**Description**: Sets the value of the specified variable

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#SG

**Arguments**: [none or 1]

**Description**: Returns space group of currently loaded file. Also takes a string template, where %# is replaced with SG number, %n - short name, %N - full name, %h - html representation of the short name, %H - same as %h for full name, %s - syngony, %HS -Hall symbol

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#SGList

**Arguments**: [none]

**Description**: Returns result of the last call to the space group determination procedure

**Options**: None

**States**: Loaded file is expected

**Parent**: None

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#SGS

**Arguments**: [none or 1]

**Description**: Returns current space settings

**Options**: None

**States**: Loaded file is expected

**Parent**: None

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#SSM

**Arguments**: [none or 1]

**Description**: Return current structure solution method, TREF or PATT currently. If current method is unknown and an argument is provided, that argument is returned

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#Strcat

**Arguments**: [2]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#Strcmp

**Arguments**: [2]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#StrDir

**Arguments**: [none]

**Description**: Returns location of the folder, where Olex2 stores structure related data

**Options**: None

**States**: Loaded file is expected

**Parent**: None

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#ThreadCount

**Arguments**: [none or 1]

**Description**: Returns/sets the number of simultaneous tasks

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#Title

**Arguments**: [none or 1]

**Description**: If the file is loaded, returns it\'s title else if a parameter passed, it is returned

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#TranslatePhrase

**Arguments**: [1]

**Description**: Translates provided phrase into current language

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#UnsetVar

**Arguments**: [1]

**Description**: Removes the specified variable

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#ValidatePlugin

**Arguments**: [1]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#VSS

**Arguments**: [1]

**Description**: Validate Structure or Solution. Takes a boolean value. If value is true, the number of tested atoms is limited by the 18A rule. Returns proportion of known atom types to the all atoms number.

**Options**: None

**States**: Loaded file is expected

**Parent**: None

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#VVol

**Arguments**: [none or 1]

**Description**: A simplistic procedure to calculate molecular volume - only pairwise overlapping of atoms is considered

**Options**: None

**States**: Loaded file is expected

**Parent**: None

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#app.ArgCount

**Arguments**: [none]

**Description**: Returns number of arguments passed to the application

**Options**: None

**States**: No requirement

**Parent**: app

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#app.BaseDir

**Arguments**: [none]

**Description**: Returns the directory from which the application is launched.

**Options**: None

**States**: No requirement

**Parent**: app

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#app.ConfigDir

**Arguments**: [none]

**Description**: Returns the configuration directory. If it is not set, the InstanceDir is returned

**Options**: None

**States**: No requirement

**Parent**: app

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#app.GetArg

**Arguments**: [1]

**Description**: Returns application argument value by index

**Options**: None

**States**: No requirement

**Parent**: app

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#app.GetLogName

**Arguments**: [none]

**Description**: Returns current log file name

**Options**: None

**States**: No requirement

**Parent**: app

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#app.GetOpt

**Arguments**: [1]

**Description**: Returns application \'option=value\' value by index. \'=\' only added if the values is not empty

**Options**: None

**States**: No requirement

**Parent**: app

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#app.InstanceDir

**Arguments**: [none]

**Description**: Returns the instance specific, writable directory.

**Options**: None

**States**: No requirement

**Parent**: app

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#app.IsBaseDirWritable

**Arguments**: [none]

**Description**: Returns true if the application can write to the BaseDir()

**Options**: None

**States**: No requirement

**Parent**: app

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#app.IsDebugBuild

**Arguments**: [none]

**Description**: Returns true if the application is built with debug info

**Options**: None

**States**: No requirement

**Parent**: app

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#app.ModuleHash

**Arguments**: [none]

**Description**: Returns current module MD5 hash

**Options**: None

**States**: No requirement

**Parent**: app

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#app.OptCount

**Arguments**: [none]

**Description**: Returns number of options passed to the application

**Options**: None

**States**: No requirement

**Parent**: app

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#app.OptValue

**Arguments**: [1 or 2]

**Description**: Returns value of the given option (default may be provided)

**Options**: None

**States**: No requirement

**Parent**: app

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#app.Platform

**Arguments**: [none]

**Description**: Returns current platform like WIN, MAC, Linux 32/64

**Options**: None

**States**: No requirement

**Parent**: app

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#app.Profiling

**Arguments**: [none or 1]

**Description**: Sets/Returns current procedure profiling status

**Options**: None

**States**: No requirement

**Parent**: app

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#app.SaveOptions

**Arguments**: [none]

**Description**: Saves options to ConfigDir/.options file

**Options**: None

**States**: No requirement

**Parent**: app

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#app.SharedDir

**Arguments**: [none]

**Description**: Returns a generic writable directory.

**Options**: None

**States**: No requirement

**Parent**: app

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#console.Clear

**Arguments**: [none]

**Description**: Clears the content of the output buffer

**Options**: None

**States**: No requirement

**Parent**: console

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#console.Command

**Arguments**: [none or 1]

**Description**: Changes/returns current command

**Options**: None

**States**: No requirement

**Parent**: console

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#console.GetName

**Arguments**: [none]

**Description**: Returns object collection name

**Options**: None

**States**: No requirement

**Parent**: console

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#console.IsGrouped

**Arguments**: [none]

**Description**: Returns true if the object is in a group

**Options**: None

**States**: No requirement

**Parent**: console

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#console.IsSelected

**Arguments**: [none]

**Description**: Returns true if the object is selected

**Options**: None

**States**: No requirement

**Parent**: console

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#console.Lines

**Arguments**: [none or 1]

**Description**: Sets/returns the number of lines to display

**Options**: None

**States**: No requirement

**Parent**: console

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#console.LineSpacing

**Arguments**: [none or 1]

**Description**: Changes/returns current line spacing

**Options**: None

**States**: No requirement

**Parent**: console

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#console.Post

**Arguments**: [any except none]

**Description**: Adds provided text to the output buffer

**Options**: None

**States**: No requirement

**Parent**: console

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#console.PromptString

**Arguments**: [none or 1]

**Description**: Changes/returns current prompt string

**Options**: None

**States**: No requirement

**Parent**: console

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#console.ShowBuffer

**Arguments**: [none or 1]

**Description**: Shows/hides the output buffer or returns current status

**Options**: None

**States**: No requirement

**Parent**: console

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#console.Visible

**Arguments**: [none or 1]

**Description**: Changes/returns object visibility

**Options**: None

**States**: No requirement

**Parent**: console

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#console.cursor.Symbol

**Arguments**: [none or 1]

**Description**: Returns or sets current symbol used to draw the cursor

**Options**: None

**States**: No requirement

**Parent**: console.cursor

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#fader.BG2FG

**Arguments**: [none or 1]

**Description**: Copies current background frame to foreground frame

**Options**: None

**States**: No requirement

**Parent**: fader

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#fader.GetName

**Arguments**: [none]

**Description**: Returns object collection name

**Options**: None

**States**: No requirement

**Parent**: fader

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#fader.InitBG

**Arguments**: [none or 1]

**Description**: Initialises xfader background frame

**Options**: None

**States**: No requirement

**Parent**: fader

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#fader.InitFG

**Arguments**: [none or 1]

**Description**: Initialises xfader foreground frame

**Options**: None

**States**: No requirement

**Parent**: fader

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#fader.IsGrouped

**Arguments**: [none]

**Description**: Returns true if the object is in a group

**Options**: None

**States**: No requirement

**Parent**: fader

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#fader.IsSelected

**Arguments**: [none]

**Description**: Returns true if the object is selected

**Options**: None

**States**: No requirement

**Parent**: fader

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#fader.Position

**Arguments**: [none or 1]

**Description**: Sets/returns current xfader position

**Options**: None

**States**: No requirement

**Parent**: fader

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#fader.Step

**Arguments**: [none or 1]

**Description**: Sets/returns xfader increment

**Options**: None

**States**: No requirement

**Parent**: fader

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#fader.Visible

**Arguments**: [none or 1]

**Description**: Changes/returns object visibility

**Options**: None

**States**: No requirement

**Parent**: fader

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#file.AbsolutePath

**Arguments**: [1 or 2]

**Description**: Returns an absolute path to a folder relative to the basedir; arguments are (base=basedir,path)

**Options**: None

**States**: No requirement

**Parent**: file

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#file.Age

**Arguments**: [1 or 2]

**Description**: Returns file age for provided file using formatting string (if provided)

**Options**: None

**States**: No requirement

**Parent**: file

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#file.ChangeExt

**Arguments**: [2]

**Description**: Returns file name with changed extension

**Options**: None

**States**: No requirement

**Parent**: file

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#file.ChDir

**Arguments**: [1]

**Description**: Changes current folder to provided folder

**Options**: None

**States**: No requirement

**Parent**: file

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#file.Copy

**Arguments**: [2]

**Description**: Copies file provided as first argument into the file provided as second argument

**Options**: None

**States**: No requirement

**Parent**: file

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#file.CurDir

**Arguments**: [none]

**Description**: Returns current folder

**Options**: None

**States**: No requirement

**Parent**: file

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#file.Delete

**Arguments**: [1]

**Description**: Deletes specified file

**Options**: None

**States**: No requirement

**Parent**: file

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#file.Exists

**Arguments**: [1]

**Description**: Returns true if specified file exists

**Options**: None

**States**: No requirement

**Parent**: file

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#file.GetDrive

**Arguments**: [1]

**Description**: Returns drive component of the full file name

**Options**: None

**States**: No requirement

**Parent**: file

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#file.GetExt

**Arguments**: [1]

**Description**: Returns file extension

**Options**: None

**States**: No requirement

**Parent**: file

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#file.GetName

**Arguments**: [1]

**Description**: Returns name part of the full/partial file name

**Options**: None

**States**: No requirement

**Parent**: file

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#file.GetPath

**Arguments**: [1]

**Description**: Returns path component of the full file name

**Options**: None

**States**: No requirement

**Parent**: file

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#file.ListDirForGUI

**Arguments**: [2 or 3]

**Description**: Returns a ready to use in GUI list of files, matching provided mask(s) separated by semicolon. The third, optional argument [f,d,fd] specifies what should be included into the list

**Options**: None

**States**: No requirement

**Parent**: file

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#file.MkDir

**Arguments**: [1]

**Description**: Creates specified folder

**Options**: None

**States**: No requirement

**Parent**: file

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#file.OSPath

**Arguments**: [1]

**Description**: Returns OS specific path for provided path

**Options**: None

**States**: No requirement

**Parent**: file

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#file.RelativePath

**Arguments**: [1 or 2]

**Description**: Returns a path to a folder relative to basedir; arguments are (base=basedir,path)

**Options**: None

**States**: No requirement

**Parent**: file

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#file.Rename

**Arguments**: [2]

**Description**: Renames specified file

**Options**: None

**States**: No requirement

**Parent**: file

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#file.Which

**Arguments**: [1]

**Description**: Tries to find a particular file looking at current folder, PATH and program folder

**Options**: None

**States**: No requirement

**Parent**: file

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#fs.Exists

**Arguments**: [1]

**Description**: Returns true if the specified file exists on the virtual file system

**Options**: None

**States**: No requirement

**Parent**: fs

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#gl.Basis

**Arguments**: [none or 1]

**Description**: Returns/sets view basis

**Options**: None

**States**: No requirement

**Parent**: gl

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#gl.CalcZoom

**Arguments**: [none]

**Description**: Returns optimal zoom value

**Options**: None

**States**: No requirement

**Parent**: gl

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#gl.Compile

**Arguments**: [1]

**Description**: Compiles or decompiles the model according to the boolean parameter

**Options**: None

**States**: No requirement

**Parent**: gl

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#gl.GetZoom

**Arguments**: [none]

**Description**: Returns current zoom value

**Options**: None

**States**: No requirement

**Parent**: gl

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#gl.LineWidth

**Arguments**: [none or 1]

**Description**: Returns/sets width of the raster OpenGl line

**Options**: None

**States**: No requirement

**Parent**: gl

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#gl.RasterZ

**Arguments**: [none or 1]

**Description**: Returns/sets maximum value of the raster Z 1 or -1 is typically expected

**Options**: None

**States**: No requirement

**Parent**: gl

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#gl.Stereo

**Arguments**: [none, 1 or 2]

**Description**: Returns/sets color/cross/anaglyph/hardware stereo mode and optionally stereo angle [3]

**Options**: None

**States**: No requirement

**Parent**: gl

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#gl.StereoColor

**Arguments**: [1, 2 or 4]

**Description**: Returns/sets colors for left/right color stereo mode glasses

**Options**: None

**States**: No requirement

**Parent**: gl

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#gl.lm.AmbientColor

**Arguments**: [none or 1]

**Description**: Returns/sets ambient color of the model

**Options**: None

**States**: No requirement

**Parent**: gl.lm

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#gl.lm.ClearColor

**Arguments**: [none or 1]

**Description**: Returns/sets background color of the model

**Options**: None

**States**: No requirement

**Parent**: gl.lm

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#gl.lm.LocalViewer

**Arguments**: [none or 1]

**Description**: Returns/sets local viewer property of the model

**Options**: None

**States**: No requirement

**Parent**: gl.lm

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#gl.lm.SmoothShade

**Arguments**: [none or 1]

**Description**: Returns/sets smooth shading of the model

**Options**: None

**States**: No requirement

**Parent**: gl.lm

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#gl.lm.TwoSides

**Arguments**: [none or 1]

**Description**: Returns/sets two sides coloring of the model

**Options**: None

**States**: No requirement

**Parent**: gl.lm

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#gl.lm.light1.Ambient

**Arguments**: [none or 1]

**Description**: Returns/sets enabled property of the light

**Options**: None

**States**: No requirement

**Parent**: gl.lm.light1

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#gl.lm.light1.Attenuation

**Arguments**: [none or 1]

**Description**: Returns/sets enabled property of the light

**Options**: None

**States**: No requirement

**Parent**: gl.lm.light1

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#gl.lm.light1.Diffuse

**Arguments**: [none or 1]

**Description**: Returns/sets enabled property of the light

**Options**: None

**States**: No requirement

**Parent**: gl.lm.light1

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#gl.lm.light1.Enabled

**Arguments**: [none or 1]

**Description**: Returns/sets enabled property of the light

**Options**: None

**States**: No requirement

**Parent**: gl.lm.light1

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#gl.lm.light1.Position

**Arguments**: [none or 1]

**Description**: Returns/sets enabled property of the light

**Options**: None

**States**: No requirement

**Parent**: gl.lm.light1

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#gl.lm.light1.Specular

**Arguments**: [none or 1]

**Description**: Returns/sets enabled property of the light

**Options**: None

**States**: No requirement

**Parent**: gl.lm.light1

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#gl.lm.light1.SpotCutoff

**Arguments**: [none or 1]

**Description**: Returns/sets spot cutoff property of the light

**Options**: None

**States**: No requirement

**Parent**: gl.lm.light1

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#gl.lm.light1.SpotDirection

**Arguments**: [none or 1]

**Description**: Returns/sets enabled property of the light

**Options**: None

**States**: No requirement

**Parent**: gl.lm.light1

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#gl.lm.light1.SpotExponent

**Arguments**: [none or 1]

**Description**: Returns/sets enabled property of the light

**Options**: None

**States**: No requirement

**Parent**: gl.lm.light1

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#gl.lm.light2.Ambient

**Arguments**: [none or 1]

**Description**: Returns/sets enabled property of the light

**Options**: None

**States**: No requirement

**Parent**: gl.lm.light2

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#gl.lm.light2.Attenuation

**Arguments**: [none or 1]

**Description**: Returns/sets enabled property of the light

**Options**: None

**States**: No requirement

**Parent**: gl.lm.light2

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#gl.lm.light2.Diffuse

**Arguments**: [none or 1]

**Description**: Returns/sets enabled property of the light

**Options**: None

**States**: No requirement

**Parent**: gl.lm.light2

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#gl.lm.light2.Enabled

**Arguments**: [none or 1]

**Description**: Returns/sets enabled property of the light

**Options**: None

**States**: No requirement

**Parent**: gl.lm.light2

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#gl.lm.light2.Position

**Arguments**: [none or 1]

**Description**: Returns/sets enabled property of the light

**Options**: None

**States**: No requirement

**Parent**: gl.lm.light2

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#gl.lm.light2.Specular

**Arguments**: [none or 1]

**Description**: Returns/sets enabled property of the light

**Options**: None

**States**: No requirement

**Parent**: gl.lm.light2

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#gl.lm.light2.SpotCutoff

**Arguments**: [none or 1]

**Description**: Returns/sets spot cutoff property of the light

**Options**: None

**States**: No requirement

**Parent**: gl.lm.light2

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#gl.lm.light2.SpotDirection

**Arguments**: [none or 1]

**Description**: Returns/sets enabled property of the light

**Options**: None

**States**: No requirement

**Parent**: gl.lm.light2

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#gl.lm.light2.SpotExponent

**Arguments**: [none or 1]

**Description**: Returns/sets enabled property of the light

**Options**: None

**States**: No requirement

**Parent**: gl.lm.light2

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#gl.lm.light3.Ambient

**Arguments**: [none or 1]

**Description**: Returns/sets enabled property of the light

**Options**: None

**States**: No requirement

**Parent**: gl.lm.light3

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#gl.lm.light3.Attenuation

**Arguments**: [none or 1]

**Description**: Returns/sets enabled property of the light

**Options**: None

**States**: No requirement

**Parent**: gl.lm.light3

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#gl.lm.light3.Diffuse

**Arguments**: [none or 1]

**Description**: Returns/sets enabled property of the light

**Options**: None

**States**: No requirement

**Parent**: gl.lm.light3

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#gl.lm.light3.Enabled

**Arguments**: [none or 1]

**Description**: Returns/sets enabled property of the light

**Options**: None

**States**: No requirement

**Parent**: gl.lm.light3

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#gl.lm.light3.Position

**Arguments**: [none or 1]

**Description**: Returns/sets enabled property of the light

**Options**: None

**States**: No requirement

**Parent**: gl.lm.light3

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#gl.lm.light3.Specular

**Arguments**: [none or 1]

**Description**: Returns/sets enabled property of the light

**Options**: None

**States**: No requirement

**Parent**: gl.lm.light3

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#gl.lm.light3.SpotCutoff

**Arguments**: [none or 1]

**Description**: Returns/sets spot cutoff property of the light

**Options**: None

**States**: No requirement

**Parent**: gl.lm.light3

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#gl.lm.light3.SpotDirection

**Arguments**: [none or 1]

**Description**: Returns/sets enabled property of the light

**Options**: None

**States**: No requirement

**Parent**: gl.lm.light3

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#gl.lm.light3.SpotExponent

**Arguments**: [none or 1]

**Description**: Returns/sets enabled property of the light

**Options**: None

**States**: No requirement

**Parent**: gl.lm.light3

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#gl.lm.light4.Ambient

**Arguments**: [none or 1]

**Description**: Returns/sets enabled property of the light

**Options**: None

**States**: No requirement

**Parent**: gl.lm.light4

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#gl.lm.light4.Attenuation

**Arguments**: [none or 1]

**Description**: Returns/sets enabled property of the light

**Options**: None

**States**: No requirement

**Parent**: gl.lm.light4

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#gl.lm.light4.Diffuse

**Arguments**: [none or 1]

**Description**: Returns/sets enabled property of the light

**Options**: None

**States**: No requirement

**Parent**: gl.lm.light4

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#gl.lm.light4.Enabled

**Arguments**: [none or 1]

**Description**: Returns/sets enabled property of the light

**Options**: None

**States**: No requirement

**Parent**: gl.lm.light4

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#gl.lm.light4.Position

**Arguments**: [none or 1]

**Description**: Returns/sets enabled property of the light

**Options**: None

**States**: No requirement

**Parent**: gl.lm.light4

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#gl.lm.light4.Specular

**Arguments**: [none or 1]

**Description**: Returns/sets enabled property of the light

**Options**: None

**States**: No requirement

**Parent**: gl.lm.light4

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#gl.lm.light4.SpotCutoff

**Arguments**: [none or 1]

**Description**: Returns/sets spot cutoff property of the light

**Options**: None

**States**: No requirement

**Parent**: gl.lm.light4

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#gl.lm.light4.SpotDirection

**Arguments**: [none or 1]

**Description**: Returns/sets enabled property of the light

**Options**: None

**States**: No requirement

**Parent**: gl.lm.light4

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#gl.lm.light4.SpotExponent

**Arguments**: [none or 1]

**Description**: Returns/sets enabled property of the light

**Options**: None

**States**: No requirement

**Parent**: gl.lm.light4

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#gl.lm.light5.Ambient

**Arguments**: [none or 1]

**Description**: Returns/sets enabled property of the light

**Options**: None

**States**: No requirement

**Parent**: gl.lm.light5

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#gl.lm.light5.Attenuation

**Arguments**: [none or 1]

**Description**: Returns/sets enabled property of the light

**Options**: None

**States**: No requirement

**Parent**: gl.lm.light5

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#gl.lm.light5.Diffuse

**Arguments**: [none or 1]

**Description**: Returns/sets enabled property of the light

**Options**: None

**States**: No requirement

**Parent**: gl.lm.light5

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#gl.lm.light5.Enabled

**Arguments**: [none or 1]

**Description**: Returns/sets enabled property of the light

**Options**: None

**States**: No requirement

**Parent**: gl.lm.light5

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#gl.lm.light5.Position

**Arguments**: [none or 1]

**Description**: Returns/sets enabled property of the light

**Options**: None

**States**: No requirement

**Parent**: gl.lm.light5

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#gl.lm.light5.Specular

**Arguments**: [none or 1]

**Description**: Returns/sets enabled property of the light

**Options**: None

**States**: No requirement

**Parent**: gl.lm.light5

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#gl.lm.light5.SpotCutoff

**Arguments**: [none or 1]

**Description**: Returns/sets spot cutoff property of the light

**Options**: None

**States**: No requirement

**Parent**: gl.lm.light5

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#gl.lm.light5.SpotDirection

**Arguments**: [none or 1]

**Description**: Returns/sets enabled property of the light

**Options**: None

**States**: No requirement

**Parent**: gl.lm.light5

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#gl.lm.light5.SpotExponent

**Arguments**: [none or 1]

**Description**: Returns/sets enabled property of the light

**Options**: None

**States**: No requirement

**Parent**: gl.lm.light5

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#gl.lm.light6.Ambient

**Arguments**: [none or 1]

**Description**: Returns/sets enabled property of the light

**Options**: None

**States**: No requirement

**Parent**: gl.lm.light6

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#gl.lm.light6.Attenuation

**Arguments**: [none or 1]

**Description**: Returns/sets enabled property of the light

**Options**: None

**States**: No requirement

**Parent**: gl.lm.light6

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#gl.lm.light6.Diffuse

**Arguments**: [none or 1]

**Description**: Returns/sets enabled property of the light

**Options**: None

**States**: No requirement

**Parent**: gl.lm.light6

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#gl.lm.light6.Enabled

**Arguments**: [none or 1]

**Description**: Returns/sets enabled property of the light

**Options**: None

**States**: No requirement

**Parent**: gl.lm.light6

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#gl.lm.light6.Position

**Arguments**: [none or 1]

**Description**: Returns/sets enabled property of the light

**Options**: None

**States**: No requirement

**Parent**: gl.lm.light6

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#gl.lm.light6.Specular

**Arguments**: [none or 1]

**Description**: Returns/sets enabled property of the light

**Options**: None

**States**: No requirement

**Parent**: gl.lm.light6

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#gl.lm.light6.SpotCutoff

**Arguments**: [none or 1]

**Description**: Returns/sets spot cutoff property of the light

**Options**: None

**States**: No requirement

**Parent**: gl.lm.light6

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#gl.lm.light6.SpotDirection

**Arguments**: [none or 1]

**Description**: Returns/sets enabled property of the light

**Options**: None

**States**: No requirement

**Parent**: gl.lm.light6

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#gl.lm.light6.SpotExponent

**Arguments**: [none or 1]

**Description**: Returns/sets enabled property of the light

**Options**: None

**States**: No requirement

**Parent**: gl.lm.light6

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#gl.lm.light7.Ambient

**Arguments**: [none or 1]

**Description**: Returns/sets enabled property of the light

**Options**: None

**States**: No requirement

**Parent**: gl.lm.light7

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#gl.lm.light7.Attenuation

**Arguments**: [none or 1]

**Description**: Returns/sets enabled property of the light

**Options**: None

**States**: No requirement

**Parent**: gl.lm.light7

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#gl.lm.light7.Diffuse

**Arguments**: [none or 1]

**Description**: Returns/sets enabled property of the light

**Options**: None

**States**: No requirement

**Parent**: gl.lm.light7

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#gl.lm.light7.Enabled

**Arguments**: [none or 1]

**Description**: Returns/sets enabled property of the light

**Options**: None

**States**: No requirement

**Parent**: gl.lm.light7

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#gl.lm.light7.Position

**Arguments**: [none or 1]

**Description**: Returns/sets enabled property of the light

**Options**: None

**States**: No requirement

**Parent**: gl.lm.light7

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#gl.lm.light7.Specular

**Arguments**: [none or 1]

**Description**: Returns/sets enabled property of the light

**Options**: None

**States**: No requirement

**Parent**: gl.lm.light7

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#gl.lm.light7.SpotCutoff

**Arguments**: [none or 1]

**Description**: Returns/sets spot cutoff property of the light

**Options**: None

**States**: No requirement

**Parent**: gl.lm.light7

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#gl.lm.light7.SpotDirection

**Arguments**: [none or 1]

**Description**: Returns/sets enabled property of the light

**Options**: None

**States**: No requirement

**Parent**: gl.lm.light7

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#gl.lm.light7.SpotExponent

**Arguments**: [none or 1]

**Description**: Returns/sets enabled property of the light

**Options**: None

**States**: No requirement

**Parent**: gl.lm.light7

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#gl.lm.light8.Ambient

**Arguments**: [none or 1]

**Description**: Returns/sets enabled property of the light

**Options**: None

**States**: No requirement

**Parent**: gl.lm.light8

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#gl.lm.light8.Attenuation

**Arguments**: [none or 1]

**Description**: Returns/sets enabled property of the light

**Options**: None

**States**: No requirement

**Parent**: gl.lm.light8

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#gl.lm.light8.Diffuse

**Arguments**: [none or 1]

**Description**: Returns/sets enabled property of the light

**Options**: None

**States**: No requirement

**Parent**: gl.lm.light8

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#gl.lm.light8.Enabled

**Arguments**: [none or 1]

**Description**: Returns/sets enabled property of the light

**Options**: None

**States**: No requirement

**Parent**: gl.lm.light8

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#gl.lm.light8.Position

**Arguments**: [none or 1]

**Description**: Returns/sets enabled property of the light

**Options**: None

**States**: No requirement

**Parent**: gl.lm.light8

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#gl.lm.light8.Specular

**Arguments**: [none or 1]

**Description**: Returns/sets enabled property of the light

**Options**: None

**States**: No requirement

**Parent**: gl.lm.light8

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#gl.lm.light8.SpotCutoff

**Arguments**: [none or 1]

**Description**: Returns/sets spot cutoff property of the light

**Options**: None

**States**: No requirement

**Parent**: gl.lm.light8

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#gl.lm.light8.SpotDirection

**Arguments**: [none or 1]

**Description**: Returns/sets enabled property of the light

**Options**: None

**States**: No requirement

**Parent**: gl.lm.light8

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#gl.lm.light8.SpotExponent

**Arguments**: [none or 1]

**Description**: Returns/sets enabled property of the light

**Options**: None

**States**: No requirement

**Parent**: gl.lm.light8

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#html.Call

**Arguments**: [1]

**Description**: Calls event of specified control, expects [popup.]control.event

**Options**: None

**States**: No requirement

**Parent**: html

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#html.ClientHeight

**Arguments**: [1 or 2]

**Description**: Returns/sets client height of an HTML window (use \'self\' to address the window itself)

**Options**: None

**States**: No requirement

**Parent**: html

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#html.ClientWidth

**Arguments**: [1 or 2]

**Description**: Returns/sets client width of an HTML window (use \'self\' to address the window itself)

**Options**: None

**States**: No requirement

**Parent**: html

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#html.ContainerHeight

**Arguments**: [1 or 2]

**Description**: Returns/sets height of a popup window

**Options**: None

**States**: No requirement

**Parent**: html

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#html.ContainerWidth

**Arguments**: [1 or 2]

**Description**: Returns/sets width of a popup window

**Options**: None

**States**: No requirement

**Parent**: html

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#html.EndModal

**Arguments**: [2]

**Description**: Ends a modal popup and sets the return code

**Options**: None

**States**: No requirement

**Parent**: html

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#html.GetBorders

**Arguments**: [none or 1]

**Description**: Returns borders width between HTML content and window boundaries

**Options**: None

**States**: No requirement

**Parent**: html

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#html.GetData

**Arguments**: [1]

**Description**: Returns data associated with specified object

**Options**: None

**States**: No requirement

**Parent**: html

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#html.GetFontName

**Arguments**: [none or 1]

**Description**: Returns current font name

**Options**: None

**States**: No requirement

**Parent**: html

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#html.GetImage

**Arguments**: [1]

**Description**: Returns image source for a button or zimg

**Options**: None

**States**: No requirement

**Parent**: html

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#html.GetItems

**Arguments**: [1]

**Description**: Returns items of a combobox or list

**Options**: None

**States**: No requirement

**Parent**: html

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#html.GetItemState

**Arguments**: [1]

**Description**: Returns item state of the given switch

**Options**: None

**States**: No requirement

**Parent**: html

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#html.GetLabel

**Arguments**: [1]

**Description**: Returns labels of specified object. Applicable to labels, buttons and checkboxes

**Options**: None

**States**: No requirement

**Parent**: html

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#html.GetState

**Arguments**: [1 or 2]

**Description**: Returns state of the checkbox or a button. For example: echo getstate(button, enabled/down) or echo getstate(checkbox)

**Options**: None

**States**: No requirement

**Parent**: html

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#html.GetValue

**Arguments**: [1]

**Description**: Returns value of specified object

**Options**: None

**States**: No requirement

**Parent**: html

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#html.Height

**Arguments**: [1 or 2]

**Description**: Returns/sets height of an HTML object window (use \'self\' to address the window itself)

**Options**: None

**States**: No requirement

**Parent**: html

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#html.IsItem

**Arguments**: [1]

**Description**: Returns true if specified switch exists

**Options**: None

**States**: No requirement

**Parent**: html

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#html.IsPopup

**Arguments**: [1]

**Description**: Returns true if specified popup window exists and visible

**Options**: None

**States**: No requirement

**Parent**: html

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#html.LoadData

**Arguments**: [1 or 2]

**Description**: Loads previously saved data of html objects form a file

**Options**: None

**States**: No requirement

**Parent**: html

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#html.SaveData

**Arguments**: [1 or 2]

**Description**: Saves state, data, label and value of all objects to a file

**Options**: None

**States**: No requirement

**Parent**: html

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#html.Select

**Arguments**: [2 or 3]

**Description**: Selects a treeview item by label (default) or data (third argument should be False)

**Options**: None

**States**: No requirement

**Parent**: html

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#html.SetBG

**Arguments**: [2]

**Description**: Sets background of specified object

**Options**: None

**States**: No requirement

**Parent**: html

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#html.SetData

**Arguments**: [2]

**Description**: Sets data for specified object

**Options**: None

**States**: No requirement

**Parent**: html

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#html.SetFG

**Arguments**: [2]

**Description**: Sets foreground of specified object

**Options**: None

**States**: No requirement

**Parent**: html

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#html.SetFocus

**Arguments**: [1]

**Description**: Sets input focus to the specified HTML control

**Options**: None

**States**: No requirement

**Parent**: html

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#html.SetImage

**Arguments**: [2]

**Description**: Sets image location for a button or a zimg

**Options**: None

**States**: No requirement

**Parent**: html

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#html.SetItems

**Arguments**: [2]

**Description**: Sets items for comboboxes and lists

**Options**: None

**States**: No requirement

**Parent**: html

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#html.SetLabel

**Arguments**: [2]

**Description**: Sets labels for a label, button or checkbox

**Options**: None

**States**: No requirement

**Parent**: html

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#html.SetState

**Arguments**: [2 or 3]

**Description**: Sets state of a checkbox or a button

**Options**: None

**States**: No requirement

**Parent**: html

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#html.SetValue

**Arguments**: [2]

**Description**: Sets value of specified object

**Options**: None

**States**: No requirement

**Parent**: html

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#html.ShowModal

**Arguments**: [1 or 2]

**Description**: Shows a previously created popup window as a modal dialog

**Options**: None

**States**: No requirement

**Parent**: html

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#html.Snippet

**Arguments**: [any except none]

**Description**: Loades a file (first arg), replaces #name from name=val for following params and returns the result.

**Options**: None

**States**: No requirement

**Parent**: html

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#html.Width

**Arguments**: [1 or 2]

**Description**: Returns/sets width of an HTML object window (use \'self\' to address the window itself)

**Options**: None

**States**: No requirement

**Parent**: html

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#lcells.Search

**Arguments**: [none, 1, 2 or 7]

**Description**: Searches given cell

**Options**: None

**States**: No requirement

**Parent**: lcells

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#math.eval

**Arguments**: [1]

**Description**: Evaluates given expression

**Options**: None

**States**: No requirement

**Parent**: math

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#mouse.IsEnabled

**Arguments**: [1]

**Description**: Returns current status for rotation, zooming, translation or selection

**Options**: None

**States**: No requirement

**Parent**: mouse

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#py.Export

**Arguments**: [1]

**Description**: Exports the library to a folder

**Options**: None

**States**: No requirement

**Parent**: py

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#py.LogLevel

**Arguments**: [none or 1]

**Description**: Sets log level - default is macro, look at LogLevel for more information

**Options**: None

**States**: No requirement

**Parent**: py

**Type**: Function

**Example**:

**Keywords**:

**Scope**:

#spy._make_history_bars

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.absorption_correctionMetadataHtmlMaker

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.add_affiliation

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.add_crystallisation

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.add_person

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.add_solvent

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.addInstruction

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.addToLocalList

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.AddVariableToUserInputList

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.AnalyseRefinementSource

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.AvailablePlugins

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.AvailableSkins

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.bgcolor

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.bijvoet_differences_NPP

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.bijvoet_differences_scatter_plot

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.calcsolv

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.ccdc_submit

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.change_skin

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.changeBoxColour

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.check_for_selection

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.ChooseLabelContent

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.citationsMetadataHtmlMaker

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.collect

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.collectionMetadataHtmlMaker

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.CompletenessPlot

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.contactLetter

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.CopyVFSFile

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.create_history

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.crystalMetadataHtmlMaker

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.CumulativeIntensityDistribution

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.currentResultFilesHtmlMaker

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.dealWithReportImage

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.delete_history

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.diffractionMetadataHtmlMaker

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.doBanner

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.doProgramSettings

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.downloadTranslation

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.dump

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.EditCifInfo

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.EditGuiItem

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.EditHelpItem

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.EditParams

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.ElementButtonStates

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.example

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.expand

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.ExtractCifInfo

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.fade_in

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.fade_out

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.FindZOfHeaviestAtomInFormua

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.flipsmall

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.Fobs_Fcalc_plot

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.Fobs_over_Fcalc_plot

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.formatted_date_from_timestamp

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.get_cif_item

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.get_news_image_from_server

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.get_refine_ls_hydrogen_treatment

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.get_refinement_methods

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.get_refinement_programs

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.get_solution_methods

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.get_solution_programs

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.get_text_from_vfs

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.GetAvailableRefinementProgs

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.GetAvailableSolutionProgs

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.getCellHTML

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.GetCurrentSelection

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.getFileContents

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.GetFormulaDisplay

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.getGenericSwitchName

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.getGenericSwitchNameTranslation

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.GetHklFileList

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.getListAffiliations

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.getListCrystallisations

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.getListPeople

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.getListSolvents

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.getmap

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.getObjectCount

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.GetOptionalHyphenString

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.GetParam

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.getPersonInfo

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.getPrintStyles

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.getReportExtraCIFItems

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.getReportImageData

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.getReportImageSrc

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.getReportPhilItem

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.getReportTitleSrc

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.GetRInfo

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.getStyles

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.getStylesList

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.GetTag

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.getTemplatesList

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.getTip

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.GetTwinLaw

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.HklStatsAnalysis

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.hooft_analysis

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.InActionButton

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.IsPluginInstalled

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.isPro

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.load_user_gui_phil

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.loadHistory

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.LoadParams

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.LoadStructureParams

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.make_gui_edit_link

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.make_history_bars

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.make_HOS

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.make_reflection_graph

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.make_warning_html

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.MakeActiveGuiButton

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.MakeElementButtonsFromFormula

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.makeFormulaForsNumInfo

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.MakeHoverButton

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.MakeHoverButtonOff

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.MakeHoverButtonOn

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.makeReflectionGraphGui

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.MergeCif

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.move

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.Normal_probability_plot

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.olex_fs_copy

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.OlexBET

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.OlexCctbxMasks

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.OlexCctbxTwinLaws

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.OlexCDS

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.OlexCheckCIF

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.Olexhole

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.OlexMail

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.OlexPlaton

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.on_twin_image_click

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.onRefinementMethodChange

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.onSolutionMethodChange

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.PopBanner

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.popout_history_tree

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.print_top_100

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.progressMetadataHtmlMaker

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.publicationMetadataHtmlMaker

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.QPeaksSlide

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.r1_factor_vs_resolution_plot

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.referenceMetadataHtmlMaker

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.refineDataMaker

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.register_new_odac

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.RemoveVariableFromUserInputList

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.rename_history

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.reset_file_in_OFS

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.reset_twin_law_img

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.resetHistory

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.resize_skin_logo

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.restraint_builder

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.revert_history

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.revert_to_original

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.round_to_n_digits

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.run_MakeMovie

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.RunRefinementPrg

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.runSadabs

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.RunSolutionPrg

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.SaveCifInfo

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.saveHistory

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.SaveStructureParams

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.SaveUserParams

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.scale_factor_vs_resolution_plot

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.set_cif_item

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.set_refinement_program

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.set_solution_program

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.set_source_file

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.setAllMainToolbarTabButtons

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.setDiffractometerDefinitionFile

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.setDisplayQuality

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.SetFormulaFromInput

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.setMainToolbarTabButtons

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.SetMaxCycles

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.SetMaxPeaks

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.SetParam

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.SetReportStyle

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.SetReportTemplate

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.settings_tree

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.ShowParams

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.standardise_path

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.stopDebugging

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.stopShelx

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.StringsAreEqual

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.StringsAreNotEqual

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.students_t_hooft_analysis

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.SwitchAllAlertsOn

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.switchButton

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.symmetry_search

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.SystematicAbsencesPlot

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.test_help_boxes

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.txt

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.UisoSelectSlide

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.weightGuiDisplay

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.which_program

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.WilsonPlot

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.write_to_olex

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.X_Y_plot

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.cif.GetCheckcifReport

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.cif

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.demo.back_demo_item

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.demo

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.demo.cancel_demo_item

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.demo

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.demo.next_demo_item

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.demo

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.demo.run_autodemo

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.demo

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.demo.run_demo_loop

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.demo

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.demo.switch_tab_for_tutorials

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.demo

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.gui.About

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.gui

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.gui.do_sort

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.gui

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.gui.GetFileListCombo

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.gui

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.gui.GetFolderList

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.gui

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.gui.GetPhilChoices

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.gui

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.gui.SetHtmlFontSize

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.gui

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.gui.SetHtmlFontSizeControls

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.gui

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.gui.SwitchPanel

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.gui

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.gui.SwitchSettings

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.gui

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.gui.dialog.FileOpen

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.gui.dialog

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.gui.dialog.FileSave

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.gui.dialog

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.gui.home.multiple_dataset.check

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.gui.home.multiple_dataset

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.gui.home.multiple_dataset.generateHtml

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.gui.home.multiple_dataset

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.gui.images.get_action_button_html

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.gui.images

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.gui.images.GetBitmapSize

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.gui.images

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.gui.images.GetPRImageInstructions

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.gui.images

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.gui.images.GetPSImageInstructions

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.gui.images

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.gui.images.make_action_button_html

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.gui.images

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.gui.images.MakeBitmapImage

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.gui.images

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.gui.maps.MapView

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.gui.maps

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.gui.maps.MaskView

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.gui.maps

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.gui.maps.SetXgridView

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.gui.maps

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.gui.maps.VoidView

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.gui.maps

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.gui.metadata.add_resolved_conflict_item_to_phil

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.gui.metadata

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.gui.metadata.conflicts

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.gui.metadata

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.gui.metadata.sources

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.gui.metadata

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.gui.report.advance_crystal_image

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.gui.report

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.gui.report.get_crystal_image

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.gui.report

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.gui.report.play_crystal_images

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.gui.report

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.gui.report.publication.add_cif_to_merge_list

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.gui.report.publication

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.gui.report.publication.AddTemplateToMergeList

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.gui.report.publication

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.gui.report.publication.DisplayMergeList

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.gui.report.publication

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.gui.report.publication.OnAddNameToAuthorList

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.gui.report.publication

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.gui.report.publication.OnContactAuthorChange

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.gui.report.publication

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.gui.report.publication.OnPersonAffiliationChange

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.gui.report.publication

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.gui.report.publication.OnPersonChange

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.gui.report.publication

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.gui.report.publication.OnPersonInfoChange

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.gui.report.publication

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.gui.report.publication.OnPublicationTemplateChange

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.gui.report.publication

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.gui.report.publication.remove_cif_from_merge_list

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.gui.report.publication

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.gui.tools.checkErrLogFile

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.gui.tools

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.gui.tools.checkPlaton

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.gui.tools

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.gui.tools.flash_gui_control

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.gui.tools

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.gui.tools.hasDisorder

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.gui.tools

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.gui.tools.make_disorder_quicktools

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.gui.tools

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.gui.tools.start_where

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.gui.tools

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.gui.tools.folder_view.generateHtml

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.gui.tools.folder_view

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.gui.tools.folder_view.list

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.gui.tools.folder_view

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.gui.tools.folder_view.loadStructure

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.gui.tools.folder_view

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.history.get

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.history

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.internal.resizeNewsImage

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.internal

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.it.make_pie_graph

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.it

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.it.resize_news_image

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.it

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.it.trim_image

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.it

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.md.export_internal_help

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.md

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.md.run

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.md

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.md.set_book_src

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.md

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.opo.upload_structure

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.opo

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.opo.web_authenticate

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.opo

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.ortepplus.GetStyleList

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.ortepplus

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.ortepplus.run_ortep_with_style

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.ortepplus

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.piltools.make_element_buttons

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.piltools

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.plugins.AskToUpdate

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.plugins

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.plugins.getAvailableModules

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.plugins

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.plugins.getModule

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.plugins

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.plugins.updateKey

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.plugins

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.plugins.gui.doAct

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.plugins.gui

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.plugins.gui.getAction

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.plugins.gui

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.plugins.gui.getCurrentModuleName

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.plugins.gui

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.plugins.gui.getInfo

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.plugins.gui

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.plugins.gui.getModuleList

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.plugins.gui

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.plugins.gui.update

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.plugins.gui

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.programs.get_known

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.programs

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.pt.make_new_plugin

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.pt

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.pt.register_new_module

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.pt

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.r.get_olex2_tables

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.r

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.report.get_crystal_image

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.report

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.report.get_report_title

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.report

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.report.handleNA

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.report

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.report.makeSpecialCifCharacter

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.report

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.report.ResolvePrograms

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.report

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.reportplus.add_to_collection

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.reportplus

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.reportplus.combine

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.reportplus

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.reportplus.edit_text

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.reportplus

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.reportplus.get_collection_structure_image_paths

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.reportplus

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.reportplus.get_single_image

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.reportplus

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.reportplus.GetFileList

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.reportplus

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.reportplus.GetFolderList

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.reportplus

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.reportplus.gui_get_collection_file_list

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.reportplus

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.reportplus.gui_initialise

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.reportplus

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.reportplus.gui_is_initialised

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.reportplus

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.reportplus.gui_on_collection_folder_change

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.reportplus

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.reportplus.gui_on_collection_name_change

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.reportplus

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.reportplus.make_collection_folder

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.reportplus

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.reportplus.make_crystallisation_item

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.reportplus

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.reportplus.make_mounting_item

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.reportplus

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.reportplus.make_new_collection

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.reportplus

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.reportplus.modify_collection

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.reportplus

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.reportplus.save_collection_structure_image_paths

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.reportplus

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.reportplus.set_single_image

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.reportplus

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.reportplus.tex

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.reportplus

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.sc.cell

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.sc

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.sc.combine_all_cifs

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.sc

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.sc.copy_files_from_download_to_location

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.sc

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.sc.dear_author_edit

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.sc

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.sc.get_canned_response_html

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.sc

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.sc.get_cif

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.sc

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.sc.get_cif_item

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.sc

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.sc.get_gui_html

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.sc

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.sc.get_id

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.sc

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.sc.get_local_checkcif_make_html

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.sc

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.sc.get_local_checkcif_run

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.sc

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.sc.get_plugin_path

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.sc

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.sc.get_stats

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.sc

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.sc.insert_canned_response

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.sc

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.sc.make_yagi

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.sc

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.sc.markdown

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.sc

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.sc.pdf_to_text

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.sc

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.sc.run_checks

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.sc

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.sc.strip_refine_special_details

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.sc

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.skin.export_parameters

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.skin

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.tex.hyphenate_iupac

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.tex

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.tex.minus

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.tex

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.threading.joinAll

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.threading

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.threading.shell.run

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.threading.shell

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.xplain.exists

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.xplain

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.xplain.get_output_name

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.xplain

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.xplain.output_exists

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.xplain

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.xplain.run

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy.xplain

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#time.DF

**Arguments**: [none]

**Description**: Returns default date format

**Options**: None

**States**: No requirement

**Parent**: time

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#time.FormatDateTime

**Arguments**: [1 or 2]

**Description**: Formats datatime using default 26 char format or using provided string. Valid formats are y(y(yy) - year like 7, 07 or 2007; M(M(M(M - month like 7, 07, Jul, July; d(d(d(d - day like 1, 01, Wed or Wednesday; h(h - for hours, m(m - minutes, s(s - seconds like 1 or 01

**Options**: None

**States**: No requirement

**Parent**: time

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#time.Now

**Arguments**: [none or 1]

**Description**: Returns current date and time as a long number if no format is provided. If a format string is provided it return a formatted string. The DF() function can be used for default formatting

**Options**: None

**States**: No requirement

**Parent**: time

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#xf.CurrentData

**Arguments**: [none or 1]

**Description**: Returns current data index or changes current data block within the CIF

**Options**: None

**States**: CIF file is expected

**Parent**: xf

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#xf.DataCount

**Arguments**: [none]

**Description**: Returns number of available data sets

**Options**: None

**States**: Loaded file is expected

**Parent**: xf

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#xf.DataName

**Arguments**: [1]

**Description**: Returns data name for given CIF block

**Options**: None

**States**: CIF file is expected

**Parent**: xf

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#xf.GetFormula

**Arguments**: [none, 1 or 2]

**Description**: Returns a string for content of the asymmetric unit. Takes single or none parameters. If parameter equals \'html\' and html formatted string is returned, for \'list\' parameter a string like \'C:26,N:45\' is returned. If no parameter is specified, just formula is returned

**Options**: None

**States**: Loaded file is expected

**Parent**: xf

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#xf.GetMu

**Arguments**: [none]

**Description**: Changes current data block within the CIF

**Options**: None

**States**: Loaded file is expected

**Parent**: xf

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#xf.SaveSolution

**Arguments**: [1]

**Description**: Saves current Q-peak model to provided file (res-file)

**Options**: None

**States**: INS file is expected

**Parent**: xf

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#xf.SetFormula

**Arguments**: [1] [P4P file is expected]

**Description**: Sets formula for current file, takes a string of the following form \'C:25,N:4\'

**Options**: None

**States**: INS file is expected

**Parent**: xf

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#xf.analysis.AnalyseUeq

**Arguments**: [none or 1]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: xf.analysis

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#xf.analysis.Scale

**Arguments**: [none or 1]

**Description**: Scales the Q-peaks according to found fragments.Returns the scale or 0

**Options**: None

**States**: No requirement

**Parent**: xf.analysis

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#xf.analysis.Trim

**Arguments**: [none or 1]

**Description**: Trims the size of the assymetric unit according to the 18 A^3 rule.Returns true if any atoms were deleted

**Options**: None

**States**: No requirement

**Parent**: xf.analysis

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#xf.au.Fractionalise

**Arguments**: [1 or 3]

**Description**: Returns fractional coordinates

**Options**: None

**States**: No requirement

**Parent**: xf.au

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#xf.au.GetAtomAfix

**Arguments**: [1]

**Description**: Returns atom AFIX

**Options**: None

**States**: No requirement

**Parent**: xf.au

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#xf.au.GetAtomCount

**Arguments**: [none]

**Description**: Returns the atom count in the asymmetric unit

**Options**: None

**States**: No requirement

**Parent**: xf.au

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#xf.au.GetAtomCrd

**Arguments**: [1]

**Description**: Returns a comma separated list of fractional coordinates for the specified atom

**Options**: None

**States**: No requirement

**Parent**: xf.au

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#xf.au.GetAtomlabel

**Arguments**: [2]

**Description**: The takes two arguments - the atom ID and increment. The increment is used to navigate through the periodic table, so increment +1 will return next element and -1 the previous element in the periodic table

**Options**: None

**States**: No requirement

**Parent**: xf.au

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#xf.au.GetAtomName

**Arguments**: [1]

**Description**: Returns atom label

**Options**: None

**States**: No requirement

**Parent**: xf.au

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#xf.au.GetAtomOccu

**Arguments**: [1]

**Description**: Returns atom occupancy

**Options**: None

**States**: No requirement

**Parent**: xf.au

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#xf.au.GetAtomType

**Arguments**: [1]

**Description**: Returns atom type (element)

**Options**: None

**States**: No requirement

**Parent**: xf.au

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#xf.au.GetAtomU

**Arguments**: [1]

**Description**: Returns a single number or six, comma separated values

**Options**: None

**States**: No requirement

**Parent**: xf.au

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#xf.au.GetAtomUiso

**Arguments**: [1]

**Description**: Returns a single number Uiso or (U11+U22+U33)/3

**Options**: None

**States**: No requirement

**Parent**: xf.au

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#xf.au.GetCell

**Arguments**: [none or 1]

**Description**: Returns six comma separated values for a, b, c and alpha, beta, gamma

**Options**: None

**States**: No requirement

**Parent**: xf.au

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#xf.au.GetCellSymm

**Arguments**: [none or 1]

**Description**: Returns space group of currently loaded file as name: \'C2\', \'I41/amd\', etc. Optionally, Hall symbol may be returned if \'hall\' is provided as an argument

**Options**: None

**States**: No requirement

**Parent**: xf.au

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#xf.au.GetCellVolume

**Arguments**: [none]

**Description**: Returns volume of the unit cell

**Options**: None

**States**: No requirement

**Parent**: xf.au

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#xf.au.GetFormula

**Arguments**: [none]

**Description**: Returns chemical formula of the asymmetric unit

**Options**: None

**States**: No requirement

**Parent**: xf.au

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#xf.au.GetPeak

**Arguments**: [1]

**Description**: Returns peak intensity

**Options**: None

**States**: No requirement

**Parent**: xf.au

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#xf.au.GetVolume

**Arguments**: [none]

**Description**: Returns volume of the unit cell divided by the number of symmetry elements

**Options**: None

**States**: No requirement

**Parent**: xf.au

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#xf.au.GetWeight

**Arguments**: [none or 1]

**Description**: Returns molecular mass of the asymmetric unit

**Options**: None

**States**: No requirement

**Parent**: xf.au

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#xf.au.GetZ

**Arguments**: [none]

**Description**: Returns current Z

**Options**: None

**States**: No requirement

**Parent**: xf.au

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#xf.au.GetZprime

**Arguments**: [none]

**Description**: Returns current Z divided byt the number of matrices of current spacegroup

**Options**: None

**States**: No requirement

**Parent**: xf.au

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#xf.au.IsAtomDeleted

**Arguments**: [1]

**Description**: Checks status of specified atom

**Options**: None

**States**: No requirement

**Parent**: xf.au

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#xf.au.IsPeak

**Arguments**: [1]

**Description**: Checks if specified atom is  peak

**Options**: None

**States**: No requirement

**Parent**: xf.au

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#xf.au.NewAtom

**Arguments**: [4]

**Description**: Adds a new atom to the asymmetric unit and return its ID, by which it can be referred. The function takes the atom name and coordinates, if -1 is returned, the atom is not created

**Options**: None

**States**: No requirement

**Parent**: xf.au

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#xf.au.NPDCount

**Arguments**: [none]

**Description**: Returns number of the NPD atoms

**Options**: None

**States**: No requirement

**Parent**: xf.au

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#xf.au.Orthogonalise

**Arguments**: [1 or 3]

**Description**: Returns orthogonalised coordinates

**Options**: None

**States**: No requirement

**Parent**: xf.au

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#xf.au.SetAtomCrd

**Arguments**: [4]

**Description**: Sets atom coordinates to specified values, first parameters is the atom ID

**Options**: None

**States**: No requirement

**Parent**: xf.au

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#xf.au.SetAtomlabel

**Arguments**: [2]

**Description**: Sets atom labels to provided value. The first parameter is the atom ID

**Options**: None

**States**: No requirement

**Parent**: xf.au

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#xf.au.SetAtomOccu

**Arguments**: [2]

**Description**: Sets atom\'s occupancy; first parameter is the atom ID followed by occupancy

**Options**: None

**States**: No requirement

**Parent**: xf.au

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#xf.au.SetAtomU

**Arguments**: [2 or 7]

**Description**: Sets atoms Uiso/anis first paramater is the atom ID followed by 1 or six parameters

**Options**: None

**States**: No requirement

**Parent**: xf.au

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#xf.au.SetZ

**Arguments**: [1]

**Description**: Sets current Z. Does not update content or whatsoever

**Options**: None

**States**: No requirement

**Parent**: xf.au

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#xf.au.SetZprime

**Arguments**: [1]

**Description**: Sets Z\' for the structure

**Options**: None

**States**: No requirement

**Parent**: xf.au

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#xf.exptl.Radiation

**Arguments**: [none or 1]

**Description**: Returns/sets experiment wavelength in angstrems

**Options**: None

**States**: No requirement

**Parent**: xf.exptl

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#xf.exptl.Size

**Arguments**: [none or 1]

**Description**: Returns/sets crystal size. Returns/accepts strings line 0.5x0.5x0.5 (in mm)

**Options**: None

**States**: No requirement

**Parent**: xf.exptl

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#xf.exptl.Temperature

**Arguments**: [none or 1]

**Description**: Returns/sets experiment temperature. Returns value in C, accepts strings like 120K, 10F. Default scale is C

**Options**: None

**States**: No requirement

**Parent**: xf.exptl

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#xf.latt.GetFragmentAtoms

**Arguments**: [1]

**Description**: Returns a comma separated list of atoms in specified fragment

**Options**: None

**States**: No requirement

**Parent**: xf.latt

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#xf.latt.GetFragmentCount

**Arguments**: [none]

**Description**: Returns number of fragments in the lattice

**Options**: None

**States**: No requirement

**Parent**: xf.latt

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#xf.latt.GetMoiety

**Arguments**: [none]

**Description**: Returns molecular moiety

**Options**: None

**States**: No requirement

**Parent**: xf.latt

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#xf.latt.IsGrown

**Arguments**: [none]

**Description**: Returns true if the structure is grow

**Options**: None

**States**: No requirement

**Parent**: xf.latt

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#xf.rm.Completeness

**Arguments**: [1]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: xf.rm

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#xf.rm.Exti

**Arguments**: [none, 1 or 2]

**Description**: Returns/sets EXTI

**Options**: None

**States**: No requirement

**Parent**: xf.rm

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#xf.rm.FVar

**Arguments**: [1 or 2]

**Description**: Returns/sets FVAR referred by index

**Options**: None

**States**: No requirement

**Parent**: xf.rm

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#xf.rm.HasOccu

**Arguments**: [none]

**Description**: Returns true if occupancy of any of the atoms is refined or deviates from 1

**Options**: None

**States**: No requirement

**Parent**: xf.rm

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#xf.rm.OSF

**Arguments**: [none or 1]

**Description**: Returns/sets OSF

**Options**: None

**States**: No requirement

**Parent**: xf.rm

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#xf.rm.UpdateCR

**Arguments**: [any except none, 1 or 2]

**Description**: Updates constraint or restraint parameters (name, index, {values})

**Options**: None

**States**: No requirement

**Parent**: xf.rm

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#xf.uc.CellEx

**Arguments**: [1]

**Description**: Returns unit cell side/angle with esd

**Options**: None

**States**: No requirement

**Parent**: xf.uc

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#xf.uc.MatrixCount

**Arguments**: [none]

**Description**: Returns the number of matrices in the unit cell

**Options**: None

**States**: No requirement

**Parent**: xf.uc

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#xf.uc.VolumeEx

**Arguments**: [none]

**Description**: Returns unit cell volume with esd

**Options**: None

**States**: No requirement

**Parent**: xf.uc

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#xgrid.Contours

**Arguments**: [none or 1]

**Description**: Returns/sets number of contour levels

**Options**: None

**States**: No requirement

**Parent**: xgrid

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#xgrid.Depth

**Arguments**: [none, 1 or 3]

**Description**: Returns/sets current depth

**Options**: None

**States**: No requirement

**Parent**: xgrid

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#xgrid.Extended

**Arguments**: [none, 1 or 6]

**Description**: Returns/sets extended size of the grid

**Options**: None

**States**: No requirement

**Parent**: xgrid

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#xgrid.GetMax

**Arguments**: [none]

**Description**: Returns maximum value of the map

**Options**: None

**States**: No requirement

**Parent**: xgrid

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#xgrid.GetMin

**Arguments**: [none]

**Description**: Returns minimum value of the map

**Options**: None

**States**: No requirement

**Parent**: xgrid

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#xgrid.GetName

**Arguments**: [none]

**Description**: Returns object collection name

**Options**: None

**States**: No requirement

**Parent**: xgrid

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#xgrid.IsGrouped

**Arguments**: [none]

**Description**: Returns true if the object is in a group

**Options**: None

**States**: No requirement

**Parent**: xgrid

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#xgrid.IsSelected

**Arguments**: [none]

**Description**: Returns true if the object is selected

**Options**: None

**States**: No requirement

**Parent**: xgrid

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#xgrid.IsValid

**Arguments**: [none or 1]

**Description**: Returns true if grid data is initialised

**Options**: None

**States**: No requirement

**Parent**: xgrid

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#xgrid.MaxDepth

**Arguments**: [none]

**Description**: Returns maximum available depth

**Options**: None

**States**: No requirement

**Parent**: xgrid

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#xgrid.PlaneSize

**Arguments**: [none or 1]

**Description**: Returns/sets current size

**Options**: None

**States**: No requirement

**Parent**: xgrid

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#xgrid.RenderMode

**Arguments**: [none or 1]

**Description**: Returns/sets grid rendering mode. Supported values: point, line, fill, plane, contour

**Options**: None

**States**: No requirement

**Parent**: xgrid

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#xgrid.Scale

**Arguments**: [none or 1]

**Description**: Returns/sets current scale

**Options**: None

**States**: No requirement

**Parent**: xgrid

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#xgrid.Size

**Arguments**: [none or 1]

**Description**: Returns/sets current size

**Options**: None

**States**: No requirement

**Parent**: xgrid

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#xgrid.Visible

**Arguments**: [none or 1]

**Description**: Changes/returns object visibility

**Options**: None

**States**: No requirement

**Parent**: xgrid

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#xgrid.label.GetName

**Arguments**: [none]

**Description**: Returns object collection name

**Options**: None

**States**: No requirement

**Parent**: xgrid.label

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#xgrid.label.IsGrouped

**Arguments**: [none]

**Description**: Returns true if the object is in a group

**Options**: None

**States**: No requirement

**Parent**: xgrid.label

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#xgrid.label.IsSelected

**Arguments**: [none]

**Description**: Returns true if the object is selected

**Options**: None

**States**: No requirement

**Parent**: xgrid.label

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#xgrid.label.Visible

**Arguments**: [none or 1]

**Description**: Changes/returns object visibility

**Options**: None

**States**: No requirement

**Parent**: xgrid.label

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#xgrid.legend.GetName

**Arguments**: [none]

**Description**: Returns object collection name

**Options**: None

**States**: No requirement

**Parent**: xgrid.legend

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#xgrid.legend.IsGrouped

**Arguments**: [none]

**Description**: Returns true if the object is in a group

**Options**: None

**States**: No requirement

**Parent**: xgrid.legend

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#xgrid.legend.IsSelected

**Arguments**: [none]

**Description**: Returns true if the object is selected

**Options**: None

**States**: No requirement

**Parent**: xgrid.legend

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#xgrid.legend.Visible

**Arguments**: [none or 1]

**Description**: Changes/returns object visibility

**Options**: None

**States**: No requirement

**Parent**: xgrid.legend

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#MACROS
#/

**Arguments**: [any] [any options]

**Description**: Add command to the ins file

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#@Close

**Arguments**: [none]

**Description**: Closes currently loaded file

**Options**: None

**States**: Loaded file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#@py

**Arguments**: [any];

**Description**: Runs provided python lines \'\n\' is used as new line separator or shows a text input window

**Options**:

- *i*: shows a text input box

- *l*: loads a file into a text input box



**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#@reap

**Arguments**: [any];

**Description**: This macro loads a file if provided as an argument. If no argument is provided, it shows a file open dialog

**Options**:

- ***: read and overlay

- *b*: blind

- *r*: also relaod the default style



**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#@update

**Arguments**: [any]

**Description**: Reads given file and if the atoms list of loaded file matches the atom list of the given file the atomic coordinates, FVAR and BASF values are updated.

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#_anisotropic

**Arguments**: [any] [any options]

**Description**: Make atoms anisotropic

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#_defaultw

**Arguments**: [any] [any options]

**Description**: Change the output to white default

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#_get

**Arguments**: [any] [any options]

**Description**: Get a structure from the dimas database

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#_isotropic

**Arguments**: [any] [any options]

**Description**: Make atoms isotropic

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#_reap_li

**Arguments**: [any] [any options]

**Description**: Load in listening mode

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#_reapa

**Arguments**: [any] [any options]

**Description**: Load a Crystallographic File for Autosolve

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#_report

**Arguments**: [any] [any options]

**Description**: Create Reports

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#_table

**Arguments**: [any] [any options]

**Description**: Create Tables

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#_tutorial

**Arguments**: [any] [any options]

**Description**: Starts the Tutorials

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#_xphadd

**Arguments**: [any] [any options]

**Description**: Run XP to do HADD

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Abort

**Arguments**: [none]

**Description**: \'abort\' statement to terminate a macro execution

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#AddBond

**Arguments**: [any]

**Description**: Adds specified bond to the connectivity table

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#AddIns

**Arguments**: [any except none]

**Description**: Adds an instruction to the INS file

**Options**: None

**States**: INS file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#AddLabel

**Arguments**: [3 or 5]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#AddObject

**Arguments**: [any except none or 1]

**Description**: Adds a new user defined object to the graphical scene

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#AddSE

**Arguments**: [any except none]

**Description**: Tries to add a new symmetry element to current space group to form a new one. [-1] is for center of symmetry

**Options**: None

**States**: Loaded file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#ADPDisp

**Arguments**: [2]

**Description**: Compares two structures in the terms of atomsic dispacement after the structure optimisation and the experimental ADP. First structure is the XRay experimental structure and the second is the optimised one. The structures are expected to have identical labelling scheme.

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#ADS

**Arguments**: [any except none]

**Description**: Changes atom draw style [sph,elp,std]

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Afix

**Arguments**: [any except none] ;

**Description**: sets atoms afix, special cases are 56,69,66,69,76,79,106,109,116 and 119

**Options**:

- *n*: to accept N atoms in the rings for afix 66



**States**: INS file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Anis

**Arguments**: [any] ;

**Description**: Makes provided atoms anisotropic if no arguments provided current selection or all atoms are considered

**Options**:

- *h*: adds hydrogen atoms



**States**: Loaded file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#ARad

**Arguments**: [any except none]

**Description**: Changes how the atoms are drawn [sfil - sphere packing, pers - static radii, isot - radii proportional to Ueq, isoth - as isot, but applied to H atoms as well]

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#ASR

**Arguments**: [none]

**Description**: Absolute structure refinement: adds TWIN and BASF to current model in the case of non-centrosymmetric structure

**Options**: None

**States**: Loaded file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#AtomInfo

**Arguments**: [any]

**Description**: Searches information for given atoms in the database

**Options**: None

**States**: Loaded file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#atreap_fader

**Arguments**: [any] [any options]

**Description**: Load a Crystallographic File

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#atreap_no_fader

**Arguments**: [any] [any options]

**Description**: Load a Crystallographic File

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#autorefine

**Arguments**: [any] [any options]

**Description**: Refines only if the user.auto_refine_after_anis parameter is set to True

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#AZoom

**Arguments**: [any except none]

**Description**: Modifies given atoms [all] radius. The first argument is the new radius in %

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Bang

**Arguments**: [any] ;

**Description**: Prints bonds and angles table for selected/given atoms

**Options**:

- *c*: copy info to the clipboard



**States**: Loaded file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Basis

**Arguments**: [none or 1]

**Description**: Shows/hides the orientation basis

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Bind

**Arguments**: [2]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#BRad

**Arguments**: [any except none];

**Description**: Multiplies provided [all] bonds default radius by given number. The default radius for covalent bonds is 0.1A and for H-bonds is 0.02A. To set radius for H-bonds use:
	brad R hbonds
Any particula bond type can also be specified like:
	brad 0.5 C-H
Note that the heavier atom type is always first

**Options**:

- *a*: specified value is absolute, in A



**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#bw

**Arguments**: [any] [any options]

**Description**: Change the output to Black and White

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#CalcCHN

**Arguments**: [none or 1]

**Description**: Calculates CHN composition of current structure or for provided formula

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#CalcFourier

**Arguments**: [none] ;

**Description**: Calculates fourier map

**Options**:

- *calc*: calculates calculated map

- *diff*: calculates difference map

- *fcf*: reads structure factors from a fcf file

- *i*: integrates the map

- *m*: mask the structure

- *obs*: calculates observed map

- *r*: resolution in Angstrems

- *scale*: scale to use for difference maps, currently available simple(s) sum(Fo^2)/sum(Fc^2)) and regression(r)

- *tomc*: calculates 2Fo-Fc map



**States**: Loaded file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#CalcMass

**Arguments**: [none or 1]

**Description**: Calculates Mass spectrum of current structure or for provided formula

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#calcms

**Arguments**: [any] [any options]

**Description**: Calculate Mass Spectrum

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#CalcPatt

**Arguments**: [none]

**Description**: Calculates Patterson map

**Options**: None

**States**: Loaded file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#CalcVoid

**Arguments**: [none or 1] ;

**Description**: Calculates solvent accessible void and packing parameters; optionally accepts a file with space separated values of Atom Type and radius, an entry a line

**Options**:

- *d*: distance from Van der Waals surface [0]

- *i*: invert the map for rendering

- *p*: precise calculation

- *r*: resolution[0.2]



**States**: Loaded file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#CalcVol

**Arguments**: [none or 1];

**Description**: Calculates tetrahedron or bipyramidal shape volume for given (selected) atom

**Options**:

- *cs*: do not clear the selection

- *n*: normalises bonds before the calculation



**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Capitalise

**Arguments**: [any except none]

**Description**: Changes atom labels capitalisation for all/given/selected atoms. The first argument is the template like Aaaa

**Options**: None

**States**: Loaded file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Ceiling

**Arguments**: [1]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Cell

**Arguments**: [none or 1] ;

**Description**: If no arguments provided inverts visibility of unit cell, otherwise sets it to the boolean value of the parameter

**Options**:

- *r*: shows reciprocal cell



**States**: Loaded file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Cent

**Arguments**: [any];

**Description**: Creates a centroid for given/selected/all atoms

**Options**:

- *rings*: finds rings specified by template and add centroids for each of them. For example cent -rings=C6



**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Center

**Arguments**: [any] ;

**Description**: Sets the centre of rotation to given point

**Options**:

- *z*: also recalculates the scene zoom



**States**: Loaded file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#ChangeSG

**Arguments**: [any except none] ;

**Description**: [shift] SG. Changes space group of current structure, applying given shit prior (if provided) to the change of symmetry of the unit cell

**Options**:

- *c*: apply cell change according to the centering change (experimental!)



**States**: Loaded file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#changesgs

**Arguments**: [any] [any options]

**Description**: Changes the space group settings

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#CheckMenu

**Arguments**: [1]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#ChemDraw

**Arguments**: [any]

**Description**: Currently only creates aromatic rings for Ph, Py and Cp rings

**Options**: None

**States**: Loaded file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Chiv

**Arguments**: [any] ;

**Description**: Restrains chiral volume of atom(s) to \'0\' or provided value

**Options**:

- *cs*:  do not clear selection



**States**: INS file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Cif2Doc

**Arguments**: [none or 1] ;

**Description**: converts cif to a document

**Options**:

- *n*: output file name



**States**: Loaded file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Cif2Tab

**Arguments**: [any] ;

**Description**: creates a table from a cif

**Options**:

- *n*: output file name

- *t*: table definition file



**States**: Loaded file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#CifCreate

**Arguments**: [none]

**Description**: Creates cif from current file, variance-covariance matrix should be available

**Options**: None

**States**: Loaded file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#CifExtract

**Arguments**: [1 or 2] ;

**Description**: extract a list of items from one cif to another

**Options**:

- *i*: a custom CIF with items to extract [etc/CIF/extract.cif]



**States**: Loaded file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#cifm

**Arguments**: [any] [any options]

**Description**: Get customised Data from SMART

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#CifMerge

**Arguments**: [any] ;

**Description**: Merges loaded or provided as first argument cif with other cif(s)

**Options**:

- *f*: creates final CIF with embedded RES file and HKL loop

- *u*: updates atom treatment if the asymmetric units of currently loaded file and of the CIF file match



**States**: Loaded file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Clean

**Arguments**: [none];

**Description**: Tidies up current model

**Options**:

- *aq*: disables analysis of the Q-peaks based on thresholds

- *at*: disables lonely atom types assignment to O and Cl

- *d*: before 'blown up' atoms, a possibility to demote will be checked

- *f*: does not run 'fuse' after the completion

- *npd*: promotes at maximum given number of atoms a call [0]



**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Clear

**Arguments**: [none]

**Description**: Clears console buffer (text)

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Close

**Arguments**: [any] [any options]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Collectivise

**Arguments**: [any]

**Description**: Does the opposite to the Individialise. If provided atoms are unique to the lattice a call to this function makes them uniq to the asymmetric unit, the following call makes the uniq to the element type

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Compaq

**Arguments**: [none] ;

**Description**: Moves all atoms or fragments of the asymmetric unit as close to each other as possible. If no options provided, all fragments are assembled around the largest one.

**Options**:

- *a*: assembles broken fragments

- *c*: similar as with no options, but considers atom-to-atom distances

- *m*: assembles non-metallic parts of the structure first, then moves metals to the closest atom

- *q*: moves Q-peaks to the atoms, atoms are not affected



**States**: Loaded file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#completeness

**Arguments**: [any] [any options]

**Description**: Calculates and displays a completeness plot

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#CONF

**Arguments**: [any] ;

**Description**: Adds dihedral angle calculation instructions to create corresponding tables in the CIF

**Options**:

- *a*: finds angles which made up of all given/selected atoms [true]



**States**: Loaded file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Conn

**Arguments**: [any except none]

**Description**: Changes provided atom(s) connectivity (only until next connectivity modifying operation for now).
Usage: conn max_bond bonding_radius [selection/atom(s)/$type]
Usage: conn max_bond [selection/atom(s)/$type]
Usage: conn bonding_radius [selection/atom(s)/$type] - note the radius should have floating point

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Constrain

**Arguments**: [any except none]

**Description**: Creates a constraint

**Options**: None

**States**: Loaded file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#CreateBitmap

**Arguments**: [2];

**Description**:

**Options**:

- *r*:



**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#CreateMenu

**Arguments**: [1, 2 or 3];

**Description**:

**Options**:

- *c*:

- *m*:

- *r*:

- *s*:



**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#CreateShortcut

**Arguments**: [2]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#cumulative_intensity

**Arguments**: [any] [any options]

**Description**: Calculates and displays the cumulative intensity distribution

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#custom_on_report

**Arguments**: [any] [any options]

**Description**: dummy definition

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Dang

**Arguments**: [any] ;

**Description**: Adds a ShelX compatible angle restraint

**Options**:

- *cs*: do not clear selection



**States**: INS file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#default

**Arguments**: [any] [any options]

**Description**: Change the style to default

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#defaultu

**Arguments**: [any] [any options]

**Description**: Change current style to default (for some broken graphics drivers on Ubuntu)

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Degen

**Arguments**: [any] ;

**Description**: Prints how many symmetry operators put given atom to the same site

**Options**:

- *cs*: clear selection



**States**: Loaded file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#DelBond

**Arguments**: [any]

**Description**: Removes specified bond from the connectivity table

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#DeleteBitmap

**Arguments**: [1]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#DeleteMenu

**Arguments**: [1]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#DelIns

**Arguments**: [1]

**Description**: A number or the name (will remove all accurances) can be provided

**Options**: None

**States**: INS file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#DelObject

**Arguments**: [1]

**Description**: Deletes graphical object by name

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Delta

**Arguments**: [none or 1]

**Description**: Prints/sets current delta fir the covalent bonds

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#DeltaI

**Arguments**: [none or 1]

**Description**: Prints/sets current delta for short interactions

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#DELU

**Arguments**: [any] ;

**Description**: Rigid bond constraint. If no atoms provided, all non-H atoms considered

**Options**:

- *cs*: do not clear selection



**States**: INS file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Describe

**Arguments**: [none]

**Description**: Describes current refinement in a human readable form

**Options**: None

**States**: Loaded file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Dfix

**Arguments**: [any];

**Description**: Restrains distancesto the given value

**Options**:

- *cs*: do not clear selection

- *e*:



**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Dir

**Arguments**: [none or 1]

**Description**: Lists current folder. A file name mask may be provided

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#dire

**Arguments**: [any] [any options]

**Description**: Opens the current directory in Explorer

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Direction

**Arguments**: [none]

**Description**: Prints current orientation of the model in factional coordinates

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#dires

**Arguments**: [any] [any options]

**Description**: open the directory using explorer

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#DisableMenu

**Arguments**: [1]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#EADP

**Arguments**: [any]

**Description**: Forces EADP/Uiso of provided atoms to be constrained the same

**Options**: None

**States**: INS file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Echo

**Arguments**: [any];

**Description**: Prints provided string, functions are evaluated before printing

**Options**:

- *c*: copy printed information to clipboard

- *m*: the printing color (info, warning, error or exceptiion)



**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#edit

**Arguments**: [any] [any options]

**Description**: Launches notepad for the file with name of current file and extension passed as parameter

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#EditAtom

**Arguments**: [any] ;

**Description**: Shows information for the given atom and all of its dependents

**Options**:

- *cs*: do not clear the selection



**States**: Loaded file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#EditIns

**Arguments**: [none]

**Description**:

**Options**: None

**States**: INS file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#EditMaterial

**Arguments**: [1]

**Description**: Brings up material properties dialog for specified object

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#edt

**Arguments**: [any] [any options]

**Description**: Edits a particular atom

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#edthelp

**Arguments**: [any] [any options]

**Description**: Invokes the help editor

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Elevate

**Arguments**: [none or 1]

**Description**: Runs Olex2 in elevated/desktop mode [true]/false- only available on Windows

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#emf

**Arguments**: [any] [any options]

**Description**: Edit a custom macro file

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#EnableMenu

**Arguments**: [1]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Envi

**Arguments**: [none, 1 or 2];

**Description**: This macro prints environment of any particular atom. Default search radius is 2.7A.

**Options**:

- *c*: prints just the connectivity information

- *cs*: leaves selection unchanged

- *h*: adds hydrogen atoms to the list

- *p*: print out precision [2], the angle printing precision will be half of that for the distances

- *q*: adds Q-peaks to the list



**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Esd

**Arguments**: [any] ;

**Description**: This procedure calculates possible parameters for the selection and evaluates their esd using the variance-covariance matrix coming from the ShelXL refinement with negative \'MORE\' like \'MORE -1\' option or from the olex2.refine

**Options**:

- *c*: copies printed values to the clipboard

- *l*: consider the list of bonds as independent

- *label*: creates a graphics label



**States**: Loaded file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Exec

**Arguments**: [any except none];

**Description**: Executes external process

**Options**:

- *d*: output dub file name

- *o*: detached

- *q*: do not post output to console

- *s*: synchronise

- *t*: a list of commands to be run when the process is terminated



**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Exit

**Arguments**: [none]

**Description**: Exits Olex2

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#expand

**Arguments**: [any] [any options]

**Description**: Expands sequence from given start, end labels and optional increment

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Export

**Arguments**: [none or 1]

**Description**: Exports reflections file and RES if present in the loaded CIF

**Options**: None

**States**: CIF file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#ExportFont

**Arguments**: [2]

**Description**: Exports given fonts into Olex2 portable format. At maximum two fonts a file are supported: a fixed and a proportional font. Example: ExportFont ChooseFont()&ChooseFont test.fnt

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#ExportFrag

**Arguments**: [none]

**Description**: Exports selected fragment to an external file

**Options**: None

**States**: Loaded file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#external_edit

**Arguments**: [any] [any options]

**Description**: Open file in an external text editor

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#EXYZ

**Arguments**: [any] ;

**Description**: Adds a new element to the given/selected site. Takes one selected atom and element types as any subsequent argument. Alternatively can take a few selected atoms of different type to be modelled as the type swapping disorder or a set of atoms of the same type and new element type on the command line.

**Options**:

- *eadp*: does not set the equivalent ADP constraint for the shared site



**States**: INS file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Fade

**Arguments**: [3]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#FcfCreate

**Arguments**: [any except none] ;

**Description**: Creates fcf from current file. Expects a number as in the shelx list number as the first argument, the second argument is the output file name filename().fcf is default

**Options**:

- *scale*: [external],simple or regression



**States**: Loaded file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#File

**Arguments**: [none or 1] ;

**Description**: Saves current model to a file. By default an ins file is saved and loaded

**Options**:

- *s*: sort the main residue of the asymmetric unit



**States**: Loaded file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#FitCHN

**Arguments**: [any except none or 1]

**Description**: Fits CHN analysis for given formula and observed data given a lits of possible solvents. A mixture of up to 3 solvents only considered, however any number of observed elements can be provided. Example: FitCHN C12H22O11 C:40.1 H:6 N:0 H2O CCl3H

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Fix

**Arguments**: [any except none]

**Description**: Fixes specified parameters of atoms: XYZ, Uiso, Occu

**Options**: None

**States**: INS file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#FixHL

**Arguments**: [none]

**Description**: Fixes hydrogen atom labels

**Options**: None

**States**: Loaded file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#FixUnit

**Arguments**: [none or 1]

**Description**: Sets SFAc and UNIT to current content of the asymmetric unit. Takes Z\', with default value of 1.

**Options**: None

**States**: Loaded file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Flat

**Arguments**: [any] ;

**Description**: Flat group restraint for at least 4 provided atoms

**Options**:

- *cs*: do not clear selection



**States**: INS file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Flush

**Arguments**: [none, 1 or 2]

**Description**:

#1
Flushes log streams
#2
An extension to \'flush log\' to \'flush output\' to flush console buffer into DataDir()/[output.txt] file, the file name can follow the command

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#FlushFS

**Arguments**: [none or 1]

**Description**: Saves current content of the virtual file system. If no parameters is given - the global state is saved. Possible arguments: global, structure

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Fmol

**Arguments**: [none]

**Description**: Shows all fragments (as opposite to uniq)

**Options**: None

**States**: Loaded file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#fobs_fcalc

**Arguments**: [any] [any options]

**Description**: Calculates and displays an Fobs vs Fcalc plot

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#fobs_over_fcalc

**Arguments**: [any] [any options]

**Description**: Calculates and displays a plot of Fobs/Fcalc vs resolution

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Focus

**Arguments**: [none]

**Description**: Sets input focus to the console

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Free

**Arguments**: [any except none]

**Description**: Frees specified parameters of atoms: XYZ, Uiso, Occu

**Options**: None

**States**: INS file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Fuse

**Arguments**: [none or 1]

**Description**: Re-initialises the connectivity list. If a number is provided, atoms of the same type connected by bonds shorter than the provided number are merged into one atom with center at the centroid formed by all removed atoms

**Options**: None

**States**: Loaded file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Fvar

**Arguments**: [any]

**Description**: Assigns/release occupancy for given atoms. Examples:
-\'fvar\' if nothing is selected will print current values of the variables. For a selection of even number atoms, will create a new variable and link occupancies of the first half of the selection to occupancy the other half of the selection.
-\'fvar 0\' - makes occupancy of provided atoms refineable
-\'fvar 1\' - fixes occupancy of provided atoms at current value
-\'fvar 1 1\' - fixes occupancy of provided atoms at chemical occupancy of 1
-\'fvar 2\' will link occupancy of the given atoms to the value of the 2nd FVAR multiplied by current value of the occupancy of the given atoms, or, if occupancy already linked to a variable - it will replace the variable index.
-\'fvar 2 0.5\' will link occupancy of the given atoms to the value of the 2nd FVAR multiplied by 0.5.

**Options**: None

**States**: INS file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#g3

**Arguments**: [any] [any options]

**Description**: Switch to Gui3

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#g4

**Arguments**: [any] [any options]

**Description**: Switch to Gui4

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#GenDisp

**Arguments**: [none or 1] ;

**Description**: Generates anisotropic dispertion parameters for current radiation wavelength

**Options**:

- *f*: generates full SFAC instructions

- *n*: for neutron data



**States**: Loaded file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#getAutoChem

**Arguments**: [any] [any options]

**Description**: Get AutoChem

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#GetParam

**Arguments**: [any] [any options]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Grad

**Arguments**: [none, 1 or 4];

**Description**: Sets options for the background gradient. No options - showsn the gradient dialog where the user can choose the gradient colors. One parameter is expected to be a boolean - shows/hides the gradient. Four parameters specify the gradient colours explicetly.

**Options**:

- *i*: toggles gradient mode and the user/white background

- *p*: sets/removes the gradient picture, the picture is assumed to have power of 2 dimensions (like 512x256), it is stretched if needed



**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#GraphPD

**Arguments**: [none] ;

**Description**: Prints a intensity vs. 2 theta graph

**Options**:

- *fcf*: take structure factors from the FCF file, otherwise calculate from current model

- *r*: resolution in degrees [0.5]

- *s*: use simple scale when calculating structure factors from the mode, otherwise regression scaling will be used



**States**: Loaded file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#GraphSR

**Arguments**: [none or 1] ;

**Description**: Prints a scale vs resolution graph for current file (fcf file must exist in current folder)

**Options**:

- *b*: number of bins



**States**: Loaded file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Group

**Arguments**: [none or 1] ;

**Description**: Groups current visible objects or selection

**Options**:

- *n*: a custom name can be provided



**States**: Loaded file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Grow

**Arguments**: [any] ;

**Description**: Grows whole structure or provided atoms only

**Options**:

- *b*: grows all visible grow bonds (when in a grow mode)

- *s*: grow shells vs fragments

- *t*: grows only provided atoms/atom types

- *w*: grows the rest of the structure, using already applied generators



**States**: Loaded file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#gui2

**Arguments**: [any] [any options]

**Description**: Switch to Gui2

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#guinames_m

**Arguments**: [any] [any options]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#HAdd

**Arguments**: [any]

**Description**: Adds hydrogen atoms to all or provided atoms, however the ring atoms are treated separately and added all the time

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Help

**Arguments**: [any];

**Description**: Prints available information. If no arguments provided prints available commands

**Options**:

- *c*: specifies commands category



**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#hho

**Arguments**: [any] [any options]

**Description**: empty htmlpanel except for header

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Hide

**Arguments**: [any];

**Description**: Hides selected objects or provided atom names (no atom related objects as bonds are hidden automatically)

**Options**:

- *b*: also hides all bonds atatched to the selected atoms



**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#HImp

**Arguments**: [any except none]

**Description**: Increases, decreases length of H-bonds. Arguments: value [H atoms]. Value might be +/- to specify to increase/decrease current value

**Options**: None

**States**: Loaded file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#HklAppend

**Arguments**: [any];

**Description**: moves reflection back into the refinement list. See excludeHkl for more details

**Options**:

- *c*:

- *h*:

- *k*:

- *l*:



**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#HklBrush

**Arguments**: [any];

**Description**: for high redundancy data sets, removes equivalents with high sigma

**Options**:

- *f*: consider Friedel law



**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#HklEdit

**Arguments**: [none, 1 or 3]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#HklExclude

**Arguments**: [any];

**Description**: Excludes reflections with give indexes from the hkl file -h=1;2 : all reflections where h=1 or 2

**Options**:

- *c*: true/false to use provided indexes in any reflection. The default is in any one reflection

- *h*: semicolon separated list of indexes

- *k*:

- *l*:



**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#HklExtract

**Arguments**: [1]

**Description**:

**Options**: None

**States**: Loaded file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#HklImport

**Arguments**: [any except none, 1, 2 or 3];

**Description**: Creates a Shelx compatible 44488(4) file format from given source. Valid arguments: fixed and separator. For example:
	\'HklImport in.hkl fixed 7 7 7 9 9 out.hkl\' or \'HklImport in.hkl separator \' \'\' out.hkl

**Options**:

- *batch*: for separator formatted file specifies that there is a batch number



**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#HklMerge

**Arguments**: [any] ;

**Description**: Merges current HKL file (ehco HKLSrc()) to given file name. Warning: if no arguments provided, the current file is overwritten

**Options**:

- *z*: zero negative intensity



**States**: Loaded file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#HklSplit

**Arguments**: [2];

**Description**: Split an HKL file according to the Fc^2/esd or the value of |Fc^2-Fo^2|/esd. The threshold value is the first argument. If it ends with \'%\' - the pecentage of the merged reflections is taken into the account. The second argument is the splitting criterion - \'i\'  for intensity or \'a\' for the agreeability. Unless -b option is provided, the \'agreeable\' reflections end up in the *_a.hkl file,  \'disagreeable\' - in the *_d.hkl file; weaker reflections end up in *_w.hkl and stronger reflections - in the *_s.hkl files.

**Options**:

- *b*: creates an HKLF 5 file (*_h5) with batches 1 and -2; only applicable when second parameter is 'a'



**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#HklStat

**Arguments**: [any] ;

**Description**: If no arguments provided, prints the statistics on all reflections as well as the ones used in the refinement. If an expressions (condition) is given in the following form: x[ahbkcl], meaning that x=ah+bk+cl for x equals 0, ((ah+bk+cl) mod x) equals 0 for positove x and not equals 0 for negative x; the subsequent expressions are combined using logical \'and\' operator. For instance 2[l] expression means: to find all reflections where l is even, the expression -2[l] means to find all reflections with odd l, 0[h-l] - reflections where h equals to l etc. The function operates on all P1 merged reflections after filtering by SHEL and OMIT, -m option merges the reflections in current space group

**Options**:

- *l*: list the reflections

- *m*: merge reflection in current space group



**States**: Loaded file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#HklView

**Arguments**: [none or 1]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Htab

**Arguments**: [none, 1 or 2] ;

**Description**: Adds HTAB instructions to the ins file, maximum bond length [2.9] and minimal angle [150] might be provided

**Options**:

- *g*: generates found interactions

- *t*: adds extra elements (comma separated -t=Se,I) to the donor list. Defaults are [N,O,F,Cl,S,Br]



**States**: INS file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#htmguifontsize

**Arguments**: [any] [any options]

**Description**: Set the default font for the html gui

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#html

**Arguments**: [any] [any options]

**Description**: Shows the current html

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#HtmlPanelSwap

**Arguments**: [none or 1]

**Description**: Swaps or sets the position of the HTML GUI panel. If no arguments given - swaps the panel position. The position can be specified by left and right

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#HtmlPanelVisible

**Arguments**: [none, 1 or 2]

**Description**: Swaps visibility of the HTML GUI panel or sets it to a given state (true/false)

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#HtmlPanelWidth

**Arguments**: [none or 1]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#ImportFont

**Arguments**: [2]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#ImportFrag

**Arguments**: [none] ;

**Description**: Import a fragment into current structure

**Options**:

- *a*: set specified AFIX to the imported fragment

- *c*: take the content from the clipboard

- *d*: generate DFIX for 1-2 and 1-3 distances

- *o*: set specified occupancy to the imported fragment atoms

- *p*: part to assign



**States**: Loaded file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Individualise

**Arguments**: [any]

**Description**: Moves provided atoms to individual collections, so that the atom properties, such as draw style and appearance can be changed separately of the group. The first call to this macro creates a group unique to the asymmetric unit, the second call makes the atom unique to the lattice

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Info

**Arguments**: [any];

**Description**: Prints out information for gived [all] atoms

**Options**:

- *c*: copy the printed information ito the clipboard

- *f*: print fractional coordinates vs Cartesian [true]

- *p*: coordinate precision [3]

- *s*: sorts the atom list



**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#InstallPlugin

**Arguments**: [1];

**Description**:

**Options**:

- *"l*: local installation from a zip file, which must contains index.ind"



**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Inv

**Arguments**: [any] ;

**Description**: Inverts whole structure or provided fragments of the structure

**Options**:

- *f*: force inversion for non-centrosymmetric space groups



**States**: Loaded file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#ISOR

**Arguments**: [any] ;

**Description**: Forses Uij of provided atoms to behave in isotropic manner. If no atoms provided, all non-H atoms considered

**Options**:

- *cs*: do not clear selection



**States**: INS file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Isot

**Arguments**: [any] ;

**Description**: Makes provided atoms isotropic, if no arguments provided, current selection or all atoms become isotropic

**Options**:

- *npd*: makes all NPD atoms isotropic



**States**: Loaded file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#IT

**Arguments**: [any];

**Description**: Calculates tensor of inertia

**Options**:

- *o*: orients basis according to principle axes of inertia



**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Kill

**Arguments**: [any];

**Description**: Deletes provided/selected atoms, bonds and other objects. \'kill labels\' hides all atom and bond labels

**Options**:

- *au*: kill atoms in the asymmetric unit (disregarding visibility/availability). This option is intended for the internal use - the model is not rebuilt after its execution



**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Label

**Arguments**: [any];

**Description**: Creates moveable labels for provided atoms/bonds/angles (selection)

**Options**:

- *cif*: creates labels for CIF data a combination of {b,a,t,h}

- *symm*: symmetry dependent tag type {[$], #, full}

- *type*: type of labels to make - subscript, brackers, default



**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Labels

**Arguments**: [any];

**Description**: Shows/hides atom labels. Takes no argument is given to invert current labels visibility or a boolean value

**Options**:

- *a*: afix

- *ao*: actual occupancy (as in the ins file)

- *b*: bond lengths

- *co*: chemical occupancy

- *f*: fixed parameters

- *h*: show hydrogen atom labels

- *i*: display labels for identity atoms only

- *l*: label

- *o*: occupancy

- *p*: part

- *qi*: Q peak intensity

- *r*: Uiso multiplier for riding atoms

- *u*: Uiso

- *v*: variables



**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Line

**Arguments**: [any];

**Description**: Creates a line or best line for provided atoms

**Options**:

- *f*: consider input in fractional coordinates vs Cartesian

- *n*: just sets current view normal to the line without creating the object



**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Lines

**Arguments**: [1]

**Description**: Sets the number of visible text lines in the console. Use -1 to display all lines

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Link

**Arguments**: [none or 1]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#link_parts_occupancies_with

**Arguments**: [any] [any options]

**Description**: link parts and occupancies with chosen restraint

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Listen

**Arguments**: [any]

**Description**: Listens for changes in a file provided as argument. If the file content changes it is automatically reloaded in Olex2. If no arguments provided prints current status of the mode

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Load

**Arguments**: [any except none]

**Description**:

#1
Arguments - textures
#2
Loads style/scene/view/gview/model/radii. For radii accepts sfil, vdw, pers

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#log

**Arguments**: [any] [any options]

**Description**: Shows the current log file

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#LS

**Arguments**: [1 or 2]

**Description**: Sets refinement method and/or the number of iterations.

**Options**: None

**States**: INS file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#LstFS

**Arguments**: [any]

**Description**: Prints out detailed content of virtual file system. Accepts * based masks

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#LstFun

**Arguments**: [any];

**Description**: Lists all defined functions. Accepts * based masks

**Options**:

- *h*: Shows help



**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#LstGO

**Arguments**: [none]

**Description**: List current graphical objects

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#LstIns

**Arguments**: [none]

**Description**: Lists all instructions of currently loaded Ins file

**Options**: None

**States**: INS file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#LstMac

**Arguments**: [any];

**Description**: Lists all defined macros. Accepts * based masks

**Options**:

- *h*: Shows help



**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#LstSymm

**Arguments**: [none]

**Description**: Prints symmetry codes for current structure

**Options**: None

**States**: Loaded file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#LstVar

**Arguments**: [any]

**Description**: Lists all defined variables. Accepts * based masks

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Mask

**Arguments**: [any except none]

**Description**: Sets primitives for atoms or bonds according to provided mask. Accepts atoms, bonds, hbonds or a name (like from LstGO).
Example: \'mask hbonds 2048\' - this resets hydrogen bond style to default

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Match

**Arguments**: [none, 1 or 2];

**Description**: Fragment matching, alignment and label transfer routine

**Options**:

- *a*: align

- *cm*: copies the transformation matrix suitable for sgen to clipboard

- *esd*: calculate esd (works for pairs only)

- *h*: excludes H atoms from matching and the RMSD calculation

- *i*: try inversion

- *n*: naming. If the value a symbol [or set of] this is appended to the label, '$xx' replaces the symbols after the atom type symbol with xx, leaving the ending, '-xx' - changes the ending of the label with xx

- *o*: matches overlayed lattices

- *s*: subgraph match

- *u*: unmatch

- *w*: use non-unit weights [ZO - atomic number X occupancy], Z - atomic number, EM - atomic mass, AM - atomic mass X occupancy, O - occupancy



**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Matr

**Arguments**: [none, 1, 2, 3 or 9];

**Description**: Displays or sets current orientation matrix. For single argument, 1,2,3 001, 111, etc values are acceptable, two values taken are of the klm form, which specify a view from k1*a+l1*b+m1*c to k2*a+l2*b+m2*c, three values pecify the view normal and nine values provide a full matrix

**Options**:

- *r*: used reciprocal cell instead



**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Mode

**Arguments**: [any except none] ;

**Description**: Turns specified mode on. Valid mode: fixu, fixc, grow, himp, match, move, name, occu, pack, part, split, fit

**Options**:

- *a*: [name] autocomplete; [grow] grow (rebuild) asymmetric unit only; [fit] afix


- *c*: [grow] covalent bonds; [move] copy fragments instead of moving


- *l*: [name] lock atom types after naming


- *p*: [name] prefix; [grow] inserts the new atoms into the AU with given [-1] part value


- *r*: [split] a restraint/constraint for split atoms; [grow] show radial bonds between the same atoms; [fit] rotation angle increment (smooth rotation by default); [name] synchronise names in the residues


- *s*: [grow] short interactions; [name] suffix; [fit] split, atoms to split offset [0]

- *shells*: [grow] grow atom shells vs fragments

- *t*: [name] type


- *v*: [grow] use user provided delta for connectivity analysis, default 2A




**States**: Loaded file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#mode_grow

**Arguments**: [any] [any options]

**Description**: setting mode grow with parameters

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#MolInfo

**Arguments**: [any] ;

**Description**: Prints molecular volume, surface area and other information for visible/selected atoms

**Options**:

- *g*: generation of the triangluation [5]

- *o*: use occupancy of the atoms in the integration

- *s*: source ([o]ctahedron, (t)etrahedron)



**States**: Loaded file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Move

**Arguments**: [none or 2];

**Description**: Moves two atoms as close to each other as possible; if no atoms given, moves all fragments as close to the cell center as possible

**Options**:

- *c*: copy moved atom

- *cs*: leaves selection unchanged



**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Mpln

**Arguments**: [any];

**Description**: Sets current view along the normal of the best plane

**Options**:

- *n*: just orient, do not create plane

- *r*: create regular plane

- *rings*: creates planes for rings template, like NC5

- *we*: use weights proportional to the (atomic mass)^we



**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#mspy

**Arguments**: [any] [any options]

**Description**: run a spy from the macro

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#my_report

**Arguments**: [any] [any options]

**Description**: Creates structure report

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Name

**Arguments**: [none, 1 or 2];

**Description**: Names atoms. If the \'sel\' keyword is used and a number (or just the number) is provided as second argument the numbering will happen in the order the atoms were selected

**Options**:

- *c*: enables checking labels for duplications

- *cs*: leaves current selection unchanged

- *r*: synchronise names in the residues

- *s*: simply changes suffix of provided atoms to the provided one (or none)



**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#NextSolution

**Arguments**: [none]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#normal_probability

**Arguments**: [any] [any options]

**Description**: Calculates and displays a Normal Probability plot

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#note

**Arguments**: [any] [any options]

**Description**: Opens a text box for editing custom log

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#oda

**Arguments**: [any] [any options]

**Description**: Launches ac_run

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#odemo

**Arguments**: [any] [any options]

**Description**: Launches OD Demo

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#OFileDel

**Arguments**: [1]

**Description**: Deletes overlayed file specified by index

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#OFileSwap

**Arguments**: [none or 1]

**Description**: Makes overlayed file, given by index the current file to which all commands are applied

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Omit

**Arguments**: [1, 2 or 3]

**Description**: Removes any particular reflection from the refinement list. If a single number is provided, all reflections with delta(F^2)/esd greater than given number are omitted

**Options**: None

**States**: INS file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#onexit

**Arguments**: [any] [any options]

**Description**: Executes on program exit

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#OnRefine

**Arguments**: [any]

**Description**: Internal procedure

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#onstartup

**Arguments**: [any] [any options]

**Description**: Executes on program start

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#options

**Arguments**: [any] [any ]

**Description**: Edit Olex2 internal options file

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Pack

**Arguments**: [any] ;

**Description**: Packs structure within default or given volume(6 or 2 values for parallelepiped or 1 for sphere). If atom names/types are provided it only packs the provided atoms.

**Options**:

- *c*: specifies if current lattice content should not be deleted



**States**: Loaded file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#panel

**Arguments**: [any] [any options]

**Description**: Set the width of the Control Panel

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Part

**Arguments**: [any] ;

**Description**: Sets part(s) to given atoms, also if -lo is given and -p > 1 allows linking occupancy of given atoms throw FVAR and/or SUMP in cases when -p > 2

**Options**:

- *c*: creates a copy of all grown atoms to which applied in the asymmetric unit and automatically links occupancies with the original atoms

- *lo*: link ocupancy of given atoms through FVAR's

- *p*: number of parts



**States**: Loaded file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Patt

**Arguments**: [none]

**Description**:

**Options**: None

**States**: INS file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#pers

**Arguments**: [any] [any options]

**Description**: Default pers macro

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Pict

**Arguments**: [1 or 2];

**Description**: Outputs a raster picture. Output file name is required, if a second numerical parameter is provided, it is considered to be image resolution in range [0.1-10] in screen sizes, anythin greater than 10 is considered as the desired picture width.

**Options**:

- *bw*: embossed output in b&w

- *c*: embossed output in color

- *dpi*: the physical resolution to be written to the file

- *nbg*: mask the background with 0 alpha (an rgb colour may be gives)

- *pq*: highest (picture) quality



**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Picta

**Arguments**: [1 or 2];

**Description**: A portable version of pict with limited resolution (OS/graphics card dependent). Not stable on some graphics cards

**Options**:

- *dpi*: the physical resolution to be written to the file

- *nbg*: mask the background with 0 alpha (an rgb colour may be gives)

- *pq*: picture quality



**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#PictPR

**Arguments**: [1]

**Description**: PovRay output

**Options**: None

**States**: Loaded file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#PictPS

**Arguments**: [1] ;

**Description**: Postscript rendering

**Options**:

- *atom_outline_color*: atom outline color[0xffffff]

- *atom_outline_oversize*:  the extra size of outline in percents[5]

- *bond_outline_color*: bond outline color[0xffffff]

- *bond_outline_oversize*: the extra size of the outline in percents [10]

- *color_bond*: bonds are colored

- *color_fill*: ellipses are filled

- *color_line*: lines

- *div_pie*: number [4] of stripes in the octant

- *lw_ellipse*: line width [0.5] of the ellipse

- *lw_font*: line width [1] for the vector font

- *lw_octant*: line width [0.5] of the octant arcs

- *lw_pie*: line width [0.5] of the octant stripes

- *multiple_bond_width*:  if 0 double and triple bonds are rendered as a fraction of their real width. If a values is not 0 - it specifies the width of the strips

- *octants*: comma separated atom types/names ADP's of which to be rendered with octants [-$C]

- *p*: perspective

- *scale_hb*: scale for H-bonds [0.5]

- *stipple_disorder*:  render stippled bonds for atoms in non 0 part [true]



**States**: Loaded file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#PictS

**Arguments**: [1 or 2] ;

**Description**: Stereoscopic picture rendering

**Options**:

- *a*: view angle [6]

- *h*: output image height [screen*resolution]

- *s*: separation between the images in % [10]



**States**: Loaded file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#PictTEX

**Arguments**: [1] ;

**Description**: Experimental tex/pgf rendering

**Options**:

- *color_fill*: ellipses are filled

- *color_line*: lines



**States**: Loaded file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#PiM

**Arguments**: [any] ;

**Description**: Creates an illustration of a \pi-system to metal bonds

**Options**:

- *l*: display labels for the created lines



**States**: Loaded file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#PiPi

**Arguments**: [none or 2] ;

**Description**: Analysis of the \pi-\pi interactions. The procedure searches for flat reqular C6 or NC5 rings and prints information for the ones where the centroid-centroid distance is smaller than [4] A and the shift is smaller than [3] A. These two parameters can be customised.

**Options**:

- *g*: generates using found symmetry operations

- *r*: ring content [C6,NC5]



**States**: Loaded file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#PiSig

**Arguments**: [none or 2] ;

**Description**: Analysis of the \pi-\igma interactions (experimental). The procedure searches for flat reqular 4 and 6 membored rings. Then it searches for atoms within [4] A from the ring centre and with less than [25] angle between the plane normal and the (plane center-atom) vectors.

**Options**:

- *g*: generates using found symmetry operations

- *r*: ring content [C6,NC5]



**States**: Loaded file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Plan

**Arguments**: [1]

**Description**: Sets the number of Fourier peaks to be found from the difference map

**Options**: None

**States**: INS file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#platon

**Arguments**: [any] [any options]

**Description**: Run PLATON

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Poly

**Arguments**: [any except none]

**Description**: Sets polyhedra type for all/selected/given atoms. Last argument specifies the type - none, auto, regular

**Options**: None

**States**: Loaded file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Popup

**Arguments**: [2];

**Description**: Creates a popup HTML window. Usage: popup popup_name html_source

**Options**:

- *b*: border[trscaip],t-caption bar, r-sizeable border, s-system menu, c-close box, a-maximise box, i-minimise box, p-window should stay on the top of others

- *h*: height

- *ondblclick*: a macro or commands to execute when window is double clicked

- *onsize*: a macro to be executed when the popup is resized

- *s*: do show the window after the creation

- *t*: title

- *w*: width

- *x*: left position

- *y*: top position



**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Post

**Arguments**: [any]

**Description**: Prints a string, but only after a new line character is encountered

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#ProcessCmd

**Arguments**: [any except none or 1]

**Description**: Send a command to current process. \'nl\' is translated to the new line char and \'sp\' to the white space char

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#profile

**Arguments**: [any] [any options]

**Description**: Opens the profiler output

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#proj

**Arguments**: [any] [any options]

**Description**: Default wireframe macro

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#ProjSph

**Arguments**: [any] ;

**Description**: Creates a projection from the selected atom onto a sphere, coloring each point on the sphere with a unique color corresponding to fragments.

**Options**:

- *e*: emboss the sphere

- *g*: sphere quality [6]



**States**: Loaded file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#pss1

**Arguments**: [any] [any options]

**Description**: PS style 1

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#pss2

**Arguments**: [any] [any options]

**Description**: Opens a text box for editing custom log

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#pss3

**Arguments**: [any] [any options]

**Description**: Opens a text box for editing custom log

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Push

**Arguments**: [any except none, 1 or 2]

**Description**: Shifts the sctructure (or provided fragments) by the provided translation

**Options**: None

**States**: Loaded file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#QPeakScale

**Arguments**: [none or 1]

**Description**: Prints/sets the scale of dependency of the Q-peak transparency vs height

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#QPeakSizeScale

**Arguments**: [none or 1]

**Description**: Prints/sets the scale the Q-peak size relative to other atoms, default is 1

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Qual

**Arguments**: [1]

**Description**: Sets drawings quality, 1 - low, 2 - medium, 3 - high

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#quit

**Arguments**: [none]

**Description**: Exits Olex2

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#reap

**Arguments**: [any] [any options]

**Description**: Load a Crystallographic File

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#reap_fade

**Arguments**: [any] [any options]

**Description**: Load a Crystallographic File

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#refine

**Arguments**: [any] [any options]

**Description**: Launches refine program. Syntax: refine [l.s.=-1] [plan=-1]

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Refresh

**Arguments**: [none]

**Description**: Refreshes the GUI

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Reload

**Arguments**: [1]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#report

**Arguments**: [any] [any options]

**Description**: Creates structure report (macro.xld)

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Reset

**Arguments**: [any] ;

**Description**: Resets current structure for the solution with ShelX

**Options**:

- *atoms*: saves the atom list alongside

- *c*: content

- *f*: alternative file name

- *rem*: exclude remarks

- *s*: space group



**States**: Loaded file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#RESI

**Arguments**: [any except none] ;

**Description**: Creates residue with given class name and optionally number and adds selected or provided atoms into the residue. If provided residue class name is \'none\', provided atoms are removed from their residues

**Options**:

- *a*: alias



**States**: Loaded file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Restrain

**Arguments**: [any]

**Description**: Creates a restraint

**Options**: None

**States**: Loaded file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#RIGU

**Arguments**: [any]

**Description**: Creates rigid bond (RIGU) restraint for a group of provided atoms(or selection)

**Options**: None

**States**: Loaded file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Rota

**Arguments**: [2 or 5]

**Description**: For two arguments the first one specifies axis of rotation (1,2,3 or x,y,z) and the second one the rotation angle in degrees. For five arguments the first three arguments specify the rotation vector [x,y,z] the forth parameter is the rotation angle and the fifth one is the increment - the rotation will be continuous

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#RRings

**Arguments**: [any];

**Description**: Makes all provided rings [like C6 or NC5] regular (flat and all distances similar). If a selection is given - the whole rings must be selected

**Options**:

- *cs*: do not clear selection



**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#RSA

**Arguments**: [any]

**Description**: Identifies chiral centres and prints R/S their stereo configuration

**Options**: None

**States**: Loaded file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#RTab

**Arguments**: [any except none]

**Description**: Adds RTAB with given name (first argument) for provided atoms/selection

**Options**: None

**States**: INS file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Run

**Arguments**: [any except none]

**Description**: Runs provided macros (combined by \'>>\')

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#sadabs

**Arguments**: [any] [any options]

**Description**: Run SADABS

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Sadi

**Arguments**: [any]

**Description**: Similar distances restraint

**Options**: None

**States**: INS file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#SAInfo

**Arguments**: [any]

**Description**: Finds and prints space groups which include any of the provided systematic absences in the form \'b~~\', \'~b~\' or \'~~b\'

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#saint

**Arguments**: [any] [any options]

**Description**: Run BrukerSaint

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Same

**Arguments**: [any] ;

**Description**: Creates SAME instruction for two fragments (two selected atoms or two atoms provided) or number_of_groups and groups following each another (or selection)

**Options**:

- *e*: expand SAME into the list of SADI

- *i*: invert the graphs



**States**: Loaded file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Save

**Arguments**: [any except none]

**Description**: Saves style/scene/view/gview/model

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Scene

**Arguments**: [none or 1];

**Description**: Prints default scene parameters or sets it (none resets)

**Options**:

- *s*: shows a file open dialog



**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Schedule

**Arguments**: [any except none or 1];

**Description**: Schedules a particular macro (second argument) to be executed within provided interval (first argument)

**Options**:

- *g*: requires GUI

- *r*: repeatable



**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Sel

**Arguments**: [any];

**Description**: If no arguments provided, prints current selection. This includes distances, angles and torsion angles and other geometrical parameters. Selects atoms fulfilling provided conditions, like
sel $type - selects any particular atom type; type can be one of the following shortcuts - * - for all atoms, M - for metals, X - for halogens
sel $*,type - selects all but type atoms

An extended syntax include keyword \'where\' and \'rings\' which allow selecting atoms and bonds according to their properties, like type and length or rings of particular connectivity like C6 or NC5. If the \'where\' keyword is used, logical operators, like and (&&), and or (||) can be used to refine the selection. For example:
sel atoms where xatom.bai.z > 2 - to select all atoms heavier after H
sel bonds where xbond.length > 2 - to select all bonds longer than 2 A
sel bonds where xbond.b.bai.z == 1 - to select all bonds where the lightest atoms is H

**Options**:

- *a*: select all

- *c*: copies printed values to the clipboard

- *i*: invert selection

- *l*: consider the list of bonds as independent

- *u*: unselect all



**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#SelBack

**Arguments**: [none];

**Description**:

**Options**:

- *a*:

- *o*:

- *x*:



**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#SetCmd

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#SetEnv

**Arguments**: [2]

**Description**: Sets an environmental variable

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#SetFont

**Arguments**: [any except none or 1];

**Description**: Sets font for specified control

**Options**:

- *b*: bold

- *i*: italic

- *ps*: point size



**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#SetMaterial

**Arguments**: [2 or 3]

**Description**: Assigns provided value to specified material

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#SetParam

**Arguments**: [any] [any options]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#setup

**Arguments**: [any] [any options]

**Description**: Setup Wizard for Olex2

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#SetView

**Arguments**: [any];

**Description**: Sets view normal to the normal of the selected plane, to a bond or mean line

**Options**:

- *c*: center



**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#sfil

**Arguments**: [any] [any options]

**Description**: Default pers macro

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#SG

**Arguments**: [none or 1];

**Description**: suggest space group

**Options**:

- *a*:



**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#sgd

**Arguments**: [any] [any options]

**Description**: Determine the Space Group

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#SGE

**Arguments**: [none or 1]

**Description**: Extended spacegroup determination. Internal use

**Options**: None

**States**: Loaded file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Sgen

**Arguments**: [any except none]

**Description**: Grows the structure using provided atoms (all if none provided) and symmetry code

**Options**: None

**States**: Loaded file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#SGInfo

**Arguments**: [none or 1];

**Description**: Prints space group information.

**Options**:

- *c*: include lattice centering matrices

- *i*: include inversion generated matrices if any



**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#SGS

**Arguments**: [any except none]

**Description**: Changes current space group settings using provided cell setting (if applicable) and axis, or 9 transformation matrix elements and the space group symbol. If the transformed HKL file is required, it should be provided as the last argument (like test.hkl)

**Options**: None

**States**: Loaded file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Shell

**Arguments**: [any]

**Description**: If no arguments launches a new interactive shell, otherwise runs provided file in the interactive shell (on windows ShellExecute is used to avoid flickering console)

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#ShowH

**Arguments**: [none or 2]

**Description**: Changes the H-atom and H-bonds visibility

**Options**: None

**States**: Loaded file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#ShowP

**Arguments**: [any];

**Description**: Shows specified or all parts of the structure

**Options**:

- *m*: do not modify the display view

- *v*: operate only on currently visible atoms/fragments;



**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#ShowQ

**Arguments**: [none, 1 or 2];

**Description**: Traverses the three states - peaks and peak bonds are visible, only peaks visible, no peaks or peak bonds. One numeric argument is taken to increment/decrement the numegbr of visibe peaks. Two aruments are taken to control the visibility of atoms or bonds, like in: \'showq a true\' or \'showq b false\'

**Options**:

- *wheel*: number of peaks to hide (if negative) or to show



**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#ShowStr

**Arguments**: [none or 1]

**Description**: Shows/hides structure and console buffer

**Options**: None

**States**: Loaded file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#ShowSymm

**Arguments**: [none or 1]

**Description**: Shows symmetry elements of the unitcell

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#ShowWindow

**Arguments**: [1 or 2]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#SignPlugin

**Arguments**: [any except none or 1]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Silent

**Arguments**: [none or 1]

**Description**: If no argument is provided, prints out current mode status. Takes \'on\' and \'off\' values to turn Olex2 log on and off

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#SIMU

**Arguments**: [any] ;

**Description**: Similarity restraint for Uij of provided atoms. If no atoms provided, all non-H atoms considered

**Options**:

- *cs*: do not clear selection



**States**: INS file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#skin

**Arguments**: [any] [any options]

**Description**: Changes the Olex2 Gui Skin

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#solve

**Arguments**: [any] [any options]

**Description**: Launches solution program XS

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Sort

**Arguments**: [any]

**Description**: Sorts atoms of the default residue. Atom sort arguments:
	m - atomic mass
	z - atomic number
	l - label, considering numbers
	p - part, 0 is first followed by all positive parts in ascending order and then negative ones
	h - to treat hydrogen atoms independent of the pivot atom
	s - non-numerical labels suffix
	n - number after the atom symbol
 Moiety sort arguments:
	s - size
	h - by heaviest atom
	m - molecular mass
Usage: sort [+atom_sort_type] or [Atoms] [moiety [+moety sort type] [moiety atoms]]. If just \'moiety\' is provided - the atoms will be split into the moieties without sorting.
Example: sort +ml F2 F1 moiety +s - will sort atoms by atomic mass and label, put F1 after F2 and form moieties sorted by size. Note that when sorting atoms, any subsequent sort type operates inside the groups created by the preceeding sort types.

**Options**: None

**States**: Loaded file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Split

**Arguments**: [any] ;

**Description**: Splits provided atoms along the longest axis of the ADP

**Options**:

- *r*: EADP,ISOR or SIMU to be placed for the split atoms



**States**: INS file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Standardise

**Arguments**: [none or 1]

**Description**: Standardises atom coordinates (similar to HKL standardisation procedure). If \'0\' is provided as argument, the asymmetric unit content is arranged as close to (0,0,0), while being inside the unit cell as possible

**Options**: None

**States**: Loaded file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#starter

**Arguments**: [any] [any options]

**Description**: Swap between start panels

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#StartLogging

**Arguments**: [1];

**Description**: Creates/opens for appending a log file, where all screen output is saved

**Options**:

- *c*: empties the file if exists



**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#startupPanel

**Arguments**: [any] [any options]

**Description**: Set the width of the Control Panel

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Stop

**Arguments**: [1]

**Description**: Switches specified mode off

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#StoreParam

**Arguments**: [2 or 3]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Style

**Arguments**: [none or 1];

**Description**: Prints default style or sets it (none resets)

**Options**:

- *s*: shows a file open dialog



**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Sump

**Arguments**: [any except none]

**Description**: Adds a linear equaltion into the refinement

**Options**: None

**States**: INS file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#SwapBg

**Arguments**: [none]

**Description**: Swaps current background to white or vice-versa

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#systematic_absences

**Arguments**: [any] [any options]

**Description**: Calculates and displays the systematic absences intensity distribution

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#tbx

**Arguments**: [any] [any options]

**Description**: toolbox

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#tbxh

**Arguments**: [any] [any options]

**Description**: toolbox help

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#tbxs

**Arguments**: [any] [any options]

**Description**: toolbox

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#telp

**Arguments**: [any] [any options]

**Description**: Default telp macro

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#telph

**Arguments**: [any] [any options]

**Description**: Default telph macro

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#TelpV

**Arguments**: [1]

**Description**: Calculates ADP scale for given thermal probability (in %)

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Test

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#TestBinding

**Arguments**: [any]

**Description**: Internal tests

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#TestMT

**Arguments**: [any]

**Description**: Testing multithreading

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#TestStat

**Arguments**: [1]

**Description**: Test: runs statistical tests on structures in current folder. Expects a file name

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#TestSymm

**Arguments**: [none] ;

**Description**: Tests current structure for missing symmetry

**Options**:

- *e*: tolerance limit



**States**: Loaded file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#text

**Arguments**: [any] [any options]

**Description**: Shows the current console buffer

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Textm

**Arguments**: [1]

**Description**: Runs subsequent commands stored in a text file

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#tidy

**Arguments**: [any] [any options]

**Description**: Automatically select things

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#TLS

**Arguments**: [any] ;

**Description**: TLS procedure. The TLS is calculated for the given atoms and then the matrices rotated to the L axes (making L diagonal) and shifted to make S symmetric. The printed R1 is calculated for ADPs in the L axes and is:
R1=sum(i=1..3,j=i..3)(|Uobs_ij-Utls_ij|)/sum(i=1..3, j=i..3)(|Uobs_ij|)
R2\' is invariant under the rotation and is calculated as
R2\'=sum(i=1..3,j=1..3)((Uobs_ij-Utls_ij)^2)/sum(i=1..3,j=1..3)(Uobs_ij^2)

**Options**:

- *a*: apply the TLS ADP to the atoms



**States**: Loaded file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Tolman

**Arguments**: [none or 5] ;

**Description**: Calculates Tolamn code angle for the selection (M P S1 S2 S3)

**Options**:

- *mpd*: M to P distance



**States**: Loaded file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#tool

**Arguments**: [any] [any options]

**Description**: Show grouped gui tools

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Transform

**Arguments**: [any]

**Description**: Transforms the structure or provided fragments according to the given matrix (a11, a12, a13, a21, a22, a23, a31, a32, a33, t1, t2, t3)

**Options**: None

**States**: Loaded file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Tref

**Arguments**: [1 or 2]

**Description**:

**Options**: None

**States**: INS file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Tria

**Arguments**: [any];

**Description**: Adds a distance restraint for bonds and \'angle\' restraint for the angle

**Options**:

- *cs*: do not clear selection



**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#tubes

**Arguments**: [any] [any options]

**Description**: Tubes bonds

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#txt

**Arguments**: [any] [any options]

**Description**: Open log file in an external text editor but with unique identifier

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#UncheckMenu

**Arguments**: [1]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Undo

**Arguments**: [none]

**Description**: Reverts some of the previous operations

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#UninstallPlugin

**Arguments**: [1]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Uniq

**Arguments**: [any]

**Description**: Shows only fragments specified by atom name(s) or selection

**Options**: None

**States**: Loaded file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Update

**Arguments**: [none]

**Description**: Does check the for the updates

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#UpdateFile

**Arguments**: [1];

**Description**:

**Options**:

- *f*:



**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#UpdateOptions

**Arguments**: [none]

**Description**: Shows the Update Options dialog

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#UpdateQPeakTable

**Arguments**: [none]

**Description**: Internal routine for synchronisation

**Options**: None

**States**: Loaded file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#UpdateWght

**Arguments**: [any]

**Description**: Copies proposed weight to current

**Options**: None

**States**: INS file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#User

**Arguments**: [none or 1]

**Description**: Changes current folder

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#user_onstartup

**Arguments**: [any] [any options]

**Description**: user settings...

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#ValidateCif

**Arguments**: [any] [any options]

**Description**: Validates a CIF file against the given CIF dictionary

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#VATA

**Arguments**: [any]

**Description**: Compares current model with the cif file and write the report to provided file (appending)

**Options**: None

**States**: Loaded file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#ViewGrid

**Arguments**: [none or 1]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#ViewLattice

**Arguments**: [1]

**Description**: Loads cell information from provided file and displays it on screen as lattice points/grid

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#VoidE

**Arguments**: [none]

**Description**: calculates number of electrons in the voids area

**Options**: None

**States**: Loaded file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#vv

**Arguments**: [any] [any options]

**Description**: runs voids

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Wait

**Arguments**: [1];

**Description**: Forces Olex2 and calling process to sleep for provided number of milliseconds

**Options**:

- *r*: during wait all events are processed



**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#WaitFor

**Arguments**: [1]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#WBox

**Arguments**: [any] ;

**Description**: Calculates wrapping box around provided box using the set of best, intermidiate and worst planes

**Options**:

- *s*: create separate boxes for fragments

- *w*: use atomic mass instead of unit weights for atoms



**States**: Loaded file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#weight

**Arguments**: [any] [any options]

**Description**: Use suggested weighting scheme

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#Wilson

**Arguments**: [none or 1] ;

**Description**: Prints Wilson plot data

**Options**:

- *b*: number of bins

- *p*: uses linear bins for picture, otherwise uses spherical bins



**States**: Loaded file is expected

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#wilson_plot

**Arguments**: [any] [any options]

**Description**: Creates and displays a Wilson Plot

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#WindowCmd

**Arguments**: [any except none or 1]

**Description**: Windows specific command which send a command to a process with GUI window. First argument is the window name, the second is the command. \'nl\' is considered as a new line char and \'sp\' as white space char

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#xp

**Arguments**: [any] [any options]

**Description**: Run XP

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#xprep

**Arguments**: [any] [any options]

**Description**: Starts XPREP if it installed on your machine

**Options**: None

**States**: No requirement

**Parent**: None

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#fs.Clear

**Arguments**: [none or 1]

**Description**: Clear the content of the VFS. A mask [-1] can be used to remove only items with particular persistence mask

**Options**: None

**States**: No requirement

**Parent**: fs

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#fs.Dump

**Arguments**: [2]

**Description**: Saves a file in the VFS to the disk file

**Options**: None

**States**: No requirement

**Parent**: fs

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#gl.Fog

**Arguments**: [none, 1 or 3]

**Description**: Sets fog color, fog without arguments removes fog

**Options**: None

**States**: No requirement

**Parent**: gl

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#gl.Perspective

**Arguments**: [none or 1]

**Description**: Un/Sets perspective view

**Options**: None

**States**: No requirement

**Parent**: gl

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#gl.Zoom

**Arguments**: [none or 1]

**Description**: If no arguments provided - resets zoom to fit to screen, otherwise increments/decrements current zoom by provided value

**Options**: None

**States**: No requirement

**Parent**: gl

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#gl.scene.MakeCurrent

**Arguments**: [none]

**Description**: Make scene for rendering/updates

**Options**: None

**States**: No requirement

**Parent**: gl.scene

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#html.DefineControl

**Arguments**: [2];

**Description**: Defines a managed control properties

**Options**:

- *bg*: background color

- *c*: checked/down

- *fg*: foreground color

- *i*: tems

- *max*: max value

- *min*: min value

- *v*: value



**States**: No requirement

**Parent**: html

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#html.Dump

**Arguments**: [1 or 2]

**Description**: Saves content of the main or given page into the file

**Options**: None

**States**: No requirement

**Parent**: html

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#html.Group

**Arguments**: [any except none or 1]

**Description**: Creates an exclusive group of buttons

**Options**: None

**States**: No requirement

**Parent**: html

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#html.Hide

**Arguments**: [1]

**Description**: Hides an Html popup window

**Options**: None

**States**: No requirement

**Parent**: html

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#html.Home

**Arguments**: [none or 1]

**Description**: Reloads the page

**Options**: None

**States**: No requirement

**Parent**: html

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#html.ItemState

**Arguments**: [any except none or 1];

**Description**: Changes state of the HTML switch, accepts masks like \'*-picture-*\'

**Options**:

- *u*: does not update the html



**States**: No requirement

**Parent**: html

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#html.Load

**Arguments**: [1 or 2]

**Description**: Loads content into main or given HTML page. Example: load name file_name

**Options**: None

**States**: No requirement

**Parent**: html

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#html.LstObj

**Arguments**: [none or 1]

**Description**: Prints the list of available HTML objects

**Options**: None

**States**: No requirement

**Parent**: html

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#html.SetBorders

**Arguments**: [1 or 2]

**Description**: Sets borders between HTML content and window edges

**Options**: None

**States**: No requirement

**Parent**: html

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#html.SetFonts

**Arguments**: [2 or 3]

**Description**: Sets normal and fixed fonts to display HTML content [html normal_face fixed_face]

**Options**: None

**States**: No requirement

**Parent**: html

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#html.Tooltips

**Arguments**: [none, 1 or 2]

**Description**: Enables or disables tooltip for HTML. If no arguments is given the state of tooltops for the main HTML is inverted. If a single boolean argument is given - the state of the tooltips is set to the given value, if the argument is not a boolean the state of the tooltips for HTML windows with given name is inverted. If two arguments are given - the first should be an HTML window name and the second - a boolean value. This function executes the htmltt state change event

**Options**: None

**States**: No requirement

**Parent**: html

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#html.Update

**Arguments**: [none or 1]

**Description**: Reloads the content of the main or given named HTML window

**Options**: None

**States**: No requirement

**Parent**: html

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#lcells.Search

**Arguments**: [none, 1, 2 or 7];

**Description**: Searches current cell, cell from given file, or given cell

**Options**:

- *d*: deviation [1 A^3]



**States**: No requirement

**Parent**: lcells

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#lcells.Update

**Arguments**: [none, 1, 2 or 3]

**Description**: Updates/creates indices using default/given configuration. To create an index, pass a folder name.

**Options**: None

**States**: No requirement

**Parent**: lcells

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#mouse.Disable

**Arguments**: [any except none]

**Description**: Disables one of the following operations: rotation, zooming, translation, selection

**Options**: None

**States**: No requirement

**Parent**: mouse

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#mouse.Enable

**Arguments**: [any except none]

**Description**: Enables one of the following operations: rotation, zooming, translation, selection

**Options**: None

**States**: No requirement

**Parent**: mouse

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#mouse.Lock

**Arguments**: [none or 1]

**Description**: [Disables]/enables rotation, zooming and translation

**Options**: None

**States**: No requirement

**Parent**: mouse

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#py.Reset

**Arguments**: [none]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: py

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#py.Run

**Arguments**: [any except none]

**Description**: Runs provided file

**Options**: None

**States**: No requirement

**Parent**: py

**Type**: Macro

**Example**:

**Keywords**:

**Scope**:

#spy.as_pdb_file

**Arguments**: [any];

**Description**:

**Options**:

- *filepath*:

- *fractional_coordinates*: (False)

- *remark*:

- *remarks*:

- *resname*:



**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.config_box

**Arguments**: [any];

**Description**:

**Options**:

- *config*: Name of the configuration file

- *name*: Name of the Config Box

- *popout*: True/False



**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.config_changed_var_val

**Arguments**: [any];

**Description**:

**Options**:

- *f*:



**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.install_plugin

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.make_help_box

**Arguments**: [any];

**Description**:

**Options**:

- *name*: Name of the Box

- *popout*: True/False

- *type*: Type of Box (help or tutorial)



**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.makeHtmlBottomPop

**Arguments**: [any];

**Description**:

**Options**:

- *name*: Name of the Bottom html popupbox

- *txt*: Text to display



**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.resize_to_panelwidth

**Arguments**: [any];

**Description**:

**Options**:

- *c*: Colourize

- *i*: Image



**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.run_Analysis

**Arguments**: [any];

**Description**:

**Options**:

- *method*: olex or cctbx

- *n_bins*: Number of bins (for histograms only!)



**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.run_MakeAllRBars

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.run_skin

**Arguments**: [any];

**Description**:

**Options**:

- *function*: The function to call



**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.SetGrad

**Arguments**: [any];

**Description**:

**Options**:

- *f*:



**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.StoreSingleParameter

**Arguments**: [any]

**Description**:

**Options**: None

**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.tbxs

**Arguments**: [any];

**Description**:

**Options**:

- *n*: The name of the setup screen



**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#spy.ValidateCif

**Arguments**: [any];

**Description**:

**Options**:

- *cif_dic*:

- *filepath*:

- *show_warnings*:



**States**: No requirement

**Parent**: spy

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#xf.EndUpdate

**Arguments**: [none]

**Description**: Must be called after the content of the asymmetric unit has changed - this function will update the program state

**Options**: None

**States**: INS file is expected

**Parent**: xf

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

#xf.rm.ShareADP

**Arguments**: [any]

**Description**: Creates a rotated ADP constraint for given atoms. Currently works only for T-X3 groups (X-CMe3, X-CF3 etc) and for rings

**Options**: None

**States**: No requirement

**Parent**: xf.rm

**Type**: Python Function

**Example**:

**Keywords**:

**Scope**:

