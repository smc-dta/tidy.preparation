
# `tidy.preparation`

<!-- badges: start -->

[![Package
Website](https://img.shields.io/badge/Package%20Website-Click--Here-9cf.svg)](https://tidylab.github.io/tidy.preparation/)
[![Travis build
status](https://travis-ci.org/tidylab/tidy.preparation.svg?branch=master)](https://travis-ci.org/tidylab/tidy.preparation)
[![Code coverage
status](https://codecov.io/gh/tidylab/tidy.preparation/branch/master/graph/badge.svg)](https://codecov.io/github/tidylab/tidy.preparation/?branch=master)
<!-- badges: end -->

## Ingest, Prepare, Store and Craft Features through a Data Pipeline

<img src="https://i.imgur.com/RLEQkhe.png" width="75%" style="display: block; margin: auto;" />

## Overview

`tidy.preparation` provides R6 classes for implementing a unidirectional
data pipeline that starts with any data source whether it’s on a remote
server or local disk. At the output of the instantiated pipeline are
amendable data, ready for consumption by multiple predictive analytics
applications such as analytical models and reports.

See the [package website](https://tidylab.github.io/tidy.preparation/)
for more information.

## Installation

You can install `tidy.preparation` by using:

    install.packages("devtools")
    devtools::install_github("tidylab/tidy.preparation")
