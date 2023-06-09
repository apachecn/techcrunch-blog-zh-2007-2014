# 谷歌云存储为所有文件推出自动服务器端加密技术

> 原文：<https://web.archive.org/web/https://techcrunch.com/2013/08/15/google-cloud-storage-now-features-server-side-encryption/>

# 谷歌云存储为所有文件启动自动服务器端加密

从今天开始，所有开发者写入谷歌云平台上非结构化存储的数据，现在都将在谷歌的服务器上自动加密。谷歌已经在其[计算引擎](https://web.archive.org/web/20221208143141/https://cloud.google.com/products/compute-engine)上对写入其[永久磁盘](https://web.archive.org/web/20221208143141/https://developers.google.com/compute/docs/disks#persistentdisks)和[暂存磁盘](https://web.archive.org/web/20221208143141/https://developers.google.com/compute/docs/disks#scratchdisks)的数据进行了加密，但正如该公司[刚刚宣布的](https://web.archive.org/web/20221208143141/http://googlecloudplatform.blogspot.ca/2013/08/google-cloud-storage-now-provides.html)，所有写入[谷歌云存储](https://web.archive.org/web/20221208143141/https://cloud.google.com/products/cloud-storage)的数据现在也将使用 128 位高级加密标准进行加密。

谷歌在今天的公告中解释说:“每个对象的密钥本身是用与对象所有者相关联的唯一密钥加密的，”并且“这些密钥还用一组定期轮换的主密钥加密。”默认情况下，谷歌将为其用户管理这些数据的密钥，但你也可以在将数据写入云存储之前自己加密数据。对于那些对自己的加密技术非常偏执的人来说，让谷歌管理和存储他们的密钥可能不是一个选择。然而，谷歌表示，它使用“谷歌用于我们自己的加密数据的相同的强化密钥管理系统，包括严格的密钥访问控制和审计。”

谷歌表示，新的服务器端加密已经对所有写入云存储的新数据生效，旧对象将在“未来几个月”进行迁移和加密。

值得注意的是，自 2011 年以来，AWS 的 S3 云存储服务已经提供了使用 256 位高级加密标准的服务器端加密。对于那些需要满足更严格的公司、合同和监管合规性数据安全要求的人，亚马逊最近还推出了一种专用的(昂贵的)硬件安全模块，用于管理亚马逊云中的敏感数据和加密密钥。