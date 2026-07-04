**柯西不等式 **

**在求二元（或多元）代数式最值或者二元（或多元）不等式的证明的题目中，巧用柯西不等式会比较方便快捷。**

**二维形式：**

对于任意实数 $a、b、c、d$ ，则

$\color {Red}{(a^{2}+b^{2})(c^{2 }+d^{2})\geq(ac+bd)^{2}}\\$当且仅当 $ad=bc$ 时成立。

**拓展形式：**

设  $n \geq 2$  是正整数且 $ x_{1}, x_{2}, \ldots, x_{n}, y_{1}, y_{2}, \ldots, y_{n} \in \mathbb{R}$ , 则有: $\color {Red}{ \left(\sum_{i=1}^{n} x_{i}^{2}\right)\left(\sum_{i=1}^{n} y_{i}^{2}\right) \geq\left(\sum_{i=1}^{n} x_{i} y_{i}\right)^{2}}\\$ 当且仅当  $\dfrac{x_{1}}{y_{1}}=\dfrac{x_{2}}{y_{2}}=\ldots=\dfrac{x_{n}}{y_{n}}$  时取到等号。

**二维形式的证明：** $\begin{align} (a^2+b^2)(c^2+d^2) &=a^{2} c^{2}+b^{2} d^{2}+a^{2} d^{2}+b^{2} c^{2} \\ &=a^{2} c^{2}+2 a b c d+b^{2} d^{2}+a^{2} d^{2}-2 a b c d+b^{2} c^{2} \\ &=(a c+b d)^{2}+(a d-b c)^{2} \\ &\geqslant(a c+b d)^{2} \end{align}\\$ 等号在且仅在 $ad-bc=0$ ，即 $ad=bc$ 时成立。

**向量形式的证明：**

设： $ m=\left(a_{1}, a_{2}, a_{3}, \cdots, a_{n}\right), n=\left(b_{1}, b_{2}, b_{3}, \cdots, b_{n}\right) $ 

