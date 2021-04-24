# Chapter3

## 3.1 Point operator

$f(x)$,$g(x)$ are pics, $x \in \mathbb{R}^2$

Pixel transforms
$g(x) = h(f(x))$

- $g(x) = af(x)+b$, a is contrast, b is brightness
- linear blend operator $g(x) = (1- \alpha) f_0(x)+ \alpha f_1(x)$
- gamma correction $g(x) = [f(x)]^{\frac{1}{\gamma}}$ ,$\gamma = 2.2$ for most pics.