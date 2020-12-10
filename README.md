# Pre-processing Tools for High-throughput Animal Tracking Data

<!-- badges: start -->
  [![Project Status: Active – The project has reached a stable, usable state and is being actively developed.](https://www.repostatus.org/badges/latest/active.svg)](https://www.repostatus.org/#active)
  [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.4033155.svg)](https://doi.org/10.5281/zenodo.4033155) 
  [![R build status](https://github.com/pratikunterwegs/atlastools/workflows/R-CMD-check/badge.svg)](https://github.com/pratikunterwegs/atlastools/actions)
  [![codecov.io](https://codecov.io/github/pratikunterwegs/atlastools/coverage.svg?branch=master)](https://codecov.io/github/pratikunterwegs/atlastools/branch/master)
<!-- badges: end -->

`atlastools` is an `R` package to pre-process high frequency animal tracking data. 
It is written and maintained by [Pratik Gupte](https://www.rug.nl/staff/p.r.gupte), at the [University of Groningen's Theoretical Biology Group](https://www.rug.nl/research/gelifes/tres/). While aimed at data from ATLAS systems, it works with any `X, Y, TIME` data.

`atlastools` use with animal tracking data is extensively documented here: https://github.com/pratikunterwegs/atlas-best-practices

## Installation

```r
# This package can be installed using devtools
install.packages("devtools")

devtools::install_github("pratikunterwegs/atlastools")
```
