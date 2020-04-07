Functions of Several Variables
==============================

Linear operator on finite linear space
--------------------------------------

First the author gives some definitions and properties of Euclidean
space <img src="https://www.zhihu.com/equation?tex=\mathbb{R}^n" alt="\mathbb{R}^n" class="ee_img tr_noresize" eeimg="1">. These are just reviews of linear algebra so we do
not repeat here. Then we talk about linear operator in
<img src="https://www.zhihu.com/equation?tex=L(\mathbb{R}^n,\mathbb{R}^m)" alt="L(\mathbb{R}^n,\mathbb{R}^m)" class="ee_img tr_noresize" eeimg="1">. We define the norm of
<img src="https://www.zhihu.com/equation?tex=A\in L(\mathbb{R}^n,\mathbb{R}^m)" alt="A\in L(\mathbb{R}^n,\mathbb{R}^m)" class="ee_img tr_noresize" eeimg="1"> as:

<img src="https://www.zhihu.com/equation?tex=\lVert A\rVert=\sup_{\left\lvert x\right\rvert\leq 1}\left\lvert Ax\right\rvert\\" alt="\lVert A\rVert=\sup_{\left\lvert x\right\rvert\leq 1}\left\lvert Ax\right\rvert\\" class="ee_img tr_noresize" eeimg="1">


By norm of linear operator, we give a important character of invertible
linear operator in <img src="https://www.zhihu.com/equation?tex=\mathbb{R}^n" alt="\mathbb{R}^n" class="ee_img tr_noresize" eeimg="1">.

Let <img src="https://www.zhihu.com/equation?tex=\Omega" alt="\Omega" class="ee_img tr_noresize" eeimg="1"> be the set of all invertible linear operators on
<img src="https://www.zhihu.com/equation?tex=\mathbb{R}^n" alt="\mathbb{R}^n" class="ee_img tr_noresize" eeimg="1">.

1.  If <img src="https://www.zhihu.com/equation?tex=A\in\Omega" alt="A\in\Omega" class="ee_img tr_noresize" eeimg="1">, <img src="https://www.zhihu.com/equation?tex=B\in L(\mathbb{R}^n)" alt="B\in L(\mathbb{R}^n)" class="ee_img tr_noresize" eeimg="1">, and
    <img src="https://www.zhihu.com/equation?tex=\lVert B-A\rVert\lVert A^{-1}\rVert<1" alt="\lVert B-A\rVert\lVert A^{-1}\rVert<1" class="ee_img tr_noresize" eeimg="1">, then <img src="https://www.zhihu.com/equation?tex=B\in\Omega" alt="B\in\Omega" class="ee_img tr_noresize" eeimg="1">.

2.  <img src="https://www.zhihu.com/equation?tex=\Omega" alt="\Omega" class="ee_img tr_noresize" eeimg="1"> is open and the mapping <img src="https://www.zhihu.com/equation?tex=A\mapsto A^{-1}" alt="A\mapsto A^{-1}" class="ee_img tr_noresize" eeimg="1"> is a
    homeomorphism on <img src="https://www.zhihu.com/equation?tex=\Omega" alt="\Omega" class="ee_img tr_noresize" eeimg="1">.

This theorem can be easily extend to the space bounded linear operator
on a Banach space <img src="https://www.zhihu.com/equation?tex=B(E)" alt="B(E)" class="ee_img tr_noresize" eeimg="1">:

Given a Banach space <img src="https://www.zhihu.com/equation?tex=E" alt="E" class="ee_img tr_noresize" eeimg="1">, Let <img src="https://www.zhihu.com/equation?tex=B(E)" alt="B(E)" class="ee_img tr_noresize" eeimg="1"> be the space bounded linear
operator on <img src="https://www.zhihu.com/equation?tex=E" alt="E" class="ee_img tr_noresize" eeimg="1"> and the <img src="https://www.zhihu.com/equation?tex=GL(E)" alt="GL(E)" class="ee_img tr_noresize" eeimg="1"> be the set of all invertible linear
operators on <img src="https://www.zhihu.com/equation?tex=E" alt="E" class="ee_img tr_noresize" eeimg="1">.

1.  If <img src="https://www.zhihu.com/equation?tex=A\in GL(E)" alt="A\in GL(E)" class="ee_img tr_noresize" eeimg="1">, <img src="https://www.zhihu.com/equation?tex=B\in B(E)" alt="B\in B(E)" class="ee_img tr_noresize" eeimg="1">, and
    <img src="https://www.zhihu.com/equation?tex=\lVert B-A\rVert\lVert A^{-1}\rVert<1" alt="\lVert B-A\rVert\lVert A^{-1}\rVert<1" class="ee_img tr_noresize" eeimg="1">, then <img src="https://www.zhihu.com/equation?tex=B\in GL(E)" alt="B\in GL(E)" class="ee_img tr_noresize" eeimg="1">.

2.  <img src="https://www.zhihu.com/equation?tex=GL(E)" alt="GL(E)" class="ee_img tr_noresize" eeimg="1"> is open and the mapping <img src="https://www.zhihu.com/equation?tex=A\mapsto A^{-1}" alt="A\mapsto A^{-1}" class="ee_img tr_noresize" eeimg="1"> is a homeomorphism
    on <img src="https://www.zhihu.com/equation?tex=GL(E)" alt="GL(E)" class="ee_img tr_noresize" eeimg="1">.

There are two varieties of the first statement:

1.  Given <img src="https://www.zhihu.com/equation?tex=A\in GL(E)" alt="A\in GL(E)" class="ee_img tr_noresize" eeimg="1">, <img src="https://www.zhihu.com/equation?tex=B\in B(E)" alt="B\in B(E)" class="ee_img tr_noresize" eeimg="1">, if <img src="https://www.zhihu.com/equation?tex=\lVert A^{-1}B-I\rVert<1" alt="\lVert A^{-1}B-I\rVert<1" class="ee_img tr_noresize" eeimg="1"> then
    <img src="https://www.zhihu.com/equation?tex=B" alt="B" class="ee_img tr_noresize" eeimg="1"> has left inverse.

2.  Given <img src="https://www.zhihu.com/equation?tex=A\in GL(E)" alt="A\in GL(E)" class="ee_img tr_noresize" eeimg="1">, if <img src="https://www.zhihu.com/equation?tex=\lVert A\rVert<1" alt="\lVert A\rVert<1" class="ee_img tr_noresize" eeimg="1">, then <img src="https://www.zhihu.com/equation?tex=I-A\in GL(E)" alt="I-A\in GL(E)" class="ee_img tr_noresize" eeimg="1">.

To prove the above two statements, we use power series.

Using Schwarz inequality we can show:

<img src="https://www.zhihu.com/equation?tex=\lVert A\rVert\leq (\sum_{i,j}a_{i,j}^2)^{\frac{1}{2}}.\\" alt="\lVert A\rVert\leq (\sum_{i,j}a_{i,j}^2)^{\frac{1}{2}}.\\" class="ee_img tr_noresize" eeimg="1">

 Replace <img src="https://www.zhihu.com/equation?tex=A" alt="A" class="ee_img tr_noresize" eeimg="1">
by <img src="https://www.zhihu.com/equation?tex=B-A" alt="B-A" class="ee_img tr_noresize" eeimg="1"> and <img src="https://www.zhihu.com/equation?tex=a_{i,j}" alt="a_{i,j}" class="ee_img tr_noresize" eeimg="1"> by continuous functions <img src="https://www.zhihu.com/equation?tex=a_{i,j}(p)" alt="a_{i,j}(p)" class="ee_img tr_noresize" eeimg="1"> we can see
mapping <img src="https://www.zhihu.com/equation?tex=p\mapsto A_p" alt="p\mapsto A_p" class="ee_img tr_noresize" eeimg="1"> is a continuous mapping.

Differentiation
---------------

Let <img src="https://www.zhihu.com/equation?tex=\mathbf{f}" alt="\mathbf{f}" class="ee_img tr_noresize" eeimg="1"> be a mapping from an open set <img src="https://www.zhihu.com/equation?tex=E" alt="E" class="ee_img tr_noresize" eeimg="1"> in <img src="https://www.zhihu.com/equation?tex=\mathbb{R}^n" alt="\mathbb{R}^n" class="ee_img tr_noresize" eeimg="1">
into <img src="https://www.zhihu.com/equation?tex=\mathbb{R}^m" alt="\mathbb{R}^m" class="ee_img tr_noresize" eeimg="1">. First we talk about the differential of
<img src="https://www.zhihu.com/equation?tex=\mathbf{f}" alt="\mathbf{f}" class="ee_img tr_noresize" eeimg="1"> or total derivative of <img src="https://www.zhihu.com/equation?tex=\mathbf{f}" alt="\mathbf{f}" class="ee_img tr_noresize" eeimg="1"> at <img src="https://www.zhihu.com/equation?tex=x" alt="x" class="ee_img tr_noresize" eeimg="1">. We write
<img src="https://www.zhihu.com/equation?tex=\mathbf{f}'(x)=A" alt="\mathbf{f}'(x)=A" class="ee_img tr_noresize" eeimg="1"> where <img src="https://www.zhihu.com/equation?tex=A" alt="A" class="ee_img tr_noresize" eeimg="1"> is a linear transformation from
<img src="https://www.zhihu.com/equation?tex=\mathbb{R}^n" alt="\mathbb{R}^n" class="ee_img tr_noresize" eeimg="1"> into <img src="https://www.zhihu.com/equation?tex=\mathbb{R}^m" alt="\mathbb{R}^m" class="ee_img tr_noresize" eeimg="1"> which satisfies:

<img src="https://www.zhihu.com/equation?tex=\lim_{\mathbf{h}\to 0}\frac{\left\lvert\mathbf{f}(\mathbf{x}+\mathbf{h})-\mathbf{f}(\mathbf{x})-A\mathbf{h}\right\rvert}{\left\lvert\mathbf{h}\right\rvert}=0\\" alt="\lim_{\mathbf{h}\to 0}\frac{\left\lvert\mathbf{f}(\mathbf{x}+\mathbf{h})-\mathbf{f}(\mathbf{x})-A\mathbf{h}\right\rvert}{\left\lvert\mathbf{h}\right\rvert}=0\\" class="ee_img tr_noresize" eeimg="1">


An useful equivalent definition of <img src="https://www.zhihu.com/equation?tex=\mathbf{f}'(x)" alt="\mathbf{f}'(x)" class="ee_img tr_noresize" eeimg="1"> is

<img src="https://www.zhihu.com/equation?tex=\mathbf{f}(\mathbf{x}+\mathbf{h})-\mathbf{f}(\mathbf{x})=\mathbf{f}'(\mathbf{x})\mathbf{h}+\mathbf{r}(\mathbf{h})\\" alt="\mathbf{f}(\mathbf{x}+\mathbf{h})-\mathbf{f}(\mathbf{x})=\mathbf{f}'(\mathbf{x})\mathbf{h}+\mathbf{r}(\mathbf{h})\\" class="ee_img tr_noresize" eeimg="1">


