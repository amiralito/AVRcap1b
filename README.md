# Supporting scripts and material for "An effector from the potato late blight pathogen bridges ENTH-domain protein TOL9a to an activated helper NLR to suppress immunity"

[![DOI](https://img.shields.io/badge/bioRxiv-doi.org/10.1101/2025.07.06.663370-BE2634)](https://doi.org/10.1101/2025.07.06.663370)
[![DOI](https://zenodo.org/badge/995431397.svg)](https://doi.org/10.5281/zenodo.19554460)


Jogi Madhuprakash, AmirAli Toghani, Hsuan Pai, Madia Harvey, Adam R. Bentham, Benjamin A. Seager, Enoch Lok Him Yuen, Juan Carlos De la Concepcion, David M. Lawson, Clare E. M. Stevenson, Angel Vergara-Cruces, Lida Derevnina, Tolga O. Bozkurt, Mark J. Banfield, Sophien Kamoun*, Mauricio P. Contreras*


Resources:
Software                            | Source
------------------------------------| ------------------------------------
*FAMSA v2.2.2*                      | ([https://github.com/refresh-bio/FAMSA](https://github.com/refresh-bio/FAMSA))
*FastTree v2.1.10*                  | ([http://www.microbesonline.org/fasttree/](http://www.microbesonline.org/fasttree/))
*IQtree v2.3.0*                     | ([http://www.iqtree.org/](http://www.iqtree.org/))
*Dendroscope v3.8.8*                | (https://software-ab.cs.uni-tuebingen.de/download/dendroscope3/welcome.html)
*R v4.4.2*                          | ([https://cran.r-project.org/](https://cran.r-project.org/))



R packages:
```R
install.packages("tidyverse")
install.packages("readxl")
install.packages("ggseqlogo")
install.packages("entropy")
install.packages("svglite")
install.packages("reshape2")
install.packages("plotly")

if (!require("BiocManager", quietly = TRUE))
    install.packages("BiocManager")
BiocManager::install("Biostrings")
BiocManager::install("ggtree")
BiocManager::install("treeio")
```
