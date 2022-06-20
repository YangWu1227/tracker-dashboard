
<!-- README.md is generated from README.Rmd. Please edit that file -->

# TrackerDashboard

<!-- badges: start -->
<!-- badges: end -->

Credit belongs to [Hadley
Wickham](https://github.com/hadley/cran-downloads), the creator of the
original CRAN package download shiny application. This is my own version
of his project using the `bs4Dash` package and possibly including Python
data.

## Google BigQuery

The download logs from PyPI in the dashboard requires the use of
BigQuery, which is accomplished in R through the use of the `bigrquery`
package. BigQuery has a free tier, which offers 10 GB storage and up to
1 TB queries per month. For working with Google APIs, refer to the
`gargle` package, which `bigrquery` uses to deal with authentication,
and its
[vignettes](https://gargle.r-lib.org/articles/get-api-credentials.html).

## Installation

Install TrackerDashboard from [GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("YangWu1227/tracker-dashboard")
```
