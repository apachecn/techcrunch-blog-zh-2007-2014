# Skype 和 Dropbox 修复了可能攻击你的脸书的重定向安全漏洞

> 原文：<https://web.archive.org/web/https://techcrunch.com/2013/04/03/goldschlager-saves-the-day/>

# Skype 和 Dropbox 修复了可能攻击你的脸书的重定向安全漏洞

Nir Goldshlager 刚刚保存了你的身份。作为世界顶级白帽安全研究人员之一，Goldshlager 本周帮助 Skype 和 Dropbox 修复了一个严重的安全漏洞，该漏洞可能会让黑客控制他们用户的脸书账户。明天 [Goldshlager](https://web.archive.org/web/20230217010014/http://www.breaksec.com/?page_id=6002) 将详细说明他是如何发现这个漏洞的，但是他已经提前通知了 TechCrunch。以下是黑客如何利用这个漏洞。

首先是好消息。由于这是负责任的报告，似乎没有人成为这个缺陷的受害者，被称为“开放重定向漏洞”。当一个网站不验证它发送给用户及其访问令牌的 URL 时，这个问题就出现了。通常情况下，网站会验证他们发送给你的网址是他们自己的还是他们信任的合作伙伴的。但是如果他们不这样做，知道某人的用户 ID 并且他们已经授予易受攻击站点的权限的黑客可以访问 www。MySiteIsVulnerable.com？UserID55555redirect=www。MaliciousSite.com 并窃取此人的访问令牌，允许他们采取行动，就像他们是被黑客攻击的用户。淘气的身份窃贼。

在这个案例中，metrics.skype.com 和 Dropbox.com 都未能验证重定向，这让他们很容易受到攻击。比如说 metrics.skype.com，黑客首先需要知道有人将他的脸书账户连接到了这些网站中的一个，才能被利用。然后他们可以通过 Graph API explorer 找到那个人的脸书用户 ID。如果黑客随后输入正确的附有用户 ID 的 metrics.skype.com… URL，然后重定向到他们控制的恶意网站，skype 将向受害者发送脸书访问令牌。这将使黑客可以做用户授予 Skype 的任何事情，比如张贴到他们的墙上，获取他们的个人信息等等。没有比发送垃圾邮件更快解除好友关系的方法了。

Goldshlager 发现了这个缺陷，但他没有自己利用它或发布给其他黑客使用，而是负责任地向 Skype、Dropbox 和脸书报告了这个缺陷，他们都证实现在已经修复了这个缺陷。就 Skype 而言，问题实际上出在为该应用程序开发软件的合作伙伴身上，他们一起解决了这个问题。尽管这个 bug 不是脸书的错，但该公司告诉我:

> 我们赞扬安全研究员将这个问题提请受影响组织的注意，并负责任地向我们的白帽计划报告了这个错误。这些错误是由 OAuth 授权域中的开放重定向漏洞触发的。虽然不是脸书漏洞，但我们已经并将继续与我们的 OAuth 合作伙伴一起防止这种利用。由于向脸书和受影响的公司负责任地报告了此问题，我们没有证据表明用户受到此问题的影响。

对以色列安全研究人员来说，整个情况并不新鲜。在过去的两年里，戈尔德施拉格一直在脸书的白帽‘感谢名单’上高居榜首，因为他向[报告的 bug](https://web.archive.org/web/20230217010014/http://www.breaksec.com/?page_id=6002)比其他任何人都多。他还创办了一家名为 [Breaksec](https://web.archive.org/web/20230217010014/http://www.breaksec.com/) 的白帽安全公司，帮助客户在骗子之前发现漏洞。

哦，那个在网上保护你安全的人也有个很棒的名字。所以这杯辣肉桂甜酒我们请客，戈德施拉格先生。继续做黑客吧。

*【图片来源:[elhombredenegro/Flickr](https://web.archive.org/web/20230217010014/http://www.flickr.com/photos/77519207@N02/6818192898/)】*