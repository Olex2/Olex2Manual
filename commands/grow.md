#grow

>A [atoms] [-w] [-s]

>B Grows all possible/given atoms. For polymeric structures or structures that require to be grown several times, Olex2 will continue grow until the operation results in a symmetry element that has been used previously.

>C -w: permits the application of previously used symmetry operations to other fragments of the asymmetric unit. In other words: if parts of the structure have been grown, this command will also generate symmetry equivalent atoms that are not connected to the already grown fragment, i.e. solvent molecules.

>D If the main molecule is grown, but only one solvent molecule is shown, using `CODE grow -w` will produce other solvent molecules using symmetry operators used to grow the main molecule.