$\begin{array}{l} m \cdot n=a_{1} b_{1}+a_{2} b_{2}+a_{3} b_{3}+\cdots+a_{n} b_{n}=|\boldsymbol{m}||\boldsymbol{n}| \cos \langle\boldsymbol{m}, \boldsymbol{n}\rangle \\\\ \quad=\sqrt{a_{1}^{2}+a_{2}^{2}+a_{3}^{2}+\cdots+a_{n}^{2}} \sqrt{b_{1}^{2}+b_{2}^{2}+b_{3}^{2}+\cdots+b_{n}^{2}} \cos \langle\boldsymbol{m}, \boldsymbol{n}\rangle \\\\ \because \cos (m, n\rangle \leqslant 1 \\\\ \therefore a_{1} b_{1}+a_{2} b_{2}+a_{3} b_{3}+\cdots+a_{n} b_{n} \geqslant\sqrt{a_{1}^{2}+a_{2}^{2}+a_{3}^{2}+\cdots+a_{n}^{2}} \sqrt{b_{1}^{2}+b_{2}^{2}+b_{3}^{2}+\cdots+b_{n}^{2}} \end{array}$ 


---


**例 **$1.$ 在等差数列 {${a_{n}}$}中，若 $a_{1}^{2}+a_{19}^{2}=10$ ，则数列{${a_{n}}$}的前 $10$ 项和 $S_{10}$ 的最大值是 $(\qquad)$ 

**提示：**由 $(a_{1}+18d)^{2}+a_{1}^{2}=10$ ， 

$S_{10}=5(a_{1}+a_{10})=5(2a_{1}+9d)$ 

$$
(2a_{1}+9d)^{2}\leq(a_{1}^{2}+(a_{1}+18d)^{2})((\dfrac{3}{2})^{2}+(\dfrac{1}{2})^{2})\leq25
$$

 故2 $a_{1}+9d\leq5$ ，则 $S_{10}\leq25 $ 


---


**例** $2.$ 非负实数 $x，y$ 满足 $x^{2}+4y^{2}+4xy+4x^{2}y^{2}=32$ ，则 $\sqrt{7}（x+2y）+2xy$ 的最大值为 $(\qquad)$ 

**提示：** $(\sqrt{7}(x+2y)+2xy)^{2}\leq((x+2y)^{2}+(2xy)^{2})((\sqrt{7})^{2}+1)=256$ 

即： $\sqrt{7}（x+2y）+2xy\leq16 $ 


---


**例** $3.$ 已知 $x，y\geq0，x+y\leq1$ ，则 $4x^{2}+4y^{2}+(1-x-y)^{2}$ 的最小值 $(\qquad)$ 

**提示：**$(4x^{2}+4y^{2}+(1-x-y)^{2})(\dfrac14+\dfrac14+1)\geq(\sqrt{4x^{2}\cdot\dfrac{1}4}+\sqrt{4y^{2}\cdot\dfrac{1}4}+\sqrt{(1-x-y)^{2}})^2=1$ 

 所以：$4x^{2}+4y^{2}+(1-x-y)^{2}\geq\dfrac23$ 

等号在 $4x=4y=1-x-y$ 处取得，即 $x=y=\dfrac{1}{6}$ 时取得 .


---


**例** $4.$ 已知 $x＞0，y＞0$ 且 $x^{2}+\dfrac{y^{2}}{2}=1$ ，求 $x+\sqrt{2+3y^{2}}$ 的最大值为 $(\qquad)$ 

**提示：**我们把 $x+\sqrt{2+3y^{2}}$ 变形为： $x+\sqrt{2+3y^{2}}=x+\sqrt{6}\cdot \sqrt{\dfrac{1}{3}+\dfrac{y^2}{2}}$ 

由柯西不等式： $\left [x+\sqrt{6}\cdot \sqrt{\dfrac{1}{3}+\dfrac{y^2}{2}}\right]^2\leq \left [x^2+(\dfrac{1}{3}+\dfrac{y^2}{2})\right]\cdot(1^2+(\sqrt{6})^2)=\dfrac{28}{3}$ 

即： $x+\sqrt{2+3y^{2}}\leq\dfrac{2\sqrt{21}}{3}\\$


---


**例** $5.$ 已知$x,y,z\in(0,+\infty),且x+y+z=1,求\dfrac{1}{x}+\dfrac{9}{y}+\dfrac{25}{z}$的最小值。

**提示：**由柯西不等式可知：

$$
(x+y+z)(\dfrac{1}{x}+\dfrac{9}{y}+\dfrac{25}{z})\ge(1+3+5)^2=81
$$

因此$\dfrac{1}{x}+\dfrac{9}{y}+\dfrac{25}{z}\ge 81\\$

故知最小值为 $81$ ， 此时$x^2=\dfrac{y^2}{9}=\dfrac{z^2}{25}$, 又因为$x+y+z=1$，可以知道$x=\dfrac{1}{9},y=\dfrac{3}{9},z=\dfrac{5}{9}$，满足$x,y,z\in(0,+\infty)$


---


**例 **$6.$ 已知 $t=\dfrac{x+y+z}{\sqrt{x^2+2y^2+4z^2}}$,求$t$的最大值

**提示：**由柯西不等式可知，$(x^2+2y^2+4z^2)^{\frac{1}{2}}(1+\dfrac{1}{2}+\dfrac{1}{4})^{\frac{1}{2}}\ge(x+y+z)$

因此，$t=\dfrac{x+y+z}{\sqrt{x^2+2y^2+4z^2}}\le(1+\dfrac{1}{2}+\dfrac{1}{4})^{\frac{1}{2}}=\dfrac{\sqrt{7}}{2}$


---


**例** $7.$ 已知$\dfrac{3}{2}\le x\le 5$，求证:$\sqrt{4x+4}+\sqrt{2x-3}+\sqrt{15-3x}<\sqrt{78}$

**提示：**因为$[(x+1)+(2x-3)+(15-3x)]^{\frac{1}{2}}(4+1+1)^{\frac{1}{2}}\ge(\sqrt{4x+4}+\sqrt{2x-3}+\sqrt{15-3x})$

化简得$\sqrt{4x+4}+\sqrt{2x-3}+\sqrt{15-3x}\le\sqrt{78}$

又因为等式取等时 $\dfrac{x+1}{4}=2x-3=15-3x$ ，此时 $x$ 无解，故等式不成立，

可得$\sqrt{4x+4}+\sqrt{2x-3}+\sqrt{15-3x}<\sqrt{78}$


---


**例 **$8.$ 函数  $y=\sqrt{x-5}+2 \sqrt{6-x}$  的最大值是 $(\qquad)$ 

**提示：**根据柯西不等式, 知

$ y=1 \sqrt{x-5}+2 \sqrt{6-x} \leq   \sqrt{1^{2}+2^{2}} \cdot \sqrt{(\sqrt{x-5})^{2}+(\sqrt{6-x})^{2}}=\sqrt{5}$ 


---


**例**$ 9.$  实数 $x，y$ 满足 $3 x^2+2 y^2=6$ , 则 $2 x+y$ 的最大值是 $(\qquad)$ 

**提示：方法 **$1.$ **由柯西不等**式得：

$\left(3 x^2+2 y^2\right)\left(\dfrac{4}{3}+\dfrac{1}{2}\right) \geqslant(2 x+y)^2$ ,

故  $(2 x+y)^2 \leqslant 6 \times \dfrac{11}{6}=11$ , $\therefore 2 x+y \leqslant \sqrt{11}， \therefore 2 x+y$  的最大值是 $\sqrt{11}$ 




**方法** $2.$ **差别式法**

令： $2 x+y=k$ ， $y=k-2 x$ ， $3 x^2+2(k-2 x)^2=6$ ， $3 x^2+2\left(k^2-4 k x+4 x^2\right)=6$ , $11 x^2-8 k x+2 k^2-6=0$ ， $\Delta \geqslant 0$ ， $-\sqrt{11} \leqslant k \leqslant \sqrt{11}$ . 

**方法 **$3.$ **三角换元**

$\dfrac{x^2}{2}+\dfrac{y^2}{3}=1$ 令 $x=\sqrt{2} \cos \alpha，y=\sqrt{3} \sin \alpha$ ， 由 $2 \sqrt{2} \cos \alpha+\sqrt{3} \sin \alpha=\sqrt{11} \sin (\alpha+\varphi)$ , 所以最大值为 $\sqrt{11}$ .


---


例 $10.$ 已知实数 $x，y$ 满足 $\sqrt{2x+2}+\sqrt{2y+3}=4$ ，则 $x+y$  的最小值 $(\qquad)$ 

提示：

**方法 **$1.$ 因为实数 $x，y$ 满足 $\sqrt{2x+2}+\sqrt{2y+3}=4$，由柯西不等式可得： $(2 x+1+2 y+3)(1+1) \geqslant(\sqrt{2 x+1} \times 1+\sqrt{2 y+3} \times 1)^2\\$ 即： $4x+4y+8\geq16$ ，求得 $x+y\geq 2$ ，当且仅当 $\sqrt{2 x+1}=\sqrt{2y+3}=2$ 时取等号，故 $x+y$  的最小值是 $2$ 

**方法 **$2.$ $\sqrt{2 x+1}+\sqrt{2 y+3}=4$ ，令  $\sqrt{2 x+1}=a$ ， $\sqrt{2 y+3}=b$ , 

则 $x=\dfrac{a^2-1}{8}$ , $y=\dfrac{b^2-3}{2}$ ,

题目转换为： $a+b=4$ ，求 $\dfrac{a^2-1}{2}+\dfrac{b^2-3}{2}=\dfrac{1}{2}\left(a^2+b^2\right)-2$ 的最小值。

$\dfrac{a^2-1}{2}+\dfrac{b^2-3}{2}=\dfrac{1}{2}\left(a^2+b^2\right)-2=\dfrac{(a+b)^2-2 a b}{2}-2\\=\dfrac{16-2 a b}{2}-2=6-a b \leqslant 6-\left(\dfrac{a+b}{2}\right)^2=2$ 


---


例 $11.$   函数 $y=5 \sqrt{2 x-1}+\sqrt{10-2 x}$ 的最大值为 $(\qquad)$ , 此时 $x=(\qquad)$ 

**提示：** 由柯西不等式 $\left[5^2+1^2\right]\left[(\sqrt{2 x-1})^2+(\sqrt{10-2 x})^2\right] \geqslant(5 \sqrt{2 x-1}+1 \times \sqrt{10-2 x})^2$ 

$\therefore(5 \sqrt{2 x-1}+\sqrt{10-2 x})^2 \leqslant 26 \times 9$ 

$\therefore 5 \sqrt{2 x-1}+\sqrt{10-2 x} \leqslant 3 \sqrt{26}$ , 当且仅当 $5 \sqrt{10-2 x}=1 \times \sqrt{2 x-1}$ 时, 取等号，即  $x=\dfrac{251}{52}$ .


---


例 $12.$ 若 $a, b \in \mathbf{R}，$ 且 $a+b=1$ ，用柯西不等式求 $\sqrt{3 a+1}+\sqrt{3 b+1}$ 的最大值 $(\qquad)$ 

提示：由柯西不等式可得： $(1^2+1^2)[(\sqrt{3a+1})^2+(\sqrt{3b+1})^2]\geq(\sqrt{3a+1}+\sqrt{3b+1})^2$ 

$\because a+b=1, \therefore(\sqrt{3 a+1}+\sqrt{3 b+1})^2 \leqslant 10, \therefore \sqrt{3 a+1}+\sqrt{3 b+1}$ 的最大值为 $\sqrt{10}$  .


---


例 $13.$ ( $2019 \cdot$ 全国卷Ⅲ)

设 $x, y, z \in \mathbf{R}$ , 且 $x+y+z=1$ .

$(1)$ 求 $(x-1)^2+(y+1)^2+(z+1)^2$ 的最小值；

$(2)$  若 $(x-2)^2+(y-1)^2+(z-a)^2 \geqslant \dfrac{1}{3}$ 成立，证明： $a \leqslant-3$  或 $a \geqslant-1$ .

解：  $(1)$ $x, y, z \in \mathbf{R}$ , 且 $x+y+z=1$ ,

由柯西不等式可得 ：

$\left(1^2+1^2+1^2\right)\left[(x-1)^2+(y+1)^2+(z+1)^2\right] \geqslant(x-1+y+1+z+1)^2=4$ ,

可得 $(x-1)^2+(y+1)^2+(z+1)^2 \geqslant \dfrac{4}{3}$ ， 即有 $(x-1)^2+(y+1)^2+(z+1)^2$ 的最小值为 $\dfrac{4}{3}$ .

$(2)$ 证明：由 $x+y+z=1$ , 柯西不等式可得

$\left(1^2+1^2+1^2\right)\left[(x-2)^2+(y-1)^2+(z-a)^2\right] \geqslant(x-2+y-1+z-a)^2=(a+2)^2 \text {, }$ 

可得 $(x-2)^2+(y-1)^2+(z-a)^2 \geqslant \dfrac{(a+2)^2}{3}$ ,

即有 $(x-2)^2+(y-1)^2+(z-a)^2$ 的最小值为 $\dfrac{(a+2)^2}{3}$ ,

由题意可得 $\dfrac{(a+2)^2}{3} \geqslant \dfrac{1}{3}$ , 解得 $a \geqslant-1$ 或 $a \leqslant-3$  .


---


例 $14.$  已知：$a,b,c\in R^+,a+b+c=1,求(a^2+b^2+2c^2)_{min}$

**提示：**首先，此题是肯定可以用加权均值不等式（也可以理解为调配系数之后的均值不等式）作出来的，方法如下：注意到有：

$$
\frac{a+b+\frac12\times2c}{\frac52}\le\sqrt{\frac{a^2+b^2+\frac12\times(2c)^2}{\frac52}}\\
$$

于是：

$$
a^2+b^2+2c^2\ge\frac52\times\left(\frac{a+b+c}{\frac52}\right)^2=\frac25\\
$$

当然，我们这里还是主要介绍柯西不等式的方法：

由柯西不等式得：

$$
\left(a^2+b^2+\left(\sqrt2c\right)^2\right)\left(1+1+\left(\frac1{\sqrt2}\right)^2\right)\ge(a+b+c)^2=1\\
$$

于是：

$$
a^2+b^2+2c^2\ge\frac52\\
$$


---


例 $15.$ 已知 $a,b,c\in R^+$ , $a+2b+3c=\sqrt{14}$  , $ a^2+b^2+c^2=1$ ,求证： $a+b=c$ 

提示：题目之中只给了两个等式，却有三个字母，左右观察一下，发现要证的式子与前面两式几乎没有联系，所以也不可能利用整体代换。于是只有一种可能：极端情况（即“恰好取等”）。

根据柯西不等式，有：

$$
\left(a^2+b^2+c^2\right)\left(1^2+2^2+3^2\right)\ge\left(a+2b+3c\right)^2\tag1
$$

代入，得：

$$
14\ge14\\
$$

说明 $(1)$ 式恰好取等，即有：

$$
a:b:c=1:2:3\\
$$

解得：

$$
\left\{ \begin{align} &a=\frac{\sqrt{14}}{14}\\ &b=\frac{\sqrt{14}}{7}\\ &c=\frac{3\sqrt{14}}{14}\\ \end{align} \right.\\
$$

于是便有 $a+b=c$ 了。


---


例 $16.$  已知 $a+b+c=1$ ,

$(1)$  求 $\sqrt{2a+1}+\sqrt{2b+1}+\sqrt{2c+1}$ 的最大值 $(\qquad)$ 

$(2)$  求 $\sqrt{2a+1}+\sqrt{2b+1}+\sqrt{3c+1}$ 的最大值 $(\qquad)$ 

**提示：** $(1)$ 直接利用柯西不等式，有：

$$
\begin{aligned}&\left(\sqrt{2a+1}+\sqrt{2b+1}+\sqrt{2c+1}\right)^2\\ & \le\left(1+1+1\right)\left(2a+1+2b+1+2c+1\right)=15\end{aligned}\\
$$

于是：

$$
\sqrt{2a+1}+\sqrt{2b+1}+\sqrt{2c+1}\le\sqrt{15}\\
$$

$(2)$ 根据柯西不等式，有：$\begin{aligned}&(\sqrt{2a+1}+\sqrt{2b+1}+\sqrt{3c+1})^2\\&=\left[\sqrt{2a+1}+\sqrt{2b+1}+\sqrt{\dfrac{3}{2}\cdot(2c+\dfrac{2}{3})}\;\right]^2\\&=\left[\sqrt{2a+1}+\sqrt{2b+1}+\dfrac{\sqrt{6}}{2}\sqrt{\cdot(2c+\dfrac{2}{3})}\;\right]^2\\&\leq(1+1+\dfrac{1}{6})(2a+1+2b+1+2c+\dfrac{2}{3})\\&=\frac{91}{9}\end{aligned}\\$ 于是： $\sqrt{2a+1}+\sqrt{2b+1}+\sqrt{3c+1}\le\dfrac{\sqrt{91}}{3}\\$