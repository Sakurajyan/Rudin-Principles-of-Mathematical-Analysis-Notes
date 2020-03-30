Sequences and Series of Functions
=================================

The main problem this chapter focuses is when the limit processes can be
interchanged with series, integral and differentiation. Another problem
is what family of functions is dense in continuous function space on
compact set.

We first define the limit function <img src="https://www.zhihu.com/equation?tex=f(x)" alt="f(x)" class="ee_img tr_noresize" eeimg="1"> of sequence <img src="https://www.zhihu.com/equation?tex=(f_n(x))" alt="(f_n(x))" class="ee_img tr_noresize" eeimg="1"> as
pointwise limit of <img src="https://www.zhihu.com/equation?tex=(f_n(x))" alt="(f_n(x))" class="ee_img tr_noresize" eeimg="1">. We give some examples in book, which show
the limit process can not be interchanged carelessly.

Uniform convergence
-------------------

To avoid the interchange problem, we introduce a new concept, uniform
convergence:

A sequence of functions <img src="https://www.zhihu.com/equation?tex=(f_n(x))" alt="(f_n(x))" class="ee_img tr_noresize" eeimg="1"> converges uniformly on <img src="https://www.zhihu.com/equation?tex=E" alt="E" class="ee_img tr_noresize" eeimg="1"> to a
function <img src="https://www.zhihu.com/equation?tex=f" alt="f" class="ee_img tr_noresize" eeimg="1"> if for every <img src="https://www.zhihu.com/equation?tex=\epsilon>0" alt="\epsilon>0" class="ee_img tr_noresize" eeimg="1"> there is an integer <img src="https://www.zhihu.com/equation?tex=N" alt="N" class="ee_img tr_noresize" eeimg="1"> such that
<img src="https://www.zhihu.com/equation?tex=n>N" alt="n>N" class="ee_img tr_noresize" eeimg="1"> implies: 
<img src="https://www.zhihu.com/equation?tex=\left\lvert f_n(x)-f(x)\right\rvert\leq \epsilon\\" alt="\left\lvert f_n(x)-f(x)\right\rvert\leq \epsilon\\" class="ee_img tr_noresize" eeimg="1">

 for
all <img src="https://www.zhihu.com/equation?tex=x\in E" alt="x\in E" class="ee_img tr_noresize" eeimg="1">.

A very convenient test for uniform convergence is Weierstrass test. It
says if <img src="https://www.zhihu.com/equation?tex=\left\lvert f_n(x)\right\rvert<M_n" alt="\left\lvert f_n(x)\right\rvert<M_n" class="ee_img tr_noresize" eeimg="1"> and <img src="https://www.zhihu.com/equation?tex=\sum M_n" alt="\sum M_n" class="ee_img tr_noresize" eeimg="1"> converges,
then <img src="https://www.zhihu.com/equation?tex=\sum f_n(x)" alt="\sum f_n(x)" class="ee_img tr_noresize" eeimg="1"> converges uniformly.

Under uniform convergence, we have following interchange statement:

1.  If <img src="https://www.zhihu.com/equation?tex=f_n\to f" alt="f_n\to f" class="ee_img tr_noresize" eeimg="1"> uniformly, then
    <img src="https://www.zhihu.com/equation?tex=\lim_{t\to x}\lim_{n\to \infty}f_n(t)=\lim_{n\to \infty}\lim_{t\to x}f_n(t)" alt="\lim_{t\to x}\lim_{n\to \infty}f_n(t)=\lim_{n\to \infty}\lim_{t\to x}f_n(t)" class="ee_img tr_noresize" eeimg="1">.

2.  If <img src="https://www.zhihu.com/equation?tex=(f_n(x))" alt="(f_n(x))" class="ee_img tr_noresize" eeimg="1"> are continuous and <img src="https://www.zhihu.com/equation?tex=f_n\to f" alt="f_n\to f" class="ee_img tr_noresize" eeimg="1"> uniformly, then <img src="https://www.zhihu.com/equation?tex=f" alt="f" class="ee_img tr_noresize" eeimg="1"> is
    continuous. The converse is true if <img src="https://www.zhihu.com/equation?tex=(f_n(x))" alt="(f_n(x))" class="ee_img tr_noresize" eeimg="1"> are on compact set
    <img src="https://www.zhihu.com/equation?tex=K" alt="K" class="ee_img tr_noresize" eeimg="1"> and <img src="https://www.zhihu.com/equation?tex=(f_n(x))" alt="(f_n(x))" class="ee_img tr_noresize" eeimg="1"> is decreasing sequence.

3.  If <img src="https://www.zhihu.com/equation?tex=(f_n(x))" alt="(f_n(x))" class="ee_img tr_noresize" eeimg="1"> are R-S integrable and <img src="https://www.zhihu.com/equation?tex=f_n\to f" alt="f_n\to f" class="ee_img tr_noresize" eeimg="1"> uniformly, then <img src="https://www.zhihu.com/equation?tex=f" alt="f" class="ee_img tr_noresize" eeimg="1">
    is R-S integrable and
    <img src="https://www.zhihu.com/equation?tex=\int_{a}^{b}fd\alpha=\lim_{n\to \infty}\int_{a}^{b}f_n d\alpha" alt="\int_{a}^{b}fd\alpha=\lim_{n\to \infty}\int_{a}^{b}f_n d\alpha" class="ee_img tr_noresize" eeimg="1">.

4.  If <img src="https://www.zhihu.com/equation?tex=(f_n(x))" alt="(f_n(x))" class="ee_img tr_noresize" eeimg="1"> are differentiable, <img src="https://www.zhihu.com/equation?tex=(f_n(x))" alt="(f_n(x))" class="ee_img tr_noresize" eeimg="1"> converges for some
    point <img src="https://www.zhihu.com/equation?tex=x_0" alt="x_0" class="ee_img tr_noresize" eeimg="1"> and <img src="https://www.zhihu.com/equation?tex=(f'_n(x))" alt="(f'_n(x))" class="ee_img tr_noresize" eeimg="1"> converges uniformly, then
    <img src="https://www.zhihu.com/equation?tex=f_n(x)\to f(x)" alt="f_n(x)\to f(x)" class="ee_img tr_noresize" eeimg="1"> uniformly and <img src="https://www.zhihu.com/equation?tex=f'(x)=\lim_{n\to\infty}f'_n(x)" alt="f'(x)=\lim_{n\to\infty}f'_n(x)" class="ee_img tr_noresize" eeimg="1">.

