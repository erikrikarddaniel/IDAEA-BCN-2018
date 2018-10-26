# IDAEA-BCN-2018

Data for the workshop at IDAEA in Barcelona November 2011.

## Data for practicals

### Main practical: R/Tidyverse

The R metapackage Tidyverse is a collection of packages for "tidy" data science.

My examples during the workshop will all use three tab separated files prepared from the 
["Atacama soils" QIIME2 tutorial](https://docs.qiime2.org/2018.8/tutorials/atacama-soils/).

The files can be found as symlinks in the `analyses` directory of the repository:

```
atacama-soils.asvtable.tsv  
atacama-soils.taxonomy.tsv
atacama-soils.samples.headers.tsv
```

If you want to practice how to read BIOM data, there's an alternative to the
`atacama-soils.asvtable.tsv`: `atacama-soils.biom`.

### QIIME2 practical

If you want to try out QIIME2 using DADA2 and the sklearn algorithm for
taxonomy assignment, start here:

https://docs.qiime2.org/2018.8/tutorials/atacama-soils/

and then continue here, to do the taxonomy assignment:

https://docs.qiime2.org/2018.8/tutorials/moving-pictures/

(Scroll down to "Taxonomic analysis".)

### MetaWRAP practical
