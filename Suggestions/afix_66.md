#AFIX 66 and disorder

AFIX 66 does not work in disorder cases where atoms are shared between the two parts. In those cases, the only way we can deal with the disorder is by duplicating shared atoms on the same site (exyz). I think it would be really good if Olex2 could set this up automatically when using the "mode split" tool or manual ways in generating the disorder model.