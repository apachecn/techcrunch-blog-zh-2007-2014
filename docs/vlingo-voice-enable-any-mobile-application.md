# Vlingo:语音支持任何移动应用 

> 原文：<https://web.archive.org/web/http://www.techcrunch.com:80/2007/08/21/vlingo-voice-enable-any-mobile-application/>

# Vlingo:语音支持任何移动应用

[![vlingologo.png](img/da7f16f40f7ec64eb1aaed7b4f673f2b.png)](https://web.archive.org/web/20221004165431/http://vlingo.com/) 人们真的很讨厌手机键盘输入数据。

任何打过客服电话的人都知道语音引导电话应用程序并不新鲜，但它们是导航菜单和输入文本的好方法。还有像 [Spinvox](https://web.archive.org/web/20221004165431/http://www.beta.techcrunch.com/2006/05/25/spinvox-converts-voicemails-to-text/) 这样的应用，它结合了语音识别将口头语音邮件转化为书面文本信息，以及 [TellMe](https://web.archive.org/web/20221004165431/http://www.beta.techcrunch.com/2007/02/26/microsoft-has-acquired-tellme/) 这样的应用，它使用语音识别来支持本地搜索，非常有用和受欢迎。

总部位于剑桥的 Vlingo 希望通过使用他们自己的语音到文本 J2ME/Brew 应用程序 API(今年晚些时候的 Windows/Symbian ),使语音应用程序变得更容易。有了这个 API，开发者将能够把用户的声音翻译成文本，并在他们的应用程序中使用，就像直接输入程序一样。他们的第一个例子是本地搜索和购物。Vlingo 在程序上启用了一个文本框，你可以通过按住通话按钮并说出一个短语来填写，比如“旧金山的披萨”。然后系统在表格中填入你所说的内容，如果出现错误，你可以正常修改文本。

在我们的试验中，这个系统对我的加州口音基本上起作用。然而，澳大利亚口音运气很差，凸显了语音识别国际化的困难。通常，语音识别公司通过限制词汇量或在单词和口音的综合词典上训练系统来使他们的工作变得更容易。但是由于他们努力的广度，Vlingo 不得不采取更通用的方法，通过统计分析使用机器学习，以便该系统可以在更广泛的用途中工作。下面有一个演示。
[http://services . bright cove . com/services/viewer/federated _ F8/271548276](https://web.archive.org/web/20221004165431/http://services.brightcove.com/services/viewer/federated_f8/271548276)他们的系统从一个基本的统计语言模型开始，对你说的话做出最好的猜测。然后，它通过考虑上下文以及正面和负面的用户反馈来改进这一点。上下文通过缩小你所说的可能单词的数量来帮助系统。例如，如果上下文是一个地址，则可能的街道名称的数量仅限于城市中的名称。用户反馈纠正系统的输出或让它保持原样有助于系统学习你如何说话(例如，将奥斯汀纠正为波士顿)。

这是一个非常雄心勃勃的项目，但背后的团队在语音识别领域有着丰富的经验。两位联合创始人(Mike Phillips 和 John Nguyen)为 SpeechWorks 工作，该公司被 ScanSoft 收购，然后更名为 Nuance。Nuance 最近[向](https://web.archive.org/web/20221004165431/http://mobilecrunch.com/2007/05/15/one-speech-recognition-company-eats-another-nuance-acquires-voicesignal/)支付了 2.93 亿美元收购 VoiceSignal，这是一家使用语音识别技术在 21 种语言中进行移动搜索的公司。

Vlingo 计划通过按月或按用户向开发者收取费用来实现这项服务的货币化。他们是一个 13 人的团队，拥有来自 CRV 和适马风险投资公司的 650 万美元。