By the second statement, we claim <img src="https://www.zhihu.com/equation?tex=C(K)" alt="C(K)" class="ee_img tr_noresize" eeimg="1"> is complete space with supremum
norm: <img src="https://www.zhihu.com/equation?tex=\lVert f\rVert=\sup\left\lvert f(x)\right\rvert" alt="\lVert f\rVert=\sup\left\lvert f(x)\right\rvert" class="ee_img tr_noresize" eeimg="1">.

We know for any bounded infinite sequence in <img src="https://www.zhihu.com/equation?tex=\mathbb{R}^n" alt="\mathbb{R}^n" class="ee_img tr_noresize" eeimg="1">, we can
extract a convergent subsequence. This is by the relation between
boundedness and compact for <img src="https://www.zhihu.com/equation?tex=\mathbb{R}^n" alt="\mathbb{R}^n" class="ee_img tr_noresize" eeimg="1">. We will talk about similar
properties for functions, but first we need to specify what convergence
we consider. We will consider pointwise convergence and uniform
convergence.

By diagonal process, given a sequence of pointwise bounded functions
<img src="https://www.zhihu.com/equation?tex=(f_n(x))" alt="(f_n(x))" class="ee_img tr_noresize" eeimg="1"> on <img src="https://www.zhihu.com/equation?tex=E" alt="E" class="ee_img tr_noresize" eeimg="1">, we can extract a subsequence which converges on a
countable subset of <img src="https://www.zhihu.com/equation?tex=E" alt="E" class="ee_img tr_noresize" eeimg="1">. But we can not extract a subsequence which
converges on <img src="https://www.zhihu.com/equation?tex=E" alt="E" class="ee_img tr_noresize" eeimg="1"> even if <img src="https://www.zhihu.com/equation?tex=(f_n(x))" alt="(f_n(x))" class="ee_img tr_noresize" eeimg="1"> is uniformly bounded.

We want to find a type a convergence which helps to make a subset of
<img src="https://www.zhihu.com/equation?tex=C(K)" alt="C(K)" class="ee_img tr_noresize" eeimg="1"> 'compact'.

Continuous function space
-------------------------

To solve the problem at the end of section 1, we need a more stronger
continuity for family of functions, called equicontinuity.

A family <img src="https://www.zhihu.com/equation?tex=\mathscr{F}" alt="\mathscr{F}" class="ee_img tr_noresize" eeimg="1"> of complex functions <img src="https://www.zhihu.com/equation?tex=f" alt="f" class="ee_img tr_noresize" eeimg="1"> defined on a set <img src="https://www.zhihu.com/equation?tex=E" alt="E" class="ee_img tr_noresize" eeimg="1"> in
a metric space <img src="https://www.zhihu.com/equation?tex=X" alt="X" class="ee_img tr_noresize" eeimg="1"> is said to be equicontinuous on <img src="https://www.zhihu.com/equation?tex=E" alt="E" class="ee_img tr_noresize" eeimg="1"> if for every
<img src="https://www.zhihu.com/equation?tex=\epsilon>0" alt="\epsilon>0" class="ee_img tr_noresize" eeimg="1"> there exists a <img src="https://www.zhihu.com/equation?tex=\delta>0" alt="\delta>0" class="ee_img tr_noresize" eeimg="1"> s.t.

<img src="https://www.zhihu.com/equation?tex=\left\lvert f(x)-f(y)\right\rvert<\epsilon\\" alt="\left\lvert f(x)-f(y)\right\rvert<\epsilon\\" class="ee_img tr_noresize" eeimg="1">

 whenever <img src="https://www.zhihu.com/equation?tex=d(x,y)<\delta" alt="d(x,y)<\delta" class="ee_img tr_noresize" eeimg="1">,
<img src="https://www.zhihu.com/equation?tex=x\in E" alt="x\in E" class="ee_img tr_noresize" eeimg="1">, <img src="https://www.zhihu.com/equation?tex=y\in E" alt="y\in E" class="ee_img tr_noresize" eeimg="1"> and <img src="https://www.zhihu.com/equation?tex=f\in \mathscr{F}" alt="f\in \mathscr{F}" class="ee_img tr_noresize" eeimg="1">.

It is clear that every member of an equicontinuous family is uniformly
continuous.

Here is a criterion for equicontinuity: If <img src="https://www.zhihu.com/equation?tex=(f_n(x))" alt="(f_n(x))" class="ee_img tr_noresize" eeimg="1"> is a sequence of
continuous function on a compact set <img src="https://www.zhihu.com/equation?tex=K" alt="K" class="ee_img tr_noresize" eeimg="1">, and <img src="https://www.zhihu.com/equation?tex=f_n(x)\to f(x)" alt="f_n(x)\to f(x)" class="ee_img tr_noresize" eeimg="1">
uniformly, then <img src="https://www.zhihu.com/equation?tex=(f_n(x))" alt="(f_n(x))" class="ee_img tr_noresize" eeimg="1"> is equicontinuous on <img src="https://www.zhihu.com/equation?tex=K" alt="K" class="ee_img tr_noresize" eeimg="1">.

Now we give the 'relative compactness' of a family of functions.

If <img src="https://www.zhihu.com/equation?tex=K" alt="K" class="ee_img tr_noresize" eeimg="1"> is compact, if <img src="https://www.zhihu.com/equation?tex=(f_n(x))\subset C(K)" alt="(f_n(x))\subset C(K)" class="ee_img tr_noresize" eeimg="1">, and if <img src="https://www.zhihu.com/equation?tex=(f_n(x))" alt="(f_n(x))" class="ee_img tr_noresize" eeimg="1"> is
pointwise bounded and equicontinuous on <img src="https://www.zhihu.com/equation?tex=K" alt="K" class="ee_img tr_noresize" eeimg="1">, then

1.  <img src="https://www.zhihu.com/equation?tex=(f_n(x))" alt="(f_n(x))" class="ee_img tr_noresize" eeimg="1"> is uniformly bounded on <img src="https://www.zhihu.com/equation?tex=K" alt="K" class="ee_img tr_noresize" eeimg="1">.

