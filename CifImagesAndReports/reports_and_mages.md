#Reports and Images

## Labelling Atoms
Options for labelling images are available under `@Tools|Images`:

- Label selected atoms this also applies to selected bonds, if no atoms are selected all atoms and bonds will be labelled, while non-H atoms will label all of the non-hydrogen atoms according to the Style selected from the drop-down box. 
- Labels can be moved, individually or in groups, while holding down the Shift key and the left mouse button and moving the mouse.

Atoms can be selected under `@Work|Select`. When the labels are active Ctrl+A selects all labels. These can then be moved with the Shift key and the left mouse button held down and then moving the mouse or alternatively deleted by pressing delete. If you leave the images section to remove the labels use Ctrl+A to select all atoms, molecules, bonds the image atom labels will be the only items not selected, use Ctrl+I to invert the selection resulting in just the image atom labels being selected, press delete to delete these labels.

###Deleting labels
Individually by selecting an atom label with the left hand mouse button and pressing delete.
Double click on any label to select them all, then press DELETE.
The Choose the label colour, Label Box and Transparent Box options do not apply to every file format so may not be applicable, check the options available under the desired file format. 
There are two independent sets of labels. The built-in labels (toggled with F3 and under `@Work|Toolbox Work') and then those accessed from `@Tools|Images`. These image labels can be positioned with SHIFT+LEFT MOUSE. The built-in labels are useful if you want to see to see all atom names but label only a few atoms.

###Saving Images
Olex2 offers a number of different file formats for saving images, these are found under `@Tools|Images`, the images are saved in the current structure folder:

- **Bitmap Images**: various option exist for changing the appearance of the image, it is worth experimenting.
- **Postscript Images**: various option exist for changing the appearance of the image, it is worth experimenting.
- **Povray Images**: Olex2 writes a .pov file but any changes need to be made using PovRay.
- **Image Series**: creates a series of images for a movie. There are op-tions for changing the Rotation around Axis, the number of degrees of rotation between each image, the Number of Frames and the Size.

There are options to specify what happens if a picture file already ex-ists, the default is to Ask, but it is also possible to select Increment or Replace.

##Generating Figures
A variety of options are available for creating figures are available under `@View|Quick-Drawing-Styles-and-Tools|Images`. Pictures are created of the molecules or fragments displayed on the graphics screen and can either be of a grown or ungrown structure.

###Changing the atom display style
The same display options apply for changing the appearance of the atoms during a refinement as can be used for generating images. These can be found under `@View|Quick-Drawing-Styles`, alternatively right click on the graphics display window and under Draw Style select the desired appearance. 
When producing figures there may be conventions for expected formats, e.g. for small molecule organic/organometallics an ellipsoid plot is typical with carbon atoms grey, oxygen red. In such cases it is a good idea to fol-low convention. In other situations the appearance of the figures may be down to the personal preference.

###Writing a Report or a Cif
Olex2 generates both a report, containing crystallographic information in table format typical for papers, and a standard CIF,  using user controlled values. The options available under `@Work|Report` are relatively self-explanatory and hence this section is not discussed in detail here.
