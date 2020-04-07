The Lebesgue Theory
===================

This chapter is about Lebesgue theory of measure and integration. Our
final goal in this chapter is to introduce the Lebesgue integration. We
first introduce the measurable set and the measure on it. Then
measurable functions are defined on measurable set. Finally we combine
measurable set and measurable function to introduce the Lebesgue
integration.

measure on sets
---------------

A measure (or a set function) is defined on a family of subset of a
given space. First we specify what family of subsets we care about.

We care about two type of family of subsets: the ring and the
<img src="https://www.zhihu.com/equation?tex=\sigma" alt="\sigma" class="ee_img tr_noresize" eeimg="1">-ring. A family <img src="https://www.zhihu.com/equation?tex=\mathscr{R}" alt="\mathscr{R}" class="ee_img tr_noresize" eeimg="1"> of subsets is called ring if it is
closed under union operation and set minus operation. A ring
<img src="https://www.zhihu.com/equation?tex=\mathscr{R}" alt="\mathscr{R}" class="ee_img tr_noresize" eeimg="1"> is called a <img src="https://www.zhihu.com/equation?tex=\sigma" alt="\sigma" class="ee_img tr_noresize" eeimg="1">-ring if it is closed under countable
union operation.

A set function <img src="https://www.zhihu.com/equation?tex=\phi" alt="\phi" class="ee_img tr_noresize" eeimg="1"> on <img src="https://www.zhihu.com/equation?tex=\mathscr{R}" alt="\mathscr{R}" class="ee_img tr_noresize" eeimg="1"> is a map from <img src="https://www.zhihu.com/equation?tex=\mathscr{R}" alt="\mathscr{R}" class="ee_img tr_noresize" eeimg="1"> to
<img src="https://www.zhihu.com/equation?tex=\overline{\mathbb{R}}" alt="\overline{\mathbb{R}}" class="ee_img tr_noresize" eeimg="1">. We call <img src="https://www.zhihu.com/equation?tex=\phi" alt="\phi" class="ee_img tr_noresize" eeimg="1"> is additive if <img src="https://www.zhihu.com/equation?tex=A\cap B=0" alt="A\cap B=0" class="ee_img tr_noresize" eeimg="1">
implies <img src="https://www.zhihu.com/equation?tex=\phi(A\cap B)=\phi(A)+\phi(B)" alt="\phi(A\cap B)=\phi(A)+\phi(B)" class="ee_img tr_noresize" eeimg="1"> and we call <img src="https://www.zhihu.com/equation?tex=\phi" alt="\phi" class="ee_img tr_noresize" eeimg="1"> is countably
additive (or <img src="https://www.zhihu.com/equation?tex=\sigma" alt="\sigma" class="ee_img tr_noresize" eeimg="1">-additive) if <img src="https://www.zhihu.com/equation?tex=A_j\cap A_i=0" alt="A_j\cap A_i=0" class="ee_img tr_noresize" eeimg="1"> implies
<img src="https://www.zhihu.com/equation?tex=\phi(\cap_{i=1}^\infty A_i)=\sum_{i=1}^\infty\phi(A)" alt="\phi(\cap_{i=1}^\infty A_i)=\sum_{i=1}^\infty\phi(A)" class="ee_img tr_noresize" eeimg="1">.

Countably additive set function <img src="https://www.zhihu.com/equation?tex=\phi" alt="\phi" class="ee_img tr_noresize" eeimg="1"> on a ring <img src="https://www.zhihu.com/equation?tex=\mathscr{R}" alt="\mathscr{R}" class="ee_img tr_noresize" eeimg="1"> is
continuous in following sense:

1.  <img src="https://www.zhihu.com/equation?tex=A_i" alt="A_i" class="ee_img tr_noresize" eeimg="1"> is a sequence of increasing sets,
    <img src="https://www.zhihu.com/equation?tex=A_1\subset A_2\subset\cdots" alt="A_1\subset A_2\subset\cdots" class="ee_img tr_noresize" eeimg="1">, <img src="https://www.zhihu.com/equation?tex=A\in \mathscr{R}" alt="A\in \mathscr{R}" class="ee_img tr_noresize" eeimg="1"> and
    <img src="https://www.zhihu.com/equation?tex=A=\cup_{i=1}^\infty A_i" alt="A=\cup_{i=1}^\infty A_i" class="ee_img tr_noresize" eeimg="1">. Then <img src="https://www.zhihu.com/equation?tex=\phi(A_n)\to \phi(A)" alt="\phi(A_n)\to \phi(A)" class="ee_img tr_noresize" eeimg="1">.

