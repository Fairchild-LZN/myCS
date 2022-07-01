# Latex

## 希腊字母

- $\delta, \lambda$
- $\Delta, \Lambda$
- $\phi, \varphi$
- $\epsilon, \varepsilon$

## 上下标

- $a^2, a_1$
- $x^{y+z}, p_{ij}$
- $x_i, x_{\text i}, x_{\rm i}$

## 分式与根式

- $\frac{1}{2}$
- $\frac{1}{x+y}$
- $\dfrac{\dfrac{1}{x}+1}{y+1}$
- $\sqrt{2}$
- $\sqrt{x+y}$
- $\sqrt[5]{x}$

## 普通运算符

- $+, -$
- $\times, \cdot, \div$
- $\pm, \mp$
- $>, <, \le, \ge, \gg, \ll, \ne, \approx, \equiv$
- $\cap, \cup, \in, \notin, \subseteq, \subseteqq, \varnothing$
- $\forall, \exist$
- $\because, \therefore$
- $\R, \mathbb Q, \Z$
- $\mathcal F, \mathscr F$
- $\cdots, \vdots, \ddots$
- $\infty, \partial, \nabla, \degree, \propto$
- $\sin x, \cosh x$
- $\log_2 x, \ln x, \lg x$
- $\lim_{x \to 0}\frac{x}{\sin x}$
- $\lim\limits_{x \to 0}\frac{x}{\sin x}$
- $\text{MSE}(x)$

## 大型运算符

- $\sum, \prod$
- $\sum_{i=0}^n x_i$
- $\sum\limits_{i=0}^n x_i$
- $\int, \iint, \oint, \oiint$
- $\int_{-\infty}^0 f(x)\,\text{d} x$
- $a\,a$
- $a\ a$
- $a\quad a$
- $a\qquad a$

## 标注符号

- $\vec{x}, \overrightarrow{AB}, \bar{x}$

## 箭头

- $\rightarrow, \Leftarrow, \Leftrightarrow, \longleftarrow$

## 括号与定界符

- $[], (), \{\}, ||$
- $\left(0, \frac{1}{a}\right]$
- $\left.\frac{\partial f}{\partial x}\right|_{x=0}$

## 多行公式

$$
\begin{align}
a&=b+c\\
&=e+f
\end{align}
$$

## 大括号

$$
f(x)=
\begin{cases}
    \sin x, & -\pi\le x \le \pi\\
    0, &\text{其他}
\end{cases}
$$

## 矩阵

- 第一种
$$
\begin{matrix}
    a & b & \cdots & z\\
    \vdots & \vdots & \ddots & \vdots\\
    e & f & \cdots & z
\end{matrix}
$$

- 第二种
$$
\begin{bmatrix}
    a & b & \cdots & z\\
    \vdots & \vdots & \ddots & \vdots\\
    e & f & \cdots & z
\end{bmatrix}
$$

- 第三种
$$
\begin{pmatrix}
    a & b & \cdots & z\\
    \vdots & \vdots & \ddots & \vdots\\
    e & f & \cdots & z
\end{pmatrix}
$$

- 第四种
$$
\begin{vmatrix}
    a & b & \cdots & z\\
    \vdots & \vdots & \ddots & \vdots\\
    e & f & \cdots & z
\end{vmatrix}
$$

## 实战演练

- $f(x)=\frac{1}{\sqrt{2/\pi}\sigma}{\rm e}^{-\frac{(x-\mu)^2}{2\sigma^2}}$
- $f(x)=\frac{1}{\sqrt{2/\pi}\sigma}\exp \left[ {-\frac{(x-\mu)^2}{2\sigma^2}} \right]$
- $\lim\limits_{N \to \infty} P \left\{ \left | \frac{I\left( \alpha_i \right)}{N} - H(s) \right| < \varepsilon  \right \} = 1$
- $x(n) = \frac{1}{2\pi} \int_{-\pi}^\pi X \left( \rm e^{{\rm j}\omega}\right) \rm e^{{\rm j}\omega n}\,{\rm d} \omega$

$$
\begin{align}
\vec B \left( \vec{r} \right) &= \frac{\mu_0}{4\pi} \oint_C \frac{I \, {\rm d} \vec l \times \vec{R}}{R^3}\\
&= \frac{\mu_0}{4\pi} \int_V \frac{\vec{J_v} \times \vec R}{R^3}\, {\rm d}V'
    
\end{align}
$$
