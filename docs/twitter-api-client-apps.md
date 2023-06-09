# Twitter 手铐客户端应用程序的新 API 变化

> 原文：<https://web.archive.org/web/https://techcrunch.com/2012/08/16/twitter-api-client-apps/>

Twitter 的 Michael Sippey 在今天的一篇博客文章中宣布了公司 API 的一系列即将到来的变化。我们已经[总结了这篇文章](https://web.archive.org/web/20230403223440/https://techcrunch.com/2012/08/16/twitter-gives-developers-6-months-to-properly-display-tweet-use-new-authentication-and-rate-limts/)，但是大图在这里:对于传统 Twitter 客户端应用的开发者来说，事情将变得更加艰难。

许多新的限制都属于“开发商的道路规则”例如，开发者现在将不得不遵循[显示指南](https://web.archive.org/web/20230403223440/https://dev.twitter.com/terms/display-guidelines)，而不是把它们当作指南。此外，预装在移动设备上的应用程序需要首先获得 Twitter 的批准。

或许最重要的是，需要超过 100 万个个人“用户令牌”的应用程序现在将不得不直接与 Twitter 合作。如果您正在访问某些“通常由传统客户端应用程序使用”的服务，如 home timeline，阈值是 100，000 个用户令牌。如果现有的应用程序已经超过了阈值，它可以继续运行，但一旦它的用户数量增加一倍，“你将能够维护你的应用程序来为你的用户服务，但*没有我们的允许，你不能添加额外的用户*。”(强调我的。)

为什么有这么多新的限制？好吧，听起来 Twitter 对支持与自己的客户端应用竞争的服务并不感兴趣。这是该公司以前说过的话，也是 Sippey 在博客文章中基本上再次说的话，并附有一个方便的图表，我已经把它放在了这篇文章的顶部。(呃，红色的字母是我加的。)如果你在左上、左下和右下象限，你就很棒。如果你在右上方…就没那么多了。或者至少，Sippey 说该公司正试图在该领域“限制某些用例”。他写道:

> 右上角是让用户与推文互动的服务，如推文监管服务 Storify 或推文发现网站 Favstar.fm。
> 
> 右上象限当然还包括“传统的”Twitter 客户端，如 Tweetbot 和 Echofon。大约 18 个月前，我们给了开发者指导，他们不应该构建模仿或复制主流 Twitter 消费者客户端体验的客户端应用。重申一下我在上一篇文章中写的，这个指导方针今天仍然适用。

需要澄清的是，邮报似乎对 Storify 和 Favstar 等服务竖起了大拇指，但对传统的 Twitter 客户端却没有。

正如 Sippey 所说， [Twitter 已经朝着这个方向前进了一段时间](https://web.archive.org/web/20230403223440/https://techcrunch.com/2011/03/11/twitter-ecosystem-guidelines/)。但是套用[亨特沃克](https://web.archive.org/web/20230403223440/https://twitter.com/hunterwalk/status/236239436805963776)的话来说，这看起来像是公司撕掉创可贴的时刻。这会伤害到一些开发者，但希望这不只是引出他们的痛苦。