2.  <img src="https://www.zhihu.com/equation?tex=A_i" alt="A_i" class="ee_img tr_noresize" eeimg="1"> is a sequence of decreasing sets,
    <img src="https://www.zhihu.com/equation?tex=A_1\supset A_2\supset\cdots" alt="A_1\supset A_2\supset\cdots" class="ee_img tr_noresize" eeimg="1">, <img src="https://www.zhihu.com/equation?tex=A\in \mathscr{R}" alt="A\in \mathscr{R}" class="ee_img tr_noresize" eeimg="1"> and
    <img src="https://www.zhihu.com/equation?tex=A=\cap_{i=1}^\infty A_i" alt="A=\cap_{i=1}^\infty A_i" class="ee_img tr_noresize" eeimg="1">. If there is a number n s.t.
    <img src="https://www.zhihu.com/equation?tex=\phi(A_n)<\infty" alt="\phi(A_n)<\infty" class="ee_img tr_noresize" eeimg="1">, then <img src="https://www.zhihu.com/equation?tex=\phi(A_n)\to \phi(A)" alt="\phi(A_n)\to \phi(A)" class="ee_img tr_noresize" eeimg="1">.

Lebesgue measure and extension theorem
--------------------------------------

We define the elementary set (or n-cube) <img src="https://www.zhihu.com/equation?tex=I" alt="I" class="ee_img tr_noresize" eeimg="1"> in <img src="https://www.zhihu.com/equation?tex=\mathbb{R}^n" alt="\mathbb{R}^n" class="ee_img tr_noresize" eeimg="1"> as
product of interval <img src="https://www.zhihu.com/equation?tex=[a_i,b_i]" alt="[a_i,b_i]" class="ee_img tr_noresize" eeimg="1">, <img src="https://www.zhihu.com/equation?tex=[a_i,b_i)" alt="[a_i,b_i)" class="ee_img tr_noresize" eeimg="1">, <img src="https://www.zhihu.com/equation?tex=(a_i,b_i]" alt="(a_i,b_i]" class="ee_img tr_noresize" eeimg="1"> and
<img src="https://www.zhihu.com/equation?tex=(a_i,b_i)" alt="(a_i,b_i)" class="ee_img tr_noresize" eeimg="1">. Let <img src="https://www.zhihu.com/equation?tex=\mathscr{E}" alt="\mathscr{E}" class="ee_img tr_noresize" eeimg="1"> be the set containing all elementary sets
and their finite disjoint union as its elements. <img src="https://www.zhihu.com/equation?tex=\mathscr{E}" alt="\mathscr{E}" class="ee_img tr_noresize" eeimg="1"> is a ring
but not a <img src="https://www.zhihu.com/equation?tex=\sigma" alt="\sigma" class="ee_img tr_noresize" eeimg="1">-ring.

Now we study the measure <img src="https://www.zhihu.com/equation?tex=m" alt="m" class="ee_img tr_noresize" eeimg="1"> on <img src="https://www.zhihu.com/equation?tex=\mathscr{E}" alt="\mathscr{E}" class="ee_img tr_noresize" eeimg="1">. We define the measure <img src="https://www.zhihu.com/equation?tex=m" alt="m" class="ee_img tr_noresize" eeimg="1">
on <img src="https://www.zhihu.com/equation?tex=\mathscr{E}" alt="\mathscr{E}" class="ee_img tr_noresize" eeimg="1"> by <img src="https://www.zhihu.com/equation?tex=m(I)=\prod_{i=1}^n (b_i-a_i)" alt="m(I)=\prod_{i=1}^n (b_i-a_i)" class="ee_img tr_noresize" eeimg="1">. This measure is
regular, which means for any set <img src="https://www.zhihu.com/equation?tex=A\in \mathscr{E}" alt="A\in \mathscr{E}" class="ee_img tr_noresize" eeimg="1">, there is an open
set <img src="https://www.zhihu.com/equation?tex=G" alt="G" class="ee_img tr_noresize" eeimg="1"> and closed set <img src="https://www.zhihu.com/equation?tex=F" alt="F" class="ee_img tr_noresize" eeimg="1"> such that <img src="https://www.zhihu.com/equation?tex=F\subset A\subset G" alt="F\subset A\subset G" class="ee_img tr_noresize" eeimg="1"> and

