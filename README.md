
<!-- README.md is generated from README.Rmd. Please edit that file -->

# roam

<!-- badges: start -->

[![Lifecycle:
experimental](https://img.shields.io/badge/lifecycle-experimental-orange.svg)](https://www.tidyverse.org/lifecycle/#experimental)
[![CRAN
status](https://www.r-pkg.org/badges/version/roam)](https://CRAN.R-project.org/package=roam)
<!-- badges: end -->

The roam package allows you to include larger datasets (and other
objects) in packages without increasing installation size (and exceeding
CRAN size limits). How? With *Remote Object ActiveBinding Magic* (roam).

Using active bindings, the familiar interface for package datasets is
retained. When an object/dataset is accessed for the first time, the
user is prompted to download the object into an app directory for
caching. Any subsequent time it is accessed, it returns the object as
normal.

## Installation

<!-- You can install the released version of roam from [CRAN](https://CRAN.R-project.org) with: -->

<!-- ``` r -->

<!-- install.packages("roam") -->

<!-- ``` -->

The **development** version can be installed from GitHub using:

``` r
# install.packages("remotes")
remotes::install_github("mitchelloharawild/roam")
```

## Example

None yet.
