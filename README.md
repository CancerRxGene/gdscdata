# gdscdata
R package containing the GDSC version 17 data set

The **gdscdata** package contains drug response data from the Genomics of Drug Sensitivity in Cancer project (GDSC) in a format 
that can be processed and analysed using the [gdscIC50 package](https://github.com/CancerRxGene/gdscIC50). This data is also 
available to browse and for download from the website [www.cancerrxgene.org](http://www.cancerrxgene.org), although some 
changes have been made since the initial release (more details in the package vignette).

You can install the package in R using the devtools library. 
 ```
> install.packages("devtools")
```
If you haven't done so already, install the gdscIC50 package. It is required to build the gdscdata vignette.
```
> devtools::install_github("cancerrxgene/gdscIC50", build_vignettes=TRUE)
```
And then install gdscdata.
```
> devtools::install_github("cancerrxgene/gdscdata", build_vignettes=TRUE)
```
Once installed, the vignette gives a guide to the GDSC v17 dataset and the accompanying plate maps.
```
> library(gdscIC50)
> vignette("gdsc_v17")
```
