#calcvoid


>A [radii file name] [all atoms/selected atoms] [-d=0] [-p] [-r=0.2 \\A]

>B Calculates and displays the structure map. Also calculates the largest channels along crystallographic directions and the packing index. 

>C **-d**: extra distance from the surface (added to the atomic radii)
**-p**: precise calculation where each map voxel is tested. The default quick algorithm uses the atom masks to find the volume occupied by the molecule. The precise calculation is vectorised.
**-r**: resolution, a resolution of at least 0.1 ANGST and -p option is required to get values for publishing
Note: The radii used in the calculation are currently coming from the CSD website:
*http://www.ccdc.cam.ac.uk/products/csd/radii*
However there are several ways how the radii can be changed, one of which is to provide  a file name with radii ([element radius] a line format). The other is to load the radii from the same kind of the file using `CODE load radii vdw` command.