<img src="https://www.zhihu.com/equation?tex=\phi(G)-\epsilon\leq \phi(A)\leq \phi(F)+\epsilon\\" alt="\phi(G)-\epsilon\leq \phi(A)\leq \phi(F)+\epsilon\\" class="ee_img tr_noresize" eeimg="1">

 or

<img src="https://www.zhihu.com/equation?tex=\phi(G-A)\leq\epsilon\quad and \quad\phi(A-F)\leq\epsilon\\" alt="\phi(G-A)\leq\epsilon\quad and \quad\phi(A-F)\leq\epsilon\\" class="ee_img tr_noresize" eeimg="1">

 We can
extend the regular set function <img src="https://www.zhihu.com/equation?tex=m" alt="m" class="ee_img tr_noresize" eeimg="1"> on <img src="https://www.zhihu.com/equation?tex=\mathscr{E}" alt="\mathscr{E}" class="ee_img tr_noresize" eeimg="1"> to a countably
additive set function <img src="https://www.zhihu.com/equation?tex=m'" alt="m'" class="ee_img tr_noresize" eeimg="1"> on a <img src="https://www.zhihu.com/equation?tex=\sigma" alt="\sigma" class="ee_img tr_noresize" eeimg="1">-ring which contains
<img src="https://www.zhihu.com/equation?tex=\mathscr{E}" alt="\mathscr{E}" class="ee_img tr_noresize" eeimg="1">. For extension we means <img src="https://www.zhihu.com/equation?tex=m'(A)=m(A)" alt="m'(A)=m(A)" class="ee_img tr_noresize" eeimg="1"> for all
<img src="https://www.zhihu.com/equation?tex=A\in \mathscr{E}" alt="A\in \mathscr{E}" class="ee_img tr_noresize" eeimg="1">.

To construct <img src="https://www.zhihu.com/equation?tex=m'" alt="m'" class="ee_img tr_noresize" eeimg="1">, first we define <img src="https://www.zhihu.com/equation?tex=m^*(E)" alt="m^*(E)" class="ee_img tr_noresize" eeimg="1"> for all <img src="https://www.zhihu.com/equation?tex=E\in \mathbb{R}^n" alt="E\in \mathbb{R}^n" class="ee_img tr_noresize" eeimg="1">
to be: 
<img src="https://www.zhihu.com/equation?tex=m^*(E)=\inf\sum_{i=1}^\infty m(A_n)\\" alt="m^*(E)=\inf\sum_{i=1}^\infty m(A_n)\\" class="ee_img tr_noresize" eeimg="1">

 where <img src="https://www.zhihu.com/equation?tex=A_n" alt="A_n" class="ee_img tr_noresize" eeimg="1"> are open
elementary sets in <img src="https://www.zhihu.com/equation?tex=\mathscr{E}" alt="\mathscr{E}" class="ee_img tr_noresize" eeimg="1"> and <img src="https://www.zhihu.com/equation?tex=E\subset \cup_{i=1}^\infty A_i" alt="E\subset \cup_{i=1}^\infty A_i" class="ee_img tr_noresize" eeimg="1">.
<img src="https://www.zhihu.com/equation?tex=m^*" alt="m^*" class="ee_img tr_noresize" eeimg="1"> has subadditivity, which means
<img src="https://www.zhihu.com/equation?tex=m^*(E)\leq \sum_{i=1}^\infty m^*(E_i)" alt="m^*(E)\leq \sum_{i=1}^\infty m^*(E_i)" class="ee_img tr_noresize" eeimg="1"> with
<img src="https://www.zhihu.com/equation?tex=E\subset \cup_{i=1}^\infty E_i" alt="E\subset \cup_{i=1}^\infty E_i" class="ee_img tr_noresize" eeimg="1">. But by regularity of <img src="https://www.zhihu.com/equation?tex=m" alt="m" class="ee_img tr_noresize" eeimg="1">, we can show
<img src="https://www.zhihu.com/equation?tex=m^*(A)=m(A)" alt="m^*(A)=m(A)" class="ee_img tr_noresize" eeimg="1"> for all <img src="https://www.zhihu.com/equation?tex=A\in \mathscr{E}" alt="A\in \mathscr{E}" class="ee_img tr_noresize" eeimg="1">.

