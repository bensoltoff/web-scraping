## Overview

Importing data is one of the first steps in a data science workflow. Unfortunately not all data sources come in ready-to-use tabular formats. Frequently individuals need to collect and organize data stored within HTML web pages. In this demonstration we will review the basic structure of HTML source code and practice reproducibly scraping content using the [`rvest`](https://rvest.tidyverse.org/) package in R.

## Objectives

- Define HTML and CSS selectors
- Introduce the `rvest` package
- Demonstrate how to extract information from HTML pages
- Practice scraping data

## Audience

This workshop is designed for individuals with introductory-to-intermediate experience programming in R. As a course topic, I teach it in the second-to-last week of [Computing for the Social Sciences](https://cfss.uchicago.edu/) and could see versions of it included in courses such as Data Science for All and Data Science.

## Prework

I recommend using RStudio Cloud for this workshop as all the required packages have been pre-configured. If you want to use your local installation of R, follow the instructions below to ensure you have all required packages and materials.

### On RStudio Cloud

- Please sign up for a free [RStudio Cloud account](https://rstudio.cloud)
- Open [this project](https://rstudio.cloud/project/3460048) in RStudio Cloud
- Click "Save a Permanent Copy" on the navigation bar

### On a local computer

- Make sure you have the latest version of [R](https://www.r-project.org/) and [RStudio](https://www.rstudio.com/products/rstudio/download/#download) installed on your computer
- Install the following packages in R:

    ```r
    install.packages(c("tidyverse", "usethis", "rvest"))
    ```
- Run the following command in R to download the required materials:

    ```r
    usethis::use_course("bensoltoff/web-scraping")
    ```

## Links

- [Slides from the workshop](slides/index.html)
