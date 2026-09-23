# Molecular Methods in Ecology and Evolution - 2026 - University of Lausanne
This is the repository for the master course "Molecular Methods in Ecology and Evolution - 2026 UNIL"

Here you will find all the information and data you will need for the computer analyses of the course.

### Repository's content

- MolGen2026_Manual - Manual with the exercises you should follow.

- #### [1.Frogs_Sanger](1.Frogs_Sanger) - This directory contains the data for the first project.

- #### [2.Frogs_RADseq](2.Frogs_RADseq) - This directory contains the data for the second project.

- #### [3.Cichlids](3.Cichlids) - This directory contains the data for the third project.

- #### [4.Eels](4.Eels) - This directory contains the data for the forth project.

### Important information

To be able to install and use all packages required you may need to use R version 3.6.x instead of R version 4.x.x. Consider swithcing versions if you have trouble installing the packages. If you already have an R version installed on your computer and want to change it, you can find instructions on how to do it [here](https://support.rstudio.com/hc/en-us/articles/200486138-Changing-R-versions-for-the-RStudio-Desktop-IDE).

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

`if (!requireNamespace("BiocManager", quietly = TRUE))`

`install.packages("BiocManager")`

`BiocManager::install("LEA", dependencies = TRUE)`

`install.packages("outliers", dependencies = TRUE)`

`install.packages("EnvStats")`