where <img src="https://www.zhihu.com/equation?tex=\mathbf{r}(\mathbf{h})" alt="\mathbf{r}(\mathbf{h})" class="ee_img tr_noresize" eeimg="1"> satisfies
<img src="https://www.zhihu.com/equation?tex=\lim_{\mathbf{h}\to 0}\frac{\left\lvert\mathbf{r}(\mathbf{h})\right\rvert}{\left\lvert\mathbf{h}\right\rvert}=0" alt="\lim_{\mathbf{h}\to 0}\frac{\left\lvert\mathbf{r}(\mathbf{h})\right\rvert}{\left\lvert\mathbf{h}\right\rvert}=0" class="ee_img tr_noresize" eeimg="1">.
Or
<img src="https://www.zhihu.com/equation?tex=\left\lvert\mathbf{r}(\mathbf{h})\right\rvert=\mathbf{\epsilon}(\mathbf{h})\left\lvert\mathbf{h}\right\rvert" alt="\left\lvert\mathbf{r}(\mathbf{h})\right\rvert=\mathbf{\epsilon}(\mathbf{h})\left\lvert\mathbf{h}\right\rvert" class="ee_img tr_noresize" eeimg="1">
where <img src="https://www.zhihu.com/equation?tex=\mathbf{\epsilon}(\mathbf{h})\to 0" alt="\mathbf{\epsilon}(\mathbf{h})\to 0" class="ee_img tr_noresize" eeimg="1"> as <img src="https://www.zhihu.com/equation?tex=\mathbf{h}\to 0" alt="\mathbf{h}\to 0" class="ee_img tr_noresize" eeimg="1">. In
other words, *continuously differentiable transformation behave locally
very much like their derivatives*.

For fixed <img src="https://www.zhihu.com/equation?tex=x" alt="x" class="ee_img tr_noresize" eeimg="1">, <img src="https://www.zhihu.com/equation?tex=\mathbf{f}'(x)" alt="\mathbf{f}'(x)" class="ee_img tr_noresize" eeimg="1"> is a linear transformation in
<img src="https://www.zhihu.com/equation?tex=L(\mathbb{R}^n,\mathbb{R}^m)" alt="L(\mathbb{R}^n,\mathbb{R}^m)" class="ee_img tr_noresize" eeimg="1">. <img src="https://www.zhihu.com/equation?tex=\mathbf{f}'" alt="\mathbf{f}'" class="ee_img tr_noresize" eeimg="1"> is a function from <img src="https://www.zhihu.com/equation?tex=E" alt="E" class="ee_img tr_noresize" eeimg="1">
into <img src="https://www.zhihu.com/equation?tex=L(\mathbb{R}^n,\mathbb{R}^m)" alt="L(\mathbb{R}^n,\mathbb{R}^m)" class="ee_img tr_noresize" eeimg="1">.

If <img src="https://www.zhihu.com/equation?tex=A\in L(\mathbb{R}^n,\mathbb{R}^m)" alt="A\in L(\mathbb{R}^n,\mathbb{R}^m)" class="ee_img tr_noresize" eeimg="1"> and <img src="https://www.zhihu.com/equation?tex=x\in \mathbb{R}^n" alt="x\in \mathbb{R}^n" class="ee_img tr_noresize" eeimg="1"> and we
define <img src="https://www.zhihu.com/equation?tex=A(x)=Ax" alt="A(x)=Ax" class="ee_img tr_noresize" eeimg="1">, then <img src="https://www.zhihu.com/equation?tex=A'(x)=A" alt="A'(x)=A" class="ee_img tr_noresize" eeimg="1">.

Another type of derivative for
<img src="https://www.zhihu.com/equation?tex=\mathbf{f}(x)=(f_1(x),f_2(x),\dots,f_m(x))" alt="\mathbf{f}(x)=(f_1(x),f_2(x),\dots,f_m(x))" class="ee_img tr_noresize" eeimg="1"> is partial derivative:

<img src="https://www.zhihu.com/equation?tex=\frac{\partial f_i}{\partial x_j}(x)=\lim_{t\to 0}\frac{f_i(x+te_j)-f_i(x)}{t}\\" alt="\frac{\partial f_i}{\partial x_j}(x)=\lim_{t\to 0}\frac{f_i(x+te_j)-f_i(x)}{t}\\" class="ee_img tr_noresize" eeimg="1">


Notice even if partial derivatives exist at a <img src="https://www.zhihu.com/equation?tex=x" alt="x" class="ee_img tr_noresize" eeimg="1">, <img src="https://www.zhihu.com/equation?tex=\mathbf{f}(x)" alt="\mathbf{f}(x)" class="ee_img tr_noresize" eeimg="1"> may
not continuous at <img src="https://www.zhihu.com/equation?tex=x" alt="x" class="ee_img tr_noresize" eeimg="1">. Even if <img src="https://www.zhihu.com/equation?tex=\mathbf{f}(x)" alt="\mathbf{f}(x)" class="ee_img tr_noresize" eeimg="1"> is continuous at <img src="https://www.zhihu.com/equation?tex=x" alt="x" class="ee_img tr_noresize" eeimg="1"> and
partial derivatives exist at <img src="https://www.zhihu.com/equation?tex=x" alt="x" class="ee_img tr_noresize" eeimg="1">, <img src="https://www.zhihu.com/equation?tex=\mathbf{f}'(x)" alt="\mathbf{f}'(x)" class="ee_img tr_noresize" eeimg="1"> may not exist.
However, if <img src="https://www.zhihu.com/equation?tex=\mathbf{f}'(x)" alt="\mathbf{f}'(x)" class="ee_img tr_noresize" eeimg="1"> exists, then partial derivatives exist at
<img src="https://www.zhihu.com/equation?tex=x" alt="x" class="ee_img tr_noresize" eeimg="1"> and: 
<img src="https://www.zhihu.com/equation?tex=\mathbf{f}'(x)=
\begin{bmatrix}     
    \frac{\partial f_1}{\partial x_1}(x)&\dots&\frac{\partial f_1}{\partial x_n}(x)\\
    \dots&\dots&\dots\\
    \frac{\partial f_m}{\partial x_1}(x)&\dots&\frac{\partial f_m}{\partial x_n}(x)
\end{bmatrix}\\" alt="\mathbf{f}'(x)=
\begin{bmatrix}     
    \frac{\partial f_1}{\partial x_1}(x)&\dots&\frac{\partial f_1}{\partial x_n}(x)\\
    \dots&\dots&\dots\\
    \frac{\partial f_m}{\partial x_1}(x)&\dots&\frac{\partial f_m}{\partial x_n}(x)
\end{bmatrix}\\" class="ee_img tr_noresize" eeimg="1">



Given a mapping <img src="https://www.zhihu.com/equation?tex=f" alt="f" class="ee_img tr_noresize" eeimg="1"> from an open set <img src="https://www.zhihu.com/equation?tex=E" alt="E" class="ee_img tr_noresize" eeimg="1"> in <img src="https://www.zhihu.com/equation?tex=\mathbb{R}^n" alt="\mathbb{R}^n" class="ee_img tr_noresize" eeimg="1"> into
<img src="https://www.zhihu.com/equation?tex=\mathbb{R}" alt="\mathbb{R}" class="ee_img tr_noresize" eeimg="1">. There is also a type of derivative called directional
derivative, defined as:

<img src="https://www.zhihu.com/equation?tex=\lim_{t\to 0}\frac{f(\mathbf{x}+t\mathbf{u})-f(\mathbf{x})}{t}=(\nabla f)(\mathbf{x})\cdot \mathbf{u}\\" alt="\lim_{t\to 0}\frac{f(\mathbf{x}+t\mathbf{u})-f(\mathbf{x})}{t}=(\nabla f)(\mathbf{x})\cdot \mathbf{u}\\" class="ee_img tr_noresize" eeimg="1">



Given differentiable <img src="https://www.zhihu.com/equation?tex=\mathbf{f}" alt="\mathbf{f}" class="ee_img tr_noresize" eeimg="1"> which maps a *convex* open set <img src="https://www.zhihu.com/equation?tex=E" alt="E" class="ee_img tr_noresize" eeimg="1"> in
<img src="https://www.zhihu.com/equation?tex=\mathbb{R}^n" alt="\mathbb{R}^n" class="ee_img tr_noresize" eeimg="1"> in to <img src="https://www.zhihu.com/equation?tex=\mathbb{R}^m" alt="\mathbb{R}^m" class="ee_img tr_noresize" eeimg="1">, there is a mean value inequality:

<img src="https://www.zhihu.com/equation?tex=\left\lvert\mathbf{f}(\mathbf{b})-\mathbf{f}(\mathbf{a})\right\rvert\leq \lVert\mathbf{f}'\rVert\left\lvert\mathbf{b}-\mathbf{a}\right\rvert\\" alt="\left\lvert\mathbf{f}(\mathbf{b})-\mathbf{f}(\mathbf{a})\right\rvert\leq \lVert\mathbf{f}'\rVert\left\lvert\mathbf{b}-\mathbf{a}\right\rvert\\" class="ee_img tr_noresize" eeimg="1">



The inverse function theorem and the implicit function theorem
--------------------------------------------------------------

Before we talk about the inverse function theorem and the implicit
function theorem, we give a fixed point theorem which is useful in proof
of the inverse function theorem:

If <img src="https://www.zhihu.com/equation?tex=X" alt="X" class="ee_img tr_noresize" eeimg="1"> is complete metric space with metric <img src="https://www.zhihu.com/equation?tex=d" alt="d" class="ee_img tr_noresize" eeimg="1"> and <img src="https://www.zhihu.com/equation?tex=\phi" alt="\phi" class="ee_img tr_noresize" eeimg="1"> satisfies
<img src="https://www.zhihu.com/equation?tex=d(\phi(x),\phi(y))\leq cd(x,y)" alt="d(\phi(x),\phi(y))\leq cd(x,y)" class="ee_img tr_noresize" eeimg="1"> where <img src="https://www.zhihu.com/equation?tex=c<1" alt="c<1" class="ee_img tr_noresize" eeimg="1">, then there exists one and
only one <img src="https://www.zhihu.com/equation?tex=x" alt="x" class="ee_img tr_noresize" eeimg="1"> such that <img src="https://www.zhihu.com/equation?tex=\phi(x)=x" alt="\phi(x)=x" class="ee_img tr_noresize" eeimg="1">.

Now we give the inverse function theorem:

