#calcfourier

>A {-calc,- diff, -obs, -tomc} [-r=0.25 ANGST] [-i] [-scale=simple] [-fcf]

>B Calculates Fourier for current model.

>C
**-r**: the resulting map resolution in ANGST
**-i**: integrates the calculated map
**-scale**: when Olex2 calculates structure factors, it uses the linear scale as a $sum(F_o^2)/sum(F_c^2)$ by default, however a linear regression scale can be also used (use -scale=regression)
**-fcf**: Olex2 will use an FCF with LIST 3 structure factors as a source of the structure factors. If this option is not specified, Olex2 will calculate the structure factors using the the reflection used in the refinement (use the `CODE hklstat` command to see more information on reflections).
