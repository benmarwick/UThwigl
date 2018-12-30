
<!-- README.md is generated from README.Rmd. Please edit that file -->

# iDADwigl

[![Travis build
status](https://travis-ci.org/benmarwick/iDADwigl.svg?branch=master)](https://travis-ci.org/benmarwick/iDADwigl)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/benmarwick/iDADwigl/master?urlpath=rstudio)

The goal of iDADwigl is to compute open-system uranium-thorium ages of
geological and archaeological samples. It is based on the
diffusion-adsorption-decay (DAD) model of Sambridge et al. (2012), which
allows for advective and diffusive transport of uranium and thorium
isotopes, while including synchronous radioactive decay.

The main function, `iDADwigl()`, will take the
(<sup>230</sup>Th/<sup>238</sup>U) and (<sup>234</sup>U/<sup>238</sup>U)
activity ratios collected along a transect perpendicular to the surface
of the tooth or bone and return an age in thousands of years ago.

## Web application

The package includes a web application that runs in your browser where
you can upload your CSV file, set the model parameters, run the model,
and view the results. Choose this option is you are not familiar with R.
Here’s a screenshot of the web app:

![](iDADwigl-shiny-app.gif)

## Run code without downloading anything

You can run the package function in your browser by [starting a binder
instance](https://mybinder.org/v2/gh/benmarwick/iDADwigl/master?urlpath=rstudio).
This will open RStudio in your browser, together with the contents of
this GitHub repository.

## Installing the iDADwigl package on your computer

To install the development version of iDADwigl from GitHub on your
computer, run:

``` r
source("https://install-github.me/tonydoss/iDADwigl")
```

Please see the [vignette](articles/idadwigl.pdf) for an example of how
to use this package.
