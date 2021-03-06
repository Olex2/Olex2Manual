\chapter{Glossary}

This is a collection of terms that require some form of definition. Neither the list or the definitions provided here are complete; please refer to the various excellent sources of information that are available on the internet for more information.

\small

TWOCOLUMNS

**Anisotropic displacement parameters**,  *ADP* or $U_{ij}$**:  Six parameters are used to define an ellipsoid representing the thermal motion of an atom.

**Asymmetric unit**: The smallest fraction of the crystal structure which by application of the symmetry elements can be used to define the contents of a unit cell.

**BASF**: this is a twin scale factor which is refined for a twinned structure to determine the fraction of each component that is present.

**Bragg's Law**: fundamental in crystallography. This gives the conditions under which diffraction will occur and thus diffracted beams will be observed. Essentially it defines the conditions for waves to combine constructively and thus give intensity. To observe diffraction, there must be an integer number of wavelengths between diffracted X-rays from parallel planes ($n\lambda$).

{2d sin\theta = n\lambda}

$d$: interplanar spacing, $\theta$: incident angle, $n$: an integer known as the order of the reflection, $\lambda$: wavelength

**CIF**: Crystallographic Information File, contains all of the important information on the crystal, experimental parameters, refinement indicators, atomic parameters and geometric information on the structure. These are essential for publication and care should be taken to ensure that all of the information is correct and as much as possible supplied.

**Constraints** are used to fix parameters to certain values. An alternative is a restraint which is softer.

