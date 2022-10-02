# FreeBSD 手册翻译项目

## 2022 FreeBSD 中文社区 翻译项目

> **部署域名**
>
> **当前网站部署域名为** [**https://handbook.bsdcn.org**](https://handbook.bsdcn.org)**，如果当前使用的不是这个域名，请切换到该域名。**

> **PDF 文档**
>
> **当前文档的 PDF 实时更新地址为** [**https://handbook.bsdcn.org/FreeBSD-简体中文手册.pdf**](https://handbook.bsdcn.org/FreeBSD-简体中文手册.pdf)**，历史存档在 [Release](https://github.com/FreeBSD-Ask/Handbook/releases)。**

> **版本说明**
>
> 当前文档版本同步至官方文档 [2022-9-11 commit 7365cde48dc150d03e85c0c42c855136822e586e](https://github.com/freebsd/freebsd-doc/commit/7365cde48dc150d03e85c0c42c855136822e586e)。如需更新请提交 issue 或 pull request。

> **警告**
>
> **未校对部分为 Deepl 机器翻译，仅人工做了格式调整，请谨慎参考。**
>
> 若发现已校对部分存在错误或者纰漏，你可以直接在发起 pull request 或 issue 提出看法，也可以在交流群里直接 @ 管理员。

## 译者相关

**机器翻译相关**

|               章节               |     Deepl 机器翻译    |        格式调整       |
| :----------------------------: | :---------: | :---------------: |
|               前言               |     ykla    |        魔王酱        |
|            第 1 章：简介            |     ykla    |        魔王酱        |
|        第 2 章：安装 FreeBSD        |     ykla    |   ulianchn38、歸野鴿  |
|    第 3 章：FreeBSD 基础【3.1-3.2】   |     ykla    |        ykla       |
|    第 3 章：FreeBSD 基础【3.3-EOL】   |    亲爱的翻译官   |      ykla、歸野鴿     |
|    第 4 章：安装应用程序: 软件包和 Ports    |    亲爱的翻译官   |   ykla、skadomsky  |
|   第 5 章：X Window 系统【5.1-5.2】   |  ykla 【重译】  |    ulianchn38、冰   |
|  第 5 章：X Window 系统 【5.3-5.4.6】 |    冰 【重译】   |  ykla、ulianchn38  |
|  第 5 章：X Window 系统 【5.4.6-EOL】 |    Lin🌠    | ykla、ulianchn38、冰 |
|          第 6 章：桌面应用程序          |     胞嘧啶     |        ykla       |
|            第 7 章：多媒体           |     无目先生    |        ykla       |
|       第 8 章：配置 FreeBSD 内核      | Jasonlecson |       ykla、冰      |
|       第 9 章：打印 【9.1-9.4】       |     潇潇雨竹    |        ykla       |
|       第 9 章：打印 【9.5-EOL】       |  ulianchn38 |        ykla       |
|   第 10 章：Linux 二进制兼容层 【10.1】   |    Altair   |        ykla       |
| 第 10 章：Linux 二进制兼容层 【10.2-EOL】 |  亲爱的翻译官【重译】 |        ykla       |
|           第 11 章：wine          | Jasonlecson |       ykla、冰      |
|          第 12 章：配置与优化          |     胞嘧啶     |       ykla、冰      |
|      第 13 章：FreeBSD 的引导过程      |     徐艺扬     |     ykla、冰、歸野鴿    |
|            第 14 章：安全           |      陈诚     |       ykla、冰      |
|           第 15 章：Jail          |      陈诚     |       ykla、冰      |
|          第 16 章：强制访问控制         |      陈诚     |       ykla、冰      |
|          第 17 章：安全事件审计         |      冰      |      ykla、歸野鴿     |
|            第 18 章：存储           | Jasonlecson |       ykla、冰      |
|     第 19 章：GEOM: 模块化磁盘转换框架     | Jasonlecson |       ykla、冰      |
|       第 20 章：Z 文件系统（ZFS）      |    徐艺扬、冰    |  ykla、ulianchn38  |
|          第 21 章：其他文件系统         | Jasonlecson |        ykla       |
|           第 22 章：虚拟化           |     歸野鴿     |       ykla、冰      |
|  第 23 章：本地化 - i18n/L10n 的使用和设置 |      郴      |       ykla、冰      |
|      第 24 章：更新与升级 FreeBSD      |  亲爱的翻译官【重译】 |        ykla       |
|          第 25 章：DTrace         |     歸野鴿     |       ykla、冰      |
| 第 26 章：USB Device 模式 / USB OTG | Jasonlecson |        ykla       |
|           第 27 章：串行通信          |     胞嘧啶     |       ykla、冰      |
|           第 28 章：PPP           |   ykla【重译】  |        ykla       |
|           第 29 章：电子邮件          |   ykla【重译】  |        ykla       |
|          第 30 章：网络服务器          |      陈诚     |       ykla、冰      |
|           第 31 章：防火墙           |      陈诚     |       ykla、冰      |
|           第 32 章：高级网络          |      陈诚     |       ykla、冰      |
|         附录 A：获取 FreeBSD        |    亲爱的翻译官   |        ykla       |
|             附录 B：书目            |     ykla    |        ykla       |
|            附录 C：网络资源           |    亲爱的翻译官   |        ykla       |
|         附录 D：OpenPGP 密钥        |     ykla    |        ykla       |
|               术语表              |    亲爱的翻译官   |        ykla       |

> > **名单排序以提交的先后顺序为准。未标明部分由 ykla 完成，下同。**

**校对相关（标记用户即为完成，下同）**

|               章节               |    第一轮校对/审阅   | 第二轮校对/审阅 | 第三轮校对/审阅 |
| :----------------------------: | :-----------: | :------: | :------: |
|               前言               | ykla |          |          |
|            第 1 章：简介            | ykla |          |          |
|        第 2 章：安装 FreeBSD    | ykla/Shengyun |          |          |
|        第 3 章：FreeBSD 基础        | ykla/Shengyun |          |          |
|    第 4 章：安装应用程序: 软件包和 Ports    | ykla/Shengyun |          |          |
|        第 5 章：X Window 系统       | ykla/Shengyun |          |          |
|          第 6 章：桌面应用程序          | ykla/Shengyun |          |          |
|            第 7 章：多媒体           |      ykla     |          |          |
|       第 8 章：配置 FreeBSD 内核      |      ykla     |          |          |
|            第 9 章：打印            |      ykla     |          |          |
|       第 10 章：Linux 二进制兼容层      |      ykla     |          |          |
|           第 11 章：wine          |      ykla     |          |          |
|          第 12 章：配置与优化          |      ykla     |          |          |
|      第 13 章：FreeBSD 的引导过程      |      ykla     |          |          |
|            第 14 章：安全           |      ykla          |          |          |
|           第 15 章：Jail          |       ykla        |          |          |
|          第 16 章：强制访问控制         |       ykla/KCommit         |          |          |
|          第 17 章：安全事件审计         |    ykla/KCommit            |          |          |
|            第 18 章：存储           |       ykla/KCommit        |          |          
|     第 19 章：GEOM: 模块化磁盘转换框架     |     ykla/KCommit           |          |          |
|       第 20 章：Z 文件系统 (ZFS)      |     ykla/KCommit          |          |          |
|          第 21 章：其他文件系统         |     ykla          |          |          |
|           第 22 章：虚拟化           |               |          |          |
|  第 23 章：本地化 - i18n/L10n 的使用和设置 |               |          |          |
|      第 24 章：更新与升级 FreeBSD      |               |          |          |
|          第 25 章：DTrace         |               |          |          |
| 第 26 章：USB Device 模式 / USB OTG |               |          |          |
|           第 27 章：串行通信          |               |          |          |
|           第 28 章：PPP           |               |          |          |
|           第 29 章：电子邮件          |               |          |          |
|          第 30 章：网络服务器          |               |          |          |
|           第 31 章：防火墙           |               |          |          |
|           第 32 章：高级网络          |               |          |          |
|         附录 A：获取 FreeBSD        |               |          |          |
|             附录 B：书目            |               |          |          |
|            附录 C：网络资源           |               |          |          |
|         附录 D：OpenPGP 密钥        |               |          |          |
|               术语表              |               |          |          |

>> **章节之间的未标明部分也经过了校对。当前已校对章节仍然可能存在一些问题需要解决，见 [issue](https://github.com/FreeBSD-Ask/Handbook/issues)。**

**网站部署与维护**

 - Shengyun
 - ykla

## Q & A

* ~~Q：对 FreeBSD Handbook 进行简体中文翻译的必要性？~~
  * ~~A：~~

~~俗话说的好，要想富先修路。要想推广和宣传 FreeBSD，也必须先翻译 Handbook。~~

~~有些人认为有英语不需要翻译，看不懂的人就不配学习 FreeBSD。此言差矣，Handbook 不专门针对开发者这一个群体，而是针对所有人（~~[~~https://docs.freebsd.org/en/books/porters-handbook/porting-why/~~](https://docs.freebsd.org/en/books/porters-handbook/porting-why/) ~~专为开发者编写），类似于 Linux 的 wiki，但是对比下手册更有体系结构。FreeBSD 也并非专门为了某些精英而创设，不懂英语是一件很正常的事情，不同的语言有不同的世界观，只有经过翻译才能让更多普通人走进 FreeBSD，发展 FreeBSD，结缘 FreeBSD。你懂英语，别人不一定懂，不能用你的标准去衡量所有人。FreeBSD 社区以及基金会从未说过不懂英语就无法使用 FreeBSD 这种话。~~

~~还有些人认为与其翻译 Handbook 不如我们自己去写原创性的文章，其实翻译handbook，恰恰是为了更好地撰写原创性的文章，我们的另一个项目——~~[~~《FreeBSD 从入门到跑路》~~](https://github.com/FreeBSD-Ask/FreeBSD-Ask)~~目标就是包括所有 Handbook 有与无的内容。我们认为，翻译文档和贡献代码是同样重要的事情；如果你有原创教程，那我们有教程征集计划——~~[~~https://docs.qq.com/doc/DSUJsUFBHTnVWQmtS~~](https://docs.qq.com/doc/DSUJsUFBHTnVWQmtS) ~~最重要的是，我们的进程已经完成等待校对。现在还在纠结这个问题这无异于在中国哲学史课程快要上完的时候还在讨论中国到底有没有哲学。~~

* Q：本项目为什么不能向 FreeBSD 上游进行合并？
  * A：

~~很简单，我们无法向上游贡献。~~[~~https://wiki.freebsd.org/Doc/Translation~~](https://wiki.freebsd.org/Doc/Translation) ~~中的指南无法具体落实，其翻译进度一直是（99%）,实际上是 0。我们多次与 FreeBSD 简体中文翻译负责人（该负责人从 18 年就进行 FreeBSD handbook 的翻译，但始终未能进行）进行联络，始终无法得到及时回应。但本着 FreeBSD 是一个开源的项目，人人都可以 fork 的态度。并不会影响我们的工作进度。也不会导致本项目产生任何问题。我们认为，踏出第一步永远比空谈任何东西都更为重要！~~

现阶段需要先完成校对并且我们现在需要人手来进行校对并向上游进行合并。要求能够对照英文找到中文的翻译。直接翻译（照抄）ykla 给定的 po 文件。另外需要一名或多名 committer 进行配合。目前 FreeBSD 上游的 doc 文档工具链存在 bug，编译出来的中文字体会乱码（疑似没有加载中文字体，只有日文字体），也许要等其修复。

* Q：怎样维护？
  * A：

翻译完毕后约 1 个月整体维护一次。对比官方 Handbook 进行更新。

## 翻译指南

[https://docs.qq.com/doc/DSUtxYmVwU29EdGVn](https://docs.qq.com/doc/DSUtxYmVwU29EdGVn)

## 关于

### 简介

来到这里你可能什么也得不到。也将不会失去任何东西。FreeBSD 中文用户社区！恪守古老的法则，追寻真正的自由。BSD 方为真正 UNIX 哲学继承者。加入我们，共同推进 FreeBSD 中国化与世界化。

|       资源      |                            链接                            |
| :-----------: | :------------------------------------------------------: |
|   Telegram 群  |     [https://t.me/freebsdba](https://t.me/freebsdba)     |
|      QQ 群     |                         787969044                        |
| Handbook 最新翻译 | [https://handbook.bsdcn.org](https://handbook.bsdcn.org) |
|  FreeBSD 入门书籍 |     [https://book.bsdcn.org](https://book.bsdcn.org)     |
|  FreeBSD 中文论坛 |      [https://bbs.bsdcn.org](https://bbs.bsdcn.org)      |
|     微信公众号     |                         freebsdzh                        |

扫码关注微信公众号：

![扫码关注微信公众号](./.gitbook/assets/weixin.jpg)

### FreeBSD 中文社区 寄言：

> 每一个人的不经意付出和教程完善的分享，都是极具意义的，理论上会长久存在，你做的每一点一滴的努力与付出都会成为历史的印记和未来某些科技的驱动力的先驱。手册是死的，我们对手册的贡献是一直存活的，存活在那些使用 Handbook 的人的心中。
>
> **“The best time to plant a tree is 20 years ago. The second-best time is now.”（种一棵树最好的时间是十年前，其次是现在）——Dambisa Moyo,** _**dead aid**_
>
> 我希望有更多的人参与进来，一起协作这个开源项目。英语水平和计算机水平固然重要，但是翻译凭借的不是傲慢与偏见，不是苦难哲学，也不是泥潭般的社区，更不是所谓的巨苣，而是我们的心，翻译是用心来完成的！用心，每个人都可以参与，无论是错别字的修正还是大章节的翻译，都是有意义的。
>
> 想参加的朋友可以看看 [https://docs.qq.com/doc/DSUtxYmVwU29EdGVn](https://docs.qq.com/doc/DSUtxYmVwU29EdGVn)

### FreeBSD 中文社区的愿景

我们成立于 2018年3月17日，由贴吧——FreeBSD 吧发展到了 QQ 群（主群 787969044），Telegram 群，乃至于微信群。

我们的成员具有非常大的广泛性和普遍性，能够代表绝大多数 FreeBSD 用户的平均水平：可能根本没有听说过何为 FreeBSD，但这并不影响我们的交流与沟通。也许有人觉得这是浪费时间，但是没有新生力量的培养，何来 FreeBSD 的明天呢？谁不知道新人可能有很多坏习惯呢。

同鲁迅先生说的那样，但愿每个人都是一束光，照亮 FreeBSD 在中国大陆地区前进的光荣的荆棘路。也希望，你可以加入我们，共同组成漫天星光亦或者是星星之火。

无穷的远方，无数的人们，都和我有关。

我曾无数次眺望远山，想要找到一汪清泉，天总是不随人愿，还是没有找到。

我是谁，我们是谁？这个问题永远也不会有结果。

我们选择 FreeBSD，是因为想选择一个清晰、明了、可靠、稳固的一个操作系统在工作上给我们带来收益以及在生活中给我们带来乐趣。当然 FreeBSD 还存在很多问题，有待大家积极发现、探讨、完善，社会在进步，技术在进步，热情丝毫不减在持续，未来越来越美好。

### 黑名单

在建设 FreeBSD 中文社区的时候我们遇到了许多困难：一些 Arch linux 邪教分子的恶意挑衅，上来就说“Arch 牛逼！”；还有一些完全没有使用过 BSD 的人，张口闭口就说 FreeBSD 没有 JAVA、没有 JNI，更没有 Eclipse；还有部分华为花粉进入社区故意借套壳安卓的鸿蒙系统，试图引发内讧。为了社区，我们建立了黑名单制度。

名单如下：

#### 2018-2021

|    QQ 号    |                                                                                                                                                                                                                                              黑名单原因                                                                                                                                                                                                                                             |
| :--------: | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
| 3623404390 |                                                                                                                                                                                                                                        过河拆桥，得到问题答案就退群，下同                                                                                                                                                                                                                                       |
|  554412630 |                                                                                                                                                                                                                  管理员为了高考学子安心备考，在高考前夕，给每个面临高考的学生都送上了高考大礼包（权限到高考结束），但他却为了逃避权限退群                                                                                                                                                                                                                  |
|   1354998  |                                                                                                                                                                                                                                        侮辱 BSD 且推广 Linux                                                                                                                                                                                                                                        |
|  156798543 |                                                                                                                                                                                                                                              寻衅滋事                                                                                                                                                                                                                                              |
| 1113749776 |                                                                                                                                                                                                                                            过河拆桥，华为海狗                                                                                                                                                                                                                                           |
| 2151722905 | 进群胡言乱语装萌新，装傻充愣，名字叫数据库，疑似一个人工智能，擅长问一些乱七八糟的拼凑起来的不存在的问题：比如 `汇编语言 c 语言之间，存在一门语言。被忽略了。整个IT界失去了一次另外发展的模式。` 再比如 `数据库表之一行记录，是可看做，某个函数的参数么？这个函数名，为什么没出现在这条记录行？是省略了函数名么？它以这个表做参数吗？它用这个表的数据流做参数吗？`又比如`编程语言，可能可以不依赖代数 不依赖几何 在更广阔的观点，编程语言可以构造代数 构造几何。只不过，暂时还没想透彻。` 和 `框架 ，是什么 ？ 是设备吗？在 看vue 对列 ，是设备吗？为什么，去电脑城，可以买到cpu 内存条 磁盘。买不到 对列？` 以及 `假设println() 是服务性函数与main一起启动不会关闭。参数流 随时可以 写入。传统对于函数的解释，可能是错误的。实用性 可行性掩盖了粗糙性荒谬性。很可能 ，函数禁用名称 函数禁用注释，才是对劲的。（不过，现在的实用观点不允许这么说这么做）。函数无名化，函数去注释，现实无法接受。` 如需更多，请提交 issue |
|  504658598 |                                                                                                                                                                                                                                               骂人                                                                                                                                                                                                                                               |
| 3458921559 |                                                                                                                                                          侮辱 BSD 且推广 `ArchLinux` ，认为 BSD 没有 `JAVA`、没有 `JNI`、没有 `Eclipse` 等，总之他的意思就是 FreeBSD 什么都没有，是个垃圾。拿出来被打脸又东拉西扯开始挑衅管理员，外号叫彩虹海盗，现在叫“大明酱”，精日分子，其 github 地址为 https://github.com/mingmoe                                                                                                                                                         |
|   2018456  |                                                                                                                                                                                                                                          侮辱 BSD，挑衅管理员                                                                                                                                                                                                                                          |
|  383925617 |                                                                                                                                                                                                                                           华为海狗，侮辱管理员                                                                                                                                                                                                                                           |
| 1510908166 |                                                                                                                                                                                                                                              过河拆桥                                                                                                                                                                                                                                              |
| 1771336464 |                                                                                                                                                                                                                                              寻衅滋事                                                                                                                                                                                                                                              |
|  595063679 |                                                                                                                                                                                                                       民科民哲。提出与常识不符的文史哲观点，认为金字塔是水泥造的，认为外国历史都是虚假的，我大天朝的才是正史                                                                                                                                                                                                                      |
|  273457914 |                                                                                                                                                                                                                 民科民哲。提出与常识不符的文史哲观点，不认识阿拉伯百年翻译运动就敢妄论西欧历史，且无视近现代科学发轫于西方哲学之事实，宣称同上                                                                                                                                                                                                                |
|  571060051 |                                                                                                                                                                                                                                 屡次阴阳怪气破坏氛围，每当有人挑衅管理员就出来表演，添油加醋                                                                                                                                                                                                                                 |
| 3303672033 |                                                                                                                                    开源邪教，擅长苦难哲学，自以为是，半瓶水晃荡，认为 `LaTeX` 在写小说方面优于 `Word`，认为 `libreoffice` 不应该兼容 `Word`，应该反过来由 `Word` 去兼容他，经典语录"你凭什么说 Libreoffice 兼容性不好?"，“你为什么不用 GIMP？为什么用 PS”，“你为什么用 Windows 10”。侮辱挑衅管理员，擅长各种举报打小报告（12321 等），造成前管理员手机号被封（目前已解）                                                                                                                                    |

| 微信名称 |             黑名单原因            |
| :--: | :--------------------------: |
| 彩虹海盗 | 侮辱 BSD 且推广 `ArchLinux`。其他同上 |

|  贴吧 ID  |                       黑名单原因                      |
| :-----: | :----------------------------------------------: |
| mechrtt | 挑衅管理员，用他人教程冒充自己写的教程，无耻至极。被识破后恼羞成怒辱骂管理员是中专生（他看不起） |

#### 2022

|    QQ 号    |                                                                                                                                                                                                 黑名单原因                                                                                                                                                                                                |
| :--------: | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
| 1187908617 |                                                                                                                           自以为是。Ubuntu 吧前吧主。一个活在自己的世界的人而已，以为世界得围着他转，让别人下台就下台，都得听他的。有一点权力就把他发挥到极致，更妄论自己没权。经典语录：“要么恢复帖子 要么下台”；被戳穿后：“我只是建议你轻松点而已”；小号众多，最是擅长挑拨离间，是典型的占着茅坑不拉屎的菊苣                                                                                                                           |
| 2777184456 |                                                                                                                                                                                        无视 FreeBSD 推广之成果，视之为广告                                                                                                                                                                                        |
|   1301771  |                                                                                                                                                                                          故意违反群规第 8 条之规定，畏罪潜逃                                                                                                                                                                                         |
|  369866382 | 曾经说自己无比热爱 FreeBSD，要参与社区工作，经过询问本人意见，给他分配了翻译 Handbook 的任务。过了很久很久说自己没时间干了，也不说理由，然后一看进度只翻译了一个小的章节还是多少来着，总之都还没有完成，问他能不能完成的小章节，他坚决地说“不”，在支付了其一个章节的翻译奖励之后就不在微信群说话了。然后某日在 QQ 群里说跑路教程不应该给 sddm 添加什么 root 教程，显得很低端，然后说自己从来不这么用，意思是也不让别人这么用。就好比那些自己不用 QQ 也不让别人用的人一样，但是他还是老老实实地用了微信，和我说这叫“工作需要”。之后又在群里找茬，说翻译文档没有任何意义，傻逼才会参与，FreeBSD 就是个垃圾之类的话。被移出群后，一看原来是微信群的那个人——占戈哥欠，目前该人已经混入了其他的 FreeBSD 社区。不反对我们的工作是继续在群里的底线 |
|   9516665  |                                                                                                                                                                                 装傻充愣，疑似 1301771，提示：QQ 位数小于 8 位数的多半有问题                                                                                                                                                                                |
|  428819551 |                                                                                                                                                                                             拒绝问卷，伸手党，侮辱社区                                                                                                                                                                                            |
| 3142739069 |                                                                                                                                                                                              拒绝遵守 CFC 章程                                                                                                                                                                                             |

| 微信名称 |     黑名单原因    |
| :--: | :----------: |
| 占戈哥欠 | 369866382 的号 |
|      |              |

| 贴吧 ID | 黑名单原因 |
| :---: | :---: |
|       |       |
|       |       |
|       |       |

希望各大开源社区引以为戒，小心上述人员的恶意破坏。黑名单用户不可解封。
