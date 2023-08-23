# Fitting Multinomial Logistic Regression Model in R
This is a repository for my statistical modelling endeavor to fit a multinomial logistic regression model to 
the fetal health data set, available on Kaggle here: [Fetal Health Classification](https://www.kaggle.com/datasets/andrewmvd/fetal-health-classification). 
You can also find the data within the data folder of this repository.

## Goals

- Practice fitting the multinomial logistic regression model
- Practice balancing data sets via over/under-sampling class stratified observations
- Applying Principal Component Analysis (PCA) to a set of predictors/features
- Use visualizations and computed metrics to assess model fit
- Practice using the [box package](https://klmr.me/box/articles/box.html) for explicit package and function dependencies (instead of using library() calls)

## Viewing the Notebook
There are two options:

1. Download this repository and knit the R Markdown document locally
2. Use this link to view the github.io website hosted from this repository: [Notebook Link](https://andrewdisher.github.io/multinomial-logistic-regression/)

## A Note on renv

[renv](https://rstudio.github.io/renv/articles/renv.html) is an R package that provides a way to track packages, their package dependencies, and the versions for these packages. 
It makes creating a reproducible R coding environment extremely easy and ensures that the packages used will always stay the same, even when future releases are announced. 

After downloading this repository and opening the R project, you must run this line of code in your R r console:

```
renv::restore(clean = TRUE)
```

This will use the `renv.lock` file to restore the project environment. After that, you should be able to knit the R Markdown document
as usual. 
