#conn

>A n [r] atoms

>B Sets the maximum number of bonds for the specified  atoms to n and changes the default bond radius for the given atom type to r.

>D `CODE conn 5 $C` sets the maximum number of bonds all C atoms can have to 5,
`CODE conn 1.3 $C` changes the bonding radius for C atoms to 1.3 (the floating point is used to distinguish between n and r in this case!),`CODE conn 5 1.3 $C` combines the two commands above
