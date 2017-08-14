# Tidying the Structure

1.  The key numbers to look at are R1, wR2, *max* and *min* Q peak values (also called highest peak and deepest hole), *Goof*\index{GooF}, *Hooft* \index{Hooft $y$ parameter} and *Flack*\index{Flack $x$ parameter} which you should examine after each refinement.

    - The values of R1 and wR2 are an indication of the agreement between Fc and Fo and should decrease as the refinement proceeds. Very high values of R1/wR2 (e.g. > 40/70 respectively) suggest that the structure solution is incorrect.
    - **Q peaks**: *max* and *min* gives information on the highest peaks and deepest holes in the electron density map.
    - GooF is the goodness of fit of a structure and should converge towards 1 at the end of the refinement.
    - **Hooft $y$** and **Flack $x$** are applicable only to structures in non-centrosymmetric space groups (i.e. *not* containing an inversion centre). They are displayed with an error and should be close to zero if the structure solution is correct, while ~1 implies the structure should be inverted and values significantly different from 0 or 1 indicate a racemic twin.

2.  Check that the chemical composition is correct and there are no extra or missing atoms. If there is an error, in `@Toolbox-Work` the atom type buttons will not be green. To update the chemical composition to agree with the structure displayed under `@Work|Toolbox Work` click on I_OK and then @@Refine@@ again.

3.  Go to the `@Info` tab and open the `@Bad Reflections` header tab if there are one or two reflections that have very large $|F_{calc}^{2}-F_{obs}^{2}|/esd$. These values they may need to be omitted. Such reflections are evident as their values are significantly out of line with the rest of the reflections. If it seems necessary to omit more than a handful of reflections, there is probably a reason that reason should be carefully investigated.

    >CRYST Do not omit reflections until all of the atoms are located, as the poorly fitting reflections are affected by missing atoms. For example, low angle reflections often appear badly fitting before the addition of hydrogen atoms.
