# rysgran
This is the new rysgran package, Version: 2.2.0.
Grain size analysis, textural classifications and distribution of unconsolidated sediments

This package is a port to R of the SysGran program, written in Delphi by Camargo (2006). It contains functions for the analysis of grain size samples (in logarithmic (phi) and geometric (micrometers) scale) based on various methods, like Folk & Ward (1957) and Methods of Moments (Tanner, 1995), among others; textural classifications and distribution of unconsolidated sediments are shown in histograms, bivariated plots and ternary diagrams of Shepard (1954) and Pejrup (1988). English and Portuguese languages are supported in outputs.

rysgran is not yet on CRAN.

To install, just do:

install.packages("remotes")
library("remotes")
remotes::install_github('mauricio-camargo/rysgran')
