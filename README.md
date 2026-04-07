# 0407
Initialization: $\hat{h}(0) = \mathrm{zeros}(p)$

Computation: For $n = 0,1,2,\ldots$

$$
\mathbf{x}(n) = \left[ x(n), x(n-1), \ldots, x(n-p+1) \right]^T
$$

$$
e(n) = d(n) - \hat{h}^H(n)\mathbf{x}(n)
$$

$$
\hat{h}(n+1) = \hat{h}(n) + \frac{\mu\, e^*(n)\mathbf{x}(n)}{\mathbf{x}^H(n)\mathbf{x}(n)}
$$

---
## Notes
- 人工智慧作業

