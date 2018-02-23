[![Project Status: Active ? The project has reached a stable, usable state and is being actively developed.](http://www.repostatus.org/badges/latest/active.svg)](http://www.repostatus.org/#active)
[![Travis Build Status](https://travis-ci.org/PerkinElmer/tiff.svg?branch=master)](https://travis-ci.org/PerkinElmer/tiff)
[![Appveyor Build status](https://ci.appveyor.com/api/projects/status/eonxe9blgyydaws5?svg=true)](https://ci.appveyor.com/project/PKI-Kent/tiff)
[![packageversion](https://img.shields.io/badge/Package%20version-0.1.7-orange.svg?style=flat-square)](commits/master)
 
# tiff

This is a fork of the official [tiff package](https://github.com/s-u/tiff)
with many updates including

- Limited support for tiled images
- New `readTIFFDirectory` function reads image tags without 
  reading the actual image
- Ability to read (or get info on) selected images within a file

See the NEWS file for details.

## Installation

Installing `tiff` from source requires that you have a working 
development environment.

- **Windows**: Install [Rtools](https://cran.r-project.org/bin/windows/Rtools/).
- **Mac**: Install Xcode from the Mac App Store.
- **Linux**: Install a compiler and various development libraries (details vary across different flavors of Linux).

Install `tiff` from github with:

``` r
# install.packages("devtools")
devtools::install_github("PerkinElmer/tiff")
```

Binary builds for 64-bit Windows are available from
[Appveyor](https://ci.appveyor.com/project/PKI-Kent/tiff/build/artifacts).

Download the `.zip` file. Then run this command and choose the downloaded file:

```r
install.packages(file.choose(), repos=NULL)
```
