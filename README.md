<!--  -*- coding: utf-8 -*- -->
<!-- README.md is generated from README.Rmd. Do not edit this file directly -->

simplecolors <img src="man/figures/logo.png" align="right" alt="" width="120" />
================================================================================

<!-- [![Codecov test coverage](https://codecov.io/gh/rjake/simplecolors/branch/master/graph/badge.svg)](https://codecov.io/gh/rjake/simplecolors?branch=master)-->
<!-- badges: start -->

[![CRAN\_Status\_Badge](https://www.r-pkg.org/badges/version/simplecolors)](https://cran.r-project.org/package=simplecolors)
[![CRAN
Downloads](https://cranlogs.r-pkg.org/badges/grand-total/simplecolors)](https://cran.r-project.org/package=simplecolors)
<!-- badges: end -->

simplecolors is designed to generate hex codes using uniformly named
colors.

Install development version from GitHub
---------------------------------------

``` r
devtools::install_github("rjake/simplecolors")
```

Usage
-----

The idea is to have a simpler way of accessing color values that is
intuitive and easy to remember. Colors can be called using `sc()` or by
using the various palette tools `sc_across()`, `sc_blue()`, etc. To see
all available colors use `show_colors()`

The colors follow a pattern of \[saturation\] \[color name\]
\[lightness\]

More details can be found in created can be found in

`vignette("Intro", package = "simplecolors")`.

![](man/figures/color_names.png)
