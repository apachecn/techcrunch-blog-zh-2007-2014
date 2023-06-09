# 我们能从丹尼斯·里奇身上学到什么？

> 原文：<https://web.archive.org/web/https://techcrunch.com/2011/10/15/what-can-we-learn-from-dennis-ritchie/>

正如我们本周早些时候提到的，UNIX 的创始人之一和 C 语言的创造者丹尼斯·里奇于上周末去世。虽然我觉得计算机科学和相关领域的许多人都知道 Ritchie 对与计算有关的一切事物的成长和发展的重要性，但我认为回顾他的成就并把他放在已经由 Lovelace，Turing 和(尽管这种欢呼会有争议，至少在历史有发言权之前)最近去世的 Steve Jobs 占据的 CS 万神殿中是有价值的。

UNIX 是最早的多用户操作系统之一，允许科学家和研究人员在传统的批处理机器上共享计算机时间。研究人员对多用户和多任务的概念非常感兴趣，因为编写、运行和接收批处理程序的输出需要时间。批处理模式下的计算机时间是昂贵的，正如这个轶事所说明的:

> 1969 年，在思考操作系统的问题时，肯·汤普森(Unix 的共同创造者)在业余时间开发了一款名为“太空旅行”的电脑游戏。这个游戏模拟了太阳系中行星的运动。玩家可以在行星之间巡游，欣赏风景，甚至可以将飞船降落在行星和卫星上。
> 
> 这个游戏首先用 Multics 编写，然后音译成 Fortran，用于 GECOS 操作系统，在阿格 635 计算机上运行。游戏的显示不稳定，难以控制，因为玩家必须键入命令来控制船只。此外，它在大型 GE 635 上花费了大约 75 美元的 CPU 时间，这一成本很难让管理层喜欢它。

一个游戏 75 美元，特别是在 20 世纪 60 年代，对于一个黑客来说很难找到任何乐趣。Dennis Ritchie 和 Thompson 一起把 UNIX 建成了黑客的天堂，一个测试小程序和分享成果的地方。他是一名物理学家和数学家，但在正确的时间进入了大型机和微计算的新生世界。20 世纪 60 年代和 70 年代是计算机与世界互动方式发生巨大变化的时期。尽管普遍的观点是“这些该死的电脑会搞乱我的电话账单”，但实际上电脑正在搞乱现状。在短短的几年里，纸质记录慢慢地被计算侵蚀，电话交换机从疯狂的蒸汽朋克章鱼变成了路由器和终端的准机械系统。贝尔实验室处于这一切的最前沿，其任务是通过铜线连接世界。最重要的是，他正在做的事情是*困难的*，在拖放、自动完成 ide 的时代，我们忘记了这一点。

UNIX 的关键是共享的概念。该操作系统始于 1969 年，是对贝尔实验室关闭汤普森和里奇最喜欢的操作系统 Multics 的反应。在包括麻省理工学院在内的多个组织的合作下，新泽西州贝尔实验室的四名程序员开始在一台被忽视的 PDP-7 机器上工作，他们在那里移植了太空旅行游戏，并开始构建一个文件系统以保存游戏。慢慢地，一个熟悉现代 Linux 的人都会理解的命令结构围绕着这个文件系统发展起来。UNIX 的词汇慢慢地从最初用户的小圈子里流传出来，1971 年，贝尔实验室专利申请办公室开始用它来格式化文件，以便用 nroff T1 打印。

同样值得注意的是，Linus Torvalds 出生于 1969 年，这使他成为收获 UNIX 时代好处的主要候选人。在一个新行业的混乱中成长是很重要的，盖茨、托沃兹和里奇都是这方面的优秀例子。

