Data Description and EDA
================

HELLO
-----

``` r
library(tidyverse)
```

    ## -- Attaching packages ----------------------------------------------------------- tidyverse 1.2.1 --

    ## v ggplot2 3.1.0     v purrr   0.3.0
    ## v tibble  2.0.1     v dplyr   0.7.8
    ## v tidyr   0.8.2     v stringr 1.3.1
    ## v readr   1.3.1     v forcats 0.3.0

    ## -- Conflicts -------------------------------------------------------------- tidyverse_conflicts() --
    ## x dplyr::filter() masks stats::filter()
    ## x dplyr::lag()    masks stats::lag()

``` r
suicide <- read_csv("master.csv", col_names = TRUE, na = "")
```

    ## Parsed with column specification:
    ## cols(
    ##   country = col_character(),
    ##   year = col_double(),
    ##   sex = col_character(),
    ##   age = col_character(),
    ##   suicides_no = col_double(),
    ##   population = col_double(),
    ##   `suicides/100k pop` = col_double(),
    ##   `country-year` = col_character(),
    ##   `HDI for year` = col_double(),
    ##   `gdp_for_year ($)` = col_number(),
    ##   `gdp_per_capita ($)` = col_double(),
    ##   generation = col_character()
    ## )

Abstract
--------

Data Description
----------------

Research Question
-----------------

What is the effect of different country factors, such as population and gdp, and age of individuals on suicide rate within the past three decades.

Data Import & Cleaning
----------------------

Data import of the main 'suicide' dataset was succesful, with only the 'HDI/year' having a number of missing values for each country and year.

Variation of Single Variables
-----------------------------

Covariation between Multiple Variables
--------------------------------------

Discussion
----------
