* \(\vec{\bf L}_+,\vec{\bf L}_-\) are decision variables representing the likelihood ratios of the forward and backward rates
* \(L_{+i} = r_{+i}/r_{-i}\) for each reaction \(j\)
* \(L_{-i} = r_{-i}/r_{+i}\) for each reaction \(j\).
* \(\displaystyle {\mathcal P}_{+i},{\mathcal P}_{-i}\) are the normalized likelihood ratios of the forward and backward rates
* \(\displaystyle \mathcal P_{+i} = \frac{r_{+i}}{r_{-i}}\left(\sum_j\frac{r_{+j}}{r_{-j}} + \frac{r_{-j}}{r_{+j}}\right)^{-1}\)
* \(\\mathcal P_{-i} = \frac{r_{-i}}{r_{+i}}\left(\sum_j\frac{r_{+j}}{r_{-j}} + \frac{r_{-j}}{r_{+j}}\right)^{-1}\)
* \(\log\vec{\bf c}\) is a decision variable representing the log concentrations of each metabolite 
*  \(S\) is the \(m\times n\) stoichiometric matrix of representing \(m\) metabolites and \(n\) reactions of the model  
*  \(\vec{\mu}^0\) is the vector of standard chemical potentials 
