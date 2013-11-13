#zoom

>B To get current value of the scene zoom use:
`CODE echo zoom()`
To set current zoom to a certain value use:
`CODE zoom(eval(Value-zoom()))`
this can be used to put different structures to the same scale. Note that the value 1 corresponds to the scale when the smallest dimension of the screen view is 1 Angstrom
To reset zoom to default for current model use:
`CODE gl.zoom`
