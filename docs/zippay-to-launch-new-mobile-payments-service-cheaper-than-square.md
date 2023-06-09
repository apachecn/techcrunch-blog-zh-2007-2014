# ZipPay 将推出比 Square 更便宜的新移动支付服务 

> 原文：<https://web.archive.org/web/http://techcrunch.com/2011/10/07/zippay-to-launch-new-mobile-payments-service-cheaper-than-square/>

描述隐形移动支付初创公司 [ZipPay](https://web.archive.org/web/20230205032353/http://zippaymobile.com/) 的最简单方式是说，这就像 [Square](https://web.archive.org/web/20230205032353/http://www.squareup.com/) 和 [Venmo](https://web.archive.org/web/20230205032353/https://venmo.com/) 生了一个孩子，这就是结果。与 Square 一样，这家初创公司旨在通过允许个人和小企业主使用手机接受信用卡支付来满足他们的需求，这些人无法负担拥有自己的商业账户所需的高额费用。与此同时，像 Venmo 一样，该解决方案也将提供一种进行个人对个人支付的方式。

但是有一些关键的区别。首先，与 Square 不同的是， [ZipPay](https://web.archive.org/web/20230205032353/http://zippaymobile.com/) 不会使用加密狗。它还承诺每次刷卡的费率低于 Square 的 2.75%。

然而，如何做到这一点还不清楚。

ZipPay 将提供一种移动钱包解决方案，使用一些未公开的正在申请专利的技术，而不是像 Square 那样连接到手机耳机插孔的加密狗。

[![](img/9743e9cacea0d6d67dd758553d3d72d6.png "cardio-Android_screenshot")](https://web.archive.org/web/20230205032353/https://techcrunch.com/wp-content/uploads/2011/09/cardio-android_screenshot.jpg) 为了将卡装入钱包，ZipPay 正在利用 [Card.io](https://web.archive.org/web/20230205032353/http://www.card.io/) ，[面向移动开发者的新软件开发套件](https://web.archive.org/web/20230205032353/https://techcrunch.com/2011/06/23/card-ios-sdk-makes-entering-credit-card-information-as-easy-as-taking-a-snapshot/) (SDK)，该套件使用计算机视觉和机器智能的结合来“读取”举在手机摄像头前的卡。与在小键盘上手工输入数字相比，这项技术可以更快地将信用卡信息输入到移动应用程序中。

与为当地商家提供数字“标签”的 [Square 的类似钱包的卡套](https://web.archive.org/web/20230205032353/https://squareup.com/cardcase)不同，ZipPay 的钱包支持所有主要的信用卡，包括 Visa、MasterCard、Discover 和 American Express。以后会支持店卡，优惠卡，会员卡。

卡数据以加密格式直接存储在设备上，但是，这不是支持 NFC 的移动钱包系统。ZipPay 应用程序有一个强制的 4 位 PIN 码，但信用卡数据如何在客户和商家或两个 ZipPay 用户之间发送仍是一个谜。

该公司首席执行官瑞安·史蒂文斯表示，出于竞争原因，他还不准备透露系统的这一部分，但有可能该应用程序以某种方式使用智能手机传感器来连接两台设备，每台设备都需要运行 ZipPay 应用程序。或许类似于[撞](https://web.archive.org/web/20230205032353/http://bu.mp/)的东西？

![](img/567ccc68606c6a6dcc690566fa9ad4c6.png "zippay-MainMenu")

在商家方面，像 Square 一样， [ZipPay](https://web.archive.org/web/20230205032353/http://zippaymobile.com/) 将允许快速注册，因此新用户可以立即开始接受信用卡。该公司当场进行基本的背景调查，如果没有任何明显的危险信号，账户就会被批准。商家在第一天可以收取高达 1000 美元的费用(与 Square 的手动输入/无卡限制相同)。后来，当完整的背景调查通过后，限制就取消了。

ZipPay 在后端有一个银行合作伙伴(暂时未命名)，付款会在 1 到 3 天内存入商家的账户，这意味着涉及到 ACH 系统。

ZipPay 系统的第二部分是涉及点对点支付的功能，这非常像初创公司 Venmo。在这种情况下，两个人都需要在他们的设备上安装 ZipPay 应用程序，然后，再次使用未披露的技术，支付可以在设备之间即时发送。

因为该公司还没有准备好详细介绍其技术，所以很难将它提供的东西与 Square、PayPal、谷歌钱包或其他公司进行比较。我们知道它不是 NFC，也没有加密狗，但仅此而已。我们还知道，它计划像 Square 一样收取一部分加工费，该应用程序还将包括“一个小广告”，这可能是它计划如何削弱 Square。

这里，安全性也是一个大问题，考虑到如果设备受到病毒或恶意软件的攻击，存储在设备上的加密数据仍然容易受到攻击。此外，在 NFC 的情况下，存储在设备上的每张非接触式卡都会生成一个密码，以专门识别每笔交易。没有两张卡共享同一个密钥，并且该密钥永远不会被传输。

ZipPay 的系统将如何工作？它是否在设备上存储完整的磁条数据？涉及什么级别和类型的加密？采取了什么措施来保护两端的数据？传输过程中？

该公司表示，它不在自己的服务器上存储信用卡数据，只存储用于解密你设备上数据的技术。使用在线仪表板，丢失或被盗的手机可以立即被禁止支付，但这并不能保证在你意识到你的手机不见了之前，信用卡数据不会以某种方式从设备中提取出来。

在系统进入测试版之前，这些问题中的许多可能仍然没有答案。ZipPay 将于 2012 年在 Q1 推出 iPhone 和 Android 应用，从 iOS 版本开始。[它现在接受测试版注册](https://web.archive.org/web/20230205032353/http://zippaymobile.com/)。