Now we give the extension theorem of regular measure <img src="https://www.zhihu.com/equation?tex=m" alt="m" class="ee_img tr_noresize" eeimg="1"> on ring
<img src="https://www.zhihu.com/equation?tex=\mathscr{E}" alt="\mathscr{E}" class="ee_img tr_noresize" eeimg="1">. Let <img src="https://www.zhihu.com/equation?tex=\mathscr{R}_F" alt="\mathscr{R}_F" class="ee_img tr_noresize" eeimg="1"> be the set contains all elements in
<img src="https://www.zhihu.com/equation?tex=\mathscr{E}" alt="\mathscr{E}" class="ee_img tr_noresize" eeimg="1"> and their limit. And let <img src="https://www.zhihu.com/equation?tex=\mathscr{R}" alt="\mathscr{R}" class="ee_img tr_noresize" eeimg="1"> be the set contains
all elements in <img src="https://www.zhihu.com/equation?tex=\mathscr{R}_F" alt="\mathscr{R}_F" class="ee_img tr_noresize" eeimg="1"> and their countable union. Then
<img src="https://www.zhihu.com/equation?tex=\mathscr{R}" alt="\mathscr{R}" class="ee_img tr_noresize" eeimg="1"> is a <img src="https://www.zhihu.com/equation?tex=\sigma" alt="\sigma" class="ee_img tr_noresize" eeimg="1">-ring and <img src="https://www.zhihu.com/equation?tex=m^*" alt="m^*" class="ee_img tr_noresize" eeimg="1"> restrict on <img src="https://www.zhihu.com/equation?tex=\mathscr{R}" alt="\mathscr{R}" class="ee_img tr_noresize" eeimg="1"> is
countably additive. We say a sequence of set <img src="https://www.zhihu.com/equation?tex=A_n" alt="A_n" class="ee_img tr_noresize" eeimg="1"> converges to set <img src="https://www.zhihu.com/equation?tex=A" alt="A" class="ee_img tr_noresize" eeimg="1">
if their Hausdorff distance <img src="https://www.zhihu.com/equation?tex=d(A_n,A)\to 0" alt="d(A_n,A)\to 0" class="ee_img tr_noresize" eeimg="1">.

A remark here is that the <img src="https://www.zhihu.com/equation?tex=\sigma" alt="\sigma" class="ee_img tr_noresize" eeimg="1">-ring <img src="https://www.zhihu.com/equation?tex=\mathscr{R}" alt="\mathscr{R}" class="ee_img tr_noresize" eeimg="1"> is not the
smallest <img src="https://www.zhihu.com/equation?tex=\sigma" alt="\sigma" class="ee_img tr_noresize" eeimg="1">-ring contains all open set. The element in smallest
<img src="https://www.zhihu.com/equation?tex=\sigma" alt="\sigma" class="ee_img tr_noresize" eeimg="1">-ring containing all open set is called Borel set, and this
<img src="https://www.zhihu.com/equation?tex=\sigma" alt="\sigma" class="ee_img tr_noresize" eeimg="1">-ring is denoted as <img src="https://www.zhihu.com/equation?tex=\mathscr{B}" alt="\mathscr{B}" class="ee_img tr_noresize" eeimg="1">. The element in <img src="https://www.zhihu.com/equation?tex=\mathscr{R}" alt="\mathscr{R}" class="ee_img tr_noresize" eeimg="1">
is the union of a Borel set and a set of measure zero.

Measurable functions
--------------------

