# 社交事件分享的艰苦战斗:Plancast TechCrunch 的事后分析

> 原文：<https://web.archive.org/web/https://techcrunch.com/2012/01/22/post-mortem-for-plancast/>

***编者按** : [马克·亨德里克森](https://web.archive.org/web/20230122032204/http://www.crunchbase.com/person/mark-hendrickson)是策划活动的社交网站 [Plancast](https://web.archive.org/web/20230122032204/http://plancast.com/) 的创始人兼首席执行官，他已经决定不再全职工作。在这篇客座博文中，亨德里克森带我们详细分析了为什么它从未起飞，以及他学到了什么。他还是一名前 TechCrunch 作家。*

大约三年前，[我离开了 TechCrunch](//web.archive.org/web/20230122032204/https://techcrunch.com/2009/03/10/hendrickson-were-gonna-miss-you/) 的职位，开始了我自己的互联网业务，我的想法是创建一个网络应用程序，帮助人们在现实生活中聚在一起，而不是像大多数社交网络应用程序那样简单地帮助他们在线联系。

Plancast 是几个月后从这个基本倾向中构思出来的服务。它的方法是为人们提供一种真正简单的方式，让他们可以在日历上制定任何有趣的计划，并与朋友公开分享，其理由是，这种特定类型的个人信息的更大社会透明度将促进偶然的聚会，并使人们对相关事件有更多的了解。就我个人而言，我认为更多地了解我的朋友和同龄人参加的活动会让我的社交和职业生活更加充实，因为我可以加入他们，或者至少了解他们是如何在城里度过时光的。

在这一过程中,[我的团队](//web.archive.org/web/20230122032204/https://worldlydevelopments.com/)开发了一个[最小可行产品](//web.archive.org/web/20230122032204/https://en.wikipedia.org/wiki/Minimum_viable_product) , [在 TechCrunch 上默默无闻](//web.archive.org/web/20230122032204/https://techcrunch.com/2009/11/30/plancast/)推出,[从当地风险投资家和天使投资人那里筹集了一轮种子资金](//web.archive.org/web/20230122032204/https://techcrunch.com/2010/03/08/plancast-funding/),并疯狂地将我们最初的成功转化为长期增长、参与和盈利。

唉，我们的努力在发布后几个月就开始停滞了，我们从来没有能够超越一个小的早期采用者社区并进入关键的主流使用。虽然最初的推出和牵引证明非常令人兴奋，但它误导了我们，让我们相信有一个更大的市场准备采用我们的产品。在接下来的一年半时间里，我们努力完善产品的目的，并通过更好的功能和设计来支持其核心价值主张，但我们最终无法让它发挥作用(用户注册增长和参与是我们的两个主要高级指标)。

这种事后分析试图描述我们产品模型中的基本缺陷，特别是事件作为一种内容类型所带来的困难。我希望其他产品设计师能从我们的经验中学到一些东西，尤其是如果他们设计的服务依赖于用户生成的内容。我在这里描述的挑战直接适用于事件，但它们可以共同用作案例研究，以推进人们对其他内容类型的思考，因为如果人们试图设计一个促进其交换的网络，所有类型都需要沿着这些路线进行认真的分析。

## 共享频率

社交网络(根据我的一般定义，我把 Plancast 算在内)本质上是在互相关心的人之间分发内容的系统，其用户在特定网络上分享内容的[频率](//web.archive.org/web/20230122032204/https://markmhendrickson.com/share-frequency)对于它将持续为他们提供多少价值至关重要。

与其他更频繁的内容类型(如状态更新和照片，每天可以共享多次)不同，计划只适合偶尔共享。大多数人根本不会去那么多的活动，即使他们去了，也有很多是不确定的。因此，用户往往不会养成每天或每周贡献内容的强烈习惯。此外，通过自发提交和从其他服务聚合获得的内容太少，无法为大多数用户提供反复发现事件的令人信服的体验。

我运营这项服务，即使是我，目前在我的[个人资料](https://web.archive.org/web/20230122032204/http://plancast.com/mark)上也只列出了五个即将推出的计划，在过去几年中共分享了 500 个计划，相比之下，同一时期 Twitter 上有近 2800 条推文。人们经常告诉我“我喜欢 Plancast，但我从来没有任何计划要分享”。对于社交网络，这有时是一个自我意识的问题(比如当人们说他们不知道该发什么微博时)，但通常他们只是在说实话；许多 Plancast 用户在他们的日历上没有任何有趣的计划。

## 消费频率

人们也不会像你想象的那样主动寻找活动来参加。我已经习惯于把人分成两个阵营:有很多空闲时间的人和没有空闲时间的人。

那些这样做的人通常会积极主动地填补空缺，部分是通过提前寻找有趣的活动来参加。他们通常对社交机会更好奇，他们会采取具体措施来发现新的机会并加以评估。

那些没有太多空闲时间的人往往希望节省时间，所以他们不去寻找或欢迎额外的机会，而是将它们视为对有限资源的精神负担。对他们来说，计划是一项高风险的工作，通常他们宁愿什么都不做，因为如果他们很忙，他们可能更喜欢保持他们的空闲时间——自由。

很难一概而论地说大多数人属于这个或那个阵营，但可以说，有许多人属于后者。对他们来说，很难让他们对一项能让他们在如何利用时间上有更多选择的服务感到兴奋。

## 拖延的倾向

即使把这种分歧放在一边，大多数人在绝对需要做出承诺之前还是会拒绝做出承诺。人们害怕错过有价值的活动，但实际上并不喜欢主动避免这种错过的机会，这需要计划。

这可以主要归因于人们希望保留他们的选择，以防随着事件日期和时间的临近出现其他冲突的机会。如果他们有能力观望，他们会的。因此，只有当他们特别有信心参加某个活动时，如果他们需要在活动满员前预订一个位置，或者如果有其他类似的特权，他们的承诺才会得到保证并提前分享。

## 分享的动机

回到分享计划的话题，这不仅仅是分享有趣的计划的问题，而是被迫分享它们的问题。不幸的是，人们不会向社交网络提交信息，因为他们喜欢数据集的完整性或利他主义地相信尽可能多地给予。他们这样做是因为自私的贡献行为会给他们带来回报。

大多数社交网络主要依靠虚荣心，因为它们允许人们分享和定制在线内容，让他们看起来更好。他们可以帮助人们与他人交流，他们上过令人印象深刻的学校，建立了惊人的职业生涯，参加过很酷的聚会，与有魅力的人约会，进行过深刻的思考，或者养育过可爱的孩子。大多数人的最高目标是让别人相信他们是他们想成为的人，无论这包括快乐、有魅力、聪明、有趣还是其他。

这种虚荣心迫使人们最强烈地分享关于他们自己(或他们遇到的事情)的内容，当有观众准备好并能够产生有效的反馈时。当你在 Instagram 上发布一张巧妙的照片时，你是在告诉全世界“我很有创造力！”分享证据。那些关注你的人通过喜欢这张照片并对它进行积极的评论来验证这种表达。首先发布照片，然后收到积极反馈的心理冲动驱使你发布更多照片，希望随后达到高潮。

不幸的是，分享计划并不能带来同样的炫耀机会，也不能带来同样的快乐。有些计划适合广泛消费，可以让一个人看起来很好，比如参加一场很棒的演唱会或者精明的会议。但是，令人沮丧的是，最无聊的事件是独家的，不适合与他人分享，尤其是细节。

反馈机制也不那么有效，因为对一个活动提出有价值的评论比评论一张照片更难，当还有加入的选项时，“喜欢”一个计划是令人困惑的。让朋友加入的积极反馈本身是不太可能的，因为那些朋友在做出承诺之前有一些考虑，而且他们会倾向于为了实际目的而推迟承诺，如上所述。

此外，如果用户想炫耀他们参加了一个很酷的活动，那么在活动开始前(T0)这样做，而不是在活动开始(T3)时(T2)简单地发推特或发布照片，几乎没有额外的好处。一个重要的例外是专业人士，他们把自己标榜为有影响力的人，并希望成为他们的同行发现事件的工具。在技术专业人士的早期采用者社区中，这个例外确实是我们的参与者贡献的大部分活动数据的原因。

## 选择性和隐私问题

当然，虚荣心并不是用户分享计划的唯一可能动机。让别人和你一起参加你将要参加的活动也是有用的，但事实证明这对于广播来说是一个微弱的激励，因为大多数人更喜欢对他们在现实生活中邀请的人相当挑剔。

虽然活动发起人在吸引各地与会者方面有经济利益，但与会者自己主要转向他们更亲密的朋友圈子，并单独接触他们。你不会特别看到很多长尾计划(比如夜游和旅行)，因为人们既担心派对不速之客，也通常对从广泛的网络中寻找参与者不感兴趣。

## 邀请的重要性

在这种不愿广泛分享计划的另一面，是人们需要亲自受邀参加活动的心理需求。

Plancast 和其他社交活动分享应用程序植根于一种理想主义的观念，即只要人们知道他们朋友的活动，他们就会自信地邀请自己参加。但是这里的信息需求不仅仅是事件细节(比如将要发生什么，什么时候，在哪里，和谁一起)。人们通常还需要通过私人邀请来知道至少有一个朋友希望他们加入。

当你有一个帮助传播个人事件信息的服务，但不能同时满足这种需求时，你会遇到这样一种情况，许多人会尴尬的意识到他们不欢迎的事件。因此，Plancast 上最吸引人的活动是那些原则上开放的活动，而不是主要通过邀请来吸引参与者，如会议和音乐会，在这些活动中，朋友和同行的出席对他们自己来说不太重要。

## 内容生命周期

让内容进入社交网络不足以确保其足够的价值；随着时间的推移，保持内容的价值也很重要，特别是如果它只是慢慢流入的话。

不幸的是，计划没有很长的保质期。在事件发生之前，用户的计划通过通知其他人这个机会来提供社会价值。但是之后，它对网络的价值急剧下降到几乎为零。由于大多数用户没有足够的信心提前一两周以上分享大多数计划，计划通常在这段时间后变得毫无用处。

将这种过期趋势与更“常青”的内容类型(如个人资料和照片)进行对比。在你建立脸书个人资料多年后，其他人可以从你的个人资料中获得价值，你在大学里发布的照片似乎甚至已经增值了。怀旧甚至不必扮演一个角色；在未来很长一段时间里，人们在 Pinterest、Tumblr 和其他视觉内容丰富的网络上看到[这只小狗](https://web.archive.org/web/20230122032204/http://pinterest.com/pin/62065301084425706/)时，他们的心会融化。但是即使你是我的朋友，你又有多在乎[我去年 10 月在纽约参加了一个技术聚会](https://web.archive.org/web/20230122032204/http://plancast.com/p/7crb/october-2011-ny-tech-meetup)？

## 地理限制

地理特殊性是计划价值的另一个内在限制。与几乎所有其他内容类型(除了签到)不同的是，当这些用户生活在或能够旅行到足够近的地方时，计划就向其他人提供了大部分价值。

我可能会分享在旧金山举办一大堆重大活动的计划，但我住在旧金山湾区以外的朋友很少有人会在意。事实上，他们会发现目睹他们将错过的东西是令人讨厌的。当然，他们可能喜欢简单地知道我在做什么，但这种监视本身的价值是相当有限的。

当试图将服务扩展到新的位置时，这尤其成问题。新用户将很难找到足够多的本地朋友，他们要么已经在使用这项服务并分享他们的计划，要么愿意应邀加入他们的新服务。在非城市地区遇到这种服务的人最难过，因为他们所在的地区通常没有太多活动，更不用说发布到 Plancast 上了。试图查看他们感兴趣的地点或类别中简单列出的所有事件，几乎不会给他们带来什么乐趣。

## 展望未来

尽管面临所有这些挑战，我仍然相信有人最终会发现如何制造和营销一种可行的服务来实现我们的目标，即帮助人们更加社交化地分享和发现事件。了解我们的朋友们计划做什么有太多未被发掘的价值，所以不要把这些信息局限在个人日历和个人头脑中。

可能会出现另一家初创公司，它可以洞察我们忽略的攻击角度。或者，更有可能的是，具有现有事件或日历产品的已建立的公司将逐渐为用户提供更大的能力来共享包含在其中的他们的个人信息。在日历方面，Google 可能是最好的 Google Calendar 和 Google+可以一起提供无缝的事件共享体验(我们为 Plancast 认真考虑的事情之一是深度的个人日历集成，但没有足够的平台可供使用)。在活动方面，Eventbrite、Meetup 和脸书等公司的服务主要吸引活动组织者，但已经包含有用的数据集，可以用来创建自己的社交活动发现并为参与者分享体验。

Plancast 成功吸引了早期采用者的利基受众，他们发现这是分享和了解活动的最有效方式之一(感谢用户！你知道你是谁)。每月有超过 100，000 人注册，超过 230，000 人访问，更不用说享受我们每天通过电子邮件发送的活动摘要。仅仅因为这个原因，尽管它的增长面临挑战，我们将尽可能长时间地保持它的运营，并希望我们能找到一个可以把它变得更大的家。我期望有一天，主流社会会把它目前为这个小社区提供的人际共享视为理所当然，我期待看到技术进步如何克服上述挑战，让我们实现这一目标。

![](img/621510e279f419f81efc521714197877.png)