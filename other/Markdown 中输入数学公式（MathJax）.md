# Markdown 中输入数学公式（MathJax）

## 基本语法

* 所有公式定义格式为：

```
$...$ 或者 \(...\) 中的数学表达式将会在行内显示。
$$...$$ 或者 \[...\] 或者 ```math 中的数学表达式将会在块内显示。
```

* 正常实例：

> `$\sum_{i=0}^N\int_{a}^{b}g(t,i)\text{d}t$`
> ![MathJax 示例效果一](http://qiniu.wflamen.cn/254eb47b08479392a48338e6e3f4e0df.png)

* 居中放大实例：

> `$$\sum_{i=0}^N\int_{a}^{b}g(t,i)\text{d}t$$`
> 显示效果：![MathJax 示例效果二](http://qiniu.wflamen.cn/img/20210602164235.png)

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

> `$\gamma$ & $\Gamma$`  -->  ![效果三](http://qiniu.wflamen.cn/c0947e7316f50c2e2a5d3a69c7583549.png)

* 若需要斜体希腊字母，在命令前加上var前缀即可(大写可斜)，如:

> `$\Gamma$ & $\varGamma$`  -->  ![效果四](http://qiniu.wflamen.cn/5f3a4c353df6638b58d6dc42da270089.png)

## 字母修饰

* 上下标：
  > 上标：`$C^2$`  -->  ![效果五](http://qiniu.wflamen.cn/603a5e9d666f315616574c052935a21e.png)
  > 下标：`$C_n$`  -->  ![效果六](http://qiniu.wflamen.cn/86d088f147107bae805b0817d6e24f25.png)

* 矢量：
  > `$\vec a$`  -->  ![效果七](http://qiniu.wflamen.cn/6c5da13f7d4d6816a413f595d085a4ce.png)
  > `$\overrightarrow {xy}$`  -->  ![效果八](http://qiniu.wflamen.cn/11c8a4a68ad57bdbf30d45432fa56662.png)

* 字体：
  * Typewriter：
    > `$\mathtt {ABCDEFGHIJKLMNOPQRSTUVWXYZ}$`
    > 显示效果：
    > ![效果九](http://qiniu.wflamen.cn/41bc9415fbee8f83a532bfb582decbdf.png)

  * Blackboard Bold：
    > `$\mathbb {ABCDEFGHIJKLMNOPQRSTUVWXYZ}$`
    > 显示效果：
    > ![效果十](http://qiniu.wflamen.cn/57f3fe98315501b26aed38d489e628e4.png)

  * Sans Serif：
    > `$\mathsf {ABCDEFGHIJKLMNOPQRSTUVWXYZ}$`
    > 显示效果：
    > ![效果十一](http://qiniu.wflamen.cn/7e8789a90ae308ee65b92a5599afa9ce.png)

* 分组：
  * {}分组功能:
    > `$10^{10}$ & $10^10$`
    > 显示效果：![效果十二](http://qiniu.wflamen.cn/748d6e46a25117aa8d63b737600a0f28.png)

* 括号：
  * 小括号;
    > `$()$`  -->  **( )**
  * 中括号;
    > `$[]$`  -->  **[ ]**
  * 尖括号;
    > `$\langle\rangle$`   -->  **< >**
  * 使用`$\left($`和`$\right)$`使符号大小与邻近的公式相适应；
    > `$(\frac{x}{y})$ & $\left(\frac{x}{y}\right)$`
    > 显示效果：![效果十三](http://qiniu.wflamen.cn/e5d3f7df1dedb3cda8ccfca9a5b6f4ad.png)

* 求和、极限与积分:
  * 求和\sum;
    > `$\sum_{i=1}^n{a_i}$`  -->  ![效果十四](http://qiniu.wflamen.cn/9597e136b5969f4b591085d35f695743.png)
  * 极限\lim;
    > `$\lim_{x\to 0}$`  -->  ![效果十五](http://qiniu.wflamen.cn/7bc8fecd39e7ada8af8e48d664b8b01c.png)
  * 积分\int;
    > `$\int_0^\infty{fxdx}$`  -->  ![效果十六](http://qiniu.wflamen.cn/e86c0e7bafb656ffdfab0640cb279dce.png)

* 分式与根式：
  * 分式\frac;
    > `$\frac{x}{y}$`  -->  ![效果十七](http://qiniu.wflamen.cn/f53d98b4b369a05837840fa13cfdcbd7.png)
  * 根式\sqrt：
    > `$\sqrt[x]{y}$`  -->  ![效果十八](http://qiniu.wflamen.cn/d4dbb54cb679855fc55065a5a493c1bb.png)

* 特殊函数：
  * \函数名：
    > `$\sin x$ & $\ln x$ & $\max(A,B,C)$`  -->  ![效果十九](http://qiniu.wflamen.cn/ce726fd3f3d552720a6163395e35ae6f.png)

* 特殊符号:

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
    > `$a\ b$`  -->  **a b**
  * 4个空格\quad;
    > `$a\quad b$`  -->  ![效果二十](http://qiniu.wflamen.cn/4beaee9f9d3ef65b9b2a7f8510b04937.png)

* 绝对值:
  > `$\lvert x \rvert$` --> ![效果二十一](http://qiniu.wflamen.cn/f0cc7b4e0895448795f2ef98f306fb6e.png)

* 左右符号自适应:
  > `$\lvert \frac{x^2}{\sqrt{y}} \rvert$` -->  ![效果二十二](http://qiniu.wflamen.cn/c52579b7ea1f0fa52c3e5ba8179cb67c.png)
  > `$\left\lvert \frac{x^2}{\sqrt{y}} \right\rvert$` --> ![效果二十三](http://qiniu.wflamen.cn/4e14c4af32ddcb9314ef06894e4f1fec.png)

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

    > ![效果二十四](http://qiniu.wflamen.cn/d32b1088322f38a88d4d63ca2a46721a.png)

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

      > ![效果二十五](http://qiniu.wflamen.cn/38abebad9a024758b02c162c30d194aa.png)

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

    > ![效果二十六](http://qiniu.wflamen.cn/79d3d39d8a906e82c28337dc8c39d22f.png)

* 方程组:
  * 需要cases环境：起始、结束处以{cases}声明;

    ```
    $$\begin{cases}
    a_1x+b_1y+c_1z=d_1\\
    a_2x+b_2y+c_2z=d_2\\
    a_3x+b_3y+c_3z=d_3\\
    \end{cases}$$
    ```

    > ![效果二十七](http://qiniu.wflamen.cn/d839bdebfdb27673938271ed70e4ddbc.png)