2.  <img src="https://www.zhihu.com/equation?tex=(f_n(x))" alt="(f_n(x))" class="ee_img tr_noresize" eeimg="1"> contains a uniformly convergent subsequence (<img src="https://www.zhihu.com/equation?tex=(f_n(x))" alt="(f_n(x))" class="ee_img tr_noresize" eeimg="1">
    is 'relative compact').

Actually, the converse is also true, and this result is Ascoli theorem.

The next topic of this section is the density subset of a continuous
function space on compact space <img src="https://www.zhihu.com/equation?tex=K" alt="K" class="ee_img tr_noresize" eeimg="1">. This result is Stone-Weierstrass
theorem.

First we show the Weierstrass' result: for a function <img src="https://www.zhihu.com/equation?tex=f\in C(K)" alt="f\in C(K)" class="ee_img tr_noresize" eeimg="1">, there
is a sequence of polynomial <img src="https://www.zhihu.com/equation?tex=(P_n)" alt="(P_n)" class="ee_img tr_noresize" eeimg="1"> that converges to <img src="https://www.zhihu.com/equation?tex=f" alt="f" class="ee_img tr_noresize" eeimg="1"> uniformly. In
other words, the space of polynomial functions on <img src="https://www.zhihu.com/equation?tex=K" alt="K" class="ee_img tr_noresize" eeimg="1"> is dense in
<img src="https://www.zhihu.com/equation?tex=C(K)" alt="C(K)" class="ee_img tr_noresize" eeimg="1">.

To generalize the Weierstrass' result, we need to isolate some
properties of the polynomials.

A family <img src="https://www.zhihu.com/equation?tex=\mathscr{A}" alt="\mathscr{A}" class="ee_img tr_noresize" eeimg="1"> of complex functions defined on a set <img src="https://www.zhihu.com/equation?tex=E" alt="E" class="ee_img tr_noresize" eeimg="1"> is said
to be an algebra if for <img src="https://www.zhihu.com/equation?tex=f, g\in\mathscr{A}" alt="f, g\in\mathscr{A}" class="ee_img tr_noresize" eeimg="1">:

1.  <img src="https://www.zhihu.com/equation?tex=f+g\in\mathscr{A}" alt="f+g\in\mathscr{A}" class="ee_img tr_noresize" eeimg="1">

2.  <img src="https://www.zhihu.com/equation?tex=fg\in\mathscr{A}" alt="fg\in\mathscr{A}" class="ee_img tr_noresize" eeimg="1">

3.  <img src="https://www.zhihu.com/equation?tex=cf\in\mathscr{A}" alt="cf\in\mathscr{A}" class="ee_img tr_noresize" eeimg="1"> for all <img src="https://www.zhihu.com/equation?tex=c\in \mathbb{C}" alt="c\in \mathbb{C}" class="ee_img tr_noresize" eeimg="1">

Let <img src="https://www.zhihu.com/equation?tex=\mathscr{A}" alt="\mathscr{A}" class="ee_img tr_noresize" eeimg="1"> be a family of functions on a set <img src="https://www.zhihu.com/equation?tex=E" alt="E" class="ee_img tr_noresize" eeimg="1">. Then
<img src="https://www.zhihu.com/equation?tex=\mathscr{A}" alt="\mathscr{A}" class="ee_img tr_noresize" eeimg="1"> is said to separate points on <img src="https://www.zhihu.com/equation?tex=E" alt="E" class="ee_img tr_noresize" eeimg="1"> if to every pair of
distinct points <img src="https://www.zhihu.com/equation?tex=x_1,x_2\in E" alt="x_1,x_2\in E" class="ee_img tr_noresize" eeimg="1">, there is a function <img src="https://www.zhihu.com/equation?tex=f\in\mathscr{A}" alt="f\in\mathscr{A}" class="ee_img tr_noresize" eeimg="1">
such that <img src="https://www.zhihu.com/equation?tex=f(x_1)\neq f(x_2)" alt="f(x_1)\neq f(x_2)" class="ee_img tr_noresize" eeimg="1">.

Let <img src="https://www.zhihu.com/equation?tex=\mathscr{A}" alt="\mathscr{A}" class="ee_img tr_noresize" eeimg="1"> be a family of functions on a set <img src="https://www.zhihu.com/equation?tex=E" alt="E" class="ee_img tr_noresize" eeimg="1">. Then
<img src="https://www.zhihu.com/equation?tex=\mathscr{A}" alt="\mathscr{A}" class="ee_img tr_noresize" eeimg="1"> vanishes at no points on <img src="https://www.zhihu.com/equation?tex=E" alt="E" class="ee_img tr_noresize" eeimg="1"> if to every point <img src="https://www.zhihu.com/equation?tex=x\in E" alt="x\in E" class="ee_img tr_noresize" eeimg="1">,
there is a function <img src="https://www.zhihu.com/equation?tex=f\in\mathscr{A}" alt="f\in\mathscr{A}" class="ee_img tr_noresize" eeimg="1"> such that <img src="https://www.zhihu.com/equation?tex=f(x)\neq 0" alt="f(x)\neq 0" class="ee_img tr_noresize" eeimg="1">.

Let <img src="https://www.zhihu.com/equation?tex=\mathscr{A}" alt="\mathscr{A}" class="ee_img tr_noresize" eeimg="1"> be a family of real functions on <img src="https://www.zhihu.com/equation?tex=\mathbb{R}" alt="\mathbb{R}" class="ee_img tr_noresize" eeimg="1">. Then
<img src="https://www.zhihu.com/equation?tex=\mathscr{A}" alt="\mathscr{A}" class="ee_img tr_noresize" eeimg="1"> is called a lattice if to every pair of functions
<img src="https://www.zhihu.com/equation?tex=f_1,f_2" alt="f_1,f_2" class="ee_img tr_noresize" eeimg="1">, <img src="https://www.zhihu.com/equation?tex=\max(f_1,f_2)" alt="\max(f_1,f_2)" class="ee_img tr_noresize" eeimg="1"> and <img src="https://www.zhihu.com/equation?tex=\min(f_1,f_2)" alt="\min(f_1,f_2)" class="ee_img tr_noresize" eeimg="1"> is in <img src="https://www.zhihu.com/equation?tex=\mathscr{A}" alt="\mathscr{A}" class="ee_img tr_noresize" eeimg="1">.

A closed subalgebra of <img src="https://www.zhihu.com/equation?tex=C(K)" alt="C(K)" class="ee_img tr_noresize" eeimg="1"> is a lattice.

Now we give the Stone's generalization of the Weierstrass theorem:

