# Supporting scripts and material for "An effector from the potato late blight pathogen bridges ENTH-domain protein TOL9a to an activated helper NLR to suppress immunity"




Resources:
Software                            | Source
------------------------------------| ------------------------------------
*MAFFT v7.526*                      | ([https://mafft.cbrc.jp/alignment/software/macosx.html](https://mafft.cbrc.jp/alignment/software/macosx.html))
*FastTree v2.1.11*                  | ([http://www.microbesonline.org/fasttree/](http://www.microbesonline.org/fasttree/))
*Dendroscope v3.8.8*                | (https://software-ab.cs.uni-tuebingen.de/download/dendroscope3/welcome.html)
*R v4.4.2*                          | ([https://cran.r-project.org/](https://cran.r-project.org/))
*NLRtracker*                        | ([https://github.com/slt666666/NLRtracker](https://github.com/slt666666/NLRtracker))



R packages:
```R
install.packages("tidyverse")
install.packages("ggseqlogo")
install.packages("entropy")
install.packages("svglite")
install.packages("reshape2")
install.packages("jsonlite")
install.packages("plotly")


if (!require("BiocManager", quietly = TRUE))
    install.packages("BiocManager")
BiocManager::install("Biostrings")
BiocManager::install("ggtree")

```

