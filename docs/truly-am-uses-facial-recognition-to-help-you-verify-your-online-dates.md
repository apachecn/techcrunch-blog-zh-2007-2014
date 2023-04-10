# Truly.am 使用面部识别来帮助您验证您的在线约会| TechCrunch

> 原文：<https://web.archive.org/web/http://techcrunch.com/2013/10/27/truly-am-uses-facial-recognition-to-help-you-verify-your-online-dates/>

# Truly.am 使用面部识别来帮助您验证您的在线约会

今天我们在 TechCrunch 欧洲黑客马拉松上看到的最酷的黑客之一是由来自乌拉圭的两名程序员创建的，他们在过去的几个月里一直在世界各地进行黑客活动。通过 Truly.am，您可以确认您正在与谁在线交谈。假设有人在脸书或约会网站上给你发了一张照片。你怎么知道他们真的是照片中的人？ [Truly.am](https://web.archive.org/web/20230306013332/http://truly-am.herokuapp.com/) 使用一些很酷的 HTML5 工具，如 WebRTC 和 [SkyBiometry 面部识别 API](https://web.archive.org/web/20230306013332/http://www.skybiometry.com/) 来验证你的对话伙伴(或你在在线约会网站上遇到的人)是否真的看起来像他们所说的那样。

事情是这样的:你不认识的人给你发了一张照片。然后你去信利. am，上传这张照片，输入这个人的电子邮件地址。然后，这个人会收到一封电子邮件，必须通过使用他们的网络摄像头拍摄一系列图像来训练识别算法，从而验证他或她的身份。一旦这些图像被上传到 Truly.am 服务器，面部识别服务就会接管并对照原始图像进行检查。一旦结果返回，Truly.am 会告诉用户图像是否匹配，当然，请求者也会收到一封带有结果的电子邮件。

正如该项目的两位程序员奥古斯丁·哈勒和达雅娜·贾比夫告诉我的那样，你经常想在网上保持匿名，但在某些情况下，你真的需要知道至少一点关于你正在交谈的人的信息。这次黑客攻击的部分灵感来自他们自己使用 Airbnb 的经历，但我毫不怀疑在线约会网站的用户会喜欢这个产品。毕竟，在这些网站上，假照片仍然占主导地位。

该团队计划将这一想法扩展到包括 LinkedIn、Xing 和其他专业服务的数据，但目前，面部识别应用程序在这里可用[现在](https://web.archive.org/web/20230306013332/http://truly-am.herokuapp.com/)你可以尝试验证你自己的潜在在线约会。