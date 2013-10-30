# Compatibility with Other Software 
Olex2 comes with its own structure solution and refinement programs: olex2.solve and olex2.refine.
Of course you are not limited to these. Olex2 fully supports a wide range of commonly used crystallographic programs and all relevant settings for these can be set from within Olex2. In some cases, for example ShelXD, the values for some of the required fields are calcuated by Olex2 and are automatically passed through to the external software

##Solution Programs

For most structures, structure solution is not a problem and any structure solution program will do. Some structures will resist solution and many tricks may be required to achieve it. All solution programs have some settings that can be adjusted, and of course it may pay to simply try all available programs and hope that one of these will solve a structure in 'default mode'. For the final structure, it is of course completely immaterial which software was used to solve the structure in the first place. 
- *Superflip* The default structure solution method is Charge Flipping. Other equally powerful methods are also available. In our experience, Superflip has the highest rate of successful structure solution. If the structure is solved, it is also able to deduce the correct space group from the solution, which might be very useful in cases where space group determination by traditional methods is not unambiguously possible.
- *ShelXS* This is probably the default solution program for most crystallographers, it has a very high success rate and is very fast. Two methods are available: ``Direct Methods`` and ``Patterson Methods``.
- *ShelXD* Another solution program based on a dual space approach, this was initially intended to solve protein structures but is also highly successful with small-molecule structures. It is inherently slow, but well worth a shot if other methods fail.
- *SIR2011* Yet another tool in the box. SIR is the default choice for many and reliably solves structures.

##Refinement Programs

ShelXL

##Other Software

- SADABS (Bruker users only)
- XP (Bruker Users only)
- Platon

For academic users ShelXS and ShelXL, written by George Sheldrick, are freely available from http://shelx.uni-ac.gwdg.de/SHELX/ . If these already exist on your computer Olex2 will normally be able to locate them automatically. If this does not occur, it is necessary to specify the path to these files on your computer and add their location to the PATH line under the environment variables on your computer. Olex2 is currently also aware of XP (Bruker), SADABS, SIR and Platon.
