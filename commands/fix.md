#fix

>A {occu, xyz, Uiso} [atoms]

>B Fixes the specified refinement parameter, ie these parameters will not be refined in subsequent refinement cycles.

>C -occu: will fix the occupancy 
-xyz: will fix the xyz coordinates
-Uiso: will fix the whole ADP


>D `CODE fix occu 0.5`: will set and fix the occupancy of the current selection to 0.5
`CODE fix xyz`: will fix the x, y and z co-ordinates of the currently selected atoms, ie not refine them. 
