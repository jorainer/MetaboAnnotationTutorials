# Use cases and examples for annotation of non-target metabolomics data

This repository provides use cases and examples for the annotation of non-target
metabolomics or small compound MS data using the `MetaboAnnotation` and
`MetaboCoreUtils` R packges.

## Installation

The R packages used in this examples can be installed with the R code below:

```
install.packages("BiocManager")
BiocManager::install(c("xcms", "pander"))
BiocManager::install(c("Spectra", "MsCoreUtils", "MetaboCoreUtils"))
BiocManager::install("RforMassSpectrometry/CompoundDb")
BiocManager::install("RforMassSpectrometry/MetaboAnnotation")
```

The source code for this document along with the test data can be downloaded
from the github repository https://github.com/jorainer/annotation_ecosystem with
the command (or alternatively downloading the zip archive directly from the
github page; note that [git-lfs](https://git-lfs.github.com/) needs to be
installed for the command below to work).

```
git clone https://github.com/jorainer/annotation_ecosystem
```

## Additional documentation resources and tutorials

- Tutorial with additional examples and explanations for $MS^2$-based
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
