# Reports and Images

Tools for the creation of images are available from `@Tools|Images`.

## Labelling Atoms
Labels can be placed on either atoms or bonds (or a mixture of both)

- If no atoms (or bonds) are selected, all atoms and bonds will be labelled. Clicking **non-H atoms** will label all of the non-hydrogen atoms. If symmetry-equivalent atoms are shown, their symmetry label will be printed according to the **Symm** and **Style** options. 
- Labels can be moved, individually or in groups, while holding down the SHIFT key and the LEFT MOUSE button and moving the mouse.

### Deleting labels
Labels can be deleted:

- Individually, by selecting an atom label with the LEFT MOUSE button and pressing DELETE.
- Double click on any label to select them all, then press DELETE.

There are two independent sets of labels. The built-in labels (toggled with F3 and under `@Work|Toolbox Work') and then those accessed from `@Tools|Images`. These image labels can be positioned with SHIFT + LEFT MOUSE. The built-in labels are useful if you want to see to see all atom names, but label only a few atoms.

### Creating and Saving Images
Olex2 offers a number of different file formats for saving images, these are found under `@Tools|Images`. 

There are options to specify what happens if a picture file **already exists**, the default is to *Ask*, but it is also possible to select *Increment* or *Replace* from the drop-down menu.

- **Bitmap Images** - will create a bitmap image of the structure by clicking **Go**. Selecting **Trim** will trim the image depending 
- **Postscript Images** - creates an image in the 'postcript' style. Click **Go** to create the image. There are numerous options to edit the image including:
	- *Atoms*: Change the outline width
	- *Octant*: Specify the number of dividers within the Octant drawn.
	- *Fonts* and *Bond Font*: Modify the font styles for the labels 	
- **Povray Images** - Olex2 writes a .pov file for the image. Click **Go** to create the image. Note that any further changes need to be made using PovRay software.
- **Image Series** - creates a series of images for a movie. There are options for changing the *Rotation around Axis*, the number of *degrees* of rotation between each image, the *Number of Frames* and the *Size*. Click **Go** to create the image.



## Generating Figures
A variety of options are available for creating figures are available under `@View|Quick Drawing Styles and Tools|Images`. Pictures are created of the molecules or fragments displayed on the graphics screen and can either be of a grown or ungrown structure.

### Changing the atom display style
The same display options apply for changing the appearance of the atoms during a refinement as can be used for generating images. These can be found under `@View|Quick Drawing Styles`. Alternatively, right click on the graphics display window and under **Draw Style** select the desired appearance. 
When producing figures there may be conventions for expected formats, e.g. for small molecule organic/organometallics an ellipsoid plot is typical with carbon atoms grey, oxygen red. In such cases, it is a good idea to follow convention. In other situations the appearance of the figures may be down to the personal preference.

## Writing a Report or a CIF
Olex2 generates both a report, containing crystallographic information in table format typical for papers, and a standard CIF,  using user controlled values. The options available under `@Work|Report` are relatively self-explanatory and hence this section is not discussed in detail here.
