
<!-- README.md is generated from README.Rmd. Please edit that file -->

# foofactors

<!-- badges: start -->

<!-- badges: end -->

The goal of foofactors is to make it easier to use factors

## Installation

And the development version from [GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("ajmcoqui/foofactors")
```

## Example

This is a basic example which shows you how to solve a common problem:

``` r
library(foofactors)

x <- factor(c("a", "b"))
y <- factor(c("c", "d"))

fbind(x, y)
#> [1] a b c d
#> Levels: a b c d
```

You’ll still need to render `README.Rmd` regularly, to keep `README.md`
up-to-date.