Let <img src="https://www.zhihu.com/equation?tex=\mathscr{A}" alt="\mathscr{A}" class="ee_img tr_noresize" eeimg="1"> be an algebra of real continuous functions on a
compact set <img src="https://www.zhihu.com/equation?tex=K" alt="K" class="ee_img tr_noresize" eeimg="1">. If <img src="https://www.zhihu.com/equation?tex=\mathscr{A}" alt="\mathscr{A}" class="ee_img tr_noresize" eeimg="1"> separates points on <img src="https://www.zhihu.com/equation?tex=K" alt="K" class="ee_img tr_noresize" eeimg="1"> and if
<img src="https://www.zhihu.com/equation?tex=\mathscr{A}" alt="\mathscr{A}" class="ee_img tr_noresize" eeimg="1"> vanishes at no point of <img src="https://www.zhihu.com/equation?tex=K" alt="K" class="ee_img tr_noresize" eeimg="1">, then <img src="https://www.zhihu.com/equation?tex=\mathscr{A}" alt="\mathscr{A}" class="ee_img tr_noresize" eeimg="1"> is dense
in <img src="https://www.zhihu.com/equation?tex=C(K)" alt="C(K)" class="ee_img tr_noresize" eeimg="1">.

This theorem does not hold for complex functions. We need an extra
condition on <img src="https://www.zhihu.com/equation?tex=\mathscr{A}" alt="\mathscr{A}" class="ee_img tr_noresize" eeimg="1"> for complex case: <img src="https://www.zhihu.com/equation?tex=\mathscr{A}" alt="\mathscr{A}" class="ee_img tr_noresize" eeimg="1"> is
self-adjoint. This means for every <img src="https://www.zhihu.com/equation?tex=f\in\mathscr{A}" alt="f\in\mathscr{A}" class="ee_img tr_noresize" eeimg="1">, <img src="https://www.zhihu.com/equation?tex=\bar{f}" alt="\bar{f}" class="ee_img tr_noresize" eeimg="1"> is in
<img src="https://www.zhihu.com/equation?tex=\mathscr{A}" alt="\mathscr{A}" class="ee_img tr_noresize" eeimg="1">.

Let <img src="https://www.zhihu.com/equation?tex=\mathscr{A}" alt="\mathscr{A}" class="ee_img tr_noresize" eeimg="1"> be a self-adjoint algebra of complex continuous
functions on a compact set <img src="https://www.zhihu.com/equation?tex=K" alt="K" class="ee_img tr_noresize" eeimg="1">. If <img src="https://www.zhihu.com/equation?tex=\mathscr{A}" alt="\mathscr{A}" class="ee_img tr_noresize" eeimg="1"> separates points on <img src="https://www.zhihu.com/equation?tex=K" alt="K" class="ee_img tr_noresize" eeimg="1">
and if <img src="https://www.zhihu.com/equation?tex=\mathscr{A}" alt="\mathscr{A}" class="ee_img tr_noresize" eeimg="1"> vanishes at no point of <img src="https://www.zhihu.com/equation?tex=K" alt="K" class="ee_img tr_noresize" eeimg="1">, then <img src="https://www.zhihu.com/equation?tex=\mathscr{A}" alt="\mathscr{A}" class="ee_img tr_noresize" eeimg="1"> is
dense in <img src="https://www.zhihu.com/equation?tex=C(K)" alt="C(K)" class="ee_img tr_noresize" eeimg="1">.

Some Special Functions
======================

Power series or analytic functions
----------------------------------

The analytic functions is of the form:

<img src="https://www.zhihu.com/equation?tex=f(x)=\sum_{n=0}^\infty c_n(x-a)^n\\" alt="f(x)=\sum_{n=0}^\infty c_n(x-a)^n\\" class="ee_img tr_noresize" eeimg="1">

 Although author restricts himself
to real values of <img src="https://www.zhihu.com/equation?tex=x" alt="x" class="ee_img tr_noresize" eeimg="1">, many conclusions still hold on complex values of
<img src="https://www.zhihu.com/equation?tex=x" alt="x" class="ee_img tr_noresize" eeimg="1">.

We look at some conclusions when <img src="https://www.zhihu.com/equation?tex=f(x)=\sum_{n=0}^\infty c_nx^n" alt="f(x)=\sum_{n=0}^\infty c_nx^n" class="ee_img tr_noresize" eeimg="1">
converges for <img src="https://www.zhihu.com/equation?tex=\left\lvert x\right\rvert<R" alt="\left\lvert x\right\rvert<R" class="ee_img tr_noresize" eeimg="1">:

1.  <img src="https://www.zhihu.com/equation?tex=\sum_{n=0}^\infty c_nx^n" alt="\sum_{n=0}^\infty c_nx^n" class="ee_img tr_noresize" eeimg="1"> converges uniformly on
    <img src="https://www.zhihu.com/equation?tex=\left\lvert x\right\rvert<R-\epsilon" alt="\left\lvert x\right\rvert<R-\epsilon" class="ee_img tr_noresize" eeimg="1"> (Theorem 8.1).

2.  <img src="https://www.zhihu.com/equation?tex=f(x)" alt="f(x)" class="ee_img tr_noresize" eeimg="1"> is continuous and differentiable for
    <img src="https://www.zhihu.com/equation?tex=\left\lvert x\right\rvert<R" alt="\left\lvert x\right\rvert<R" class="ee_img tr_noresize" eeimg="1">, and
    <img src="https://www.zhihu.com/equation?tex=f'(x)=\sum_{n=1}^\infty nc_nx^{n-1}" alt="f'(x)=\sum_{n=1}^\infty nc_nx^{n-1}" class="ee_img tr_noresize" eeimg="1"> for
    <img src="https://www.zhihu.com/equation?tex=\left\lvert x\right\rvert<R" alt="\left\lvert x\right\rvert<R" class="ee_img tr_noresize" eeimg="1"> (Theorem 8.1).

3.  If <img src="https://www.zhihu.com/equation?tex=f(x)" alt="f(x)" class="ee_img tr_noresize" eeimg="1"> converges at <img src="https://www.zhihu.com/equation?tex=x=R" alt="x=R" class="ee_img tr_noresize" eeimg="1">, then <img src="https://www.zhihu.com/equation?tex=f(x)" alt="f(x)" class="ee_img tr_noresize" eeimg="1"> continuous at <img src="https://www.zhihu.com/equation?tex=x=R" alt="x=R" class="ee_img tr_noresize" eeimg="1">
    (Theorem 8.2). This can be used to give another proof of formula for
    product of two series.

