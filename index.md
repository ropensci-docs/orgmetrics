# orgmetrics

Metrics for your GitHub organization, collated from applying
accompanying [`repometrics`
package](https://docs.ropensci.org/repometrics/) across all organization
repositories, enhanced with additional organization-level data. Live
demonstration for the entire rOpenSci organization currently at
[ropensci-review-tools.github.io/orgmetrics-ropensci/](https://ropensci-review-tools.github.io/orgmetrics-ropensci/).

## How?

### Installation

First, install the package either via
[`r-universe`](https://r-universe.dev):

``` r

options (repos = c (
    ropenscireviewtools = "https://ropensci-review-tools.r-universe.dev",
    CRAN = "https://cloud.r-project.org"
))
install.packages ("orgmetrics")
```

or directly from GitHub with one of these two lines:

``` r

remotes::install_github ("ropensci-review-tools/orgmetrics")
pak::pkg_install ("ropensci-review-tools/orgmetrics")
```

The package may also be installed from locations other than GitHub, with
any of the following options:

``` r

remotes::install_git ("https://codeberg.org/ropensci-review-tools/orgmetrics")
remotes::install_git ("https://codefloe.com/ropensci-review-tools/orgmetrics")
```

## Code of Conduct

Please note that this package is released with a [Contributor Code of
Conduct](https://ropensci.org/code-of-conduct/). By contributing to this
project, you agree to abide by its terms.

## Contributors

All contributions to this project are gratefully acknowledged using the
[`allcontributors` package](https://github.com/ropensci/allcontributors)
following the [allcontributors](https://allcontributors.org)
specification. Contributions of any kind are welcome!

### Code

[TABLE]

### Issues

[TABLE]
