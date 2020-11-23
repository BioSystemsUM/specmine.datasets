specmine.datasets
================
```{r echo=FALSE, results="hide", message=FALSE}
library("badger")
```

```{r, echo = FALSE, results='asis'}
cat(
	badge_cran_release("badger", "green"),
)
```

Datasets for the R package *specmine*.

## Installation

You can install the released version of *specmine.datasets* from
[CRAN](https://CRAN.R-project.org) with:

``` r
install.packages("specmine.datasets")
```

And the development version from [GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("BioSystemsUM/specmine.datasets")
```
## Example

This is a basic example which shows you how to load *specmine.datasets* and an example dataset to your environment:

``` r
library("specmine.datasets")

data("cachexia")
```

