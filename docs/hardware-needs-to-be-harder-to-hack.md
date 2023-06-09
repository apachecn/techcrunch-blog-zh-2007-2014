# 硬件需要更难破解 

> 原文：<https://web.archive.org/web/https://techcrunch.com/2014/02/20/hardware-needs-to-be-harder-to-hack/>

# 硬件需要更难破解

有消息称，Linksys 和 Belkin 的硬件本来就不安全，很容易让黑客进入你的本地网络并控制你的设备。

首先是“月亮”，一种可以感染 Linksys 的 E1000、E1200 和 E2400 路由器的恶意软件。恶意软件从一个路由器传播到另一个路由器，但是[似乎没有做太多](https://web.archive.org/web/20230129083324/https://isc.sans.edu/diary/Linksys+Worm+%22TheMoon%22+Summary%3A+What+we+know+so+far/17633)除了广泛传播自己。

然而，更可怕的是[的一次黑客攻击，黑客可以访问他们的智能家居设备 WeMo 系列](https://web.archive.org/web/20230129083324/http://www.ioactive.com/pdfs/IOActive_Belkin-advisory-lite.pdf)。WeMo 是一系列智能墙壁开关和控制器，可以让你感应运动，远程控制灯光和电器。黑客将他们自己的固件注入设备，访问交换机，更改设置，甚至访问本地网络。安全公司 IOActive 建议“从 WeMo 产品中拔出所有受影响的设备。”

当我们接近真正的“物联网”时，我们连接的这些东西最好是安全的。随着健康追踪器和恒温器等设备成为真正的个人传感器系统，它们提供的数据将越来越有价值，它们提供的服务也越来越关键。很长一段时间以来，家用硬件都是不联网的。现在不是了。

需要做些什么？简而言之，硬件制造商必须强化他们的系统。WeMo 黑客存在仅仅是因为 Belkin 变懒了。它们允许攻击者对修改过的固件进行数字“签名”，从而将 WeMo 变成一个攻击媒介。虽然如果一个普通的入侵者试图打开和关闭你的灯可能并不可怕，但对于一个想要访问你的文件的坚定的黑客来说，这种利用是很有价值的。我们的 Fitbits、Basis bands 和 Pebbles 也是如此——普通用户没有什么可担心的，但获取目标在各种情况下的心率可以为攻击者提供一种方法，在社交上设计一个毫无防备的目标。再加上对心脏起搏器等健康设备的远程控制，你就有了真正可怕的东西。

硬件早就太难黑了。它是不连接的，大型制造商倾向于创建愚蠢的协议，虽然安全，但不能做太多。既然我们期望从每个 gewgaw 中获得大的东西，我们需要准备好这些东西将会被黑客攻击，更重要的是，被黑客攻击。