4.  <img src="https://www.zhihu.com/equation?tex=f(x)" alt="f(x)" class="ee_img tr_noresize" eeimg="1"> has another representation,
    <img src="https://www.zhihu.com/equation?tex=f(x)=\sum_{n=1}^\infty\frac{f^{(n)}(a)}{n!}(x-a)^n" alt="f(x)=\sum_{n=1}^\infty\frac{f^{(n)}(a)}{n!}(x-a)^n" class="ee_img tr_noresize" eeimg="1">. And it
    converges in
    <img src="https://www.zhihu.com/equation?tex=\left\lvert x-a\right\rvert<R-\left\lvert a\right\rvert" alt="\left\lvert x-a\right\rvert<R-\left\lvert a\right\rvert" class="ee_img tr_noresize" eeimg="1"> (Theorem
    8.4). Note the new representation may converge in a larger interval.
    This gives a method for analytic continuation.

If two power series converges in the same region <img src="https://www.zhihu.com/equation?tex=\Omega" alt="\Omega" class="ee_img tr_noresize" eeimg="1">, and they
coincide in some sequence of distinct points with limit point in
<img src="https://www.zhihu.com/equation?tex=\Omega" alt="\Omega" class="ee_img tr_noresize" eeimg="1">, then they coincide in region <img src="https://www.zhihu.com/equation?tex=\Omega" alt="\Omega" class="ee_img tr_noresize" eeimg="1"> (Theorem 8.5). This
theorem is particularly used to extend power series like exponential
function from <img src="https://www.zhihu.com/equation?tex=\mathbb{R}" alt="\mathbb{R}" class="ee_img tr_noresize" eeimg="1"> to <img src="https://www.zhihu.com/equation?tex=\mathbb{C}" alt="\mathbb{C}" class="ee_img tr_noresize" eeimg="1">.

Exponential, logarithmic and trigonometric functions
----------------------------------------------------

We define 
<img src="https://www.zhihu.com/equation?tex=E(x)=\sum_{n=0}^\infty \frac{z^n}{n!}\\" alt="E(x)=\sum_{n=0}^\infty \frac{z^n}{n!}\\" class="ee_img tr_noresize" eeimg="1">

 By showing
<img src="https://www.zhihu.com/equation?tex=E(z+w)=E(z)E(w)" alt="E(z+w)=E(z)E(w)" class="ee_img tr_noresize" eeimg="1"> and <img src="https://www.zhihu.com/equation?tex=E(1)=e" alt="E(1)=e" class="ee_img tr_noresize" eeimg="1">, we have <img src="https://www.zhihu.com/equation?tex=E(p)=e^p" alt="E(p)=e^p" class="ee_img tr_noresize" eeimg="1"> for all positive
rational number. Then we define <img src="https://www.zhihu.com/equation?tex=E(x)=\sup e^p" alt="E(x)=\sup e^p" class="ee_img tr_noresize" eeimg="1"> for <img src="https://www.zhihu.com/equation?tex=p<x" alt="p<x" class="ee_img tr_noresize" eeimg="1"> with
<img src="https://www.zhihu.com/equation?tex=p\in \mathbb{Q}" alt="p\in \mathbb{Q}" class="ee_img tr_noresize" eeimg="1">. Now we have <img src="https://www.zhihu.com/equation?tex=E(x)" alt="E(x)" class="ee_img tr_noresize" eeimg="1"> defined on all real number <img src="https://www.zhihu.com/equation?tex=x" alt="x" class="ee_img tr_noresize" eeimg="1">.
Using <img src="https://www.zhihu.com/equation?tex=E(z)E(-z)=E(0)=1" alt="E(z)E(-z)=E(0)=1" class="ee_img tr_noresize" eeimg="1">, we have <img src="https://www.zhihu.com/equation?tex=E(x)" alt="E(x)" class="ee_img tr_noresize" eeimg="1"> defined on <img src="https://www.zhihu.com/equation?tex=\mathbb{R}" alt="\mathbb{R}" class="ee_img tr_noresize" eeimg="1">.

The logarithm function <img src="https://www.zhihu.com/equation?tex=L(y)" alt="L(y)" class="ee_img tr_noresize" eeimg="1"> on <img src="https://www.zhihu.com/equation?tex=\mathbb{R}^+" alt="\mathbb{R}^+" class="ee_img tr_noresize" eeimg="1"> is defined by

<img src="https://www.zhihu.com/equation?tex=E(L(y))=y\\" alt="E(L(y))=y\\" class="ee_img tr_noresize" eeimg="1">

 By differentiating and integrating above equation, we have
integral formula for <img src="https://www.zhihu.com/equation?tex=L(y)" alt="L(y)" class="ee_img tr_noresize" eeimg="1">: 
<img src="https://www.zhihu.com/equation?tex=L(y)=\int_{1}^{y}\frac{dx}{x}\\" alt="L(y)=\int_{1}^{y}\frac{dx}{x}\\" class="ee_img tr_noresize" eeimg="1">



Using <img src="https://www.zhihu.com/equation?tex=x^n=E(nL(x))" alt="x^n=E(nL(x))" class="ee_img tr_noresize" eeimg="1"> and the same procedure as in exponential function,
we have <img src="https://www.zhihu.com/equation?tex=x^\alpha=e^{\alpha \log x}" alt="x^\alpha=e^{\alpha \log x}" class="ee_img tr_noresize" eeimg="1"> for all <img src="https://www.zhihu.com/equation?tex=\alpha\in \mathbb{R}" alt="\alpha\in \mathbb{R}" class="ee_img tr_noresize" eeimg="1"> and
<img src="https://www.zhihu.com/equation?tex=x\in \mathbb{R}^+" alt="x\in \mathbb{R}^+" class="ee_img tr_noresize" eeimg="1">.

The trigonometric functions are defined as:

<img src="https://www.zhihu.com/equation?tex=C(x)=\frac{1}{2}(E(ix)+E(-ix))\\" alt="C(x)=\frac{1}{2}(E(ix)+E(-ix))\\" class="ee_img tr_noresize" eeimg="1">

 and

