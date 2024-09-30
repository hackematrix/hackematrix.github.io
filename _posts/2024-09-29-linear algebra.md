---
 title: linear algebra
 date: 2024-9-29 23:00:00 +0800
 categories: [Blog, Build]
 tags: [blog,math]
 ---

 
 # 线性代数 Linear algebra
## 第一天
### 消元法：
* 英文名：Gauss elimination
* 方法：保持主元行不为0（Pivots can't be zero），形成三角矩阵，然后回代（substitution）
* 基础知识:<ul>
* 矩阵乘以向量：<ul>
* 1.矩阵乘以行向量：
<br> $$
\left[
\begin{matrix}
a &b &c\\
d &e &f\\
h &i &j
\end{matrix}
\right]
$$
$\left[
\begin{matrix}
m\\
n\\
u
\end{matrix}
\right]$
上式等价为
$m$ $\left[
\begin{matrix}
a \\
d \\
h 
\end{matrix}
\right]$+
$n$ $\left[
\begin{matrix}
b \\
e \\
i 
\end{matrix}
\right]$+$u$ $\left[
\begin{matrix}
c \\
f\\
j 
\end{matrix}
\right]$
* 2.矩阵乘以列向量：
$\left[
\begin{matrix}
m\\
n\\
u
\end{matrix}
\right]$
$\left[
\begin{matrix} 
a &b &c\\
d &e&f\\
h&i&j
\end{matrix}
\right]$    
上式等价为
<br>
$m$ $\left[
\begin{matrix}
a&b&c
\end{matrix}
\right]$+<br>
$n$ $\left[
\begin{matrix}
d&e&f
\end{matrix}
\right]$+<br>
$u$ $\left[
\begin{matrix}
h&i&j
\end{matrix}
\right]$
</ul>

</ul>
  
* 置换(基本知识应用)：
  * 互换行：
$\left[
\begin{matrix}
0&1\\
1&0
\end{matrix}
\right]$ $\left[
\begin{matrix}
a&b\\
c&d
\end{matrix}
\right]$<br>=$\left[
\begin{matrix}
c&d\\
a&b
\end{matrix}
\right]$<ul>
* 互换列：
$\left[
\begin{matrix}
a&b\\
c&d
\end{matrix}
\right]$ $\left[
\begin{matrix}
0&1\\
1&0
\end{matrix}
\right]$<br>=
$\left[
\begin{matrix}
b&a\\
d&c
\end{matrix}
\right]$ </ul>
