# 直流电与交流电

## 什么是直流电与交流电？

首先从严格的定义上来看，**世界上既不存在直流电也不存在交流电。** **因为世界上既不存在完全符合正弦波的交流电也不存在恒压恒流的直流电**。因为在现代物理学上时间和能量都是不连续的。也就是说我们既做不到直流也做不到交流。我们只能把符合一定范围内的东西叫交流电或直流电。

其次，**任何交流电本质上是直流电，任何直流电本质上也是交流电。** **你要是说交流电是方向变化，直流不会变化只能说明你没看懂第一段。**

## 定义并解释

- 频率。频率单位为赫兹（Hz），1Hz 代表 1 秒钟重复多少次。

>常用交流电一般为 50Hz 或 60 Hz，即代表在 1 秒钟内，电流方向会正反变化 50 次或 60 次。即在一秒钟内，电流向正负方向变化 100 次或 120 次。
>
>假如某交流电每秒 50 次变化，每次往相反的方向变化一次。那么该交流电的频率是 50Hz。该交流电的频率范围是 2。

- 交流电。交流电本质上是方向会改变的直流电。

- 有效值（Root Mean Square，RMS）。交流电的电压是随时变化的，平均值是 0。

>**注意，电压多大不完全决定电能** 你说交流电电压是多少伏根本没有意义，他是来回变的。220V 只是变化的平均值，其实也没有任何意义，因为根本就不存在，只是人为定义。

- 直流电。因为能量和时间及电动机原理，直流电本质上是方向不会变化的交流电。因为交流电是间断的，始终有一刻对用电器来说是不能提供能量的。所谓直流电也一样。

- 用电器。我们的用电器，并不消耗任何电压、任何电荷或者电流。所以在绝对理论上的电池应该是无限期使用的。

>**反证：** 电压电流和电荷有关，如果用电器消耗电压或电流
>
>- ① 既不符合欧姆定律也不符合串联定律、并联定律，因为如果他消耗电压或电流，那么不可能做到符合上述定律。
>
>- ② 如果消耗电荷，那么电流移动是靠的电线，那么电线很快就会被消耗掉了。

根据现有物理学，用电器消耗的是电能，是电势差。

可以想象一座水库。水库在上游，发电机在下游。水库蓄水提升了水的机械能，电池充电，提升了电的电势差。反之，水库开闸放水是释放机械能，电池放电也是释放电能。**因此作为能量的电能本质上和机械能没有任何区别**。

>这也符合了我们的认知，无论是物理学还是其他科学，都逐渐使我们认识到，看似复杂的东西其实他们的本质都是一样的，都由简单的东西符合而成的。不存在任何差别。构成物质的元素只有百余个，而且更基本的单位又更少了，至于是不是一个，我们仍未知道且永远不可能知道。所以，也许世界的确是一个整体且任何事物在本质上也没有任何差别。

为了方便，本文中的交流电一般指有效值为 220V，频率为 50Hz 的市电。

## 电流战争（War of the currents）

在历史上存在交流电和直流电之争，一般课本会认为是交流电胜利了，是特斯拉胜利了。但是，历史与现实告诉我们。胜利的是爱迪生的直流电而绝非特斯拉的交流电。就和新文化运动时说在表达同样的意思时现代汉语比古代汉语用的字更少一样，你好好想想到底是哪个字少。

因为在现代电力系统中，几乎只能在变压器到入户看到交流电。其他任何设备都是交流电。

**就连我们的绝大部分家用电器在本质上使用的也是直流电而非交流电**。

也就是说对于一般的家用电器，你接入 220V 的直流电（比如串联 N 节南孚电池，参考[用 150 个 5 号电池串联成 220v 电源，可以带动电器使用吗？](https://www.bilibili.com/video/BV1fs4y1B7kd)）他也是可以正常工作的。

>由于交流电只是有效值为 220 V，所以可能在理论上并不需要 220V 的直流电。**自己算去吧。**

也就是说，现代的交流电只存在于变压器到家里的插座之间。所以，无论交流电的电流方向怎么变，用电器都能取电，因为他根本用的就是直流电，就和直流电机的电刷一样转换了交流电。

交流电每秒变 120 次，始终有零点出现 120 次是没有功率的，所以在严格意义上交流电的效率是低于直流电的（你用数学公式算微积分证明他们效率一样也是无意义的，因为这是现实，不是数学模型，现实的时间和能量都是不连续的，现实的时间不是无穷小的），即使这个值可能无法观测。交流电他会变，变得快，肯定就始终有那么多次没有电，在变的那一刻上。

>**论证：你从灯泡频闪就能看出来他绝非可以忽略，这也反证了直流电也根本不存在，永远都是有瑕疵的。**

当初对交流电优于直流电的论证思路是：

- ① 交流电压降小，从导线开始到末尾的电压基本不变，适合远距离输电。
- ② 直流灭弧难（电弧）。
- ③ 容易升压降压，便宜。
- ④ 任何发电机本质上都是交流发电机。

现在我们看一下，以上优点，基本只有 ③ 仍然存在。并且在输电方面由于高压直流输变电（HVDC）技术也不存在 ① 了。② 也在技术上也被解决了。④ 任何发电机本质上都是交流发电机。通过简单机械或电子结构也能输出较为标准的直流电。

**所以在理论上，唯一吸引我们使用交流电的就是升降压容易，便宜。**

我们再来看交流电的弊端，交流电除了升降压以外几乎没有任何好处。因为电生磁，磁又生电，不断反复，所以交流电的电磁场会造成很多问题，有各种乱七八糟的效应。你甚至无法在一根铁管内穿两根线。由于交流电的频率变化等问题，会造成很多直流电根本不存在的问题，如：

- 集肤效应（增大导线电阻，干扰信号，损耗能量）
- 邻近效应（增大导线电阻，损耗能量）
- 边缘效应（干扰信号，损耗能量）
- 涡流损耗（感应电流、损耗能量）


所以我们之所以还在使用交流电是因为 **交流电在短距离内输电成本最优，他最便宜。除此之外对于普通家庭来说使用交流电没有任何好处**，还在用只是因为他容易用便宜的方法实现升降压。

现在只有变压器到家里是交流电，整个供电系统几乎全是直流电。

**从某种意义上说，特斯拉的交流电为人类带来了巨大的财产损失。**

所以，从现在的现实来看，赢的是爱迪生的直流电绝非课本上说的特斯拉的交流电。升降压这是技术问题，在人类可以预见的未来，直流电必将彻底取代交流电。

>**论证**：我们现在家中使用的网线是 RJ45 接头的双绞线。我们知道，我们只有在局域网中才会使用这种双绞线。从电信公司到你家也不用他，而是使用光纤传输。交流电就好比双绞线，直流电就好比光纤。
>
>
>我们在家里的网络设备之间（比如路由器到 PC）之所以不用光纤，是因为成本昂贵，需要 100 多块钱才能得到一对入门级的光纤接收和发射器。而相同尺寸的网线，可能只需要 2 块钱。并且可能光纤容易折断。
>
>
>但是这同样是价格及技术决定的。在人类可以预见的未来，光纤必将彻底取代双绞线。