A function defined on measurable space <img src="https://www.zhihu.com/equation?tex=X" alt="X" class="ee_img tr_noresize" eeimg="1"> with values in
<img src="https://www.zhihu.com/equation?tex=\overline{\mathbb{R}}" alt="\overline{\mathbb{R}}" class="ee_img tr_noresize" eeimg="1"> is measurable if the set 
<img src="https://www.zhihu.com/equation?tex=\{x|f(x)>a\}\\" alt="\{x|f(x)>a\}\\" class="ee_img tr_noresize" eeimg="1">

 is
measurable for every real number <img src="https://www.zhihu.com/equation?tex=a" alt="a" class="ee_img tr_noresize" eeimg="1">.

Measurable functions are closed under following arithmetic operation:

1.  If <img src="https://www.zhihu.com/equation?tex=f" alt="f" class="ee_img tr_noresize" eeimg="1"> is measurable, then <img src="https://www.zhihu.com/equation?tex=\left\lvert f\right\rvert" alt="\left\lvert f\right\rvert" class="ee_img tr_noresize" eeimg="1"> is
    measurable.

2.  If <img src="https://www.zhihu.com/equation?tex=f_n" alt="f_n" class="ee_img tr_noresize" eeimg="1"> is a sequence of measurable function, then <img src="https://www.zhihu.com/equation?tex=\sup f_n(x)" alt="\sup f_n(x)" class="ee_img tr_noresize" eeimg="1">
    and <img src="https://www.zhihu.com/equation?tex=\limsup f_n(x)" alt="\limsup f_n(x)" class="ee_img tr_noresize" eeimg="1"> is measurable.

3.  If <img src="https://www.zhihu.com/equation?tex=f" alt="f" class="ee_img tr_noresize" eeimg="1"> is measurable, then <img src="https://www.zhihu.com/equation?tex=f^+=\max(f,0)" alt="f^+=\max(f,0)" class="ee_img tr_noresize" eeimg="1"> and <img src="https://www.zhihu.com/equation?tex=f^-=-\min(f,0)" alt="f^-=-\min(f,0)" class="ee_img tr_noresize" eeimg="1"> are
    measurable.

4.  If <img src="https://www.zhihu.com/equation?tex=f" alt="f" class="ee_img tr_noresize" eeimg="1"> and <img src="https://www.zhihu.com/equation?tex=g" alt="g" class="ee_img tr_noresize" eeimg="1"> are measurable, and <img src="https://www.zhihu.com/equation?tex=F" alt="F" class="ee_img tr_noresize" eeimg="1"> is continuous on
    <img src="https://www.zhihu.com/equation?tex=\mathbb{R}^2" alt="\mathbb{R}^2" class="ee_img tr_noresize" eeimg="1">, then <img src="https://www.zhihu.com/equation?tex=F(f(x),g(x))" alt="F(f(x),g(x))" class="ee_img tr_noresize" eeimg="1"> are measurable.

5.  If <img src="https://www.zhihu.com/equation?tex=f" alt="f" class="ee_img tr_noresize" eeimg="1"> and <img src="https://www.zhihu.com/equation?tex=g" alt="g" class="ee_img tr_noresize" eeimg="1"> are measurable, then <img src="https://www.zhihu.com/equation?tex=f+g" alt="f+g" class="ee_img tr_noresize" eeimg="1"> and <img src="https://www.zhihu.com/equation?tex=fg" alt="fg" class="ee_img tr_noresize" eeimg="1"> are measurable.

Lebesgue integration
--------------------

In the following discussion, we use <img src="https://www.zhihu.com/equation?tex=\mu" alt="\mu" class="ee_img tr_noresize" eeimg="1"> to represent the Lebesgue
measure. First we define the Lebesgue integration for simple function
<img src="https://www.zhihu.com/equation?tex=s(x)=\sum_{i=1}^n c_i\chi_{E_i}(x)" alt="s(x)=\sum_{i=1}^n c_i\chi_{E_i}(x)" class="ee_img tr_noresize" eeimg="1"> to be:

<img src="https://www.zhihu.com/equation?tex=\int_{E}s d\mu=\sum_{i=1}^n c_i\mu(E\cap E_i)\\" alt="\int_{E}s d\mu=\sum_{i=1}^n c_i\mu(E\cap E_i)\\" class="ee_img tr_noresize" eeimg="1">

 and the integration
