# Hypothesis Formulation
This repository contains R code and supporting functions for the paper:

**"Choice of the hypothesis matrix for using the ANOVA-type statistic"** by Paavo Sattler and Manuel Rosenbaum
 (<https://doi.org/10.1016/j.spl.2025.110356>)


## Contents
- R function `MSroot` to calculate the matrix square root of a positive semidefinite matrix.
- R function `MSrootcompact` to calculate the compact root of a positive semidefinite matrix to transform the hypothesis matrix without changing the value of the ATS (Anova-type-statistic).
- R function `CompanionHypothesis`, which for a given linear null hypothesis (specified through hypothesis matrix **H** and corresponding vector **y**) returns the hypothesis matrix **L** and corresponding **ytilde**. These formulate the same hypothesis as the initial ones and also result in the same value of the ATS but have a minimal number of rows. 
- R function `ZhangHypothesis`, which for a given linear null hypothesis (specified through hypothesis matrix **H** and corresponding vector **y**) returns the hypothesis **G** and corresponding **yGtilde**, based on the work of Zhang et al. (2017)

## Literature
- Sattler, P. und Rosenbaum, M. (2025); Choice of the hypothesis matrix for using the Anova-type-statistic. Statistics & Probability Letters, Volume 219, page 110356.
 <https://doi.org/10.1016/j.spl.2025.110356)>
- Zhang, J.T., Guo, J., Zhou, B., 2017. Linear hypothesis testing in high-dimensional one-way manova. J. Multivariate Anal. 155, 200–216.
 <http://dx.doi.org/10.1016/j.jmva.2017.01.002>
