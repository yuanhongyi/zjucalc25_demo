---
theme: neversink
transition: fade-out
---

# #5 微分中值定理 2

#### Taylor 公式

---


## Taylor

若要证明的式子中含有高阶导数（如$f^{(4)}(\xi)$、$f^{(m)}(\xi)$等），一般要用带拉格朗日余项的泰勒公式：


$$
f(x)=f(x_{0})+f'(x_{0})(x - x_{0})+\dfrac{f^{\prime \prime}(x_{0})}{2!}(x - x_{0})^{2}+\cdots+\dfrac{f^{(n)}(\xi)}{(n)!}(x - x_{0})^{n}
$$
<br>
<v-clicks>

在选取展开点和被展开点时，总的思路是**选取导数值信息多的点作为$x_{0}$(在$x_0$处展开)**。

当然，有时也会有其他展开方式，**如将两端点均在中点处展开、将中点分别在两个端点处展开、在任意点处展开等**，具体情况需具体分析！

</v-clicks>
  
---

#### 例1
设$f(x)$在$[-1,1]$三阶连续可导，$f(-1)=0$，$f'(0)=0$，$f(1)=1$，证：$\exists \xi \in(-1,1)$，s.t.$f^{\prime \prime \prime}(\xi)=3$

<v-clicks>

证明：法1：（泰勒公式）  

$f(1)$，$f(-1)$分别在$0$处展开  

$$f(1)=f(0)+f'(0)+\frac{f''(x)}{2}+\frac{f'''(\xi_1)}{6}$$  

$$f(-1)=f(0)-f'(0)+\frac{f''(x)}{2}-\frac{f'''(\xi_2)}{6}$$  

两式相减得$3 = \dfrac{f'''(\xi_1)+f'''(\xi_2)}{2}$ 

由介值定理得$\exists \xi \in (0,1)$ s.t. $f'''(\xi)=\dfrac{f'''(\xi_1)+f'''(\xi_2)}{2}$，得证  

<AdmonitionType type='tip' >

注1：介值定理小推论：$af(u)+bf(v) = (a+b)f(\eta)$ 

注2：由达布定理可知，这里的“三阶连续可导”可弱化为“三阶可导”，部分题目有类似情况。
</AdmonitionType>

</v-clicks>

---

<AdmonitionType type='important' >
This is important text
</AdmonitionType>


<AdmonitionType type='warning' >
This is a warning
</AdmonitionType>

<AdmonitionType type='caution' >
This is warning text
</AdmonitionType>


