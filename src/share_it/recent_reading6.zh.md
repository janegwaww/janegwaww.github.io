

# 分享最近阅读的书籍清单（六）

这些都是在人生中的好书藉或好内容，我想把这些优秀的东西分享出来，并赋上自己的一些主观想法，能让更多人知道并从中受益。这里只是做一个引荐，精彩需要你自己亲自拜读从中感受。


# Table of Contents

1.  [分享最近阅读的书籍清单（六）](#org797c292)
    1.  [Building Browser Extensions](#org648b415)
    2.  [The Art of Functional Programming](#org4eaf263)
    3.  [Interactive Data Visualization for the Web](#org1b0276e)
    4.  [Learn You a Haskell for Great Good!](#org00b61cc)
    5.  [呂世浩講史記](#org9393e8e)
    6.  [吕世浩讲秦始皇](#org37c0b86)
    7.  [Poor Economics: A Radical Rethinking of the Way to Fight Global Poverty](#org260b84c)
    8.  [YaleCourses: Philosophy of Death ](#orgb665598)
    9.  [The Lambda Calculus: Its Syntax and Semantics](#orge98aad7)
2.  [相关阅读](#org11dd536)
3.  [写在后面](#orgfd7ebc3)

> 人二三十年讀圣人书，一旦遇事，便与巷人无异，&#x2026;&#x2026;，只缘讀书不作有用看故也。&#x2026;&#x2026;何取？觀史如身在其中，見事之利害，時之禍患，必掩卷自思，使我遇此等事，當作何處之。如此觀史，学問亦可以進，智識亦可以高，方为有益。
> 
> &#x2013;宋·吕祖谦


<a id="org648b415"></a>

## Building Browser Extensions<sup><a id="fnr.1" class="footref" href="#fn.1" role="doc-backlink">1</a></sup>

*Create Modern Extensions for Chrome, Safari, Firefox,and Edge*

<div class="org-center">
<p>
游览器插件开发&#x2013;开发可用于Chrome, Safari, Firefox和Edge的现代插件
</p>
</div>

> 探索强大的工具和功能来自定义Firefox并打造属于您自己的浏览器。
> 
> &#x2013;addons.mozilla.org

**我的结论**

一本普通的技术书籍，说它普通是因为里面介绍了并不是什么新颖的技术，都是前端相关的技术，更多的加上游览器权限对开发的限制。说它技术是因为它确实填补了一个空白，填补了游览器扩展开发的一个市场空白。游览器扩展开发即是你在游览器这个平台上，对游览器的功能进行扩展的开发。因为是在游览器这个平台上开发，所以很多方面都受到的限制，例如也有跨域的限制，也有权限的限制等。它都是使用前端的技术开发，js写逻辑，css负责渲染，html写页面，还有js的各种框架也可以使用。因为是基于平台的小体量开发，所以它也成为了很多人的个人创业选项，基于平台做小体量开发保证了一定的用户量，开发成本也非常低，而你只需要一个非常好的创意。这里推荐一下我个人的chrome扩展软件FleetMarks，一个管理游览器书签的神器：[Chrome WebStore](https://chrome.google.com/webstore/detail/fleetmarks/fjbndejcdmoakifmbilbjnnooiamophd?hl=en)和[Github](https://github.com/janegwaww/fleetmarks-official/releases)。


<a id="org4eaf263"></a>

## The Art of Functional Programming<sup><a id="fnr.2" class="footref" href="#fn.2" role="doc-backlink">2</a></sup>

*with examples in OCaml, Haskell, and Java*

<div class="org-center">
<p>
函数式编程的艺术&#x2013;用OCaml, Haskell, Java作范例
</p>
</div>

> 函数式编程擅长抽象和组合。
> 
> &#x2013;摘要

**我的结论**

这本书可以做为函数式编程的入门书。函数式编程是一个编程思想，他使得数学应用于编程更加的容易，产生了像[范畴论](recent_reading3.zh.md)这样的数学理论应用于编程，而数学还有更多像这样的数之不尽的理论还没有被挖掘。函数式编程中输入与输出永远是一一对应的，你输入什么值就会输出什么值，没有任何的副作用。而使用这本书，你可以慢慢建立起对函数式编程的思维，在编程过程中原来值绝对不能改变，你只能复制返回新值，不同于其他的编程泛式通过赋值和副作用获取功能。当然函数式编程也有副作用，例如都会有IO，只是这些都被放在了项目的最外层。


<a id="org1b0276e"></a>

## Interactive Data Visualization for the Web<sup><a id="fnr.3" class="footref" href="#fn.3" role="doc-backlink">3</a></sup>

<div class="org-center">
<p>
前端交互数据可视化
</p>
</div>

> 我们这个信息时代让人觉得信息过载。过多的信息让人难以承受；只有当我们能对这些信息进行洞察时，原始数据才对我们有用。
> 
> &#x2013;摘要

**我的结论**

数据可视化的好处是让普通人也能看懂数据的走向，而不用看那死死的数字了。而前端作为天然与用户行为交互的载体，数据可视化是一个大大能提升用户体验的事，为此而生的框架[D3JS](https://d3js.org/)就非常好的做到的了这一点，他让大量的数据可视化成为可能。虽然现在市面上存在很多前端3D可视化框架，但在数据可视化这一块d3应该是做的最好的了。如果你有大量的可视化数据的需求，那d3与现代游览器交互的功能，强大的可视化组件和数据驱动的操作DOM是你的不二之选。基于这样的选择，这本书是初学者学习这个工具的不二之选，但对于中级或高级开发者里面的内容并不值得你花这个钱。你最好有些JS的基础知识，这样学起来比较轻松点。因为里面的操作涉及到大量的数据，所以对于D3开发你最好也是有一定的函数编程的思维，这样开发起来也比较有趣一点。


<a id="org00b61cc"></a>

## Learn You a Haskell for Great Good!<sup><a id="fnr.4" class="footref" href="#fn.4" role="doc-backlink">4</a></sup>

<div class="org-center">
<p>
Haskell编程
</p>
</div>

> 音乐是个神秘的数学，有无限的元素参与其中。
> 
> &#x2013;Claude Debussy

**我的结论**

自从我在JavaScript中用上函数编程之后，就无法自拔凡是遇到问题都喜欢用函数解决，反正没有一个问题是函数不能解决的，大点的问题就把它拆分成小问题，再用组合把它们组合在一起解决这个大问题，更复杂点的上[Monads](https://en.wikipedia.org/wiki/Monad_(functional_programming))。这样的代码看起来简洁又有效，而且BUG还少，我听说90%的BUG都是因为赋值引发的，没有赋值减少90%的BUG，再加上强大的类型系统保证你代码输入输出的正确，让BUG无处躲藏。既然函数式编程代码如此优雅, 如此让人有安全感，那我为什么不直接使用专门为此而生的语言Haskell呢。如果你为数不尽的类，超类，继承等各种相关联的概念和随便写一个方法都要一个class所折磨，那来试试这清爽的函数式编程吧。毕竟编程的尽头就是数学，如果你对此感兴趣可以配合这个入门教程视频[Functional Programming Fundamentals](https://www.youtube.com/watch?v=4Z6BlLqAqt8&t=656s)更佳。


<a id="org9393e8e"></a>

## 呂世浩講史記<sup><a id="fnr.5" class="footref" href="#fn.5" role="doc-backlink">5</a></sup>

> 我欲载之空言，不如见之于行事之深切著明也。
> 
> &#x2013;论语

**我的结论**

如果你不喜欢历史，那推荐你看看吕世浩老师的历史公开课。讲述如何正确的学习历史，陪养正确的历史观，会让你从此爱上历史。学习历史能让你知道学习的目地是什么？自己活在一个什么样的时代？稽其兴、坏、成、败之理，能形成自己的思辨，审时度势，看懂人性和良知。可以说现在的应试教育就是在泯灭人性，如果你也是其中的受害者，那可以听听这位老师的史记课，可以说让人醍醐灌顶。历史可以启发智慧，在历史中把自己带入当事人的位置，如果是你你会怎么做与当事人怎么做做个对比则磨炼了自己的智慧。讲一个有趣的故事：圯上纳履。有一天张良从容步游下邳圯上，有一个老人，穿着褐色的衣服，走到张良跟前，把他自己的鞋子脱下来从桥上丢下去，然后故意对良说：小子，下去帮我取下鞋子。张良很惊讶，想打他。但因为看他是老人,强忍住，乖乖下去取鞋。老人又说：替我穿上。张良想着取都取了就替他穿上吧，于是张良长跪下来替老上穿上了鞋子。老人穿上鞋后大笑而去。张良深感振憾，目光久久无法离去。老人走了许久又返回来，对张良说：孺子可教也，五天后早上，在这里见我。张良很奇怪，但还是乖乖答应了。五天后早上张良来到桥上，但是老人早已经到了，并愤怒的说：与老人约会怎么可以迟到，然后离开了并说：过五天后再来。到第五天张良在鸡鸣后就动身前往，可老人又是早早到了，又生气了并说：怎么又迟到了，离开并说：过五天再来。五天后张良还在半夜就前往了，过了一会儿老人也来了，看见张良高兴的说：就应该这样。然后给了张良一本书，并说：读此书可为帝王师，今后十年你将建功立业，十三年后你可以在济北见到我，谷城山下的黄石就是我了。然后离去不再看见。天亮时看到这书乃是《太公兵法》。张良因为好奇经常学习背诵。

这是史记记载的汉初三杰张良年轻时的故事。史记花了如此多的笔墨不可能只是告诉我们要尊敬老人和约会不能迟到。注意开头提到的从容步游，这就要讲讲故事背景了，张良刚刚做了一件惊天动地的大事：在博浪沙刺杀秦始皇，正在被全国通缉，可是他还能从容步游，换成其他人早就是恍恍不安度日了。此时张良步游应该也是在想下一步应该怎么办，好这一刻如果是你你会怎么办？而张良迎来了命运的转折点，遇到一个老人。衣褐强调了这是一个穷人家，如果此刻碰上的是你你会怎么做？肯定是避开这个陌生人远远走开吧，正常人都会这么做的，但是老人家显然也是有备而来的，他想试探张良，所以张良刚开始的反应也是想打这个老人，但是张良忍住了，用理智控制了感情，强忍。但是老人非但没有谢谢还且还得寸进尺的说：替我穿上。这一刻是你你又会怎么做？正常人应该都是我他妈都把鞋给你取回来了还要我替你穿上，早就骂你一通然后甩手离开了，但是张良没有，他不但是替他穿上，而且是长跪的替他穿上，也由此可见张良的忍耐力了。而老人的反应是大笑而去，也由此可见老人的从容不迫。老人离开后又折返回来了，此时老人怎么知道张良还在原地，因为经过刚才的交峰双方都明白了对方是什么人物，所以张良在原地等着他回来，因为老人做了这么多肯定是有事交待不可能让你穿穿鞋这么简单，所以老人说了句孺子可教也，这就是老人对张良悟性的肯定，老人是道家代表，不像儒家道家教人讲求悟性。并说了五日后早上见，张良乖乖答应，可见张良也看出了老人的不简单了。后面我们也看到了，老人总是比张良先一步到，这里我们就要怀疑了，老人到底是要干什么？老人其实是在和张良争先，争谁先到桥上，也是老人在教张良先发制人后发则受制于人。这也是老人用行动教育张良兵法的忍与先。忍就是兵法中的让敌人以为你没有威胁，先就是兵法中的占住先机出奇制胜。这又回到了张良刺杀失败后思考下一步怎么办了，张良知道下一步怎么做了吗？很显然，老人就是在点拔张良为什么会刺杀失败，而老人就是教育他为他后来的成功奠定基础。


<a id="org37c0b86"></a>

## 吕世浩讲秦始皇<sup><a id="fnr.6" class="footref" href="#fn.6" role="doc-backlink">6</a></sup>

> 莫之为而为，莫之致而至。
> 
> &#x2013;孟子

**我的结论**

吕世浩老师对我的影响很深，有幸在自己迷忙的时候他刚好开设了读史记的课程。我对历史也非常感兴趣，无耐中学的历史课程都是各种洗脑，让人无法产生任何兴趣。而见识到他开设的课程之后，让我重新认识了历史，认识了中华文化，虽然只是短短的几个小时，但是其中产生的振憾对我的人生有很大的影响，好的内容在精不在多，通过他我确认了自己的人生观与价值观，虽然已经7,8年过去了，没有后续的消息，但是这几个小时也能让人受用终生了。也希望再次见到他的课程时，自己对自己对人生已经有了更深的理解，能轻松读懂他的课程，读懂史记字里行间更深层次的意思。虽然不知道以后是否有机会亲身体验他的课程，但是高山仰止景行行止，吾心常向往之。


<a id="org260b84c"></a>

## Poor Economics: A Radical Rethinking of the Way to Fight Global Poverty<sup><a id="fnr.7" class="footref" href="#fn.7" role="doc-backlink">7</a></sup>

<div class="org-center">
<p>
贫穷的本质-<i>如何逃离贫穷陷阱</i>
</p>
</div>

> 求仁得仁，又何怨乎？
> 
> &#x2013;史记·伯夷列传

**我的结论**

贫穷的本质来自两个方面：一个是错误的信念，另一个是不充分的信息。建议缺少阅历的年轻人多看看这些书，因为对你们帮助很大。虽然此书采取抽样，分组对照实验，前期说了很多的实验过程，和一些数据等比较估燥，但他也确实揭露了一些事实。例如他说的穷人总是抱着错误的信念，在中国就有读书改变命运，努力一定成功，大力出奇迹等;和穷人得不到足够的信息，这个在中国都和公权力相关，因为在中国舆论是受到管控的，要不然不给你真相，要不然只是给你部份真相，你永远也无法获得充分的真相。在不充分的信息方面他讲了这么一个故事：在印度的某个地方农民歉收，这个时候怎么办呢？其实这些农民想的和金融家一样，分散投资，分散风险;想着多打几份工，分散农业减产的风险。可是这个时候如果传来消息说某个城镇好找工作，农民们就会蜂拥而致，背景离乡跑去打工，但是实际上并没有那么多的工作机会，农民多了反而造成工资下跌，城镇负担也加重了。然而实际上农田减产可以通过增加肥料和杀虫弥补的，比他们去打工效益要高的多，但是农民们没有得到充分的信息，或者是受到了某些误导做出了错误的判断，也就错失了正确解决问题的机会。对冲基金经理处理问题的方式与这些农民无异，区别只是这些经理得到的信息更充分，所以做出错误的判断的机率也小。在生活中穷人无时无刻不是处在风险中，一股脑跑去城市打工又没打着工的农民错失了两个机会：在城市没打着工，又失去在农田解决问题的机会。到头来陷入困境只好去借高利贷，又被利息拖的喘不上气，穷人就是这样一步步陷入贫穷的陷阱的。而当你追究所谓城市好找工作的消息来源时，可能只是某些人的调侃，但是当这些假消息来自大众媒体，来自官方的某种所谓『正能量』时呢？那这个账又该怎么算？穷人是非常容易受误导的群体，因为他们都急于采取行动来摆脱困境，所以他们很难有耐心去做周全的考虑，下个月就要揭不开锅了，下个月就还不上房货了，你让他们保持耐心就是站着说话不腰庝了，这个时候哪来的耐心。所以这些人对所谓的『权威』信息非常的依赖，很少对消息真实性质疑，而年轻人是更加容易受到伤害的的群体，因为他们储蓄少，抗风险能力低，上一点岁数的还能靠存款撑个一两年，而年轻人都是月光族，这个月没工作，下个月就还不上房货了，而且他们还缺少生活阅历，所以那些所谓的收破烂月入过万的『正能量』就令人极端厌恶了，因为他们就是冲着年轻人这个最容易伤害的群体来的。也许你还要抬摃说真的有人靠收破烂月入过万了，可是这个月真的月入过万了那下个月呢下下个月呢，能每个月月入过万吗？况且又有几个拾荒者能做到单月月入过万的？而这就是夸大部份事实带来的恶果了。

持续的贫穷也往往来自错误的信念，比如穷人有多个子女，在各个国家都有一个观念认为：把教育的机会集中在一个看起来还不错的孩子身上，其他兄弟姐妹都少受教育，把资源集中到这一个孩子身上，让他多读书，然后再帮助兄弟姐妹们赡养父母，一般家庭是这么计划的，这样做对不对呢？其实还真的不对，在这件事上其实越平均越好，尽量让每个子女得到平均受教育的的机会，产生的效益其实是最大的，让子女多读两年书也比一个子女得到充分教育要强，因为每个人的潜质需要时间和机会才能表现出来，不是当下时间点某个孩子最聪明以后也最有出息的。可能某个笨笨的孩子，也许要到20岁才能把他的经商天赋表现出来，这个时候他只要有基本的读写能力和数学知识就能挣大钱了，可是如果这个时候连基本的读写能力都没有，那就是浪费一个经商的天才了。这就是错误的信念导致的结果。

而不充分的信息和错误的信念也高度关联，互为因果，在生活中无处不在，例如小时候父母们反覆向我们灌输说只有成绩好才能改变命运，小时候也坚定不移认真读书，但是出来工作后我也发现了，考试成绩在工作中没有任何鸟用，而我通过自己努力学习的能力帮助自己获得了不错的工作机会，又或者到了一定年龄后长者教育我们成家立业，养儿防老，可我最清楚养儿能不能防老了，因为我就是从孩子一步步长大的。又或者有一段时间到处都在宣传买房才能结婚，男女也都这样想的，可当真的买了房结了婚，就会发现生活质量并没有什么变化，只是多了个房货让你永远都翻不身。这个时候你再怀疑这些信念时也没有改变的机会了。而这种父母的所谓的善意的信念并不会让事情变好，你也无法指责他们。但是还有一些恶意的信念例如某某月入过万的等，他们的动机就是想让年轻人陷入自责，这个社会没有问题，有问题的只是你自己，你就别抱怨社会了来回避责任，这就更可恶了，也间接导致了天门山事件，最后RIP。


<a id="orgb665598"></a>

## YaleCourses: Philosophy of Death <sup><a id="fnr.8" class="footref" href="#fn.8" role="doc-backlink">8</a></sup>

<div class="org-center">
<p>
耶鲁大学公开课：死亡哲学
</p>
</div>

> 自杀是最愚蠢的决定，因为你连死亡都不怕了，还有什么是不能做成的呢？不怕死会成为你最历害的武器。
> 
> &#x2013;吕世浩

**我的结论**

死亡一直是中国一个很避讳的话题，从古代的王侯将相贩夫走足还是到现代的官商士绅市井民众，似乎都很难面对这样一个现实：死亡是一个自然规律，你能做的就是坦然的面对他。这个课程的教授他委委道来，用专业的知识向我们讲述死亡这个在中国鲜有人敢提及的现象，弥补了我们对这个自然宿命的知识的欠缺。本课程的主旨是我可以肯定我将会死去，但是我要怎么去看待这个事实呢？本课程将研究关于死亡的许多问题：

1.  如果死亡并不是一种终结，那从某种意义上来说我们是不朽的吗？永生不好吗？
2.  对死亡的过程将有一个更清晰认识，说一个人死了意味着什么？死亡是一个怎样的事实？
3.  最后，评估了对死亡的不同态度。死亡是邪恶的吗？怎么样算邪恶？为什么是邪恶的？自杀在道德上是允许的吗？合理吗？我认识到自己将会死亡的事实将如何影响我现在的生活？


<a id="orge98aad7"></a>

## The Lambda Calculus: Its Syntax and Semantics<sup><a id="fnr.9" class="footref" href="#fn.9" role="doc-backlink">9</a></sup>

<div class="org-center">
<p>
Lambda演算法：它的语法和语义
</p>
</div>

> 设身处地，揣摩通透，体贴入微，洞见表里。
> 
> &#x2013;读史16字决

**我的结论**

比较专业的一本书，你需要一阶逻辑，拓扑学，集合论，递归理论，范畴论相关知识。lambda演算法是以函数为第一规则的不限类型的理论。如何理解它呢？你只要清楚做所有事情都用函数就对了。当你有前面的前置知识之后，本书就是一艘带你邀游函数海洋的快艇，而你唯一需要遵守的规则就是函数，而如果你喜欢这样的简单与纯粹，那就去享受这样的快乐吧。函数式编程就是基于本书之理论。


# 相关阅读

-   [分享最近阅读的书籍清单(一)](recent_reading.md)
-   [分享最近阅读的书籍清单(二)](recent_reading2.zh.md)
-   [分享最近阅读的书藉清单(三)](recent_reading3.zh.md)
-   [分享最近阅读的书籍清单(四)](recent_reading4.zh.md)
-   [分享最近阅读的书籍清单(五)](recent_reading5.zh.md)


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


<tr>
<td class="org-right">11</td>
<td class="org-left"><a href="functional-programming.html">函数编程在JavaScript中的简单应用</a></td>
</tr>


<tr>
<td class="org-right">12</td>
<td class="org-left"><a href="../build_it/vanillajs-validation.html">用最简单的方式实现前端校验，也许你并不需要任何框架</a></td>
</tr>


<tr>
<td class="org-right">13</td>
<td class="org-left"><a href="recent_reading6.zh.html">分享最近阅读的书籍清单(六)</a></td>
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

<sup><a id="fn.1" href="#fnr.1">1</a></sup> <https://www.amazon.com/Building-Browser-Extensions-Create-Firefox/dp/148428724X>

<sup><a id="fn.2" href="#fnr.2">2</a></sup> <https://www.amazon.com/Functional-Programming-Minh-Quang-Tran/dp/3000735348>

<sup><a id="fn.3" href="#fnr.3">3</a></sup> <https://www.amazon.com/Interactive-Data-Visualization-Web-Introduction/dp/1491921285>

<sup><a id="fn.4" href="#fnr.4">4</a></sup> <http://learnyouahaskell.com/>

<sup><a id="fn.5" href="#fnr.5">5</a></sup> [呂世浩講史記](https://www.bilibili.com/video/BV1ii4y157Xo/?spm_id_from=333.788.recommend_more_video.0&vd_source=35ad3ca8835c204ff8357c31e80ea7e6)

<sup><a id="fn.6" href="#fnr.6">6</a></sup> [吕世浩讲秦始皇](https://www.bilibili.com/video/BV1C54y1C7dV/?spm_id_from=333.1007.top_right_bar_window_default_collection.content.click&vd_source=35ad3ca8835c204ff8357c31e80ea7e6)

<sup><a id="fn.7" href="#fnr.7">7</a></sup> <https://book.douban.com/subject/30161884/>

<sup><a id="fn.8" href="#fnr.8">8</a></sup> <https://www.youtube.com/watch?v=p2J7wSuFRl8&list=PLE0D425F951001F57>

<sup><a id="fn.9" href="#fnr.9">9</a></sup> <https://www.amazon.com/Calculus-Semantics-Studies-Foundations-Mathematics/dp/0444875085>
