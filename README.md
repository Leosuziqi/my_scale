
<!-- README.md is generated from README.Rmd. Please edit that file -->

myscale
=======

<!-- badges: start -->
<!-- badges: end -->

The goal of myscale is to scale the input by log or exp algorithm.

Installation
------------

You can install the released version of myscale from
[CRAN](https://CRAN.R-project.org) with:

    devtools::install_github("Leosuziqi/myscale")

Example
-------

This is a basic example which shows you how to solve a common problem:

    library(myscale)
    myscale(10,"log")
    #> [1] 2.302585


## Brief Explanation

I made my R packages "myscale.R" with "devtools" and "usethis". The main steps are shown below:

(1) Load library and create R package to desired location
```{r}
library(devtools)
create_package("C:/STAT545b/assignment/scale")
```

(2) Create R script and wrote down my function
```{r}
use_r("myscale")
use_git()
use_mit_license("Ziqi")
```

(3) Use tools from "devtools" and "usethis" packages to document my package
```{r}
library(roxygen2)
#Code -> Insert Roxygen Skeleton
use_package("purrr")
use_vignette("myscale")
document()
```

(4) Build test file to test and check my function
```{r}
use_testthat()
# Create several conditions to check my function
test()
```
