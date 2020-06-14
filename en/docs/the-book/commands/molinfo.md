#molinfo

>A [radii file name] [atoms] [-g=5] [-s=o]

>B Calculates molecular volume and surface area for all/selected atoms.

>C
 * **-g**: generation of the triangulation process
 * **-s**: source of the triangles for the sphere triangulation, [o]ctahedron or [t]etrahedron are available. Generation 5; for octahedron-approximate sphere by 8192 triangles, for tetrahedron by 4096 triangles. Each generation up increases the number of triangles by factor of 4, generation down - decreases by the same factor.
