# Molecular Methods in Ecology and Evolution - 2026 - University of Lausanne
This is the repository for the master course "Molecular Methods in Ecology and Evolution - 2026 UNIL"

Here you will find all the information and data you will need for the computer analyses of the course.

### Repository's content

- MolGen2026_Manual - Manual with the exercises you should follow.

- #### [1.Frogs_Sanger](1.Frogs_Sanger) - This directory contains the data for the first project.

- #### [2.Frogs_RADseq](2.Frogs_RADseq) - This directory contains the data for the second project.

- #### [3.Cichlids](3.Cichlids) - This directory contains the data for the third project.

- #### [4.Eels](4.Eels) - This directory contains the data for the forth project.


### Packages installation

To install all packages required, please run the following commands:

In case you don't have administrator's access to your computer, you can specify where the packages should be installed with the `lib` option in `install.packages()`

`install.packages("ape", dependencies = TRUE)`

`install.packages("phangorn", dependencies = TRUE)`

`install.packages("seqinr", dependencies = TRUE)`

`install.packages("adegenet", dependencies = TRUE)`

`install.packages("pegas", dependencies = TRUE)`

`install.packages("hierfstat", dependencies = TRUE)`

`install.packages("raster", dependencies = TRUE)`

`install.packages("outliers", dependencies = TRUE)`

`install.packages("EnvStats")`

```
if (!requireNamespace("BiocManager", quietly = TRUE))

install.packages("BiocManager")

BiocManager::install("LEA", dependencies = TRUE)
```

### Trouble shooting

Sometimes package installation fails due to the R version you're trying to install packages on. if you have trouble installing the packages consider switching R version 4.x.x. to R version 3.6.x instead.  If you already have an R version installed on your computer and want to change it, you can find instructions on how to do it [here](https://support.rstudio.com/hc/en-us/articles/200486138-Changing-R-versions-for-the-RStudio-Desktop-IDE).

### Search for the following functions.
Once all packages have been install load them using the function `library()` as `library(ape)`.
Let's search for a few functions provided by the packages you just installed. Make sure you can read the help of the following functions, this way we are sure that the packages were correctly installed and that you will be able to use the functions in the following days.
```
library(ape)
?read.dna
```
Load all the packages you previously installed and call the help of the following functions, in the help text displayed you should be able to identify the package to which the function belongs:
```
?dist.ml
?root
?basic.stats
?pairwise.neifst
?genind2genpop
?mantel.randtest
?snmf
```