for non-negative measurable function <img src="https://www.zhihu.com/equation?tex=f" alt="f" class="ee_img tr_noresize" eeimg="1"> to be

<img src="https://www.zhihu.com/equation?tex=\int_{E}f d\mu=\sup \int_{E}s d\mu\\" alt="\int_{E}f d\mu=\sup \int_{E}s d\mu\\" class="ee_img tr_noresize" eeimg="1">

 where <img src="https://www.zhihu.com/equation?tex=0\leq s\leq f" alt="0\leq s\leq f" class="ee_img tr_noresize" eeimg="1">. For
measurable function <img src="https://www.zhihu.com/equation?tex=f" alt="f" class="ee_img tr_noresize" eeimg="1">, we define the integration of <img src="https://www.zhihu.com/equation?tex=f" alt="f" class="ee_img tr_noresize" eeimg="1"> to be:

<img src="https://www.zhihu.com/equation?tex=\int_{E}f d\mu=\int_{E}f^+ d\mu-\int_{E}f^- d\mu\\" alt="\int_{E}f d\mu=\int_{E}f^+ d\mu-\int_{E}f^- d\mu\\" class="ee_img tr_noresize" eeimg="1">

 if at least one
integration in right hide side is finite.

There are three important theorems in Lebesgue integration:

1.  Monotone convergence theorem: Given an increasing sequence of
    non-negative measurable function <img src="https://www.zhihu.com/equation?tex=f_n" alt="f_n" class="ee_img tr_noresize" eeimg="1"> and its pointwise limit <img src="https://www.zhihu.com/equation?tex=f" alt="f" class="ee_img tr_noresize" eeimg="1">,
    we have 
<img src="https://www.zhihu.com/equation?tex=\lim\int_{E}{f_nd\mu}=\int_{E}{fd\mu}\\" alt="\lim\int_{E}{f_nd\mu}=\int_{E}{fd\mu}\\" class="ee_img tr_noresize" eeimg="1">



2.  Fatou's lemma: Given a sequence of non-negative measurable function
    <img src="https://www.zhihu.com/equation?tex=f_n" alt="f_n" class="ee_img tr_noresize" eeimg="1">, we have
    
<img src="https://www.zhihu.com/equation?tex=\int_{E}{\liminf f_n d\mu}\leq \liminf \int_{E}{f_nd\mu}\\" alt="\int_{E}{\liminf f_n d\mu}\leq \liminf \int_{E}{f_nd\mu}\\" class="ee_img tr_noresize" eeimg="1">



3.  Dominated convergence theorem: Given a sequence of measurable
    function <img src="https://www.zhihu.com/equation?tex=f_n" alt="f_n" class="ee_img tr_noresize" eeimg="1">, the pointwise limit of <img src="https://www.zhihu.com/equation?tex=f_n" alt="f_n" class="ee_img tr_noresize" eeimg="1"> exists,
    <img src="https://www.zhihu.com/equation?tex=f_n(x)\to f(x)" alt="f_n(x)\to f(x)" class="ee_img tr_noresize" eeimg="1">. If <img src="https://www.zhihu.com/equation?tex=\left\lvert f_n(x)\right\rvert\leq g(x)" alt="\left\lvert f_n(x)\right\rvert\leq g(x)" class="ee_img tr_noresize" eeimg="1"> for a
    measurable function <img src="https://www.zhihu.com/equation?tex=g" alt="g" class="ee_img tr_noresize" eeimg="1"> with all <img src="https://www.zhihu.com/equation?tex=n" alt="n" class="ee_img tr_noresize" eeimg="1">, we have
    
<img src="https://www.zhihu.com/equation?tex=\lim\int_{E}{f_n d\mu}=\int_{E}{fd\mu}\\" alt="\lim\int_{E}{f_n d\mu}=\int_{E}{fd\mu}\\" class="ee_img tr_noresize" eeimg="1">



Most properties of Riemann integration are also satisfied for Lebesgue
integration. We do not repeat them here. But there is one special
property satisfied by Lebesgue integration, which is we can partition
the domain of integration for measurable set.

