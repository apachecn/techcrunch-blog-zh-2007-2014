# 便携式加密硬盘的深度安全分析 TechCrunch

> 原文：<https://web.archive.org/web/https://techcrunch.com/2010/08/27/in-depth-security-analysis-of-portable-encrypted-hard-drive/>

# 便携式加密硬盘的深度安全分析

![](img/0e32d84e3bc47ede8a352105ce3d3357.png "disk-genie-pcb")
耶鲁安·多姆伯格，又名“雪碧”，写过一篇*优秀的* [分步安全分析](https://web.archive.org/web/20221205084012/http://spritesmods.com/?art=diskgenie)的 [iStorage DiskGenie](https://web.archive.org/web/20221205084012/http://www.istorage-uk.com/diskgenie_over.php) 。DiskGenie 是一款用于便携式硬盘的硬件加密解决方案，完全不需要客户端软件即可运行。DiskGenie 内部的硬盘通过外壳内置的键盘解锁。我总是有点怀疑像这样的消费加密产品在现实世界中的安全性:如果说这些年来我学到了什么的话，那就是对设备的物理访问意味着对该设备的几乎完全控制。在对 DiskGenie 的评估中，Domburg 深入研究了一些硬件攻击的本质，进一步强调了物理访问通常是完全访问。

多姆伯格对他的方法论的通俗易懂的描述非常棒。他简洁地解释了定时攻击的方式和原因。他寻找绕过磁盘精灵暴力预防机制的方法——甚至走得更远，以创建定制电路来中断设备的内部通信。

多姆伯格的攻击只取得了相对的成功:他从未能够解密硬盘，但他能够收集到关于该设备及其工作原理的大量信息。这是一个人，独自工作，用普通的设备。试想一个敬业的专业团队能做些什么。正如丁伯格总结的那样:

> 那么，安全吗？这个问题的答案将是(像往常一样):视情况而定。
> 
> 如果你只是一个普通的想确保你的私人照片不会被你的同事或孩子看到的人，那你就是黄金。纯软件攻击无法获取密码这一事实意味着，开始入侵该设备需要一些硬件经验，这将足以阻止偶然的旁观者，使该设备对好奇的邻居或同事来说完全安全，即使他们足够聪明，例如，在你的 PC 上安装了键盘记录器。
> 
> 如果你是一个需要隐藏真实信息的商务人士，这些信息可能会给其他人带来经济利益……你仍然可以使用这个，但是一定要选择一个强有力的密码。11 位以上就可以了，这取决于其他人对数据的渴望程度。

即使我已经给出了结局，我仍然强烈推荐阅读整个分析。有那么好。