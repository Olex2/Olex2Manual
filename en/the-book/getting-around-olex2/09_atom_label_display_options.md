# Atom Label Display Options
> How to display and label atoms

Olex2 offers a large range of properties that can be displayed as labels on atoms. This provides immediate feedback on these properties of the atoms: `@Work|Toolbox-Work|Labels`:

- @@Labels On/Off@@  show or hide atom name labels and Q-peak labels (alternatively press F3). This will switch other types of labelling off but selecting it again will display atom name labels.
- @@Atom Names@@  F3 shows non-hydrogen atom and Q-peak labels
- @@Crystallographic Occupancy@@ \index{crystallographic occupancy} displays the occupancy of any atoms. Please note that atoms in special positions will also display a number, but this does not mean that the site is not fully occupied. Unless you really know what you are doing, the *Chemical Occupancy* choice is probably the one you want.
- @@Chemical Occupancy@@ \index{chemical occupancy} displays the occupancy of any atoms which are not 100% occupied i.e. their occupancy is not 1. As opposed to the *crystallographic occupancy*, \index{occupancy} the multiplicity of atoms in special positions will be taken into account. An atom on a center of inversion has a crystallographic occupancy of 0.5, but from a chemical point of view it is fully occupied. So in this mode, if there is a number displayed next to an atom, this means it is a partially occupied site.
- @@Parts@@  displays part numbers for atoms that are not in PART 0. By default, all atoms are in PART 0, unless they have explicitly been assigned to another part.
- @@Link-Code@@  this is displayed ShelX FVAR style: `21` and `-21` etc. This denotes atoms whose occupancy is linked: The occupancies of atoms in `21` and `-21` have to add up to unity.
- @@H Atom Labels@@  will include the hydrogen atom labels along with the atom name and Q-peak labels.
- @@Fixed Parameters@@  if any parameters are fixed, these will be displayed as the atom label: _occupancy_, _xyz_, Ueq.
- @@Variables@@  displays all variables associated with the atom.
- @@AFIX Commands@@  useful to check the AFIX commands that are being applied to the structure.
- @@Q-Peak Intensities@@  intensities of the Q-peaks will be displayed.