Suppose <img src="https://www.zhihu.com/equation?tex=\mathbf{f}" alt="\mathbf{f}" class="ee_img tr_noresize" eeimg="1"> is a <img src="https://www.zhihu.com/equation?tex=C^1" alt="C^1" class="ee_img tr_noresize" eeimg="1"> mapping of an open set
<img src="https://www.zhihu.com/equation?tex=E\subset \mathbb{R}^n" alt="E\subset \mathbb{R}^n" class="ee_img tr_noresize" eeimg="1"> into <img src="https://www.zhihu.com/equation?tex=\mathbb{R}^n" alt="\mathbb{R}^n" class="ee_img tr_noresize" eeimg="1"> and <img src="https://www.zhihu.com/equation?tex=\mathbf{f}'(a)" alt="\mathbf{f}'(a)" class="ee_img tr_noresize" eeimg="1"> is
invertible at some point <img src="https://www.zhihu.com/equation?tex=a" alt="a" class="ee_img tr_noresize" eeimg="1">.. Then there exists an open set <img src="https://www.zhihu.com/equation?tex=U" alt="U" class="ee_img tr_noresize" eeimg="1"> and <img src="https://www.zhihu.com/equation?tex=V" alt="V" class="ee_img tr_noresize" eeimg="1">
s.t. <img src="https://www.zhihu.com/equation?tex=a\in U" alt="a\in U" class="ee_img tr_noresize" eeimg="1"> <img src="https://www.zhihu.com/equation?tex=f(a)\in V" alt="f(a)\in V" class="ee_img tr_noresize" eeimg="1">, and <img src="https://www.zhihu.com/equation?tex=\mathbf{f}" alt="\mathbf{f}" class="ee_img tr_noresize" eeimg="1"> is a homeomorphism from <img src="https://www.zhihu.com/equation?tex=U" alt="U" class="ee_img tr_noresize" eeimg="1">
to <img src="https://www.zhihu.com/equation?tex=V" alt="V" class="ee_img tr_noresize" eeimg="1">. Also, the inverse of <img src="https://www.zhihu.com/equation?tex=\mathbf{f}" alt="\mathbf{f}" class="ee_img tr_noresize" eeimg="1"> is also in <img src="https://www.zhihu.com/equation?tex=C^1" alt="C^1" class="ee_img tr_noresize" eeimg="1">.

The key idea in this proof is constructing function
<img src="https://www.zhihu.com/equation?tex=\phi(x)=x+A^{-1}(y-f(x))" alt="\phi(x)=x+A^{-1}(y-f(x))" class="ee_img tr_noresize" eeimg="1"> and showing <img src="https://www.zhihu.com/equation?tex=\phi(x)" alt="\phi(x)" class="ee_img tr_noresize" eeimg="1"> has a fixed point in an
open set <img src="https://www.zhihu.com/equation?tex=U" alt="U" class="ee_img tr_noresize" eeimg="1">. One interesting corollary of above theorem is that if
<img src="https://www.zhihu.com/equation?tex=\mathbf{f}'(x)" alt="\mathbf{f}'(x)" class="ee_img tr_noresize" eeimg="1"> is invertible at <img src="https://www.zhihu.com/equation?tex=x" alt="x" class="ee_img tr_noresize" eeimg="1"> in open set <img src="https://www.zhihu.com/equation?tex=E" alt="E" class="ee_img tr_noresize" eeimg="1">, then <img src="https://www.zhihu.com/equation?tex=\mathbf{f}" alt="\mathbf{f}" class="ee_img tr_noresize" eeimg="1">
is an open mapping of <img src="https://www.zhihu.com/equation?tex=E" alt="E" class="ee_img tr_noresize" eeimg="1"> to <img src="https://www.zhihu.com/equation?tex=\mathbb{R}^n" alt="\mathbb{R}^n" class="ee_img tr_noresize" eeimg="1">.

Let <img src="https://www.zhihu.com/equation?tex=x\in \mathbb{R}^n" alt="x\in \mathbb{R}^n" class="ee_img tr_noresize" eeimg="1"> and <img src="https://www.zhihu.com/equation?tex=y\in \mathbb{R}^m" alt="y\in \mathbb{R}^m" class="ee_img tr_noresize" eeimg="1">. Given
<img src="https://www.zhihu.com/equation?tex=A\in L(\mathbb{R}^{n+m},\mathbb{R}^n)" alt="A\in L(\mathbb{R}^{n+m},\mathbb{R}^n)" class="ee_img tr_noresize" eeimg="1">, we define:

<img src="https://www.zhihu.com/equation?tex=A_xh=A(h,0),\quad A_yk=A(0,k),\quad A(h,k)=A_xh+A_yk\\" alt="A_xh=A(h,0),\quad A_yk=A(0,k),\quad A(h,k)=A_xh+A_yk\\" class="ee_img tr_noresize" eeimg="1">

 where
<img src="https://www.zhihu.com/equation?tex=h\in \mathbb{R}^n" alt="h\in \mathbb{R}^n" class="ee_img tr_noresize" eeimg="1"> and <img src="https://www.zhihu.com/equation?tex=k\in \mathbb{R}^m" alt="k\in \mathbb{R}^m" class="ee_img tr_noresize" eeimg="1">.

The implicit function theorem is:

Let <img src="https://www.zhihu.com/equation?tex=\mathbf{f}" alt="\mathbf{f}" class="ee_img tr_noresize" eeimg="1"> be a <img src="https://www.zhihu.com/equation?tex=C^1" alt="C^1" class="ee_img tr_noresize" eeimg="1"> mapping of an open set
<img src="https://www.zhihu.com/equation?tex=E\subset \mathbb{R}^{n+m}" alt="E\subset \mathbb{R}^{n+m}" class="ee_img tr_noresize" eeimg="1"> into <img src="https://www.zhihu.com/equation?tex=\mathbb{R}^n" alt="\mathbb{R}^n" class="ee_img tr_noresize" eeimg="1">, s.t.
<img src="https://www.zhihu.com/equation?tex=\mathbf{f}(a,b)=0" alt="\mathbf{f}(a,b)=0" class="ee_img tr_noresize" eeimg="1"> for some point <img src="https://www.zhihu.com/equation?tex=(a,b)\in E" alt="(a,b)\in E" class="ee_img tr_noresize" eeimg="1">. Let
<img src="https://www.zhihu.com/equation?tex=A=\mathbf{f}'(a,b)" alt="A=\mathbf{f}'(a,b)" class="ee_img tr_noresize" eeimg="1"> and assume <img src="https://www.zhihu.com/equation?tex=A_x" alt="A_x" class="ee_img tr_noresize" eeimg="1"> is invertible. Then:

There exists open sets <img src="https://www.zhihu.com/equation?tex=U\subset \mathbb{R}^{n+m}" alt="U\subset \mathbb{R}^{n+m}" class="ee_img tr_noresize" eeimg="1"> and
<img src="https://www.zhihu.com/equation?tex=W\subset \mathbb{R}^m" alt="W\subset \mathbb{R}^m" class="ee_img tr_noresize" eeimg="1">, with <img src="https://www.zhihu.com/equation?tex=(a,b)\in U" alt="(a,b)\in U" class="ee_img tr_noresize" eeimg="1"> and <img src="https://www.zhihu.com/equation?tex=b\in W" alt="b\in W" class="ee_img tr_noresize" eeimg="1">, having the
following property:

1.  To every <img src="https://www.zhihu.com/equation?tex=y\in W" alt="y\in W" class="ee_img tr_noresize" eeimg="1"> there is a unique <img src="https://www.zhihu.com/equation?tex=x" alt="x" class="ee_img tr_noresize" eeimg="1"> such that <img src="https://www.zhihu.com/equation?tex=(x,y)\in U" alt="(x,y)\in U" class="ee_img tr_noresize" eeimg="1"> and
    <img src="https://www.zhihu.com/equation?tex=\mathbf{f}(x,y)=0" alt="\mathbf{f}(x,y)=0" class="ee_img tr_noresize" eeimg="1">.

2.  If this <img src="https://www.zhihu.com/equation?tex=x" alt="x" class="ee_img tr_noresize" eeimg="1"> is defined to be <img src="https://www.zhihu.com/equation?tex=g(y)" alt="g(y)" class="ee_img tr_noresize" eeimg="1">, then <img src="https://www.zhihu.com/equation?tex=g" alt="g" class="ee_img tr_noresize" eeimg="1"> is a <img src="https://www.zhihu.com/equation?tex=C^1" alt="C^1" class="ee_img tr_noresize" eeimg="1"> mapping of
    <img src="https://www.zhihu.com/equation?tex=W" alt="W" class="ee_img tr_noresize" eeimg="1"> into <img src="https://www.zhihu.com/equation?tex=\mathbb{R}^n" alt="\mathbb{R}^n" class="ee_img tr_noresize" eeimg="1">, <img src="https://www.zhihu.com/equation?tex=g(b)=a" alt="g(b)=a" class="ee_img tr_noresize" eeimg="1"> and <img src="https://www.zhihu.com/equation?tex=f(g(y),y)=0" alt="f(g(y),y)=0" class="ee_img tr_noresize" eeimg="1"> for <img src="https://www.zhihu.com/equation?tex=y\in W" alt="y\in W" class="ee_img tr_noresize" eeimg="1">.

3.  <img src="https://www.zhihu.com/equation?tex=g'(b)=-(A_x)^{-1}A_y" alt="g'(b)=-(A_x)^{-1}A_y" class="ee_img tr_noresize" eeimg="1">.

The first statement claims that for <img src="https://www.zhihu.com/equation?tex=y\in W" alt="y\in W" class="ee_img tr_noresize" eeimg="1">, there is a 'curve'
satisfies <img src="https://www.zhihu.com/equation?tex=f(x,y)=0" alt="f(x,y)=0" class="ee_img tr_noresize" eeimg="1"> for <img src="https://www.zhihu.com/equation?tex=(x,y)\in U" alt="(x,y)\in U" class="ee_img tr_noresize" eeimg="1">. The second and third statements
claim we can have the 'explicit' representation for 'curve' <img src="https://www.zhihu.com/equation?tex=x=g(y)" alt="x=g(y)" class="ee_img tr_noresize" eeimg="1"> and
this curve has derivative at point <img src="https://www.zhihu.com/equation?tex=b" alt="b" class="ee_img tr_noresize" eeimg="1">.

To prove this theorem, we define <img src="https://www.zhihu.com/equation?tex=F(x,y)=(f(x,y),y)" alt="F(x,y)=(f(x,y),y)" class="ee_img tr_noresize" eeimg="1">. Once we show
<img src="https://www.zhihu.com/equation?tex=F(x,y)" alt="F(x,y)" class="ee_img tr_noresize" eeimg="1"> is 1-1 mapping of <img src="https://www.zhihu.com/equation?tex=E" alt="E" class="ee_img tr_noresize" eeimg="1"> into <img src="https://www.zhihu.com/equation?tex=\mathbb{R}^{n+m}" alt="\mathbb{R}^{n+m}" class="ee_img tr_noresize" eeimg="1">, we consider
curve defined the preimage of the 'vertical' line <img src="https://www.zhihu.com/equation?tex=(0,y)" alt="(0,y)" class="ee_img tr_noresize" eeimg="1">. This gives
the <img src="https://www.zhihu.com/equation?tex=x=g(y)" alt="x=g(y)" class="ee_img tr_noresize" eeimg="1"> corresponding to <img src="https://www.zhihu.com/equation?tex=y" alt="y" class="ee_img tr_noresize" eeimg="1"> that makes <img src="https://www.zhihu.com/equation?tex=f(x,y)=0" alt="f(x,y)=0" class="ee_img tr_noresize" eeimg="1">. Since
<img src="https://www.zhihu.com/equation?tex=F(x,y)=F(g(y),y)" alt="F(x,y)=F(g(y),y)" class="ee_img tr_noresize" eeimg="1"> is 1-1 mapping and <img src="https://www.zhihu.com/equation?tex=F'(a,b)" alt="F'(a,b)" class="ee_img tr_noresize" eeimg="1"> is invertible, we
consider the function <img src="https://www.zhihu.com/equation?tex=G" alt="G" class="ee_img tr_noresize" eeimg="1"> which inverts <img src="https://www.zhihu.com/equation?tex=F" alt="F" class="ee_img tr_noresize" eeimg="1">. By inverse function
theorem, <img src="https://www.zhihu.com/equation?tex=G(f(x,y),y)=(x,y)" alt="G(f(x,y),y)=(x,y)" class="ee_img tr_noresize" eeimg="1"> is <img src="https://www.zhihu.com/equation?tex=C^1" alt="C^1" class="ee_img tr_noresize" eeimg="1"> function, which is obvious in
<img src="https://www.zhihu.com/equation?tex=C^1" alt="C^1" class="ee_img tr_noresize" eeimg="1"> on the 'curve' <img src="https://www.zhihu.com/equation?tex=f(x,y)=0" alt="f(x,y)=0" class="ee_img tr_noresize" eeimg="1">. That means <img src="https://www.zhihu.com/equation?tex=G(0,y)=(g(y),y)" alt="G(0,y)=(g(y),y)" class="ee_img tr_noresize" eeimg="1"> is in
<img src="https://www.zhihu.com/equation?tex=C^1" alt="C^1" class="ee_img tr_noresize" eeimg="1"> and the first component is in <img src="https://www.zhihu.com/equation?tex=C^1" alt="C^1" class="ee_img tr_noresize" eeimg="1"> consequently.

