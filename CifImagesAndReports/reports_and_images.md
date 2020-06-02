# Reports and Images
> Every structure determination needs reports and images. Here's how you get them using Olex2

Tools for the creation of images are available from `@Tools|Images`.

## Labelling Atoms
Labels can be placed on either atoms or bonds (or a mixture of both).

- If no atoms (or bonds) are selected, all atoms and bonds will be labelled. Clicking @@non-H atoms@@ will label all of the non-hydrogen atoms. If symmetry-equivalent atoms are shown, their symmetry label will be printed according to the @@Symm@@ and @@Style@@ options.
- Labels can be moved, individually or in groups, while holding down the SHIFT key and the LEFT MOUSE button and moving the mouse.

### Deleting labels
Labels can be deleted:

- Individually, by selecting an atom label with the LEFT MOUSE button and pressing DELETE.
- Double click on any label to select them all, then press DELETE.

There are two independent sets of labels. The built-in labels (toggled with F3 and under `@Work|Toolbox-Work`) and then those accessed from `@Tools|Images`. These image labels can be positioned with SHIFT + LEFT MOUSE. The built-in labels are useful if you want to see to see all atom names, but label only a few atoms.

## Generating Figures
A variety of options are available for creating figures are available under `@View|Quick-Drawing-Styles` and `@Tools|Images`. Pictures are created of the molecules or fragments displayed on the graphics screen and can either be of a grown or ungrown structure.

### Creating and Saving Images
Olex2 offers a number of different file formats for saving images, these are found under `@Tools|Images`. A name for the structure image can be typed into the white box. There are options to specify what happens if an image file @@already exists@@, the default is to @@Ask@@, but it is also possible to select @@Increment@@ or @@Replace@@ from the drop-down menu. A number of other options are available:

- @@Label selected@@ - will label all the selected atoms and/or bonds. If none are selected, then all bonds and atoms will be labelled.
- @@Non-H atoms@@ - will label all atoms that are not hydrogens.
- @@DELETE all labels@@ - deletes any labels shown.
- @@Choose the label colour@@ and @@Label Box@@ - allows you to customise the labels and label box by changing their colour, transparency etc.
- @@Align@@ - Clicking on *View* will show the structure with the largest number of atoms visible on the screen. Clicking on *Plane* will show the view with the best plane through the structure.
- @@Lock all@@ - Ticking this box locks the structure so it cannot be zoomed, rotated or translated. Unticking any of the boxes will reinstall the feature.

There are a number of further image customising and saving options under `@Tools|Images`:

- @@Bitmap Images@@ - will create a bitmap image of the structure by clicking @@Go@@.
	- Selecting @@Trim@@ will trim the image depending on the @@Padding@@ selected (greater padding means a larger distance between the structure and edge of crop in the final image).
	- There is an option to add a @@Border@@ and customise its @@Colour@@. Click @@Add Fog@@ to change the definition of the structure and use the *Front* and *Back* slider bars to customise this. @@Clear Fog@@ will remove the fog effect and return to showing the normal image.
	- There is also an option to change the Atom (@@Atom Label Font (Olex2)@@) and Bond (@@Bond Label Font (Olex2)@@ label fonts from a saved file. Clicking @@System Font@@ allows different fonts to be selected.
- @@Postscript Images@@ - creates a postscript image in ORTEP style. Click @@Go@@ to create the image. There are numerous options to edit the image including:
	- *Atoms*: Change the outline width.
	- *Octant*: Specify the number of dividers within the Octant drawn.
	- *Fonts* and *Bond Font*: Modify the font styles for the labels.
- @@Povray Images@@ - Olex2 writes a .pov file for the image. Click @@Go@@ to create the image. Note that any further changes need to be made using PovRay software.
- @@Image Series@@ - creates a series of images for a movie. There are options for changing the *Rotation around Axis*, the number of *degrees* of rotation between each image, the *Number of Frames* and the *Size*. Click @@Go@@ to create the image.

### Changing the atom display style
The same display options apply for changing the appearance of the atoms during a refinement as can be used for generating images. These can be found under `@View|Quick Drawing Styles`. Alternatively, right click on the graphics display window and under @@Draw Style@@ select the desired appearance.

>CRYST When producing figures there may be conventions for expected formats, e.g. for small-molecule organic and organometallic compounds an ellipsoid plot is typical with carbon atoms grey, oxygen red. In such cases, it is a good idea to follow convention. In other situations the appearance of the figures may be down to the personal preference.

## Writing a Report or a CIF
Olex2 generates both a report, containing crystallographic information in table format typical for papers, and a standard CIF, using user controlled values. The options available under `@Work|Report` are relatively self-explanatory and hence this section is not discussed in detail here.
