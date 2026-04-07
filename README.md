# 0407
## 隨便打字
**$\hat{h}(0) = zeros(p)$**
---

## Computation
For `n = 0, 1, 2, ...`

### Input Vector
$$
x(n) = [x(n), x(n-1), \dots, x(n-p+1)]^T
$$

### Error
$$
e(n) = d(n) - \hat{h}^H(n)x(n)
$$

### Update
$$
\hat{h}(n+1) = \hat{h}(n) + \frac{\mu e^*(n)x(n)}{x^H(n)x(n)}
$$

---
## Notes
- 人工智慧作業

