
# flowiQC_shinyAPP

[FlowiQC](https://github.com/SIgNBioinfo/flowiQC_shinyAPP) is a Shiny 
application that allows to perform 
an interactive quality control of flow cytometry data. 

## Tutorial

FlowiQC can be hosted by a server, or it is possible to use a local machine as both the "back and front ends".
In the last case a R session on your machine will be the back end and your web browser will be the front end.

### Quick install/launch instructions

A version of FlowiQC has been deployed on the cloud of the 
platform shinyapps.io and it is reachable from the link 
[https://haoeric.shinyapps.io/flowQC_shiny/](https://haoeric.shinyapps.io/flowQC_shiny/).

For a more frequent usage we suggest to download a [copy of 
the latest version of the package](https://github.com/SIgNBioinfo/flowiQC_shinyAPP/archive/master.zip)
 and install it on a server or local machine.
Make sure you have the last version of R and that the dependencies have been installed.
Launch the following code to install or update the dependencies:
```r
install.packages(c("shiny", "RColorBrewer", "lattice", "reshape2", "tabplot", "googleVis"))
source("http://bioconductor.org/biocLite.R")
biocLite("flowCore")
```
 
 
 
 
 ## Citation
FlowiQC is freely distributed for both academic and non-academic porpuses. 
If the application gives any benefits, we only require to cite it.


 
 