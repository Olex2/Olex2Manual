#sort
>A [m] [l] [p] [h] [z] [n] [s] atoms
[s] [h] [m] moiety

>B The sorting of atoms in the atom list is very powerful, but also quite complex.

>C -m: atomic weight
-z: atomic number
-l: label, considering numbers
-p: part, 0 is first followed by all positive parts in ascending order and then negative ones
-h: to treat hydrogen atoms independent of the pivot atom.
-s: non-numerical label suffix
-n: number after the atom symbol

Sorting of moieties
-s: by size
-h: by heaviest atom
-m: by molecular weight

>D `CODE sort [+atom_sort_type]` TBA
`CODE sort [Atoms] [moiety [+moiety_sort_type] [moiety_atoms]]` If just *moiety* is provided - the atoms will be split into the moieties without sorting.
Examples:
`CODE sort +m1 F2 F1 moiety +s` will sort atoms by atomic mass and label, put F1 after F2 and form moieties sorted by size. Note that when sorting atoms, any subsequent sort type operates inside the groups created by the preceding sort types.
