#Importing Fragments

It is possible to import "fragments" into Olex2. A fragment is typically a molecule (often a solvent molecule or a counter ion), and you might want to import it because the entity turns out to be disordered. Imported fragments can be fully constrained or resrained, so that the relative position of the atoms in the fragment does not change (i.e. it is imported as a "rigid body").

Ilia Guzei maintains a library of common fragments, and there is a link to this library from Olex2 at `@Tools|Disorder` (http://bit.ly/2fwt8yE)

If you have trouble with a chloroform molecule, for example, then you will find this bit of text on Ilia's page:

    FRAG 17
    CL1 5  1.692203  0.000000 -0.571985
    CL2 5 -0.846102  1.465491 -0.571985
    CL3 5 -0.846102 -1.465491 -0.571985
    C1  1  0.000000  0.000000 -0.032312
    H1  2  0.000000  0.000000  1.058268
    FEND

All you need to do to import this fragment as a rigid body into Olex2 is this:

1. Make sure you have only electron density peaks (Q-peaks) where the chloroform will go.
2. Highlight the text on Ilia's page in your browser
3. Copy it on the clipboard (CTRL+C)
4. Paste it into Olex2 (CTRL+V)
5. Overlay corresponding Q-peaks and atom pairwise. So first you click on Q1, then one of the Cl atoms. Then Q2, followed by another of the Cl atoms. And so on. You may have to practice this 'matching' for a bit, and once you get familiar with how this works you will find it easy.

That's it. The molecule is now in your model, and it's fully constrained as a rigid body. It can only move laterally and rotate, but all atoms within the molecule will stay in their relative positions.

Another way to import fragments is to make use of the ImportFrag command. This command will open a file explorer, and you may then select any .xyz file that contains the fragment you wish to import. In order to import is as a rigid body, you must use the command: `CODE ImportFrag -a=6`

The full options for `CODE ImportFrag` are these:

**-a**: sets AFIX to the imported molecule
**-d**: generates DFIX for 1,2 and 1,3 distance for the imported molecule
**-p**: sets given part to the imported molecule

You may export a fragment (i.e. from a "healthy" structure) using the `CODE ExportFrag` command. This will generate an xyz file for use with `CODE ImportFrag'.