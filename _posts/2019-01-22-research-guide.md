---
layout: post
title: "CV科研鸡汤"
subtitle: 'How to make it in Computer Vision'
date:       2019-01-22
author:     "Icep"
header-img: "img/post-bg-alitrip.jpg"
catalog: true
tags:
  - 科研
---

> 原文链接：https://mp.weixin.qq.com/s/sVga4llkPfYYdZFlf0wiMw

### 学习态度
- 心静下来才能钻进某个领域里认真做事。

### 方法论
明确研究各环节的方法
- 如何做基本调查
- 如何下手问题
- 如何分析问题
- 如何坚持自己的观点
- 如何给任务定优先级
- 如何将直观一点一点地转换为数学语言并且验证

### 思维过程
开始入门时期容易经常在自己的思维困局中转圈，在推公式，想直观，堆hack之间往返。

但是真正要进入的思维过程阶段是：发现理论与现实的黄金结合点，找到和现实吻合又干脆利落的假设，推出意料之外又情理之中的定理。

### 研究技巧
- 1. 喜欢自己的研究方向，内心的motivation很重要。
- 2. 做研究要每天花时间想，沉浸入要解决的问题。
- 3. 有思路(idea)就记下来，记录到自己的思维导图中。
- 4. 多看一下别人的工作，看完几篇本领域最重要的文章后认真总结，猜出大部分人的路数还有各种方法的优缺点，然后面对新文章的时候采用跳跃式读法，边看边猜，这样可以把握大局细节，自己想新思路也可以自然而然的攻击命门。
- 5. 选导师，他做什么研究并不重要，比这更重要的是人品及交流与表达能力。
- 6. 注意点：要从事自己从来没有尝试过的领域要非常小心，要不断考虑自己的思维模式是否适合，能否在有限时间内达到高度敏感性，在自己擅长的思维模式下，不断向前拓展，是最稳妥最实际最有效的方法。

### 写作技巧

中国人写作的最大瓶颈并不是英语能力而是组织能力。

不要把论文写成技术报告，先做什么后做什么，最后是什么，在公布一下实验结果。

论文是要引人深思的，给人启发的，要让人受教的，要让读者读完后，觉得这篇文章公正的评价了前人的工作，明白这篇文章的创新意义所在，并且同意作者的出发点，认为这是一个很有前途的方向。

**论文要挖深，想法要想透，才不会觉得写文章像挤牙膏。**

举个例子，写目标函数是什么，如何用梯度下降优化，数学上就两个公式，但是段落里可以说明如何选初始点，初始点在这个具体应用中的意义何在，如何取步长，为何这样选，收敛速度通常多快，哪里可以加速，哪里可以并行化再加GPU，等等，这样内容就丰富多了。又比如，一个算法的若干步骤，本来是毫无意义的流程图，但在介绍它之前做些解释，阐明设计的一些基本原则，然后在解释每步时充分使用这些原则，那读来就会觉得容易接受得多。 

克服了这两点，做到开局有理有据，正文言之有物，实验让人信服，那这篇文章基 本上可以中稿了。接下来，就可以进入高级模式了。 

**首先，立意要高远。** 一篇文章规矩着写，说“我们加了新特征，因为新特征针对数 据集的某些特性建模，实验效果更好”，虽然基本可被录用，但一般不会出彩；如果说“我们建立了新的框架，统一了以前的诸多方法，在这个框架下，算法能自动分析数据加入新特征，实验效果更好”，那这篇就有戏。

为什么呢？工业界看重效果 ，因为效果和经济利益直接挂钩；而学术界是想要为一个领域找一个简洁明了的理论，是要仰望星空，问天几何的——因此每一篇好文章，都必须建造出自己的一套世界出来，给出自己的世界观和方法论，在这个宏大的图景下，给前人的工作标好地位，给自己的工作定下基调，然后拿着这张画好的地图，去解决实际问题。

而所谓的博士研究和博士论文，则是在一套统一自洽的世界观下，含有两至三篇或者更多的文章，以证明这套世界观的合理性。 

这听起来像是忽悠的游戏。因为像计算机视觉这种实用的领域，哪有那么多理论可挖。是的，在一定程度上确实如此。但是建筑世界观本身，会促使研究者对已有的 工作进行排列，得到新的启发，看到新的联系，因此仍然是对研究本身有益的。有些表面上的联系可能被证明是偶然，但有些则会揭示本质，促进人们深化认识，为 将来的突破性进展作准备。另一方面，功利地来说，有一个宏大的世界观有利于一 位博士生发大量文章，早点毕业:-) 

