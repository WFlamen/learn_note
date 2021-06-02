## 基本语法

* 所有公式定义格式为：
```
$...$ 或者 \(...\) 中的数学表达式将会在行内显示。
$$...$$ 或者 \[...\] 或者 ```math 中的数学表达式将会在块内显示。
```

* 正常实例：
> `$\sum_{i=0}^N\int_{a}^{b}g(t,i)\text{d}t$`
> 显示效果：**$\sum_{i=0}^N\int_{a}^{b}g(t,i)\text{d}t$**

* 居中放大实例：
> `$$\sum_{i=0}^N\int_{a}^{b}g(t,i)\text{d}t$$`
> 显示效果：**$$\sum_{i=0}^N\int_{a}^{b}g(t,i)\text{d}t$$**

## 希腊字母
| 显示 |     命令     | 显示 |    命令    |
| ---- | ------------ | ---- | ---------- |
|  α   |  `$\alpha$`  |  β   | `$\beta$`  |
|  γ   |  `$\gamma$`  |  δ   | `$\delta$` |
|  ϵ   | `$\epsilon$` |  ζ   | `$\zeta$`  |
|  η   |   `$\eta$`   |  θ   | `$\theta$` |
|  ι   |  `$\iota$`   |  κ   | `$\kappa$` |
|  λ   | `$\lambda$`  |  μ   |  `$\mu$`   |
|  ν   |   `$\nu$`    |  ξ   |  `$\xi$`   |
|  π   |   `$\pi$`    |  ρ   |  `$\rho$`  |
|  σ   |  `$\sigma$`  |  τ   |  `$\tau$`  |
|  υ   | `$\upsilon$` |  ϕ   |  `$\phi$`  |
|  χ   |   `$\chi$`   |  ψ   |  `$\psi$`  |
|  ω   |  `$\omega$`  |      |            |

* 如果需要大写的希腊字母，只需将命令的首字母大写即可(有的字母没有大写)，如:
> `$\gamma$ & $\Gamma$`  -->  **$\gamma$ & $\Gamma$**

* 若需要斜体希腊字母，在命令前加上var前缀即可(大写可斜)，如:
> `$\Gamma$ & $\varGamma$`  -->  **$\Gamma$ & $\varGamma$**

## 字母修饰
* 上下标：
  > 上标：`$C^2$`  -->  **$C^2$**
  > 下标：`$C_n$`  -->  **$C_n$**

* 矢量：
  > `$\vec a$`  -->  **$\vec a$**
  > `$\overrightarrow {xy}$`  -->  **$\overrightarrow {xy}$**

* 字体：
  * Typewriter：
    > `$\mathtt {ABCDEFGHIJKLMNOPQRSTUVWXYZ}$`
    > 显示效果：**$\mathtt {ABCDEFGHIJKLMNOPQRSTUVWXYZ}$**

  * Blackboard Bold：
    > `$\mathbb {ABCDEFGHIJKLMNOPQRSTUVWXYZ}$`
    > 显示效果：**$\mathbb {ABCDEFGHIJKLMNOPQRSTUVWXYZ}$**

  * Sans Serif：
    > `$\mathsf {ABCDEFGHIJKLMNOPQRSTUVWXYZ}$`
    > 显示效果：**$\mathsf {ABCDEFGHIJKLMNOPQRSTUVWXYZ}$**

* 分组：
  * {}分组功能:
    > `$10^{10}$ & $10^10$`
    > 显示效果：**$10^{10}$ & $10^10$**

* 括号：
  * 小括号;
    > `$()$`  -->  **$()$**
  * 中括号;
    > `$[]$`  -->  **$[]$**
  * 尖括号;
    > `$\langle\rangle$`   -->  **$\langle\rangle$**
  * 使用`$\left($`和`$\right)$`使符号大小与邻近的公式相适应；
    > `$(\frac{x}{y})$ & $\left(\frac{x}{y}\right)$`
    > 显示效果：**$(\frac{x}{y})$ & $\left(\frac{x}{y}\right)$**

* 求和、极限与积分:
  * 求和\sum;
    > `$\sum_{i=1}^n{a_i}$`  -->  **$\sum_{i=1}^n{a_i}$**
  * 极限\lim;
    > `$\lim_{x\to 0}$`  -->  **$\lim_{x\to 0}$**
  * 积分\int;
    > `$\int_0^\infty{fxdx}$`  -->  **$\int_0^\infty{fxdx}$**

* 分式与根式：
  * 分式\frac;
    > `$\frac{x}{y}$`  -->  **$\frac{x}{y}$**
  * 根式\sqrt：
    > `$\sqrt[x]{y}$`  -->  **$\sqrt[x]{y}$**

* 特殊函数：
  * \函数名：
    > `$\sin x$ & $\ln x$ & $\max(A,B,C)$`  -->  **$\sin x$ & $\ln x$ & $\max(A,B,C)$**

*  特殊符号:

| 显示 |      命令       | 显示 |     命令     |
| ---- | --------------- | ---- | ------------ |
|  ∞   |   `$\infty$`    |  ∪   |   `$\cup$`   |
|  ∩   |    `$\cap$`     |  ⊂   | `$\subset$`  |
|  ⊆   |  `$\subseteq$`  |  ⊃   | `$\supset$`  |
|  ∈   |     `$\in$`     |  ∉   |  `$\notin$`  |
|  ∅   | `$\varnothing$` |  ∀   | `$\forall$`  |
|  ∃   |   `$\exists$`   |  ¬   |  `$\lnot$`   |
|  ∇   |   `$\nabla$`    |  ∂   | `$\partial$` |

* 空格：
  * LaTex会忽略空格；
  * 小空格\ ；
    > `$a\ b$`  -->  **$a\ b$**
  * 4个空格\quad;
    > `$a\quad b$`  -->  **$a\quad b$**

* 绝对值:
  > `$\lvert x \rvert$` --> **$\lvert x \rvert$**

* 左右符号自适应:
  > `$\lvert \frac{x^2}{\sqrt{y}} \rvert$` -->  $\lvert \frac{x^2}{\sqrt{y}} \rvert$
  > `$\left\lvert \frac{x^2}{\sqrt{y}} \right\rvert$` --> $\left\lvert \frac{x^2}{\sqrt{y}} \right\rvert$

## 矩阵
* 基本语法：
  * 起始标记`begin{matrix}`；
  * 结束标记e`nd{matrix}`；
  * 每行末尾标记`\\`；
  * 行间元素之间以`&`分隔；
    ```
    $$\begin{matrix}
    1&0&0\\
    0&1&0\\
    0&0&1\\
    \end{matrix}$$
    ```
    > $$\begin{matrix}
    > 1&0&0\\
    > 0&1&0\\
    > 0&0&1\\
    > \end{matrix}$$

* 矩阵边框:
  * 将matrix换成下列词语;

|  命令   |    样式    |
| ------- | ---------- |
| matrix  |   无样式   |
| pmatrix | 小括号边框 |
| bmatrix | 中括号边框 |
| Bmatrix | 大括号边框 |
| vmatrix | 单竖线边框 |
| Vmatrix | 双竖线边框 |

  * 省略元素；
    * 横省略号\cdots；
    * 竖省略号\vdots；
    * 斜省略号\ddots；
      ```
      $$\begin{vmatrix}
      {a_{11}}&{a_{12}}&{\cdots}&{a_{1n}}\\
      {a_{21}}&{a_{22}}&{\cdots}&{a_{2n}}\\
      {\vdots}&{\vdots}&{\ddots}&{\vdots}\\
      {a_{m1}}&{a_{m2}}&{\cdots}&{a_{mn}}\\
      \end{vmatrix}$$
      ```
      > $$\begin{vmatrix}
      > {a_{11}}&{a_{12}}&{\cdots}&{a_{1n}}\\
      > {a_{21}}&{a_{22}}&{\cdots}&{a_{2n}}\\
      > {\vdots}&{\vdots}&{\ddots}&{\vdots}\\
      > {a_{m1}}&{a_{m2}}&{\cdots}&{a_{mn}}\\
      > \end{vmatrix}$$

* 阵列；
  * 起始、结束处以{array}声明；
  * 对齐方式：在{array}后以{}逐行统一声明；
    * 左对齐：1；居中：c；
    * 右对齐：r；
    * 竖直线：在声明对齐方式时，插入|建立竖直线；

  * 插入水平线：\hline；

  ```
  $$\begin{array}{c|lll}
  {↓}&{a}&{b}&{c}\\
  \hline
  {R_1}&{c}&{b}&{a}\\
  {R_2}&{b}&{c}&{c}\\
  \end{array}$$
  ```

  > $$\begin{array}{c|lll}
  > {↓}&{a}&{b}&{c}\\
  > \hline
  > {R_1}&{c}&{b}&{a}\\
  > {R_2}&{b}&{c}&{c}\\
  > \end{array}$$

* 方程组:
  * 需要cases环境：起始、结束处以{cases}声明;
    ```
    $$\begin{cases}
    a_1x+b_1y+c_1z=d_1\\
    a_2x+b_2y+c_2z=d_2\\
    a_3x+b_3y+c_3z=d_3\\
    \end{cases}$$
    ```
    > $$\begin{cases}
    > a_1x+b_1y+c_1z=d_1\\
    > a_2x+b_2y+c_2z=d_2\\
    > a_3x+b_3y+c_3z=d_3\\
    > \end{cases}$$
