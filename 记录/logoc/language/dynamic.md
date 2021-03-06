#! https://zhuanlan.zhihu.com/p/409988015

<br/>

*由L. T. F. Kanud of Vihara译出(译：[cjy](https://www.douban.com/people/140626077/)、校：[zz](https://www.douban.com/people/64695086/))
曾载于豆瓣：https://www.douban.com/note/802851280/ 

*该词条由以下学者合作完成
[Rick Nouwen](http://ricknouwen.org/)(rnouwen@protonmail.com) 乌得勒支大学语言、文学与传播学副教授，主要关注于命题与可能世界、更新与蕴含、关于意义推理的博弈论、迭代最佳响应算法、贝叶斯推断、不确定性，信息与理性言语行为模型、含混性与理性言语行为模型

[Adrian Brasoveanu](https://people.ucsc.edu/~abrsvn/)(abrsvn@ucsc.edu) 加州大学圣克鲁兹分校语言学系教授，主要关注于语义学与语用学——平行于个体、时态、模态、程度域的量化与照应；对不同语义与语用框架进行整合的方法；各种结构的跨语言语义；

[Jan van Eijck](https://staff.fnwi.uva.nl/d.j.n.vaneijck2/)(jan@vaneijck.org) 阿姆斯特丹CWI高级研究员，阿姆斯特丹ILLC计算语义学兼职正教授

[Albert Visser](https://www.uu.nl/medewerkers/AVisser)(a.visser@uu.nl) 乌得勒支大学哲学与宗教系教授 算术的逻辑方面、模态逻辑、逻辑哲学、结构主义、逻辑与语言以及语言哲学。

*参考文献部分请参原文：https://plato.stanford.edu/archives/win2016/entries/dynamic-semantics/#Bib

<br/>

*First published Mon Aug 23, 2010; substantive revision Tue Jul 12, 2016*

<br/>

动态语义学是一个自然语言语义学的视角，它强调时间中信息的增长。它是一种这样的意义表征方法，其将其中的文本(text)或话语(discourse)的片段视为，去用新信息更新一个现存语境(context)的指令，而结果就是一个被更新的语境。有一句口号是这样形容的， “意义就是语境变换潜能(context change potential)”

注意该视角的抽象性是十分重要的，以保证其免受各种各样不合理的非议。其中之一就是，人们可以很轻松地说动态语义学或者更新语义学(update semantics)至少部分承诺了一种关于语义的内在论(internalist)想法，因为信息状态(information states)是“内在的”——在这种意义上，这些信息状态将完全包含在个体的心灵/大脑中。换句话说，人们可能会将动态语义的信息状态当作Putnam (1975)所谓的“一种状态，唯心主义方法论上意义上的东西”。见词条[scientific realism](https://plato.stanford.edu/entries/scientific-realism/)、[computational theory of mind](https://plato.stanford.edu/entries/computational-mind/)、[externalism about mental content](https://plato.stanford.edu/entries/content-externalism/) 以及[narrow mental content](https://plato.stanford.edu/entries/content-narrow/)。然而，一般性框架并没有说状态到底是什么。状态完全可以包含解释者身处于中的环境，因此也就包含了“外在”成分。

第二个可能的误解是，动态语义或更新语义是一种完全相反于经典真值条件语义(truth conditional semantics)的东西(比较词条[classical logic](https://plato.stanford.edu/entries/logic-classical/)与[first-order model theory](https://plato.stanford.edu/entries/modeltheory-fo/))。事实上，如该词条中马上将要澄清的一样，动态语义提供了一种对真值条件语义的泛化与推广，而不是一个迥然不同的替代方案。经典意义变成了话语行动成功的前置条件。动态语义主张的是，组合性(compositional)意义有着函数或者关系的本质，并且经典意义可以从关系性动态意义中复原，作为对后者输入的坐标的投影。

对这个抽象框架的使用之关键不是给出一个经验性预测。这个任务是于该框架内的具体实现的任务。动态语义框架(i) 提供了一个思考的方向，以及(ii) 允许我们从对该框架的数学研究中引入一些方法。由此可见，自然语言的意义是否内在地是动态的，这个问题并没有一个经验答案。不过，还是可以说的是，将解释，作为线性有序过程的研究，还是颇有成效与收获。

由于动态语义学关注的是发送者和接收者的话语行为，所以它接近于，在哲学中的一种以使用为导向的，对意义的研究进路，就像维特根斯坦(Wittgenstein)与达米特(Dummett)的工作一样。然而，我们需要避免简单地将动态语义学同这些进路等同起来。动态语义作为一种抽象性框架完全兼容于许多关于意义和解释的哲学观点。动态语义的目标是建模意义与解释。你完全可以做到这一点而不必回答，例如像，到底什么使得主体与这些意义成为相关联的，这样的广义哲学问题。举个例子，在动态谓词逻辑(dynamic predicate logic(DPL))中，我们将“horse”的意义考虑为给定了的，而不对关于，对一个主体来说拥有概念“horse”究竟意味着什么，这样的问题做出任何实质性主张，我们仅仅规定主体拥有这个概念。这并不是说，像上面这样的问题——其是维特根斯坦与达米特工作的中心——最终并没有必要得到回答，而是说，它只是一个有趣的模型，即使我们不回答这些问题。(注意，尝试给出一个关于意义的系统性(systematic)与组合性的说明的动态语义学，将同晚期维特根斯坦哲学的精神完全不同。)

一个之于动态语义学的进路是话语表达理论话语表达理论([discourse representation theory](https://plato.stanford.edu/entries/discourse-representation-theory/)(DRT, Kamp 1981))。(与Kamp的方法密切相关的是Irene Heim的文档变换语义学(file change semantics(FCS, Heim 1983a))以及Seuren 1985的话语语义学(discourse semantics)。在DRT中，意义是被称作话语表达结构(discourse representation structures(DRSs))的东西。这些结构是一种包含了信息之具体片段的数据库。DRS本身是一个静态的对象，但DRT可以被称之为一个动态语义框架，因为它允许我们将意义的组合过程考虑为一个，话语表达结构的合并过程。在这种方法下，信息的变化变成了解释过程中的一个不可分割的部分。

在这个词条中，我们主要关注于之于动态语义的第二种进路，虽然我们也将会在其中同DRT做一些比较。在第二种进路下，动态意义是一种活动(actions)，这是一种通过它们所引起的变化而被个体化东西。其是一种联系于动态谓词逻辑(Groenendijk and Stokhof 1991a)的进路。根据动态语义传统，一个意义，就是一个如何修改接收者信息状态的说明。比如它可以是一个函数，该函数将一个旧的信息状态映射到一个，被其意义所体现的信息更新后的信息状态上。或者，它可以是一个关系，其表达了一种意义带来的信息变化。(关于该传统的早期工作，见Groenendijk and Stokhof 1991a,b; Muskens 1991; Dekker 1993; Vermeulen 1993; van Eijck 1994; Vermeulen 1994; Krahmer 1995; van den Berg 1996; Groenendijk et al. 1996; Aloni 1997; Muskens et al. 1997)。


<br/><br/>


目录：

<br/>

1. Interpretation as a Process
   
	1.1 Update Semantics

	1.2 Propositional Logic as an Update Logic

	1.3 Programming Statements and their Execution

	1.4 The notion of context in dynamic semantics

2. Dynamic Predicate Logic
   
	2.1. Conceptual Underpinnings

	2.2 Specifying Dynamic Predicate Logic

	2.3 Example: donkey sentences

	2.4 Dynamic generalized quantification

	2.5 Dynamics beyond anaphora

3. Presupposition
   
	3.1 Presupposition and dynamic semantics of connectives

	3.2 Presuppositions and Dynamic Epistemic Logic

	3.3. Beyond presupposition

4. Encoding Dynamics in Typed Logic
   
5. Conclusion
   
	Bibliography
________________________________________










<br/><br/>












1. Interpretation as a Process
   
陈述句的解释可以被视为一个产品或者一个过程。在将其视为一个产品的观点下，人们聚焦的是给定情境下的真值，这个概念。而在将其是作为过程的这个观点下，一个命题的解释，将被视为信息更新的步骤，后者将允许我们用新的，更准确的知识状态去替换给定的一个知识的旧的状态。动态语义学关注的是将解释视作为一个过程。

<br/>

1.1 Update Semantics

更新语义是一个可以实现“解释即过程”——这个想法的特定方式。更新语义背后的核心思想非常简单。我们以一个依顺序接收信息的听者/接收者的一个简单模型开始。在每一刻，该听者都处于某一种状态：她掌握某种信息。以一种系统性的方式传达过来的新信息，将会修改这个状态。现在，我们将这个新传达过来的项目的意义考虑为，它们对接收者信息状态之改变所产生的贡献。因此，意义就可以被视为活动，或者更准确地说，活动类型(action types)。它们并不是一种，某个给定状态到另一个状态的具体变化，而是这些变化之普遍所有的共同之处。

<br/>

1.2	Propositional Logic as an Update Logic

命题逻辑(否定、析取与合取的逻辑)可以被以如下地方式视作是一个更新逻辑(update logic)。考虑一下以下情况，我们有的如下三个基本命题p，q和r，以及关于三者的真值我们什么都不知道。因此，这里就有八种可能性：$\{\overline{pqr} , p\overline{qr} , \overline{p}q\overline{r} ,\overline{pq}r,pq\overline{r} ,p\overline{q}r, \overline{p}qr,pqr\}$ 。在此，$\overline{pqr}$ 将被读作$p$,$q$,$r$中没有任何一个为真；$p\overline{qr}$ 就是，$p$为真，但$q,r$为假，其他同理。如果现在宣告$¬p$(非$p$)为真，那么这八种可能性中的四种就会消失掉，而遗留下来的就是$\{\overline{pqr},\overline{p}q\overline{r} , \overline{pq}r, \overline{p}qr\}$。如果接下来$q∨¬r$被宣告了，那么就是……以及如此等等。我们可以将像$¬p$与$q∨¬r$这样命题的意义视作是，从可能性的集合到其子集的映射。

可能性的集合表达了知识的状态。例如$\{\overline{pqr} ,p\overline{qr}p(qr), \overline{p}q\overline{r}, \overline{pq}r, pq\overline{r}, p\overline{q}r, \overline{p}qr, pqr\}$表达了，对于命题$p$,$q$,$r$完全无知的状态。像$\{pq\overline{r}\}$这样的单元集就表达了我们关于这三个命题有充分了解的状态。而空集$∅$，则表达了从对，关于$p$,$q$,$r$的不相容的断言的处理中，得出的不一致，这个状态。在此，我们列出了我们命题逻辑语句的动态意义：

-	原子句(Atomic statements). 它们是$p$,$q$,$r$。对应的更新活动是，在当前语境中选出，其中命题符号没有被删除(不带有上划线)的那些可能性
-	否定句(Negated statements). 形式为$¬ϕ$。对应的更新活动是，在当前语境中选出，由语句$ϕ$所选出的可能性集的补集。
-	语句的合取(Conjunctions of statements). 形式为$ϕ∧ψ$。对应的更新活动是，在当前语境中选出，由语句$ϕ$与$ψ$从当前语境中所选出的可能性集的交集。 
-	语句的析取(Disjunctions of statements). 形式为$ϕ∨ψ$。对应的更新活动是，在当前语境中选出，由语句$ϕ$与ψ从当前语境中所选出的可能性集的并集。

<br/>

如此，我们就将命题联结词的意义给定为了，从一个表达知识状态的旧语境，到，一个表达知识状态的新语境的运算，这个表达知识状态的新语境则是对命题信息进行处理后的结果。
	
<br/>

1.3    Programming Statements and their Execution

将更新语义的活动同编程语句及其执行相比较是十分具有启发性的。这样的比较能够让我们初步了解量化是如何在动态环境下工作的。命令式语义的编程语句在机器状态的背景下得到解释(或者“执行”)，其中机器状态可被视作为，向寄存器分配值。假设寄存器由变量$x$,$y$,$z$命名，而这些寄存器的内容是自然数，那么如下就是一个机器状态：

| x	| 12  |
|---|---  | 
| y	| 117 |
| z	| 3   |

如果语句$z:=x$在这个状态中被执行，即被“解释”(在C语言句法中，这个语句将具有更简单的形式$z=x$)，那么结果就说一个新的机器状态：

| x	| 12  |
|---|---  | 
| y	| 117 |
| z	| 12  |

如果语句序列x:=y; y:=z在这个状态中被执行，那么结果就是：

| x	| 117  |
|---|---  | 
| y	| 12 |
| z	| 12   |

这说明了序列$z:=x; x:=y; y:=z$的结果就是，$x$与$y$的值被调换了，副作用则是$z$的旧值丢失了。换句话来说，程序$z:=x; x:=y; y:=z$的意义就可以被视为，从一个输入机器状态$s$到输入机器状态$s'$的映射，其中$s'$在以下方面不同于$s：s' (x)=s(y)$以及$s' (y)=s(x)$(这意味着，$x$与$y$的输入值在输出状态中被调换了)，并且$s' (z)=s' (y)$。

现在考虑存在量词“there exists $x$ such that $A$”。假设我们将这个算子添加到命令式编程语言中。什么会是它的意义呢？它将是一条用一个新值去替换$x$的旧值的指令，其中新值具有性质$A$。我们可以将这个分解为，一个“there exists $x$”的部分，和一个测试$A$。$A$公式/指令是一个测试(test)，当，由它贡献的更新是一个个地接受输入语境的状态，并测试其是否满足一个特定条件。如果它们满足，那么它们就被包含在输出语境中，如果不满足就被丢弃掉。这意味着，一个测试就是一次更新，它接受一个输入语境，并输出一个作为该输入语境子集的语境。在1.2节中，所有命题逻辑的公式都是测试。

这两个部分，“there exists $x$”与测试$A$，是顺序性地组合在一起的：$∃x;A$。着眼于部分“$∃x$”，什么会是它的本质意义呢？一条用某个任意新值去替换x的旧值的指令。这再次的就是一个在输入状态和输出状态间的关系，但这同像$x:=y$这样的限定性指派不同，现在的这个关系并不是一个函数。实际上，量词的这种关系性意义在众所周知的一阶逻辑的塔斯基式真定义中(比较词条[Tarski’s truth definitions](https://plato.stanford.edu/entries/tarski-truth/))展现了出来： 

<br/>

*$∃xϕ$在模型$M$中相对于变项指派$α$为真，当且仅当，存在某个变项指派$β$，$β$最多在对$x$的值的指派上不同于$α$，且该$ϕ$在模型$M$中相对于指派$β$为真。*

<br/>

暗含在塔斯基式定义中的是一个在指派$α$与指派$β$间的关系，该关系成立，当且仅当，对所有不同于$x$的变项y，都有$α(y)=β(y)$。这个关系时常被称作x的随机测试(random reset of x)，并被写作$[x]$。对于任一变项$x$，全指派$[x]$间的二元关系，就是指派之间的等价关系，即，其是一个自反的，对称的，传递的二元关系。在下面我们将看到这种关系是如何在动态版本的谓词逻辑中发挥作用的。将$[x]$采纳为“$∃x$”的意义，注意，它的意义在本质上与一个测试完全不同，因为它在输出语境中创造了新的值。相反，由测试的更新产生的输出语境将总是输入语境的一个子集，因此也不可能含有任何相对于输入语境的新东西。

<br/>

1.4 The notion of context in dynamic semantics

信息状态时常被称作语境，因为该状态是“解释”的前置条件，即，对一个形式或自然语言表达式的语义赋值的前置条件。对词语“语境”的使用也会澄清，我们感兴趣的不是接收者的整个状态，我们感兴趣的只是以下方面：我们所关心的表达式/信息项目的解释方面。因此，在动态传统中，意义常被称作语境变换潜能。

虽然笼统地讲，以下说法也是正确的，即，在动态语义中意义所带来的变化涉及到语境的各个方面，但重要的是要注意到语义学家在讨论语境时可能会意味着各种各样的东西(比较词条[epistemic contextualism](https://plato.stanford.edu/entries/contextualism-epistemology/)与 [indexicals](https://plato.stanford.edu/entries/indexicals/))，而这些不同的视角也催生了为了应对各种不同议题的，各式各样的动态语义学。其中的一些议题是：为代词指称构建一个合适的机制(比较词条[anaphora](https://plato.stanford.edu/entries/anaphora/) 与[reference](https://plato.stanford.edu/entries/reference/))；解释条件句的语义(比较词条[conditionals](https://plato.stanford.edu/entries/conditionals/)与[the logic of conditionals](https://plato.stanford.edu/entries/logic-conditionals/))；给出一个在断言和先设间有所区别的语义处理(比较词条[assertion](https://plato.stanford.edu/entries/assertion/)、[speech acts](https://plato.stanford.edu/entries/speech-acts/)、[implicature](https://plato.stanford.edu/entries/implicature/)与 [pragmatics](https://plato.stanford.edu/entries/pragmatics/))；发展一个关于“先设投射(presupposition projection)”的理论，以解释，话语的解释是如何被存在于说话者与听话者间的共同基础所影响与引导的，并发展一个关于，这个共同基础如何随着话语的进行而发展的理论(比较pragmatics与 implicature)。

语境在两个独立的区分中起着重要作用。第一个区分是在语境与对语境作出修改间的区分。在此，语境是信息状态或者是一个对其的适当抽象(比较词条 [semantic conceptions of information](https://plato.stanford.edu/entries/information-semantic/))。而对语境的修改则是被接受的信息项目(的意义)。信息不能在没有一种正确的被预设的信息状态下得到接受。在静态的经典谓词逻辑中的恰当类比是这样的(比较词条classical logic与first-order model theory)：信息状态是一个指派(环境)或一个指派集，而被接受的信息是一个指派集。第二个区分是在语境与内容间的区分。在此，语境是一种类似于，接收者的存储能力，或各种可能影响到新表达式/信息项目将被如何解释的东西。而内容则是(实际上，真值条件)被存储的信息。因此，例如，此意义上的语境就可以是寄存器或变项的集，或者用DRT/FCS的术语来说就是话语指称(discourse referents)或者文档。而内容就将会是某个指派集；或者可能是世界/指派有序对的集合：指派负责约束这些话语指称的值，再加上作为现实世界候选的世界集。
下面举一个例子来说明这些区分。假设我们将信息状态视作一个以下两者的有序对，即，一个话语指称的有限集，与，一个世界/指派有序对的集，对于后者其中的这些指派来说，它们的域是话语指称的给定有限集。这种情况下的一个信息状态将是第一种意义上的语境，而这个话语指称集将是第二种意义上的语境。一种基本的更新将是内容的更新：在这里我们约束了世界/指派有序对，并让话语指称集保持不变。第二种基本更新将是对指称集的扩展：我们扩展被分配给我们的存储能力。我们将给定的世界/指称有序对修改为，世界/被扩展的指派的有序对，其中我们经过扩展的指派被旧的所约束，但在新的指称上接受所有可能的值。因此，更新过程在我们的例子中是二维的：我们同时拥有对内容的更新，以及对第二种意义上的对语境的更新。

<br/>

2. Dynamic Predicate Logic
   

2.1 Conceptual Underpinnings
发展一个关于自然语言的动态语义框架的最初的也是最重要的动机来自于，人称代词的指称与不定名词短语的指称间的潜在依存关系。关于这样的依存关系，最简单的例子是共指称的话语照应(anaphora)：

-	(1) Mary met a student yesterday. He needed help.

<br/>

对这一串句子的一个观察就是，它们同下面这样的单个句子具有相同的意义：

-	(2) Yesterday, Mary met a student who needed help.

<br/>

如果我们假设不定词就是存在量词，那么对(2)的分析就非常简单。它说的是，存在一个$x$，$x$是学生，以及在昨天遇见了Mary并需要她的帮助。在谓词逻辑中：

-	(3) ∃x(student(x)∧met(m,x)∧need-help(x))

<br/>

然而，相似的分析对于与之等价的那串两个的句子，即对(1)来说则是行不通的。这是因为解释是组合性的(相关讨论见词条[compositionality](https://plato.stanford.edu/entries/compositionality/)) ，而在我们组合性的分析中，我们首先分析的是“Mary met a student yesterday”，其将具有形式，$∃x(student(x)∧met(m,x))$。同样的第二个句子将会对应于 $need-help(x)$。假设合并多个句子的默认模式就是把它们连接在一起，那么现在我们就有了：

-	(4) $∃x(student(x)∧met(m,x))∧need-help(x)$

<br/>

x的最后一次出现是未被约束的，以及因此在经典谓词逻辑中我们就没有得到对(1)与(2)的等价翻译。结果就是，如果我们想要在静态的语义框架中解释(1)与(2)间的等价关系，我们就不能保证对个别句子的组合性翻译。我们将必须去假设(1)必须被整个地翻译出来。

这是反直觉的。我们知道(1)中的个别句子的含义，以及我们想要抓住其中这样一种潜能，即，它们的意义可以同其他的句子的意义结合在一起以形成一个有意义的整体。动态语义允许我们在句子以及超-句子(supra-sentential)层面对意义提供一个完全组合性的分析。而这是动过保证下面这件事来完成的，即，与经典谓词逻辑相反，在对经典谓词逻辑句法的动态解释下，(3)和(4)是等价的。

特别是，以下在动态谓词逻辑中是有效的：
$∃x(ψ∧ϕ) \ iff \ ∃x(ψ)∧ϕ$

<br/>

在这种自然语言的动态语义中，句子的意义不再对应于一个真值条件集，而是对应于对一个语境执行的活动。存在两种活动。像$need-help(x)$或$met(m,x)$这样的谓述就是测试。它们仅仅是检测在当前语境中的所有状态/指派是否指派了一个满足相关谓词的值给$x$；当(且仅当)通过了该测试，测试就将这个未修改的指派传递给输出语境。相反，存在量词则不是一个测试。它有的是去通过随机重置相关变项的值而改变语境的潜能。所以，$∃x(ψ)$接受了一个语境，在该语境的每一指派中随机地改变了x的值，并将这些已被改变的指派传递到输出语境中，如果这些指派同样也满足了由测试ψ贡献的条件的话。

这种语义学的一个主要后果是，在原则上，存在量词的辖域将是没有限制的。它改变某些变项的值直到该变量发生进一步的改变，任意后续测试都可及于这个被设定下来的特定值。这也意味着存在量化的语义可以在不参考任何辖域的情况下给出：$∃x$的意义就是一个活动，它接受了一个语境然后返回了相同语境，被返还的语境中，最多$x$的值被随机替换成了另一个值(细节将会在后面呈现)。

现在，术语，动态语义的两种含义(其都是应用于自然语言的)就浮现了出来。首先也是最重要的是，动态语义是一种总体思路：逻辑语句并不表达真值条件而是表达一种语境上的活动(其中，“语境”可以以多种方式来概念化)。而另一种对术语动态语义的理解则是，它是一系列，在关于某个自然语言现象之争论中，采取的理论立场，最值得注意的现象就是照应(类似于此，采取动态语义这个立场的情况也反映在关于先设的讨论中)。关于照应的情况，这种理论性的理解体现在以下两个假设的结合中：(i) 代词对应于变项；(ii) 不定词是非量化性的，它们仅仅贡献一个动态的变项指派更新。从第二个假设中可以清楚地看到，术语动态语义的理论性用法预设了更一般性的观点，即意义是语境上的活动。

在我们转向去定义动态谓词逻辑之前，我们需要注意的是，动态语义为了说明回指而采取的这条路径，并不是文献中可以找到的唯一路径。我们当然也可以选择放弃代词对应于变项的想法，并对它们指派更复杂的意义，一个类似于有定摹状词的东西。在当代传统中，这样一种想法最早出现在Quine 1960与Geach 1962中，之后(特别)由Evans (1977, 1980), Parsons (1978, Other Internet Resources), Heim (1990), and Elbourne (2001, 2005)完善。相关讨论见Nouwen (forthcoming)。

<br/>

2.2 Specifying Dynamic Predicate Logic

在上一小节中我们初窥到了动态语义框架的基本目标，该目标就是去定义一个逻辑语义学，在这种语义学中语句表达的是活动，以及特别地，其中的存在量化具有重置变项的潜能，并因此改变语境。我们可以通过检视存在量化在一般的谓词逻辑中的定义来得到该如何实现这件事的线索。假设我们有一个，固定论域$D$中的，变项的不变集**VAR**上，的全指派。全指派的集**ASSIGN**因此就是从**VAR**到$D$的所有(全)函数。

<br/>

设，形如$P(x)$的原子公式的意义是，所有指派$α$的集$F$，使得 $α(x)$是一个满足$P$的对象。

<br/>

现在，定义：
$α[x]β:=∀v∈VAR∖\{x\} (α(v)=β(v))$

<br/>

因此$[x]$就是这样的二元关系：指派$β$是，最多重置了指派$α$中变项$x$值后的结果。如已经提到的那样，这是一个在变项指派上的等价关系。现在，$∃xP(x)$的意义$G$就将是：

<br/>

$G:=\{α∈ASSIGN ∣∃β∈Fα[x]β\}$

<br/>

因此，$G$就是可以成功地对$x$进行重置的指派集，并且在$F$中获得一个指派作为这种重置的结果。换一个角度来看，$G$就是以下给出的关系$R$的域：

<br/>

$αRβ:=α[x]β \ and \ β∈F$

<br/>

我们可以说这个$G$是重置活动$R$的前置条件。现在**DPL**的想法就是，不将$∃xP(x)$的意义当成这个前置条件$G$(就像在静态的经典谓词逻辑一样)，而是当成重置活动$R$。在这种方式下我们不会丢失任何信息，因为$G$总是可以通过$R$得到。此外，关系$R$的值域是由指派$β$构成的，$β$最多在$x$的值上不同于前置条件$G$中的指派，并且因此$β$属于$F$(即，$β(x)$是$P$的解释)。被储存在二元关系$R$的值域中的值$x$，将正好是满足$P$的值，即，我们正在寻找的那些值。

更一般地，我们将**DPL**-意义考虑成指派间的二元关系。这样一种关系可以被视为(模拟的)重置活动。这是一个简单化的，但众所周知且有用的，模拟活动之实例：一个活动，将被视为，以下两者间的一个关系，即，该活动被执行前世界的状态，和该活动之后所对应的状态，这样两个状态间的关系。

这里是完整定义 。假设，一个非空论域$D$，一个变项集**VAR**，以及一个signature $Σ$的模型$M=<D,I>$。原子条件(atomic conditions)$π$的形式是$P(x_0,…x_(n-1))$，其中$P∈Σ$的元数为$n$。原子重置(atomic resets)$ε$的形式是$∃v$，其中$v$是变项。$Σ$的谓词逻辑语言被如下地给定 (“∙”为合取，“$~$”为否定)：
$ϕ::=⊥∣⊤∣π∣ε∣ϕ⋅ϕ∣∼(ϕ)$

指派就是，属于$ASSIGN:=D^{VAR}$的元素$α,β,…$。我们将关于这个语言的动态/关系语义，定义为如下：
	
$α[⊥]β:=α≠α$

$α[⊤]β:=α=β$

$α[P(x_0,…x_(n-1))]β:=α=β$ ，以及$⟨α(x_0),…,α(x_(n-1))⟩∈I(P)$，其中$P∈Σ$其元数为$n$

$α[∃v]β:=α[v]β$

$α[ϕ∙ψ]β:=存在一个 γ$ ，使得$α[ϕ]γ且γ[ψ]β$, 或者缩写为$α[ϕ]γ[ψ]β$ 

$α[∼(ϕ)]β:=α=β$，且没有一个$γ$ 使得 $α[ϕ]γ$

<br/>

注意，合取“∙”被解释为了关系合成，而否定“~”则基本上被解释为了，相对于由被否定公式所指谓的关系的域的补。

真则由关系意义来定义；我们基本上把指派间的这个二元关系投射到它们的第一坐标上：

$α⊨ϕ:=∃β α[ϕ]β$

<br/>

我们可以将蕴含$ϕ→ψ$，定义为$∼(ϕ⋅∼ψ)$。将真定义应用于此则可以得到：

$α⊨ϕ→ψ \ iff \ ∀β(α[ϕ]β⇒β⊨ψ)$，即，任意用前件$ϕ$更新$α$后得到的指派$β$，都满足后件$ψ$。

关系性意义同样可以产生出下面这样的，动态后承(dynamic entailment)的漂亮定义：
$ϕ⊨ψ:=∀α,β(α[ϕ]β⇒∃γβ[ψ]γ)$

该定义由Hans Kamp在他的开创性论文Kamp 1981中首次引入。

不那么形式地说，它告诉我们，任何已合并了由$ϕ$贡献的更新的赋值$β$，都保证支持/满足$ψ$。

注意，$∼ϕ$等价于$(ϕ→⊥)$，以及$(ϕ→ψ)$为真，当且仅当，$ϕ⊨ψ$。
同样重要的是，我们可以将$∀x(ϕ)$定义为$(∃x→ϕ)$。

对于$∃v$来说，一个可能的替换概念是$[v:=?]$(随机重置)。这强调了同编程语言中的随机指派的联系。

谓词符号的解释是条件。它们是对角线$\{⟨α,α⟩∣α∈ASSIGN \}$(这是$⊤$的意义)的子集。该对角线的子集就是测试：它们不修改任何东西，只将那些可以通过测试的(满足该条件的)传递下去并抛弃掉那些不能通过的。将一个指派集$F$传给一个条件$\{⟨α,α⟩∣α∈F\}$的映射**diag**，是一个在经典静态与动态世界间的链接。例如，$diag(F)$与$diag(G)$的关系性合成是$diag(F∩G)$。

经典一阶逻辑(FOL)可以被如下地解释为**DPL**。我们假定FOL语言有如下的联结词与量词：$⊥,⊤,∧,→,∃x$。那么我们就可以这样来翻译 ：

- 若$ϕ$是原子公式，$(ϕ)*∶= ϕ*$

- $(ϕ→ψ)*:=(ϕ*→ψ*)$

- $(ϕ∧ψ)*:=ϕ*⋅ψ*$

- $(∃x(ϕ))*:=¬¬(∃x⋅ϕ*)$

<br/>

我们得到，$[ϕ*]$是$ϕ$的经典解释的对角线。我们的翻译是组合性的。它显示了FOL可以被认为是**DPL**的一个片段。

反过来说，也可以将任何DPL-公式ϕ翻译为谓词逻辑公式$ϕ°$，使得$[ϕ]$的域就是$ϕ°$的经典解释。定义此翻译的方法之一就是通过霍尔规则(Floyd-Hoare rules)，借助一个叫前置条件演算(precondition calculus)的东西来进行(Eijck and de Vries 1992)。以下是该方法的一个变种。以标准谓词逻辑语言为例，其添加了菱形模态 $⟨ψ⟩ϕ$，其中的$ψ$包括了**DPL**公式，以及 $α⊨⟨ψ⟩ϕ$，当且仅当，存在带有$α[ψ]β$的赋值$β$，且$β⊨ϕ$。那么下面的等价关系就显示了这样的扩展并没有增加任何的表达能力。

- $⟨⊥⟩ϕ↔⊥$
  
-	$⟨⊤⟩ϕ↔ϕ$
-	$⟨P(x_0,…x_n)⟩ϕ↔(P(x_0,…x_n)∧ϕ)$
-	$⟨∃v⟩ϕ↔∃vϕ$
-	$⟨ψ_1⋅ψ_2⟩ϕ↔⟨ψ_1⟩⟨ψ_2⟩ϕ$
-	$⟨∼(ψ)⟩ϕ↔(¬(⟨ψ⟩⊤)∧ϕ)$

<br/>

所以，在一个弱意义上“没有任何新东西发生在DPL中”。我们并不能定义一个我们在FOL中就同样也不能定义的集合。该模式的等价关系固定了一个翻译， ( )°，为了实现给定的后置条件，它提供了最弱前置条件(the weakest precondition)；对这样一个翻译的说明见下一节。

<br/>

2.3 Example: donkey sentences

关于动态谓词逻辑之优势的一个例子是，其允许对驴子句(donkey sentence) (Geach 1962)提供一个直接组合性的分析 。
-	(5) If a farmer owns a donkey, he beats it.

<br/>

在代词与不定名词短语间，即“he”与“a farmer”；以及“it”与“a donkey”之间存在着一个明显的依存关系。简而言之，关于(5)的经典分析带来的问题是，这样一个分析给了我们两个选择，而这两个选择加在一起也没能涵盖(5)的意义。如果我们将不定名词短语当作，其指称这一位特定的farmer以及一只特定的donkey，并且上面两个代词只是简单地挑出了与不定名词短语的指称相同的实体，那么我们就会得到一个可能的对(5)的解读，但这个解读并不是十分突出。而最突出的解读应是，其描述了一个在owning关系与beating关系间的共变：任何对own关系成立的 farmer-donkey对，都同样对beat 关系成立。显然，我们需要将不定名词短语解释为量词。然而如果我们真这样做的话，它们就没办法去约束在条件句后件中的变项，而这是因为，组合性分析将会把由代词贡献的变项放在，该条件句前件中的存在量词的经典辖域之外。这就是(6)的情况，它并没有得到关于(5)的正确的真值条件。
-	(6) $(∃x(farmer(x)∧∃y(donkey(y)∧own(x,y))))→beat(x,y)$

<br/>

(6)的动态版本将是得出了正确真值条件的(7)：对于x与y的任意随机重置，若使得x是一位farmer，y是一只donkey并且x owned y，那么该随机重置同样也使得x beats y。
-	$(7) ∃x⋅farmer(x)⋅∃y⋅donkey(y)⋅own(x,y)→beat(x,y)$

<br/>

有趣的是，将(7)翻译进谓词逻辑的翻译$( )°$并不是(6)而是(8)。所以，问题不是谓词逻辑不能表达驴子条件句的真值条件，而是(8)看起来并不像是由组
合性解释过程输出的结果(但见Barker and Shan 2008)。
-	$(8) ¬∃x(farmer(x)∧∃y(donkey(y)∧own(x,y)∧¬beat(x,y)))$

以下是(8)如何从(6)导出的过程：

$(⟨(∃x⋅Fx⋅∃y⋅Dy⋅Hxy)→Bxy⟩⊤)°$

$=(⟨∼((∃x⋅Fx⋅∃y⋅Dy⋅Hxy)⋅∼Bxy)⟩⊤)°$

$=¬(⟨(∃x⋅Fx⋅∃y⋅Dy⋅Hxy)⋅∼Bxy⟩⊤)°$

$=⋯$

$=¬∃x(Fx∧∃y(Dy∧Hxy∧¬Bxy)))$.

<br/>

2.4	Dynamic generalized quantification

将动态谓词逻辑成功地应用在了对自然语言中量化与照应的解释之上——这项动态谓词逻辑的成功应用，取决于以下事实：在**DPL**中存在量化是动态的而全称量化则不是。那么如果全称量化也变成动态的话将会发生些什么呢？首先需要注意的是，定义一个平行于随机重置活动$∃x$的，全称量化活动$∀x$，是没有任何意义的。这是因为全称量化只有在给定论域(限定部分(restrictor))下，并相对于某些给定性质(辖域)之下才是有意义的。第二，如果我们对$∀x(ϕ)(ψ)$也给定一个动态解释的话，那么这将预示着，全称量词也可以跨句建立同单称代词的照应关系，就像存在量词那样。而对于像(9)这样的情况来说则显然是不可取的。

-	(9) Every boy wrote an essay. #He wrote a research proposal too.

<br/>

然而，只要我们看一下复数形式的照应(plural anaphora)，那么我们就能够发现全称量化(事实上，也包括其他非-不定式广义量词)的静态性质并不是那么理所当然。例如，(10)允许了这样一个解读，其中“they”照应性地联系于“every boy”。
-	(10) Every boy wrote an essay. They wrote a research proposal too.

<br/>

在(10)也需要接受动态处理，这个假设下(见前文关于其他替代方案的评论，以及Nouwen forthcoming)，结论就只能是这个全称量词并不能被给定一个静态解释。接下来的问题就是，那么哪种解释是合适的，以及这样的解释如何能够区分(9)与(10)呢，因为前者的照应并不合法。一个选项是去区分以下两者，即，被指派给，受其所在辖域内之量词约束的，变项的值；与，被指派给，该量词辖域之外的，变项的值(这种策略的例子见Kamp and Reyle 1993，以及Nouwen 2007关于它的讨论)。为了能够说明 (10)，人们会让，被(10)中第一个句子的量词所约束的变项，在“个体男孩”的范围中取值，而在这个量词的辖域之外(即，在第二个句子中)，则获得“所有男孩”这个复数指派。然而，就如由van den Berg (1996)所首次表明的那样，这样一个方案只解决了一半问题。在话语中，代词不仅可及于联系于量词的复数，而且对这样的量词所参与到的关系而言，其也是可及的。例如，在(11)的第二个句子中，代词“it”同主语中在“boys”上的量化相吻合，因此第二句的意义是，每个男孩都提交了他所写的论文(参，van den Berg 1996; Krifka 1996; Nouwen 2003; Brasoveanu 2007, 2008)。
-	(11) Every boy wrote an essay. Each of them submitted it to a journal.

<br/>

在对广义量化(generalized quantification)与复数照应的动态处理中，主导思想将是，不要通过给变项指派复数形式来表达复数值，而是要接受一个这样的语境概念，其将允许指派函数的复数形式(例如，指派函数的复数个集)。 假设如下地将(11)的第一个句子翻译进带有动态量词的动态谓词逻辑中：$∀x(boy(x))(∃y⋅essay(y)⋅wrote(x,y))$。对这种式子的解释就要求下面这样一些指派函数的集族，这些指派函数将使得 $x$的值是一个男孩，且$y$的值是这个男孩写的一篇文章。该全称量词要求这样一个集族去包括，对谓词“boy”来说所有可能的值。在接下来的话语中，现在我们就可及于：(i) 包含了所有$x$的值的这个集合，即，所有男孩的集；(ii) 所有y值的集，即，这些男孩所写之文章的集；(iii) 由个别的boy-essay组成的对：这使得，跟随在(11)的第一个句子之后的语境指派的集中的，原子指派$f$，满足$f(y)$是一篇被男孩$f(x)$所写的文章。为了说明(11)中照应的情况，现在我们需要的就是假设，这里的这个全称量化涉及到的是在指派函数上的全称量化，而不仅仅是在值上的量化。关于这个想法的各式各样的实现，见van den Berg (1996), Nouwen (2007, forthcoming), Brasoveanu (2007, 2008, 2013)。

结果就是，给定一个对，语境的恰当地结构化的概念，就可以一般性地对量词给出动态解释。一个重要的后果是，将这种分析扩展到非名词性量词上(Brasoveanu 2007)。像(11)这样的情况可以被描述为量化从属关系(quantificational subordination)的情况，以及这个结构化语境的方法可以被视为旨在提供一个窗口，以能够了解从属关系背后的机制。模态从属关系的情况(Roberts 1987, 1989)，就像著名的(12)一样，可以得到一个平行的处理。

-	(12)A wolf might come in. It may eat you.

<br/>

模态词“might”引入了一个在可能世界上的量词，该量词的辖域将包括不定名词短语“a wolf”，而同样地，上文(11)中“every boy”的辖域也将包括“an essay”。指派函数的集，作为由(12)中第一个句子所贡献的更新的输出的结果，其将存储由“might”贡献的可能世界的集，而这些可能世界是相对于现实世界而认识上可能的可能世界；而且也将储存在这些认知可及的世界中会来的狼的集合。(12)中的第二个句子可以进一步阐明狼和世界间的依存关系，而这则要求至少存在一些认识上的可能性，使得相应的狼不仅会来，而且还会把你吃掉！(┗|｀O′|┛ 嗷~~)

<br/>

2.5 	Dynamics beyond anaphora

虽然对照应和先设(见下文)来说，它们是人们通常会认为的，需要对其提供一个动态语义分析的核心语言学现象，但原则上，语境的任何方面都可以是值得一个动态分析解释的目标。Barker 2002对含混(vague)语句的处理就说明了这一点。Barker假设，对于像“tall”这样的含混形容词来说，语境将包含一些清晰的规则。这样，类似于(19)的句子就可以以两种不同的方式来使用。(19) John is tall. 如果信息状态包含了关于什么将被算作“tall”的(足够)清晰的信息，那么对(19)的使用就将是去提供关于John之身高的信息。然而，如果听者不知道关于像表达式“tall”的恰当的精确化(precisification)(比如说他或她是个外星人或者外国人)，但她或他确实又拥有关于John的身高的信息，那么(19)就可以被用来提供关于这个人现在所不知道的这个标准的信息。

<br/>

3.	Presupposition

3.1	Presupposition and dynamic semantics of connectives

在先设中，语境有着重要的作用。像(13)一样的句子先设了“John is late”。但是把这句话放进提供这个信息的语境中时，就像在(14)中那样，这个先设就消失掉了。在(14)中“John is late”是被断言的，而不是被先设的。
-	(13) Mary knows that John is late.
-	(14) John is late and Mary knows that he is late.

<br/>

Stalnaker 1973将先设考虑为基于假定的共同知识。提出一个句子(13)理所当然地就将John迟到了这件事当作了共同知识。在这个意义上，(13)需要表达的语境，去使得这个共同知识是到位的。相反，(14)缺乏这种需求，仅仅因为(14)的第一个合取枝断言了被第二个合取枝当作是理所当然的东西。Stalnaker做出的关键假设是，在下面这种意义上，解释是递增的：对于形如$[S1 \ and \ S 2]$这样的句子来说，S2的解释出现在语境中的时候，其就已经被S1所更新了：

-	$(15)C[S1 and S2]=(C[S1])(S2)$

<br/>

Stalnaker对(15)中模式的解释是语用的：当我们在话语中遇到一连串子句时，我们将根据已经被以前的一些子句所信息化的一个语境来解释后面的这些子句。递增解释这个想法简单而有力，同时它对有着合取式解释的复杂话语也非常有意义(例如，有着“and”的并列句，以及简单的陈述句序列)。因为在一个合取中的合取枝有着断言语力(assertoric force)，它们可以被用来更新语境以创造一个新的局部语境。然而问题是这些先设不仅仅只是在合取环境中消失掉了。就像，如同(14)的(16)一样，(16)同样缺乏对，把John迟到了，作为共同知识的需求。但是，此处的第一个析取枝并没有断言语力(对此的讨论见Schlenker 2009)。并不清楚哪种语用规则可以说明(16)中先设的缺失。
-	(16)Either John is not late or Mary does not know that he is late.

<br/>

(16)这样的句子唤起了人们对于像(15)那样的递增解释的怀疑。最重要的是，(15)在关于解释如何进行的假设上过于激进。断言一个带有命题内容p的子句，并不自动地使得p将成为一个共同知识。p是否成为共同基础取决于其他对话者是否愿意接受该命题(例如，不去反驳这个断言)。换言之，(15)看起来并不适合于抓住信息流的(动态的)语用。

一个可能的出路是不把(15)看成语用规则，而是语义规则，这样的语义规则在可以解释的动态概念中得到表述。这是继Karttunen 1973之后最重要的提议，由Heim 1983b提出。Karttunen区分了全局语境(global contexts)，其是相对于当前要被赋值的句子的语境，以及局部语境(local contexts)，其是相对于当前要被解释的子句(或是，潜在的某个子-子句实体)的语境。现在的想法就是，像(15)这样的规则可以表达“and”的语义。在(15)中，C是全局语境。 合取之语义的关键部分是：对于S2来说的局部语境是，一个更新，该更新带有S1的全局语境。因此，在(14)中不存在预设就仅仅因为 “and”的动态语义。为了对(16)中先设的缺失给出一个说明，我们只需要给出一个析取的语义，其中第二个析取枝的局部语境已经被，带有否定的第一个析取枝所更新了；关于这样一种，抓住了(双重)否定与照应间的相互作用的说明，见Krahmer and Muskens 1996。

为了更加具体一些，让我们假定语境是可能世界集，以及，对带有一个简单子句S的C的更新C[S]就是C∩p，其中p是S的命题内容：用一个子句更新C，输出的是C世界，在这些世界中该子句为真。(18)中的展示了，关于英语中主要命题算子的动态解释的，一个Heim式片段。
-	(17) $C[not S1]=C∖C[S1]$

     $C[S1 and S2]=(C[S1])[S2]$ 

     $C[If S1, then S2]=(C[not S1])∪(C[S1])[S2]$ 

     $C[S1 or S2]=C[S1]∪(C[not S1])[S2]$

有些人会质疑这样一个动态解释，即(18)，的价值，因为该框架未能说明为什么这里似乎没有一个自然语言表达式来编码(17)的最小变体，其中第二个合取枝$S2$的局部语境是$C[S1]$而不是$C[not S1]$；或者，其中$S1$的局部语境基于的是用$S2$进行的更新；或者，像(18)那样的东西中就根本不存在任何局部语境(例如，见Soames 1989)
-	(18) $C[S1\  or \ S2]=C[S1]∪C[S2]$

考虑到这样一些批评，最近有些关于先设投射的静态进路已经开始复兴，例如Schlenker (2008, 2009)的语用进路；Chemla (2008, Other Internet Resources)；以及George (2008) 与Fox (2008)的(三值)语义进路。然而，如Rothschild指出的那样，存在一条道路可以使得一个语义学沿着(17)说明的路线行进下去。要做到这一点，人们就必须表明，联结词之可允许的动态解释分享了某些属性。如Rothschild (2011)显示的那样，当我们假定语境变换潜能坚持了某些定义性(definedness)的原则，一个说明以及关于先设的经验上恰当的动态处理就是可能的。让我们假定$C[S]$(对于一个简单子句$S$)是仅得到定义的，当且仅当， $S$的任何先设在$C$的所有世界中都为真。(17)中的规则决定了之于复杂句的定义性条件。例如，根据(17)，当$S$在$C$中是未经定义之时，$[not S]$在$C$中是仅未经定义的。Rothschild的洞见是，我们可以通过限制结果的定义性条件来对动态解释做出限制。

<br/>

3.2 Presuppositions and Dynamic Epistemic Logic

认知逻辑(epistemic logic)，即关于知识的逻辑，是模态逻辑的一个分支，其研究的是模态“i knows that”(比较词条：[epistemic logic](https://plato.stanford.edu/entries/logic-epistemic/)与[logic of belief revision](https://plato.stanford.edu/entries/logic-belief-revision/))。认知逻辑中的动态转向大概发生在2000年左右，这引入了对状态之变化的关注，而现在，状态则被认为是一个认知主体(agents)集的知识表征。

如果我们确定一个基本命题集$P$，以及一个认知主体集$I$，那么对于$P$与$I$来说，一个知识状态将包括一个可能世界集$W$，以及$W$中的每个$w$指派一个$P$的子集的一个赋值函数$V$(如果$w∈W$，那么$V(w)$列出了在$w$中为真的基本命题)，并且对于每个认知主体 $i∈I$，存在一个关系$R_i$，该关系说明了$i$的认知相似性(epistemic similarities)(如果$wR_i w'$，那么这意味着认知主体$i$无法分辨$w$与$w'$)。认知模型，$M=(W,V,\{R_i∣i∈I\})$被考虑为多模态的克里普克模型(Kripke models)。认知点模型(pointed models)为，带有一个指定世界$w_0$的认知模型，$w_0$表示现实世界。

如果公开宣告了$ϕ$为真，那么对于一个给定的认知状态$(M,w_0)=((W,V,{R_i∣i∈I}),w_0)$来说会发生些什么呢？直观地，$M$的可能世界集将被限制到对$ϕ$成立的那些可能世界$w$上，其中$w∈W$，并且赋值函数$V$与认知关系$R_i$也将被相应地限制。称这个新模型为$M∣ϕ$。当$ϕ$在$w_0$为真，$ϕ$之公开宣告的意义就可以被认为是，一个从$(M,w_0)$到$(M∣ϕ,w_0)$的映射。而当$ϕ$在$w_0$为假，那么就没有什么可能的更新。

Veltman的更新逻辑可以容纳进公开宣告逻辑(public announcement logic)中(比较词条 [common knowledge](https://plato.stanford.edu/entries/common-knowledge/))，人们可以通过允许形如$♢ϕ$的公开宣告来做到这一点，其中的这个模态被读作，共同知识下的可达性(reachability under common knowledge)，如果之于一个认知主体集(比较词条 epistemic logic)的一个**S5**知识状态被公开宣告$♢ϕ$更新了，那么在这种情况下，$ϕ$就在模型的某处为真，该更新没有改变任何东西(对于$M∣♢ϕ$来说，其等同于$M$)，否则就会产生不一致(因为该公开宣告将被断言为真)。这符合更新逻辑的定义。

对于认知逻辑来说，带有交流更新的逻辑工具箱常被称作动态认知逻辑(dynamic epistemic logic)或者**DEL**。**DEL**始于对公开宣告的，认识论上与信念上的，影响的分析(Plaza 1989; Gerbrandy 1999)。公开宣告是十分有趣的，这是因为它创造了共同知识。有着各种各样的宣告——私人宣告、群体宣告、秘密分享、谎言等等——以上这些都有着定义明确的认知影响。在Baltag et al. 1999与Baltag and Moss 2004中，其提出了一个，关于一个广泛的更新活动类别的，一般性框架。在Benthem et al. 2006中则提供了一个进一步概括，其是关于交流与变化的完整逻辑，其中有着可以改变关于世界之事实的丰富活动。在Ditmarsch et al. 2006中则给出了对动态认知逻辑的一个教科书式处理。

在认知逻辑的环境下，人们可以如下地通过先设来表达一个交流情境。首先，我们需要表达，在一个多认知主体信念(或认知)状态下，一个说话者假设了他的听者知道或相信着哪些东西，然后，我们需要建模交流活动对信念状态的影响。在动态认知逻辑中把握先设表达的一个简单方式是，将一个先设$P$模拟为一个公开宣告“it is common knowledge that $P$”。在$P$确实是共同知识的情况下，这个信息更新不会改变任何东西。然而，在$P$并不是共同知识的情况下，该表达就为假，并且对假表达的公开宣告输出了不一致的知识状态。

<br/>

3.3	Beyond presupposition

动态语义学特别适合于描述语言学材料是如何影响到信息状态的不同方面的。尤其是动态语义学允许人们建模这样一个区别，即，议题上的内容(at-issue content)，例如——被一个陈述句表达所断言的内容；与，非议题上的内容(non-at issue content)，例如，起着某种次要作用的内容，这两个内容间的区别。比如说，(19)的议题上的内容是，昨天John的邻居被逮捕了：这是说话者意图去断言的内容。同位语“who I have never met”，则是非议题上的内容。可以看到这种情况的一个方法是，当她或他意图挑战那个邻居被逮捕了这个事实时，而不是仅仅表达她或他不相信说话者从来没见过那个邻居的主张时，其才会回应“That’s not true!”。
-	(19)John’s neighbour, who I have never met, was arrested yesterday.

<br/>

对于分析随着句子的解释其将会发生些什么来说，动态语义学也是个十分适宜的框架，因为它自然地就允许对单独的信息流进行建模。例如AnderBois et al. 2015就为像(19)那样的，其母句更新了一个局部的可能世界集的这样一个句子，提供了一个说明。该更新集可以被视为用来更新共同基础的潜在候选。反之，那个同位语则直接更新了该共同基础。后者这个更新，与其说是提议的共同基础更新，不如说是强加的更新(一种替代版本的动态逻辑见Nouwen 2007)。AnderBois et al. 2015的想法部分地受到了，在据素(evidentials)领域成功应用的相似想法的启发，后者见Murray 2014。

<br/>

4.	Encoding Dynamics in Typed Logic

在自然语言语义学中使用逻辑系统时，组合性一直是个非常重要的考量(见词条compositionality)。通过对高阶逻辑的使用(见词条[second-order and higher-order logics](https://plato.stanford.edu/entries/logic-higher-order/)与[Church’s type theory](https://plato.stanford.edu/entries/type-theory-church/))，可以对，例如自然语言的量化系统，提供一个彻底组合性的说明，正如在经典的蒙太古语法(Montague grammar)中证明到的那样(Montague 1974a,b, 1973; 比较词条[logical form](https://plato.stanford.edu/entries/logical-form/))。我们将要回顾如何将动态方法扩展到高阶系统上。在动态语义学与类型论(type theory)间的链接更像是一个联系，而不是一个稳定的婚姻：并没有一个关于这种联系的内在需求。在此处理这种联系只是为了说明蒙太古语法之于动态语义的历史影响。

大多数关于蒙太古语法的动态版本的提议都实际上发展了一种高阶版本的动态谓词逻辑。这对Groenendijk and Stokhof 1990; Chierchia 1992, 1995; Muskens 1994, 1995, 1996; Eijck 1997; Eijck and Kamp 1997; Kohlhase et al. 1996; Kuschert 2000，它们来说都成立。所有这些系统都从DPL中继承了一个特征(或者说一个bug)：它们制造了十分具有破坏性的再指派。DRT则不会遭受这个问题的困扰：Kamp 1981以及Kamp and Reyle 1993的话语表达构造算法可以用带有有限域的函数来表达，并对每个需要处理的新名词短语，仔细地去讨论“采取一个新的话语指称”来扩展验证函数的域。

在外延性的蒙太古语法中“a man”被翻译作：

$λP∃x(man x∧Px)$

在此，$P$的类型$e→t$，是**VP**空位的变项：这假设了**VPs**指谓实体集。

在Groenendijk and Stokhof 1990的动态蒙太古语法(Dynamic Montague Grammar (DMG))中，对不定**NP**的翻译引入了一个照应下标。“a man”的这个翻译就是：
$λPλaλa'⋅∃x(man x∧Pu_i (u_i∣x)aa')$

<br/>

不像经典外延性蒙太古语法一样只有基本类型$e$与$t，DMG$的基本类型是$e，t$以及$m$($m$即标记)。状态为标记挑出实体，所以状态可以被视为类型为$m→e$的对象。将$m→e$缩写为$s$(即状态)，我们就可以称类型$s→s→t$的对象为状态转换。在**DMG**对“a man”的翻译中的变项$P$有着类型$m→s→s→t$，所以**VP**的意义就已经从类型$e→t$提升到了该类型上了。注意，这里的“$→$”关联的是右侧，所以$m→s→s→t$是$m→(s→(s→t))$的缩写。的确，**DMG**可以被视为，用标记来对实体进行系统性替换，以及用状态转换来替换真值的结果。表示“is happy”的VP是一个将标记映射到状态转换的函数。对标记$u_i$来说的状态转换将会核查，输入的状态是否把$u_i$映射到了一个正确的实体上，以及输出语境是否和输入语境相等。变量$a$与$a'$涵盖状态，并且表达式$(u_i∣x)a$指谓，将$a$中的$u_i$的值重置为$x$后的结果，所以$u_i$的旧值就被破坏掉了(破坏性的指派)。在指称标记$u_i$上的照应下标$i$是由翻译引入的。实际上，翻译是从带下标的不定名词短语“a mani”开始的。蒙太古式组合性与动态语义学间的联系，以及蒙太古式成分与动态成分的联系，在由Muskens 1991, 1995, 1996提出的变化的类型逻辑(typed Logic of Change)中更加透明与精简。因此，在当前对组合性动态语义学的研究中，Muskens的组合性DRT或许是实际上的标准与出发点。一个替代方案是在递增类型逻辑(Incremental Typed Logic(ITL))中给出的，其是一个基于变项自由加标的“堆栈语义(stack semantics)”，而对类型逻辑进行的一个扩展，以及因此避免了破坏性指派的问题。之于DPL的堆栈语义的基本思想由Vermeulen 1993发展，并替换了一般**DPL**中的破坏性指派，这种破坏性指派在进行重置时丢弃了旧的值。堆栈值指派为每个变项指派一个堆栈的值，而堆栈的顶端就是当前值。存在量化将给堆栈一个新值，但也存在值被弹出堆栈，以重新使用旧值的可能性。Eijck 2000的ITL实际上是使用单一堆栈的堆栈语义的类型化版本。

假设一个实体域，语境是实体的有限列表。如果$c$是长度为$n$的语境，那么我们称其元素为$c[0],…,c[n-1]$，其长度为$|c|$。我们称长度i的语境的类型为$[e]^i$，如果$c$是$[e]^i$中的语境，则类型$\{0,…,i-1\}$的对象就可以作为指标引入$c$。如果$c∈[e]^i$且$j∈\{0,…,i-1\}$，那么$c[j]$就是，出现在该语境中位置$j$的类型$e$之对象。在语境上的关键操作是使用元素进行扩展。如果$c::[e]^i$且$x::e$($c$是一个长度为$i$的语境且$x$是一个实体)，那么$c^x$就是有着元素$c[0],…,c[i-1],x$的长度为$i+1$的语境。因此“$^$”就是一个类型为 $[e]^i→e→[e]^i+1$的算子。同样要注意到的是，像$[e]^i$这样的类型是多态类型，其带有的$i$作为的是一个类型变项。见Milner 1978。

在**ITL**中不存在任何破坏性指派，以及不定名词短语在句法中不携带指标。**ITL**对“a man”的翻译是如下地从语境中获得指标的：

$λPλcλc'⋅∃x(man x^P|c|(c^x)c')$

<br/>

此处的$P$是一个类型为$\{0,…,i\}→[e]^(i+1)→[e]^j→t$的变项，同时$c$是一个类型为$[e]^i$的变项，这表示的是长度为i的输入语境。而$c'$是一个类型为$[e]^j$的变项，这表示的是输出语境。注意，之于$P$的类型$\{0,…,i\}→[e]^{(i+1)}→[e]^j→t$，表明的是，$P$在范围$\{0,…,i\}$内接受了获得一个指标，接下来一个语境将符合这个范围(一个长度为$i+1$的语境)，再接下来是一个长度还未知的语境，最后给出一个真值。$P$如下地从一元谓词的类型提升到了语境变换算子层面的类型：一个被提升的谓词用的是，涵盖了输入语境大小的一个变项，以去形成了一个指谓语境变换算子的表达式，而不是去用涵盖了对象的变项来形成一个类型为$e$的表达式。

“a man”的ITL翻译拥有类型：

$(\{0,…,i\}→[e]^{(i+1)}→[e]^j→t)→[e]^i→[e]^j→t$

在$P|c|(c^x)c'$中，变项$P$标记的是为**VP**解释准备的空位；$|c|$给出了对$P$的输入语境的长度；其获取了值$i$，这是当语境被扩展时下一个可用空位的位置。该空位被，指谓一个男人的对象$x$所填充。注意$c^x[|c|]=c^x[i]=x$，所以上标$i$的作用是从语境中挑出那个男人。

为了看到一个动态高阶系统在**ITL**中是可表达的，只要表明如何去定义恰当的动态算子就足够了。假设$ϕ$与$ψ$具有语境转换的类型，即，类型$[e]→[e]→t$(将$[e]$用作任意语境)，以及$c,c',c''$具有类型$[e]$。那么我们可以如下地定义动态存在量词、动态否定以及动态合取：

$ℇ:=λcc'⋅∃x(c^x=c')$

$∼ϕ:=λcc'⋅(c=c'^¬∃c''ϕcc'')$

$ϕ;ψ:=λcc'⋅∃c''(ϕcc''∧ψcc')$

动态蕴含$⇒$，用通常的方式定义为$∼(ϕ;∼ψ)$。

<br/>

**ITL**与Muskens式组合性**DRT**并不是不相容的；例子见Bittner 2014。我们通过对大家提醒如下这件事来结束本节的讨论：整合了蒙太古式组合性与动态语义学的系统的范围还远远没有被完全画出来。最近一系列的，由基于延续性(continuation)的与动态语义的整合，所作出的贡献，正在进一步探索，整合及一般化蒙太古式组合性与动态语义学两者的新可能。见Groote 2006, Bumford and Barker 2013, Charlow 2014, Bumford 2015, Martin 2016。

<br/>

5.	Conclusion

希望以上内容已经提供给了读作你一个这样的感觉——对于意义与信息处理来说，动态语义学是一个灵活且成果颇丰的进路。动态语义提出了一系列灵活的工具，并有着一系列“杀手级应用”，例如对驴子句的组合性处理、对照应连接的说明、对先设投射的说明、对认知更新的说明，以及在不同更新间进行的精细区分(如，非议题上的更新)。动态语义是形式语义学中一个非常活跃的子领域，并且寻求动态方法的跨语言现象们的范围，正以越来越快地速度在绝赞扩大中。
