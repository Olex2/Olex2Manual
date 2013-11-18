# Changing the Structure View

## Changing the Display Style
The same display options apply for changing the appearance of the atoms during a refinement as can be used for generating images. These can be found under `@View|Quick-Drawing-Styles`, alternatively right click on the graphics display window and under @@Draw Style@@ select the desired appearance.

## Atom Display Quality
The quality of the atom appearance can be adjusted by right clicking in the display window and under @@Draw quality@@ is the option to change between High, Medium or Low. Alternatively type `CODE qual -h/m/l` in the command-line. When very large structures or packing diagrams are displayed, the graphics may respond slowly if the draw quality is set too high - besides, you will see the same regardless of which quality setting you choose.

## Rotating a Structure
To rotate the structure, click with the LEFT MOUSE button in the graphics screen (avoiding atoms or Q-peaks) and move the mouse. Holding CTRL down at the same time rotates the structure around in the plane of the screen. You can also use SHIFT + DIRECTION keys to rotate the structure using the keyboard.
It is also possible to rotate the structure by a user-defined amount relative to the screen orientation under `@View|Rotate`, @@x@@ rotates the structure from top to bottom, @@y@@ rotates from left to right and @@z@@ rotates around in the plane of the page. On the command-line, `CODE rota 1 30` will rotate the molecule by 30 degrees around axis 1.

## Zooming 
Holding the RIGHT MOUSE button down in the graphics screen (avoiding atoms or Q-peaks) and moving the mouse will zoom into or out of the structure. If you do this while pressing the ALT-Key, the zooming will be smoother and more precise.

## View Along a Specific Direction
Right click on the background of the graphics window, under @@View@@ select the desired viewing direction from 100, 010, 001, 110, 101, 011 or 111.
In general, you can use `CODE matr` to align the model along a direction in real or reciprocal spaces (with `CODE matr -r`). Sometimes you find a good view, and would like to find the corresponding direction: type `CODE direction` and Olex2 will tell you in which direction the structure is oriented.
The viewing direction can be saved and loaded using `CODE save view <name>` and `CODE load view <name>`, where <name> is any name you choose.

## Displaying Basis Vectors and Cell Axes

- @@Show Basis@@: Toggle to display/hide the basis vectors. Alternatively right click in the display window under @@Model@@ is the option to Show / Hide Basis or type `CODE basis`. The basis vectors can be moved by dragging them with left mouse button while holding down Shift, and zoomed by dragging it with the right mouse button.
- @@Show Cell@@: Toggle to display/hide the cell axes. Alternatively right click in the display window under @@Model@@ is the option to Show / Hide Unit Cell or type `CODE cell`. The directions (*a*, *b*, *c* and origin) are also displayed. While holding Shift down, you can move these labels with the left mouse button.

## Stereo View
Various output options for Stereo viewing are available under `@View|Stereo-View`. Some of these produce stereo images on a standard monitor, but stereo output on dedicated 3-D monitors is also supported for either of the two commonly available systems
