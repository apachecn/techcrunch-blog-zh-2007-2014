# ControlC:将剪切和粘贴转变为 Web 服务 

> 原文：<https://web.archive.org/web/https://techcrunch.com/2008/01/29/controlc-turning-cut-paste-into-a-web-service/>

 [](https://web.archive.org/web/20230203091821/http://www.controlc.com/) [ControlC](https://web.archive.org/web/20230203091821/http://www.controlc.com/) 是一个有趣的新网站，它采用普通的复制和粘贴(Ctrl-C)并通过 web 服务运行。

最基本的是，在您创建一个帐户并安装软件之后，只要您按 Ctrl-C，信息就会以简单文本的形式保存到 ControlC 网站和您的本地剪贴板上，如果您拷贝的是一个链接，也可以是一个 URL 链接。这些信息既是私有的又是加密的，尽管如果你愿意，你可以将任何项目公开。网站上的朋友可以通过 RSS 或 API 访问公共信息，并对其进行评论和评级。这是通过一个适用于 Windows 或 Mac 电脑的小下载来完成的。整个项目都是开源的。

它能用来做什么？嗯，最明显的用途是一种简单的方法，可以将你复制到剪贴板的任何内容永久保存到网络上。它类似于一些社交书签应用程序，也允许从网站上复制选定的文本。主要区别在于 ControlC 可以在任何应用程序上工作，而不仅仅是浏览器和网页。

因为人们往往会不假思索地复制如此多的个人信息，所以数据的安全性是这家初创公司的一个重点。创始人罗恩·迈尔斯说，这就是为什么他们将数据默认为私有，并对其进行加密:

> 任何未标记为公开的内容都将是私有的，仅对您可读。毫无疑问，每个人都会将极其敏感的数据放入剪贴板，如密码和信用卡号，向某人保证这些数据在远程存储时是安全的并不是一件容易的事情。投入 ControlC 的开发时间几乎有一半是为了确保在任何情况下都不会暴露私有数据，无论是通过 SQL 注入、XSS，还是有人闯入数据中心窃取服务器上的数据。我们所做的是用一个唯一的密钥双向加密所有私人数据，每个用户-这是基于他们的纯文本密码(我们不存储在任何地方，只有一个 MD5)-因为我们不存储这个变量(当你想查看敏感项目时，你输入它)，即使攻击者能够“侵入”服务器，数据也是安全的。我想大多数初创公司都不会承认网站可能会被黑客攻击，因为这会让他们觉得自己很“业余”，但公开我们如何保护数据肯定是非常重要的。

商业模式类似于我上周提到的[WebMynd](https://web.archive.org/web/20230203091821/https://techcrunch.com/tag/webmynd/)——在有限的时间内免费访问，如果你想访问旧数据，需要付费升级。

核心服务极其简单，这也是我喜欢它的原因。由于它是开源的，我们可能会看到该服务出现创造性的变化。例如，一些像 Zoho 这样的在线办公初创公司可能会发现 ControlC 的用处。

一些读者可能还记得微软的雷·奥茨在 2006 年 3 月推广一项名为 Live Clipboard 的服务。Live Clipboard 允许在 web 应用程序和桌面应用程序之间复制和粘贴数据，包括动态更新数据。

ControlC 处于私有测试阶段，但您可以使用代码:beta4040 注册。每个新帐户都会收到五个邀请，因此我们也将此添加到了[邀请共享](https://web.archive.org/web/20230203091821/http://www.inviteshare.com/site.php?id=87)。