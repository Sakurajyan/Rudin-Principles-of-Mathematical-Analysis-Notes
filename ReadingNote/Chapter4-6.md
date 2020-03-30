Continuity
==========

We can define the limit under a function <img src="https://www.zhihu.com/equation?tex=\lim_{x\to p}f(x)=q" alt="\lim_{x\to p}f(x)=q" class="ee_img tr_noresize" eeimg="1"> either
using neighborhood language:

<img src="https://www.zhihu.com/equation?tex=\forall \epsilon>0, \exists \delta>0, 0<d_X(x,p)<\delta \Rightarrow d_Y(f(x)-q)<\epsilon\\" alt="\forall \epsilon>0, \exists \delta>0, 0<d_X(x,p)<\delta \Rightarrow d_Y(f(x)-q)<\epsilon\\" class="ee_img tr_noresize" eeimg="1">


or sequence language:

<img src="https://www.zhihu.com/equation?tex=\lim_{n\to\infty}f(p_n)=q \quad \forall (p_n)~s.t.~p_n\neq p, \lim_{n\to\infty}p_n=p\\" alt="\lim_{n\to\infty}f(p_n)=q \quad \forall (p_n)~s.t.~p_n\neq p, \lim_{n\to\infty}p_n=p\\" class="ee_img tr_noresize" eeimg="1">


. This limit operation (or we can call it topological operation), is
communitive with arithmetic operation on function like addition and
multiplication. If we give the value of function at the limit point, we
can talk about continuous functions. Notice if point <img src="https://www.zhihu.com/equation?tex=p" alt="p" class="ee_img tr_noresize" eeimg="1"> is an isolated
point, every function is continuous at <img src="https://www.zhihu.com/equation?tex=p" alt="p" class="ee_img tr_noresize" eeimg="1"> by definition.

There are some equivalent characterizations of continuous function:

1.  <img src="https://www.zhihu.com/equation?tex=f" alt="f" class="ee_img tr_noresize" eeimg="1"> is continuous.

2.  For every subset <img src="https://www.zhihu.com/equation?tex=A" alt="A" class="ee_img tr_noresize" eeimg="1">, one has <img src="https://www.zhihu.com/equation?tex=f(\bar{A})\subset\overline{f(A)}" alt="f(\bar{A})\subset\overline{f(A)}" class="ee_img tr_noresize" eeimg="1">.

3.  For every open subset <img src="https://www.zhihu.com/equation?tex=V" alt="V" class="ee_img tr_noresize" eeimg="1">, <img src="https://www.zhihu.com/equation?tex=f^{-1}(V)" alt="f^{-1}(V)" class="ee_img tr_noresize" eeimg="1"> is open.

4.  For every closed subset <img src="https://www.zhihu.com/equation?tex=V" alt="V" class="ee_img tr_noresize" eeimg="1">, <img src="https://www.zhihu.com/equation?tex=f^{-1}(V)" alt="f^{-1}(V)" class="ee_img tr_noresize" eeimg="1"> is closed.

By above characterizations, we can easily prove that the composition of
continuous functions are continuous function. Also,addition and
multiplication preserves continuity by properties of limit operation.

Recall we have two identity: <img src="https://www.zhihu.com/equation?tex=f(f^{-1}(E))\subset E" alt="f(f^{-1}(E))\subset E" class="ee_img tr_noresize" eeimg="1"> and
<img src="https://www.zhihu.com/equation?tex=f^{-1}(f(E))\supset E" alt="f^{-1}(f(E))\supset E" class="ee_img tr_noresize" eeimg="1">. This is useful when prove continuous function
maps compact set to compact set. By the compact of image and least upper
bound property of <img src="https://www.zhihu.com/equation?tex=\mathbb{R}^1" alt="\mathbb{R}^1" class="ee_img tr_noresize" eeimg="1">, <img src="https://www.zhihu.com/equation?tex=f" alt="f" class="ee_img tr_noresize" eeimg="1"> can attain the maximum and minimum
value. Also, a continuous map from compact metric space to another
metric space is a homeomorphism (continuous bijection with continuous
inversion).

The first inclusion is equality if <img src="https://www.zhihu.com/equation?tex=f" alt="f" class="ee_img tr_noresize" eeimg="1"> is surjective and the second
inclusion is equality if <img src="https://www.zhihu.com/equation?tex=f" alt="f" class="ee_img tr_noresize" eeimg="1"> is injective.

