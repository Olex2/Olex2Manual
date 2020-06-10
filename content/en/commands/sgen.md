#sgen

>A atoms

>B Generates symmetry equivalents of the selected atoms (or all atoms, if there is no selection) using the provided symmetry operation.
Note: For symmetry operations starting with `-` and a letter, a leading zero must be added or the expression has to be quoted (for example, `0-x,-y,-z`), otherwise Olex2 confuses this with an option. The Symmetry operation is represented as `1_555, 1555` or `-1+X,Y,Z` and atoms as a selection or a names list. As a special case, twelve numbers can be provided to specify any matrix operating on the fractional coordinates (e.g. see the match)
