#matr

>A [1,2,3 or abc] or [abc a1b1c1] or [x11 x12 x13 y11 y12 y13 z11 z12 z13]

>B Orientates the model along; a (1 or 100), b (2 or 010), c (3 or 001) or any other crystallographic direction e.g. 123, which sets the current normal along the  $(1*a+2*b+3*c)$ vector. Two crystallographic directions (from and to) may be specified to align the current view normal along the (to-from) vector. Also a full Cartesian matrix can be specified. If the directions are signed or consist of multiple digits, all components should be of the same length like in 120101 or -1+1+1 (same as -10101). If no arguments are given, the current Cartesian orientation matrix is printed.

>C -r: uses the reciprocal lattice instead of the direct.

>D `CODE matr 1` or `CODE matr a` or `CODE matr 100` - sets the current normal along the crystallographic a direction. `CODE matr 100 011` sets the current normal along the (011-100) direction (the normal direction changes if from and to are swapped)
