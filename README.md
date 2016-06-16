
<!-- README.md is generated from README.Rmd. Please edit that file -->

[![CRAN_Status_Badge](http://www.r-pkg.org/badges/version/digitize)](http://cran.r-project.org/package=digitize)
![](http://cranlogs.r-pkg.org/badges/digitize?color=yellow)
![](http://cranlogs.r-pkg.org/badges/grand-total/digitize?color=yellowgreen)
[![Travis-CI Build Status](https://travis-ci.org/ashander/digitize.svg?branch=master)](https://travis-ci.org/ashander/digitize)


digitize : a plot digitizer in R
===============

Get the data from a graph by providing calibration points

## Install

```
if(!require(devtools)) install.packages('devtools')
devtools::install_github("tpoisot/digitize")
```

## How to use it

Read a [tutorial from Luke Miller](http://lukemiller.org/index.php/2011/06/digitizing-data-from-old-plots-using-digitize/).

## Citation


```r
citation('digitize')
#> 
#>   Poisot, T. The digitize package: extracting numerical data from
#>   scatterplots. The R Journal 3.1 (2011): 25-26.
#> 
#> A BibTeX entry for LaTeX users is
#> 
#>   @Article{,
#>     title = {The digitize package: extracting numerical data from scatterplots},
#>     author = {T. Poisot},
#>     journal = {The R Journal},
#>     year = {2011},
#>     volume = {3},
#>     number = {1},
#>     pages = {25-26},
#>     url = {http://rjournal.github.io/archive/2011-1/RJournal_2011-1.pdf#page=25},
#>   }
```

## Image Types


Works with three bitmap image formats (jpeg, png, bmp), automatically detecting
the image type using package `readbitmap`.