The counterexample for <img src="https://www.zhihu.com/equation?tex=E" alt="E" class="ee_img tr_noresize" eeimg="1"> not compact on <img src="https://www.zhihu.com/equation?tex=\mathbb{R}^1" alt="\mathbb{R}^1" class="ee_img tr_noresize" eeimg="1"> (not closed or
not bounded) is interesting (Theorem 4.20)

1.  Continuous function but not bounded on a bounded set <img src="https://www.zhihu.com/equation?tex=E" alt="E" class="ee_img tr_noresize" eeimg="1"> (hence <img src="https://www.zhihu.com/equation?tex=E" alt="E" class="ee_img tr_noresize" eeimg="1">
    is not closed): <img src="https://www.zhihu.com/equation?tex=f(x)=\frac{1}{x-x_0}" alt="f(x)=\frac{1}{x-x_0}" class="ee_img tr_noresize" eeimg="1"> with <img src="https://www.zhihu.com/equation?tex=x_0" alt="x_0" class="ee_img tr_noresize" eeimg="1"> is a limit point
    not in <img src="https://www.zhihu.com/equation?tex=E" alt="E" class="ee_img tr_noresize" eeimg="1">.

2.  Continuous function but not uniformly continuous on a bounded set
    <img src="https://www.zhihu.com/equation?tex=E" alt="E" class="ee_img tr_noresize" eeimg="1"> (hence <img src="https://www.zhihu.com/equation?tex=E" alt="E" class="ee_img tr_noresize" eeimg="1"> is not closed): <img src="https://www.zhihu.com/equation?tex=f(x)=\frac{1}{x-x_0}" alt="f(x)=\frac{1}{x-x_0}" class="ee_img tr_noresize" eeimg="1"> with <img src="https://www.zhihu.com/equation?tex=x_0" alt="x_0" class="ee_img tr_noresize" eeimg="1"> is
    a limit point not in <img src="https://www.zhihu.com/equation?tex=E" alt="E" class="ee_img tr_noresize" eeimg="1">.

3.  Continuous function but not attained maximum on bounded set <img src="https://www.zhihu.com/equation?tex=E" alt="E" class="ee_img tr_noresize" eeimg="1">
    (hence <img src="https://www.zhihu.com/equation?tex=E" alt="E" class="ee_img tr_noresize" eeimg="1"> is not closed): <img src="https://www.zhihu.com/equation?tex=g(x)\frac{1}{1+(x-x_0)^2}" alt="g(x)\frac{1}{1+(x-x_0)^2}" class="ee_img tr_noresize" eeimg="1"> with <img src="https://www.zhihu.com/equation?tex=x_0" alt="x_0" class="ee_img tr_noresize" eeimg="1"> is
    a limit point not in <img src="https://www.zhihu.com/equation?tex=E" alt="E" class="ee_img tr_noresize" eeimg="1">.

4.  For a non-bounded set <img src="https://www.zhihu.com/equation?tex=E" alt="E" class="ee_img tr_noresize" eeimg="1">, <img src="https://www.zhihu.com/equation?tex=f(x)=x" alt="f(x)=x" class="ee_img tr_noresize" eeimg="1"> and <img src="https://www.zhihu.com/equation?tex=h(x)=\frac{x^2}{1+x^2}" alt="h(x)=\frac{x^2}{1+x^2}" class="ee_img tr_noresize" eeimg="1"> are
    counterexample for boundedness and maximum. But there is no example
    for uniformly continuous for any non compact and unbounded set <img src="https://www.zhihu.com/equation?tex=E" alt="E" class="ee_img tr_noresize" eeimg="1">.
    Indeed, if <img src="https://www.zhihu.com/equation?tex=E" alt="E" class="ee_img tr_noresize" eeimg="1"> is the set of all integers, any function on <img src="https://www.zhihu.com/equation?tex=E" alt="E" class="ee_img tr_noresize" eeimg="1"> is
    uniformly continuous.

