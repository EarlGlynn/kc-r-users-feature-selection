# Survey of Machine Learning Feature Selection Methods
Talk given on Sept. 8, 2018 to the [KC R Users Group](https://www.meetup.com/Kansas-City-R-Users-Group/).

The talk is an overview of several feature selection methods, including:

1. Remove Highly Correlated Variables
1. Run OLS and select significant features
1. Caret’s Recursive Feature Extraction (RFE)
1. Feature Importance
1. glmnet
1. Boruta “All Relevant” Variables
1. Singular Value Decomposition (SVD)
1. Principal Component Analysis (PCA)

The Forensic Glass dataset from the MASS package is used in most of the examples.

Since the use of PCs as predictors was introduced as a topic, the last few slides show visual exploratory analysis of PCs in a 3D scatterplot, both interactively and with an animated GIF file.

## Files
R Markdown and corresponding HTML files:

**Forensic-Glass-FILE.Rmd** and **Forensic-Glass-FILE.html**

**FILE**

    Boruta
    Correlation
    PCA
    SVD

**Forensic-Glass-caret-FILE.Rmd** and **Forensic-Glass-caret-FILE.html**

**FILE**

    glmnet
    RFE

Some additional files mentioned can be found in a talk given last year:  [Using R's Caret Package for Machine Learning](https://github.com/EarlGlynn/kc-r-users-caret-2017).

