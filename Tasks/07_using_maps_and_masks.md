#	Using Maps and Masks

## Maps
Various maps can be calculated by Olex2 and are displayed interactively. These options are available under `@Tools|Maps`:
The appearance of the maps can be changed under the top heading of **View** (e.g. plane, contour, contour + plane, surface, wire, points). The additional options to adjust the view change depending on which option has been selected. The tool information provides more detail on the different views.

### Calculate Voids
This calculates all voids in the structure. The resolution of the map (Res/$\AA$) and the distance from atoms (Distance/%\AA$) can be adjusted to user-defined values. Click on **Void** to toggle between displaying and not displaying voids. The **Precise** option uses a different algorithm which will return more precise values, but the calculation will take much longer. The approximate values are normally all you need.

### Calculate Solvent Accessible Voids
Calculates voids that are large enough to contain solvent. Probe/$\AA$ adjusts the probe size (think of it as a `sphere' rolling about the structure - a smaller sphere will fit into smaller gaps and therefore return a larger void than a larger sphere would). The Grid/$\AA$ is the resolution of the map that will be explored when calculating the voids. If the resolution is too high, the calculation might take a Very Long Time at not much benefit. Click on **Void** to toggle between displaying and not displaying solvent accessible voids. On the graphics screen the size of any solvent accessible voids that are found will be displayed.

### Electron Density
The resolution of the map can adjusted using Res/$\AA$, the smaller the number the more detailed the map. The **Mask** tick-box enables the map to either overlay on the structure (box ticked) or lie to one side of the structure (box unticked). There are four different map options available: diff, Fc, 2Fo-Fc and Fo
An electron density map can also be calculated quickly under `@Work|Toolbox-Work|Electron-Density-Map` which will use the settings selected under `@Tools|Maps|Electron-Density`. If refinement has been attempted using both ShelXL and olex2.refine, there is the option to select either olex or an *.fcf* file. Ensure that the file from the last cycle of refinement is used.

### Masks
The **Masks** option serves as an alternative to SQUEEZE which is implemented in Platon (*http://www.cryst.chem.uu.nl/platon/*). These sorts of approaches should only be used when the solvent cannot be identified or modelled, although every effort should be made to try and do this. 

## 3D Electron Density Maps
In order to see whether disorder is likely it can be very useful to see a map of the residual electron density.

##Modelling Solvents
Where possible, every attempt should be made to model the solvent if it can be identified and sensibly modelled, as this will give the most accurate structure and therefore calculated structure factors. However, this is not always possible if the structure contains large voids enabling multiple solvent molecules to be incorporated at various positions within the structure. In such cases **Masks** (either calculated by Olex2 or by Platon/SQUEEZE can be used.
Often a solvent is disordered over more than one position and needs to be modelled as disordered.
A solvent is not always present is every ASU. For example, sometimes the solvent is only loosely bound in the structure and so it may evaporate out i.e. the occupancy does not necessarily equal 1. Care has to be taken when refining the occupancy due to the link between occupancy and thermal parameters.
