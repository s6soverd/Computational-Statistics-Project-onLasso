
# Computational Statistics Course Project: 
## On the shrinkage method - LASSO, does the shrinkage of OLS parameters give improved prediction errors?
## Exploring the essential quality of LASSO in setting parameters to zero under various simulatory contexts

<a href="https://nbviewer.jupyter.org/github/s6soverd/Computational-Statistics-Project-onLASSO/blob/master/finalproject_lasso.ipynb"
   target="_parent">
   <img align="center"
  src="https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.png"
      width="109" height="20">
</a>
<a href="https://mybinder.org/v2/gh/s6soverd/Computational-Statistics-Project-onLASSO/master?filepath=finalproject_lasso.ipynb"
    target="_parent">
    <img align="center"
       src="https://mybinder.org/badge_logo.svg"
       width="109" height="20">
</a>
---

#### Downloading and Viewing this project:
The best way to view this project is to view it from nbviewer/or mybinder badges above. As github can't read certain markdown syntax in jupyter notebook. Or even better, by downloading it from this github repository. 

#### Briefly on the project:
This paper focuses on the theoretical properties of LASSO - an  𝑙1 -norm regularization method, and drawing upon these theoretical properties, I have set up simulations that elucidate either visually or with the help of tables how LASSO acts in certain specified settings, and with which features it differs from OLS or Ridge - both being also linear regression methods. The structure of the paper is outlined in the "Table of Contents" below. The first section focuses briefly on the famous "Bias and Variance" tradeoff in Machine Learning, which builds the context on why I chose to focus on LASSO for this project paper. The second section explains why OLS fails in estimating parameters in high-dimensional data settings, what is high-dimensional and why LASSO is helpful in such settings are all accounted for in this section, as well. The proceeding Section sheds light on the fact that LASSO doesn't have a closed-form solution, but there are very few simplifed cases, where a LASSO estimation can be derived. The underlying subsection 3.1. shows in simulatory setting what happens when we shrink OLS parameters by very small random values. Questions like *"Are we getting better predictions? Or do the variance of such models get improved? etc."* are addressed in this set-up.

The Section 4, in passing, talks about the major difference and commonalities between Ridge and LASSO, before we utilize simulation set-ups that use also Ridge as a benchmark. In the subsection 4.1., with a simple linear regression model I show visually why Ridge only assymptotically gets close to zero, but LASSO can indeed set the parameter, in question, to zero. In the Section 5, it is shown when the some values of true  𝛽  vector are zero, on average, which of the linear regression methods are good at predicting them.

The rest of this project paper is comprised of 2 simulations that unravel the differences between Ridge and LASSO. Questions like *"How the parameters of the covariates with differential variances are dealt by LASSO and Ridge?, "What about the parameters of correlated covariates?"* are all adressed in these two sections.

### References:
1. Gauraha, N. (2018). Introduction to the LASSO. *Reson, 23*, 439–464. 

2. Wieringen, W.N. (2015). Lecture notes on ridge regression. arXiv: Methodology.

3. Gareth James, Daniela Witten, Trevor Hastie, Robert Tibshirani. (2013). An introduction to statistical learning: with applications in R. New York: Springer.

4. Belloni, Alexandre, Victor Chernozhukov, and Christian Hansen. (2014). "High-Dimensional Methods and Inference on Structural and Treatment Effects." *Journal of Economic Perspectives, 28 (2):* 29-50.





