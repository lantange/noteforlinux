## 插入数学公式
### 方法1：使用GitHub with MathJax
[参考链接](https://math.meta.stackexchange.com/questions/5020/mathjax-basic-tutorial-and-quick-reference)
1. 行内公式`$x=\frac{-b\pm\sqrt{b^2-4ac}}{2a}$`  
公式$x=\frac{-b\pm\sqrt{b^2-4ac}}{2a}$  
2. 行间公式`$$x=\frac{-b\pm\sqrt{b^2-4ac}}{2a}$$`
$$x=\frac{-b\pm\sqrt{b^2-4ac}}{2a}$$
3. 复杂公式举例  
+ 求和
$$\[J_\alpha(x) = \sum_{m=0}^\infty \frac{(-1)^m}{m! \Gamma (m + \alpha + 1)}\]$$
+ 指数的指数
$$x^{y^z}=(1+{\rm e}^x)^{-2xy^w}$$
+ 似然最大
$$\mathop{argmax}\_{K}$$
+ 求极限
$$\lim_{n \rightarrow +\infty} \frac{1}{n(n+1)}$$
+ 矩阵  
`$$\begin{pmatrix}
	1 & x & x^2 \\\\
	1 & y & y^2 \\\\
	1 & z & z^2 \\\\
\end{pmatrix}$$`
$$\begin{pmatrix}
	1 & x & x^2 \\\\
	1 & y & y^2 \\\\
	1 & z & z^2 \\\\
\end{pmatrix}$$
+ 大括号等式
$$f(x)=\begin{cases}
a_1x+b_1y+c_1z=d_1\\\\
a_2x+b_2y+c_2z=d_2\\\\
a_3x+b_3y+c_3z=d_3
\end{cases}$$
- 大括号等式右边
$$
\left\{\begin{array}{l}
\text{if $n$ is even:}&n/2\\
\text{if $n$ is odd:}&3n+1
\end{array}
\right\}
=f(n)$$
+ 增广矩阵
$$\left\[
\begin{array}{cc|c}
  1&2&3\\\\
  4&5&6
\end{array}
\right\] $$
+ 行内小矩阵  
行内小矩阵$\bigl( \begin{smallmatrix} a & b \\\\ c & d \end{smallmatrix} \bigr)$  