Ritchie 继续创造了许多其他的改进，并且在 C 操作系统的开发中，给了世界第一个多机器、交叉兼容的编码标准，任何人，从头发斑白的机器语言老手到赫尔辛基的年轻学生，都可以使用和理解。UNIX 源代码像圣经一样从一个程序员传到另一个程序员，即使在[拒绝向教育机构提供之后。它是用 C 语言编写的，它的一些核心组件是用机器语言编写的，以便节省时间和周期，最重要的是，保留 Ritchie 和 Thompson 通过思想的交叉授粉灌输的优雅。没有人，甚至是里奇，理解 UNIX 这个庞然大物的复杂性，而这是有意为之的。我们的目标是前面简单，后面复杂，这是计算领域的每个人都应该效仿的模式。](https://web.archive.org/web/20230330130905/http://en.wikipedia.org/wiki/Lions'_Commentary_on_UNIX_6th_Edition,_with_Source_Code)

同样重要的是渴望达到一个清晰和优雅的黄金理想。UNIX 团队的成员道格·麦克洛伊写道:“同行的压力和对工艺的简单骄傲导致大量代码被重写或丢弃，因为出现了更好或更基本的想法。”。“专业竞争和地盘保护实际上是未知的:如此多的好事正在发生，以至于没有人需要对创新拥有所有权”。

问题是，那么我们能从这个计算巨人那里学到什么来构建我们自己的产品呢？**首先，里奇和汤普森想要找乐子。**他们最初并不急于赚钱，事实上，他们的目标是省钱，或者至少通过将游戏转移到更便宜的机器上来隐藏游戏。

第二是在你的舒适区之外工作的必要性。里奇是一名物理学家和数学家。然而，他成了一名程序员。正如比雅尼·斯特劳斯特鲁普[提到的](https://web.archive.org/web/20230330130905/http://www.economist.com/node/2724348)，尽管很明显他的背景在构建 UNIX 和 C 语言方面帮了他很大的忙，但里奇并不害怕尝试在新的和不熟悉的领域工作。“如果丹尼斯决定花十年时间研究深奥的数学，Unix 就会胎死腹中，”他写道。

第三，不干涉创新的重要性。Ritchie 是幸运的，因为 Bell Labs 有资金和人员允许他和他的朋友们躲在暗处，按照他们自己的时间线创造他们想要的东西。谷歌似乎已经捕捉到了同样的内部实验意识，很明显，他们的 20%项目以及他们的实验室产品慢慢变成了主流工具。谷歌创始人在公司成立后几乎立即允许这 20%的项目，这证明了汤普森和里奇的方法论。当工头看着的时候，人们制造低劣的工具，而当让他们自己设计的时候，人们制造出杰作。

**最后，我们知道分享的重要性。看到一家小型初创企业用保密协议和秘密来掩饰他们的产品，或者看到企业家们把热情的握手误认为是人际交往，这让我觉得非常有趣。当这种情况发生时，很明显他们的想法并不新颖，也不会特别成功，他们的态度也不特别有利于成长。我认为，许多目前成功的企业家并不是因为他们谈论一个好游戏而成功，而是因为他们玩一个好游戏。**

可以说，当今世界上最重要的软件项目——Linux——之所以重要，是因为它非常容易获得并且是开放的。有些人会吹嘘开放并不是有利可图的同义词，但这些人充其量是悲观主义者，最糟糕的是傻瓜。

最后，丹尼斯·里奇告诉我们，计算机不是一个秘密社团，一个需要多年服务和特殊咒语才能加入的社团。他在知识上的慷慨表现在我们在网上做的每一件事上，他作为一个解释者——尽管是出了名的害羞——在他大量的评论和网上笔记中闪耀。尽管我们中没有人能达到他和 Bell/AT T 团队所达到的成就，尤其是考虑到他们所处的环境和信息时代的相对开端，我们被提醒这并不重要。毕竟，正如我们多年前从 UNIX 源代码中了解到的:

> *我们不期望您理解这一点。

你只需要在它的基础上发展。

[Img via Wikipedia](https://web.archive.org/web/20230330130905/http://en.wikipedia.org/wiki/File:Dennis_MacAlistair_Ritchie_.jpg)