# Business Analytics of Craigslist car sales dataset

**Author:** Adettoun  
**Date:** 2023-05-18

This repository contains code and analysis for business analytics of the Craigslist car sales dataset.
## Getting Started
## Introduction

In this project, I analyze sales data of used vehicles from Craigslist to understand the impact of odometer, year, title status, and condition on the price of the car in the US. The exploratory data analysis resulted in some interesting findings. I also observed that the price of a used car is positively correlated with its manufacturing year, and cars with a clean title status tend to fetch a higher price. Also, as anticipated, the correlation matrix revealed a negative association between price and odometer.

## Analysis Details

- [Data Cleaning](#data-cleaning-step)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Distribution Analysis](#distribution-analysis)
- [Simple Linear Regression](#simple-linear-regression)
- [Multiple Linear Regression](#multiple-linear-regression)
- [ANOVA by Title_Status](#anova-by-title_status)
- [ANOVA by Condition](#anova-by-condition)

## Here are some key findings from the analysis:

Newer cars tend to have higher prices.
Cars with higher odometer values have lower prices.
Clean title status is associated with higher prices.
Better condition is associated with higher prices.


## Conclusion

This evaluation holds significant worth for both buyers and sellers in the pre-owned auto industry, as it offers valuable insights into market trends and aids in informed decision-making. Manufacturers can leverage the findings to gain an understanding of consumer preferences, enhance their production processes, and boost their brand's market share. Meanwhile, purchasers can make more informed decisions by keeping up with the current market trends.

To replicate or use the analysis in this repository, follow the steps below:

## Clone this repository to your local machine using the following command:
git clone https://github.com/Adettoun/Adettoun-Business-Analytics-Using-R.git


## You will need R and RStudio installed on your machine to run the R code. You can download R and RStudio from the following links:
- [R](https://cran.r-project.org/)
- [RStudio](https://www.rstudio.com/products/rstudio/download/)

# Open the R Markdown document (`README.Rmd`) in RStudio.

# Install the required R packages listed in the R Markdown document by running the following code chunks:
```R
install.packages("ggplot2")
install.packages("gplots")
install.packages("ggpubr")
# ... (install other packages as needed)






