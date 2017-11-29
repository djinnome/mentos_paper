## Probability distribution of the reactions in a metabolic network ##
\We define the probability that a reaction in the metabolic network will fire by normalizing the thermodynamic driving force of each reaction by the sum of all forward and backward driving forces:
$$\begin{eqnarray}
\vec{\mathscr P}_+  & = & \frac{\vec{L}_+}{\sum_j\left( L_{+j} + L_{-j} \right)} & = &   \frac{\mbox{diag}^{-1}(\vec{\bf r}_-)\cdot\vec{\bf r}_+}{\sum_j\left(\frac{r_{+j}}{r_{-j}} + \frac{r_{-j}}{r_{+j}}\right)}  \\
 \vec{\mathscr P}_- & = & \frac{\vec{L}_- }{\sum_j\left( L_{+j} + L_{-j} \right)} & = &  \frac{\mbox{diag}^{-1}(\vec{\bf r}_+)\cdot\vec{\bf r}_-}{\sum_j\left(\frac{r_{+j}}{r_{-j}} + \frac{r_{-j}}{r_{+j}}\right)} \\
\end{eqnarray}
$$

In this context, the thermodynamic driving force is simply the unnormalized likelihood, or $L_+$