If <img src="https://www.zhihu.com/equation?tex=A=\cup A_n" alt="A=\cup A_n" class="ee_img tr_noresize" eeimg="1"> and <img src="https://www.zhihu.com/equation?tex=A_i\cap A_j=\emptyset" alt="A_i\cap A_j=\emptyset" class="ee_img tr_noresize" eeimg="1">, then:

<img src="https://www.zhihu.com/equation?tex=\int_{A}{fd\mu}=\sum_{i=1}^\infty\int_{A_i}{fd\mu}\\" alt="\int_{A}{fd\mu}=\sum_{i=1}^\infty\int_{A_i}{fd\mu}\\" class="ee_img tr_noresize" eeimg="1">



On bounded interval <img src="https://www.zhihu.com/equation?tex=[a,b]" alt="[a,b]" class="ee_img tr_noresize" eeimg="1"> in <img src="https://www.zhihu.com/equation?tex=\mathbb{R}" alt="\mathbb{R}" class="ee_img tr_noresize" eeimg="1">, if <img src="https://www.zhihu.com/equation?tex=f" alt="f" class="ee_img tr_noresize" eeimg="1"> is Riemann
integrable, then <img src="https://www.zhihu.com/equation?tex=f" alt="f" class="ee_img tr_noresize" eeimg="1"> is Lebesgue integrable, and the Lebesgue
integration and Riemann integration coincides. Furthermore, for a
bounded function on <img src="https://www.zhihu.com/equation?tex=[a,b]" alt="[a,b]" class="ee_img tr_noresize" eeimg="1">, <img src="https://www.zhihu.com/equation?tex=f" alt="f" class="ee_img tr_noresize" eeimg="1"> is Riemann integrable if and only if
<img src="https://www.zhihu.com/equation?tex=f" alt="f" class="ee_img tr_noresize" eeimg="1"> is discontinuous on a countable set.

<img src="https://www.zhihu.com/equation?tex=L^2" alt="L^2" class="ee_img tr_noresize" eeimg="1"> function
--------------

we say a measurable function is in <img src="https://www.zhihu.com/equation?tex=L^2(X)" alt="L^2(X)" class="ee_img tr_noresize" eeimg="1"> if the integration
<img src="https://www.zhihu.com/equation?tex=\int_{X}{\left\lvert f\right\rvert^2d\mu}<\infty" alt="\int_{X}{\left\lvert f\right\rvert^2d\mu}<\infty" class="ee_img tr_noresize" eeimg="1"> and we define the
norm of <img src="https://www.zhihu.com/equation?tex=f" alt="f" class="ee_img tr_noresize" eeimg="1"> to be
<img src="https://www.zhihu.com/equation?tex=\lVert f\rVert=\left( \int_{X}{\left\lvert f\right\rvert^2d\mu} \right)^{\frac{1}{2}}" alt="\lVert f\rVert=\left( \int_{X}{\left\lvert f\right\rvert^2d\mu} \right)^{\frac{1}{2}}" class="ee_img tr_noresize" eeimg="1">.

<img src="https://www.zhihu.com/equation?tex=\{f_n\}" alt="\{f_n\}" class="ee_img tr_noresize" eeimg="1"> is called a Cauchy sequence in <img src="https://www.zhihu.com/equation?tex=L^2(X)" alt="L^2(X)" class="ee_img tr_noresize" eeimg="1"> if there exists a
number <img src="https://www.zhihu.com/equation?tex=N" alt="N" class="ee_img tr_noresize" eeimg="1"> such that <img src="https://www.zhihu.com/equation?tex=\lVert f_n-f_m\rVert\leq \epsilon" alt="\lVert f_n-f_m\rVert\leq \epsilon" class="ee_img tr_noresize" eeimg="1"> for all
<img src="https://www.zhihu.com/equation?tex=m,n>N" alt="m,n>N" class="ee_img tr_noresize" eeimg="1">. <img src="https://www.zhihu.com/equation?tex=L^2(X)" alt="L^2(X)" class="ee_img tr_noresize" eeimg="1"> is complete space, which means Cauchy sequence <img src="https://www.zhihu.com/equation?tex=f_n" alt="f_n" class="ee_img tr_noresize" eeimg="1">
converges to a measurable function <img src="https://www.zhihu.com/equation?tex=f" alt="f" class="ee_img tr_noresize" eeimg="1"> and <img src="https://www.zhihu.com/equation?tex=f\in L^2(X)" alt="f\in L^2(X)" class="ee_img tr_noresize" eeimg="1">.

