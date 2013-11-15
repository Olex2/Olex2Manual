#zoom

>B To get the current value of the scene zoom use:
`CODE echo zoom()`
To set current zoom to a certain value use:
`CODE zoom(eval(Value-zoom()))`
This can be used to put different structures on the same scale. Note that a value of 1 corresponds to the scale where the smallest dimension of the screen view is 1 Angstrom.
To reset zoom to default for the current model use:
`CODE gl.zoom`