The rank theorem
----------------

The inverse function theorem and the implicit function theorem are only
concerned with function <img src="https://www.zhihu.com/equation?tex=f" alt="f" class="ee_img tr_noresize" eeimg="1"> from <img src="https://www.zhihu.com/equation?tex=\mathbb{R}^n" alt="\mathbb{R}^n" class="ee_img tr_noresize" eeimg="1"> to <img src="https://www.zhihu.com/equation?tex=\mathbb{R}^n" alt="\mathbb{R}^n" class="ee_img tr_noresize" eeimg="1"> and
<img src="https://www.zhihu.com/equation?tex=f'(x)" alt="f'(x)" class="ee_img tr_noresize" eeimg="1"> is invertible at some point <img src="https://www.zhihu.com/equation?tex=a" alt="a" class="ee_img tr_noresize" eeimg="1">. A more general theorem is
concerned with function <img src="https://www.zhihu.com/equation?tex=f" alt="f" class="ee_img tr_noresize" eeimg="1"> from <img src="https://www.zhihu.com/equation?tex=\mathbb{R}^n" alt="\mathbb{R}^n" class="ee_img tr_noresize" eeimg="1"> to <img src="https://www.zhihu.com/equation?tex=\mathbb{R}^m" alt="\mathbb{R}^m" class="ee_img tr_noresize" eeimg="1"> and
<img src="https://www.zhihu.com/equation?tex=f'(x)" alt="f'(x)" class="ee_img tr_noresize" eeimg="1"> has only rank r.

Suppose <img src="https://www.zhihu.com/equation?tex=m" alt="m" class="ee_img tr_noresize" eeimg="1">, <img src="https://www.zhihu.com/equation?tex=n" alt="n" class="ee_img tr_noresize" eeimg="1">, <img src="https://www.zhihu.com/equation?tex=r" alt="r" class="ee_img tr_noresize" eeimg="1"> are nonnegative integers, <img src="https://www.zhihu.com/equation?tex=m\geq r" alt="m\geq r" class="ee_img tr_noresize" eeimg="1">, <img src="https://www.zhihu.com/equation?tex=n\geq r" alt="n\geq r" class="ee_img tr_noresize" eeimg="1">,
<img src="https://www.zhihu.com/equation?tex=F" alt="F" class="ee_img tr_noresize" eeimg="1"> is a <img src="https://www.zhihu.com/equation?tex=C^1" alt="C^1" class="ee_img tr_noresize" eeimg="1"> mapping of an open set <img src="https://www.zhihu.com/equation?tex=E\subset \mathbb{R}^n" alt="E\subset \mathbb{R}^n" class="ee_img tr_noresize" eeimg="1"> into
<img src="https://www.zhihu.com/equation?tex=\mathbb{R}^m" alt="\mathbb{R}^m" class="ee_img tr_noresize" eeimg="1">, and <img src="https://www.zhihu.com/equation?tex=F'(x)" alt="F'(x)" class="ee_img tr_noresize" eeimg="1"> has rank <img src="https://www.zhihu.com/equation?tex=r" alt="r" class="ee_img tr_noresize" eeimg="1"> for every <img src="https://www.zhihu.com/equation?tex=x\in E" alt="x\in E" class="ee_img tr_noresize" eeimg="1">.

Fixed <img src="https://www.zhihu.com/equation?tex=a\in E" alt="a\in E" class="ee_img tr_noresize" eeimg="1">, put <img src="https://www.zhihu.com/equation?tex=A=F'(a)" alt="A=F'(a)" class="ee_img tr_noresize" eeimg="1">, let <img src="https://www.zhihu.com/equation?tex=Y_1" alt="Y_1" class="ee_img tr_noresize" eeimg="1"> be subspace <img src="https://www.zhihu.com/equation?tex=A(\mathbb{R}^n)" alt="A(\mathbb{R}^n)" class="ee_img tr_noresize" eeimg="1">
and <img src="https://www.zhihu.com/equation?tex=P" alt="P" class="ee_img tr_noresize" eeimg="1"> is projection in <img src="https://www.zhihu.com/equation?tex=\mathbb{R}^m" alt="\mathbb{R}^m" class="ee_img tr_noresize" eeimg="1"> whose range is <img src="https://www.zhihu.com/equation?tex=Y_1" alt="Y_1" class="ee_img tr_noresize" eeimg="1">. Let <img src="https://www.zhihu.com/equation?tex=Y_2" alt="Y_2" class="ee_img tr_noresize" eeimg="1">
be the null space of <img src="https://www.zhihu.com/equation?tex=P" alt="P" class="ee_img tr_noresize" eeimg="1">.

Then there are open sets <img src="https://www.zhihu.com/equation?tex=U" alt="U" class="ee_img tr_noresize" eeimg="1"> and <img src="https://www.zhihu.com/equation?tex=V" alt="V" class="ee_img tr_noresize" eeimg="1"> in <img src="https://www.zhihu.com/equation?tex=\mathbb{R}^n" alt="\mathbb{R}^n" class="ee_img tr_noresize" eeimg="1">, with <img src="https://www.zhihu.com/equation?tex=a\in U" alt="a\in U" class="ee_img tr_noresize" eeimg="1">,
<img src="https://www.zhihu.com/equation?tex=U\subset E" alt="U\subset E" class="ee_img tr_noresize" eeimg="1">, and there is a 1-1 <img src="https://www.zhihu.com/equation?tex=C^1" alt="C^1" class="ee_img tr_noresize" eeimg="1"> mapping <img src="https://www.zhihu.com/equation?tex=H" alt="H" class="ee_img tr_noresize" eeimg="1"> of <img src="https://www.zhihu.com/equation?tex=V" alt="V" class="ee_img tr_noresize" eeimg="1"> onto <img src="https://www.zhihu.com/equation?tex=U" alt="U" class="ee_img tr_noresize" eeimg="1">
(whose inverse is also in <img src="https://www.zhihu.com/equation?tex=C^1" alt="C^1" class="ee_img tr_noresize" eeimg="1">) such that

<img src="https://www.zhihu.com/equation?tex=F(H(x))=Ax+\phi(Ax)\quad (x\in V)\\" alt="F(H(x))=Ax+\phi(Ax)\quad (x\in V)\\" class="ee_img tr_noresize" eeimg="1">

 where <img src="https://www.zhihu.com/equation?tex=\phi" alt="\phi" class="ee_img tr_noresize" eeimg="1"> is a <img src="https://www.zhihu.com/equation?tex=C^1" alt="C^1" class="ee_img tr_noresize" eeimg="1"> mapping of
the open set <img src="https://www.zhihu.com/equation?tex=A(V)\subset Y_1" alt="A(V)\subset Y_1" class="ee_img tr_noresize" eeimg="1"> into <img src="https://www.zhihu.com/equation?tex=Y_2" alt="Y_2" class="ee_img tr_noresize" eeimg="1">.

This theorem illustrates again the fact that the local behavior of a
continuously differentiable mapping <img src="https://www.zhihu.com/equation?tex=F" alt="F" class="ee_img tr_noresize" eeimg="1"> near a point <img src="https://www.zhihu.com/equation?tex=x" alt="x" class="ee_img tr_noresize" eeimg="1"> is similar to
that of the linear transformation <img src="https://www.zhihu.com/equation?tex=F'(x)" alt="F'(x)" class="ee_img tr_noresize" eeimg="1">. Consider the following
example:

Given a <img src="https://www.zhihu.com/equation?tex=C^1" alt="C^1" class="ee_img tr_noresize" eeimg="1"> mapping <img src="https://www.zhihu.com/equation?tex=F" alt="F" class="ee_img tr_noresize" eeimg="1"> that maps <img src="https://www.zhihu.com/equation?tex=E\subset \mathbb{R}^n" alt="E\subset \mathbb{R}^n" class="ee_img tr_noresize" eeimg="1"> into
<img src="https://www.zhihu.com/equation?tex=\mathbb{R}^n" alt="\mathbb{R}^n" class="ee_img tr_noresize" eeimg="1"> and <img src="https://www.zhihu.com/equation?tex=F'(x)" alt="F'(x)" class="ee_img tr_noresize" eeimg="1"> is invertible for all <img src="https://www.zhihu.com/equation?tex=x\in E" alt="x\in E" class="ee_img tr_noresize" eeimg="1">. choose
<img src="https://www.zhihu.com/equation?tex=a\in E" alt="a\in E" class="ee_img tr_noresize" eeimg="1"> s.t. there is an open ball <img src="https://www.zhihu.com/equation?tex=B(a,h)" alt="B(a,h)" class="ee_img tr_noresize" eeimg="1"> in <img src="https://www.zhihu.com/equation?tex=E" alt="E" class="ee_img tr_noresize" eeimg="1">, we have:

<img src="https://www.zhihu.com/equation?tex=F(a+h)-F(a)=F'(a)h+r(h)\\" alt="F(a+h)-F(a)=F'(a)h+r(h)\\" class="ee_img tr_noresize" eeimg="1">

 Now consider the mapping <img src="https://www.zhihu.com/equation?tex=G" alt="G" class="ee_img tr_noresize" eeimg="1"> inverts <img src="https://www.zhihu.com/equation?tex=F" alt="F" class="ee_img tr_noresize" eeimg="1"> and
an inverse linear transformation <img src="https://www.zhihu.com/equation?tex=T" alt="T" class="ee_img tr_noresize" eeimg="1"> , then:

<img src="https://www.zhihu.com/equation?tex=F(G(T(a+h)))-F(G(T(a)))=Th=F'(a)h+r(h)\\" alt="F(G(T(a+h)))-F(G(T(a)))=Th=F'(a)h+r(h)\\" class="ee_img tr_noresize" eeimg="1">

 Let <img src="https://www.zhihu.com/equation?tex=h\to 0" alt="h\to 0" class="ee_img tr_noresize" eeimg="1">, we see
<img src="https://www.zhihu.com/equation?tex=T\to F'(a)" alt="T\to F'(a)" class="ee_img tr_noresize" eeimg="1">. The mapping <img src="https://www.zhihu.com/equation?tex=H" alt="H" class="ee_img tr_noresize" eeimg="1"> in this example can be considered as
<img src="https://www.zhihu.com/equation?tex=G(F'(a))" alt="G(F'(a))" class="ee_img tr_noresize" eeimg="1">.

