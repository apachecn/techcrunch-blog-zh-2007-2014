# 脸书新的移动测试框架诞生底部标签栏导航重新设计 iOS 5、6 和 7 TechCrunch

> 原文：<https://web.archive.org/web/https://techcrunch.com/2013/09/18/facebooks-new-mobile-test-framework-births-bottom-tab-bar-navigation-redesign-for-ios-5-6-7/>

当脸书将其应用程序从 HTML5 切换到 native 时，它失去了“快速移动和打破东西”的能力。但它又找回了它的魔力。[今天，它宣布](https://web.archive.org/web/20230129164817/http://newsroom.fb.com/News/723/Updates-to-Facebook-for-iOS)一个大的 [iOS 7 风格的应用重新设计](https://web.archive.org/web/20230129164817/https://itunes.apple.com/us/app/facebook/id284882215?mt=8)，采用先进的原生移动测试框架构建底部屏幕“标签栏”导航。脸书知道通过在 1000 万用户中测试不同的界面来抛弃拉出式导航抽屉。

[如果你在应用商店没有看到新的脸书应用，等一个小时，因为推出似乎有点慢]

iOS 版[脸书](https://web.archive.org/web/20230129164817/https://itunes.apple.com/us/app/facebook/id284882215?mt=8)不仅仅是 iOS 7 版。它也将推出 iOS 5 和 6，但在屏幕底部有一个黑色的导航标签栏，与旧的 iOS 风格相匹配，而不是 iOS 7 的白色标签栏。然而，标签栏不会出现在脸书的 iPad 上，因为它认为抽屉仍然适合更大的屏幕。

对于小家伙，新的标签栏提供了一个超级充电的“更多”按钮。它出现在最右侧，靠近新闻订阅源、请求、邮件和通知的单触按钮。

More 会像旧抽屉一样显示你的应用程序书签，但会在你浏览的任何产品中保存你的位置。以前，如果你打开抽屉，转而查看事件或照片，你会失去你在新闻提要中的位置或你正在做的任何事情。新的 More 按钮实际上是在提要的顶部打开选项卡，因此您的状态和上下文被保留下来。它甚至在会议之间工作，所以如果你让活动在更多中打开，你的聚会将随时在那里等待你点击更多。

![Facebook Translucent Nav Bar](img/46de4e1dae4b6af434a97ea6ae557922.png)

至于美观，脸书还将顶部标题栏做成半透明的，并重新设计了许多图标，比如信息图标，以匹配苹果新移动操作系统的线条和弧线风格。但是脸书并没有把一切都变平，而是给画面留下了一些质感和深度。你可以在这里看到重新设计的应用程序的视频。

然而，今天真正的故事不是这款应用，而是它是如何制作的。

### HTML5 很慢，但男孩可以测试

脸书从来不害怕尝试新事物，看看什么能坚持下去。它发明了[“看门人”系统](https://web.archive.org/web/20230129164817/https://techcrunch.com/2011/05/30/facebook-source-code/)，让它在网络上用用户子集同时测试脸书的数千种变体。它将收集关于使用和性能的数据，以告知向每个人推出什么。

在手机上，它希望做同样的事情，所以它使用原生架构和 HTML5 的弗兰肯斯坦组合来构建其 iOS 和 Android 应用程序。后者让它可以在不需要正式应用程序更新的情况下，即时向用户发布代码更改和测试。“有了 HTML5，我们每天都可以发送代码，并且能够在服务器端进行切换”，脸书产品经理 Michael Sharon 告诉我。这意味着它可以在某一天向 5%的用户推送重新设计的新闻源，一周后向所有人推送，几天后修复一个错误。

但是除了测试之外，HTML5 是一场灾难。这使得脸书的应用程序运行缓慢，反应迟钝，影响了参与度、广告浏览量和应用商店的评级。用户讨厌慢书。马克·扎克伯格后来在 TechCrunch Disrupt 的舞台上说“[我们最大的错误](https://web.archive.org/web/20230129164817/https://techcrunch.com/2012/09/11/mark-zuckerberg-our-biggest-mistake-with-mobile-was-betting-too-much-on-html5/)作为一家公司……在 HTML5 上下了太多赌注”。

所以脸书[抛弃了 HTML5，并在去年夏天完全基于本地基础设施重建了应用](https://web.archive.org/web/20230129164817/https://techcrunch.com/2012/08/23/facebook-for-ios-faster/)。他们快了一倍。突然，他们的应用商店评分飙升，人们平均阅读两倍的新闻报道。这对脸书来说是一个巨大的胜利。

除了它必须牺牲 HTML5 的测试能力。

### “我们虔诚地使用测试”

Sharon 解释说“我们失去的一件事是进行测试的能力。我们虔诚地在 web 和 HTML5 应用程序中使用测试，这是我们希望尽可能回归的东西。”

对于这家通常反应敏捷的公司来说，不得不等到每月应用更新周期来测试新版本的应用是一种折磨。它希望推动变革并获得即时反馈。为了解决 Android 上的问题，脸书在 2013 年 6 月推出了一个测试者俱乐部，让它利用 Android 对开发者更宽容的态度，让高级用户注册玩潜在的新功能并捕捉漏洞。

但是 iOS 拒绝用这样的测试版功能玷污它的简单性。因此，在过去的一年里，脸书悄悄地建立了一个新的原生移动应用测试框架，并在 3 月份将其付诸行动，以构建今天发布的应用更新。

![Facebook Tab Bar](img/04f3c493c1eaa441f8841b2f6ea91235.png)

它的工作原理是，当你下载 iOS 版脸书时，该应用程序实际上包含多个不同版本的界面。然而，你和几十万其他用户在一起，你只能看到一个版本的应用程序。通过这种方式，脸书可以一次尝试大量的变化，而不会有多次应用程序更新或给用户带来任何困惑。自三月份以来，我们都是移动测试框架中的试验品，但我们中没有人知道这一点。

![Boo For Facebook](img/59239e616c70aadcc848caa53596c899.png) Sharon 坚持认为这些不同的测试不是半生不熟的测试版，他说“我们不会发布我们应用的不合格版本。我们正在推出完整的生产就绪版本，这可能会成为主要的体验”。加起来，脸书将一次测试 500 万到 1000 万用户的重大变化——比许多应用程序的用户总数还要多。

“我不会说我们是‘数据驱动的’。“我们是‘数据感知型’或‘数据知情型’，”莎伦说。这意味着，尽管脸书收集了一系列动摇其决策的测试数据，但它不会仅仅因为数据这么说就抛弃自己的直觉或自己相信的设计。

新测试框架的第一大任务是重新思考用户如何在移动设备上导航。它想知道是否有比从应用程序侧面滑出的导航抽屉更好的东西。

它使用新的测试框架对几十种不同的界面设计进行了实验，并根据包括“参与度指标、满意度指标、收入指标、速度指标、速度感知指标”在内的指标对它们进行了比较，直到它发现，从整体上看，feed 或主屏幕底部的一排按钮是最好的设计。这就是今天 iOS 将提供的内容[。](https://web.archive.org/web/20230129164817/https://itunes.apple.com/us/app/facebook/id284882215?mt=8)

这就是脸书如何找回测试的最佳状态。