

# 分享最近阅读的书籍清单(五)

1.  [How to Take Smart Notes](#org783f718)
2.  [The Craft of Text Editing](#org31ddf81)
3.  [Beautiful Racket](#orgc88b1a8)
4.  [Technical Blogging, Second Edition](#org775c40b)
5.  [Crafting Interpreters](#org036072c)
6.  [Master Emacs](#org4053ca0)
7.  [Benjamin Franklin: An American Life](#org67a85d0)
8.  [Practical Common Lisp](#orgdbd5bef)
9.  [Paradigms of Artificial Intelligence Programming: Case Studies in Common Lisp](#org0af41ea)
10. [相关阅读](#org1f8e013)

这些都是在人生中的好书藉，我想把这些优秀的东西分享出来，并赋上自己的一些主观想法，能让更多人知道并从中受益。这里只是做一个引荐，精彩需要你自己亲自拜读从中感受。


<a id="org783f718"></a>

## How to Take Smart Notes<sup><a id="fnr.1" class="footref" href="#fn.1" role="doc-backlink">1</a></sup>

*One Simple Technique to Boost Writing, Learning and Thinking – for Students, Academics and Nonfiction Book Writers.*

<div class="org-center">
<p>
卡片笔记写作法<sup><a id="fnr.2" class="footref" href="#fn.2" role="doc-backlink">2</a></sup>
</p>
</div>

> 没有人能在不作记录下思考。
> 
> &#x2013;Luhmann

**我的结论**

我想我们的任何努力都不会白费，只要你肯将他们记录下来并永久保留。大脑是用来思考的，而生活中我们所做的点滴努力让笔记替我们记住, 让人有限的精力尽量去做思考而不是去记忆。但是如何高效的做笔记呢，不至于写过一遍就再也找不到了，或者并不能成为大脑的延展为我们分忧解难，而且让我们的努力白白浪费？而这就是读这本书的好处了。借助此书中的方法[卢曼](https://en.wikipedia.org/wiki/Niklas_Luhmann)产出了58本书和数百篇论文，[特罗洛普](https://en.wikipedia.org/wiki/Anthony_Trollope)产出了47本小说和16本其他书籍，你要是知道现在的大学毕业生产出一篇论文都要饺尽脑汁你就知道本书方法的强大之处了。而他的本质就是合理组织你所学到的所有知识，当在你要做任何事情时，从过去的所学中提取出你所需要的知识，进行合理的组合来完成你想要做的事，也就是你积累的越多你所能做的就越多，并且在你没有灵感时，能通过不同的组合给予你新的灵感。而要完成这些的关键之处是，要组织起我们所学到的任何知识并为我们所用，就像我们大脑的延伸，想要时随时能联系起来，存在时能充分给予我们源源不断的灵感。 `#todo` 笔记方法。 而要做到这些简单的不能再简单了，你只要几个纸片和一支笔，或者信息时代你只需一个记笔记软件就能做到，可以看看我分享的[这些](share_note_app.zh.md)。当知道方法之后你剩下要做的就是去积累知识吧，没有天生的天才，只要肯努力人人都是天才，毕竟天才也才只有一个脑子。


<a id="org31ddf81"></a>

## The Craft of Text Editing<sup><a id="fnr.3" class="footref" href="#fn.3" role="doc-backlink">3</a></sup>

<div class="org-center">
<p>
打造文本编辑器
</p>
</div>

> 好的编程不是从泛泛而谈中学来的，而是通过应用常识和良好的编程实践，了解如何使重要的程序变得干净、易于阅读、易于维护和修改、人为设计、高效和可靠。仔细研究和模仿好的程序可以使写作更好。
> 
> &#x2013;Kernighan and Plauger

**我的结论**

如何构建一个大型系统，特别是编辑器，例如像emacs这样类型的编辑器？如果你有意愿打造自己的编辑器，这本书是个不错的选择。计算机科学本质上是工程行业，就像造房子，先设计蓝图，打地基，然后一砖一瓦把房子累起来。而特定的软件，又有他特定的知识点，就像你造住人的房子跟工业厂房就需要完全不同的知识，适宜居住的房子结构如何排布，保证人的舒适，以及阳光等，而厂房更多的是安全性，适合作业，以及大量的人流水电排污等。软件行业也类似，虽然都是C++但是游戏行业软件和工业软件就需要不同的知识点，不同的操作界面，不同的数据类型，不同的硬件需求，以及不同的算法结构和命令结构等。所以单单学会一个语言要做到专业化也是有难度，这就是这书存在的理由。对于一个编辑器，你要考虑人们使用他的整个流程是怎样的（进入、编辑、保存、退出&#x2026;），使用怎样的文件格式进行保存，用户的操作界面，以及内存管理，算法，命令行设置等。如果你有意于创造自己的编辑器，就要对这些有所了解，首先保证了方向的正确，其次可能能与市面上的编辑器竞争，然后根据特定人群做特殊化定制与市面上的编辑器需别开来，才有可能存活下来，要不然就是自己做玩具自己玩了。例如你开发了个新语言，想要一个配套设施编辑器，或者市面上的编辑器不符合公司需求，公司里面有很多基础设施现有编辑器满足不了，做深度定制成本又非常高，这时开发独属于公司的编辑器就非常必要了，又或者你开发了一个渲染引擎，需要一个编辑器让用户方便使用该引擎功能，这时就有需要打造一个编辑器了。本书使用C语言做案例分析，有一定的编程基础对阅读本书有一定帮助。


<a id="orgc88b1a8"></a>

## Beautiful Racket<sup><a id="fnr.4" class="footref" href="#fn.4" role="doc-backlink">4</a></sup>

*an introduction to language-oriented programming using Racket*

<div class="org-center">
<p>
优雅的Racket：用Racket介绍面向语言编程
</p>
</div>

> 你认为你已经懂了，并写下来确定了自己的想法，通过教授加深了自己的认知，但是当你实际做出来之后才算你真的理解了。
> 
> &#x2013;Alan Perlis at Yale University computer scientist

**我的结论**

如何创造一门语言？RacketLisp让这个过程变得简单而有趣。Racket是lisp的一个方言继承自scheme，是一个很适合编写语言的语言。虽然目前已经存在成百上千的语言了，但是还远远不够，还有很多的领域需要一门语言，例如艺术设计可以专门设计一门语言给艺术家门用，音乐创造也可以设计一门计算机语言用于创作音乐，或者还可以继续深挖到更深更特殊的领域，在大型公司中财务管理一般是很重要的，我们可以针对公司复杂的会计科目，开发出针对财务会计的计算机语言管理公司金钱，或者你也可以去发现哪些事情困扰着你，去询问他人生活工作中有什么困难，当遇到很多人有类似问题时，就可以发明你的语言或者软件针对的解决这个问题。语言不需要很复杂，简单的语言也能处理问题。当然如果你就是奔着想设计一个语言来参考此书的话，那这本书并不适合你，他可能能给你一些启发，但不是语言设计教科书或专业书。阅读此书需要一些编程经验。此书作者曾因Racket社区不友善行为而离开社区了。


<a id="org775c40b"></a>

## Technical Blogging, Second Edition<sup><a id="fnr.5" class="footref" href="#fn.5" role="doc-backlink">5</a></sup>

*Amplify Your Influence*

<div class="org-center">
<p>
技术博客第二版：扩大你的影响力
</p>
</div>

> 我知道你对工作，对任何事都很失望，也&#x2026;
> 
> 我只是想让你知道我理想你的感受。
> 
> 我曾经也是这样过来的。
> 
> 而且我敢打赌我比你更痛恨现在的工作，但是30年了我也还是过来了。
> 
> 只需记住，只要坚持的够久就会有好事发生。
> 
> &#x2013; Office Space

**我的结论**

如何打理你的博客？通过博客扩大你的影响力？首先你要确定博客的主题，不能什么都谈然后什么都不专业，你要确定一个方向，然后针对这个方向去做更深的探讨，例如你比较善长python，那就专门写pthon相关的文章，并进行深入分析，这样人们才能确定是否继续追踪你的博客。做好博客SEO这样人们更容易针对性找的到你的博客，内容为王博客最重要的是要做好内容，并且在固定时间经常性更新，一般选择星期三或者星期四更新，因为周一大家刚开始上班比较忙碌，周五的都准备放松休息了没心情看博客。做好各人社交网络的传播，有助于博客的扩散。根据博客阅览的数据分析（一般是google analytic），选择针对性的更新内容，然后精进自己的技术的同时对一些专业性的内容或服务进行收费，多跟观众互动把观众转化为顾客。然后继续扩散影响力建立团队建立起自己的博客王国。有需要的话，具体内容到书中观看。


<a id="org036072c"></a>

## Crafting Interpreters<sup><a id="fnr.6" class="footref" href="#fn.6" role="doc-backlink">6</a></sup>

<div class="org-center">
<p>
打造编译器
</p>
</div>

> 童话的真实不是因为告诉了我们恶龙的存在，而是恶龙终将被打败。
> 
> &#x2013;G.K. Chesterton by way of Neil Gaiman, Coraline

**我的结论**

我们第一次接触新鲜事物时总能给我们留下深刻的印象，第一次吃到巧克力，第一次游泳，第一次旅游等。所以学习工作也是一样，当你刚开始学习数学时，你希望曾经的自己接触到的第一本数学书是什么，当你想编程时你希望接触到的第一本编程书是什么，或者你想进入一个新的领域时你希望找到这个领域最适合新手的一本书，他既能照顾到新人的什么都不懂又能窥探整个领域让你有一个整体的认识，学习水到渠成，不至于跌跌撞撞，踩了许多坑，最后学了个皮毛。而这本书就是你希望进入语言这个领域时读的第一本书，至少作者是这么做的。全书通篇会写两个编译器，然后各章节有具体详细步骤，尽量不错过任何的细节，来达成我们所需要的功能。全书三个部份，第一部份介绍，介绍这本书所用到的概念，简单概括书中内容，第二部份为第一个编译器的制作，第三部份为第二个编译器的制作，阅读一本书，特别是有大量内容的书籍，目录和介绍是第一个必须要看的内容，对书有个大概的了解，能把握好阅读的方向。第一个编译器用Java第二编译器用C，虽然都是编译器，但是达成的目地是不同的，第一个编译器着重正确的达到目地，第二个着重更快的达到目地，阅读本书前对Java和C有点了解对阅读是有帮助的。


<a id="org4053ca0"></a>

## Master Emacs<sup><a id="fnr.7" class="footref" href="#fn.7" role="doc-backlink">7</a></sup>

<div class="org-center">
<p>
Emacs高级指南
</p>
</div>

> 人类是工具型动物&#x2026;
> 
> 没了工具他什么都不是，
> 
> 有了工具他就是全能。
> 
> &#x2013;Thomas Carlyle(1795-1881)

**我的结论**

一本非常好的教授emacs使用的书藉，他非常好的一点是，虽然emacs是一个非常复杂的仪器，但是他很精准的把重要内容讲清楚，不会让你在这个精密仪器的各种功能中眼花缭乱不知如何下手。然后对于重要的功能他不但说明了如何正确使用，并且可能的利弊以及将来可能会碰到的问题等都详细说明。用这本书入门emacs没错的，emacs这个编辑神器以及海量的神奇插件也值得花这些时间学习。


<a id="org67a85d0"></a>

## Benjamin Franklin: An American Life<sup><a id="fnr.8" class="footref" href="#fn.8" role="doc-backlink">8</a></sup>

<div class="org-center">
<p>
本杰明.富兰克林传：美国人的一生
</p>
</div>

> 1.  在一段时间内我要极其节俭，直到偿清所有欠款。
> 
> 2.  努力在一切场合说真话，不向任何人许下不可能履行的诺官，言一行均以真诚为本，这是一个有理智的人最动人的优点。
> 
> 3.  要求自己奋致力于正在从事的行业，不因任何一夜暴富的愚计划而动摇，因为勤劳和坚韧是最可靠的致富途径。
> 
> 4.  不议论他人的短处。
> 
> &#x2013;未来行为准则

**我的结论**

本杰明.富兰克林集各个头衔于一身，最著明的就是美国开国国父，起草和签定了独立宣言主和美国宪法。美国，可以说是现代文明的开创者和国际规则制定者，是什么造就了如此强大的一个国家，如此强大的一个文明，或许通过了解他的缔造者富兰克林能探窥一二。他最为我们所熟知可能来自于他的风争实验，来对电进行探索，100美元印着他的头像。这本书的作者也写了《史蒂夫·乔布斯传》，至少他写的传记得到了乔布斯肯定。我们可以通过了解这个人，来了解如何通过个人修养也建造自己的强大“王国”。


<a id="orgdbd5bef"></a>

## Practical Common Lisp<sup><a id="fnr.9" class="footref" href="#fn.9" role="doc-backlink">9</a></sup>

<div class="org-center">
<p>
Common Lisp实践
</p>
</div>

> 如果你热衷于用尽量简单易懂的代码解决问题，那CommonLisp是目前电脑上最好的语言了。
> 
> &#x2013;摘要

**我的结论**

如果你是一位经验丰验的工程师，那么用这本书过度到Common Lisp是一个不错的选择，基于已有的智慧与学识可以让我们更轻松面对挑战。而这本书就是在Lisp领域最好的选择，他让你基于已有的经验轻松过度到Lisp并快速应用到工作当中。我听说如何快速上手一门语言：就是用新的语言重新写你曾经做过的项目，例如你比较善长python，并且用他做过机器学习相关的项目，但是python用起来虽然很接近英语，但是他的运行速度也让你一言难尽，于是你听说了Rust这个语言性能接近C语法接近Python，于是你决定用这个语言，这个时候快速入门这个语言最好的方法就是用这个新语言重写一遍你曾经做过的机器学习项目，几周就可以熟练该语言了。这个学习方法很注重实践，而且算法，设计模式，编程方法各个语言大同小异，所以在已有的经验上这个学习方法不失为一个好方法，但是如果一个语言无法让你的思维发生转变，无法让你固有的经验有重新的认识，那么学习他的意义又在哪里呢？可能只剩工作了吧。所以Practical Common Lisp他让你清楚知道你已有的经验如何运用到Lisp这个语言中，并且也让你清楚了解CommonLisp的独到之处，并且有大幅篇章用实际项目实践其中的知识点。不建议新手用这本书入门，新手更推荐[COMMON LISP: A Gentle Introduction to Symbolic Computation](https://www.cs.cmu.edu/%7Edst/LispBook/)和[ANSI Common Lisp](http://www.paulgraham.com/acl.html)以及后继的[SICP](https://ocw.mit.edu/courses/6-001-structure-and-interpretation-of-computer-programs-spring-2005/)。


<a id="org0af41ea"></a>

## Paradigms of Artificial Intelligence Programming: Case Studies in Common Lisp<sup><a id="fnr.10" class="footref" href="#fn.10" role="doc-backlink">10</a></sup>

<div class="org-center">
<p>
人工智能编程范式：用CommonLisp作案例讲解
</p>
</div>

> 现在开始机器在世界上将占有一席之地。
> 
> &#x2013;Herbert Simon

**我的结论**

人工智能从来不是新鲜玩意，最原始的人工智能语言Lisp距今也已经60多年，而基于此已有成套的理论基础和经典案例了。而最近的风口似乎又回到的人工智能，像是历史的重演，而风浪之后又能留下什么呢！阅读此书最好懂一点CommonLisp，如果对人工智能感兴趣的这是一本不错的入门书藉，不过最好有编程基础，或者学习过[SICP](https://ocw.mit.edu/courses/6-001-structure-and-interpretation-of-computer-programs-spring-2005/)课程。


<a id="org1f8e013"></a>

## 相关阅读

-   [分享最近阅读的书籍清单(一)](recent_reading.md)
-   [分享最近阅读的书籍清单(二)](recent_reading2.zh.md)
-   [分享最近阅读的书藉清单(三)](recent_reading3.zh.md)
-   [分享最近阅读的书籍清单(四)](recent_reading4.zh.md)


# 写在后面

<table border="2" cellspacing="0" cellpadding="6" rules="groups" frame="hsides">


<colgroup>
<col  class="org-right" />

<col  class="org-left" />
</colgroup>
<thead>
<tr>
<th scope="col" class="org-right">NO.</th>
<th scope="col" class="org-left">Content</th>
</tr>
</thead>

<tbody>
<tr>
<td class="org-right">1</td>
<td class="org-left"><a href="recent_reading.html">分享最近阅读的书籍清单(一)</a></td>
</tr>


<tr>
<td class="org-right">2</td>
<td class="org-left"><a href="recent_reading2.zh.html">分享最近阅读的书籍清单(二)</a></td>
</tr>


<tr>
<td class="org-right">3</td>
<td class="org-left"><a href="recent_reading3.zh.html">分享最近阅读的书籍清单(三)</a></td>
</tr>


<tr>
<td class="org-right">4</td>
<td class="org-left"><a href="../build_it/how_face_midnight.html">如何面对35岁</a></td>
</tr>


<tr>
<td class="org-right">5</td>
<td class="org-left"><a href="recent_reading4.zh.html">分享最近阅读的书籍清单(四)</a></td>
</tr>


<tr>
<td class="org-right">6</td>
<td class="org-left"><a href="../build_it/why_you_should_learn_several_programming_language_and_where_to_learn_them.html">为什么你应该学习多种语言及哪里可以学到他们</a></td>
</tr>


<tr>
<td class="org-right">7</td>
<td class="org-left"><a href="../build_it/older_developer.zh.html">作为大龄程序员，你如何持续的保持自己的竞争优势</a></td>
</tr>


<tr>
<td class="org-right">8</td>
<td class="org-left"><a href="../build_it/how_to_stop_caring.zh.html">程序员在职场中如何缓解过度焦虑</a></td>
</tr>


<tr>
<td class="org-right">9</td>
<td class="org-left"><a href="share_note_app.zh.html">分享最近使用过的记笔记软件</a></td>
</tr>


<tr>
<td class="org-right">10</td>
<td class="org-left"><a href="recent_reading5.zh.html">分享最近阅读的书籍清单(五)</a></td>
</tr>
</tbody>

<tbody>
<tr>
<td class="org-right">&#xa0;</td>
<td class="org-left">如果喜欢该文章欢迎Star我的<a href="https://github.com/janegwaww/article">github</a></td>
</tr>


<tr>
<td class="org-right">&#xa0;</td>
<td class="org-left"><a href="https://paypal.me/janegwaww">捐助</a>我的创作</td>
</tr>


<tr>
<td class="org-right">&#xa0;</td>
<td class="org-left"><a href="https://v2ex.com/member/mascteen/topics">我的社区更新地址</a></td>
</tr>


<tr>
<td class="org-right">&#xa0;</td>
<td class="org-left">Email: <a href="mailto:tiglapiles@gmail.com">tiglapiles@gmail.com</a></td>
</tr>
</tbody>

<tbody>
<tr>
<td class="org-right">&#xa0;</td>
<td class="org-left"><a href="https://www.janegwaww.com">Home Page</a></td>
</tr>
</tbody>
</table>


# Footnotes

<sup><a id="fn.1" href="#fnr.1">1</a></sup> <https://www.amazon.com/How-Take-Smart-Notes-Nonfiction/dp/1542866502>

<sup><a id="fn.2" href="#fnr.2">2</a></sup> <https://book.douban.com/subject/35503571/>

<sup><a id="fn.3" href="#fnr.3">3</a></sup> <http://www.finseth.com/craft/>

<sup><a id="fn.4" href="#fnr.4">4</a></sup> <https://beautifulracket.com/>

<sup><a id="fn.5" href="#fnr.5">5</a></sup> <https://medium.com/pragmatic-programmers/table-of-contents-10982edb748f>

<sup><a id="fn.6" href="#fnr.6">6</a></sup> <https://craftinginterpreters.com/>

<sup><a id="fn.7" href="#fnr.7">7</a></sup> <https://www.masteringemacs.org/>

<sup><a id="fn.8" href="#fnr.8">8</a></sup> <https://book.douban.com/subject/26371154/>

<sup><a id="fn.9" href="#fnr.9">9</a></sup> <https://gigamonkeys.com/book/>

<sup><a id="fn.10" href="#fnr.10">10</a></sup> <https://github.com/norvig/paip-lisp>
