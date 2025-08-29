# Framingham Logistic Modeling

This project analyzes the Framingham Heart Study dataset using logistic regression and other classification methods. The goal is to model cardiovascular disease risk and compare performance across multiple approaches. For this project, we use a course-provided dataset from my time at the University of Washington to illustrate these methods; the focus is on model application, comparison, and interpretation rather than data collection.

## Project Structure

- `framingham_logistic_modeling.Rmd` — Main R Markdown file containing code and explanations.
- `framingham_logistic_modeling.html` — Knitted HTML version of the analysis.
- `framingham_logistic_modeling.pdf` — Knitted PDF version of the analysis.
- `data/` — Contains the dataset used in the project.
- `figures/` — Exported plots from the analysis.

## Key Points

- Logistic regression models trained on subsets of predictors.  
- Comparison with additional classification methods (e.g., Ridge regression, LASSO regression).  
- Performance evaluated via accuracy scores and confusion matrices.  

## Requirements

- R (≥ 4.0)  
- RStudio (recommended)  
- R packages: `glmnet`, `leaps`, `ggplot2`, `caret`
You can install the R packages with: `install.packages(c("glmnet", "leaps", "ggplot2", "caret"))`

## How to Use

1. Clone or download this repository.  
2. Open `framingham_logistic_modeling.Rmd` in RStudio.  
3. Run the code chunks to reproduce results and figures. 