If <img src="https://www.zhihu.com/equation?tex=E" alt="E" class="ee_img tr_noresize" eeimg="1"> is not compact. there is example, a function <img src="https://www.zhihu.com/equation?tex=f" alt="f" class="ee_img tr_noresize" eeimg="1"> is not a
homeomorphism even if <img src="https://www.zhihu.com/equation?tex=f" alt="f" class="ee_img tr_noresize" eeimg="1"> is bijective and continuous and <img src="https://www.zhihu.com/equation?tex=f(E)" alt="f(E)" class="ee_img tr_noresize" eeimg="1"> is
compact (<img src="https://www.zhihu.com/equation?tex=f(x)=(\cos x,\sin x)" alt="f(x)=(\cos x,\sin x)" class="ee_img tr_noresize" eeimg="1">).

Another topological property related to continuous function is
continuous function maps connected set to connected set. One consequence
of this property is intermediate values theorem. However, intermediate
value property does not implies continuous (<img src="https://www.zhihu.com/equation?tex=\sin \frac{1}{x}" alt="\sin \frac{1}{x}" class="ee_img tr_noresize" eeimg="1"> with <img src="https://www.zhihu.com/equation?tex=0" alt="0" class="ee_img tr_noresize" eeimg="1">
at <img src="https://www.zhihu.com/equation?tex=x=0" alt="x=0" class="ee_img tr_noresize" eeimg="1">).

Monotonic functions has many good properties. The right and left limit
of points always exist (Theorem 4.29). In proof of Theorem 4.29, we show
for any <img src="https://www.zhihu.com/equation?tex=\epsilon>0" alt="\epsilon>0" class="ee_img tr_noresize" eeimg="1">, there exists <img src="https://www.zhihu.com/equation?tex=\delta>0" alt="\delta>0" class="ee_img tr_noresize" eeimg="1"> s.t.
<img src="https://www.zhihu.com/equation?tex=\left\lvert f(t)-A\right\rvert<\epsilon" alt="\left\lvert f(t)-A\right\rvert<\epsilon" class="ee_img tr_noresize" eeimg="1"> with <img src="https://www.zhihu.com/equation?tex=x-\delta<t<x" alt="x-\delta<t<x" class="ee_img tr_noresize" eeimg="1">. However,
no hint shows the <img src="https://www.zhihu.com/equation?tex=\delta" alt="\delta" class="ee_img tr_noresize" eeimg="1"> tends to <img src="https://www.zhihu.com/equation?tex=0" alt="0" class="ee_img tr_noresize" eeimg="1">. But if
<img src="https://www.zhihu.com/equation?tex=(t_n)\subset (x-\delta,x)" alt="(t_n)\subset (x-\delta,x)" class="ee_img tr_noresize" eeimg="1">, then
<img src="https://www.zhihu.com/equation?tex=A-\epsilon<\liminf f(t_n)\leq \limsup f(t_n)<A+\epsilon" alt="A-\epsilon<\liminf f(t_n)\leq \limsup f(t_n)<A+\epsilon" class="ee_img tr_noresize" eeimg="1">. Thus for any
converge sequence <img src="https://www.zhihu.com/equation?tex=(t_n)" alt="(t_n)" class="ee_img tr_noresize" eeimg="1"> less than <img src="https://www.zhihu.com/equation?tex=x" alt="x" class="ee_img tr_noresize" eeimg="1">,
<img src="https://www.zhihu.com/equation?tex=A-\epsilon<\lim (f_n)<A+\epsilon" alt="A-\epsilon<\lim (f_n)<A+\epsilon" class="ee_img tr_noresize" eeimg="1">. Hence <img src="https://www.zhihu.com/equation?tex=f(x-)=A" alt="f(x-)=A" class="ee_img tr_noresize" eeimg="1">.

An interesting example for monotonic function is in Remark 4.31. It
construct a monotonic function with countable discontinuous point s
which is dense in <img src="https://www.zhihu.com/equation?tex=(a,b)" alt="(a,b)" class="ee_img tr_noresize" eeimg="1">. The construction is by an absolutely
convergent series and all rationals less than a particular value <img src="https://www.zhihu.com/equation?tex=x" alt="x" class="ee_img tr_noresize" eeimg="1">.
Formally: 
<img src="https://www.zhihu.com/equation?tex=f(x)=\sum_{x_n<x}c_n\\" alt="f(x)=\sum_{x_n<x}c_n\\" class="ee_img tr_noresize" eeimg="1">

 where <img src="https://www.zhihu.com/equation?tex=\sum c_n" alt="\sum c_n" class="ee_img tr_noresize" eeimg="1"> converges
absolutely. The function constructed can be either left continuous or
right continuous.

Differentiation
===============

The steps for introducing differentiation is same as for continuity:

