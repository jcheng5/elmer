
<!-- README.md is generated from README.Rmd. Please edit that file -->

# elmer

<!-- badges: start -->

[![R-CMD-check](https://github.com/hadley/elmer/actions/workflows/R-CMD-check.yaml/badge.svg)](https://github.com/hadley/elmer/actions/workflows/R-CMD-check.yaml)
<!-- badges: end -->

The goal of elmer is to provide a user friendly wrapper over the most
common APIs for calling llm’s. Major design goals include support for
streaming and making it easy to register and call R functions.

## Installation

You can install the development version of elmer from
[GitHub](https://github.com/) with:

``` r
# install.packages("pak")
pak::pak("hadley/elmer")
```

## Usage

To use elmer, you need an OpenAI API key. You can get one from [your
developer console](https://platform.openai.com/account/api-keys). Then
you should save that value as the `OPENAI_API_KEY` environment variable
in your `~/.Renviron` (an easy way to open that file is to call
`usethis::use_renviron()`).
