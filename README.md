# GWDBB, a reference data library for clinical trials and omics data

## Data Library Description ##

A data repository for multiple studies' data developed by the [Department of Biostatistics and Bioinformatics (DBB)](https://publichealth.gwu.edu/departments/biostatistics-and-bioinformatics) at [George Washington University](https://www.gwu.edu/). 

* *Citation*: **A reference data library for clinical trials and omics data**, Department of Biostatistics and Bioinformatics, Milken Institute School of Public Health, George Washington University, 2020 

## Data orgnization ##
This repository includes a library of datasets from study's performed by faculty members of DBB. 
Each dataset has:
* a brief description
* link and citation to related publications, and
* a wiki page including instructions (R and Python) to load and performing data analyses from the library. 

The datasets are for different human disease, environmental studies, and include omics and clinical trail datatypes. 

--------------------------------------------

## Install the library ##

The data library is implemented as an R package.

Instruction to install it using RStudio.

If you do not have RStudio installed on your computer, then please find information to install it from [here](https://rstudio.com/products/rstudio/download/)

I RStudio console you can run the following R commands to install requirements and the library:

* install devtools: a tool enables installing packages from Github

  ```library(devtools)```

* install GWDBB from the GitHub repository 

  ```install_github(‘GWCBI/GWDBB')```

* load the library

  ```library(GWDBB)```

* load a dataset of interest 

  ```load('GWDBB')```

--------------------------------------------

## Datasets ##

* [iHMP Meatbolomics Data](https://github.com/gwcbi/Data_Library/wiki/iHMP)
* [The Diabetes Control and Complications Trial (DCCT)](https://github.com/gwcbi/Data_Library/wiki/The-Diabetes-Control-and-Complications-Trial-(DCCT))

--------------------------------------------

## Troubleshooting ##
 

