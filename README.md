# -重学前端
深读winter老师的《重学前端》的笔记总结

**首先要明确，前端已经是研发体系中不可分割的一部分**

一下是自己在《重学前端》中的总结，以及反思。我是按照winter的章节来的，读完每一章文章之后，细细品味，好好反思。
1. [第一章--明确你的前端学习路线与方法](#01明确你的前端学习路线与方法)
2. [第二章--前端知识总体架构](#02前端知识架构图)








## 01明确你的前端学习路线与方法
##### 前端目前存在的一些列问题
* 基础知识
* 技术存在短板
* 前端技术发展太快
* 学习时间
* 学习能力

**winter**老师主要列出了三个问题，**基础知识、技术存在短板、前端技术发展**。

我自己添加了两点，学习时间和学习能力。目前前端发展确实很快，大家的关注点在于三大框架，而对于基础知识却关注度不高，之前面试的过程中遇到一个只问基础知识的面试官，问的我哑口无言，从那之后，开始深度学习前端基础知识，至少是js的基础知识。从目前的情况看还是需要继续巩固！特别是自己忽视的`CSS`内容。

前端发展确实太快，快的大家跟不上前端的步伐，所以我认为学习时间和学习能力尤其重要。至少是自己，平常下班有大把的时间学习，但是自己真正去学习的又有几天呢？接下来，立目标！让血热起来！

##### 学习路线和学习方法
* 摸索适合自己的学习方法
* 建立知识架构
* 追溯本源

建立自己的学习方法需要在学习过程中逐渐摸索的，但是大致的方向需要确定，那就是建立知识架构以及追溯本源。winter老师的这两点我完全赞同，回想自己之前的学习方法，一味地无头脑的学习，最后自己学到了什么？不知道~
**建立知识架构**尤其特别重要，winter老师用我们前端的js进行举例。
>我们思考一个问题，如果我们要给js知识做一个顶层目录，我们该怎么做？
> 如果我们把一些特别流行的术语和问题，拼凑起来，可能会变成这样
>* 类型转换
>* this指针
>* 闭包
>* 作用域链
>* 原型链
> 这其实不是我们想要的结果，因为这些知识点之间，没有任何逻辑关。也就是说他们是没有意义的。
> 如果让我来做，我会这样划分：
> * 文法
> * 语义
> * 运行时
这样子的话就在大的范围内来一层一层的链接起来。例如：文法分为词法和语义。运行时分为类型和执行过程。这样一层层划分，就会让自己的目录结构清晰完成。

**而对事物保持好奇心也很重要**。保持好奇心让自己有追溯本源的驱动力。winter老是用`opacity`和`display`两个`CSS`属性来距离说明。opacity是一个非常单纯的数值，但是`display`则不同，要想搞懂`display`需要关注`正常流`、关注`弹性布局`、关注`grid布局`等等。

***总之，接下来的学习过程中，要让自己学会学习，深度学习，并在此基础上逐步建立自己的知识架构，查漏补缺。让血热起来！！！***

## 02前端知识架构图
前端总体知识包括`JS`,`HTML`,`CSS`,`浏览器的实现原理和API`。
#### JavaScript
放上**winter**老师管局js的知识图

![image](https://static001.geekbang.org/resource/image/6a/9b/6aec0a09381a2f74014ec604ef99c19b.png)

>用一句话总结就是：**用一定的词法和语法，表达一定语义，从而操作运行时。**
运行时分为数据结构和算法部分，其中数据结构包含类型和实例。类型也就是js中存在的基本类型，实例是js的内置对象。算法部分是js的执行过程。

#### HTML和CSS
![image](https://static001.geekbang.org/resource/image/41/62/4153891927afac7f4c21ccf6a141f062.png)

winter老师把html分为元素和语言以及补充标准。
其中元素是html中重要的内容。`HTML`中标签分为很多种，例如`head`内的元信息类标签、`nav/footer`语义标签、`img/video`引入外部内容的标签、以及表单标签`input/button`这些。
**HTML标签分类：**
1. *文档元信息*：通常出现在head标签内部，包含了描述文档自身的一些信息；
2. *语义相关*：扩展了纯文本，表达文章结构，让标签更加语义化；
3. *链接*：提供文档内外链接；
4. *表单*：填写和提交表单操作；
5. *表格*：表头、表尾、单元格；

**`CSS`**从语言和功能划分，语言就是CSS的各种语法结构（例如标签选择器，单位等）。**功能分为布局、绘制和交互。**

感觉winter对这类的划分非常好，CSS部分不就是一个从布局到绘制再到交互的过程吗？！感谢winter老师！

#### 浏览器的实现原理和API
![image](https://static001.geekbang.org/resource/image/cb/cb/cbb6d198ccfb95af4906eeb0581333cb.png)

**浏览器的实现过程其实就是从解析-->构建DOM树-->计算CSS-->渲染、合成、绘制的一个流程。**

最后。附上winter老师的总结图以及课程表，感兴趣的同学可以去看看。最好能亲自用笔画一下，整理一下前端基础部分的一个框架。
![image](https://static001.geekbang.org/resource/image/d1/a8/d1cb4040d91207075e0591abffe1b9a8.jpg)

