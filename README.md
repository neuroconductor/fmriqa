
<!-- README.md is generated from README.Rmd. Please edit that file -->
fmriqa
======

Overview
--------

The fmriqa package provides an implemenation of the fMRI QA analysis protocol detailed in:

Friedman L and Glover GH. Report on a multicenter fMRI quality assurance protocol. J Magn Reson Imaging. 2006 Jun;23(6):827-39.

Installation
------------

You can install the stable version of fmriqa from CRAN:

``` r
install.packages("fmriqa", dependencies = TRUE)
```

Or the the development version from GitHub (requires `devtools` package):

``` r
install.packages("devtools")
devtools::install_github("martin3141/fmriqa")
```

Usage
-----

``` r
# load the package
library(fmriqa)

# get help on the options for run_qa
?run_qa

# run the analysis - a file chooser will appear when a data_file argument is not given
run_qa()
```

Here is a example png output file showing an RF spiking artifact:

![](SPIKE_EG_qa_plot.png)