1.  definition, notice the derivative of end points are left (right)
    derivative:
    
<img src="https://www.zhihu.com/equation?tex=f'(x)=\lim_{t\to x}\frac{f(t)-f(x)}{t-x}\quad t\neq x\\" alt="f'(x)=\lim_{t\to x}\frac{f(t)-f(x)}{t-x}\quad t\neq x\\" class="ee_img tr_noresize" eeimg="1">



2.  arithmetic operation under differentiation, like addition,
    multiplication and division.

3.  composition under differentiation: <img src="https://www.zhihu.com/equation?tex=(f\circ g(y))'=f'(g(y))g'(y)" alt="(f\circ g(y))'=f'(g(y))g'(y)" class="ee_img tr_noresize" eeimg="1">.

Next we talk about mean value theorem. The frequently used form is

<img src="https://www.zhihu.com/equation?tex=f(b)-f(a)=(b-a)f'(x) \quad x\in (a,b)\\" alt="f(b)-f(a)=(b-a)f'(x) \quad x\in (a,b)\\" class="ee_img tr_noresize" eeimg="1">

 There is also an intermediate
value theorem for derivative of <img src="https://www.zhihu.com/equation?tex=f" alt="f" class="ee_img tr_noresize" eeimg="1">. But we need not assume the
continuity for derivative. The proof is by construct function
<img src="https://www.zhihu.com/equation?tex=g(x)=f(x)-\lambda x" alt="g(x)=f(x)-\lambda x" class="ee_img tr_noresize" eeimg="1"> and shows there is a maximum (minimum) value for
<img src="https://www.zhihu.com/equation?tex=g(x)" alt="g(x)" class="ee_img tr_noresize" eeimg="1"> and thus <img src="https://www.zhihu.com/equation?tex=g'(x)=0" alt="g'(x)=0" class="ee_img tr_noresize" eeimg="1">. Notice by definition of derivative, <img src="https://www.zhihu.com/equation?tex=g'(a)<0" alt="g'(a)<0" class="ee_img tr_noresize" eeimg="1">
implies <img src="https://www.zhihu.com/equation?tex=g(x_1)<g(a)" alt="g(x_1)<g(a)" class="ee_img tr_noresize" eeimg="1"> for some <img src="https://www.zhihu.com/equation?tex=a<x_1<b" alt="a<x_1<b" class="ee_img tr_noresize" eeimg="1">. An consequence of this
intermediate value theorem is that <img src="https://www.zhihu.com/equation?tex=f'" alt="f'" class="ee_img tr_noresize" eeimg="1"> cannot have any simple
discontinuities.

The proof of L'Hospital's rule uses density of <img src="https://www.zhihu.com/equation?tex=\mathbb{R}" alt="\mathbb{R}" class="ee_img tr_noresize" eeimg="1"> a lot.
Notice to apply L'Hospital's rule, one of following condition needs to
be satisfied:

1.  <img src="https://www.zhihu.com/equation?tex=f(x)\to 0" alt="f(x)\to 0" class="ee_img tr_noresize" eeimg="1"> and <img src="https://www.zhihu.com/equation?tex=g(x)=0" alt="g(x)=0" class="ee_img tr_noresize" eeimg="1"> as <img src="https://www.zhihu.com/equation?tex=x\to a" alt="x\to a" class="ee_img tr_noresize" eeimg="1">

2.  <img src="https://www.zhihu.com/equation?tex=g(x)\to +\infty" alt="g(x)\to +\infty" class="ee_img tr_noresize" eeimg="1"> or <img src="https://www.zhihu.com/equation?tex=g(x)\to -\infty" alt="g(x)\to -\infty" class="ee_img tr_noresize" eeimg="1"> as <img src="https://www.zhihu.com/equation?tex=x\to a" alt="x\to a" class="ee_img tr_noresize" eeimg="1">

In the end of this chapter we talk about higher order derivative and
Taylor's theorem. To make <img src="https://www.zhihu.com/equation?tex=f^{(n)(x)}" alt="f^{(n)(x)}" class="ee_img tr_noresize" eeimg="1"> exists at <img src="https://www.zhihu.com/equation?tex=x" alt="x" class="ee_img tr_noresize" eeimg="1">. <img src="https://www.zhihu.com/equation?tex=f^{(n-1)}(x)" alt="f^{(n-1)}(x)" class="ee_img tr_noresize" eeimg="1">
must exist in a neighborhood of <img src="https://www.zhihu.com/equation?tex=x" alt="x" class="ee_img tr_noresize" eeimg="1">. And to make proceeding statement
true, <img src="https://www.zhihu.com/equation?tex=f^{(n-2)}(x)" alt="f^{(n-2)}(x)" class="ee_img tr_noresize" eeimg="1"> must be differentiable in that neighborhood.

