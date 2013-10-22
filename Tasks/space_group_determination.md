# Space Group Determination
In most routine cases, space group determination is a fairly fail-safe procedure that you would have carried out (or was carried out auto-matically) during the data processing step. If all worked well, it’s usually not a problem. But things do not always work out this well.
Olex2 contains a space group determination routine in Work | Solve | Suggest SG. The result will appear in the drop-down box (in which you can also type your own choice of space group). Plots of your data are also available: the Wilson plot and the cumulative plot are particularly useful when you have trouble determining the correct space group.
If you have the Rigaku XPlain program on the system path, Olex2 will offer it as an alternative method for the space group determination.
Another option you’ve got is to solve your structure using Superflip -- the charge-flipping algorithm used works in P1 (i.e. it assumes no symmetry at all) and Superflip is able to calculate the correct space group from the solution. This works really rather well, but of course the catch is that a solution must be found in the first place. And often it is the tricky datasets where the space-group determination poses problems that won’t be solved...
## Reflection Data Plots
Olex2 offers a range of different plots that can assist during a refinement; these are located in Info | Reflection Statistics:
### Wilson Plot
This is a statistical comparison of the observed intensity data with the theoretical distribution for a random atomic arrangement which helps with identifying whether the data centric or acentric.
### Cumulative Intensity
Provides an indication of whether the data is centric, acentric or twinned. If the Wilson plot is inconclusive, this graph will often help. It is also a very quick way to check whether your data may be from a twinned crystal!
### Systematic Absences
The intensity distribution of reflections that should be systematically absent (but are not) is plotted. These should all be very weak.
### Completeness
The percentage completeness is plotted against the resolution. For good data this should be ~100% complete in all regions. If the completeness is low (i.e. you find a sharp decrease at higher 2O values, or if sections of data are missing), you will probably find that something isn’t quite right with your final structure. Also, most journals require a minimum completeness for acceptance of a crystal structure for publication. 
### Bijvoet Differences Probability Plot
Similarly to the normal probablility plot above, this plots the ordered deviations between the observed and calculated Bijvoet differences. Frequently it is observed that this plot can deviate from linearity, sug-gesting that the errors are not normally distributed. Hooft et. al (2010) suggested that a Student's t distribution may better describe the errors in the Bijvoet differences. Olex2 can calculate this plot for both the normal and Student's t distribution, allowing you to judge whether or not a Student's t distribution is a better model for the errors in your data.
### Bijvoet Differences Scatter Plot
This plots the calculated Bijvoet differences, Fcalc2(+) -- Fcalc2(-), against the observed Bijvoet differences, Fobs2(+) -- Fobs2(-), along with error bars indicating the uncertainty in the measurement of the Bijvoet differences. For a correct, strongly determined absolute structure, this plot should form a positive slope, with gradient close to 1. A negative slope for this plot can indicate incorrect assignment of the absolute structure, and you should try inverting your structure ( inv -f).
