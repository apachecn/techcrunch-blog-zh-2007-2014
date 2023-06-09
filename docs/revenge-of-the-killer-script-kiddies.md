# 黑仔脚本小子的复仇！

> 原文：<https://web.archive.org/web/https://techcrunch.com/2011/08/20/revenge-of-the-killer-script-kiddies/>

他们在外面。害怕。他们可能在任何地方，任何地方，任何人。他们是阴暗的、致命的、神秘的，由知识分子引导，庞大、冷静、冷漠。安全顾问和反病毒公司悄悄告诉他们的客户关于他们的传说，直接吓他们。他们是网络安全的伏地魔，除了每个人都急于说出他们的名字:高级持续威胁。把你的孩子藏起来！你不能阻止他们！

…嗯，事实上你可能可以，也很容易，但显然大多数人不会被打扰。

《名利场》杂志[刚刚气喘吁吁地写了](https://web.archive.org/web/20230312035559/http://www.vanityfair.com/culture/features/2011/09/operation-shady-rat-201109)关于“可疑老鼠行动”的报道，其中提到了“*一种以前从未见过的恶意软件:一封包含网页链接的鱼叉式网络钓鱼电子邮件，当点击它时，会自动将一个恶意程序——一种远程访问工具，或称 RAT——加载到受害者的电脑上*军事工业的旗手诺斯罗普·格鲁曼公司“ *[不断受到网络团伙](https://web.archive.org/web/20230312035559/http://www.networkworld.com/news/2011/062111-northrop-grumman.html)* 的攻击。”几个月前，安全公司 RSA 的 SecurID 系统成为“ *[一种高级持续威胁的受害者，这是一种缓慢而持续的攻击，黑客利用它来获取特定信息](https://web.archive.org/web/20230312035559/http://www.homelandsecuritynewswire.com/cyber-security-firm-victim-cyber-attacks-pentagon-networks-potentially-compromised)* 。”五角大楼意识到了这种威胁，并表示它开始更多地关注威慑而不是防御，因为每年都有超过国会图书馆规模的知识产权从美国政府和私营部门网络中被盗。“为什么，就在本周，旧金山政府所有的 BART 系统被——

…等一下。

人们永远无法确定，尤其是在这个竞技场，但是巴特的警方数据库似乎被一个十几岁的法国女孩黑了，她报告说:“他们没有任何安全措施。”[这里是](https://web.archive.org/web/20230312035559/http://bartpoa.com/forms/contact_form.asp?i=0%27%20UNION%20ALL%20SELECT%201,2,3,4,5,%28%27%3C%28%20%27%2buserId%29,%28firstname%2b%27%20%27%2blastname%29,%28address%2b%27%20city:%27%2bcity%29,9,10,11,12,13,14,15,16,%28email%2b%27%20--Password:%20%27%2buserpwd%2b%27%20%29%3E%27%29,18,19,20,21,22,23,24,25,26,27,28,29,30%20FROM%20%2)据称她用来黑他们的链接。别担心，它已经不活动了。好好看看那个网址。让你想起什么了吗？如果你是 XKCD 的读者，它应该:

[![exploits of a mom](img/87ac4f9e6ad91229e54e713809b953b5.png)](https://web.archive.org/web/20230312035559/http://xkcd.com/327/)

啊， [SQL 注入](https://web.archive.org/web/20230312035559/http://en.wikipedia.org/wiki/SQL_injection)，那个老谣言。但是等等，更糟糕的是:

真的吗？ *[当真](https://web.archive.org/web/20230312035559/http://www.aspheute.com/english/20040105.asp)？*明文？谁负责这些小丑的安全工作，憨豆先生？

好吧，也许 BART hack 是一个被白痴激活的脚本小子。但是“黑幕鼠”呢？很高兴你问了。《名利场》毫无头绪的夸张让它听起来像是互联网历史上从来没有人发送过链接到利用浏览器漏洞的页面的电子邮件。地球对他们的编辑说:你已经落后时代 15 年了。然后，攻击者[使用隐写术](https://web.archive.org/web/20230312035559/http://gcn.com/Articles/2011/08/12/Shady-RAT-steganography-malware-images.aspx)与被入侵的机器进行通信。Ooo，隐写术，吓人又难念！当然，这在十年前可能是非常复杂的。

RSA 黑客的工作方式[与](https://web.archive.org/web/20230312035559/http://gcn.com/articles/2011/04/04/rsa-hack-securid-adobe-flash.aspx)完全相同:向员工发送带有诱人附件的电子邮件，外加零日 Flash 漏洞。科技媒体疯狂关注 APT 对一家安全公司的致命攻击。你*在和我*开玩笑吗？这是“高级持续威胁”的一个例子？土坯产品因其不安全性而成为 [*传奇*](https://web.archive.org/web/20230312035559/http://www.h-online.com/security/news/item/Kaspersky-study-finds-Adobe-software-is-biggest-security-risk-1323895.html) 。如果这是一个恰当的说法，那么新闻集团幼儿园技术水平的手机黑客攻击也是如此。

但是不要只相信我的话:“【Shady RAT 行动中描述的攻击是真正高级的持续性威胁吗？我认为事实并非如此，尤其是当你考虑到在配置服务器时出现的错误，以及本案中使用的相对不复杂的恶意软件和技术时。或者就像 IT 世界 T14 明确指出的那样 T15，一般来说容易受到攻击:“T16 令人吃惊的是受害者借口的复杂性，而不是黑客的技术……只有 3%的攻击被认为太狡猾，受害者无法阻止。这使得 97%的数据泄露受害者试图寻找除自己以外的原因。

有真正的，复杂的，聪明的黑帽黑客。他们中的一些人分组工作。有些人甚至为民族国家和军队工作，很可能包括 18 个月前攻击谷歌的人。但大多数黑客攻击之所以成为可能，是因为受害者允许他们这么做；我们不应该忘记，安保公司有各种动机让危险看起来尽可能致命和复杂。

各地的组织建立起全方位的防火墙，起草拜占庭式和卡夫卡式的安全政策，派代表参加安全会议，小声严肃地谈论 APTs，并以安全剧场的名义在[提出无休止的毫无意义和/或灾难性适得其反的](https://web.archive.org/web/20230312035559/http://russell.ballestrini.net/security-professionals-yes-we-appear-vulnerable-but-that-attack-vector-will-never-happen/)要求，例如强迫人们使用不可能记住的密码

[![password strength](img/e7e5188f1270ba77567b78a6b5d0e248.png)](https://web.archive.org/web/20230312035559/http://xkcd.com/936/)

同时在易受 URL SQL 注入攻击的数据库中以明文形式存储那些不可理解的密码，当他们的员工打开陌生人发送的带毒附件时。这就像你太担心一个敌对的民族国家是否向你的房子发射了巡航导弹，以至于忘记了你的车整夜都开着门，钥匙还插在点火器上。在奥克兰。如今，担心中国导演的 apt 非常性感——如果公然仇视中国的话——但也许组织不应该开始担心中央王国的敌意，直到他们首先建立起处理无聊的法国少女的能力。

*图片鸣谢:*《公敌/轻微威胁》、 [believekevin](https://web.archive.org/web/20230312035559/http://www.flickr.com/photos/believekevin/2656404984/) 、Flickr。