For vector-valued functions, the derivative exists if the norm of
different between quotient and a value tends to 0:

<img src="https://www.zhihu.com/equation?tex=\lim_{t\to x}\left\lvert\frac{\mathbf{f}(t)-\mathbf{f}(x)}{t-x}-\mathbf{f}'(x)\right\rvert=0\\" alt="\lim_{t\to x}\left\lvert\frac{\mathbf{f}(t)-\mathbf{f}(x)}{t-x}-\mathbf{f}'(x)\right\rvert=0\\" class="ee_img tr_noresize" eeimg="1">


The arithmetic operation under differentiation still holds. But the mean
value theorem and L'Hospital's rule fails. However, a mean value
inequality holds for vector-valued functions:
<img src="https://www.zhihu.com/equation?tex=\left\lvert\mathbf{f}(b)-\mathbf{f}(a)\right\rvert\leq (b-a)\left\lvert\mathbf{f}'(x)\right\rvert" alt="\left\lvert\mathbf{f}(b)-\mathbf{f}(a)\right\rvert\leq (b-a)\left\lvert\mathbf{f}'(x)\right\rvert" class="ee_img tr_noresize" eeimg="1">

Notes and Errata
----------------

We give analogous proof for <img src="https://www.zhihu.com/equation?tex=g(x)\to -\infty" alt="g(x)\to -\infty" class="ee_img tr_noresize" eeimg="1"> as <img src="https://www.zhihu.com/equation?tex=x\to a" alt="x\to a" class="ee_img tr_noresize" eeimg="1">.

We already have:

1.  There is a point <img src="https://www.zhihu.com/equation?tex=c\in(a,b)" alt="c\in(a,b)" class="ee_img tr_noresize" eeimg="1">, s.t. <img src="https://www.zhihu.com/equation?tex=\frac{f'(x)}{g'(x)}<r" alt="\frac{f'(x)}{g'(x)}<r" class="ee_img tr_noresize" eeimg="1"> for all
    <img src="https://www.zhihu.com/equation?tex=x\in (a,c)" alt="x\in (a,c)" class="ee_img tr_noresize" eeimg="1">.

2.  If <img src="https://www.zhihu.com/equation?tex=a<x<y<c" alt="a<x<y<c" class="ee_img tr_noresize" eeimg="1">, then there is a point <img src="https://www.zhihu.com/equation?tex=t\in(x,y)" alt="t\in(x,y)" class="ee_img tr_noresize" eeimg="1"> s.t.
    <img src="https://www.zhihu.com/equation?tex=\frac{f(x)-f(y)}{g(x)-g(y)}=\frac{f'(t)}{g'(t)}" alt="\frac{f(x)-f(y)}{g(x)-g(y)}=\frac{f'(t)}{g'(t)}" class="ee_img tr_noresize" eeimg="1"> and by above
    statement, <img src="https://www.zhihu.com/equation?tex=\frac{f(x)-f(y)}{g(x)-g(y)}<r" alt="\frac{f(x)-f(y)}{g(x)-g(y)}<r" class="ee_img tr_noresize" eeimg="1">.

Now suppose <img src="https://www.zhihu.com/equation?tex=g(x)\to -\infty" alt="g(x)\to -\infty" class="ee_img tr_noresize" eeimg="1"> as <img src="https://www.zhihu.com/equation?tex=x\to a" alt="x\to a" class="ee_img tr_noresize" eeimg="1">. We can choose a point
<img src="https://www.zhihu.com/equation?tex=c_1\in(a,y)" alt="c_1\in(a,y)" class="ee_img tr_noresize" eeimg="1"> s.t. <img src="https://www.zhihu.com/equation?tex=g(x)<g(y)" alt="g(x)<g(y)" class="ee_img tr_noresize" eeimg="1"> and <img src="https://www.zhihu.com/equation?tex=g(x)<0" alt="g(x)<0" class="ee_img tr_noresize" eeimg="1"> if <img src="https://www.zhihu.com/equation?tex=a<x<c_1" alt="a<x<c_1" class="ee_img tr_noresize" eeimg="1">. Thus
<img src="https://www.zhihu.com/equation?tex=\frac{f(x)-g(y)}{g(x)}>0" alt="\frac{f(x)-g(y)}{g(x)}>0" class="ee_img tr_noresize" eeimg="1"> and the following steps are the same as in
this book.

