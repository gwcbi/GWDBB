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

  ```install_github('GWCBI/GWDBB')```

* load the library

  ```library(GWDBB)```

* load a dataset of interest e.g. micorbail species from Human Microbiome Project

  ```data("HMP1_II_Metadata")```

--------------------------------------------

## Datasets ##
* [HMP1-II: a dataset of microbial species abundance and related metadata](https://github.com/gwcbi/Data_Library/wiki/HMP1-II)
* [Breast milk and infant stool omics](https://github.com/gwcbi/Data_Library/wiki/Breast-milk-infant-stool-omics)

* [Treatment Options for Type II Diabetes in Adolescents and Youth (TODAY) study](https://github.com/gwcbi/GWDBB/wiki/The-Treatment-Options-for-Type-II-Diabetes-and-Youth-Study)
* [Systemic Lupus Erythematosus: Gene Expression and Expression of Human Endogenous Retroviruses](https://github.com/gwcbi/GWDBB/wiki/Systemic-Lupus-Erythematosus)
* [COVID-19 Community Research Partnership](https://github.com/gwcbi/GWDBB/wiki/The-COVID-19-Community-Research-Partnership)

--------------------------------------------

## Utilities ##
* [Instruction to contribute new dataset](https://github.com/gwcbi/GWDBB/wiki/Instruction-to-contribute-new-dataset)

--------------------------------------------

## Troubleshooting ##

Please submit any issue you face when using the data library using [Issues](https://github.com/gwcbi/GWDBB/issues)
 