So what does the theorem told us? If the range of <img src="https://www.zhihu.com/equation?tex=F'(x)" alt="F'(x)" class="ee_img tr_noresize" eeimg="1"> is
<img src="https://www.zhihu.com/equation?tex=\mathbb{R}^m" alt="\mathbb{R}^m" class="ee_img tr_noresize" eeimg="1">, we can first map <img src="https://www.zhihu.com/equation?tex=x" alt="x" class="ee_img tr_noresize" eeimg="1"> to <img src="https://www.zhihu.com/equation?tex=H(x)" alt="H(x)" class="ee_img tr_noresize" eeimg="1">, then <img src="https://www.zhihu.com/equation?tex=F\circ H" alt="F\circ H" class="ee_img tr_noresize" eeimg="1"> can be
described as linear transform <img src="https://www.zhihu.com/equation?tex=F'(a)" alt="F'(a)" class="ee_img tr_noresize" eeimg="1">. <img src="https://www.zhihu.com/equation?tex=H" alt="H" class="ee_img tr_noresize" eeimg="1"> changes as your chosen <img src="https://www.zhihu.com/equation?tex=a" alt="a" class="ee_img tr_noresize" eeimg="1">
changes. In other words, after a homeomorphism mapping <img src="https://www.zhihu.com/equation?tex=x\to H^{-1}(x)" alt="x\to H^{-1}(x)" class="ee_img tr_noresize" eeimg="1">,
any function <img src="https://www.zhihu.com/equation?tex=F" alt="F" class="ee_img tr_noresize" eeimg="1"> with <img src="https://www.zhihu.com/equation?tex=F'(x)" alt="F'(x)" class="ee_img tr_noresize" eeimg="1"> being surjective can be considered as a
linear mapping locally in <img src="https://www.zhihu.com/equation?tex=H^{-1}(U)" alt="H^{-1}(U)" class="ee_img tr_noresize" eeimg="1">.

Things changes if <img src="https://www.zhihu.com/equation?tex=F'(a)" alt="F'(a)" class="ee_img tr_noresize" eeimg="1"> is not surjective. <img src="https://www.zhihu.com/equation?tex=F'(x)" alt="F'(x)" class="ee_img tr_noresize" eeimg="1"> can not fill the
space <img src="https://www.zhihu.com/equation?tex=\mathbb{R}^m" alt="\mathbb{R}^m" class="ee_img tr_noresize" eeimg="1">, so we fill the rest part by the function <img src="https://www.zhihu.com/equation?tex=\phi" alt="\phi" class="ee_img tr_noresize" eeimg="1">.

Derivatives of higher order and differentiation of Integrals
------------------------------------------------------------

We actually talk about higher order partial derivatives, we have mean
value theorem on second partial derivative:

<img src="https://www.zhihu.com/equation?tex=f(a+h,b+k)-f(a+h,b)-f(a,b+k)+f(a,b)=hk\frac{\partial^2 f}{\partial x_1\partial x_2}(x,y)\\" alt="f(a+h,b+k)-f(a+h,b)-f(a,b+k)+f(a,b)=hk\frac{\partial^2 f}{\partial x_1\partial x_2}(x,y)\\" class="ee_img tr_noresize" eeimg="1">


where <img src="https://www.zhihu.com/equation?tex=(x,y)" alt="(x,y)" class="ee_img tr_noresize" eeimg="1"> is in the interior of rectangle having <img src="https://www.zhihu.com/equation?tex=(a,b)" alt="(a,b)" class="ee_img tr_noresize" eeimg="1"> and
<img src="https://www.zhihu.com/equation?tex=(a+h,b+k)" alt="(a+h,b+k)" class="ee_img tr_noresize" eeimg="1"> as opposite vertices.

The next topic is the problem when the equation

<img src="https://www.zhihu.com/equation?tex=\frac{d}{dt}\int_{a}^{b}\phi(x,t)d\alpha(x)=\int_{a}^{b}\frac{\partial \phi}{\partial t}(x,t)d\alpha(x)\\" alt="\frac{d}{dt}\int_{a}^{b}\phi(x,t)d\alpha(x)=\int_{a}^{b}\frac{\partial \phi}{\partial t}(x,t)d\alpha(x)\\" class="ee_img tr_noresize" eeimg="1">


is true. The sufficient condition is when <img src="https://www.zhihu.com/equation?tex=\phi(x,t)" alt="\phi(x,t)" class="ee_img tr_noresize" eeimg="1"> is in
<img src="https://www.zhihu.com/equation?tex=\mathscr{R}(\alpha)" alt="\mathscr{R}(\alpha)" class="ee_img tr_noresize" eeimg="1"> for all <img src="https://www.zhihu.com/equation?tex=t" alt="t" class="ee_img tr_noresize" eeimg="1"> and <img src="https://www.zhihu.com/equation?tex=\frac{\partial \phi}{\partial t}" alt="\frac{\partial \phi}{\partial t}" class="ee_img tr_noresize" eeimg="1">
is continuous w.r.t <img src="https://www.zhihu.com/equation?tex=t" alt="t" class="ee_img tr_noresize" eeimg="1">.

For Lebesgue integral, we pass the limit in integral sign by dominated
convergence theorem.

Integration of Differential Forms
=================================

This chapter is the hardest part of this book. First we introduce the
integration on n-cell: 
<img src="https://www.zhihu.com/equation?tex=\int_{\mathbb{I}^n}{f(x)dx}\\" alt="\int_{\mathbb{I}^n}{f(x)dx}\\" class="ee_img tr_noresize" eeimg="1">

 This integration
is assigned by integrating in each dimension one by one.

Another tools in integration on higher dimension is change of variables:

<img src="https://www.zhihu.com/equation?tex=\int_{\mathbb{R}^n}{f(y)dy}=\int_{\mathbb{R}^n}{f(T(x))\left\lvert J_T(x)\right\rvert dx}\\" alt="\int_{\mathbb{R}^n}{f(y)dy}=\int_{\mathbb{R}^n}{f(T(x))\left\lvert J_T(x)\right\rvert dx}\\" class="ee_img tr_noresize" eeimg="1">


where <img src="https://www.zhihu.com/equation?tex=T" alt="T" class="ee_img tr_noresize" eeimg="1"> is a 1-1 <img src="https://www.zhihu.com/equation?tex=C^1" alt="C^1" class="ee_img tr_noresize" eeimg="1"> mapping and <img src="https://www.zhihu.com/equation?tex=J_T(x)\neq 0" alt="J_T(x)\neq 0" class="ee_img tr_noresize" eeimg="1"> on support of
<img src="https://www.zhihu.com/equation?tex=f(y)" alt="f(y)" class="ee_img tr_noresize" eeimg="1">.

Differential forms
------------------

There are lots of definitions in topic of differential forms. First we
introduce the k-surface:

Suppose <img src="https://www.zhihu.com/equation?tex=E" alt="E" class="ee_img tr_noresize" eeimg="1"> is an open set in <img src="https://www.zhihu.com/equation?tex=\mathbb{R}^n" alt="\mathbb{R}^n" class="ee_img tr_noresize" eeimg="1">. A k-surface in <img src="https://www.zhihu.com/equation?tex=E" alt="E" class="ee_img tr_noresize" eeimg="1"> is a
<img src="https://www.zhihu.com/equation?tex=C^1" alt="C^1" class="ee_img tr_noresize" eeimg="1"> mapping <img src="https://www.zhihu.com/equation?tex=\Phi" alt="\Phi" class="ee_img tr_noresize" eeimg="1"> from a compact set <img src="https://www.zhihu.com/equation?tex=D\subset \mathbb{R}^k" alt="D\subset \mathbb{R}^k" class="ee_img tr_noresize" eeimg="1"> in to
<img src="https://www.zhihu.com/equation?tex=E" alt="E" class="ee_img tr_noresize" eeimg="1">.

The 'k' indicates the dimension of parameter of <img src="https://www.zhihu.com/equation?tex=\Phi" alt="\Phi" class="ee_img tr_noresize" eeimg="1">. Roughly
speaking, the theory of differential form is the study of integration of
surface. The definition of differential form makes this idea concrete:

Suppose <img src="https://www.zhihu.com/equation?tex=E" alt="E" class="ee_img tr_noresize" eeimg="1"> is an open set in <img src="https://www.zhihu.com/equation?tex=\mathbb{R}^n" alt="\mathbb{R}^n" class="ee_img tr_noresize" eeimg="1">. A differential form of
order <img src="https://www.zhihu.com/equation?tex=k\geq 1" alt="k\geq 1" class="ee_img tr_noresize" eeimg="1"> in <img src="https://www.zhihu.com/equation?tex=E" alt="E" class="ee_img tr_noresize" eeimg="1"> is a function <img src="https://www.zhihu.com/equation?tex=\omega" alt="\omega" class="ee_img tr_noresize" eeimg="1">, symbolically represented
by the sum:

<img src="https://www.zhihu.com/equation?tex=\omega=\sum a_{i_1,\dots,i_k}(x)dx_{i_1}\wedge\cdots dx_{i_k}\\" alt="\omega=\sum a_{i_1,\dots,i_k}(x)dx_{i_1}\wedge\cdots dx_{i_k}\\" class="ee_img tr_noresize" eeimg="1">

 which
assigns to each k-surface <img src="https://www.zhihu.com/equation?tex=\Phi" alt="\Phi" class="ee_img tr_noresize" eeimg="1"> in <img src="https://www.zhihu.com/equation?tex=E" alt="E" class="ee_img tr_noresize" eeimg="1"> a number
<img src="https://www.zhihu.com/equation?tex=\omega(\Phi)=\int_{\Phi}{\omega}" alt="\omega(\Phi)=\int_{\Phi}{\omega}" class="ee_img tr_noresize" eeimg="1"> according to the rule:

<img src="https://www.zhihu.com/equation?tex=\int_{\Phi}{\omega}=\int_{D}{\sum a_{i_1,\dots,i_k}(\Phi(u))\frac{\partial(x_{i_1},\dots,x_{i_1})}{\partial(u_{1},\dots,u_{k})}du}\\" alt="\int_{\Phi}{\omega}=\int_{D}{\sum a_{i_1,\dots,i_k}(\Phi(u))\frac{\partial(x_{i_1},\dots,x_{i_1})}{\partial(u_{1},\dots,u_{k})}du}\\" class="ee_img tr_noresize" eeimg="1">


