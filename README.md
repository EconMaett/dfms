# dfms: Dynamic Factor Models for R

The dfms R package is available on [CRAN](https://cran.r-project.org/package=dfms), [GitHub](https://github.com/SebKrantz/dfms) and on [the package website](https://sebkrantz.github.io/dfms/).

Check out the post on R-bloggers called [Introducting dfms: Efficient Estimation of Dynamic FActor Models in R](https://www.r-bloggers.com/2022/10/introducing-dfms-efficient-estimation-of-dynamic-factor-models-in-r/).

Find a first introduction in the article [Introduction to dfms](https://sebkrantz.github.io/dfms/articles/introduction.html).

For a short theoretical overview of dynamic factor models consult the paper [Dynamic Factor Models: A Very Short Introduction](https://raw.githubusercontent.com/SebKrantz/dfms/main/vignettes/dynamic_factor_models_paper.pdf).

## EM algorithm

The dfms package provides efficient estimation of Dynamic Factor Models via the expectation maximization (EM) algorithm, which can be performed in different ways following: 

- Doz, C., Giannone, D., & Reichlin, L. (2011). A two-step estimator for large approximate dynamic factor models based on Kalman filtering. Journal of Econometrics, 164(1), 188-205. [doi:10.1016/j.jeconom.2011.02.012](https://doi.org/10.1016/j.jeconom.2011.02.012)

- Doz, C., Giannone, D., & Reichlin, L. (2012). A quasi-maximum likelihood approach for large, approximate dynamic factor models. Review of economics and statistics, 94(4), 1014-1024. [doi:10.1162/REST_a_00225](https://doi.org/10.1162/REST_a_00225)

- Banbura, M., & Modugno, M. (2014). Maximum likelihood estimation of factor models on datasets with arbitrary pattern of missing data. Journal of Applied Econometrics, 29(1), 133-160. [doi:10.1002/jae.2306](https://doi.org/10.1002/jae.2306)

## Comparison with other R packages

The dfms R package uses C++ code, making it orders of magnitudes faster than the popular [MARSS](https://cran.r-project.org/package=MARSS), [nowcasting](https://github.com/nmecsys/nowcasting) and [nowcastDFM](https://github.com/dhopp1/nowcastDFM) R packages.

## Citation

Krantz S, Bagdziunas R (2023). _dfms: Dynamic
Factor Models_. R package version 0.2.1,
<https://CRAN.R-project.org/package=dfms>.