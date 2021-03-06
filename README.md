---
output: github_document
---

<!-- README.md is generated from README.Rmd. Please edit that file -->



# TMwR

<!-- badges: start -->
<!-- badges: end -->

This repository has the sources for _Tidy Modeling with R_ book. Its purpose of the book is to demonstrate how the tidyverse can be used to produce high quality models. The [_tidymodels packages_](https://github.com/tidymodels) are the focus of the book. 

# Reproducing the book or results

First, you'll need to install the required packages. To do this, first install the `remotes` package:

``` r
install.packages("remotes")
```

then use this to install what you need to create the book: 

``` r
remotes::install_github("topepo/TMwR")
```

Although we rigorously try to use the current CRAN versions of all packages, the code above may install some development versions. 

The content is created using the `bookdown` package. To compile the book, use

```r
bookdown::render_book("index.Rmd", "bookdown::gitbook")
```

This will create the HTML files in a directory called `_book`. **Note** that, before the first compile, you'll need to make `_book` and copy the `premade` directory in this repository to `_book` so that existing diagrams will be found. 


# Problems, questions, or issues

## Code of Conduct
  
Please note that the TMwR project is released with a [Contributor Code of Conduct](https://contributor-covenant.org/version/2/0/CODE_OF_CONDUCT.html). By contributing to this project, you agree to abide by its terms.