where <img src="https://www.zhihu.com/equation?tex=D" alt="D" class="ee_img tr_noresize" eeimg="1"> is the parameter domain of <img src="https://www.zhihu.com/equation?tex=\Phi" alt="\Phi" class="ee_img tr_noresize" eeimg="1"> and
<img src="https://www.zhihu.com/equation?tex=\frac{\partial(x_{i_1},\dots,x_{i_1})}{\partial(u_{1},\dots,u_{k})}" alt="\frac{\partial(x_{i_1},\dots,x_{i_1})}{\partial(u_{1},\dots,u_{k})}" class="ee_img tr_noresize" eeimg="1"> is
the Jacobian of mapping
<img src="https://www.zhihu.com/equation?tex=(u_1,\dots,u_k)\mapsto (\phi_{i_1}(u),\dots\phi_{i_k}(u))" alt="(u_1,\dots,u_k)\mapsto (\phi_{i_1}(u),\dots\phi_{i_k}(u))" class="ee_img tr_noresize" eeimg="1">. We say
<img src="https://www.zhihu.com/equation?tex=\omega=0" alt="\omega=0" class="ee_img tr_noresize" eeimg="1"> if <img src="https://www.zhihu.com/equation?tex=\int_{\Phi}{\omega}" alt="\int_{\Phi}{\omega}" class="ee_img tr_noresize" eeimg="1"> for every k-surface <img src="https://www.zhihu.com/equation?tex=\Phi" alt="\Phi" class="ee_img tr_noresize" eeimg="1">.

There are some elementary properties of k-form but we will not mention
them here. We only talk about two operations of k-form, the
multiplication and differentiation.

Suppose <img src="https://www.zhihu.com/equation?tex=\omega=\sum_I b_I(x)dx_I" alt="\omega=\sum_I b_I(x)dx_I" class="ee_img tr_noresize" eeimg="1"> and <img src="https://www.zhihu.com/equation?tex=\lambda=\sum_J c_J(x)dx_J" alt="\lambda=\sum_J c_J(x)dx_J" class="ee_img tr_noresize" eeimg="1"> are
p-form and q-form. The product of <img src="https://www.zhihu.com/equation?tex=\omega" alt="\omega" class="ee_img tr_noresize" eeimg="1"> and <img src="https://www.zhihu.com/equation?tex=\lambda" alt="\lambda" class="ee_img tr_noresize" eeimg="1"> is defined to
be: 
<img src="https://www.zhihu.com/equation?tex=\omega\wedge\lambda=\sum_{I,J}b_I(x)c_J(x)d{x_I}\wedge dx_J\\" alt="\omega\wedge\lambda=\sum_{I,J}b_I(x)c_J(x)d{x_I}\wedge dx_J\\" class="ee_img tr_noresize" eeimg="1">


Notice the product of 0-form with p-form can be interchanged:

<img src="https://www.zhihu.com/equation?tex=f\omega=\omega f=\sum_If(x)b_I(x)dx_I\\" alt="f\omega=\omega f=\sum_If(x)b_I(x)dx_I\\" class="ee_img tr_noresize" eeimg="1">

 The differentiation of k-form
<img src="https://www.zhihu.com/equation?tex=\omega" alt="\omega" class="ee_img tr_noresize" eeimg="1"> is assigning a (k+1)-form <img src="https://www.zhihu.com/equation?tex=d\omega" alt="d\omega" class="ee_img tr_noresize" eeimg="1"> on <img src="https://www.zhihu.com/equation?tex=\omega" alt="\omega" class="ee_img tr_noresize" eeimg="1">. When <img src="https://www.zhihu.com/equation?tex=\omega" alt="\omega" class="ee_img tr_noresize" eeimg="1">
is a 0-form, in other words, <img src="https://www.zhihu.com/equation?tex=\omega" alt="\omega" class="ee_img tr_noresize" eeimg="1"> is a real function <img src="https://www.zhihu.com/equation?tex=f" alt="f" class="ee_img tr_noresize" eeimg="1">, we define:

<img src="https://www.zhihu.com/equation?tex=df=\sum_{i=1}^n\frac{\partial f}{\partial x_i}(x)dx_i\\" alt="df=\sum_{i=1}^n\frac{\partial f}{\partial x_i}(x)dx_i\\" class="ee_img tr_noresize" eeimg="1">

 When
<img src="https://www.zhihu.com/equation?tex=\omega=\sum b_I(x)dx_I" alt="\omega=\sum b_I(x)dx_I" class="ee_img tr_noresize" eeimg="1"> is a k-form, we define:

<img src="https://www.zhihu.com/equation?tex=d\omega=\sum_I (db_I)\wedge dx_I=\sum_I (\sum_{i=1}^n\frac{\partial b_I}{\partial x_i}(x)dx_i)\wedge dx_I=\sum_I \sum_{i=1}^n\frac{\partial b_I}{\partial x_i}(x)dx_i\wedge dx_I\\" alt="d\omega=\sum_I (db_I)\wedge dx_I=\sum_I (\sum_{i=1}^n\frac{\partial b_I}{\partial x_i}(x)dx_i)\wedge dx_I=\sum_I \sum_{i=1}^n\frac{\partial b_I}{\partial x_i}(x)dx_i\wedge dx_I\\" class="ee_img tr_noresize" eeimg="1">


This two operations on differential form are a little different from
differentiation on functions:

1.  If <img src="https://www.zhihu.com/equation?tex=\omega" alt="\omega" class="ee_img tr_noresize" eeimg="1"> and <img src="https://www.zhihu.com/equation?tex=\lambda" alt="\lambda" class="ee_img tr_noresize" eeimg="1"> are k-form and p-form. Then
    <img src="https://www.zhihu.com/equation?tex=d(\omega\wedge\lambda)=(d\omega)\wedge\lambda+(-1)^k \omega\wedge d\lambda" alt="d(\omega\wedge\lambda)=(d\omega)\wedge\lambda+(-1)^k \omega\wedge d\lambda" class="ee_img tr_noresize" eeimg="1">.

2.  <img src="https://www.zhihu.com/equation?tex=d^2\omega=0" alt="d^2\omega=0" class="ee_img tr_noresize" eeimg="1">.

Change of variables in differential form
----------------------------------------

Suppose <img src="https://www.zhihu.com/equation?tex=E" alt="E" class="ee_img tr_noresize" eeimg="1"> is an open set in <img src="https://www.zhihu.com/equation?tex=\mathbb{R}^n" alt="\mathbb{R}^n" class="ee_img tr_noresize" eeimg="1">,
<img src="https://www.zhihu.com/equation?tex=T=(t_1(x),t_2(x),\dots,t_m(x))" alt="T=(t_1(x),t_2(x),\dots,t_m(x))" class="ee_img tr_noresize" eeimg="1"> is a <img src="https://www.zhihu.com/equation?tex=C^1" alt="C^1" class="ee_img tr_noresize" eeimg="1"> mapping of <img src="https://www.zhihu.com/equation?tex=E" alt="E" class="ee_img tr_noresize" eeimg="1"> into a open
set <img src="https://www.zhihu.com/equation?tex=V\subset \mathbb{R}^m" alt="V\subset \mathbb{R}^m" class="ee_img tr_noresize" eeimg="1">, and <img src="https://www.zhihu.com/equation?tex=\omega=\sum_I b_I(y)dy_I" alt="\omega=\sum_I b_I(y)dy_I" class="ee_img tr_noresize" eeimg="1"> is a k-form
in <img src="https://www.zhihu.com/equation?tex=V" alt="V" class="ee_img tr_noresize" eeimg="1">. We define <img src="https://www.zhihu.com/equation?tex=\omega_T" alt="\omega_T" class="ee_img tr_noresize" eeimg="1"> as:

<img src="https://www.zhihu.com/equation?tex=\omega_T=\sum_I b_I(T(x))dt_{i_1}\wedge\dots\wedge dt_{ik}\\" alt="\omega_T=\sum_I b_I(T(x))dt_{i_1}\wedge\dots\wedge dt_{ik}\\" class="ee_img tr_noresize" eeimg="1">

 Given a
k-surface <img src="https://www.zhihu.com/equation?tex=\Phi" alt="\Phi" class="ee_img tr_noresize" eeimg="1"> with parameter domain <img src="https://www.zhihu.com/equation?tex=D" alt="D" class="ee_img tr_noresize" eeimg="1">, we define a k-surface
<img src="https://www.zhihu.com/equation?tex=\Delta" alt="\Delta" class="ee_img tr_noresize" eeimg="1"> in <img src="https://www.zhihu.com/equation?tex=\mathbb{R}^k" alt="\mathbb{R}^k" class="ee_img tr_noresize" eeimg="1"> by <img src="https://www.zhihu.com/equation?tex=\Delta(u)=u" alt="\Delta(u)=u" class="ee_img tr_noresize" eeimg="1">. we have change of domain of
integration: 
<img src="https://www.zhihu.com/equation?tex=\int_{\Phi}{\omega}=\int_{\Delta}{\omega_\Phi}\\" alt="\int_{\Phi}{\omega}=\int_{\Delta}{\omega_\Phi}\\" class="ee_img tr_noresize" eeimg="1">

 More
generally, we can change of domain of integration between two k-surfaces
under a <img src="https://www.zhihu.com/equation?tex=C^1" alt="C^1" class="ee_img tr_noresize" eeimg="1"> mapping <img src="https://www.zhihu.com/equation?tex=T" alt="T" class="ee_img tr_noresize" eeimg="1">:

<img src="https://www.zhihu.com/equation?tex=\int_{T\Phi}{\omega}=\int_{\Phi}{\omega_T}\\" alt="\int_{T\Phi}{\omega}=\int_{\Phi}{\omega_T}\\" class="ee_img tr_noresize" eeimg="1">

 where <img src="https://www.zhihu.com/equation?tex=T" alt="T" class="ee_img tr_noresize" eeimg="1"> maps k-surface
<img src="https://www.zhihu.com/equation?tex=\Phi" alt="\Phi" class="ee_img tr_noresize" eeimg="1"> in <img src="https://www.zhihu.com/equation?tex=\mathbb{R}^n" alt="\mathbb{R}^n" class="ee_img tr_noresize" eeimg="1"> to k-surface <img src="https://www.zhihu.com/equation?tex=T\Phi" alt="T\Phi" class="ee_img tr_noresize" eeimg="1"> in <img src="https://www.zhihu.com/equation?tex=\mathbb{R}^m" alt="\mathbb{R}^m" class="ee_img tr_noresize" eeimg="1">.

Simplexes and chains
--------------------

We define oriented affine k-simplex 
<img src="https://www.zhihu.com/equation?tex=\sigma=[p_0,p_1,\dots p_k]\\" alt="\sigma=[p_0,p_1,\dots p_k]\\" class="ee_img tr_noresize" eeimg="1">

 to be
the k-surface wither parameter domain <img src="https://www.zhihu.com/equation?tex=Q^k" alt="Q^k" class="ee_img tr_noresize" eeimg="1"> which is given by the affine
mapping:

<img src="https://www.zhihu.com/equation?tex=\sigma(\alpha_1e_1+\cdots+\alpha_ke_k)=p_0+\sum_{i=1}^k\alpha_i(p_i-p_0)\\" alt="\sigma(\alpha_1e_1+\cdots+\alpha_ke_k)=p_0+\sum_{i=1}^k\alpha_i(p_i-p_0)\\" class="ee_img tr_noresize" eeimg="1">


