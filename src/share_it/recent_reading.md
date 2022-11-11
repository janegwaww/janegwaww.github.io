

# 分享最近阅读的书籍清单（一）

1.  [Code Complete](#org8352212)
2.  [Structure and Interpretation of Computer Programs](#org098d891)
3.  [The Pragmatic Programmer: Your Journey to Mastery](#org4797c60)
4.  [Design Patterns: Elements of Reusable Object-Oriented Software](#org1f4a759)
5.  [Refactoring: Improving the Design of Existing Code,Second Edition](#org7c4645d)
6.  [TypeScript Documentation](#orgeaa6e91)
7.  [Fullstack Vue - The Complete Guide to Vue.js](#org37bb475)
8.  [An Introduction to Programming in Emacs Lisp](#org7ed9d9c)
9.  [Composing Software](#orge47d0ee)
10. [Eloquent JavaScript](#org1f0ec73)
11. [Simplifying JavaScript](#orgbd99d12)
12. [A Philosophy of Software Design](#org3813e13)
13. [Learning GNU Emacs](#orgd3418ea)
14. [Rediscovering JavaScript](#orgf335c74)
15. [Harley Hahn's Emacs Field Guide](#org358e846)
16. [fullstack react](#org6944b16)
17. [Land of Lisp](#orga90ad22)
18. [曾国潘家书](#org789be65)
19. [Designing Data-Intensive Applications](#org3e5ca4c)
20. [史记](#org6433bf0)

> 从长远来看，我们塑造我们的生活，我们塑造我们自己。这个过程永远不会结束, 直到我们死去。而我们做出的选择最终是我们自己的责任。
> 
> &#x2013;埃莉诺·罗斯福

这些都是在行业中或历史中的经典书藉，我想把这些优秀的书藉分享出来，并賳上自己的一些主观想法，能让更多人知道并从中受益。这里只是做一个引荐，精彩需要你自己亲自拜读从中感受。


<a id="org8352212"></a>

## Code Complete<sup><a id="fnr.1" class="footref" href="#fn.1" role="doc-backlink">1</a></sup>

代码大全

> 一个软件设计师想通过需求进行合理的，没有错误的程序设计，那是不现实的。从来没有那样开发过任何系统，而且可能永远也不会。 甚至教科书和论文中显示的小型程序开发都是不现实的。在需求人向我们展示他希望他所要做的事，而不是已经实际发生的事之前，已经对它们进行了修改和修订。
> 
> &#x2013;大卫·帕纳斯（David Parnas）和保罗·克莱门特（Paul Clements）

> 设计是一个启发式过程,隐喻是启示而不是算法。典型情况下需求会有多少改动？IBM和其他公司的研究发现， 平均水平的项目在开发过程中，需求会有25%的变化（Boehm 1981，Jones 1994，Jones 2000）。在典型的项目中，需求变更导致的返工占到返工总量的75%到85%（Leffingwell 1997，Wiegers 2003）。注意项目的商业案例：有些需求作为功能特色来看是不错的想法，但是当你评估“增加的商业价值”时就会觉得它是个糟透了的主意。一个好的项目规划者，应能尽早清楚项目中的主要风险，以使大部分工作能平稳进行。
> 
> &#x2013;文中摘要

-   我的结论
    
    我们的设计不能局限于语言，应该利用语言，作为刚入行的人应该阅读他，他提供了丰富的经验和细节，而作为经验丰富的从业者也应该翻翻能刷新一些认知；一个项目从需求到设计到编码到发布，我们的主要工作是编码，可是结构设计对于项目的生死至关重要，所以设计做好了其他就能一气呵成。这是一本软件设计百科全书， 囊括了软件设计的方方面面。

-   第一部份：打好基础
    
    一本好书的一开始一般会说明为什么会写这本书，本书也不例外。什么是软件构造，软件构造为什么如此重要，以及作为有1000页的大全书你应该如何去使用他。当你了解上面这些之后，然后会告诉中软件行业中的一些专业术语，或者说行话吧。（例如你想学数学那你要了解数学公式的表达，因为他可以大大缩减用正常语言来表达一个公式，我自己感受最深的是欧几里德几何原本，里面每一卷会给出公理和定义，然后在这些公理和定义之上推理出命题，都是用文字描述的，因为都是建立在公理定义之上的，严谨自不必说，但是现在都把这些都换成数学公式，如果你有一定的数学的严谨思维，你可以很快的通读这本书了。） 之后是一个项目开始之前的工作：首先是先决条件，然后你要开发的软件类型，并且一定要花足够多时间把这些前期条件作好，因为往往改需求的成本是最高的，以及作为一个开发如何应付领导。 （当要你冲冲上马项目并且与投资人关系不好时，那只能祝你好运了，或者假装在做项目了实际没有，第三是在技术上教育领导讲道理，最后是找另一份工作，市场虽然变化莫测但优秀的工程师总是稀缺资源）

-   第二部分：创建高质量的代码
    
    设计是什么？设计就是构建，像盖房子;在软件构建中，你需要构建蓝图，设计模式，用类和路徑构建系统架构。讲道设计中挑战，关键，单元等。然后是构健类，软件又是一个个类组成的，而类其是就是抽像数据类型，如何写出高质量类接口，以及每个类都有合理存在的理由，及类之上的包等; 娄之后是如何写出高质量的路徑，好的路徑使代码更具可读性，可靠性，可维护性;下一个讲的是防御性编码，当他人运行代码时无后顾之忧，正确处理错误，bug，例外; 最后是伪代码编程，何谓伪代码，就是不能运行的代码，你把功能逻辑功能以一种类似代码的形式写出来，这样的好处是更容易看的懂，也方便做文档以便后期更新维护。

-   第三部分：变量
    
    变量是什么？变量其实就是可以更改的数据，他是代码的重要组成部分，而变量中最重要的就是取名字，一个好的变量名字，可以大大提向代码的质量，变量中各种数据类型，包括： 数值，字符，枚举，不可变值，数组等，或者创建你自已类型;

-   第四部分：语句
    
    代码中语句最好依一定的顺序进行组合，如果没有顺序就根据相关性组合在一起; 不要做太多if-else的嵌套，如果一定要做，最好有一定顺序，增加可读性; 然后环循或者递归是比较复杂的，我们要谨慎处理;

-   第五部分：代码改善
    
    高质量的代码有什么特性，外部特性包括：可修复性，有用性，高效性，可靠性，完整性，适应性，准确性，稳健性; 内部特性包括：可维护性，灵活性，可移植性，可重用性，可读性，可测试性，易理解性; 如何进行代码测试，debug，重构等。

-   第六部分：系统考虑
    
    软件大小，性能都要考虑到系统的效能;

-   第七部分：软件工艺
    
    代码中的个人风格，缩进、排列、组合、排布等; 最好的要有注释，有个人主题和风格。


<a id="org098d891"></a>

## Structure and Interpretation of Computer Programs<sup><a id="fnr.2" class="footref" href="#fn.2" role="doc-backlink">2</a></sup>

计算机程序的构造和解释

> "总之，我希望我们不是为了做任务而做任务。不要觉得自己是做产品销售的。这个世界已经有很多这种人了。我们知道的知识别人也将很容易学习到。不要认为成功就是把一切劳动掌握在手中。我们有什么？我想也希望是智慧：相比于我们第一次接触计算机科学，我们有能力看到更多，并能做的更多。我想我们做计算机科学的最重要是要保持开心。当开始学习时应该有很多乐趣。当我们按客户的需求做事时我们开始认真对待。我们也开始为成功和完成产品做事。我认为我们不是。我想我们的责任是把东西朝正确的方向规划出来之后，然后又可以快乐的玩爽了。我希望计算机科学永远不要失去乐趣。"
> 
> &#x2013;文中摘要

-   我的结论
    
    这本书，准确的说应该是这门课程，因为这本书是这门课的配套教材，他是MIT的基础编程课程，而这门课在编程中经久不衰，从1985年开始到现在，现在MIT基础编程课程改用pythod了。但是lisp这门第二古老语言一点也不过时，而这本书或者说这个课程讲了很多思想也被现在各种软件设计和语言所借鉴。如递归，循环，作用域，lamada，分层等，并衍生出了多个方言。


<a id="org4797c60"></a>

## The Pragmatic Programmer: Your Journey to Mastery<sup><a id="fnr.3" class="footref" href="#fn.3" role="doc-backlink">3</a></sup>

程序员修炼之道-从小工到专家

> 生活是你自己的。 分享它。 庆祝它。 构建它。 然后玩得开心！
> 
> &#x2013;最后一个提示

-   我的结论
    
    技术千变万化，但使用技术的人是不容易改变的，而本书正是针对的是人，如何成为更好的程序员？如何帮助他人成为更好的程序员？你可以成为专家。这关乎你的态度，风格和解决问题方式，对自己的代码负责。


<a id="org1f4a759"></a>

## Design Patterns: Elements of Reusable Object-Oriented Software<sup><a id="fnr.4" class="footref" href="#fn.4" role="doc-backlink">4</a></sup>

设计模式-可复用面向对象软件的基础

> 请记住，这不是一本读完就放在书架上的书。 我们希望你把它当作一本参考书，时不时地翻阅它以获取新的设计见解和灵感。
> 
> &#x2013;摘要

-   我的结论
    
    橡棋大师和菜鸟的区别是能从棋盘中找到规律而后总能领先对手几步,如果棋子无任何规律摆放那大师和菜鸟没什么区别,做开发能从复杂的业务中抽象出普遍的设计模式,并能在遇到问题运用该模式,这就是开发大师和菜鸟的区别,这本书首先教你如何用设计模式解决问题然后列举到目前为止的模式并举例子


<a id="org7c4645d"></a>

## Refactoring: Improving the Design of Existing Code,Second Edition<sup><a id="fnr.5" class="footref" href="#fn.5" role="doc-backlink">5</a></sup>

重构-改善既有代码的设计（第2版）

> 任何傻瓜都可以编写计算机可以理解的代码。 而好的程序员编写人类可以理解的代码。
> 
> &#x2013;重构代码tips

-   我的结论
    
    当我们完成了一个完整功能的代码后，我们需要一次又一次轮循去修改它优化它，实现代码的可读性，可复用性和可维护性;大型的软件更是如此，但是确是很少有人能做到去优化代码，或者能做到正确的优化代码;而这本书填补了这么一个空白，即完成的代码和完美的代码之间的空白。代码和艺术似乎又有点类似，你需要一遍又一遍的去雕琢它，而好的重构也需要非常细微。当你第一次开始做某事时你就直接去做，当你第二次做时，可能会重复的做同一件事，当你第三次再做类似的事你就去重构它。


<a id="orgeaa6e91"></a>

## TypeScript Documentation<sup><a id="fnr.6" class="footref" href="#fn.6" role="doc-backlink">6</a></sup>

TypeScript文档主页

> 最佳软件工程实践与一般软件工程实践之间的差距非常广泛——也许比任何其他工程学科都要广泛。 而这时候能有一个传授最佳实践的工具就很重要了。
> 
> &#x2013;弗雷德·布鲁克斯

-   我的结论
    
    珠玉在前，你如何在其上弥补瑕疵？因此一份好的文档尤为重要。JS的弱类型使其容易上手也给了TS机会，但是TS如何做到让别人放心使用他，首先由微软做后台，然后着重给做后台的人员使用的前端JS，然后语法上也没有做更多的改变，只是在原语法上扩展了类型，前端开发人员也无须过多的学习成本；还有用TS写出的强大好用的主载了前端开发的编辑器vscode；然后最最重要的：一份好的文档，一进入界面，就是非常有针对性的关于该语言的你所要知道的让你快速上手的知识，及很多大厂的使用范例，你无需任何顾忌；从简单的介绍，快速的上手到说明书再到API配置等，到说明书上针对类型的菜单，无不透露着只要这一份文档你有一定的JS基础不管是前端或后端的就可以简单易上手这个语言了。TS能在JS如此流行当下能快速的流行起来不无他的道理。


<a id="org37bb475"></a>

## Fullstack Vue - The Complete Guide to Vue.js<sup><a id="fnr.7" class="footref" href="#fn.7" role="doc-backlink">7</a></sup>

全栈VUE

> 如果“盒子”是边界约束和条件，那么诀窍是找到盒子……不要跳出盒子思考——找到盒子。
> 
> &#x2013;安迪·亨特和戴夫 托马斯

-   我的结论
    
    框架全栈系列书藉,先让你用框架最原始的方法写一个APP,让你对技术有一个基础的概念,然后琢步深入用教你如何使用框架,这个系列的书藉大体是这个框架，再到组件化开发，定制化事件，全局状态管理，与服务端交互，表单管理等.针对VUE这个书着重介绍单文件组件,Vuex,及VUE开发。


<a id="org7ed9d9c"></a>

## An Introduction to Programming in Emacs Lisp<sup><a id="fnr.8" class="footref" href="#fn.8" role="doc-backlink">8</a></sup>

Emacs Lisp编程简介

> 需求如水。 当它们被冻结时，它们更容易雕琢。
> 
> &#x2013;摘要

-   我的结论
    
    一个软件的强大或许更再于他文档的齐全和扩展性，作为emacs配套的扩展语言ellisp, 此书是该语言的入门，而此书的强大之处是他就像一本教科书级别的编程入门书，所有人都能看懂，当然后面还有更多配套的扩展书藉。


<a id="orge47d0ee"></a>

## Composing Software<sup><a id="fnr.9" class="footref" href="#fn.9" role="doc-backlink">9</a></sup>

撰写软件

> 如果我看得更远，那是因为我站在巨人的肩膀上
> 
> &#x2013;艾萨克·牛顿

-   我的结论
    
    用JS讲述编程的本质，即把一个复杂的问题分解为各简单的小问题，用编程单位一般是函数写这些小逻辑，然后把这些方法组合起来，解决复杂的业务逻辑。书里包含组合方法，着重介绍函数编程，并且推荐：纯函数>组合函数>组合对象>Mixins>继承，推荐给要在JS上更上一层楼的。


<a id="org1f0ec73"></a>

## Eloquent JavaScript<sup><a id="fnr.10" class="footref" href="#fn.10" role="doc-backlink">10</a></sup>

雄辩的JavaScript

> 我们认为我们正在为自己的目的创建系统。 我们相信我们正在按照我们自己的形象制造它&#x2026;&#x2026;但计算机并不像我们一样。 它是我们自己非常纤细的一部分的投射：致力于逻辑、秩序、规则和清晰的那部分。
> 
> &#x2013;艾伦·厄尔曼，接近机器：技术狂热及其不满

-   我的结论
    
    这是另一本全面学习JS的好书，先讨论JS语言，然后与游览器的交互，最后nodejs。这是一本关于计算机指导的书，它立意高，通过JS这个跨平台游览器语言来指导编程算法设计等，让你不局限于语言有全局观。他适合初学者没有专业词汇，知识让人易于接受。


<a id="orgbd99d12"></a>

## Simplifying JavaScript<sup><a id="fnr.11" class="footref" href="#fn.11" role="doc-backlink">11</a></sup>

简化JavaScript

> 如果你不能向一个六岁的孩子解释清楚一个东西，那就是你自己真的不理解。
> 
> &#x2013;艾尔伯特 爱因斯坦

-   我的结论
    
    如果你纠结于用Object, Array, Map还是Set.那这是一本难得的书，他给你在代码中最直接的提示，并分赋值，数据，集合，条件，循环等章节。如何让代码看起来更整洁，选择最优的集合等等。首先给你一个提示然后解释为什么这么做。解决代码选择困难症。


<a id="org3813e13"></a>

## A Philosophy of Software Design<sup><a id="fnr.12" class="footref" href="#fn.12" role="doc-backlink">12</a></sup>

软件设计哲学

> 构建软件设计有两种方式：一种方式是简单到没有明显缺陷，另一种是复杂到没有明显缺陷。
> 
> &#x2013;C.A.R.霍尔

-   我的结论
    
    如果你志力于软件设计，这本书是一个好的开始，它讲述了软件设计的基本原则：减少复杂性，封装方法，变量名，固定的风格等等，就是说你想做软件设计遵循这些原则一定是正确的方向。软件设计不一定要遵循这些原则，但一个好的软件设计一定能找到这些哲学。


<a id="orgd3418ea"></a>

## Learning GNU Emacs<sup><a id="fnr.13" class="footref" href="#fn.13" role="doc-backlink">13</a></sup>

学习GNU Emacs

> 当我处理一个问题时，我从不考虑美。 我想只有如何解决问题。 但是当我完成后，如果解决方案不漂亮，我知道它是错误的。
> 
> &#x2013;R.巴克敏斯特富勒

-   我的结论
    
    动物书，作为最强大的编辑器，此书的内容确实九牛一毛，简单的介绍，快速的上手，跟其他所有的动物书一样着重操作，他也几乎囊括了emacs的各个方面，但是是点到为止，也介绍了几种语言下的配置，emacs可以作为终生工具和操作系统来使用，有一定的编程经验此书作为入门不错。


<a id="orgf335c74"></a>

## Rediscovering JavaScript<sup><a id="fnr.14" class="footref" href="#fn.14" role="doc-backlink">14</a></sup>

重新发现JavaScript

> 不要先问系统做了什么； 问它有什么作用！
> 
> &#x2013;伯特兰·迈耶

-   我的结论
    
    此书浅显易懂的讲JS最新语法，即使之前没有接触过JS的也能看懂，但如果要全面学习JS的这恐怕不是一本好书。他着重讲了JS好的语法，也讲述了JS最新的面向对象编程，同步方法以及更深层次的元编程等，有一定的JS基础此书用来学习JS最新语法是个不错的选择。


<a id="org358e846"></a>

## Harley Hahn's Emacs Field Guide<sup><a id="fnr.15" class="footref" href="#fn.15" role="doc-backlink">15</a></sup>

哈雷·哈恩（Harley Hahn）的Emacs现场指南

> 如有疑问，请使用蛮力。
> 
> &#x2013;巴特勒·兰普森

-   我的结论
    
    工欲善其事必先利其器，好的编辑器可以改变你的思维方式。没人愿意花时间教一个人如何使用工具，你只能通过书来学习练习，而此书就像位老师把emacs历史、环境、益处、使用方法等娓娓道来，有人说如果vim是小孩的玩具，那emacs就是大人的工具。


<a id="org6944b16"></a>

## fullstack react<sup><a id="fnr.16" class="footref" href="#fn.16" role="doc-backlink">16</a></sup>

全栈react

> 让事情尽可能简单——但不是随便。
> 
> &#x2013;艾尔伯特.爱因斯坦

-   我的结论
    
    作为目前最流行的前端框架，react将交互性做到了最好，而这本书做入门指南也是操作与理论相结合，他指导你一步步将代码写出来，并在JS的基础上将react的概念解释清楚，并囊括react周边生态，他有大量的代码，详细的解释，阅读完本书你完全可以写一个react app.


<a id="orga90ad22"></a>

## Land of Lisp<sup><a id="fnr.17" class="footref" href="#fn.17" role="doc-backlink">17</a></sup>

Lisp之地

> “天哪，Lisp 听起来确实与人们谈论的其他语言不同。 也许我应该找个时间拿起一本 Lisp 书。”
> 
> &#x2013;摘要

-   我的结论
    
    这本书语言有趣，用生动的动画讲述lisp这个第二古老的语言，最古老的是Fortran，他到现在还在被使用，而目前有很多语言都借鉴了他，包括现在流行的JS，他如此强大，以至于有人说作者发现了这门语言而不是发明他，他语法简洁，以至于当你学习他之后就能取代你熟练的语言成为你的母语。


<a id="org789be65"></a>

## 曾国潘家书<sup><a id="fnr.18" class="footref" href="#fn.18" role="doc-backlink">18</a></sup>

> 夫家和则福自生，若一家之中兄有言，弟无不从，弟有请，兄无不应，和气蒸帮而家不兴者，未之有也。反是而不败者，亦未之有也。伏望大人察男之志！即此敬禀叔父之人，恕不另具。六弟将来必为叔父克家之子，即为吾族光大门弟，可喜也！谨述一二，余续禀。
> 
> &#x2013;摘要

-   我的结论
    
    曾国潘是传统中国儒家学者，他身体立行着儒学的礼义孝廉等，做到了兄恭弟及父慈子孝，修身齐家治国平天下，立功立德立言。立功是在朝为官，誉为“同治中兴”第一功臣; 立言是留下了一部《曾文正公全集》而流传下来的是这本《曾国潘家书》; 至于立德，曾国潘在朝时毁誉参半，有镇压太平天国的大功，也有”天津教案”中的杀人割地，至少在当时的历史中是毁德了。而这本书对了解一个中国传统儒家学者有很大的帮助，他记录了这么一个学者的言传身教和一言一行，如何处理国家危机，以至于对于了解中国传统文化都有很大的帮助，因为他离你不远，他就是传统的中国人，他受到的都是传统的教育。


<a id="org3e5ca4c"></a>

## Designing Data-Intensive Applications<sup><a id="fnr.19" class="footref" href="#fn.19" role="doc-backlink">19</a></sup>

数据密集型应用系统设计

> 技术是我们社会的强大力量。 数据、软件和通信可用于坏事：巩固不公平的权力结构、破坏人权和保护既得利益。 但它们也可以用于好的方面：让未被充分代表的人们的声音被听到，为每个人创造机会，并避免灾难。 本书献给所有为善而努力的人。
> 
> &#x2013;摘要

> 计算是流行文化。 [&#x2026;] 流行文化蔑视历史。 流行文化是关于身份和感觉就像你在参与。 它与合作无关，与过去或未来无关——它活在当下。 我认为大多数为金钱编写代码的人也是如此。 他们不知道[他们的文化来自哪里]。
> 
> &#x2013;艾伦·凯

-   我的结论
    
    如果要说现今最伟大的是什么，我想说应该是技术了，你无需多强大，只要你能熟练掌握，你也能改变世界。


<a id="org6433bf0"></a>

## 史记<sup><a id="fnr.20" class="footref" href="#fn.20" role="doc-backlink">20</a></sup>

> 人固有一死，或重于泰山，或轻于鸿毛，用之所趋异也。
> 
> &#x2013;司马迁

-   我的结论
    
    我们为什么要读历史？因为时代虽然不一样，但历史总是重复的，但是历史本身又记录什么？举《史记》这个例子：司马迁说唯倜傥非常之人称焉，就是说历史记录的不是普通人，而是非常之人，例如我们耳熟能详的项羽本纪，项羽这个人中国五千年历史上几乎没出现过类似的，他的得失与其性格值得为之记录。而普通人就没什么好记的了，因为太多没什么好记的了;但是历史人物他们本身也是人，只是他们做到了人本身的极限并可以为之记录的人，既然如此我们看到了历史人物的故事那就可以以此伸展开并更容易猜出普通人的故事了。不仅是史书，现在关于记录的媒体就更多了，例如我看了辛普森一家关于婚姻的故事，故事很有想象力很幽默搞笑，其中讲到辛普森年轻时的老婆回来与现在老婆抢丈夫，这样辛普森就面临选择了，年轻的一个说我可以给你更加刺激与完美的服务，现一个说我知道你所有的优点与缺点并愿意接纳你，最后辛普森和现老婆抱在了一起，你如果没结婚当然不懂婚姻后的生活，但你可以借鉴这个至少以后和小三抢男人时知道了一个技巧。回到史记这部书，有十二本纪写的是十二个算是当时能操纵 国家命运的人，而里面唯一一个写女人是吕后本纪，所以你也可以以此为借鉴了解天下所有女人， 吕后是介绍给刘邦的，刘邦死后吕后掌权第一件事是杀戚夫人为人彘及各个威胁政权的人，然后分封各姓吕的人，你想是不是每个女人都会这么做，只是她们没办法达到那个位置，无法释放那欲望而已，当然肯定有不一样的女人，只是吕后作为一个极端例子，反应的也是绝大多数的女人，因为你没办法阅尽所有女人，所以典型的抓出来就了解了，这就是读书特别是史书的功用。回到现在本身，我们工作生活作为一个普通人，难道不是一直在重复历史吗？


# 写在后面

<table id="orgc1ea5f8" border="2" cellspacing="0" cellpadding="6" rules="groups" frame="hsides">


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
<td class="org-left">如果喜欢该文章欢迎Star我的<a href="https://github.com/tiglapiles/article">github</a></td>
</tr>


<tr>
<td class="org-right">9</td>
<td class="org-left">捐助我的<a href="https://itch.io/profile/tiglapiles">游戏</a>，支持我的创作</td>
</tr>


<tr>
<td class="org-right">10</td>
<td class="org-left"><a href="https://v2ex.com/member/mascteen/topics">我的社区更新地址</a></td>
</tr>


<tr>
<td class="org-right">11</td>
<td class="org-left">email: <a href="mailto:tiglapiles@gmail.com">tiglapiles@gmail.com</a></td>
</tr>


<tr>
<td class="org-right">12</td>
<td class="org-left"><a href="../../">Home Page</a></td>
</tr>
</tbody>
</table>


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
