

# 函数编程在JavaScript中的简单应用


# Table of Contents

1.  [函数编程在JavaScript中的简单应用](#orge7839bf)
    1.  [什么是函数编程](#org3807543)
    2.  [JavaScript简单介绍](#orgaf64b29)
    3.  [函数编程的基础单位](#orgcd87b9c)
    4.  [函数编程简单介使用](#org457d3c6)
    5.  [数据结构](#org04bb026)
    6.  [设计模式](#org3be3601)
    7.  [数据流](#orgabe002e)
    8.  [应用](#org7b23975)
2.  [写在后面](#org80f4333)


<a id="org3807543"></a>

## 什么是函数编程

函数式编程是一种编程范例，其中通过应用和组合函数来构造程序。 它是一个声明式编程范例，其中函数定义是每个返回一个值的表达式树，而不是一系列更改程序状态的命令性语句。<sup><a id="fnr.1" class="footref" href="#fn.1" role="doc-backlink">1</a></sup>

编程范例的其他示例包括面向对象的编程（其中数据和行为位于同一位置）和过程式编程，这是一种命令式样式分组算法，将其归为倾向于依赖于共享可变状态的过程。

与强制性或面向对象的代码相比，功能性代码往往更简洁，更可预测且更易于测试-但是，如果您不熟悉它以及与之相关的通用模式，功能性代码也可能看起来更加密集，并且相关文献可能对新来者不友好。

要理解函数编程要弄懂这几个概念：

-   纯函数
    -   给一个输入值会获得一个固定的输出值（相同的输入值总是会获得相同的输出值）。
    -   没有其他任何的副作用
-   函数组合
    各种小函数通过组合获得更大的函数处理更复杂的问题，
-   辟免状态共亨
    这个状态可以是一个全局变量，或是一个作用区域，而函数编程尽量辟免使用这种全局变量等。
-   辟免状态修改
    就是一串数据通过函数后原先的值不能被修改，这是函数编程的核心，输入和输出的对应的，输入不变输入也不会变。
-   辟免副作用
    所谓副作用是你运行了一个函数却改变了一个全局变量的值，或者副加的运行一个外部程序，这些在函数编程中都是不允许。
-   声明式与命令式
    -   声明式：怎么做，我们的代码描述几个具体的步聚来达成某个目地。
    -   命令式：做什么，我们代码描述数据流


<a id="orgaf64b29"></a>

## JavaScript简单介绍

JavaScript（JS）是函数为第一类级的轻量级，解释性，即时编译的编程语言。<sup><a id="fnr.2" class="footref" href="#fn.2" role="doc-backlink">2</a></sup>

学习一门语言从三个方面入手：

-   主要的数据类型;
    JS的数据类型主要就：数值，字符，boolean, symbol, 对象; 对象里面又包含：函数，数组，时间，正则等。
-   组合方式;
    常规的加减乘除，逻辑关系，还有各种的运算符各种的组合方式等;
-   抽象化;
    把一个具体的问题通过代码层面展示出来，用一个类去代表一个具体的事物，然后类里面的事物的各种属性等;
    
    例如我们去声明一个变量：
    
        const x = 3
        const y = 4
    
    例如我们去声明一个函数：
    
        function add (x,y) {
          return x+y
        }
    
    然后运行该函数：
    
        add (x,y) //=> 7


<a id="orgcd87b9c"></a>

## 函数编程的基础单位


<a id="org457d3c6"></a>

## 函数编程简单介使用

javascript中可以这样声明一个函数：

    const double => (x) => x*2
    double (1) //=> 2
    
    // currying: 连续的函数
    const add = (x) => (y) => x+y
    add (1) (2) //=> 3
    
    // 函数组合
    add (double (1)) (double (2)) //=> 6
    
    // 数组循环
    const arr = [1,2,3,4]
    arr.map (double) //=> [2,4,6,8]
    // 连续循环
    const arr = [1,2,3,4]
    arr.map (double).map (double) //=> [4,8,12]
    
    // 高阶函数
    // 所谓的高阶函数是指一个函数，他要传入一个函数作为参数，或者值是返回另一个函数;
    const int = (x) => x+1
    const add2 = (fn) => fn(2)
    add2(int) //=> 3


<a id="org04bb026"></a>

## 数据结构


<a id="org3be3601"></a>

## 设计模式


<a id="orgabe002e"></a>

## 数据流


<a id="org7b23975"></a>

## 应用


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


<tr>
<td class="org-right">14</td>
<td class="org-left"><a href="../build_it/no_pain_no_gain.zh.html">天道是否有报－从三个层次解读『求仁得仁又何怨乎』</a></td>
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

<sup><a id="fn.1" href="#fnr.1">1</a></sup> <https://en.wikipedia.org/wiki/Functional_programming>

<sup><a id="fn.2" href="#fnr.2">2</a></sup> <https://developer.mozilla.org/en-US/docs/Web/JavaScript>
