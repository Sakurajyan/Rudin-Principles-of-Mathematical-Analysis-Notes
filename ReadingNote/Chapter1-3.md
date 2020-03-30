The Real and Complex Number Systems
===================================

In this chapter, we talk about number systems. We begin our topic with
rational number and shows rational number field has a shortcoming:
rational number system does not have *least-upper bound property*.

We first talk about two topological concept: order set and least-upper
bound property. Least-upper bound property implies greatest-lower
bounded property (Theorem 1.11). We show that rational number system is
an ordered set but does not have least-upper bound property.

In an algebraic view, number systems have an algebraic structure called
field. Field <img src="https://www.zhihu.com/equation?tex=F" alt="F" class="ee_img tr_noresize" eeimg="1"> is a set with two operations <img src="https://www.zhihu.com/equation?tex=+" alt="+" class="ee_img tr_noresize" eeimg="1"> and <img src="https://www.zhihu.com/equation?tex=*" alt="*" class="ee_img tr_noresize" eeimg="1"> and they
follow distributive law. Under operation <img src="https://www.zhihu.com/equation?tex=+" alt="+" class="ee_img tr_noresize" eeimg="1">, <img src="https://www.zhihu.com/equation?tex=F" alt="F" class="ee_img tr_noresize" eeimg="1"> is a communitive group
with identity element 0. Under operation <img src="https://www.zhihu.com/equation?tex=*" alt="*" class="ee_img tr_noresize" eeimg="1">, <img src="https://www.zhihu.com/equation?tex=F" alt="F" class="ee_img tr_noresize" eeimg="1"> is a communitive
monoid, with all elements have inverse expect element 0. There are some
basic arithmetic properties and rules under these two operations.

We combine the topological and algebraic structure and introduce the
ordered field.

Now we back to our number system. We can extend rational number system
to real number system and the real number system has least-upper bound
property (Theorem 1.19). The proof is rather long and is therefore
presented in the Appendix. By least-upper bound property of real number
system, we give some properties of real number system:

1.  There is a rational number between two real numbers (Theorem 1.20).

2.  We can take the nth roots of positive reals (Theorem 1.21).

Then we give the concept of extended real number system and complex
field. Extended real number system is no longer a field. The complex
field can be defined as tuples with operation. So the image number <img src="https://www.zhihu.com/equation?tex=i" alt="i" class="ee_img tr_noresize" eeimg="1">
has a clear meaning.

Finally we talk about the Euclidean spaces with inner product and the
norm induced by inner product.

There exists an ordered field <img src="https://www.zhihu.com/equation?tex=R" alt="R" class="ee_img tr_noresize" eeimg="1"> which has the least-upper-bound
property.

Moreover, <img src="https://www.zhihu.com/equation?tex=R" alt="R" class="ee_img tr_noresize" eeimg="1"> contains <img src="https://www.zhihu.com/equation?tex=\mathbb{Q}" alt="\mathbb{Q}" class="ee_img tr_noresize" eeimg="1"> as a subfield.

Here we give the sketch of proof. We first construct the Dedekind cut
<img src="https://www.zhihu.com/equation?tex=R" alt="R" class="ee_img tr_noresize" eeimg="1"> from <img src="https://www.zhihu.com/equation?tex=\mathbb{Q}" alt="\mathbb{Q}" class="ee_img tr_noresize" eeimg="1">. And shows that <img src="https://www.zhihu.com/equation?tex=R" alt="R" class="ee_img tr_noresize" eeimg="1"> is an ordered field with the
least-upper-bound property. Notices a cut may not has least upper bound
in <img src="https://www.zhihu.com/equation?tex=\mathbb{Q}" alt="\mathbb{Q}" class="ee_img tr_noresize" eeimg="1">, such as all rational number less than <img src="https://www.zhihu.com/equation?tex=\sqrt{2}" alt="\sqrt{2}" class="ee_img tr_noresize" eeimg="1">. For a
rational number <img src="https://www.zhihu.com/equation?tex=r" alt="r" class="ee_img tr_noresize" eeimg="1">, the rational cut <img src="https://www.zhihu.com/equation?tex=r^*" alt="r^*" class="ee_img tr_noresize" eeimg="1"> which consists of all
<img src="https://www.zhihu.com/equation?tex=p\in \mathbb{Q}" alt="p\in \mathbb{Q}" class="ee_img tr_noresize" eeimg="1"> such that <img src="https://www.zhihu.com/equation?tex=p<r" alt="p<r" class="ee_img tr_noresize" eeimg="1">. And we can construct the isomorphism
between <img src="https://www.zhihu.com/equation?tex=r^*" alt="r^*" class="ee_img tr_noresize" eeimg="1"> and <img src="https://www.zhihu.com/equation?tex=r" alt="r" class="ee_img tr_noresize" eeimg="1">. The second statement of the theorem is in
isomorphic sense.

In this book the author does not prove a fact: any two ordered fields
with the least-upper-bound property are isomorphic.

The statement in page 19 is not clear. It should be understand as
follows: there is an integer n such that <img src="https://www.zhihu.com/equation?tex=nw\in \alpha" alt="nw\in \alpha" class="ee_img tr_noresize" eeimg="1"> but
<img src="https://www.zhihu.com/equation?tex=(n+1)w\notin \alpha" alt="(n+1)w\notin \alpha" class="ee_img tr_noresize" eeimg="1">. <img src="https://www.zhihu.com/equation?tex=n" alt="n" class="ee_img tr_noresize" eeimg="1"> can be negative.

I wonder the relation between completeness of Dedekind cut and of Cauchy
sequence. These are two different construction of real numbers. Also
these construction invoke me the real number is the power set of
rational number.

Basic Topology
==============

In this chapter, we talk about point-set topology in <img src="https://www.zhihu.com/equation?tex=\mathbb{R}^n" alt="\mathbb{R}^n" class="ee_img tr_noresize" eeimg="1">.
Before we talk about topological concept, we talk about set theory. One
important observation for set <img src="https://www.zhihu.com/equation?tex=A" alt="A" class="ee_img tr_noresize" eeimg="1"> being infinite set is there is a
bijection from set <img src="https://www.zhihu.com/equation?tex=A" alt="A" class="ee_img tr_noresize" eeimg="1"> to a proper subset of <img src="https://www.zhihu.com/equation?tex=A" alt="A" class="ee_img tr_noresize" eeimg="1">. For infinite set,
countable sets represent the smallest infinity since no uncountable set
can be a subset of a countable set (Theorem 2.8). The countable union of
countable sets are still countable.

Usually, the proof of all sequence whose elements are the digits 0 and 1
forming an uncountable set <img src="https://www.zhihu.com/equation?tex=A" alt="A" class="ee_img tr_noresize" eeimg="1"> is to show that there is an element not
match all listed sequences if we assume this set is countable. In this
book author gives a direct proof: Let set of listed sequences be a
countable subset of <img src="https://www.zhihu.com/equation?tex=A" alt="A" class="ee_img tr_noresize" eeimg="1">, the \"diagonal\" element is always not in this
countable subset. Thus every countable set of <img src="https://www.zhihu.com/equation?tex=A" alt="A" class="ee_img tr_noresize" eeimg="1"> is a proper subset of
<img src="https://www.zhihu.com/equation?tex=A" alt="A" class="ee_img tr_noresize" eeimg="1">. If <img src="https://www.zhihu.com/equation?tex=A" alt="A" class="ee_img tr_noresize" eeimg="1"> is countable, then <img src="https://www.zhihu.com/equation?tex=A" alt="A" class="ee_img tr_noresize" eeimg="1"> is a proper subset of <img src="https://www.zhihu.com/equation?tex=A" alt="A" class="ee_img tr_noresize" eeimg="1">. This is
absurd. Thus <img src="https://www.zhihu.com/equation?tex=A" alt="A" class="ee_img tr_noresize" eeimg="1"> is uncountable.

