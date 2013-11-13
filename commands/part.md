#part

>A [part=new_part] [occupancy] [atoms] [-p=1]

>B Changes part number/occupancy for given/selected atom

>C -lo: links occupancies of the atoms through a +/-variable or linear equation (SUMP) depending on the -p[=1]
-p:  specifies how many parts to create. If -p=1, -lo is ignored and the given or new part is assigned to the provided atoms. If the number of parts is greater than 2 and -lo option is given, a new SUMP restrain will be automatically added.


>D
