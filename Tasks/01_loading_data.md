# Loading Data
Olex2 can handle a number of data formats. There are three categories of data to consider in the solution of a molecular structure from single crystal diffraction data.

1. Reflection data: .hkl, .raw
2. The model: .ins (.res), .xyz, .cif ...
3. Metadata: .p4p, .prp, .cif

>CRYST The Crystallographic Information File (CIF) plays a special role once the structure solution has been completed -- it is the structure archival format. In theory it should contain all the information (experiment condition, sample information, references to the software and algorithms used in the process) available about a structure -- all three of the above categories are combined into this one file.

If you obtain a .cif file that was generated from ShelXL-2013, you will have the reflection (.hkl) data embedded in this file. If you load one of these .cif files into Olex2, you can start the structure refinement and working with it otherwise straight off -- it will automatically extract the reflections and the model data and place them into the appropriate files.

If you want to work with your structure (solve, build the model, refine) you need the diffraction data -- most commonly these are available in the form of an *.hkl* file.
If you don't have the diffraction data, you can still prepare tables, reports and images from the contents of the .res file, but you can't modify your model!

## Opening a Structure
The basic unit you work with in Olex2 is 'a structure'. It has a name and that should not change throughout the process. You may think of it as a 'project', if that helps you. Underlying this structure is a single data collection (which may, of course, give rise to more than one *.hkl* file). We encourage you to place all files belonging to a structure (and only those!) into a named directory. In practice, this means that, after a data collection is finished, you work in a particular directory (`work' in the Bruker world, 'struct/' in the Agilent world). In order to open a particular structure, do one of the following: 

- Simply drag and drop any crystallographic file into Olex2. 
- On the GUI panel under Home|Start, select Open Existing Structure or Data File, locate your directory, select the *.ins* file and click Open. 
- In the menu bar `@File|Open`, locate directory, select the *.ins* file and click Open.
- On the GUI panel `@Info|Recent Files` contains recently refined structures, if any exist, click on a file name to load a structure.