The <img src="https://www.zhihu.com/equation?tex=Q^k" alt="Q^k" class="ee_img tr_noresize" eeimg="1"> called the standard simplex, which is the set of all
<img src="https://www.zhihu.com/equation?tex=u\in \mathbb{R}^k" alt="u\in \mathbb{R}^k" class="ee_img tr_noresize" eeimg="1"> of the form <img src="https://www.zhihu.com/equation?tex=u=\sum_{i=1}^k\alpha_ie_i" alt="u=\sum_{i=1}^k\alpha_ie_i" class="ee_img tr_noresize" eeimg="1"> such that
<img src="https://www.zhihu.com/equation?tex=\alpha_i\geq 0" alt="\alpha_i\geq 0" class="ee_img tr_noresize" eeimg="1"> and <img src="https://www.zhihu.com/equation?tex=\sum a_i\leq 1" alt="\sum a_i\leq 1" class="ee_img tr_noresize" eeimg="1">. When <img src="https://www.zhihu.com/equation?tex=k=0" alt="k=0" class="ee_img tr_noresize" eeimg="1">, the oriented
0-simplex is defined to be a point with a sign attached. We write
<img src="https://www.zhihu.com/equation?tex=\sigma=+p_0" alt="\sigma=+p_0" class="ee_img tr_noresize" eeimg="1"> or <img src="https://www.zhihu.com/equation?tex=\sigma=-p_0" alt="\sigma=-p_0" class="ee_img tr_noresize" eeimg="1">. And integration of real function on this
simplex <img src="https://www.zhihu.com/equation?tex=\sigma=\epsilon p_0" alt="\sigma=\epsilon p_0" class="ee_img tr_noresize" eeimg="1"> is defined to be:

<img src="https://www.zhihu.com/equation?tex=\int_{\sigma}f=\epsilon f(p_0)\\" alt="\int_{\sigma}f=\epsilon f(p_0)\\" class="ee_img tr_noresize" eeimg="1">



An affine k-chain <img src="https://www.zhihu.com/equation?tex=\Gamma" alt="\Gamma" class="ee_img tr_noresize" eeimg="1"> is a collection of finitely many oriented
affine k-simplexes <img src="https://www.zhihu.com/equation?tex=\sigma_1,\dots \sigma_r" alt="\sigma_1,\dots \sigma_r" class="ee_img tr_noresize" eeimg="1">. And we define the
integration of k-form <img src="https://www.zhihu.com/equation?tex=\omega" alt="\omega" class="ee_img tr_noresize" eeimg="1"> on <img src="https://www.zhihu.com/equation?tex=\Gamma" alt="\Gamma" class="ee_img tr_noresize" eeimg="1"> to be:

<img src="https://www.zhihu.com/equation?tex=\int_{\Gamma}\omega=\sum_{i=1}^r\int_{\sigma}\omega\\" alt="\int_{\Gamma}\omega=\sum_{i=1}^r\int_{\sigma}\omega\\" class="ee_img tr_noresize" eeimg="1">

 and symbolically
we write: 
<img src="https://www.zhihu.com/equation?tex=\Gamma=\sigma_1+\cdots+\sigma_r=\sum_{i=1}^r\sigma_i\\" alt="\Gamma=\sigma_1+\cdots+\sigma_r=\sum_{i=1}^r\sigma_i\\" class="ee_img tr_noresize" eeimg="1">

 We
write <img src="https://www.zhihu.com/equation?tex=\Gamma=0" alt="\Gamma=0" class="ee_img tr_noresize" eeimg="1"> if <img src="https://www.zhihu.com/equation?tex=\int_{\Gamma}\omega=0" alt="\int_{\Gamma}\omega=0" class="ee_img tr_noresize" eeimg="1"> for all <img src="https://www.zhihu.com/equation?tex=\omega" alt="\omega" class="ee_img tr_noresize" eeimg="1">.

For <img src="https://www.zhihu.com/equation?tex=k\geq 1" alt="k\geq 1" class="ee_img tr_noresize" eeimg="1">, given an affine k-simplex <img src="https://www.zhihu.com/equation?tex=\sigma=[p_0,p_1,\dots p_k]" alt="\sigma=[p_0,p_1,\dots p_k]" class="ee_img tr_noresize" eeimg="1">,
we define the boundary of <img src="https://www.zhihu.com/equation?tex=\sigma" alt="\sigma" class="ee_img tr_noresize" eeimg="1"> to be the affine (k-1)-chain:

<img src="https://www.zhihu.com/equation?tex=\partial \sigma=\sum_{j=0}^k(-1)^j[p_0,\dots,p_{j-1},p_{j+1},\dots, p_k]\\" alt="\partial \sigma=\sum_{j=0}^k(-1)^j[p_0,\dots,p_{j-1},p_{j+1},\dots, p_k]\\" class="ee_img tr_noresize" eeimg="1">



After the affine case, now we can consider the general case. Let <img src="https://www.zhihu.com/equation?tex=T" alt="T" class="ee_img tr_noresize" eeimg="1"> be
a <img src="https://www.zhihu.com/equation?tex=C^2" alt="C^2" class="ee_img tr_noresize" eeimg="1"> mapping from <img src="https://www.zhihu.com/equation?tex=E\subset \mathbb{R}^n" alt="E\subset \mathbb{R}^n" class="ee_img tr_noresize" eeimg="1"> to <img src="https://www.zhihu.com/equation?tex=V\subset \mathbb{R}^m" alt="V\subset \mathbb{R}^m" class="ee_img tr_noresize" eeimg="1">.
We consider the composite mapping <img src="https://www.zhihu.com/equation?tex=\Phi=T\sigma" alt="\Phi=T\sigma" class="ee_img tr_noresize" eeimg="1">, which is a k-surface
in <img src="https://www.zhihu.com/equation?tex=V" alt="V" class="ee_img tr_noresize" eeimg="1">. We call <img src="https://www.zhihu.com/equation?tex=\Phi" alt="\Phi" class="ee_img tr_noresize" eeimg="1"> an oriented k-simplex. The k-chain
<img src="https://www.zhihu.com/equation?tex=\Psi=\sum \Phi_i" alt="\Psi=\sum \Phi_i" class="ee_img tr_noresize" eeimg="1"> is defined to be:

<img src="https://www.zhihu.com/equation?tex=\int_{\Psi}{\omega}=\sum_{i=1}^r\int_{\Phi_i}{\omega}\\" alt="\int_{\Psi}{\omega}=\sum_{i=1}^r\int_{\Phi_i}{\omega}\\" class="ee_img tr_noresize" eeimg="1">

 And the
boundary <img src="https://www.zhihu.com/equation?tex=\partial\Phi" alt="\partial\Phi" class="ee_img tr_noresize" eeimg="1"> of k-simplex <img src="https://www.zhihu.com/equation?tex=\Phi" alt="\Phi" class="ee_img tr_noresize" eeimg="1"> is (k-1)-chain:

<img src="https://www.zhihu.com/equation?tex=\partial\Phi=T(\partial\sigma)\\" alt="\partial\Phi=T(\partial\sigma)\\" class="ee_img tr_noresize" eeimg="1">

 And the boundary <img src="https://www.zhihu.com/equation?tex=\partial\Psi" alt="\partial\Psi" class="ee_img tr_noresize" eeimg="1"> of
k-chain <img src="https://www.zhihu.com/equation?tex=\Psi=\sum \Phi_i" alt="\Psi=\sum \Phi_i" class="ee_img tr_noresize" eeimg="1"> is (k-1)-chain:

<img src="https://www.zhihu.com/equation?tex=\partial\Psi=\sum\partial\Phi_i\\" alt="\partial\Psi=\sum\partial\Phi_i\\" class="ee_img tr_noresize" eeimg="1">



Stoke's theorem, closed and exact forms
---------------------------------------

The Stoke's theorem is:

If <img src="https://www.zhihu.com/equation?tex=\Psi" alt="\Psi" class="ee_img tr_noresize" eeimg="1"> is a k-chain and if <img src="https://www.zhihu.com/equation?tex=\omega" alt="\omega" class="ee_img tr_noresize" eeimg="1"> is a (k-1)-form, then

<img src="https://www.zhihu.com/equation?tex=\int_{\Psi}{d\omega}=\int_{\partial\Psi}{\omega}\\" alt="\int_{\Psi}{d\omega}=\int_{\partial\Psi}{\omega}\\" class="ee_img tr_noresize" eeimg="1">



