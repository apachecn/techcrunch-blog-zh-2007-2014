# Android 2.2 的音频流听起来很糟糕，但修复方案即将出台 TechCrunch

> 原文：<https://web.archive.org/web/https://techcrunch.com/2010/08/09/android-22-sound-pandora/>

# Android 2.2 的音频流听起来很糟糕，但修复即将到来

谷歌移动操作系统的最新版本 Android 2.2 现在被部署到 droid 和 Evo 等流行设备上，是一个速度恶魔。不幸的是，它也是音盲:该操作系统有一个缺陷，每当你收听 Pandora 或 MOG 等流媒体音乐服务时，你的耳机听起来就像一对锡罐。在运行旧版本 Android 的同一台设备上听起来很棒的音乐突然听起来模糊不清，带有微弱的高音——你可以分辨出音符和歌词，但它们听起来不再令人愉快。

几周前，我第一次注意到这个问题，并确信是我的蓝牙耳机造成的，但后来我们收到了多个报告，称其他用户也有同样的问题。关于这个问题，已经出现了许多论坛帖子，就像谷歌代码上这篇冗长的[错误报告](https://web.archive.org/web/20221006230843/http://code.google.com/p/android/issues/detail?id=9308)一样。根据错误报告的评论，该问题与 Android 从 OpenCore 媒体框架切换到 Stagefright 有关。后者支持 HTTP 渐进式流媒体，但无法正确处理 AAC+和 e AAC+媒体编解码器，这些编解码器被一些最流行的音乐流媒体服务所使用。

幸运的是，修复工作正在进行中。谷歌发言人告诉我们:

> “我们已经修复了这个漏洞，并正在与我们的合作伙伴一起尽快更新受影响的 Android 设备。”

谷歌还没有发布补丁的时间表(听起来会因设备而异)，但希望在不久的将来。

像 Pandora、[最近推出的](https://web.archive.org/web/20221006230843/https://beta.techcrunch.com/2010/07/20/mog-iphone-android/) MOG 和 TuneWiki 这样的服务显然依赖于他们的流媒体音频听起来不错。Android 团队已经知道这个问题一个多月了，如果不是更久的话。更糟糕的是，用户更可能将音频问题归咎于他们正在收听的任何服务，而不是操作系统本身。