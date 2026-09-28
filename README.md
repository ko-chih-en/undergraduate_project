# undergraduate_project

In this project, we compare 4 methods to compute or estimate the one bit quantization problem.

One bit quantization problem:

Assuming that X_1 and X_2 are two N(0, 1) random variables and d is the threshold for one-bit quantization.

$Y_1 = \begin{array}[ll]
1 & if X_1>d
\end{array}$ if $X_1>d$ and $-1$ if $X_1<d$

$Y_2 = 1$ if $X_2>d$ and $-1$ if $X_2<d$

$\mu = Y_1 Y_2$

And, we aim to use $\mathcal{E}[\mu]$ to derive the correlation coefficient of $X_1$ and $X_2$.