**Difference map**: max and min (also known as *highest peak*/*deepest hole*). Values indicate residual electron density peaks and holes in units of e/A. The closer the values to zero the better.

**Disorder** indicates that not all of the asymmetric units are identical, for example longer chains which are flexible such as butyl groups often show positional disorder within the structure, with some asymmetric units containing the molecules in one orientation and others in a slightly different orientation.

**Ellipsoid**: The anisotropic displacement parameters are usually visualised by displaying an atom as an ellipsoid. If these ellipsoids are relatively large or small - or look distorted - then this usually indicates a problem with the refinement.

**$F$**: the structure factors has a phase and amplitude associated with it.

**Flack \thinspace $x$**: applicable to non-centrosymmetric structures the Flack parameter can indicate whether the absolute structure is correct. The parameter is calculated with an esd which should be examined to assess whether the analysis is meaningful. A value of 1 with a small esd indicates that the absolute structure should be inverted, while 0 with a small esd suggest that the absolute structure is correct. A value of 0.5 may suggest that a centre of symmetry has been missed, while values in between 0 and 1 could indicate the presence of racemic twinning.

**Free variable (FVAR)**: The first number on the FVAR line corresponds to the overall scale factor for the data and should not be edited. Subsequent numbers can be used to link to parameters that are being refined e.g. if the occupancy of two atoms needs to be linked or the isotropic displacement parameter. For example 21.000 means 1 x free variable 2 (i.e. the 2nd number on the FVAR line, before refinement here 0.75). --21.000 means 1 -- (1 $\times$ free variable 2) in other words the occupancy of the two parts adds to 1.

**$GooF$**: The Goodness of Fit values should converge to 1.0 for a very good structure at the end of the refinement.

\begin{displaymath}
GooF = (S[w(F_{obs}^{2}-F_{calc}^{2})2] / (n-p))^{1/2}
\end{displaymath}

$w$: weight, $F_{obs}$: observed structure factors, $F_{calc}$: calculated structure factor, $n$: number of reflections, $p$: total number of parameters

**Hooft \thinspace $y$**: An alternative to the Flack parameter, uses an analysis of Bijvoet-pairs to determine the absolute structure of a compound (R. W. W. Hooft, L. H. Straver, A. L. Spek (2008) *J. Appl. Cryst.*, **41**, 96-103).
$I(F^{2})$: the measured intensity of a reflection.

**.ins file**: The .ins file is the instruction file which initially contain information on the radiation used, cell parameters (and esd), structure factor cards relating to the specific atom types, the number of each atom type, the space group (in the form of LATT and SYMM instructions) and the format of the .hkl file. At the end of a structure solution and refinement the .ins file will contain information about your atom positions, their thermal parameters and any restraints/constraints that have been used.

**Isotropic displacement parameters ($U_{iso}$)**: one parameter is used to define a sphere to represent the average thermal motion of an atom.

**_.hkl_ file**: The .hkl file contains the information on the reflections. The format can vary slightly depending on the type of data e.g. X-ray, neutron, twinned and an instruction is supplied in the .ins file to specify the type of reflection file that is being used.

**Laue group** gives information on the symmetry of the diffracted intensities. There are 11 Laue groups.

**Non positive definite (N.P.D.)**: a physically impossible state in which one or more of the displacement parameters has become negative. Large numbers of atoms that are non-positive definite need investigation and can be caused for a variety of reasons, for example, an incorrect atom assignment, incorrect space group, twinning or weak data.

**Occupancy** is used to define the fraction of an atom modelled in a particular location, for most atoms this will be 1 indicating that they are fully occupied. However, when disorder is present the two (or more) parts could not both be present in the asymmetric unit at the same time, hence as an average across the structure they are fractionally occupied e.g. one part 0.8 and one part 0.2. This means that 80% of the asymmetric units contain the molecule in one orientation and 20% contain the molecule in the second orientation.

**Phase problem** Like all waves, X-rays have both a phase and amplitude associated with them, however during a diffraction experiment we are only able to measure the amplitude of a reflection ($\sqrt{I} = F$) not its phase. In order to solve a structure it is essential to determine the relative phase of each reflection in order to add all of the waves together correctly.

**Q-peaks**: represent peaks or troughs (depending what is plotted) in the difference electron density map. The size of them gives an indication of their significance and whether or not they indicate a missing atom.

**Restraints**: are used to restrain a parameter to a particular value within a user-defined error. They are softer than constraints which fix values.

**R1**: a standard measure of the quality of the agreement between Fo and Fc. A very large R1 value suggests an incorrect solution and a need to try more rigorous structure solution routines.

\begin{displaymath}
R1 = S| |F_{obs}| - |F_{calc}| | / S |F_{obs}|
\end{displaymath}

$F_{obs}$: observed structure factors, $F_{calc}$: calculated structure factors

**_.res_ file**: The .res file contains essentially all of the information in the .ins but after the last refinement cycle so some instructions that have been implemented may no longer be present e.g. AFIX or ANIS. There will also be information on the highest residual peaks.

**$R_{int}$**: Measure of how "equivalent" symmetry equivalent reflections really are. The lower the **Rint**, the better. A high value indicates bad data, poor absorption correction, or wrong space group (i.e. Laue symmetry).

\begin{displaymath}
R_{int} = S | F_{obs^{2}} - F{obs^{2}mean} | / S F_{obs^{2}}
\end{displaymath}

**Space Group** will be one of 230 possible space groups, these give information on the complete symmetry of the crystal structure.

**Systematic absences** these are systematically absent reflections which do not appear in the diffraction pattern as a result of the symmetry of the space group. The presence of certain groups of systematic absence can be used to identify symmetry elements or lattice centring that is present in a particular crystal lattice and help to identify the space group for the structure.

**$U_{ij}$**: see anisotropic displacement parameters

**$U_{iso}$**: see isotropic displacement parameters

**Unit Cell**: represents the fraction of the crystal structure which repeats by translation. The unit cell parameters consists of 3 unit cell axes (a, b and c) and 3 unit cell angles (alpha, beta and gamma) which define a parallelepiped. There are multiple unit cell choices available and conventions exist for selecting a unit cell, the smallest choice is the reduced cell but for various reasons a slightly larger cell may be selected. The unit cell will be one of the 7 crystal systems and 14 Bravais lattices.

**wR2**: a standard measure of the quality of the agreement between Fo and Fc. A very large wR2 value suggests an incorrect solution and a need to try more rigorous structure solution routines.

\begin{displaymath}
wR_2 = (S [w(F_{obs}^{2} - F_{calc}^{2})2] / S [w(F_{obs}^{2})2]
\end{displaymath}

$w$: weighting scheme, $F_{obs}$: observed structure factors, $F_{calc}$: calculated structure factor)

**Z** and **Z'**: Z is the number of formula units in the unit cell, Z' is the number of formula units in the asymmetric unit.

NOCOLUMNS
