# Real-Time-Rendering-4th-CN
《Real-Time Rendering 4th》 (RTR4) 中文翻译

## 关于本书

英文名称：《Real-Time Rendering, Fourth Edition》

原作者：Tomas Akenine-Moller, Eric Haines, Naty Hoffman, Angelo Pesce, Michal lwanicki, Sebastien Hillaire

翻译者：Morakito

版本：v1.0

时间：2023.11.20

内容简介：本翻译版涵盖了RTR4中的第1章-第26章中的内容。附录内容详见在线网站，参考文献目录详见参考文献网站和参考文献合集，已涵盖勘误内容（截止到2023.10.30）。由于本人才疏学浅，翻译难免有误，望各位不吝惜指正。本翻译仅供交流学习，如有侵权，请联系删除。

## 相关链接

-   PDF文件：[https://github.com/Morakito/Real-Time-Rendering-4th-CN/releases/tag/v1.0](https://github.com/Morakito/Real-Time-Rendering-4th-CN/releases/tag/v1.0 "https://github.com/Morakito/Real-Time-Rendering-4th-CN/releases/tag/v1.0")
-   源文件仓库：[https://github.com/Morakito/Real-Time-Rendering-4th-CN](https://github.com/Morakito/Real-Time-Rendering-4th-CN "https://github.com/Morakito/Real-Time-Rendering-4th-CN")
-   在线网站：[https://www.realtimerendering.com](https://www.realtimerendering.com/ "https://www.realtimerendering.com")
-   勘误网站：[https://www.realtimerendering.com/corrigenda.html](https://www.realtimerendering.com/corrigenda.html "https://www.realtimerendering.com/corrigenda.html")
-   参考文件网站：[https://www.realtimerendering.com/refs.html](https://www.realtimerendering.com/refs.html "https://www.realtimerendering.com/refs.html")
-   参考文献合集仓库：[https://github.com/QianMo/Real-Time-Rendering-4th-Bibliography-Collection](https://github.com/QianMo/Real-Time-Rendering-4th-Bibliography-Collection "https://github.com/QianMo/Real-Time-Rendering-4th-Bibliography-Collection")
-   wolai文件：[https://www.wolai.com/fkGSwxLu2pjWD7kiBY1V7W](https://www.wolai.com/fkGSwxLu2pjWD7kiBY1V7W "https://www.wolai.com/fkGSwxLu2pjWD7kiBY1V7W")

## 序言

（下文来自毛星云的自序，共勉）

> All our dreams can come true, if we have thecourage to pursue them.

> 沃尔特·迪斯尼——我们所有的梦想都可以成真，只要我们有勇气去追求它们。&#x20;

依稀记得那还是F4红遍大街小巷，满城都飘扬着《流星雨》的年代。

那个时候的电子游戏，无论是投币式的街机游戏，还是网吧里的《反恐精英》、《流星蝴蝶剑》、《仙剑奇侠传》、《星际争霸》、《帝国时代》等引领时代的游戏界的璀璨明珠，总能深深地吸引住每个纯真无邪孩童的心，绚烂的游戏画面总是让孩童们流连忘返。

那个时候，每次放学后唯一单纯的想法，就是悄悄溜到学校附近的网吧，和电脑游戏亲密接触。口袋里有邻花钱的时候就能玩上一会儿，没有零花钱的时候就痴痴地站在屏幕前面看别人操纵着荧幕前的剑侠闯荡世界。年少的我单纯地认为，游戏世界中存在着一个无比恢弘的世界，那是可以装下梦想的地方。应该是我对游戏的痴迷，对游戏开发梦想的虔诚，让我走向了研习游戏开发的这条道路。

还记得那个香樟树覆盖的夏天，年幼无知的我在一帮同学中吹牛说：我长大后，一定要自己开发出比这些还牛还要好玩的游戏。

现在想想，这几年走过的路途，真应了那句话，“现在的努力，都是为了小时候吹过的牛逼”。

这些年来，在学习游戏编程的道路上有过惊喜，有过坎坷，有过自豪，有过怅惘，走了不少弯路，也算是最终走上了正途，小有所成。于是，我单曲循环着五月天的《有些事情现在不做一辈子都不会做了》，打开Word，打开Visual Studio，把自己这么多年来的游戏开发经验和心得用文字凝聚起来，开始为大家写这本书。

而这么一写，就是一整年。

经过一年夙兴夜寐，终于，赶在22岁生日之前，近百万字的书稿随着一声响指而初具雏形。

“谨以此书献给父母，因养育之恩无以回报。谨以此书献给母校南京航空航天大学和乌克兰国立航空航天大学，因赐予我一颗不甘平庸、上下求索的心。谨以此书献给所有怀揣游戏开发梦想的人们，因为，你们不是一个人在战斗。”

当在书稿的开头写下这三个“谨以”的时候，我终于开始觉得，这一年的夜以继日，这一年的披星戴月，都是值得的。

然而，因为岁月积累的关系，这本书中渗透的编程思想或许不能和编程界中的泰斗们同日而语。但是，我可以捂着胸口问心无愧地说，我把这些年自己悟出来的关于游戏编程的学习方法和真知灼见，毫无保留地呈现给了大家。大家能看到的眼前的这些句子和代码，全都是经过一遍又一遍的深思熟虑，一遍又一遍的修改，然后小心谨慎地敲出来的。

详细研究过游戏编程的朋友们都应该有这样的共识：“中国人写的书水平上不去，外国人写的书水平有了，但是翻译得往往都强差人意，理解不了”。也许正是这个原因，国内游戏编程的入门门槛一直很高，DirectX一直被人们认为是很难学的。很多怀揣游戏开发梦想的热血青年们，信誓旦旦地开始着手学习游戏编程的时候，却被晦涩难懂的游戏编程教材拒之梦想门外，碰了一鼻子灰，从此和最初的梦想失之交臂。我想，这正是导致国产游戏业界的萎靡，国产游戏一直很难成长起来的原因之一。

在这样的环境的激励下，这本倾注我一年多心血的书出现了，它的创作初衷便是渴望能够改变这样的现状。

愿这本书，能帮到那些热爱游戏编程、怀揣游戏开发梦想，却苦于难以入门的人们，让他们少走弯路。

愿这本书，能为国产游戏、国产游戏引擎的崛起，开启一扇门，迎接新的黎明。

我有一个梦想，将来的某一天，大家都能玩到蕴含着中国上下五千年本土文化的优质游戏大作。

我有一个梦想，有一天，西游记能出ACT，让老外去体会中国文化西游记中”斗战胜佛”的打击快感，那一定比西方的动作巅峰之作《战神》、《鬼泣》更加深邃。

我有一个梦想，有一天，上海滩能出沙盒游戏，而不是玩《GTA》感受美国梦，亦或是玩着《热血无赖》体验国外公司强行塞给我们的“中国文化”。

我有一个梦想，有一天，不少3A大作不需要汉化，因为是我们自己的游戏，配音是中文，文化也是中国的。

我有一个梦想，将来的某一天，国产游戏能像中国的其他产业一样，以一个领跑者的姿态，面对全世界，面对全宇宙，器宇轩昂，扬眉吐气。

这会是由我们一起去完成的梦想。

我等着我们的好消息。

浅墨 2013年5月于乌克兰

希望我们可以一起努力，翻过那座山。
