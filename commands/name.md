#name
>A [selection/atom names] [-c] [-s=]

>B The command allows changing the atom names.

>C c: check if the generated names are unique
s: change the suffix only (no value removes the suffix, i.e. the part of label after the element symbol and numerical value)

>D `CODE name O1 O2`: renames O1 to O2
name 1: (some atoms selected) sequentially names the atoms in the order of the selection by adding 1,2, etc to the element symbol. Note that in this case if any generated name is not unique (and the -c option is not given), a random name will be generated
`CODE name $q C`: changes the element type of Q to C - all the electron density peaks will become carbons
`CODE name sel -s=a`: changes suffix of the selected atoms to *a*, replacing any existing suffix. Note that sel is a required keyword in this case (but may be removed in the future)
`CODE name Q? C?`: change type for all electron density peaks with single number label to carbon atoms preserving the number

