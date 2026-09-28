# undergraduate_project

In this project, we compare 4 methods to compute or estimate the one bit quantization problem.

One bit quantization problem:

Assuming that X_1 and X_2 are two N(0, 1) random variables and d is the threshold for one-bit quantization.

$$
Y_1 = 
\begin{cases}
1, & \text{if \ } X_1 > d \\
-1, & \text{if \ } X_1 < d
\end{cases}
$$

$$
Y_2 = 
\begin{cases}
1, & \text{if } X_2 > d \\
-1, & \text{if } X_2 < d
\end{cases}
$$

and
$$\mu = Y_1 Y_2$$.

Here we aim to use $\mathcal{E}[\mu]$ to derive the correlation coefficient of $X_1$ and $X_2$.