<img src="https://www.zhihu.com/equation?tex=S(x)=\frac{1}{2i}(E(ix)-E(-ix))\\" alt="S(x)=\frac{1}{2i}(E(ix)-E(-ix))\\" class="ee_img tr_noresize" eeimg="1">



The interesting part in author's constructions is he define <img src="https://www.zhihu.com/equation?tex=\pi" alt="\pi" class="ee_img tr_noresize" eeimg="1"> as the
smallest number which make <img src="https://www.zhihu.com/equation?tex=C(\frac{\pi}{2})=0" alt="C(\frac{\pi}{2})=0" class="ee_img tr_noresize" eeimg="1">. He also shows by this
definition, <img src="https://www.zhihu.com/equation?tex=E(z+2\pi i)=E(z)" alt="E(z+2\pi i)=E(z)" class="ee_img tr_noresize" eeimg="1"> for complex <img src="https://www.zhihu.com/equation?tex=z" alt="z" class="ee_img tr_noresize" eeimg="1">. And he proves <img src="https://www.zhihu.com/equation?tex=C(x)" alt="C(x)" class="ee_img tr_noresize" eeimg="1"> and
<img src="https://www.zhihu.com/equation?tex=S(x)" alt="S(x)" class="ee_img tr_noresize" eeimg="1"> have period <img src="https://www.zhihu.com/equation?tex=2\pi" alt="2\pi" class="ee_img tr_noresize" eeimg="1">. To make his argument meaningful, he finally
shows the length of unit circle is <img src="https://www.zhihu.com/equation?tex=2\pi" alt="2\pi" class="ee_img tr_noresize" eeimg="1"> with his definition of <img src="https://www.zhihu.com/equation?tex=\pi" alt="\pi" class="ee_img tr_noresize" eeimg="1">,
and <img src="https://www.zhihu.com/equation?tex=C(x)" alt="C(x)" class="ee_img tr_noresize" eeimg="1"> and <img src="https://www.zhihu.com/equation?tex=S(x)" alt="S(x)" class="ee_img tr_noresize" eeimg="1"> are identical with usual definition of <img src="https://www.zhihu.com/equation?tex=\cos x" alt="\cos x" class="ee_img tr_noresize" eeimg="1">
and <img src="https://www.zhihu.com/equation?tex=\sin x" alt="\sin x" class="ee_img tr_noresize" eeimg="1">.

Fourier series
--------------

We define Fourier series of function <img src="https://www.zhihu.com/equation?tex=f" alt="f" class="ee_img tr_noresize" eeimg="1"> as:

<img src="https://www.zhihu.com/equation?tex=\sum_{n=-\infty}^\infty c_ne^{in x}\\" alt="\sum_{n=-\infty}^\infty c_ne^{in x}\\" class="ee_img tr_noresize" eeimg="1">

 where <img src="https://www.zhihu.com/equation?tex=c_n" alt="c_n" class="ee_img tr_noresize" eeimg="1"> called Fourier
coefficients of <img src="https://www.zhihu.com/equation?tex=f" alt="f" class="ee_img tr_noresize" eeimg="1">:

<img src="https://www.zhihu.com/equation?tex=c_n=\frac{1}{2\pi}\int_{-\pi}^{\pi}f(x)e^{-in x}dx\\" alt="c_n=\frac{1}{2\pi}\int_{-\pi}^{\pi}f(x)e^{-in x}dx\\" class="ee_img tr_noresize" eeimg="1">

 Notice
<img src="https://www.zhihu.com/equation?tex=(e^{inx})" alt="(e^{inx})" class="ee_img tr_noresize" eeimg="1"> is an orthonormal system of functions on <img src="https://www.zhihu.com/equation?tex=[-\pi,\pi]" alt="[-\pi,\pi]" class="ee_img tr_noresize" eeimg="1">.

In general, given any orthonormal system of functions <img src="https://www.zhihu.com/equation?tex=(\phi_n(x))" alt="(\phi_n(x))" class="ee_img tr_noresize" eeimg="1"> on
<img src="https://www.zhihu.com/equation?tex=[a,b]" alt="[a,b]" class="ee_img tr_noresize" eeimg="1">, consider two partial sums <img src="https://www.zhihu.com/equation?tex=s_n=\sum_{m=1}^n b_m \phi_m(x)" alt="s_n=\sum_{m=1}^n b_m \phi_m(x)" class="ee_img tr_noresize" eeimg="1"> and
<img src="https://www.zhihu.com/equation?tex=t_n=\sum_{m=1}^n \gamma_m \phi_m(x)" alt="t_n=\sum_{m=1}^n \gamma_m \phi_m(x)" class="ee_img tr_noresize" eeimg="1"> where

<img src="https://www.zhihu.com/equation?tex=b_m=\int_{a}^{b}f(x)\phi_m(x)dx\\" alt="b_m=\int_{a}^{b}f(x)\phi_m(x)dx\\" class="ee_img tr_noresize" eeimg="1">

 We have

<img src="https://www.zhihu.com/equation?tex=\int_{a}^{b}\left\lvert f-s_n\right\rvert^2dx\leq\int_{a}^{b}\left\lvert f-t_n\right\rvert^2dx\\" alt="\int_{a}^{b}\left\lvert f-s_n\right\rvert^2dx\leq\int_{a}^{b}\left\lvert f-t_n\right\rvert^2dx\\" class="ee_img tr_noresize" eeimg="1">


and equality holds if and only if <img src="https://www.zhihu.com/equation?tex=\gamma_m=c_m" alt="\gamma_m=c_m" class="ee_img tr_noresize" eeimg="1">.

From above inequality, we have Bessel inequality for all orthonormal
<img src="https://www.zhihu.com/equation?tex=(\phi_n)" alt="(\phi_n)" class="ee_img tr_noresize" eeimg="1">:

<img src="https://www.zhihu.com/equation?tex=\sum_{n=1}^\infty\left\lvert b_n\right\rvert^2\leq \int_{a}^{b}\left\lvert f(x)\right\rvert^2 dx\\" alt="\sum_{n=1}^\infty\left\lvert b_n\right\rvert^2\leq \int_{a}^{b}\left\lvert f(x)\right\rvert^2 dx\\" class="ee_img tr_noresize" eeimg="1">


and Riemann-Lebesgue lemma: <img src="https://www.zhihu.com/equation?tex=\lim c_n=0" alt="\lim c_n=0" class="ee_img tr_noresize" eeimg="1">.

