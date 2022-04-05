yoneda lemma

https://www.math3ma.com/blog/the-yoneda-embedding

e.g. suppose X and Y are topological spaces and let ∙ denote the one-point space and I and S^1 the unit interval and the circle. 

Then, X and Y have the same cardinality if and only if hom(∙, X) ≅ hom(∙,Y).

X and Y have the same path space if and only if hom(I,X)≅hom(I,Y).

X and Y have the same (free) loop space if and only if hom(S^1,X)≅hom(S1,Y).

$X\mapsto \text{hom}(-,X)$

Where does 
hom(−,X) live? It, too, lives in a category! As we mentioned long ago, there is a category $Set^{C^{op}}$ whose objects are functors C^op→Set and whose morphisms are natural transformations.

there is a functor Y:C→$Set^{C^{op}}$ that sends an object X to hom(−,X) and a morphism f:X→Y to the natural transformation  f∗:hom(−,X)→hom(−,Y). Each component of this natural transformation is given by postcomposing with 
f. Functors in the category 
$Set^{C^{op}}$ are called presheaves, and the presheaves we're interested in—i.e. those of the form hom(−,X)—are called representable functors. 

for every pair X,Y in C, the function

$\text{hom}(X,Y)\to\mathsf{Nat}(\text{hom}(-,X),\text{hom}(-,Y))
$

defined by $f\mapsto f_*
$ (here f_* sends a morphism g:Z \to X to the composition $f\circ g:Z\to Y
$) should be a bijection, i.e is fully faithful and is said to embed the category C into Set^{c^{op}}.

Injectivity is clear: if f, g: X \to Y are distinct morphisms, then their pushforwards f_* and g_* are distinct.

Surjectivity means given any natural transformation $\eta\colon\text{hom}(-,X)\to\text{hom}(-,Y)
$, there is a morphism f: X \to Y so that \eta = f_*.

Yoneda lemma says something much stronger, it tells us something about natural transformations hom(-, X) \to F for any functor F: C^{op} \to Set. And morphisms X \to Y are in bijection with natural transformations hom(-,X) \to hom(-,Y) is  merely a consequence of the Yoneda lemma.

More generally, given any functor F:C→D, there is a function hom_C(X,Y)→hom_D(F(X),F(Y)) given by f↦F(f). If this map is an injection, F is called faithful, if it is a surjection, F is called full, and if it is a bijection, F is called fully faithful. 

The Yoneda Lemma
For any functor 
F
:
C
^o
p
→
S
e
t
 and any object 
X
 in 
C
, natural transformations 
hom
(
−
,
X
)
→
F
 are in bijection with  elements in the set 
F
(
X
)
. That is,
N
a
t
(
hom
(
−
,
X
)
,
F
)
≅
F
(
X
)
.