**其次，故事要流畅。**我老板说过，一篇好的文章，就如同带着读者在一个花园里行走，路面平坦舒适，左边有山，右边有水，引人入胜，读者漫步欣赏美景，走过亭 台楼阁，一点不费劲，一下子就逛完所有还意犹未尽。迄今为止，我对这种抽象的诗一般的表达还不能完全理解，但是既然他声称读完了所有哈利波特的同人小说， 而我只不过写过一部二十五万字的小长篇，我想我还是宁愿相信他比较好-_-。 

在大的方面来说，一篇文章从开篇开始，就要让人有所期待，各种背景知识交代自然，详略得当，指出前人工作各有缺陷，然后自身的贡献娓娓道来，最后各种证据 证明自己所言得当；或是先摆出正反证据，引人思索，指出前人各种问题，再列出自己方案，教人拍案叫绝。细节上，全篇重要的论点要适当重复，每次出现都要和上下文语境相符，无聊冗长的段落适当精简，但必要的实验步骤需要交代；每一段都要有总起有概括，像是花园的指路牌，让读者不至于晕头转向；不设弯路，反复推敲逻辑关系，能用一层逻辑说清的绝不用两层，能用简单故事说明白的不用复杂公式，就算有复杂公式也放进附录里；繁简要有计划，细节要略写以免让人费解，主干则要用重笔让人印象深刻；插图要不言自明，要出现在该出现的地方，能恰当地作成段落注解；语句不能太长，避免从句套从句，长短结合比较好，等等。 

**这里所有的要求，都是为了读者着想。**每条单独做起来都相对容易，但要合在一起 就难，需要充分的思考和不停地修改。每过一段时间，脑中就会浮现出更好的组织 方式，而这种新的组织方式，又反过来会启发出新的理解，推进整个研究的进展。 接着，各部分贡献大小又有变化，详略又会调整，文章又得修改，如此往复。渐渐 地，才会从斧凿拼接模样的文章，变成一气呵成的神作。到这个时候，写作和研究 浑然一体，写作促进研究，研究促进写作，才终于算是步入专家级别了。 


### 上台演说技巧

第一次的会议ORAL演讲：一定要准备充分，倒背如流，就是怎么都不会忘，不管怎么紧张都是顺嘴，准备一两个月，把每个幻灯片都牢记。后面的演讲通过一次次这样的准备，渐渐自己也会有自我的发挥，所以脱稿很重要。流畅了，下一次就更不会紧张了，这是良性循环。

**最好的演讲是一个有唯一主题的流畅故事。**

演讲什么是重点呢？

很多人会下意识的认为花时间最多的细节就是重点，到准备演讲时就恋恋不舍，其实什么是重点要看具体目标是什么：如果是提高性能的系统性工作，小技巧就成为主线；若是新算法设计，那目标函数的精巧构造就是看点，若是研究数据的统计特征，那归一化至关重要；若是讨论大规模分布式的可行性，那梯度下降公式中参数间的相互依赖关系及相应的计算复杂度就成为关键。

**总之，如果细节不能为自己构建的宏大世界添砖加瓦，那就不能在演讲时打断提及。**

**先把幻灯片做好，写好演讲词，然后看看自己能不能在规定时间内脱稿讲出。**

**一定要脱稿，如果照稿朗读，那就没有敏锐的直觉，就不用说提高演讲水平了。**

最好不要自己的话写在幻灯片上，幻灯片上的内容是演讲者说完之后，最希望观众记得的内容， "take home message!"

好的幻灯片有几种类型：可以只含一张大图，或者互有联系的若干张图片，或一个前人工作的列表，或一件事物的优劣二分法，或一个算法的三个步骤，或一些事物的相互关系。

一句话，如果盯着它十秒钟没看出来重点是什么，那就打回去重做吧。

### 时间管理
制定计划会让人对任务难度有更清醒的认识，增强利用时间的动机。

制定的计划要适当 **宽松** ，宽松的计划其整体期望值就会降低，原来必须完成的事，现在就变成还可以再做一件事的情感奖励，会更加有意愿坚持下去。

制定的计划要 **简洁** ，计划寥寥几笔，勾勒出几小时，几天后或者几年后的方针图景即可。
