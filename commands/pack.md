#pack

>A a_from a_to b_from b_to c_from c_to [atoms]

>B Packs all or specified atoms within given dimensions

>C -c: prevents clearing existing model

>D `CODE pack $O` will pack all O atoms with the default of -1.5 to 1.5 cells range.

>A from to

>B Equivalent to 'pack from to from to from to', like 'pack 0 1' is expanded to 'pack 0 1 0 1 0 1'

>A Cell

>B Shows content of the unit cell. In conjunction with 'grow -w' allows the creation of views where all asymmetric units contributing to the unit cell are shown.

>A Wbox

>B Packs the volume inside the 3D selection box (the once can be shown by selecting at least 3 atoms and typing 'sel wbox'), to pack multiple boxes - use '-c' option.

>A R

>B Packs fragments within radius r of the selected atom(s) or the centre of gravity of the asymmetric unit.
