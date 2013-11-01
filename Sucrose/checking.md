#Checking the Structure

During a refinement there are a number of checks that should be made after each refinement cycle.

- Check that all of the ADPs are of a similar size throughout the structure and look sensible (the ellipsoid axes should not appear significantly different).

- Check that the correct number of hydrogen atoms are present and that they are appropriately positioned.

- Go to the Info tab and open the Refinement Indicators header tab if there are any errors some or all of the parameters will be orange (potential moderate problem) or red (potential serious problem). These should improve as the refinement proceeds. Attempts should always be made to correct these or be able to explain why they are not ideal.

- Check that the bond lengths and angles are sensible. There are several ways to do this: 

-- Hover over a bond and the bond length will be displayed; left click on the bond to select it and then right click to view the bond length. 

-- Select 2 atoms for a bond length, 3 atoms for a bonded angle or 4 atoms to get a torsion angle, then go to the View tab, under the Geometry header tab click on Distance and Angles (of selection).

-- Right click on an atom or bond in a molecule under Fragment -- Select bonds will highlight all bonds. Under `Tools|Images` select Label selected atoms. To delete bond labels it is necessary to be in `Tools|Images`. Depending on what had been carried out in the interim time period, pressing CTRL+A will either select the bond length labels (in which case press delete) or the atoms and bonds in which case press CTRL+I to invert the selection, the bond length labels will now be selected press delete.

-- The Cambridge Structural Database is an excellent resource to use to check that your bond lengths and angles are sensible and within expected ranges. If they are not, investigate why not!

>OLEX2 The sel command can be always used in the command-line to print information regarding the current selection.

### What To Look For In a Good Refinement

#### All of the ADPs are chemically sensible
The 'thermal ellipsoids' of the atoms should all look similar and of approximately the same dimensions. If there are some really large or really small ones, then there's something wrong. If there are some that are very elongated or very 'squashed', then that's also not right.

#### No residual L.S. Shift
Check that the Max Shift is very close to 0 in the top panel, if it is not, the refinement has not converged and further cycles of refinement should be carried out. If convergence can't be achieved using further cycles for refinement the reasons for this need to be investigated, for example overuse of restraints. Often you find that the largest shifts are associated with hydrogen atoms that have not been appropriately constrained. Click on the label that tells you about the largest shift and the 'culprit' will be selected!

#### Good R factors: R1 and wR2
R1 and wR2 should be as small as possible. wR2 is always larger than R1 due to the way it is calculated. The expected values depend both on the type of structure that is being solved and the quality of the data e.g. for a molecular organic compound an R1 ~5-7% and wR2 ~10-15% is reasonable. If heavy elements are involved, the final R-factors will be considerably lower. This is because a larger proportion of the electrons in the molecule are in the metal, and we can typically pinpoint the position of these very accurately. Associated with wR2 (and also the weighting scheme) is the Goodness of Fit (GooF) parameter, which should be close to 1. If it deviates a lot (say, larger than 1.2 or smaller than 0.8), there is a problem.

#### The Highest Peak and Deepest Hole
The Highest Electron Density Peak and Deepest Electron Density Hole should be small and approximately equal for a molecular organic compound ~0.5 e/A. If the structure contains a heavy atom e.g. a transition metal, Cl or Br slightly larger peaks might be expected particularly in the vicinity of the heavy element. You can click on the Q-peak and type `CODE envi`, or right-click on it and then choose 'BANG' (which stands for Bonds ANGgles) to calculate the distance of any suspect residual peak to the heavy element.

#### Data/Parameter Ratio
This one is a tricky one -- because there really isn't much you can do to fix it if this should become a problem: the ratio of the number of reflections (observed parameters) to refinement variables (model parameters) should be no less than 8 to 1. If enough data have not been recorded, e.g. a very weakly diffracting crystal, very small sample or high pressure data -- it may be necessary to reduce the number of refinement parameters using constraints.
