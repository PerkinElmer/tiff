[![Project Status: Active ? The project has reached a stable, usable state and is being actively developed.](http://www.repostatus.org/badges/latest/active.svg)](http://www.repostatus.org/#active)
[![Build Status](https://travis-ci.org/PKI-Kent/tiff.svg?branch=master)](https://travis-ci.org/PKI-Kent/tiff)
 
---
 
[![packageversion](https://img.shields.io/badge/Package%20version-0.1.6-orange.svg?style=flat-square)](commits/master)
 
# tiff

This is a fork of the official [tiff package](https://github.com/s-u/tiff)
with many updates including

- limited support for tiled images
- readTIFFDirectory() function reads image tags without 
  reading the actual image
- Ability to read (or get info on) selected images

See the NEWS file for details.

## Installation

Installing `tiff` from source requires that you have a working development environment.
    * **Windows**: Install [Rtools](https://cran.r-project.org/bin/windows/Rtools/).
    * **Mac**: Install Xcode from the Mac App Store.
    * **Linux**: Install a compiler and various development libraries (details vary across different flavors of Linux).

Install `tiff` from github with:

``` r
# install.packages("devtools")
devtools::install_github("PerkinElmer/tiff")
```