Now we begin our topic of point-set topology for <img src="https://www.zhihu.com/equation?tex=\mathbb{R}^n" alt="\mathbb{R}^n" class="ee_img tr_noresize" eeimg="1">. In this
book, the definition of some concept like neighborhood, open set is
different from general topology, since topology we talk about is induced
by an usual metric. Here are two not obvious properties:

If p is a limit point of a set <img src="https://www.zhihu.com/equation?tex=E" alt="E" class="ee_img tr_noresize" eeimg="1">, then every neighborhood of <img src="https://www.zhihu.com/equation?tex=p" alt="p" class="ee_img tr_noresize" eeimg="1">
contains infinitely many points of <img src="https://www.zhihu.com/equation?tex=E" alt="E" class="ee_img tr_noresize" eeimg="1">.

and its corollary: A finite point set has no limit points.

Some theorems are actually the definition of concept in general
topology, such as

1.  Neighborhood is an open set.

2.  Set <img src="https://www.zhihu.com/equation?tex=A" alt="A" class="ee_img tr_noresize" eeimg="1"> is open if and only if its complement set <img src="https://www.zhihu.com/equation?tex=A^c" alt="A^c" class="ee_img tr_noresize" eeimg="1"> is closed.

3.  Union of open set is open.

Then we talk about an important concept in topology: compactness.
Compactness can be used for describe the space but open and closed not,
since the properties of being open or closed depends on the space in
which it is embedded. The theorems related to compactness are so many,
but the proof of them is usually just a verification of definition. In
this book we talk about compactness in metric space, however the
following holds for a more general space, Hausdorff space.

1.  Suppose <img src="https://www.zhihu.com/equation?tex=K\subset Y\subset X" alt="K\subset Y\subset X" class="ee_img tr_noresize" eeimg="1">. <img src="https://www.zhihu.com/equation?tex=K" alt="K" class="ee_img tr_noresize" eeimg="1"> is compact relative to <img src="https://www.zhihu.com/equation?tex=X" alt="X" class="ee_img tr_noresize" eeimg="1"> if and
    only if <img src="https://www.zhihu.com/equation?tex=K" alt="K" class="ee_img tr_noresize" eeimg="1"> is compact relative to <img src="https://www.zhihu.com/equation?tex=Y" alt="Y" class="ee_img tr_noresize" eeimg="1"> (Theorem 2.33).

2.  Compact subsets are closed (Theorem 2.34).

3.  Closed subsets of compact sets are compact (Theorem 2.35).

Here is an important but simple theorem:

<img src="https://www.zhihu.com/equation?tex=(K_\alpha)" alt="(K_\alpha)" class="ee_img tr_noresize" eeimg="1"> is a collection of compact subsets such that the finite
intersection is nonempty, then <img src="https://www.zhihu.com/equation?tex=\cap_\alpha K_\alpha" alt="\cap_\alpha K_\alpha" class="ee_img tr_noresize" eeimg="1"> is nonempty.

It is a trivial consequence of another equivalent definition of
compactness: <img src="https://www.zhihu.com/equation?tex=A" alt="A" class="ee_img tr_noresize" eeimg="1"> is compact if and only if any collection of closed
subsets <img src="https://www.zhihu.com/equation?tex=(K_\alpha)" alt="(K_\alpha)" class="ee_img tr_noresize" eeimg="1">, finite intersection of <img src="https://www.zhihu.com/equation?tex=K_\alpha" alt="K_\alpha" class="ee_img tr_noresize" eeimg="1"> is nonempty
implies <img src="https://www.zhihu.com/equation?tex=\cap_\alpha K_\alpha" alt="\cap_\alpha K_\alpha" class="ee_img tr_noresize" eeimg="1"> is nonempty. This definition is
contrapositive of definition using finite cover.

Now we consider the one dimensional version of corollary of Theorem
2.36: For a sequence of decreasing interval <img src="https://www.zhihu.com/equation?tex=(I_n)" alt="(I_n)" class="ee_img tr_noresize" eeimg="1"> in <img src="https://www.zhihu.com/equation?tex=\mathbb{R}^1" alt="\mathbb{R}^1" class="ee_img tr_noresize" eeimg="1">,
<img src="https://www.zhihu.com/equation?tex=\cap_1^{\infty}I_n" alt="\cap_1^{\infty}I_n" class="ee_img tr_noresize" eeimg="1"> is not empty (Theorem 2.38). But the author uses a
different proof idea. This different idea shows how the
least-upper-bound property plays in infinite intersection for intervals
in <img src="https://www.zhihu.com/equation?tex=\mathbb{R}^1" alt="\mathbb{R}^1" class="ee_img tr_noresize" eeimg="1"> and n-cells (closed cubes) in <img src="https://www.zhihu.com/equation?tex=\mathbb{R}^n" alt="\mathbb{R}^n" class="ee_img tr_noresize" eeimg="1">.

Here is an important property of space <img src="https://www.zhihu.com/equation?tex=\mathbb{R}^n" alt="\mathbb{R}^n" class="ee_img tr_noresize" eeimg="1">:

Every k-cell is compact.

The proof of Theorem 2.40 uses an important tool. It keeps separating
n-cell and shows there is a point in sequences of decreasing sequence of
k-cells. The existence of the point is guaranteed by compactness. But it
can also be guaranteed by completeness. (Indeed, completeness and
precompactness implies compactness, the separation steps actually show
the <img src="https://www.zhihu.com/equation?tex=\mathbb{R}^n" alt="\mathbb{R}^n" class="ee_img tr_noresize" eeimg="1"> is precompact).

Theorem 2.41 generalizes Theorem 2.40, and gives the necessary condition
for compactness in <img src="https://www.zhihu.com/equation?tex=\mathbb{R}^n" alt="\mathbb{R}^n" class="ee_img tr_noresize" eeimg="1">.

The following statements are equivalent for a set <img src="https://www.zhihu.com/equation?tex=E" alt="E" class="ee_img tr_noresize" eeimg="1"> in <img src="https://www.zhihu.com/equation?tex=\mathbb{R}^n" alt="\mathbb{R}^n" class="ee_img tr_noresize" eeimg="1">:

1.  <img src="https://www.zhihu.com/equation?tex=E" alt="E" class="ee_img tr_noresize" eeimg="1"> is closed and bounded.

2.  <img src="https://www.zhihu.com/equation?tex=E" alt="E" class="ee_img tr_noresize" eeimg="1"> is compact.

3.  Every infinite subset of <img src="https://www.zhihu.com/equation?tex=E" alt="E" class="ee_img tr_noresize" eeimg="1"> has a limit point in <img src="https://www.zhihu.com/equation?tex=E" alt="E" class="ee_img tr_noresize" eeimg="1">.

