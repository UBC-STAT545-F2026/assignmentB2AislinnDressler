
<!-- README.md is generated from README.Rmd. Please edit that file -->

# assignmentB2AislinnDressler

<!-- badges: start -->

<!-- badges: end -->

The goal of assignmentB2AislinnDressler is to provide a package for a
function to count missing values (count_all_missing_by_group).The
function counts the amount of missing data in each column of a dataset
and outputs a tibble with the amount of missing data in each column
group.

## Installation

You can install the development version of assignmentB2AislinnDressler
from [GitHub](https://github.com/) with:

``` r
# install.packages("pak")
pak::pak("UBC-STAT545-F2026/assignmentB2AislinnDressler")
```

## Example

This is a basic example which shows you how to solve a common problem:

``` r
library(assignmentB2AislinnDressler)
count_all_missing_by_group(airquality, Month)
#> # A tibble: 5 × 6
#>   Month Ozone Solar.R  Wind  Temp   Day
#>   <int> <int>   <int> <int> <int> <int>
#> 1     5     5       4     0     0     0
#> 2     6    21       0     0     0     0
#> 3     7     5       0     0     0     0
#> 4     8     5       3     0     0     0
#> 5     9     1       0     0     0     0
```