Given a k-form <img src="https://www.zhihu.com/equation?tex=\omega" alt="\omega" class="ee_img tr_noresize" eeimg="1"> in an open set <img src="https://www.zhihu.com/equation?tex=E\subset \mathbb{R}^n" alt="E\subset \mathbb{R}^n" class="ee_img tr_noresize" eeimg="1">, if there
is a (k-1)-form <img src="https://www.zhihu.com/equation?tex=\lambda" alt="\lambda" class="ee_img tr_noresize" eeimg="1"> s.t. <img src="https://www.zhihu.com/equation?tex=\omega=d\lambda" alt="\omega=d\lambda" class="ee_img tr_noresize" eeimg="1">, then <img src="https://www.zhihu.com/equation?tex=\omega" alt="\omega" class="ee_img tr_noresize" eeimg="1"> is said
to be exact in <img src="https://www.zhihu.com/equation?tex=E" alt="E" class="ee_img tr_noresize" eeimg="1">. If <img src="https://www.zhihu.com/equation?tex=d\omega=0" alt="d\omega=0" class="ee_img tr_noresize" eeimg="1">, then <img src="https://www.zhihu.com/equation?tex=\omega" alt="\omega" class="ee_img tr_noresize" eeimg="1"> is said to be closed.
Since <img src="https://www.zhihu.com/equation?tex=d^2\omega=0" alt="d^2\omega=0" class="ee_img tr_noresize" eeimg="1">, every exact form is closed. The converse is true if
<img src="https://www.zhihu.com/equation?tex=E" alt="E" class="ee_img tr_noresize" eeimg="1"> is convex open set (Poincare's lemma). The convex property
guarantees us to use mean value inequality, more precisely, <img src="https://www.zhihu.com/equation?tex=f'(x)=0" alt="f'(x)=0" class="ee_img tr_noresize" eeimg="1"> on
<img src="https://www.zhihu.com/equation?tex=E" alt="E" class="ee_img tr_noresize" eeimg="1"> implies <img src="https://www.zhihu.com/equation?tex=f(x)" alt="f(x)" class="ee_img tr_noresize" eeimg="1"> is constant on <img src="https://www.zhihu.com/equation?tex=E" alt="E" class="ee_img tr_noresize" eeimg="1"> if <img src="https://www.zhihu.com/equation?tex=E" alt="E" class="ee_img tr_noresize" eeimg="1"> is convex. This statement
is important in proof of Poincare's lemma.

Given a open set <img src="https://www.zhihu.com/equation?tex=E" alt="E" class="ee_img tr_noresize" eeimg="1">, which satisfies all closed form on <img src="https://www.zhihu.com/equation?tex=E" alt="E" class="ee_img tr_noresize" eeimg="1"> is exact
form. We map <img src="https://www.zhihu.com/equation?tex=E" alt="E" class="ee_img tr_noresize" eeimg="1"> onto <img src="https://www.zhihu.com/equation?tex=U" alt="U" class="ee_img tr_noresize" eeimg="1"> by a 1-1 <img src="https://www.zhihu.com/equation?tex=C^2" alt="C^2" class="ee_img tr_noresize" eeimg="1"> mapping <img src="https://www.zhihu.com/equation?tex=T" alt="T" class="ee_img tr_noresize" eeimg="1"> which <img src="https://www.zhihu.com/equation?tex=T^{-1}" alt="T^{-1}" class="ee_img tr_noresize" eeimg="1"> is
also in <img src="https://www.zhihu.com/equation?tex=C^2" alt="C^2" class="ee_img tr_noresize" eeimg="1">. Then every closed k-form in <img src="https://www.zhihu.com/equation?tex=U" alt="U" class="ee_img tr_noresize" eeimg="1"> is exact in <img src="https://www.zhihu.com/equation?tex=U" alt="U" class="ee_img tr_noresize" eeimg="1"> (Theorem
10.40). We call <img src="https://www.zhihu.com/equation?tex=E" alt="E" class="ee_img tr_noresize" eeimg="1"> and <img src="https://www.zhihu.com/equation?tex=U" alt="U" class="ee_img tr_noresize" eeimg="1"> are <img src="https://www.zhihu.com/equation?tex=C^2" alt="C^2" class="ee_img tr_noresize" eeimg="1">-equivalent.

Thus not only on convex open set closed forms are exact s, but also on
any open set is <img src="https://www.zhihu.com/equation?tex=C^2" alt="C^2" class="ee_img tr_noresize" eeimg="1">-equivalent to a convex set they are.

Vector analysis
---------------

In this section we talk some examples and theorems related to
differential forms in <img src="https://www.zhihu.com/equation?tex=\mathbb{R}^3" alt="\mathbb{R}^3" class="ee_img tr_noresize" eeimg="1">.

Let <img src="https://www.zhihu.com/equation?tex=F=F_1e_1+F_2e_2+F_3e_3" alt="F=F_1e_1+F_2e_2+F_3e_3" class="ee_img tr_noresize" eeimg="1"> be a continuous mapping of an open set
<img src="https://www.zhihu.com/equation?tex=E\subset \mathbb{R}^3" alt="E\subset \mathbb{R}^3" class="ee_img tr_noresize" eeimg="1">. We associated <img src="https://www.zhihu.com/equation?tex=F" alt="F" class="ee_img tr_noresize" eeimg="1"> with following differential
forms and functions:

1.  <img src="https://www.zhihu.com/equation?tex=\lambda_F=F_1dx+F_2dy+F_3dz" alt="\lambda_F=F_1dx+F_2dy+F_3dz" class="ee_img tr_noresize" eeimg="1">

2.  <img src="https://www.zhihu.com/equation?tex=\omega_F=F_1dy\wedge dz+F_2dz\wedge dx+F_3dx\wedge dz" alt="\omega_F=F_1dy\wedge dz+F_2dz\wedge dx+F_3dx\wedge dz" class="ee_img tr_noresize" eeimg="1">

3.  <img src="https://www.zhihu.com/equation?tex=\nabla\cdot F=D_1F_1+D_2F_2+D_3F_3" alt="\nabla\cdot F=D_1F_1+D_2F_2+D_3F_3" class="ee_img tr_noresize" eeimg="1">

4.  <img src="https://www.zhihu.com/equation?tex=\nabla\times F=(D_2F_3-D_3F_2)e_1+(D_3F_1-D_1F_3)e_2+(D_1F_2-D_2F_1)e_3" alt="\nabla\times F=(D_2F_3-D_3F_2)e_1+(D_3F_1-D_1F_3)e_2+(D_1F_2-D_2F_1)e_3" class="ee_img tr_noresize" eeimg="1">

And associated a real function <img src="https://www.zhihu.com/equation?tex=u" alt="u" class="ee_img tr_noresize" eeimg="1"> with its gradient:

<img src="https://www.zhihu.com/equation?tex=\nabla u=(D_1u)e_1+(D_2u)e_2+(D_3u)e_3\\" alt="\nabla u=(D_1u)e_1+(D_2u)e_2+(D_3u)e_3\\" class="ee_img tr_noresize" eeimg="1">

 By easy computation, the
following equations:

<img src="https://www.zhihu.com/equation?tex=F=\nabla u,\quad \nabla\times F=0,\quad F=\nabla\times G,\quad \nabla\cdot F=0\\" alt="F=\nabla u,\quad \nabla\times F=0,\quad F=\nabla\times G,\quad \nabla\cdot F=0\\" class="ee_img tr_noresize" eeimg="1">


are equivalent to:

<img src="https://www.zhihu.com/equation?tex=\lambda_F=du,\quad d\lambda_F=0,\quad \omega_F=d\lambda_G,\quad d\omega_F=0\\" alt="\lambda_F=du,\quad d\lambda_F=0,\quad \omega_F=d\lambda_G,\quad d\omega_F=0\\" class="ee_img tr_noresize" eeimg="1">


By using the equations of differential form, we can prove:

1.  If <img src="https://www.zhihu.com/equation?tex=F=\nabla u" alt="F=\nabla u" class="ee_img tr_noresize" eeimg="1">, then <img src="https://www.zhihu.com/equation?tex=\nabla\times F=0" alt="\nabla\times F=0" class="ee_img tr_noresize" eeimg="1">

2.  If <img src="https://www.zhihu.com/equation?tex=F=\nabla\times G" alt="F=\nabla\times G" class="ee_img tr_noresize" eeimg="1">, then <img src="https://www.zhihu.com/equation?tex=\nabla\cdot F=0" alt="\nabla\cdot F=0" class="ee_img tr_noresize" eeimg="1">

Then converse is true if <img src="https://www.zhihu.com/equation?tex=E" alt="E" class="ee_img tr_noresize" eeimg="1"> is <img src="https://www.zhihu.com/equation?tex=C^2" alt="C^2" class="ee_img tr_noresize" eeimg="1"> equivalent to a convex set.

Now we consider the relation between integrations of above differential
forms and functions.

Given a 1-surface (curve) <img src="https://www.zhihu.com/equation?tex=\gamma" alt="\gamma" class="ee_img tr_noresize" eeimg="1"> in an open set
<img src="https://www.zhihu.com/equation?tex=E\subset \mathbb{R}^3" alt="E\subset \mathbb{R}^3" class="ee_img tr_noresize" eeimg="1"> with parameter interval <img src="https://www.zhihu.com/equation?tex=[0,1]" alt="[0,1]" class="ee_img tr_noresize" eeimg="1">, we define the
unit vector <img src="https://www.zhihu.com/equation?tex=\mathbf{t}(u)" alt="\mathbf{t}(u)" class="ee_img tr_noresize" eeimg="1"> to be
<img src="https://www.zhihu.com/equation?tex=\gamma'(u)=\left\lvert\gamma'(u)\right\rvert\mathbf{t}(u)" alt="\gamma'(u)=\left\lvert\gamma'(u)\right\rvert\mathbf{t}(u)" class="ee_img tr_noresize" eeimg="1"> and the
element of arc length <img src="https://www.zhihu.com/equation?tex=ds" alt="ds" class="ee_img tr_noresize" eeimg="1"> to be <img src="https://www.zhihu.com/equation?tex=\left\lvert\gamma'(u)\right\rvert du" alt="\left\lvert\gamma'(u)\right\rvert du" class="ee_img tr_noresize" eeimg="1">.
We have:

<img src="https://www.zhihu.com/equation?tex=\int_{\gamma}{\lambda_F}=\int_{0}^1{F(\gamma(u))\cdot \mathbf{t}(u))ds}\\" alt="\int_{\gamma}{\lambda_F}=\int_{0}^1{F(\gamma(u))\cdot \mathbf{t}(u))ds}\\" class="ee_img tr_noresize" eeimg="1">


And we denote the second integration as
<img src="https://www.zhihu.com/equation?tex=\int_{\gamma}{(F\cdot \mathbf{t})ds}" alt="\int_{\gamma}{(F\cdot \mathbf{t})ds}" class="ee_img tr_noresize" eeimg="1">.

Given a 2-surface <img src="https://www.zhihu.com/equation?tex=\Phi" alt="\Phi" class="ee_img tr_noresize" eeimg="1"> in an open set <img src="https://www.zhihu.com/equation?tex=E\subset \mathbb{R}^3" alt="E\subset \mathbb{R}^3" class="ee_img tr_noresize" eeimg="1"> with
parameter domain <img src="https://www.zhihu.com/equation?tex=D" alt="D" class="ee_img tr_noresize" eeimg="1">, we define

<img src="https://www.zhihu.com/equation?tex=N(u,v)=\frac{\partial(y,z)}{\partial(u,v)}e_1+\frac{\partial(z,x)}{\partial(u,v)}e_2+\frac{\partial(x,y)}{\partial(u,v)}e_3\\" alt="N(u,v)=\frac{\partial(y,z)}{\partial(u,v)}e_1+\frac{\partial(z,x)}{\partial(u,v)}e_2+\frac{\partial(x,y)}{\partial(u,v)}e_3\\" class="ee_img tr_noresize" eeimg="1">


where <img src="https://www.zhihu.com/equation?tex=(x,y,z)=\Phi(u,v)" alt="(x,y,z)=\Phi(u,v)" class="ee_img tr_noresize" eeimg="1">. And we define the unit vector
<img src="https://www.zhihu.com/equation?tex=\mathbf{n}(u,v)" alt="\mathbf{n}(u,v)" class="ee_img tr_noresize" eeimg="1"> to be
<img src="https://www.zhihu.com/equation?tex=N(u,v)=\left\lvert N(u,v)\right\rvert\mathbf{n}(u,v)" alt="N(u,v)=\left\lvert N(u,v)\right\rvert\mathbf{n}(u,v)" class="ee_img tr_noresize" eeimg="1"> and the element
of area <img src="https://www.zhihu.com/equation?tex=dA" alt="dA" class="ee_img tr_noresize" eeimg="1"> to be <img src="https://www.zhihu.com/equation?tex=\left\lvert N(u,v)\right\rvert dudv" alt="\left\lvert N(u,v)\right\rvert dudv" class="ee_img tr_noresize" eeimg="1">. We have:

<img src="https://www.zhihu.com/equation?tex=\int_{\Phi}{\omega_F}=\int_{D}{F(\Phi(u,v))\cdot \mathbf{n}(u,v))dA}\\" alt="\int_{\Phi}{\omega_F}=\int_{D}{F(\Phi(u,v))\cdot \mathbf{n}(u,v))dA}\\" class="ee_img tr_noresize" eeimg="1">


And we denote the second integration as
<img src="https://www.zhihu.com/equation?tex=\int_{\Phi}{(F\cdot \mathbf{n})dA}" alt="\int_{\Phi}{(F\cdot \mathbf{n})dA}" class="ee_img tr_noresize" eeimg="1">.

By Stoke's formula, we have:

1.  Stoke's formula:
    <img src="https://www.zhihu.com/equation?tex=\int_{\Phi}{(\nabla\times F)\cdot \mathbf{n}dA}=\int_{\partial\Phi}{(F\cdot \mathbf{t})ds}" alt="\int_{\Phi}{(\nabla\times F)\cdot \mathbf{n}dA}=\int_{\partial\Phi}{(F\cdot \mathbf{t})ds}" class="ee_img tr_noresize" eeimg="1">

2.  The divergence theorem:
    <img src="https://www.zhihu.com/equation?tex=\int_{\Omega}{(\nabla\cdot F)dV}=\int_{\partial\Omega}{(F\cdot \mathbf{n})dA}" alt="\int_{\Omega}{(\nabla\cdot F)dV}=\int_{\partial\Omega}{(F\cdot \mathbf{n})dA}" class="ee_img tr_noresize" eeimg="1">
