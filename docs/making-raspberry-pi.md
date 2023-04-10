# 制作 35 美元的树莓派迷你电脑:快速而小心地做

> 原文：<https://web.archive.org/web/https://techcrunch.com/2012/12/24/making-raspberry-pi/>

可以肯定的是，一些极客父母的孩子明天会在他们的圣诞树下发现一个长方形的包裹。当他们撕开闪亮的包装时，这些幸运的孩子会发现里面有一个非常美味的树莓派:一台 35 美元的迷你电脑，可以播放蓝光质量的视频，比任天堂 Wii 的图形能力更强——尽管这些都不会立即显而易见。Pi 是一个学习工具，而不是即插即用的玩具。

当孩子们从防静电包装中取出他们的 Pi 时，他们可能注意到的第一件事就是它看起来有点奇怪。如果他们在 iPhones 和 iPads 等光滑闪亮的消费电子产品周围长大，他们可能从来没有接触过未覆盖的电路板。从密封的盒子中回收电子产品是 [Raspberry Pi 基金会让孩子们学习编码](https://web.archive.org/web/20230322160429/https://techcrunch.com/2012/10/14/raspberry-pi-the-small-computer-with-the-big-ambition-to-get-kids-coding-again/)计划的一部分——好奇心是学习和创造力的重要组成部分。

因此，本着再剥离几层的精神，我一直在问基金会，制造 35 美元迷你电脑的秘诀是什么。基本的食谱是这样的:有非常熟练的厨师，他们能以最快的速度制作一批又一批的覆盆子馅饼，而且尽可能少的失败。

许多树莓 Pi 是在英国制造的，在[索尼的 Pencoed 工厂](https://web.archive.org/web/20230322160429/http://www.sonypencoed.co.uk/)在威尔士[获得了一份价值数百万英镑的合同，为基金会的 Pi 许可证持有人之一，Premier Farnell 生产 Pi](https://web.archive.org/web/20230322160429/http://www.sonypencoed.co.uk/news/2012/09/06/sony-uk-tec-tune-in-for-success/)。Premier Farnell 在中国也有两个生产 Pi 的工厂，但其大部分生产(70%)是在 Pencoed，到 1 月份，该工厂将占其全部 Pi 产量。(该基金会无法透露每个被许可方到底占了多少比例。)

索尼的 Pencoed 工厂平均每天生产 4000 台 B 型 Pi T1——或者说每 7.5 秒生产一台。当你考虑到生产数以千计的双面 PCB(印刷元件板)所涉及的复杂性时，这是很难想象的，这些 PCB 的两面都有表面贴装元件，顶部有电镀通孔元件，熔化的焊料滴在正确的位置，正确的元件以每秒 5.5 个零件的速度压印在上面。而且预算非常紧张。

电路板由六个 Pis 面板制成，经过四道“关键工序”:安装底面元件、安装顶面元件、安装电镀通孔元件；然后测试和包装。

### 预算中的 Pi

当然，制造一个 Pi 远没有制造一部现代智能手机那么复杂，但这里的平衡之举是在不损害分销商商业模式的情况下压低价格。Pi 中最昂贵的组件是处理器和内存芯片，其次是连接器。

标价 35 美元(即将推出的[型号 A Pi](https://web.archive.org/web/20230322160429/http://www.raspberrypi.org/archives/2615) 只需 25 美元)的组件必须以合适的价格购买，而且还要有合适的质量——因为制造缺陷也必须最小化，并从生产过程中挤出，直到它们几乎不存在。减缓生产也没有好处:对 Pi 的需求如此之高，他们每天必须能够生产数千个。

“为了实现低价格，同时还能产生可持续的商业模式，需要熟练的制造优化和零件采购，”Pi 硬件设计师和基金会受托人 Pete Lomas 说(没有关系！).“生产线必须高效运行，并且故障率非常低。必须从质量和价格两方面选择部件供应商，任何潜在的变化都必须通过详细的选择程序。如果成品树莓派的故障率上升，在组件上节省 40 美分是没有多大用处的。同样，每个缺陷都被积极地追寻，以了解其根本原因并消除它。”

“测试失败”当然仍然存在，但洛马斯说，“据我们所知”，不到 100 块电路板被用户作为有缺陷的产品退回，这意味着不到 0.1%的电路板逃过了质量控制网。“其中，一些有物理(运输)损坏，另一些没有发现故障，所以实际数字又有点低，”他补充说。

### 热销

就满足需求而言，洛马斯承认，该基金会最初有些措手不及——严重低估了人们对圆周率的兴趣——这导致了最初几个月的发货延迟。“在最初几天，人们对 Pi 的兴趣大增，这让我们措手不及，”他表示。“当我们准备适度生产 20，000 辆的时候，表达出的兴趣超过了我们 10 倍。在这一点上，我们决定与我们的合作伙伴法内尔总理和 rs。

“即使他们有大量的资源，为 10 万个 Pis 获取组件并将其制造出来的物流也是一个挑战。”

与苹果(Apple)或三星(Samsung)等电子巨头不同，非营利组织 Raspberry Pi Foundation 及其供应商无法在发布前储备组件，以扩大规模应对意外的需求激增。(而且让我们面对现实吧，即使是[苹果也不能总是跟得上需求](https://web.archive.org/web/20230322160429/https://techcrunch.com/2012/09/24/iphone-5-sells-over-5m-in-opening-weekend/)。Lomas 说，另一个延迟因素是一些 Pi 组件的交付周期长。

“(我们的合作伙伴)没有机会在上市前囤积(不像苹果)，所以事情总是很棘手。可扩展性还取决于组件，某些部件(尤其是处理器)的交付周期非常重要，一年内仍会出现制造问题。”

该基金会预计在运营的第一年销售约 100 万辆 Pis 与最初预算的 2 万辆相去甚远。

### 在英国烘焙

树莓圆周率诞生于英国，所以自然基金会希望圆周率也在英国制造。Lomas 说，索尼的 Pencoed 工厂被选中是因为它符合各种条件——尤其是对儿童开放，让他们参观正在制作的 Pi。

“在英国制作树莓派是我们第一天就有的愿望。该基金会的目标是鼓励孩子们培养对编程、电子和相关工程学科的兴趣。他告诉 TechCrunch:“在一个我们可以提供‘展示和讲述’机会的地方制造 Pi 也很重要，索尼管理层和员工的整体理念是这一点的重要促成因素。”

“选择 Sony Pencoed 是因为他们世界级的技术能力和他们对整个 Raspberry Pi 项目的热情。我们也不应该忘记，他们为我们的被许可方提供了一个可行的成本模型，与远东制造的“总成本”相当。同样，从技术角度来看，任何与设计相关的生产问题或优化的管理和解决都要容易得多，只要几个小时。”

该工厂现在有超过 22 名员工专门从事 Pi 生产。从第一次与工厂联系到达到“批量生产”的总交付时间约为 14 周——这表明索尼花了多长时间来设计 Pi 生产线。洛马斯说，现在 Premier Farnell 和索尼之间有一个“滚动生产预测”，允许大约一个月通知的“一定程度的生产灵活性”。

“索尼生产流程中唯一没有的流程是一个接一个的包装。在引入计划中，他们深入研究了该过程，选择并安装了设备，并在将该过程引入 Pi 生产线之前进行了试验验证，”他补充道。 ****

### 又一份圆周率

当被问及索尼的工厂未来能否扩大产能时，洛马斯表示，有“大量额外产能”可以投入生产。“最终是被许可方决定在哪里放置额外的容量，但总的来说，索尼的体验非常好，”他补充道。

根据洛马斯的说法，对聚酰亚胺的需求没有减少，但该基金会认为其现有的聚酰亚胺工厂有足够的能力满足需求。“我们希望，在未来几个月，我们将达到平衡，制造业与需求达到平衡(就像以往一样)。我们可以选择增加现有制造商的产能，因此很可能不需要额外的工厂。”

关于 Pi 生产的更多信息，洛马斯已经写了一篇出色的、[详细描述了](https://web.archive.org/web/20230322160429/http://www.raspberrypi.org/archives/2569)索尼 Pencoed Pi 生产线的各个阶段和过程——比如用于保持生产正常进行的表面贴装元件的卷轴，Pi 板如何在巨大的烤箱中烘烤(是的，真的)以确保所有元件都正确粘合，以及“熔岩事故”的危险

该基金会还制作了一个视频剪辑，展示了《少年派》的一些制作阶段:

[YouTube http://www.youtube.com/watch?v=zj9bFgsaBd4]