
# Table of Contents

1.  [分享最近阅读的书藉清单（一）](#org3bdb285)
    1.  [Code Complete](#org7988539)
    2.  [Structure and Interpretation of Computer Programs](#org6239806)
    3.  [The Pragmatic Programmer: Your Journey to Mastery](#org9b5123b)
    4.  [Design Patterns: Elements of Reusable Object-Oriented Software](#orgd058111)
    5.  [Refactoring: Improving the Design of Existing Code,Second Edition](#orgab0ac28)
    6.  [TypeScript Documentation](#org66fdea0)
    7.  [Fullstack Vue - The Complete Guide to Vue.js](#orgf2f6828)
    8.  [An Introduction to Programming in Emacs Lisp](#org3274932)
    9.  [Composing Software](#orge74f1e7)
    10. [Eloquent JavaScript](#orgb2e69fa)
    11. [Simplifying JavaScript](#org65c16a2)
    12. [A Philosophy of Software Design](#orgb10fd2f)
    13. [Learning GNU Emacs](#org67c5d91)
    14. [Rediscovering JavaScript](#orgc3b1393)
    15. [Harley Hahn's Emacs Field Guide](#orgef7d7aa)
    16. [fullstack react](#org54391e2)
    17. [Land of Lisp](#org6c0af05)
    18. [曾国潘家书](#org18c655b)
    19. [Designing Data-Intensive Applications](#orgfdfc88b)
    20. [史记](#org19a456f)
    21. [写在后面](#orgcf94439)



<a id="org3bdb285"></a>

# 分享最近阅读的书藉清单（一）

> 从长远来看，我们塑造我们的生活，我们塑造我们自己。这个过程永远不会结束, 直到我们死去。
> 而我们做出的选择最终是我们自己的责任。 &#x2014;埃莉诺·罗斯福

这些都是在行业中或历史中的经典书藉，我想把这些优秀的书藉分享出来，并賳上自己的一些主观想法，能让更多人知道并从中受益。
这里只是做一个引荐，精彩需要你自己亲自拜读从中感受。


<a id="org7988539"></a>

## Code Complete<sup><a id="fnr.1" class="footref" href="#fn.1">1</a></sup>

代码大全

> 一个软件设计师想通过需求进行合理的，没有错误的程序设计，那是不现实的。
> 从来没有那样开发过任何系统，而且可能永远也不会。 甚至教科书和论文中显示的小型程序开发都是不现实的。
> 在需求人向我们展示他希望他所要做的事，而不是已经实际发生的事之前，已经对它们进行了修改和修订。
> &#x2014; 大卫·帕纳斯（David Parnas）和保罗·克莱门特（Paul Clements）

> 设计是一个启发式过程,隐喻是启示而不是算法。
> 典型情况下需求会有多少改动？IBM和其他公司的研究发现， 平均水平的项目在开发过程中，需求会有25%的变化（Boehm 1981，Jones 1994，Jones 2000）。
> 在典型的项目中，需求变更导致的返工占到返工总量的75%到85%（Leffingwell 1997，Wiegers 2003）。
> 注意项目的商业案例：有些需求作为功能特色来看是不错的想法，但是当你评估“增加的商业价值”时就会觉得它是个糟透了的主意。
> 一个好的项目规划者，应能尽早清楚项目中的主要风险，以使大部分工作能平稳进行。
> &#x2014; 文中摘要

-   我的结论

我们的设计不能局限于语言，应该利用语言，作为刚入行的人应该阅读他，他提供了丰富的经验和细节，
而作为经验丰富的从业者也应该翻翻能刷新一些认知；一个项目从需求到设计到编码到发布，我们的主要工作是编码，
可是结构设计对于项目的生死至关重要，所以设计做好了其他就能一气呵成。这是一本软件设计百科全书，
囊括了软件设计的方方面面。

-   第一部份：打好基础

一本好书的一开始一般会说明为什么会写这本书，本书也不例外。什么是软件构造，软件构造为什么如此重要，以及作为有1000页的大全书你应该如何去使用他。
当你了解上面这些之后，然后会告诉中软件行业中的一些专业术语，或者说行话吧。（例如你想学数学那你要了解数学公式的表达，因为他可以大大缩减用正常语言来表达一个公式，
我自己感受最深的是欧几里德几何原本，里面每一卷会给出公理和定义，然后在这些公理和定义之上推理出命题，都是用文字描述的，因为都是建立在公理定义之上的，严谨自不必说，
但是现在都把这些都换成数学公式，如果你有一定的数学的严谨思维，你可以很快的通读这本书了。） 之后是一个项目开始之前的工作：首先是先决条件，然后你要开发的软件类型，
并且一定要花足够多时间把这些前期条件作好，因为往往改需求的成本是最高的，以及作为一个开发如何应付领导。 （当要你冲冲上马项目并且与投资人关系不好时，那只能祝你好运了，
或者假装在做项目了实际没有，第三是在技术上教育领导讲道理，最后是找另一份工作，市场虽然变化莫测但优秀的工程师总是稀缺资源）

-   第二部分：创建高质量的代码
-   第三部分：变量
-   第四部分：语句
-   第五部分：代码改善
-   第六部分：系统考虑
-   第七部分：软件工艺


<a id="org6239806"></a>

## Structure and Interpretation of Computer Programs<sup><a id="fnr.2" class="footref" href="#fn.2">2</a></sup>

计算机程序的构造和解释

-   我的结论

这本书，准确的说应该是这门课程，因为这本书是这门课的配套教材，他是MIT的基础编程课程，而这门课在编程中经久不衰，从1985年开始到现在，
现在MIT基础编程课程改用pythod了。但是lisp这门第二古老语言一点也不过时，而这本书或者说这个课程讲了很多思想也被现在各种软件设计和语言所借鉴。
如递归，循环，作用域，lamada，分层等，并衍生出了多个方言。

> "总之，我希望我们不是为了做任务而做任务。不要觉得自己是做产品销售的。这个世界已经有很多这种人了。
> 我们知道的知识别人也将很容易学习到。不要认为成功就是把一切劳动掌握在手中。我们有什么？
> 我想也希望是智慧：相比于我们第一次接触计算机科学，我们有能力看到更多，并能做的更多。
> 我想我们做计算机科学的最重要是要保持开心。当开始学习时应该有很多乐趣。当我们按客户的需求做事时我们开始认真对待。
> 我们也开始为成功和完成产品做事。我认为我们不是。我想我们的责任是把东西朝正确的方向规划出来之后，然后又可以快乐的玩爽了。
> 我希望计算机科学永远不要失去乐趣。"
> &#x2014; 文中摘要


<a id="org9b5123b"></a>

## The Pragmatic Programmer: Your Journey to Mastery<sup><a id="fnr.3" class="footref" href="#fn.3">3</a></sup>

程序员修炼之道-从小工到专家

> 生活是你自己的。 分享它。 庆祝它。 构建它。 然后玩得开心！
> &#x2014; 最后一个提示


<a id="orgd058111"></a>

## Design Patterns: Elements of Reusable Object-Oriented Software<sup><a id="fnr.4" class="footref" href="#fn.4">4</a></sup>

设计模式-可复用面向对象软件的基础

-   我的结论

橡棋大师和菜鸟的区别是能从棋盘中找到规律而后总能领先对手几步,如果棋子无任何规律摆放那大师和菜鸟没什么区别,
做开发能从复杂的业务中抽象出普遍的设计模式,并能在遇到问题运用该模式,这就是开发大师和菜鸟的区别,
这本书首先教你如何用设计模式解决问题然后列举到目前为止的模式并举例子


<a id="orgab0ac28"></a>

## Refactoring: Improving the Design of Existing Code,Second Edition<sup><a id="fnr.5" class="footref" href="#fn.5">5</a></sup>

重构-改善既有代码的设计（第2版）

> 任何傻瓜都可以编写计算机可以理解的代码。 而好的程序员编写人类可以理解的代码。
> &#x2014; 重构代码tips


<a id="org66fdea0"></a>

## TypeScript Documentation<sup><a id="fnr.6" class="footref" href="#fn.6">6</a></sup>

TypeScript文档主页

-   我的结论

珠玉在前，你如何在其上弥补瑕疵？因此一份好的文档尤为重要。JS的弱类型使其容易上手也给了TS机会，但是TS如何做到让别人放心使用他，
首先由微软做后台，然后着重给做后台的人员使用的前端JS，然后语法上也没有做更多的改变，只是在原语法上扩展了类型，前端开发人员也无须过多的学习成本；
还有用TS写出的强大好用的主载了前端开发的编辑器vscode；然后最最重要的：一份好的文档，一进入界面，
就是非常有针对性的关于该语言的你所要知道的让你快速上手的知识，及很多大厂的使用范例，你无需任何顾忌；
从简单的介绍，快速的上手到说明书再到API配置等，到说明书上针对类型的菜单，无不透露着只要这一份文档你有一定的JS基础不管是前端或后端的就可以简单易上手这个语言了。
TS能在JS如此流行当下能快速的流行起来不无他的道理。


<a id="orgf2f6828"></a>

## Fullstack Vue - The Complete Guide to Vue.js<sup><a id="fnr.7" class="footref" href="#fn.7">7</a></sup>

全栈VUE

-   我的结论

框架全栈系列书藉,先让你用框架最原始的方法写一个APP,让你对技术有一个基础的概念,然后琢步深入用教你如何使用框架,
这个系列的书藉大体是这个框架，再到组件化开发，定制化事件，全局状态管理，与服务端交互，表单管理等.针对VUE这个书着重介绍单文件组件,Vuex,及VUE开发。


<a id="org3274932"></a>

## An Introduction to Programming in Emacs Lisp<sup><a id="fnr.8" class="footref" href="#fn.8">8</a></sup>

Emacs Lisp编程简介

-   我的结论

一个软件的强大或许更再于他文档的齐全和扩展性，作为emacs配套的扩展语言ellisp, 此书是该语言的入门，
而此书的强大之处是他就像一本教科书级别的编程入门书，所有人都能看懂，当然后面还有更多配套的扩展书藉。


<a id="orge74f1e7"></a>

## Composing Software<sup><a id="fnr.9" class="footref" href="#fn.9">9</a></sup>

撰写软件

-   我的结论

用JS讲述编程的本质，即把一个复杂的问题分解为各简单的小问题，用编程单位一般是函数写这些小逻辑，然后把这些方法组合起来，
解决复杂的业务逻辑。书里包含组合方法，着重介绍函数编程，并且推荐：纯函数>组合函数>组合对象>Mixins>继承，推荐给要在JS上更上一层楼的。


<a id="orgb2e69fa"></a>

## Eloquent JavaScript<sup><a id="fnr.10" class="footref" href="#fn.10">10</a></sup>

雄辩的JavaScript

-   我的结论

这是另一本全面学习JS的好书，先讨论JS语言，然后与游览器的交互，最后nodejs。这是一本关于计算机指导的书，它立意高，
通过JS这个跨平台游览器语言来指导编程算法设计等，让你不局限于语言有全局观。他适合初学者没有专业词汇，知识让人易于接受。


<a id="org65c16a2"></a>

## Simplifying JavaScript<sup><a id="fnr.11" class="footref" href="#fn.11">11</a></sup>

简化JavaScript

-   我的结论

如果你纠结于用Object, Array, Map还是Set.那这是一本难得的书，他给你在代码中最直接的提示，
并分赋值，数据，集合，条件，循环等章节。如何让代码看起来更整洁，选择最优的集合等等。首先给你一个提示然后解释为什么这么做。解决代码选择困难症。


<a id="orgb10fd2f"></a>

## A Philosophy of Software Design<sup><a id="fnr.12" class="footref" href="#fn.12">12</a></sup>

软件设计哲学

-   我的结论

如果你志力于软件设计，这本书是一个好的开始，它讲述了软件设计的基本原则：减少复杂性，封装方法，变量名，固定的风格等等，
就是说你想做软件设计遵循这些原则一定是正确的方向。软件设计不一定要遵循这些原则，但一个好的软件设计一定能找到这些哲学。


<a id="org67c5d91"></a>

## Learning GNU Emacs<sup><a id="fnr.13" class="footref" href="#fn.13">13</a></sup>

学习GNU Emacs

-   我的结论

动物书，作为最强大的编辑器，此书的内容确实九牛一毛，简单的介绍，快速的上手，跟其他所有的动物书一样着重操作，
他也几乎囊括了emacs的各个方面，但是是点到为止，也介绍了几种语言下的配置，emacs可以作为终生工具和操作系统来使用，有一定的编程经验此书作为入门不错。


<a id="orgc3b1393"></a>

## Rediscovering JavaScript<sup><a id="fnr.14" class="footref" href="#fn.14">14</a></sup>

重新发现JavaScript

-   我的结论

此书浅显易懂的讲JS最新语法，即使之前没有接触过JS的也能看懂，但如果要全面学习JS的这恐怕不是一本好书。
他着重讲了JS好的语法，也讲述了JS最新的面向对象编程，同步方法以及更深层次的元编程等，有一定的JS基础此书用来学习JS最新语法是个不错的选择。


<a id="orgef7d7aa"></a>

## Harley Hahn's Emacs Field Guide<sup><a id="fnr.15" class="footref" href="#fn.15">15</a></sup>

哈雷·哈恩（Harley Hahn）的Emacs现场指南

-   我的结论

工欲善其事必先利其器，好的编辑器可以改变你的思维方式。没人愿意花时间教一个人如何使用工具f，
你只能通过书来学习练习，而此书就像位老师把emacs历史、环境、益处、使用方法等娓娓道来，有人说如果vim是小孩的玩具，那emacs就是大人的工具。


<a id="org54391e2"></a>

## fullstack react<sup><a id="fnr.16" class="footref" href="#fn.16">16</a></sup>

全栈react

-   我的结论

作为目前最流行的前端框架，react将交互性做到了最好，而这本书做入门指南也是操作与理论相结合，
他指导你一步步将代码写出来，并在JS的基础上将react的概念解释清楚，并囊括react周边生态，他有大量的代码，详细的解释，阅读完本书你完全可以写一个react app.


<a id="org6c0af05"></a>

## Land of Lisp<sup><a id="fnr.17" class="footref" href="#fn.17">17</a></sup>

Lisp之地

-   我的结论

这本书语言有趣，用生动的动画讲述lisp这个第二古老的语言，最古老的是Fortran，他到现在还在被使用，
而目前有很多语言都借鉴了他，包括现在流行的JS，他如此强大，以至于有人说作者发现了这门语言而不是发明他，他语法简洁，以至于当你学习他之后就能取代你熟练的语言成为你的母语。


<a id="org18c655b"></a>

## 曾国潘家书<sup><a id="fnr.18" class="footref" href="#fn.18">18</a></sup>


<a id="orgfdfc88b"></a>

## Designing Data-Intensive Applications<sup><a id="fnr.19" class="footref" href="#fn.19">19</a></sup>

数据密集型应用系统设计


<a id="org19a456f"></a>

## 史记<sup><a id="fnr.20" class="footref" href="#fn.20">20</a></sup>

-   我的结论

我们为什么要读历史？因为时代虽然不一样，但历史总是重复的，但是历史本身又记录什么？举《史记》这个例子：司马迁说唯倜傥非常之人称焉，就是说历史记录的不是普通人，
而是非常之人，例如我们耳熟能详的项羽本纪，项羽这个人中国五千年历史上几乎没出现过类似的，他的得失与其性格值得为之记录。而普通人就没什么好记的了，
因为太多没什么好记的了;但是历史人物他们本身也是人，只是他们做到了人本身的极限并可以为之记录的人，既然如此我们看到了历史人物的故事那就可以以此伸展开并更容易猜出普通人的故事了。
不仅是史书，现在关于记录的媒体就更多了，例如我看了辛普森一家关于婚姻的故事，故事很有想象力很幽默搞笑，其中讲到辛普森年轻时的老婆回来与现在老婆抢丈夫，
这样辛普森就面临选择了，年轻的一个说我可以给你更加刺激与完美的服务，现一个说我知道你所有的优点与缺点并愿意接纳你，最后辛普森和现老婆抱在了一起，
你如果没结婚当然不懂婚姻后的生活，但你可以借鉴这个至少以后和小三抢男人时知道了一个技巧。回到史记这部书，有十二本纪写的是十二个算是当时能操纵 国家命运的人，
而里面唯一一个写女人是吕后本纪，所以你也可以以此为借鉴了解天下所有女人， 吕后是介绍给刘邦的，刘邦死后吕后掌权第一件事是杀戚夫人为人彘及各个威胁政权的人，
然后分封各姓吕的人，你想是不是每个女人都会这么做，只是她们没办法达到那个位置，无法释放那欲望而已，当然肯定有不一样的女人，只是吕后作为一个极端例子，反应的也是绝大多数的女人，
因为你没办法阅尽所有女人，所以典型的抓出来就了解了，这就是读书特别是史书的功用。回到现在本身，我们工作生活作为一个普通人，难道不是一直在重复历史吗？


<a id="orgcf94439"></a>

## 写在后面

本清单所列书藉我已读过一遍或多遍

本清单会持续更新至満意层度

后期也会随着阅读出新的清单

本文地址<https://github.com/tiglapiles/article/blob/master/recent_reading.org>

社区更新地址<https://v2ex.com/member/tiglapiles（主要更新地址>）

如果你想访问更多我的文章欢迎访问我的[github仓库](https://github.com/tiglapiles/article)

转载请注明出处


# Footnotes

<sup><a id="fn.1" href="#fnr.1">1</a></sup> <https://book.douban.com/subject/1477390/>

<sup><a id="fn.2" href="#fnr.2">2</a></sup> <https://book.douban.com/subject/34464721/>

<sup><a id="fn.3" href="#fnr.3">3</a></sup> <https://book.douban.com/subject/1152111/>

<sup><a id="fn.4" href="#fnr.4">4</a></sup> <https://book.douban.com/subject/1052241/>

<sup><a id="fn.5" href="#fnr.5">5</a></sup> <https://book.douban.com/subject/30468597/>

<sup><a id="fn.6" href="#fnr.6">6</a></sup> <https://www.typescriptlang.org/docs/home.html>

<sup><a id="fn.7" href="#fnr.7">7</a></sup> <https://book.douban.com/subject/30327032/>

<sup><a id="fn.8" href="#fnr.8">8</a></sup> <https://book.douban.com/subject/1432501/>

<sup><a id="fn.9" href="#fnr.9">9</a></sup> <https://book.douban.com/subject/35002566/>

<sup><a id="fn.10" href="#fnr.10">10</a></sup> <https://book.douban.com/subject/5402021/>

<sup><a id="fn.11" href="#fnr.11">11</a></sup> <https://book.douban.com/subject/30251546/>

<sup><a id="fn.12" href="#fnr.12">12</a></sup> <https://book.douban.com/subject/30218046/>

<sup><a id="fn.13" href="#fnr.13">13</a></sup> <https://book.douban.com/subject/1236987/>

<sup><a id="fn.14" href="#fnr.14">14</a></sup> <https://book.douban.com/subject/30322511/>

<sup><a id="fn.15" href="#fnr.15">15</a></sup> <https://book.douban.com/subject/26913125/>

<sup><a id="fn.16" href="#fnr.16">16</a></sup> <https://book.douban.com/subject/30346678/>

<sup><a id="fn.17" href="#fnr.17">17</a></sup> <https://book.douban.com/subject/3704991/>

<sup><a id="fn.18" href="#fnr.18">18</a></sup> <https://book.douban.com/subject/1491153/>

<sup><a id="fn.19" href="#fnr.19">19</a></sup> <https://book.douban.com/subject/30329536/>

<sup><a id="fn.20" href="#fnr.20">20</a></sup> <https://book.douban.com/subject/1077847/>