The Riemann-Stieltjes Integral
==============================

The definition of Riemann Integral is based on partition <img src="https://www.zhihu.com/equation?tex=P" alt="P" class="ee_img tr_noresize" eeimg="1"> of interval
<img src="https://www.zhihu.com/equation?tex=[a,b]" alt="[a,b]" class="ee_img tr_noresize" eeimg="1">. When upper and lower Riemann integral meets, we say the Riemann
integral exists. There is an important criterion of existence of Riemann
integral, but we postpone it until we talk about Lebesgue integral.

Given a monotonically increasing function <img src="https://www.zhihu.com/equation?tex=\alpha(x)" alt="\alpha(x)" class="ee_img tr_noresize" eeimg="1">, if we use the
increment value <img src="https://www.zhihu.com/equation?tex=\alpha(x_i)-\alpha(x_{i+1})" alt="\alpha(x_i)-\alpha(x_{i+1})" class="ee_img tr_noresize" eeimg="1"> between two points <img src="https://www.zhihu.com/equation?tex=x_i" alt="x_i" class="ee_img tr_noresize" eeimg="1">
and <img src="https://www.zhihu.com/equation?tex=x_{i+1}" alt="x_{i+1}" class="ee_img tr_noresize" eeimg="1"> instead of the difference <img src="https://www.zhihu.com/equation?tex=x_{i+1}-x_i" alt="x_{i+1}-x_i" class="ee_img tr_noresize" eeimg="1">, we can define
Riemann-Stieltjes integral similarly.

Now we give a criterion of existence of Riemann integral.