Now we come back to the topic on Fourier series. First is pointwise
convergence. By Riemann-Lebesgue lemma, partial sum of Fourier series
converges to <img src="https://www.zhihu.com/equation?tex=f(x)" alt="f(x)" class="ee_img tr_noresize" eeimg="1"> at point <img src="https://www.zhihu.com/equation?tex=x" alt="x" class="ee_img tr_noresize" eeimg="1">, where
<img src="https://www.zhihu.com/equation?tex=\left\lvert f(x+t)-f(x)\right\rvert\leq M\left\lvert t\right\rvert" alt="\left\lvert f(x+t)-f(x)\right\rvert\leq M\left\lvert t\right\rvert" class="ee_img tr_noresize" eeimg="1"> for
all small enough <img src="https://www.zhihu.com/equation?tex=t" alt="t" class="ee_img tr_noresize" eeimg="1">. The second is partial sum of Fourier series of <img src="https://www.zhihu.com/equation?tex=f" alt="f" class="ee_img tr_noresize" eeimg="1">
converges uniformly to continuous <img src="https://www.zhihu.com/equation?tex=f" alt="f" class="ee_img tr_noresize" eeimg="1">. Since <img src="https://www.zhihu.com/equation?tex=(e^{inx})" alt="(e^{inx})" class="ee_img tr_noresize" eeimg="1"> is orthonormal,
this is easy by Stone-Weierstrass theorem and Bessel inequality. Finally
by uniform convergence of partial sum of Fourier series of <img src="https://www.zhihu.com/equation?tex=f" alt="f" class="ee_img tr_noresize" eeimg="1"> and
<img src="https://www.zhihu.com/equation?tex=C([-\pi,\pi])" alt="C([-\pi,\pi])" class="ee_img tr_noresize" eeimg="1"> being dense in <img src="https://www.zhihu.com/equation?tex=\mathscr{R}" alt="\mathscr{R}" class="ee_img tr_noresize" eeimg="1">, we have Parseval's
theorem:

Suppose <img src="https://www.zhihu.com/equation?tex=f" alt="f" class="ee_img tr_noresize" eeimg="1"> and <img src="https://www.zhihu.com/equation?tex=g" alt="g" class="ee_img tr_noresize" eeimg="1"> are Riemann-integrable functions with period <img src="https://www.zhihu.com/equation?tex=2\pi" alt="2\pi" class="ee_img tr_noresize" eeimg="1">,
and

<img src="https://www.zhihu.com/equation?tex=f(x)\sim \sum_{-\infty}^\infty c_n e^{inx}\quad  g(x)\sim \sum_{-\infty}^\infty \gamma_n e^{inx}\\" alt="f(x)\sim \sum_{-\infty}^\infty c_n e^{inx}\quad  g(x)\sim \sum_{-\infty}^\infty \gamma_n e^{inx}\\" class="ee_img tr_noresize" eeimg="1">


Then partial sum <img src="https://www.zhihu.com/equation?tex=\sum_{-n}^n c_n e^{inx}" alt="\sum_{-n}^n c_n e^{inx}" class="ee_img tr_noresize" eeimg="1"> converges to <img src="https://www.zhihu.com/equation?tex=f" alt="f" class="ee_img tr_noresize" eeimg="1"> in 2-norm.
And

<img src="https://www.zhihu.com/equation?tex=\frac{1}{2\pi}\int_{-\pi}^{\pi}f(x)\overline{g(x)}dx=\sum_{-\infty}^\infty c_n\bar{\gamma}_n\\" alt="\frac{1}{2\pi}\int_{-\pi}^{\pi}f(x)\overline{g(x)}dx=\sum_{-\infty}^\infty c_n\bar{\gamma}_n\\" class="ee_img tr_noresize" eeimg="1">



<img src="https://www.zhihu.com/equation?tex=\frac{1}{2\pi}\int_{-\pi}^{\pi}\left\lvert f(x)\right\rvert^2dx=\sum_{-\infty}^\infty \left\lvert c_n\right\rvert^2\\" alt="\frac{1}{2\pi}\int_{-\pi}^{\pi}\left\lvert f(x)\right\rvert^2dx=\sum_{-\infty}^\infty \left\lvert c_n\right\rvert^2\\" class="ee_img tr_noresize" eeimg="1">



The gamma function
------------------

We define gamma function as:

<img src="https://www.zhihu.com/equation?tex=\Gamma(x)=\int_{0}^{\infty}t^{x-1}e^{-t}dt\quad (0<x<\infty)\\" alt="\Gamma(x)=\int_{0}^{\infty}t^{x-1}e^{-t}dt\quad (0<x<\infty)\\" class="ee_img tr_noresize" eeimg="1">

 Gamma
function <img src="https://www.zhihu.com/equation?tex=\Gamma(x)" alt="\Gamma(x)" class="ee_img tr_noresize" eeimg="1"> has following properties and these properties
characterize <img src="https://www.zhihu.com/equation?tex=\Gamma(x)" alt="\Gamma(x)" class="ee_img tr_noresize" eeimg="1"> completely:

1.  <img src="https://www.zhihu.com/equation?tex=\Gamma(x)" alt="\Gamma(x)" class="ee_img tr_noresize" eeimg="1"> is a positive function on <img src="https://www.zhihu.com/equation?tex=(0,\infty)" alt="(0,\infty)" class="ee_img tr_noresize" eeimg="1">.

2.  <img src="https://www.zhihu.com/equation?tex=\Gamma(x+1)=x\Gamma(x)" alt="\Gamma(x+1)=x\Gamma(x)" class="ee_img tr_noresize" eeimg="1">.

3.  <img src="https://www.zhihu.com/equation?tex=\Gamma(1)=1" alt="\Gamma(1)=1" class="ee_img tr_noresize" eeimg="1">.

4.  <img src="https://www.zhihu.com/equation?tex=\log\Gamma" alt="\log\Gamma" class="ee_img tr_noresize" eeimg="1"> is convex.

This theorem is called Bohr-Mollerup theorem. From the proof of this
theorem we have the relation:

<img src="https://www.zhihu.com/equation?tex=\Gamma(x)=\lim_{n\to\infty}\frac{n!n^x}{x(x+1)\cdots(x+n)}\\" alt="\Gamma(x)=\lim_{n\to\infty}\frac{n!n^x}{x(x+1)\cdots(x+n)}\\" class="ee_img tr_noresize" eeimg="1">

 There is
