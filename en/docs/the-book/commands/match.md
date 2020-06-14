#match

>A [atoms] [-a] [-w] [-i] [-n] [-u] [-esd] [-h] [-cm] [-o]

>B This procedure finds the relationship between the connectivity graphs of molecular fragments of loaded structure and aligns the fragments. If no arguments are given, the procedure analyses all fragments and in the case when fragments with matching connectivity are found, it aligns Acta A45 (1989), 208 and prints corresponding root mean square distance (RMSD) in angstroms. If two atoms are provided (explicitly by name or through the selection) the graph relation information - orientation matrix and the matching atoms - is printed. Use `CODE -a` option to align the fragments.

>C
 * **-a**: align the fragments (used when a pair of atoms are provided)
 * **-w**: specifies weight for the atomic positions - by default the unit weights are used. If this option is given, the atomic position are weighted by the element mass. 
 * **-i**: try to invert one of the fragments.
 * **-n**: transfers labels from one fragment to another (two atoms should be provided as 'to' and 'from' fragments). If the value is a symbol (or a set thereof) this is appended to the label. `CODE $xx` replaces the symbol after the atom type symbol with xx, leaving the ending. `CODE -xx` changes the ending of the label TO xx. Note that if the molecules match with `CODE -i` options, this should also be provided for the label transfer.
 * **-u**: restores the coordinates of the matched fragments - this is useful if the grown structure is matched.
 * **-esd**: if the variance-covariance matrix can be located (after refinement with the MORE negative option in the xl), the esd on the RMSD can be calculated using this option.
 * **-h**: calculates the final matching and RMSD calculation without taking H-atoms into account.
 * **-o**: when overlaying molecules from different structures whole lattices (if packed/grown) are overlayed, not only the two fragments. To use, select an atom in a fragment of one lattice and an atom in a matching fragment of the other lattice.
When a selection of two atoms is given the command prints the alignment matrix. This matrix alongside the `CODE sgen` command can be used to generate new atoms. Use the `CODE -cm` option to copy the matrix to the clipboard.