[\[thm: theorem 6.6\]]{#thm: theorem 6.6 label="thm: theorem 6.6"}
<img src="https://www.zhihu.com/equation?tex=f\in\mathscr{R}(\alpha)" alt="f\in\mathscr{R}(\alpha)" class="ee_img tr_noresize" eeimg="1"> on <img src="https://www.zhihu.com/equation?tex=[a,b]" alt="[a,b]" class="ee_img tr_noresize" eeimg="1"> if and only if for every
<img src="https://www.zhihu.com/equation?tex=\epsilon>0" alt="\epsilon>0" class="ee_img tr_noresize" eeimg="1"> there is a partition <img src="https://www.zhihu.com/equation?tex=P" alt="P" class="ee_img tr_noresize" eeimg="1"> such that

<img src="https://www.zhihu.com/equation?tex=U(P,f,\alpha)-L(P,f,\alpha)<\epsilon\\" alt="U(P,f,\alpha)-L(P,f,\alpha)<\epsilon\\" class="ee_img tr_noresize" eeimg="1">



By theorem
[\[thm: theorem 6.6\]](#thm: theorem 6.6){reference-type="ref"
reference="thm: theorem 6.6"}, we can show the following functions are
R-S integrable.

1.  <img src="https://www.zhihu.com/equation?tex=f" alt="f" class="ee_img tr_noresize" eeimg="1"> is continuous on <img src="https://www.zhihu.com/equation?tex=[a,b]" alt="[a,b]" class="ee_img tr_noresize" eeimg="1">

2.  <img src="https://www.zhihu.com/equation?tex=f" alt="f" class="ee_img tr_noresize" eeimg="1"> is monotonic on <img src="https://www.zhihu.com/equation?tex=[a,b]" alt="[a,b]" class="ee_img tr_noresize" eeimg="1"> and <img src="https://www.zhihu.com/equation?tex=\alpha" alt="\alpha" class="ee_img tr_noresize" eeimg="1"> is continuous on <img src="https://www.zhihu.com/equation?tex=[a,b]" alt="[a,b]" class="ee_img tr_noresize" eeimg="1">

3.  <img src="https://www.zhihu.com/equation?tex=f" alt="f" class="ee_img tr_noresize" eeimg="1"> is bounded on <img src="https://www.zhihu.com/equation?tex=[a,b]" alt="[a,b]" class="ee_img tr_noresize" eeimg="1">, f has only finitely many points of
    discontinuity on <img src="https://www.zhihu.com/equation?tex=[a,b]" alt="[a,b]" class="ee_img tr_noresize" eeimg="1"> and <img src="https://www.zhihu.com/equation?tex=\alpha" alt="\alpha" class="ee_img tr_noresize" eeimg="1"> is continuous at every point
    at which f is discontinuous.

4.  <img src="https://www.zhihu.com/equation?tex=f=\phi(g)" alt="f=\phi(g)" class="ee_img tr_noresize" eeimg="1"> where <img src="https://www.zhihu.com/equation?tex=\phi" alt="\phi" class="ee_img tr_noresize" eeimg="1"> is continuous and <img src="https://www.zhihu.com/equation?tex=g" alt="g" class="ee_img tr_noresize" eeimg="1"> is R-S integrable.

Just like continuity and differentiation, there are some arithmetic
properties of R-S integral, like addition, scalar multiplication and
multiplication, and there are some basic inequalities involve R-S
integration (theorem 6.12 and theorem 6.13). But we do not mention them
here.

Stieltjes process is somewhat more flexibility than original Riemann
integral: If <img src="https://www.zhihu.com/equation?tex=\alpha(x)" alt="\alpha(x)" class="ee_img tr_noresize" eeimg="1"> is a pure step function, then the integral
reduces to a finite or infinite series. If <img src="https://www.zhihu.com/equation?tex=\alpha(x)" alt="\alpha(x)" class="ee_img tr_noresize" eeimg="1"> has an integrable
derivative, i.e., <img src="https://www.zhihu.com/equation?tex=\alpha'(x)\in\mathscr{R}" alt="\alpha'(x)\in\mathscr{R}" class="ee_img tr_noresize" eeimg="1">, then the R-S integral
reduces to an ordinary Riemann integral.

The final important theorem for R-S integral is change of variable:

Suppose <img src="https://www.zhihu.com/equation?tex=\phi" alt="\phi" class="ee_img tr_noresize" eeimg="1"> is a strictly increasing continuous function that maps an
interval <img src="https://www.zhihu.com/equation?tex=[A,B]" alt="[A,B]" class="ee_img tr_noresize" eeimg="1"> onto <img src="https://www.zhihu.com/equation?tex=[a,b]" alt="[a,b]" class="ee_img tr_noresize" eeimg="1">. Suppose <img src="https://www.zhihu.com/equation?tex=\alpha" alt="\alpha" class="ee_img tr_noresize" eeimg="1"> is monotonically
increasing on <img src="https://www.zhihu.com/equation?tex=[a,b]" alt="[a,b]" class="ee_img tr_noresize" eeimg="1"> and <img src="https://www.zhihu.com/equation?tex=f\in\mathscr{R}(\alpha)" alt="f\in\mathscr{R}(\alpha)" class="ee_img tr_noresize" eeimg="1"> on <img src="https://www.zhihu.com/equation?tex=[a,b]" alt="[a,b]" class="ee_img tr_noresize" eeimg="1">. Define
<img src="https://www.zhihu.com/equation?tex=\beta(y)=\alpha(\phi(y))" alt="\beta(y)=\alpha(\phi(y))" class="ee_img tr_noresize" eeimg="1"> and <img src="https://www.zhihu.com/equation?tex=g(y)=f(\phi(y))" alt="g(y)=f(\phi(y))" class="ee_img tr_noresize" eeimg="1">. Then
<img src="https://www.zhihu.com/equation?tex=g\in\mathscr{R}(\beta)" alt="g\in\mathscr{R}(\beta)" class="ee_img tr_noresize" eeimg="1"> and

<img src="https://www.zhihu.com/equation?tex=\int_{A}^{B}g d\beta=\int_{a}^{b}f d\alpha\\" alt="\int_{A}^{B}g d\beta=\int_{a}^{b}f d\alpha\\" class="ee_img tr_noresize" eeimg="1">



Take <img src="https://www.zhihu.com/equation?tex=\alpha(x)=x" alt="\alpha(x)=x" class="ee_img tr_noresize" eeimg="1"> and assume <img src="https://www.zhihu.com/equation?tex=\phi'\in\mathscr{R}" alt="\phi'\in\mathscr{R}" class="ee_img tr_noresize" eeimg="1">. Then

<img src="https://www.zhihu.com/equation?tex=\int_{a}^{b}f(x) dx=\int_{A}^{B}f(\phi(y))\phi'(y)dy\\" alt="\int_{a}^{b}f(x) dx=\int_{A}^{B}f(\phi(y))\phi'(y)dy\\" class="ee_img tr_noresize" eeimg="1">

 Now we talk
about connection between integration and differentiation. Let

<img src="https://www.zhihu.com/equation?tex=F(x)=\int_{a}^{x}f(t)dt\\" alt="F(x)=\int_{a}^{x}f(t)dt\\" class="ee_img tr_noresize" eeimg="1">

 Then <img src="https://www.zhihu.com/equation?tex=F(x)" alt="F(x)" class="ee_img tr_noresize" eeimg="1"> is continuous. Furthermore,
<img src="https://www.zhihu.com/equation?tex=F(x)" alt="F(x)" class="ee_img tr_noresize" eeimg="1"> is differentiable at <img src="https://www.zhihu.com/equation?tex=x_0" alt="x_0" class="ee_img tr_noresize" eeimg="1"> which is continuous point of <img src="https://www.zhihu.com/equation?tex=f(x)" alt="f(x)" class="ee_img tr_noresize" eeimg="1">.
<img src="https://www.zhihu.com/equation?tex=F'(x_0)=f(x_0)" alt="F'(x_0)=f(x_0)" class="ee_img tr_noresize" eeimg="1">.

If we assume <img src="https://www.zhihu.com/equation?tex=F(x)" alt="F(x)" class="ee_img tr_noresize" eeimg="1"> is differentiable and <img src="https://www.zhihu.com/equation?tex=F'(x)=f(x)" alt="F'(x)=f(x)" class="ee_img tr_noresize" eeimg="1"> then the
fundamental theorem of calculus and integration by parts hold.

Finally we talk about R-S integral of vector-valued functions and
rectifiable curves. Many analogues of theorems for R-S integral holds
for vector-valued functions. We call a continuous mapping <img src="https://www.zhihu.com/equation?tex=\gamma" alt="\gamma" class="ee_img tr_noresize" eeimg="1"> of an
interval <img src="https://www.zhihu.com/equation?tex=[a,b]" alt="[a,b]" class="ee_img tr_noresize" eeimg="1"> into <img src="https://www.zhihu.com/equation?tex=\mathbb{R}^n" alt="\mathbb{R}^n" class="ee_img tr_noresize" eeimg="1"> a curve in <img src="https://www.zhihu.com/equation?tex=\mathbb{R}^n" alt="\mathbb{R}^n" class="ee_img tr_noresize" eeimg="1">. By
partition, we can define the length of <img src="https://www.zhihu.com/equation?tex=\gamma" alt="\gamma" class="ee_img tr_noresize" eeimg="1">:

<img src="https://www.zhihu.com/equation?tex=\Lambda(\gamma)=\sup\Lambda(P,\gamma)=\sup \sum_{i=1}^n\left\lvert\gamma(x_i)-\gamma(x_{i-1})\right\rvert\\" alt="\Lambda(\gamma)=\sup\Lambda(P,\gamma)=\sup \sum_{i=1}^n\left\lvert\gamma(x_i)-\gamma(x_{i-1})\right\rvert\\" class="ee_img tr_noresize" eeimg="1">


If <img src="https://www.zhihu.com/equation?tex=\Lambda(\gamma)<\infty" alt="\Lambda(\gamma)<\infty" class="ee_img tr_noresize" eeimg="1">, we say that <img src="https://www.zhihu.com/equation?tex=\gamma" alt="\gamma" class="ee_img tr_noresize" eeimg="1"> is rectifiable. For
continuously differentiable curves <img src="https://www.zhihu.com/equation?tex=\gamma" alt="\gamma" class="ee_img tr_noresize" eeimg="1">. Then length of <img src="https://www.zhihu.com/equation?tex=\gamma" alt="\gamma" class="ee_img tr_noresize" eeimg="1"> can
be given as Riemann integral:

<img src="https://www.zhihu.com/equation?tex=\Lambda(\gamma)=\int_{a}^{b}\left\lvert\gamma'(t)\right\rvert dt\\" alt="\Lambda(\gamma)=\int_{a}^{b}\left\lvert\gamma'(t)\right\rvert dt\\" class="ee_img tr_noresize" eeimg="1">


