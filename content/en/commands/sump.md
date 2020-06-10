#sump

>A [val=1] [esd=0.01] [part=new_part] [occupancy] [atoms] [-p=1]

>B Creates a new linear equation. If any of the selected atoms has refinable or fixed occupancy, a new variable is added with the value 1/(number of given atoms). Otherwise, an already used variable is used with weight of 1.0. Also look at `CODE part` command.

>D If 3 atoms (A1, A2, A3) are selected, this command will generate three free variables (var1, var2 and var3) and insert the `1 1 var1 1 var2 1 var3` instruction (equivalent to

\begin{displaymath}
1 = 1 \times occ(A1) + 1 \times occ(A2) + 1 \times occ(A3)
\end{displaymath}
