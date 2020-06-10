# Compatibility with Other Software
> Olex2 will make use of plenty of other crystallographic software

Olex2 comes with its own structure solution and refinement programs: olex2.solve and olex2.refine. Of course, you are not limited to these. Olex2 fully supports a wide range of commonly used crystallographic programs and all relevant settings for these can be set from within Olex2. In some cases, for example, ShelXD, the values for some of the required fields are calculated by Olex2 and are automatically passed through to the external software

##Solution Programs

For most structures, structure solution is not a problem and any structure solution program will do. Some structures will resist solution and many tricks may be required to achieve it. All solution programs have some settings that can be adjusted, and of course, it may pay to simply try all available programs and hope that one of these will solve a structure in "default mode". For the final structure, it is of course completely immaterial which software was used to solve the structure in the first place.

- iiiShelXTiiiidx is the latest of George Sheldrick's structure solution programs, and it is easily the best. The solution method employed here is called 'intrinsic phasing' and is a mixture of direct and dual space methods. Its solution success rate is very high, and, since the structure solution happens without assuming any symmetry at all (i.e. it solves in $P1$), the correct space group can often be determined simply by solving with ShelXT (the same is true for Superflip, see below!). After the structure solution in ShelXT, a few cycles of refinement are added and the what is returned is very often the completely assigned structure. If heavy elements are found during the solution process, but none are in the formula, ShelXT will place heavy halogens (Br or I) in their place, so watch out for this!

>OLEX2 The first program called 'shelxl.exe' will be the default ShelXL version for Olex2. It is entirely up to you to decide which one this should be, but we _strongly_ advise that you use the latest stable verison of ShelXL -- i.e. 2014/7 (at the time of writing).

- iiiSuperflipiiiidx The default structure solution method of Superflip is iiiCharge Flippingiiiidx. Other equally powerful methods are also available. In our experience, Superflip has a very high rate of successful structure solution. If the structure is solved, it is also able to deduce the correct space group from the solution, which might be very useful in cases where space group determination by traditional methods is not unambiguously possible.

- iiiShelXSiiiidx probably used to be the default solution program for most crystallographers, since it has a very high success rate and is very fast. Two solution methods are available: iiiDirect Methodsiiiidx and iiiPatterson Methodiiiidx.

- iiiShelXDiiiidx Another solution program based on a 'dual space' approach, this was initially intended to solve protein structures but is also highly successful with small-molecule structures. It is inherently slow, but well worth a shot if other methods fail.

- iiiSIR2011iiiidx Yet another tool in the box. SIR is the default choice for many and reliably solves structures.

- iiiolex2.solveiiiidx Uses a charge flipping algorithm. A fairly high completeness is required for this solution program to work, however

##Refinement Programs

- iiiShelXLiiiidx The is probably the default refinement program for most crystallographers.  There are two options L.S. which uses full matrix least-squares refinement and CGLS which employs a block refinement.  A full matrix least-squares refinement should always be used for the final refinement cycles. For many years, ShelXL-97 used to be the default program for most, but since about 2013, there have been new versions of ShelXL. Of these, the most stable version to date is iiiSheXL-2016/6iiiidx.

- iiiolex2.refineiiiidx This also has two options for refinement Gauss-Newton (full matrix least squares) and Levenberg-Marquardt (block refinement method).  A full matrix least squares should always be used for the final refinement cycles. This refinement package is based on the iiicctbciiiidx and has been developed from scratch by the Olex2 team.

##Other Software

- iiiSADABSiiiidx (Licenced Bruker users only) is recognised -- simply type `sadabs` in Olex2, and it will open with the current data loaded.

- iiiXPiiiidx (Licenced Bruker users only) is similarly recognised. After it is opened, Olex2 will be in a 'listening mode' and any changes you make in XP and then save will automatically be loaded into Olex2.

- iiiPlatoniiiidx is almost a requirement for performing structure analyses. It is packed with

For academic users, all ShelX programs, written by George Sheldrick, are freely available from http://shelx.uni-ac.gwdg.de/SHELX/ . If these already exist on your computer, Olex2 will normally be able to locate them automatically. If this does not occur, it is necessary to specify the path to these files on your computer and add their location to the PATH line under the environment variables on your computer. Olex2 is currently also aware of XP (Bruker), SADABS, SIR and Platon.