An orthonormal set <img src="https://www.zhihu.com/equation?tex=\{\phi_n\}" alt="\{\phi_n\}" class="ee_img tr_noresize" eeimg="1"> is said to be complete if for
<img src="https://www.zhihu.com/equation?tex=f\in L^2" alt="f\in L^2" class="ee_img tr_noresize" eeimg="1">, <img src="https://www.zhihu.com/equation?tex=\int_{X}{f\bar{\phi}_n d\mu}=0" alt="\int_{X}{f\bar{\phi}_n d\mu}=0" class="ee_img tr_noresize" eeimg="1"> implies <img src="https://www.zhihu.com/equation?tex=\lVert f\rVert=0" alt="\lVert f\rVert=0" class="ee_img tr_noresize" eeimg="1">.
Given a complete orthonormal set, for any <img src="https://www.zhihu.com/equation?tex=L^2" alt="L^2" class="ee_img tr_noresize" eeimg="1"> function <img src="https://www.zhihu.com/equation?tex=f" alt="f" class="ee_img tr_noresize" eeimg="1">, we define

<img src="https://www.zhihu.com/equation?tex=c_n=\int_{X}{f\bar{\phi}_n d\mu}\\" alt="c_n=\int_{X}{f\bar{\phi}_n d\mu}\\" class="ee_img tr_noresize" eeimg="1">

 We have:

<img src="https://www.zhihu.com/equation?tex=\int_{X}{\left\lvert f\right\rvert^2d\mu}=\sum_{i=1}^\infty\left\lvert c_n\right\rvert^2\\" alt="\int_{X}{\left\lvert f\right\rvert^2d\mu}=\sum_{i=1}^\infty\left\lvert c_n\right\rvert^2\\" class="ee_img tr_noresize" eeimg="1">


Conversely, given a sequence of number <img src="https://www.zhihu.com/equation?tex=c_n" alt="c_n" class="ee_img tr_noresize" eeimg="1"> and
<img src="https://www.zhihu.com/equation?tex=\sum\left\lvert c_n\right\rvert^2" alt="\sum\left\lvert c_n\right\rvert^2" class="ee_img tr_noresize" eeimg="1"> converges, the function <img src="https://www.zhihu.com/equation?tex=f" alt="f" class="ee_img tr_noresize" eeimg="1"> defined
to be: 
<img src="https://www.zhihu.com/equation?tex=\sum_{i=1}^\infty c_n\phi_n\\" alt="\sum_{i=1}^\infty c_n\phi_n\\" class="ee_img tr_noresize" eeimg="1">

 is a <img src="https://www.zhihu.com/equation?tex=L^2" alt="L^2" class="ee_img tr_noresize" eeimg="1"> function
(Riesz-Fischer theorem).

Hence every complete orthonormal set induces a 1-1 correspondence
between the functions <img src="https://www.zhihu.com/equation?tex=f\in L^2" alt="f\in L^2" class="ee_img tr_noresize" eeimg="1"> and the sequence <img src="https://www.zhihu.com/equation?tex=\left\{ c_n\right\}" alt="\left\{ c_n\right\}" class="ee_img tr_noresize" eeimg="1">
for which <img src="https://www.zhihu.com/equation?tex=\sum_{i=1}^\infty\left\lvert c_n\right\rvert^2" alt="\sum_{i=1}^\infty\left\lvert c_n\right\rvert^2" class="ee_img tr_noresize" eeimg="1"> converges.
Thus the function space <img src="https://www.zhihu.com/equation?tex=L^2" alt="L^2" class="ee_img tr_noresize" eeimg="1"> is isometric to the sequence space
<img src="https://www.zhihu.com/equation?tex=\ell^2" alt="\ell^2" class="ee_img tr_noresize" eeimg="1">.
