## 常用结论
- $\lim\limits_{x\rightarrow0}\frac{sinx}{x} = 1$
> $\lim\limits_{x\rightarrow0}(1 + x)^\frac{1}{x} = e$
> $\lim\limits_{x\rightarrow\infty}(1 + \frac{1}{x})^x = e$
> $\lim\limits_{x\rightarrow0^+}(1 + \frac{1}{x})^x = e$
- $\lim\limits_{x\rightarrow+\infty}(1 + x)^\frac{1}{x} = 1$

- $\lim\limits_{x\rightarrow0}(\frac{a^x - 1}{x}) = \ln a$

- $\lim\limits_{x\rightarrow\infty}\sqrt[n]{n} = 1$

- $\lim\limits_{x\rightarrow\infty}\sqrt[a]{n} = 1 (a > 0)$

- $\lim\limits_{x\rightarrow\infty}\frac{a_nx^n + a_{n-1}x^{n+1} + ... + a_1x + a_0}{b_mx^m + b_{m - 1}x^{m - 1} + ... + b_!x + b_0} = \left\{
\begin{matrix}
 \frac{a_n}{b_m}, n = m, \\
 0, n < m,  \\
 \infty, n > m, 
\end{matrix}
\right.$
> 多项式趋近于无穷只需看最高次，趋向0只需看最低次

- $\lim\limits_{x\rightarrow\infty}x^n = \left\{
\begin{matrix}
 0, | x | < 0, \\
 +\infty, | x | > 0,  \\
 1, x  = 0, 
\end{matrix}
\right.$

## 等价无穷小
$x \sim sinx \sim tanx \sim arcsinx \sim arctanx \sim \ln(1 + x) \sim e^x - 1$

$(1 + x)^n \sim ax$

$1 - cosx \sim \frac{1}{2}x^2$

$a^x - 1 \sim x\ln a$

$x - sinx \sim \frac{1}{6}x^3$&nbsp;&nbsp;&nbsp;&nbsp;$tanx - x = \frac{1}{3}x^3$

$arcsinx - x \sim \frac{1}{6}x^3$&nbsp;&nbsp;&nbsp;&nbsp;$x - arctanx = \frac{1}{3}x^3$

$x - \ln (1 + x) \sim \frac{1}{2}x^2$

#### 一些推广
$sin ax \sim ax$

$e^{ax^b} - 1 \sim ax^b$

$(1 + \alpha(x))^{\beta(x)} - 1 \sim \alpha(x)\beta(x)$&nbsp;条件:$(\alpha(x) > 0, \alpha(x)\beta(x) > 0)$

$1 - cos^ax \sim \frac{a}{x}x^2$

$\ln(1 + bx^a) \sim bx^a$

## 泰勒公式
- $e^x = 1 + x + \frac{x^2}{2!} + ... + \frac{x^n}{n!} + o(x^n)$

- $sinx = x - \frac{x^2}{3!} + ... + (-1)^{n - 1}\frac{x^{2n - 1}}{(2n - 1)!} + o(x^{2n - 1})$

- $cosx = x - \frac{x^2}{2!} + ... + (-1)^{n}\frac{x^{2n}}{(2n)!} + o(x^{2n})$

- $\ln(1 + x) = x - \frac{x^2}{2} + ... + (-1)^{n}\frac{x^n}{n} + o(x^n)$

- $(1 + x)^n = 1 + \alpha x + \frac{\alpha(\alpha - 1)}{2!}x^2 + ... + \frac{\alpha(\alpha - 1)...(\alpha - n + 1)}{2!}x^n + o(x^n)$