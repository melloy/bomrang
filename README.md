
<!-- README.md is generated from README.Rmd. Please edit that file -->
*BOMRang*: Fetch Australian Government Bureau of Meteorology Data
=================================================================

[![Travis-CI Build Status](https://travis-ci.org/ToowoombaTrio/BOMRang.svg?branch=master)](https://travis-ci.org/ToowoombaTrio/BOMRang) [![AppVeyor Build Status](https://ci.appveyor.com/api/projects/status/github/ToowoombaTrio/BOMRang?branch=master&svg=true)](https://ci.appveyor.com/project/ToowoombaTrio/BOMRang) [![Last-changedate](https://img.shields.io/badge/last%20change-2017--05--03-brightgreen.svg)](https://github.com/toowoombatrio/BOMRang/commits/master) [![minimal R version](https://img.shields.io/badge/R%3E%3D-3.4.0-brightgreen.svg)](https://cran.r-project.org/)

Fetches Fetch Australian Government Bureau of Meteorology Weather forecasts and returns a tidy data frame in a *Tibble* of the current and next six days weather.

*Limited to Queensland and temperature values only at the moment*

Credit for the name, *BOMRang*, goes to the attendees of the 2016 \#AUUnconf in Brisbane, I can't recall if it was @MilesMcBain who suggested it or someone else? If you can take credit, submit a pull request taking credit please.

Quick start
-----------

``` r
if (!require("devtools")) {
  install.packages("devtools", repos = "http://cran.rstudio.com/") 
  library("devtools")
}

devtools::install_github("toowoombatrio/BOMRang")
library("BOMRang")
```

Meta
----

Please note that this project is released with a [Contributor Code of Conduct](CONDUCT.md). By participating in this project you agree to abide by its terms.