The proof of Theorem 2.41, 3 implying 2, implicitly use the converse
part of the sequence lemma (Lemma 21.2 in Munkres' Topology): Let <img src="https://www.zhihu.com/equation?tex=X" alt="X" class="ee_img tr_noresize" eeimg="1"> be
a metrizable space and <img src="https://www.zhihu.com/equation?tex=A\subset X" alt="A\subset X" class="ee_img tr_noresize" eeimg="1">, then for any limit point <img src="https://www.zhihu.com/equation?tex=x" alt="x" class="ee_img tr_noresize" eeimg="1"> of
<img src="https://www.zhihu.com/equation?tex=A" alt="A" class="ee_img tr_noresize" eeimg="1">, there is a sequence of points of <img src="https://www.zhihu.com/equation?tex=A" alt="A" class="ee_img tr_noresize" eeimg="1"> that converges to <img src="https://www.zhihu.com/equation?tex=x" alt="x" class="ee_img tr_noresize" eeimg="1">. If <img src="https://www.zhihu.com/equation?tex=X" alt="X" class="ee_img tr_noresize" eeimg="1">
is not a metric space or is not metrizable, the sequence of convergent
points can not be extracted. The proof also shows the limit point of
this sequence is unique in metric space.

After compact sets, we study perfect sets. Here is one character of
perfect sets: A non empty perfect sets in <img src="https://www.zhihu.com/equation?tex=\mathbb{R}^n" alt="\mathbb{R}^n" class="ee_img tr_noresize" eeimg="1"> is uncountable
(Theorem 2.43). The proof given in this book is a little mysterious:
<img src="https://www.zhihu.com/equation?tex=V_1" alt="V_1" class="ee_img tr_noresize" eeimg="1"> is a neighborhood of <img src="https://www.zhihu.com/equation?tex=x_1" alt="x_1" class="ee_img tr_noresize" eeimg="1"> but <img src="https://www.zhihu.com/equation?tex=V_n" alt="V_n" class="ee_img tr_noresize" eeimg="1"> may be not a neighborhood of
<img src="https://www.zhihu.com/equation?tex=x_n" alt="x_n" class="ee_img tr_noresize" eeimg="1"> for <img src="https://www.zhihu.com/equation?tex=n>1" alt="n>1" class="ee_img tr_noresize" eeimg="1">. If we suppose a non empty perfect set is countable, we
can construct a sequence of compact sets and shows the intersection
contains no point. Thus we have proved Theorem 2.43

The Cantor set is an interesting example. It is compact since it is
closed by intersection of closed set and obvious bounded. This
intersection procure explains an usually misunderstanding: For finite
<img src="https://www.zhihu.com/equation?tex=N" alt="N" class="ee_img tr_noresize" eeimg="1">, <img src="https://www.zhihu.com/equation?tex=\cap_{n=1}^N E_n=E_N" alt="\cap_{n=1}^N E_n=E_N" class="ee_img tr_noresize" eeimg="1"> but expression <img src="https://www.zhihu.com/equation?tex=E_\infty" alt="E_\infty" class="ee_img tr_noresize" eeimg="1"> has no meaning. We
can only has a \"legal\" expression <img src="https://www.zhihu.com/equation?tex=\cap_{n=1}^\infty E_n" alt="\cap_{n=1}^\infty E_n" class="ee_img tr_noresize" eeimg="1">. Since every
<img src="https://www.zhihu.com/equation?tex=E_n" alt="E_n" class="ee_img tr_noresize" eeimg="1"> is closed (the index is always finite if we consider a particular
index), we can state that <img src="https://www.zhihu.com/equation?tex=\cap_{n=1}^\infty E_n" alt="\cap_{n=1}^\infty E_n" class="ee_img tr_noresize" eeimg="1"> is always closed. It
is also perfect. Since every neighborhood (segment <img src="https://www.zhihu.com/equation?tex=S" alt="S" class="ee_img tr_noresize" eeimg="1"> contains <img src="https://www.zhihu.com/equation?tex=x" alt="x" class="ee_img tr_noresize" eeimg="1">) of
<img src="https://www.zhihu.com/equation?tex=x" alt="x" class="ee_img tr_noresize" eeimg="1"> in Cantor set intersects other points <img src="https://www.zhihu.com/equation?tex=x_n" alt="x_n" class="ee_img tr_noresize" eeimg="1"> (end point of <img src="https://www.zhihu.com/equation?tex=E_n" alt="E_n" class="ee_img tr_noresize" eeimg="1">
contains <img src="https://www.zhihu.com/equation?tex=x" alt="x" class="ee_img tr_noresize" eeimg="1">).

Finally we talk about connected sets. The definition of connected sets
in this book is little different from general topology. Usually we say
<img src="https://www.zhihu.com/equation?tex=A" alt="A" class="ee_img tr_noresize" eeimg="1"> is connected if <img src="https://www.zhihu.com/equation?tex=A" alt="A" class="ee_img tr_noresize" eeimg="1"> can be written as union of two disjoint open
set. And the statement <img src="https://www.zhihu.com/equation?tex=\bar{A}\cap B" alt="\bar{A}\cap B" class="ee_img tr_noresize" eeimg="1"> <img src="https://www.zhihu.com/equation?tex=A\cap \bar{B}" alt="A\cap \bar{B}" class="ee_img tr_noresize" eeimg="1"> are empty is an
consequence of usual definition (Lemma 23.1 in Munkres' Topology). This
is easy since <img src="https://www.zhihu.com/equation?tex=A=B^c" alt="A=B^c" class="ee_img tr_noresize" eeimg="1"> and <img src="https://www.zhihu.com/equation?tex=B" alt="B" class="ee_img tr_noresize" eeimg="1"> is open implies <img src="https://www.zhihu.com/equation?tex=A" alt="A" class="ee_img tr_noresize" eeimg="1"> is closed. Thus <img src="https://www.zhihu.com/equation?tex=A" alt="A" class="ee_img tr_noresize" eeimg="1">
and <img src="https://www.zhihu.com/equation?tex=B" alt="B" class="ee_img tr_noresize" eeimg="1"> is both open and closed. The connected subsets of the line have
a particularly simple structure: every point between two points in
connected subsets is in connected subsets. This simple structure is by
<img src="https://www.zhihu.com/equation?tex=\mathbb{R}^1" alt="\mathbb{R}^1" class="ee_img tr_noresize" eeimg="1"> being an ordered set.

Numerical Sequences and Series
==============================

Limit of numerical sequences
----------------------------

In this chapter, we give some basic properties of limits and some
convergence test of series. First we talk about limit in metric space.
One conclusion is the converse part of the sequence lemma (Lemma 21.2 in
Munkres' Topology). For a limit point <img src="https://www.zhihu.com/equation?tex=p" alt="p" class="ee_img tr_noresize" eeimg="1"> of <img src="https://www.zhihu.com/equation?tex=E" alt="E" class="ee_img tr_noresize" eeimg="1">, we can obtain a
sequence in <img src="https://www.zhihu.com/equation?tex=E" alt="E" class="ee_img tr_noresize" eeimg="1"> which converges to <img src="https://www.zhihu.com/equation?tex=p" alt="p" class="ee_img tr_noresize" eeimg="1"> (Theorem 3.2 (d)). And the limit
in metric space is unique (Theorem 3.2 (b)). Then we talk about
algebraic operations on limit process in <img src="https://www.zhihu.com/equation?tex=\mathbb{R}^1" alt="\mathbb{R}^1" class="ee_img tr_noresize" eeimg="1"> and in
<img src="https://www.zhihu.com/equation?tex=\mathbb{R}^n" alt="\mathbb{R}^n" class="ee_img tr_noresize" eeimg="1">, like addition, scalar multiplication, multiplication and
division on convergent sequences.

Theorem 3.6 is a converse conclusion of Theorem 3.2 (d). Theorem 3.2 (d)
says given a limit point of set <img src="https://www.zhihu.com/equation?tex=A" alt="A" class="ee_img tr_noresize" eeimg="1">, we can obtain a convergent sequence
from <img src="https://www.zhihu.com/equation?tex=A" alt="A" class="ee_img tr_noresize" eeimg="1">. Theorem 3.6 guarantees the existence of the limit point for a
sequence in compact set. The existence of the subsequence is also by the
converse part of the sequence lemma (Lemma 21.2 in Munkres' Topology).

In Theorem 3.7, we show the subsequential limits form a closed set,
which is important in definition of <img src="https://www.zhihu.com/equation?tex=\limsup" alt="\limsup" class="ee_img tr_noresize" eeimg="1">. Given a sequence <img src="https://www.zhihu.com/equation?tex=(s_n)" alt="(s_n)" class="ee_img tr_noresize" eeimg="1">,
let set <img src="https://www.zhihu.com/equation?tex=E" alt="E" class="ee_img tr_noresize" eeimg="1"> contains all limits of subsequence. The idea of the proof of
Theorem 3.7 is to draw a subsequence from each converge subsequence
which the limit is converge to the limit point of <img src="https://www.zhihu.com/equation?tex=E" alt="E" class="ee_img tr_noresize" eeimg="1">.

Then we talk about the Cauchy sequence. Let set <img src="https://www.zhihu.com/equation?tex=E_N" alt="E_N" class="ee_img tr_noresize" eeimg="1"> consists of the
points <img src="https://www.zhihu.com/equation?tex=p_N, p_{N+1}, p_{N+2},\dots" alt="p_N, p_{N+1}, p_{N+2},\dots" class="ee_img tr_noresize" eeimg="1">. The equivalent of <img src="https://www.zhihu.com/equation?tex=(p_n)" alt="(p_n)" class="ee_img tr_noresize" eeimg="1"> is a
Cauchy sequence is <img src="https://www.zhihu.com/equation?tex=\lim_{N\to \infty}\operatorname{diam}E_N=0" alt="\lim_{N\to \infty}\operatorname{diam}E_N=0" class="ee_img tr_noresize" eeimg="1">.

Here is a theorem about limit of compact sets:

If <img src="https://www.zhihu.com/equation?tex=K_n" alt="K_n" class="ee_img tr_noresize" eeimg="1"> is a sequence of compact sets in metric space <img src="https://www.zhihu.com/equation?tex=X" alt="X" class="ee_img tr_noresize" eeimg="1"> such that
<img src="https://www.zhihu.com/equation?tex=K_n\supset K_{n+1}" alt="K_n\supset K_{n+1}" class="ee_img tr_noresize" eeimg="1"> and <img src="https://www.zhihu.com/equation?tex=\lim\operatorname{diam}K_n=0" alt="\lim\operatorname{diam}K_n=0" class="ee_img tr_noresize" eeimg="1">, then
<img src="https://www.zhihu.com/equation?tex=\cap_1^{\infty}K_n" alt="\cap_1^{\infty}K_n" class="ee_img tr_noresize" eeimg="1"> consists of exactly one point.

*Empty set is compact since every finite set is compact*. So the
statement of Theorem 3.10 is ambiguous since there are two definitions
of diameter of empty set. We must exclude the case <img src="https://www.zhihu.com/equation?tex=K_n=\emptyset" alt="K_n=\emptyset" class="ee_img tr_noresize" eeimg="1">.
However, the author exclude the definition of diameter for empty set.
Thus we can assume <img src="https://www.zhihu.com/equation?tex=K_n" alt="K_n" class="ee_img tr_noresize" eeimg="1"> is not empty safely. Also, the metric space
guarantees the <img src="https://www.zhihu.com/equation?tex=\cap_1^\infty K_n" alt="\cap_1^\infty K_n" class="ee_img tr_noresize" eeimg="1"> consists exactly one point. Theorem
3.11 gives the equivalence of Cauchy sequence and convergent sequence in
<img src="https://www.zhihu.com/equation?tex=\mathbb{R}^n" alt="\mathbb{R}^n" class="ee_img tr_noresize" eeimg="1"> The proof of Theorem 3.11 uses boundedness and closed
sets is compact for metric space. If we only concern the convergence of
Cauchy sequence, we have concept \"completeness\" to describe the space
that every Cauchy sequence is convergent. For boundedness and
convergence, convergence implies boundedness, and the converse is true
if we talk about monotonic sequence. The limit is given by least upper
bound. The proof is easy if we using least upper bound

One important concept is upper and lower limits. For any real number
sequence, the upper and lower limits always exist if we allow the
<img src="https://www.zhihu.com/equation?tex=+\infty" alt="+\infty" class="ee_img tr_noresize" eeimg="1"> and <img src="https://www.zhihu.com/equation?tex=-\infty" alt="-\infty" class="ee_img tr_noresize" eeimg="1"> for limit. The definition of upper limit is the
sup of all limits of subsequence and we denote as
<img src="https://www.zhihu.com/equation?tex=\limsup_{n\to \infty}s_n=\sup E" alt="\limsup_{n\to \infty}s_n=\sup E" class="ee_img tr_noresize" eeimg="1">, where <img src="https://www.zhihu.com/equation?tex=E" alt="E" class="ee_img tr_noresize" eeimg="1"> contains all limits of
subsequence. The lower limits are similarly defined. Theorem 3.17 says
there actually exists a subsequence which the limit is <img src="https://www.zhihu.com/equation?tex=\limsup s_n" alt="\limsup s_n" class="ee_img tr_noresize" eeimg="1">
(Theorem 3.17 (a)), and for any number <img src="https://www.zhihu.com/equation?tex=x>\limsup s_n" alt="x>\limsup s_n" class="ee_img tr_noresize" eeimg="1">, <img src="https://www.zhihu.com/equation?tex=s_n<x" alt="s_n<x" class="ee_img tr_noresize" eeimg="1"> for
<img src="https://www.zhihu.com/equation?tex=n>N" alt="n>N" class="ee_img tr_noresize" eeimg="1"> with large enough <img src="https://www.zhihu.com/equation?tex=N" alt="N" class="ee_img tr_noresize" eeimg="1"> (Theorem 3.17 (b)). Then the uniqueness of
<img src="https://www.zhihu.com/equation?tex=\limsup s_n" alt="\limsup s_n" class="ee_img tr_noresize" eeimg="1"> is by these two properties.

The upper limit preserves the order. Precisely, <img src="https://www.zhihu.com/equation?tex=s_n\leq t_n" alt="s_n\leq t_n" class="ee_img tr_noresize" eeimg="1"> implies
<img src="https://www.zhihu.com/equation?tex=\limsup s_n\leq \limsup t_n" alt="\limsup s_n\leq \limsup t_n" class="ee_img tr_noresize" eeimg="1"> (Theorem 3.19). We can prove by
contradiction and by Theorem 3.17 (b). *Here is an useful trick. If we
assume <img src="https://www.zhihu.com/equation?tex=a>b" alt="a>b" class="ee_img tr_noresize" eeimg="1">, we can always find <img src="https://www.zhihu.com/equation?tex=c" alt="c" class="ee_img tr_noresize" eeimg="1"> with <img src="https://www.zhihu.com/equation?tex=a>b>c" alt="a>b>c" class="ee_img tr_noresize" eeimg="1">*.
<img src="https://www.zhihu.com/equation?tex=\limsup s_n>c> \limsup t_n" alt="\limsup s_n>c> \limsup t_n" class="ee_img tr_noresize" eeimg="1"> will leads a contradiction.

Finally author gives some special and important limits:

1.  If <img src="https://www.zhihu.com/equation?tex=p>0" alt="p>0" class="ee_img tr_noresize" eeimg="1">, then <img src="https://www.zhihu.com/equation?tex=\lim_{n\to \infty}\frac{1}{n^p}=0" alt="\lim_{n\to \infty}\frac{1}{n^p}=0" class="ee_img tr_noresize" eeimg="1">.

2.  If <img src="https://www.zhihu.com/equation?tex=p>0" alt="p>0" class="ee_img tr_noresize" eeimg="1">, then <img src="https://www.zhihu.com/equation?tex=\lim_{n\to \infty}\sqrt[n]{p}=0" alt="\lim_{n\to \infty}\sqrt[n]{p}=0" class="ee_img tr_noresize" eeimg="1">.

3.  <img src="https://www.zhihu.com/equation?tex=\lim_{n\to \infty}\sqrt[n]{n}=1" alt="\lim_{n\to \infty}\sqrt[n]{n}=1" class="ee_img tr_noresize" eeimg="1">

4.  If <img src="https://www.zhihu.com/equation?tex=p>0" alt="p>0" class="ee_img tr_noresize" eeimg="1"> and <img src="https://www.zhihu.com/equation?tex=\alpha" alt="\alpha" class="ee_img tr_noresize" eeimg="1"> is real, then
    <img src="https://www.zhihu.com/equation?tex=\lim_{n\to \infty}\frac{n^\alpha}{(1+p)^n}=0" alt="\lim_{n\to \infty}\frac{n^\alpha}{(1+p)^n}=0" class="ee_img tr_noresize" eeimg="1">.

5.  If <img src="https://www.zhihu.com/equation?tex=\left\lvert x\right\rvert<1" alt="\left\lvert x\right\rvert<1" class="ee_img tr_noresize" eeimg="1">, then <img src="https://www.zhihu.com/equation?tex=\lim_{n\to \infty}x^n=0" alt="\lim_{n\to \infty}x^n=0" class="ee_img tr_noresize" eeimg="1">

Many proofs use binomial theorem and \"sandwich\" rule. 

Convergent criterion and some special series
--------------------------------------------

One of most hardest and important part of this book is series and its
convergent criterion. We can also use Cauchy criterion for series. It
has some easy consequences:

1.  If <img src="https://www.zhihu.com/equation?tex=\sum a_n" alt="\sum a_n" class="ee_img tr_noresize" eeimg="1"> converges, <img src="https://www.zhihu.com/equation?tex=\lim a_n=0" alt="\lim a_n=0" class="ee_img tr_noresize" eeimg="1">.

2.  Absolutely convergence implies convergence.

3.  Comparison test: If <img src="https://www.zhihu.com/equation?tex=\left\lvert a_n\right\rvert<c_n" alt="\left\lvert a_n\right\rvert<c_n" class="ee_img tr_noresize" eeimg="1"> for <img src="https://www.zhihu.com/equation?tex=n>N_0" alt="n>N_0" class="ee_img tr_noresize" eeimg="1">,
    where <img src="https://www.zhihu.com/equation?tex=N_0" alt="N_0" class="ee_img tr_noresize" eeimg="1"> is some fixed integer, then <img src="https://www.zhihu.com/equation?tex=\sum c_n" alt="\sum c_n" class="ee_img tr_noresize" eeimg="1"> converges implies
    <img src="https://www.zhihu.com/equation?tex=\sum a_n" alt="\sum a_n" class="ee_img tr_noresize" eeimg="1"> converges.

Here is another useful criterion of convergence. This theorem says a
rather \"thin\" subsequence of <img src="https://www.zhihu.com/equation?tex=(a_n)" alt="(a_n)" class="ee_img tr_noresize" eeimg="1"> determines the convergence or
divergence of <img src="https://www.zhihu.com/equation?tex=\sum a_n" alt="\sum a_n" class="ee_img tr_noresize" eeimg="1">.

Suppose <img src="https://www.zhihu.com/equation?tex=a_1\geq a_2\geq a_3\geq a_4\geq \dots \geq 0" alt="a_1\geq a_2\geq a_3\geq a_4\geq \dots \geq 0" class="ee_img tr_noresize" eeimg="1">. Then the series
<img src="https://www.zhihu.com/equation?tex=\sum a_n" alt="\sum a_n" class="ee_img tr_noresize" eeimg="1"> converges if and only if the series
<img src="https://www.zhihu.com/equation?tex=\sum_{k=0}^\infty 2^ka_{2^k}" alt="\sum_{k=0}^\infty 2^ka_{2^k}" class="ee_img tr_noresize" eeimg="1"> converges.

The proof of this theorem is by showing the partial sum
<img src="https://www.zhihu.com/equation?tex=\sum_{k=0}^n 2^ka_{2^k}\leq 2\sum_{k=0}^m a_n" alt="\sum_{k=0}^n 2^ka_{2^k}\leq 2\sum_{k=0}^m a_n" class="ee_img tr_noresize" eeimg="1"> with <img src="https://www.zhihu.com/equation?tex=m>2^n" alt="m>2^n" class="ee_img tr_noresize" eeimg="1"> and
<img src="https://www.zhihu.com/equation?tex=\sum_{k=0}^n 2^ka_{2^k}\geq\sum_{k=0}^m a_n" alt="\sum_{k=0}^n 2^ka_{2^k}\geq\sum_{k=0}^m a_n" class="ee_img tr_noresize" eeimg="1"> with <img src="https://www.zhihu.com/equation?tex=m<2^n" alt="m<2^n" class="ee_img tr_noresize" eeimg="1">. By this
theorem, we can examine the convergence and divergence condition for
series <img src="https://www.zhihu.com/equation?tex=\sum \frac{1}{n^p}" alt="\sum \frac{1}{n^p}" class="ee_img tr_noresize" eeimg="1">, <img src="https://www.zhihu.com/equation?tex=\sum_{n=2}^\infty \frac{1}{n(\log n)^p}" alt="\sum_{n=2}^\infty \frac{1}{n(\log n)^p}" class="ee_img tr_noresize" eeimg="1">
and more complex series involving <img src="https://www.zhihu.com/equation?tex=\log n" alt="\log n" class="ee_img tr_noresize" eeimg="1">.

Before we continue our convergent criterion, we talk about the number
<img src="https://www.zhihu.com/equation?tex=e" alt="e" class="ee_img tr_noresize" eeimg="1">. We give it definition and shows it is the limit of an important
sequence: <img src="https://www.zhihu.com/equation?tex=\lim_{n\to \infty}(1+\frac{1}{n})^n=e" alt="\lim_{n\to \infty}(1+\frac{1}{n})^n=e" class="ee_img tr_noresize" eeimg="1">. By the estimation of
convergence speed, we can prove <img src="https://www.zhihu.com/equation?tex=e" alt="e" class="ee_img tr_noresize" eeimg="1"> is irrational.

There are another two convergent tests frequently used: the root tests
and the ratio tests:

Given <img src="https://www.zhihu.com/equation?tex=\sum a_n" alt="\sum a_n" class="ee_img tr_noresize" eeimg="1">, put <img src="https://www.zhihu.com/equation?tex=\alpha=\limsup\sqrt[n]{a_n}" alt="\alpha=\limsup\sqrt[n]{a_n}" class="ee_img tr_noresize" eeimg="1">. Then

1.  If <img src="https://www.zhihu.com/equation?tex=\alpha<1" alt="\alpha<1" class="ee_img tr_noresize" eeimg="1">, <img src="https://www.zhihu.com/equation?tex=\sum a_n" alt="\sum a_n" class="ee_img tr_noresize" eeimg="1"> converges.

2.  If <img src="https://www.zhihu.com/equation?tex=\alpha>1" alt="\alpha>1" class="ee_img tr_noresize" eeimg="1">, <img src="https://www.zhihu.com/equation?tex=\sum a_n" alt="\sum a_n" class="ee_img tr_noresize" eeimg="1"> diverges.

3.  If <img src="https://www.zhihu.com/equation?tex=\alpha=1" alt="\alpha=1" class="ee_img tr_noresize" eeimg="1">, the test gives no information.

Given <img src="https://www.zhihu.com/equation?tex=\sum a_n" alt="\sum a_n" class="ee_img tr_noresize" eeimg="1">. Then

1.  <img src="https://www.zhihu.com/equation?tex=\sum a_n" alt="\sum a_n" class="ee_img tr_noresize" eeimg="1"> converges if
    <img src="https://www.zhihu.com/equation?tex=\limsup\left\lvert\frac{a_{n+1}}{a_n}\right\rvert<1" alt="\limsup\left\lvert\frac{a_{n+1}}{a_n}\right\rvert<1" class="ee_img tr_noresize" eeimg="1">

2.  <img src="https://www.zhihu.com/equation?tex=\sum a_n" alt="\sum a_n" class="ee_img tr_noresize" eeimg="1"> diverges if
    <img src="https://www.zhihu.com/equation?tex=\limsup\left\lvert\frac{a_{n+1}}{a_n}\right\rvert\geq 1" alt="\limsup\left\lvert\frac{a_{n+1}}{a_n}\right\rvert\geq 1" class="ee_img tr_noresize" eeimg="1"> for all
    <img src="https://www.zhihu.com/equation?tex=n>N_0" alt="n>N_0" class="ee_img tr_noresize" eeimg="1">, where <img src="https://www.zhihu.com/equation?tex=N_0" alt="N_0" class="ee_img tr_noresize" eeimg="1"> is a fixed number.

The root tests are more powerful but the ratio tests are easy to apply.
The relation of two tests is:

For any sequence <img src="https://www.zhihu.com/equation?tex=(c_n)" alt="(c_n)" class="ee_img tr_noresize" eeimg="1"> of positive numbers,

<img src="https://www.zhihu.com/equation?tex=\liminf_{n\to \infty}\frac{c_{n+1}}{c_n}\leq \liminf_{n\to \infty}\sqrt[n]{c_n},\\" alt="\liminf_{n\to \infty}\frac{c_{n+1}}{c_n}\leq \liminf_{n\to \infty}\sqrt[n]{c_n},\\" class="ee_img tr_noresize" eeimg="1">



<img src="https://www.zhihu.com/equation?tex=\limsup_{n\to \infty}\sqrt[n]{c_n}\leq\limsup_{n\to \infty}\frac{c_{n+1}}{c_n}\\" alt="\limsup_{n\to \infty}\sqrt[n]{c_n}\leq\limsup_{n\to \infty}\frac{c_{n+1}}{c_n}\\" class="ee_img tr_noresize" eeimg="1">



*Here is another useful trick. If we prove <img src="https://www.zhihu.com/equation?tex=\limsup a_n<\beta" alt="\limsup a_n<\beta" class="ee_img tr_noresize" eeimg="1"> for any
<img src="https://www.zhihu.com/equation?tex=\beta>\alpha" alt="\beta>\alpha" class="ee_img tr_noresize" eeimg="1">, we have <img src="https://www.zhihu.com/equation?tex=\limsup a_n<\alpha" alt="\limsup a_n<\alpha" class="ee_img tr_noresize" eeimg="1">. This is also another
version of above trick: If we assume <img src="https://www.zhihu.com/equation?tex=a>b" alt="a>b" class="ee_img tr_noresize" eeimg="1">, we can always find <img src="https://www.zhihu.com/equation?tex=c" alt="c" class="ee_img tr_noresize" eeimg="1"> with
<img src="https://www.zhihu.com/equation?tex=a>b>c" alt="a>b>c" class="ee_img tr_noresize" eeimg="1">*.

Now we talk about convergent tests for power series and product of two
series. For power series, we have radius of convergence of
<img src="https://www.zhihu.com/equation?tex=\sum c_nz^n" alt="\sum c_nz^n" class="ee_img tr_noresize" eeimg="1">. And the test is familiar with root tests and ratio tests.
For product of two series, we first introduce the partial summation
formula:

<img src="https://www.zhihu.com/equation?tex=\sum_{n=p}^q a_n b_n=\sum_{n=p}^{q-1}A_n(b_n-b_{n+1})+A_q b_q-A_{p-1}b_p\\" alt="\sum_{n=p}^q a_n b_n=\sum_{n=p}^{q-1}A_n(b_n-b_{n+1})+A_q b_q-A_{p-1}b_p\\" class="ee_img tr_noresize" eeimg="1">


where <img src="https://www.zhihu.com/equation?tex=A_n=\sum_{k=0}^na_k" alt="A_n=\sum_{k=0}^na_k" class="ee_img tr_noresize" eeimg="1">. If <img src="https://www.zhihu.com/equation?tex=A_n" alt="A_n" class="ee_img tr_noresize" eeimg="1"> is bounded and <img src="https://www.zhihu.com/equation?tex=b_n" alt="b_n" class="ee_img tr_noresize" eeimg="1"> decrease
monotonically to 0, then <img src="https://www.zhihu.com/equation?tex=\sum a_n b_n" alt="\sum a_n b_n" class="ee_img tr_noresize" eeimg="1"> converges (Theorem 3.42). This
implies alternating series with absolute value of each term decreasing
monotonically to 0 converges. The strength of partial summation formula
is that the comparison test is a test for absolute convergence, but the
partial summation formula can be used for test for non-absolute
convergence.

The Cauchy product <img src="https://www.zhihu.com/equation?tex=\sum c_n" alt="\sum c_n" class="ee_img tr_noresize" eeimg="1"> where <img src="https://www.zhihu.com/equation?tex=\sum_{k=0}^na_kb_{n-k}" alt="\sum_{k=0}^na_kb_{n-k}" class="ee_img tr_noresize" eeimg="1"> is used for
product of two series <img src="https://www.zhihu.com/equation?tex=(\sum a_n)(\sum b_n)" alt="(\sum a_n)(\sum b_n)" class="ee_img tr_noresize" eeimg="1">. And it's partial sum
converges if one of series converges absolutely (Theorem 3.50). Theorem
3.51 shows the sum of Cauchy product is actually the product of two
series if the sum are converges.

Rearrangements
--------------

Finally in this chapter we talk about rearrangements of series. The
rearrangements of non-absolutely convergent series can be any value in
extended real field. More precisely, the <img src="https://www.zhihu.com/equation?tex=\liminf" alt="\liminf" class="ee_img tr_noresize" eeimg="1"> and <img src="https://www.zhihu.com/equation?tex=\limsup" alt="\limsup" class="ee_img tr_noresize" eeimg="1"> of
rearrangements can be any value in extended real field (Theorem 3.54).
This theorem is due to Riemann. But the rearrangements of absolutely
convergent series does not affect the limit.

If an infinite series converges, then the associative property holds (by
<img src="https://www.zhihu.com/equation?tex=b_k=a_{k_1+1}+a_{k_1+2}+\dots+a_{k_2}" alt="b_k=a_{k_1+1}+a_{k_1+2}+\dots+a_{k_2}" class="ee_img tr_noresize" eeimg="1"> and considering <img src="https://www.zhihu.com/equation?tex=\sum b_k" alt="\sum b_k" class="ee_img tr_noresize" eeimg="1">). But
a non converge series has no associative property (consider
<img src="https://www.zhihu.com/equation?tex=\sum (-1)^n" alt="\sum (-1)^n" class="ee_img tr_noresize" eeimg="1">).

Notes and Errata
----------------

We use Cauchy criterion. The finite sum has associative property, thus

<img src="https://www.zhihu.com/equation?tex=\sum_{k=n}^m a_k= r_n+\sum_{k=3i}^{k=3j}(\frac{1}{4k-3}+\frac{1}{4k-1}-\frac{1}{2k})+r_m\\" alt="\sum_{k=n}^m a_k= r_n+\sum_{k=3i}^{k=3j}(\frac{1}{4k-3}+\frac{1}{4k-1}-\frac{1}{2k})+r_m\\" class="ee_img tr_noresize" eeimg="1">


where <img src="https://www.zhihu.com/equation?tex=3i" alt="3i" class="ee_img tr_noresize" eeimg="1"> is the first number greater than <img src="https://www.zhihu.com/equation?tex=n" alt="n" class="ee_img tr_noresize" eeimg="1"> and <img src="https://www.zhihu.com/equation?tex=3j" alt="3j" class="ee_img tr_noresize" eeimg="1"> is the last
number less than <img src="https://www.zhihu.com/equation?tex=m" alt="m" class="ee_img tr_noresize" eeimg="1">. Notice:

<img src="https://www.zhihu.com/equation?tex=\sum_{k=3i}^{k=3j}(\frac{1}{4k-3}+\frac{1}{4k-1}-\frac{1}{2k})=\sum_{k=3i}^{k=3j}\frac{8k-3}{2k(4k-3)(4k-1)}\leq\sum_{k=3i}^{k=3j}\frac{C}{k^2}\leq\sum_{k=n}^{k=m}\frac{C}{k^2}\\" alt="\sum_{k=3i}^{k=3j}(\frac{1}{4k-3}+\frac{1}{4k-1}-\frac{1}{2k})=\sum_{k=3i}^{k=3j}\frac{8k-3}{2k(4k-3)(4k-1)}\leq\sum_{k=3i}^{k=3j}\frac{C}{k^2}\leq\sum_{k=n}^{k=m}\frac{C}{k^2}\\" class="ee_img tr_noresize" eeimg="1">


We know <img src="https://www.zhihu.com/equation?tex=\left\lvert r_n\right\rvert" alt="\left\lvert r_n\right\rvert" class="ee_img tr_noresize" eeimg="1">, <img src="https://www.zhihu.com/equation?tex=\left\lvert r_m\right\rvert" alt="\left\lvert r_m\right\rvert" class="ee_img tr_noresize" eeimg="1"> and
<img src="https://www.zhihu.com/equation?tex=\sum_{k=n}^{k=m}\frac{C}{k^2}" alt="\sum_{k=n}^{k=m}\frac{C}{k^2}" class="ee_img tr_noresize" eeimg="1"> tends to 0 for <img src="https://www.zhihu.com/equation?tex=n,m>N" alt="n,m>N" class="ee_img tr_noresize" eeimg="1"> for large enough
<img src="https://www.zhihu.com/equation?tex=N" alt="N" class="ee_img tr_noresize" eeimg="1">. So <img src="https://www.zhihu.com/equation?tex=\left\lvert\sum_{k=n}^m a_k\right\rvert" alt="\left\lvert\sum_{k=n}^m a_k\right\rvert" class="ee_img tr_noresize" eeimg="1"> tends to 0 for <img src="https://www.zhihu.com/equation?tex=n,m>N" alt="n,m>N" class="ee_img tr_noresize" eeimg="1">
for large enough <img src="https://www.zhihu.com/equation?tex=N" alt="N" class="ee_img tr_noresize" eeimg="1">.

Thus

<img src="https://www.zhihu.com/equation?tex=1+\frac{1}{3}-\frac{1}{2}+\frac{1}{5}+\frac{1}{7}-\frac{1}{4}+\frac{1}{9}+\frac{1}{11}-\frac{1}{6}\dots\\" alt="1+\frac{1}{3}-\frac{1}{2}+\frac{1}{5}+\frac{1}{7}-\frac{1}{4}+\frac{1}{9}+\frac{1}{11}-\frac{1}{6}\dots\\" class="ee_img tr_noresize" eeimg="1">


converges.

A simple rearrangement of a series is a rearrangement of the series in
which the positive terms of the rearranged series occur in the same
order as the original series and the negative terms occur in the same
order.

If <img src="https://www.zhihu.com/equation?tex=\sum a_n" alt="\sum a_n" class="ee_img tr_noresize" eeimg="1"> is a simple rearrangement of the Alternating Harmonic
Series, let <img src="https://www.zhihu.com/equation?tex=p_k" alt="p_k" class="ee_img tr_noresize" eeimg="1"> be the number of positive terms in the first k terms,
<img src="https://www.zhihu.com/equation?tex=\{a_1, a_2, a_3,\dots,a_k\}" alt="\{a_1, a_2, a_3,\dots,a_k\}" class="ee_img tr_noresize" eeimg="1">. The asymptotic density, <img src="https://www.zhihu.com/equation?tex=\alpha" alt="\alpha" class="ee_img tr_noresize" eeimg="1">, of the
positive terms in the rearrangement is
<img src="https://www.zhihu.com/equation?tex=\alpha = \lim_{k\to \infty} \frac{p_k}{k}" alt="\alpha = \lim_{k\to \infty} \frac{p_k}{k}" class="ee_img tr_noresize" eeimg="1">. if the limit exists.

A simple rearrangement of the Alternating Harmonic Series converges to
an extended real number if and only if <img src="https://www.zhihu.com/equation?tex=\alpha" alt="\alpha" class="ee_img tr_noresize" eeimg="1">, the asymptotic density
of the positive terms in the rearrangement, exists.

Moreover, the sum of a rearrangement with asymptotic density <img src="https://www.zhihu.com/equation?tex=\alpha" alt="\alpha" class="ee_img tr_noresize" eeimg="1"> is
<img src="https://www.zhihu.com/equation?tex=\ln 2+\frac{1}{2}\ln (\frac{\alpha}{1-\alpha})" alt="\ln 2+\frac{1}{2}\ln (\frac{\alpha}{1-\alpha})" class="ee_img tr_noresize" eeimg="1">

We choose real-valued sequences <img src="https://www.zhihu.com/equation?tex=(a_n)" alt="(a_n)" class="ee_img tr_noresize" eeimg="1">, <img src="https://www.zhihu.com/equation?tex=(b_n)" alt="(b_n)" class="ee_img tr_noresize" eeimg="1"> such that <img src="https://www.zhihu.com/equation?tex=a_n\to a" alt="a_n\to a" class="ee_img tr_noresize" eeimg="1">,
<img src="https://www.zhihu.com/equation?tex=b_n\to b" alt="b_n\to b" class="ee_img tr_noresize" eeimg="1">, <img src="https://www.zhihu.com/equation?tex=a_n<b_n" alt="a_n<b_n" class="ee_img tr_noresize" eeimg="1">, <img src="https://www.zhihu.com/equation?tex=b_1>0" alt="b_1>0" class="ee_img tr_noresize" eeimg="1">.

But no such restriction that <img src="https://www.zhihu.com/equation?tex=b_2>a_1" alt="b_2>a_1" class="ee_img tr_noresize" eeimg="1">, so the second step may not be
achieved, except we mean <img src="https://www.zhihu.com/equation?tex=m_2" alt="m_2" class="ee_img tr_noresize" eeimg="1"> here is greater or equal to 0. If
<img src="https://www.zhihu.com/equation?tex=b_2<a_1" alt="b_2<a_1" class="ee_img tr_noresize" eeimg="1">, we just let <img src="https://www.zhihu.com/equation?tex=m_2=0" alt="m_2=0" class="ee_img tr_noresize" eeimg="1">, which means no <img src="https://www.zhihu.com/equation?tex=P_n" alt="P_n" class="ee_img tr_noresize" eeimg="1"> term added. If the
last terms are <img src="https://www.zhihu.com/equation?tex=P_{m_n}" alt="P_{m_n}" class="ee_img tr_noresize" eeimg="1">, then <img src="https://www.zhihu.com/equation?tex=m_n>0" alt="m_n>0" class="ee_img tr_noresize" eeimg="1">. And we have <img src="https://www.zhihu.com/equation?tex=x_n-P_{m_n}<b_n" alt="x_n-P_{m_n}<b_n" class="ee_img tr_noresize" eeimg="1"> by
construction of <img src="https://www.zhihu.com/equation?tex=x_n" alt="x_n" class="ee_img tr_noresize" eeimg="1"> (<img src="https://www.zhihu.com/equation?tex=m_n" alt="m_n" class="ee_img tr_noresize" eeimg="1"> is the smallest integers such that
<img src="https://www.zhihu.com/equation?tex=x_n>b_n" alt="x_n>b_n" class="ee_img tr_noresize" eeimg="1"> and <img src="https://www.zhihu.com/equation?tex=m_n>0" alt="m_n>0" class="ee_img tr_noresize" eeimg="1"> guarantees there is a <img src="https://www.zhihu.com/equation?tex=P_{m_n}" alt="P_{m_n}" class="ee_img tr_noresize" eeimg="1"> in <img src="https://www.zhihu.com/equation?tex=x_n" alt="x_n" class="ee_img tr_noresize" eeimg="1">). Then we
have <img src="https://www.zhihu.com/equation?tex=x_n-b_n<P_{m_n}" alt="x_n-b_n<P_{m_n}" class="ee_img tr_noresize" eeimg="1">. and <img src="https://www.zhihu.com/equation?tex=x_n>b_n" alt="x_n>b_n" class="ee_img tr_noresize" eeimg="1"> guarantees
<img src="https://www.zhihu.com/equation?tex=\left\lvert x_n-b_n\right\rvert<P_{m_n}" alt="\left\lvert x_n-b_n\right\rvert<P_{m_n}" class="ee_img tr_noresize" eeimg="1">.

For another inequality, <img src="https://www.zhihu.com/equation?tex=y_n<a_n" alt="y_n<a_n" class="ee_img tr_noresize" eeimg="1"> and <img src="https://www.zhihu.com/equation?tex=y_n+Q_{k_n}>a_n" alt="y_n+Q_{k_n}>a_n" class="ee_img tr_noresize" eeimg="1"> implies
<img src="https://www.zhihu.com/equation?tex=Q_{k_n}>a_n-y_n" alt="Q_{k_n}>a_n-y_n" class="ee_img tr_noresize" eeimg="1"> and thus
<img src="https://www.zhihu.com/equation?tex=Q_{k_n}>\left\lvert a_n-y_n\right\rvert=\left\lvert y_n-a_n\right\rvert" alt="Q_{k_n}>\left\lvert a_n-y_n\right\rvert=\left\lvert y_n-a_n\right\rvert" class="ee_img tr_noresize" eeimg="1">.
Since <img src="https://www.zhihu.com/equation?tex=P_n\to 0" alt="P_n\to 0" class="ee_img tr_noresize" eeimg="1"> and <img src="https://www.zhihu.com/equation?tex=Q_n \to 0" alt="Q_n \to 0" class="ee_img tr_noresize" eeimg="1">, we see that <img src="https://www.zhihu.com/equation?tex=x_n\to b" alt="x_n\to b" class="ee_img tr_noresize" eeimg="1">, <img src="https://www.zhihu.com/equation?tex=y_n\to a" alt="y_n\to a" class="ee_img tr_noresize" eeimg="1">

Let <img src="https://www.zhihu.com/equation?tex=x'_{m_n+1}=x'_{m_n+2}=\dots=x'_{m_{n+1}}=x_n" alt="x'_{m_n+1}=x'_{m_n+2}=\dots=x'_{m_{n+1}}=x_n" class="ee_img tr_noresize" eeimg="1">,
<img src="https://www.zhihu.com/equation?tex=x'_{k_n+1}=x'_{k_n+2}=\dots=x'_{k_{n+1}}=x_{n-1}" alt="x'_{k_n+1}=x'_{k_n+2}=\dots=x'_{k_{n+1}}=x_{n-1}" class="ee_img tr_noresize" eeimg="1">. We have the partial
sum <img src="https://www.zhihu.com/equation?tex=s_n" alt="s_n" class="ee_img tr_noresize" eeimg="1"> satisfies <img src="https://www.zhihu.com/equation?tex=s_n<x'_n" alt="s_n<x'_n" class="ee_img tr_noresize" eeimg="1"> for all <img src="https://www.zhihu.com/equation?tex=n" alt="n" class="ee_img tr_noresize" eeimg="1">. Thus by Theorem 3.19,
<img src="https://www.zhihu.com/equation?tex=\limsup s_n\leq \limsup x'_m=\lim x'_m=b" alt="\limsup s_n\leq \limsup x'_m=\lim x'_m=b" class="ee_img tr_noresize" eeimg="1">. The <img src="https://www.zhihu.com/equation?tex=\liminf" alt="\liminf" class="ee_img tr_noresize" eeimg="1"> part are
almost the same.
