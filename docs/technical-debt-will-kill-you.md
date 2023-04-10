# 技术债务会害死你(如果你放任不管)

> 原文：<https://web.archive.org/web/https://techcrunch.com/2013/02/09/technical-debt-will-kill-you/>

乔恩·埃文斯是工程咨询公司 HappyFunCorp 的首席技术官；六部小说、一部漫画小说和一本游记的获奖作者；自 2010 年以来一直是 TechCrunch 的周末专栏作家。

More posts by this contributor

我一直在做的一个项目最近启动了。嗯，重新启动。一个叫做 [Postography](https://web.archive.org/web/20230107053325/http://www.postography.com/) 的精巧的小 iPhone 应用，它可以让你用你的 iPhone 发送带有信息和图片的明信片。俏皮，但听起来相当简单，对不对？一个不应该花太多时间构建的应用程序。

可惜，[我们](https://web.archive.org/web/20230107053325/http://www.happyfuncorp.com/)没有造出来；我们建造了它。第一个尝试的公司(这里没有指名道姓)在服务器端做得相当好……但是应用程序本身的初始版本糟糕透顶。哦，除了许多错误和频繁的崩溃之外，它最终有点工作。但除此之外，它的代码库是一个充满全局变量、意大利面条式代码、黑客、无操作和竞争条件的溃烂深渊，如果没有重大的重建手术，扩展或改变它几乎是不可能的。

这种情况比任何人愿意承认的都要多。在许多应用程序闪亮的用户界面背后，潜伏着洛夫克拉夫特式的架构噩梦，挑战着任何负责维护它们或添加功能的人的心智。问一个开发者，任何一个开发者；他们会有一些可怕的故事要讲。

如果你的公司是其中之一——如果你的公司是一个应用程序，并且这个应用程序工作正常，但是工作不干净，不优雅，不可扩展，不可扩展——那么你的公司已经积累了一堆技术债务，不管你是否知道，你已经有大麻烦了。

我喜欢用一个住房的比喻:仅仅因为你的房子看起来不错，房间舒适且装饰良好，并不意味着它不是建立在如此糟糕的基础上，如果一个身材魁梧的客人跑下楼梯，它可能会倒塌。再补充一个故事？你在开玩笑吗？别提了。事实上，你的房子可能一开始就建在很差的地基上，在这种情况下，甚至一个新的地基都不行:你必须完全废弃它，在别的地方重新开始。

这种情况甚至发生在技术含量极高的公司。我举 RIM 为例。还记得他们发布不带电子邮件应用的平板电脑吗？还记得当 iOS 和 Android 把黑莓甩在身后的时候，他们是如何无声无息地踩着水走了很久吗？这些失败不是设计选择或深思熟虑的执行决策。它们之所以发生，是因为 RIM 积累了大量的技术债务，并花了数年时间才还清。

就像货币债务一样，技术债务是完全可以的，只要 a)你不会积累太多，b)你完全了解它。当然，经常要在可伸缩性和开发速度之间做出妥协。当然，当截止日期临近，和/或资金不足，任务看起来巨大时，快速破解捷径有时是正确的选择。当然，可以理解的是，所有开发人员都偏向于他们知道的工具——或者，有时，他们想要学习的工具——而不是最适合手头工作的工具。

### 像所有债务一样，技术债务会随着时间的推移而增加。

但太多时候，为了短期成功而积累技术债务最终是一个可怕的错误。像所有债务一样，技术债务会随着时间的推移而增加。更糟糕的是，许多非技术人员(即太多的经理、高管和创始人)往往低估了它的危险，或者甚至没有意识到他们正在加速发展……直到他们发现自己花了好几个月的时间来偿还技术债务，而他们的竞争对手却在愉快地加速前进。就像 RIM 一样。

那么，创业公司如何避免这种可怕的命运呢？

当然，雇佣合适的人至关重要。结对编程很有帮助，我喜欢的[主/辅模式](https://web.archive.org/web/20230107053325/https://techcrunch.com/2012/03/03/pair-programming-considered-harmful/)也是如此。我一直认为技术评估是个好主意:让一些有经验的人花一周左右的时间来审核你的代码和架构，一次在应用程序生命周期的早期，另一次在中途。[我工作的公司](https://web.archive.org/web/20230107053325/http://www.happyfuncorp.com/)曾经这样做过一两次，但是，唉，这并不是真正普遍的行业惯例，或者至少现在还不是。

如果你已经背上了一大堆技术债务，你能做什么？首先，不要逃避现实，承认你有一个大问题。第二，别挖了。停止添加新功能，让事情进入一个半稳定的状态，这样你就可以看到你有什么，没有什么。然后尝试确定你是否可以保留你的隐喻房子，但需要重建基础——即使之前工作的东西会在修复过程中再次出现故障，这总是令人沮丧——或者你是否必须抛弃一切重新开始。(这可能是最好的解决方案，也可能是最快的解决方案。)

不过，最重要的是，听听你的开发者的意见。如果你雇佣了合适的人，那么他们和你一样想要干净的、可扩展的、可伸缩的代码。浏览 Postography 应用程序的初始源代码几乎是一件痛苦的事情。现在我觉得有点像我们做了手术，拯救了一个可怕的车祸受害者的生命，他后来成为了一名奥林匹克运动员。拯救你的应用永远不会太迟；但是你开始得越早，就越容易。

*影像学分:*《金钱的影像》、【TaxFix.co.uk】/[Flickr](https://web.archive.org/web/20230107053325/http://www.flickr.com/photos/59937401@N07/7214463188/)。