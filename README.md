# katdetectr

![license](https://img.shields.io/badge/license-GPL--3-blue.svg) [![GitHub issues](https://img.shields.io/github/issues/ErasmusMC-CCBC/katdetectr.svg)]() ![rversion](https://img.shields.io/badge/R%20version-%3E4.1.0-lightgrey.svg)

# Introduction

`katdetectr` is an *R* package for the detection, characterization and visualization of localized hypermutated regions, often referred to as *kataegis*.

Please see the [Application Note](https://www.google.com) (under submission) for additional background, details and performance evaluations of `katdetectr`.

The general workflow of `katdetectr` can be summarized as follows:

1. Import of genomic variants; VCF, MAF or VRanges objects.
2. Detection of kataegis foci.
3. Visualization of segmentation and kataegis foci.

Please see the vignette for an overview of the workflow in a step-by-step manner on publicly-available datasets which are included within this package.


## Citation

Not yet published.


## Installation

The latest development version can be installed directly from GitHub:

```R
# Require/install devtools package if not already installed.
if (!require("devtools")) install.packages("devtools", repos = "http://cran.r-project.org")

# Install katdetectr from GitHub.
devtools::install_github(repo = "ErasmusMC-CCBC/katdetectr")

# Download all required packages
library(katdetectr)
```

Or from BioConductor:
```R
if (!requireNamespace("BiocManager", quietly = TRUE))
    install.packages("BiocManager")

BiocManager::install("katdetectr")

```

# Usage

Please view the vignettes for instructions and tutorials on how to use this package.

```R
browseVignettes("katdetectr")
```
