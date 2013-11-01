#Tidying the Structure

1.	The key numbers to look at are R1, wR2, Difference map: max and min, GooF, Hooft y and Flack x which should be examined after each refinement cycle.
>The values of R1 and wR2 are an indication of the agreement between Fc and Fo and should decrease as the refinement proceeds; very high values of R1/wR2 (e.g. > 40/70 respectively) suggest that the structure solution is incorrect. Difference map: max and min gives information on the highest and lowest peaks and holes in the electron density map. GooF is the goodness of fit of a structure and should converge towards 1 at the end of the refinement. Hooft y and Flack x are applicable only to structures in non-centrosymmetric space groups (i.e. not containing an inversion centre). They are displayed with an error and should be close to zero if the structure solution is correct, while ~1 implies the structure should be inverted and values significantly different from 0 or 1 indicate a racemic twin.

2.	Check that the chemical composition is correct and there are no extra or missing atoms. If there is an error in Toolbox Work the atom types will not appear green. To update the chemical composition to agree with the structure displayed on the screen under `@Work|Toolbox Work' click on I_OK and then refine again.

3.	Go to the Info tab and open the Bad Reflections header tab if there are one or two reflections that have very large $|F_{calc}^{2}-F_{obs}^{2}|/esd$ values they may need to be omitted. Such reflections will be obvious as their values will be significantly out of line with the rest of the reflections. If it seems necessary to omit more than a handful of reflections, there is probably a reason that should be investigated. 
	
>CRYST Do not omit reflections until all of the atoms have been located as the poorly fitting reflections are affected by missing atoms, for example low angle reflections often appear badly fitting prior to the addition of hydrogen atoms.
