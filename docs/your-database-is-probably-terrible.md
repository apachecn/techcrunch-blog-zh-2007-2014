# 你的数据库可能很糟糕

> 原文：<https://web.archive.org/web/https://techcrunch.com/2013/01/19/your-database-is-probably-terrible/>

数据库并不性感，但它们是技术世界的绝对基础，是建造所有大厦的基础。你可能每天用一百个。至少在*时*。他们就像 *[沙丘](https://web.archive.org/web/20230328231607/http://en.wikipedia.org/wiki/Dune_%28novel%29)* 里的香料:“谁控制了数据库，谁就控制了宇宙！”好吧，现在不要看，但是宇宙开始震动了。

一开始是平面文件，瞧，它相当糟糕，所以帮助我们 [Codd](https://web.archive.org/web/20230328231607/http://en.wikipedia.org/wiki/Edgar_F._Codd) 。然后是 SQL 和拉里·埃里森，他莫名其妙地成为世界上第六富有的人，靠的是完全平庸的甲骨文数据库。(我曾经做过几个月的 Oracle 开发人员。这是我职业生涯中最长的几个月。)

在很长一段时间里，Oracle、IBM 的 DB2 和微软的 SQL Server 三足鼎立的关系数据库没有受到挑战，Oracle 在同类数据库中独占鳌头。然后是开源革命，还有 MySQL 和 PostgreSQL。(以及运行在移动设备上的 SQLite。但 10 年前，每个人都知道那只是一个利基市场。[右](https://web.archive.org/web/20230328231607/http://www.sqlite.org/)？)

然后 Web 2.0 出现了，事实证明关系数据库没有很好地扩展。哦，他们在某种程度上很好。但是当全世界都开始攻击你的服务器时？你的服务器倒了。脸书仍然在 MySQL 上运行，但是他们不得不跳过许多(昂贵的)聪明的关卡。推特也是如此。Reddit 完全抛弃了传统的关系数据库设计。

像往常一样，谷歌通过其 [BigTable](https://web.archive.org/web/20230328231607/http://en.wikipedia.org/wiki/BigTable) 数据库在其他任何人之前解决了这个问题，该数据库可伸缩性极佳……但代价是几个怪癖，包括禁止每个查询使用多个不等式运算符。(例如，如果您有一个“盒子”数据库，您可以搜索“长度大于 5”或“宽度大于 3”的盒子……但不能同时搜索两者。我实际上非常喜欢 BigTable，我已经相当广泛地使用了它，但是我在多个场合发现这令人恼火。)这就迎来了的时代。 [MongoDB](https://web.archive.org/web/20230328231607/http://www.mongodb.org/) ， [CouchDB](https://web.archive.org/web/20230328231607/http://en.wikipedia.org/wiki/CouchDB) ，可以说是 [Redis](https://web.archive.org/web/20230328231607/http://redis.io/) 等等:他们疯狂地伸缩！它们真的很容易使用！

不幸的是，他们不得不牺牲一些关系数据库擅长的东西。比如交易的完整性。你可以拥有一个伸缩性非常好的数据库，或者你可以拥有 [ACID](https://web.archive.org/web/20230328231607/http://en.wikipedia.org/wiki/ACID) (原子性、一致性、隔离性、持久性。相信我，这些都是很重要的事情。)但是你不能两者兼得。每个人都知道。工程是一个优化妥协的问题，仅此而已。你总是要妥协。每个人都知道。

好吧。*几乎*所有人。

事实证明，在谷歌内部，有很多人并没有过多考虑 BigTable 及其局限性。所以他们去建立了 [Spanner](https://web.archive.org/web/20230328231607/http://strata.oreilly.com/2012/10/google-spanner-relational-database.html) ，一个关系数据库，不仅可以扩展，还可以扩展到整个星球。与此同时， [FoundationDB](https://web.archive.org/web/20230328231607/http://www.foundationdb.com/) 正在从一端着手解决这个问题，创建了一个既有[NoSQL*又有* ACID](https://web.archive.org/web/20230328231607/https://techcrunch.com/2012/09/10/foundationdb-not-your-standard-nosql-database/) 的数据存储库，而 [Clustrix](https://web.archive.org/web/20230328231607/https://techcrunch.com/2012/07/05/clustrix-6-75-million-shit-ton-of-unstructured-data/) 正在创建一个关系数据库，当你添加更多服务器时，它可以愉快地无缝水平扩展。(本周，他们也推出了亚马逊网络服务。)

数据库管理员是出了名的保守。这很有道理。你不想弄乱你的数据。再说一遍，它是一切事物赖以建立的基础。一旦你在一个数据库上构建了一个完整的系统，你最不想做的事情就是迁移到另一个数据库。但与此同时，数据库技术已经突飞猛进，尤其是最近。

那么，您在工作场所使用的数据库是什么？它们可能不是最好的。事实上，相对而言，它们可能相当糟糕；这种情况可能不会很快改变。下一次，当你仅仅因为某项新技术优于所有竞争对手，就期望它彻底改变世界时，这是值得思考的。世界上大多数人不想被革命。世界上大多数人都喜欢它的数据库。你无法说服他们改变；你必须*驱使*他们去做。