# Use Cases and Examples for Annotation of Untargeted Metabolomics Data

[![License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc/4.0/)

![MetaboAnnotation](man/figures/MetaboAnnotation.png)
![MetaboCoreUtils](man/figures/MetaboCoreUtils.png)
![Spectra](man/figures/Spectra.png)
![MsCoreUtils](man/figures/MsCoreUtils.png)
![MsBackendMassbank](man/figures/MsBackendMassbank.png)
![MsBackendMgf](man/figures/MsBackendMgf.png)
![CompoundDb](man/figures/CompoundDb.png)

This repository provides use cases and examples for the annotation of non-target
metabolomics or small compound MS data using the `MetaboAnnotation` and
`MetaboCoreUtils` R packages. Refer to the original article [A Modular and
Expandable Ecosystem for Metabolomics Data Annotation in
R](https://doi.org/10.3390/metabo12020173) to **cite** this package/repository
or any functionality described here.

## Installation

Requirements: R version >= 4.2 (and hence Bioconductor 3.15) is needed.

The R packages as well as the example files used in this document can be
installed with the R code below:

```r
install.packages("BiocManager")
BiocManager::install("jorainer/MetaboAnnotationTutorials",
    dependencies = TRUE, ask = FALSE, update = TRUE)
```


Alternatively, the packages can be installed individually with:

```r
install.packages("BiocManager")
BiocManager::install("ProtGenerics")

## Packages with low-level core functionality
BiocManager::install("MsCoreUtils")
BiocManager::install("MetaboCoreUtils")

## Packages with high-level user functionality
BiocManager::install("Spectra")
BiocManager::install("MetaboAnnotation")
BiocManager::install("CompoundDb")

## Support for MGF files
BiocManager::install("MsBackendMgf")

## Support for MassBank
BiocManager::install("MsBackendMassbank")

## Support for MSP files
BiocManager::install("MsBackendMsp")
```

The source code for this document along with the test data can be downloaded
from the github repository https://github.com/jorainer/MetaboAnnotationTutorials
with the command (or alternatively downloading the zip archive directly from the
github page).

```
git clone https://github.com/jorainer/MetaboAnnotationTutorials
```

## Contribution

For contributions, see the [RforMassSpectrometry contributions
guideline](https://rformassspectrometry.github.io/RforMassSpectrometry/articles/RforMassSpectrometry.html#contributions).


## Code of Conduct

See the [RforMassSpectrometry Code of
Conduct](https://rformassspectrometry.github.io/RforMassSpectrometry/articles/RforMassSpectrometry.html#code-of-conduct).


## Additional documentation resources and tutorials

- Tutorial with additional examples and explanations for MS2-based
  annotations: https://jorainer.github.io/SpectraTutorials/
- Repository of the `MsCoreUtils` package:
  https://rformassspectrometry.github.io/MsCoreUtils/
- Repository of the `MetaboCoreUtils` package:
  https://rformassspectrometry.github.io/MetaboCoreUtils/
- Repository of the `Spectra` package:
  https://rformassspectrometry.github.io/Spectra/
- Repository of the `MetaboAnnotation` package:
  https://rformassspectrometry.github.io/MetaboAnnotation/
- Repository of the `CompoundDb` package:
  https://rformassspectrometry.github.io/CompoundDb/
