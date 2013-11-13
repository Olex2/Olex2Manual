#tria

>A d1 d2 angle [esd=0.02]

>B For given set of bond pairs sharing an atom or atom triplets generates two dfix commands and one dang command.

>C

>D `CODE tria 1 1 180 C1 C2 C3` will generate `CODE DFIX 1 0.02 C1 C2  C2 C3` and `CODE DANG 2 0.04 C1 C3` it will calculate the distance for dang from d1 d2 and the angle.