#constrain

>A U [atoms]
>A Site or xyz [atoms]
>A Same group [n=2 atoms]

>B This is a generic macro to generate constraints.  Constrain U generates EADP constraint, site or xyz -- EXYZ.

The same group or non-crystallographic symmetry constraint makes two or more groups identical and linked through a transformation matrix, refined as a shift and 3 Euler angles. If two atoms are given, they must belong to two identical fragments; Olex2 will then try to match the fragments containing the atoms and automatically generate the constraint. In more generic/complex cases the user has to provide the number of groups to generate the constraint for and also the selection which matches atoms in the fragments. 
