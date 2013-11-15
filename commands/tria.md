#tria

>A d1 d2 angle [esd=0.02]

>B For a given set of bond pairs, sharing an atom or atom triplet generates two `DFIX` commands and one `DANG` command.

>D `CODE tria 1 1 180 C1 C2 C3` will generate `DFIX 1 0.02 C1 C2 C2 C3`.
\par
`CODE DANG 2 0.04 C1 C3` will calculate the distance for DANG from d1 d2 and the angle.
