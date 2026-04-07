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
- 
# 1. 標題（Heading）
# 人工智慧作業

## 2. 次標題
## 次標題

### 3. 更小標題
### 更小標題

**4. 粗體**
**粗體***

*5. 斜體*
*斜體*

~~6. 刪除線~~
~~刪除線~~

> 7. 引用
> 引用

- 8. 無序清單
- 無序清單

1. 9. 有序清單
1. 有序清單

`10. 行內程式碼`
`行內程式碼`
