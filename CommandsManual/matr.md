#matr

>A [1,2,3 or abc] or [abc a1b1c1] or [x11 x12 x13 y11 y12 y13 z11 z12 z13]

>B Orients the model along a (1 or 100), b (2 or 010), c (3 or 001) or any other crystallographic direction, like 123, which sets current normal along (1*a+2*b+3*c) vector. Two crystallographic directions (from and to) may be specified align current view normal along the (to-from) vector. Also a full Cartesian matrix can be specified. If the directions are signed or consist of multiple digits all components should be of the same length like in 120101 or -1+1+1 (same as -10101). If no arguments given, prints current Cartesian orientation matrix.

>C -r: uses reciprocal lattice instead of the direct

>D matr 1 or matr a or matr 100 - sets current normal along the crystallographic a direction
matr 100 011 sets current normal along (011-100) direction (the normal direction changes if from and to are swapped)