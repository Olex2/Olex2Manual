#hklexclude

>A [-h=h1;h2;.. -k=k1;k2.. -l=l1;l2.. [-c]

>B This function provides a mechanism to reversibly exclude some reflections from refinement (these reflections will be moved to the end of the .hkl file so they appear after the `0 0 0` reflection).

>C **-c**: option controls how the given indices are treated. If no **-c** option is provided, then any reflection having any of the given *h*, *k* or *l* indices will be excluded; otherwise only reflections with indices within provided *h*, *k* and *l* will be excluded.
