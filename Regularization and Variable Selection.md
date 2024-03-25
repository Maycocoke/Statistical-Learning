# Regularization and Variable Selection

Contents:

1. Lasso
2. Ridge
3. Comparision between LASSO and Ridge
4. Lesat Angle Regression
5. Selection Consistency
6. Effective Degree of Freedom

## Nadaraya-Waston Kernel Regression
gaussian 
$$

\hat{f}(x) = \frac{\sum_{i=1}^n Y_i K(\frac{X_i-x}{h})}{sum_{i=1}^nK(\frac{X_i-x}{h})}=\sum_{i=1}^n W_i(x)Y_i

$$
