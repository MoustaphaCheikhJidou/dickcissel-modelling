# Dickcissel Abundance Modelling

## Description

This project provides a comprehensive analysis aimed at understanding the climatic and landscape factors that influence the abundance of dickcissels. By leveraging a rich environmental dataset, the study applies multiple linear regression techniques to identify key predictors of dickcissel abundance. The analysis not only includes descriptive statistics and visualizations but also incorporates model validation and diagnostic checks to ensure robust findings. The results are intended to support conservation efforts and guide habitat management decisions for this species.

## Project Contents

- **dickcissel_analysis.Rmd**: An R Markdown document containing the complete analysis code. The document includes:
  - Descriptive analysis (univariate statistics, distributions, etc.)
  - Bivariate and multivariate analyses
  - Construction and validation of a multiple linear regression model
  - Visualizations to assess the model and interpret results
- **dickcissel.csv**: The dataset used in the analysis (place in the project folder).
- **README.md**: This file, which explains the project, its goals, and its structure.
- **.gitignore**: Configuration file to ignore unwanted files (e.g., temporary files, cache).

## Objectives

- **Identify** the key environmental variables impacting dickcissel abundance.
- **Model** the relationship between these variables and abundance using multiple linear regression.
- **Provide** recommendations for conservation and habitat management based on the analysis results.

## Prerequisites

To run the `dickcissel_analysis.Rmd` file, you will need R and the following packages:

- ggplot2
- dplyr
- naniar
- e1071
- GGally
- corrplot
- ggcorrplot
- car
- vegan
- MASS
- RColorBrewer
- broom
- gridExtra

You can install these packages via CRAN using:

```r
required_packages <- c("ggplot2", "dplyr", "naniar", "e1071", "GGally", "corrplot", "ggcorrplot", "car", "vegan", "MASS", "RColorBrewer", "broom", "gridExtra")
install.packages(setdiff(required_packages, rownames(installed.packages())))
