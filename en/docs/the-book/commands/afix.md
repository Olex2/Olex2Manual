#afix

>A number{mn}[-n]

>B If no atoms are provided and afix corresponds to a fitted group where *n* is 6 or 9 (such as 106 or 79), all the rings which satisfy the given afix will be automatically made rigid (this is useful in the case of many PPh3 fragments). Alternatively a single ring atom can be selected to make that ring rigid. In other cases, depending on afix, either 5,6 or 10 atoms will be expected. In special cases of afix, 0, 1 and 2 can be used to remove afix, fix all parameters or leave just the coordinates refinable. All other afix instructions will consider the first atom as a pivot atom and the rest as dependent atoms.
The AFIX command can also be used to generate missing atoms to complete rings or fragments. For example, the following command generates three missing atoms in positions 4,5 and 6 for the Ph ring when applied to a selection of 3 atoms (assumed to be in positions 1, 2 and 3):
`CODE AFIX 66 1,2,3`
Note that there are no white spaces between the identification of the selected positions.

>C
 * **-n**: consider *n*-atoms as parts of rings
