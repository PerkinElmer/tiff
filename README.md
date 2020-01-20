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

### Prerequisites

Installing the `tiff` package requires that you have a working 
development environment and, for macOS and Linux, an installed copy of `libtiff`.

**Windows**: Install [Rtools](https://cran.r-project.org/bin/windows/Rtools/).

**macOS**: 

- Install Xcode from the 
  [Mac App Store](https://apps.apple.com/us/app/xcode/id497799835).
- Install [Homebrew](https://brew.sh/) using
  [these instructions](https://brew.sh/).
- Install `libtiff` with the Terminal command `brew install libtiff`.


**Linux**: 

- Install a compiler and the development version of `libtiff`
using the package manager for your Linux version.
  - Redhat Linux: `sudo yum install libtiff-devel`
  - Ubuntu 16.004 LTS: `sudo apt-get install libtiff5-dev`

### Install from GitHub

Finally, install the `tiff` package from GitHub with:

``` r
# install.packages("remotes")
remotes::install_github("akoyabio/tiff")
```
