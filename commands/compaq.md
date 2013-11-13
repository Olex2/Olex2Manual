#compaq

>A [-a] [-c] [-q] [-m]

>B Moves all atoms or fragments of the asymmetric unit as close to each other as possible. If no options are provided, all fragments are assembled around the largest one.

>C -a: assembles broken fragments
-c: similar to the default behaviour but considers atom-to-atom distances. It will move all atoms as close as possible to the largest fragment in the structure.
-q: moves the electron density peaks closer to the atoms.
-m: disconnects metals, then does compaq -a and then reattaches the metals.