also a simple approximate expression called Stirling's formula for
<img src="https://www.zhihu.com/equation?tex=\Gamma(x+1)" alt="\Gamma(x+1)" class="ee_img tr_noresize" eeimg="1"> when <img src="https://www.zhihu.com/equation?tex=x" alt="x" class="ee_img tr_noresize" eeimg="1"> is large:

<img src="https://www.zhihu.com/equation?tex=\lim_{x\to\infty}\frac{\Gamma(x+1)}{(\frac{x}{e})^x\sqrt{2\pi x}}=1\\" alt="\lim_{x\to\infty}\frac{\Gamma(x+1)}{(\frac{x}{e})^x\sqrt{2\pi x}}=1\\" class="ee_img tr_noresize" eeimg="1">



Finally we introduce beta function which is related to gamma function:

<img src="https://www.zhihu.com/equation?tex=B(x,y)=\int_{0}^{1}t^{x-1}(1-t)^{y-1}dt=\frac{\Gamma(x)\Gamma(y)}{\Gamma(x+y)}\\" alt="B(x,y)=\int_{0}^{1}t^{x-1}(1-t)^{y-1}dt=\frac{\Gamma(x)\Gamma(y)}{\Gamma(x+y)}\\" class="ee_img tr_noresize" eeimg="1">



Details of proof
----------------

A function <img src="https://www.zhihu.com/equation?tex=f" alt="f" class="ee_img tr_noresize" eeimg="1"> called convex function if
<img src="https://www.zhihu.com/equation?tex=f(\lambda x+(1-\lambda)y)\leq \lambda f(x)+(1-\lambda)f(y)" alt="f(\lambda x+(1-\lambda)y)\leq \lambda f(x)+(1-\lambda)f(y)" class="ee_img tr_noresize" eeimg="1">. We first
prove that for <img src="https://www.zhihu.com/equation?tex=x<y<z" alt="x<y<z" class="ee_img tr_noresize" eeimg="1">. Then:

<img src="https://www.zhihu.com/equation?tex=\frac{f(y)-f(x)}{y-x}\leq \frac{f(z)-f(x)}{z-x}\leq \frac{f(z)-f(y)}{z-y}\\" alt="\frac{f(y)-f(x)}{y-x}\leq \frac{f(z)-f(x)}{z-x}\leq \frac{f(z)-f(y)}{z-y}\\" class="ee_img tr_noresize" eeimg="1">


Thus <img src="https://www.zhihu.com/equation?tex=\frac{f(y)-f(x)}{y-x}\leq\frac{f(z)-f(y)}{z-y}" alt="\frac{f(y)-f(x)}{y-x}\leq\frac{f(z)-f(y)}{z-y}" class="ee_img tr_noresize" eeimg="1">.

Let <img src="https://www.zhihu.com/equation?tex=y=\lambda x+(1-\lambda)z" alt="y=\lambda x+(1-\lambda)z" class="ee_img tr_noresize" eeimg="1">. Then
<img src="https://www.zhihu.com/equation?tex=f(y)\leq \lambda f(x)+(1-\lambda)f(z)" alt="f(y)\leq \lambda f(x)+(1-\lambda)f(z)" class="ee_img tr_noresize" eeimg="1">. Now we have:

<img src="https://www.zhihu.com/equation?tex=\frac{f(y)-f(x)}{y-x}\leq \frac{\lambda f(x)+(1-\lambda)f(z)-f(x)}{\lambda x+(1-\lambda)z-x}\leq\frac{f(z)-f(x)}{z-x}\\" alt="\frac{f(y)-f(x)}{y-x}\leq \frac{\lambda f(x)+(1-\lambda)f(z)-f(x)}{\lambda x+(1-\lambda)z-x}\leq\frac{f(z)-f(x)}{z-x}\\" class="ee_img tr_noresize" eeimg="1">


and

<img src="https://www.zhihu.com/equation?tex=\frac{f(z)-f(y)}{z-y}\geq \frac{f(z)-(\lambda f(x)+(1-\lambda)f(z))}{z-(\lambda x+(1-\lambda)z)}\geq\frac{f(z)-f(x)}{z-x}\\" alt="\frac{f(z)-f(y)}{z-y}\geq \frac{f(z)-(\lambda f(x)+(1-\lambda)f(z))}{z-(\lambda x+(1-\lambda)z)}\geq\frac{f(z)-f(x)}{z-x}\\" class="ee_img tr_noresize" eeimg="1">



By above inequality,
<img src="https://www.zhihu.com/equation?tex=\log n\leq \frac{\phi(n+1+x)-\phi(n+1)}{x}\leq \log (n+1)" alt="\log n\leq \frac{\phi(n+1+x)-\phi(n+1)}{x}\leq \log (n+1)" class="ee_img tr_noresize" eeimg="1"> holds.

For fixed <img src="https://www.zhihu.com/equation?tex=y" alt="y" class="ee_img tr_noresize" eeimg="1">: 
<img src="https://www.zhihu.com/equation?tex=\begin{aligned}
        B(\frac{x_1}{p}+\frac{x_2}{q},y)=&\int_{0}^{1}t^{\frac{x_1-1}{p}+\frac{x_2-1}{q}}(1-t)^{y-1}dt\\
        =&\int_{0}^{1}t^{\frac{x_1-1}{p}}(1-t)^\frac{y-1}{p}t^{\frac{x_2-1}{q}}(1-t)^\frac{y-1}{q}dt
    \end{aligned}\\" alt="\begin{aligned}
        B(\frac{x_1}{p}+\frac{x_2}{q},y)=&\int_{0}^{1}t^{\frac{x_1-1}{p}+\frac{x_2-1}{q}}(1-t)^{y-1}dt\\
        =&\int_{0}^{1}t^{\frac{x_1-1}{p}}(1-t)^\frac{y-1}{p}t^{\frac{x_2-1}{q}}(1-t)^\frac{y-1}{q}dt
    \end{aligned}\\" class="ee_img tr_noresize" eeimg="1">

 Using Holder's inequality, we show <img src="https://www.zhihu.com/equation?tex=\log B(x,y)" alt="\log B(x,y)" class="ee_img tr_noresize" eeimg="1"> is
convex for fixed <img src="https://www.zhihu.com/equation?tex=y" alt="y" class="ee_img tr_noresize" eeimg="1">.
