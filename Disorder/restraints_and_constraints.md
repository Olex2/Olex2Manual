# Restraints and Constraints
Some structures need restraints or constraints in order to obtain a chemically reasonable refinement. Constraints will fix items to an exact value, and there are only three of them in ShelXL: EADP, EXYZ and AFIX. Constraints are NOT refined; two (or more) atoms will end up in exactly the same position (EXYZ), or have exactly the same displacement parameters (EADP) and AFIX constraints some or all geometrical parameters. Special cases of constraint is the use of free variables (FVARs) to express occupancy of one atom through the occupancy of the other aka 'linked occupancies' or to introduce a linear dependency on occupancies or $U_{iso}$ and riding $U_{iso}$ -- when the riding atom's $U_{iso}$ is fixed at $k \times U_{iso}$/Ueq of the pivot atom, where k is a constant and typically equals 1.2 or 1.5.
Restraints, on the other hand, are refined parameters, e.g. SADI, SIMU, and others are associated with a value (the weight) that tells the refinement engine 'how much' you would like to enforce them. If you know from your chemical background that two (or more) bonds have to have the same length (for example the N-O distances in nitrate), but for some reason (and this reason is usually disorder!) the refinement presents you with a nitrate where these distances differ, you can help the refinement engine by telling it that these distances are equal (e.g. SADI). If the refinement still returns unequal distances, then you may increase the weight (e.g. SADI 0.005). If this gives you three equal distances, but your R-factor has increased a lot, then you probably don't have a nitrate there, but possibly an acetate.
Care should always be taken to ensure that any constraints or restraints that are applied are chemically sensible and appropriate to the data, and that they are not being used to incorrectly fit the expected model to the data. That said, appropriately used constraints and restraints can be a very useful tool during a refinement, especially if there is insufficient local data, which is often the case with disorder.

## Using Restraints and Constraints
Under Tools are three sub-tab headings with options for applying restraints or constraints. The sub-tab Olex2 Constraints Restraints contains constraints and restraints that will only work within Olex2, while Shelx Compatible Constraints and Shelx Compatible Restraints will be recognisable to users of ShelXL and will work both within Olex2 and ShelXL. When an option is selected from the dropdown menu information about the constraint or restraint will appear below it explaining what the option does and how to use it. If available, an option for extra parameters may appear, for example a standard deviation. A brief summary of the commands available through the GUI panel is supplied below.

## Olex2 Constraints & Restraints
Some of these restraints and constraints are specific to the olex2.refine refinement engine. If you swap between ShelXL and olex2.refine then the instructions will be retained during ShelXL refinement cycles, but will have no effect.
Olex2 Constraints and Restraints
RRINGS 	Restrains selected atoms to lie in a plane and have the same distances. This constructs the relevant ShelXL compatible restraints automatically and is compatible with both engines.
TRIA 	Given the central atom (C) to the two other (X) atoms distance and the X-C-X angle in degrees, this command generates the ShelXL compatible restraint for angle.
ADPUEQ 	Restrains the ADPs of the selected atoms to have similar or given Ueq value.
ADPVOL 	Restrains the displacement parameter of selected atoms to the value provided or if no value is provided they will be restrained to be the same.
ANGLE 	Restrains the angle to the value provided.
DIANG 	Restrains the dihedral angle of the selection to the value provided.

## Shelx Compatible Constraints
It is very easy to apply any SHELX constraints (and restraints) in Olex2. The instructions are fully managed, so you don't have to take care of atom names in this. For example, if you want two atoms to have the same ADP value, you simply select the two atoms and type EADP (or find the corresponding command on the GUI, where you will also find some more information about this command and how to apply it). If you later decide to rename any of the atoms involved in a constraint, this doesn't matter -- Olex2 takes care of this for you.
For the detailed documentation of ShelXL constraints and restraints, please refer to the SHELX manual. A link to this manual is provided on our GUI with George Sheldrick's kind permission
Shelx Compatible Constraints
AFIX 	Constrains molecular geometry to a specified shape.
EXYZ 	The coordinates of selected atoms are constrained to be the same. Useful for occupational disorder.
EADP 	 The ADPs/$U_{iso}$ of selected atoms will be constrained to be the same.

## Shelx Compatible Restraints
Again, these are fully managed: for example, if you wanted to say that two bonds should be restrained to the same length, you would apply the 'SADI' restraint by selecting the two bonds in question (or the atoms that define the bond -- two atoms to define the first bond, then two atoms to define the second bond) and then type SADI (or find the corresponding command on the GUI). In the case when there are no bonds, but two the distances (A-C and B-C) to be restrained share an atom (C), three atoms, A,C and B can be selected to generate the similarity restraint. 
ShelX Compatible Restraints
DFIX	Restrains bond lengths to a particular value d with a standard deviation s.
DANG 	Usually used to restrain 1,3 distances, i.e. to define an angle, which can't be done directly in ShelXL.
SADI 	Restrain bond lengths to similar values with a weight.
CHIV 	Restrains the chiral volume of selected atoms to a specified value V with a weight.
FLAT 	Restrains four or more selected atoms to lie in the same plane within a weight s1.
DELU 	All bonds are subject to a rigid bond restraint, i.e. the ADPs in the bond direction are restrained to be equal with weight s1. The same restraint is applied to the 1,3-distances and if the weight s2 is not supplied it will take the same value as s1.
SIMU 	Restrains the Uij components (essentially the ADPs) of selected atoms, that are less than dmax apart, to have the same value within the standard deviation s.
ISOR 	Restrains the Uij components (essentially the ADPs) of selected atoms to be modelled approximately isotropically within the standard deviation s.
Olex2 automatically puts the correct information into the .ins file when any of the restraint or constraint commands are applied from the command-line or the GUI panel . To adjust the parameters later, you need to edit a file-representation of the constraint or restraint in question. The best way to do this is to select ONE atom that's involved in the restraint/constraint, and then click on @@@@ or type EditAtom. This will open an editor, which will show information related to the selected atom, including any constraints or restraints where you can adjust any of the parameters.