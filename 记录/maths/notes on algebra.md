###代数

**Def1** **子群** 群$(G, *)$的子群为$(H,*),H⊆G$

**Theo1** **Cayley表示定理** 任何一个子群与其上的变换群（集合上若干个变换作成的群）的子群同构（**习题1**）

**Def3** **右正则表示** $G_r={ τ_a ∶a∈G},τ_a (x)=x*a^(-1),∀x∈G$（**习题** 证明任何一个群与它的右正则表示同构）

**Def4** **置换群**

**Def5** **对称群** n元集合上最大的置换群（全体置换作成的群）称为一个$n$元对称群$S_n$；

**Prop1** $S_n$有$n!$个元

**习题1** $S_3$是最小的有限非交换群（一个有限非交换群至少有6个元）

Def6 循环置换 $S_n$ $$\pi: \begin{pmatrix}i_!,&i_2&\cdots&i_k\\
i_2&i_3&\cdots&i_1\\
\end{pmatrix}$$
$\pi$称为一个$k$-循环置换
简记为$(i_1,i_2  ,…,i_k )$

**Exp1** $S_5$ $$\begin{pmatrix}1,&2&3&4&5\\
2&3&1&4&5\\
\end{pmatrix}$$；特别地，还有$1$-循环置换

**Theo2** $S_n$中每一个$n$元置换$\pi$都可以写成若干个互相没有共同数字的循环置换的乘积（**Hint**归纳）
**Remark1** 循环群在置换群里起到了因子的作用，类似质数在正整数的作用，发挥了一种原子的作用

**Theo3** 每一个有限群都与一个置换群同构

**习题2** 证明两个不相连的循环置换可交换

**习题3** $(i_1,   i_2,…,i_k )^(-1)=(i_k,i_(k-1),…,i_1)$

**Def7** **循环群** 若群$(G,*)$的每个元都是$G$中某个固定元$a$的乘方（或幂次），称$G$为循环群，也说$G$为由$a$生成的，$G=(a)$，$a$称为$G$的生成元

**Exp2** 整数加法群$(Z,+),a=1；(Z_p,+),∀a,b∈Z_p,a+b=a+b \hspace{0.1cm} mod \hspace{0.1cm} p$ ; $1∈Z_p,∀a∈Z_p,a= Z_p,a=\underbrace{(1+⋯+1)}_\textrm{a个}$

这两个群从同构的意义上来说就是所有的循环群
**Theo4** 循环群$(G,*)，G=(a)$的结构完全由$a$的阶来决定：
(1) $a$的阶$=0$ or $+∞$，则$G \sim (z,+)$
(2) $a$的阶为$p∈N$,则$G \sim (Z_p ,+)$

**Exp3** 每个群都至少有它自己和${e}$两个子群

**The5** 设$(G,*)$是群，$H⊆G$是$G$的子集，$(H,*)$是其子群$⟺$
1. $a,b∈H ⟹ a*b∈H$
2. $a∈H ⟹ a^{-1}∈H$

**The6** 设$(G,*)$是群，$H⊆G$是$G$的子集，$(H,*)$是其子群 $⟺ ∀a, b∈H, a*b^{-1}∈H$

**Def8** 设$(G,*)$是一个群，$(H,*)$是一个子群，在$G$上约定一个关系$\sim$（右等价）,$∀a,b∈G,if \hspace{0.1cm} a*b^{-1}∈H, then \hspace{0.1cm} a \sim b$

**Prop2** $\sim$是一个等价关系

**右陪集** 由等价关系$\sim$所决定的$G$的分类中的称为H的右陪集，$a∈G$,包含$a$的右陪集记为$Ha$

**Remark2** 包含元素$a$的右陪集$Ha= \{ h*a \hspace{0.1cm}|\hspace{0.1cm} h∈H \} $
**Proof** $⟹: ∀b∈Ha,b \sim a,a*b^{-1}∈H⟹∃k∈H,a*b^{-1}=k⟺ b=k^{-1}*a∈\{h*a\hspace{0.1cm} |\hspace{0.1cm}  h∈H\},for\hspace{0.1cm} H \hspace{0.1cm} is\hspace{0.1cm} a \hspace{0.1cm}subgroup,k∈H\hspace{0.1cm} implies \hspace{0.1cm}that \hspace{0.1cm}k^{-1}∈H  $
$⟸:$

**Remark3** $a,a'∈G,Ha=Ha'⟺a~a'$
同理，约定关系 $\sim$（左等价）,$a~b⟺b^{-1}*a∈H$,我们称为其所决定的$G$的分类中的为$H$的左陪集
**The7** （虽然因为群$G$不一定满足交换律，）$(G, *)$群，$(H, *)$子群，$H$的右陪集个数与左陪集个数相等，它们或为$∞$ ，或为有限数且相等

