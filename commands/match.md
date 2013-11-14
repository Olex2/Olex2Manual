#match

>A [atoms] [-a] [-w] [-i] [-n] [-u] [-esd] [-h] [-cm] [-o]

>B This procedure find relation between the connectivity graphs of molecular fragments of loaded structure and aligns the fragments. If no arguments are given, the procedure analyses all fragments and in the case fragments with matching connectivity found, aligns Acta A45 (1989), 208  them and prints corresponding root mean square distance (RMSD) in angstroms. If two atoms are provided (explicitly by name or through the selection) the graph relation information - orientation matrix and the matching atoms is printed, use -a option to align the fragments.

>C -a: align the fragments (used when a pair of atoms is provided)
-w: specifies weight for the atomic positions - by default the unit weights are used. If this option is given - the atomic position are weighted by the element mass 
-i: try to invert one of the fragments
-n: transfer labels from one fragment to another (two atoms should be provided for from and to fragments. If the value a symbol [or set of] this is appended to the label, *$xx* replaces the symbols after the atom type  symbol with xx, leaving the ending, *-xx* - changes the ending of the label with *xx*. Note that if the molecules match with -i options, this should also be provided for the label transfer
-u: restores the coordinates of the matched fragments, this is useful if grown structure is matched
-esd: if the variance-covariance matrix can be located (after the refinement with the negative MORE option in the xl), the esd on the RMSD can be calculated using this option
-h: does the final matching and RMSD calculation and without taking H-atoms into account
-o: when overlaying molecules from different structures, whole lattices (if packed/grown) are overlayed, not only the two fragments. To use -- select an atom in a fragment of one lattice and an atom in a matching fragment of the other lattice.
When a selection of two atoms is given the command prints the alignment matrix. This matrix alongside the sgen command can be used to generate new atoms. Use the *-cm* option to copy the matrix to the clipboard.
