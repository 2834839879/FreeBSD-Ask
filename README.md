# FreeBSD 从入门到跑路

## 概述

(↓↓↓ 正文阅读请点击下方的项目预览 ↓↓↓)

[项目预览——如果你认为拼音显得奇怪，那么你应该点击此处。](https://book.freebsdcn.org)

PDF 请点击 “[Release](https://github.com/FreeBSD-Ask/FreeBSD-Ask/releases)”下载。请注意，PDF 仅供参考，且存在这样或那样的问题，应该以在线版本为主。

### 本书定位

我们的目标并非是 Handbook 的翻译，而是编写一本类似于《鸟哥的 Linux 私房菜：基础学习篇》+《鸟哥的 Linux 私房菜：服务器架设篇》二合一的基于 FreeBSD 的教程。也就说我们是 Handbook 的超集。

### 编辑指南概要

我们欢迎所有支持 FreeBSD 的人进行编写，并会将您添加到贡献者名单当中。

[详细的编辑指南，点击此处](https://github.com/FreeBSD-Ask/FreeBSD-Ask/wiki)。

## 前言

### FreeBSD 从入门到跑路

本书诞生于 2021 年 12 月 19 日。编写目的是为了促进 FreeBSD 的中国化与世界化。编写内容为 FreeBSD 的基础与高阶知识。对于章节安排，如果你有一定的计算机基础可以跳过第 〇 章，如果你对 FreeBSD 有一定认识，欢迎你加入我们一起编写本书，贡献自己的力量。

### 内容提要

本书是由道长发起，并由 FreeBSD QQ 群 731675387 的一些群成员参与编写的《FreeBSD 从入门到跑路》。我们尝试从 0 开始，带领普通人走进 FreeBSD 世界，充分参考了 FreeBSD Handbook，构建了一个完整、科学的目录体系。本书不是一个教程的大杂烩亦或者是大集合，而是为了构建一个自成体系的一本开源书籍。全书共分二十九章，既强调了学习 FreeBSD 的必要基础也提供了内核设计与实现等专业性较强的教程。本书可作为高等学校“FreeBSD 操作系统”课程的本科生教材，同时也适合相关专业研究生或计算机技术人员参考阅读。

### 开源维护与捐赠

![](.gitbook/assets/proud_donor.gif)

[点此捐赠 FreeBSD 基金会](https://freebsdfoundation.org/donate)。

为了能够更好地维护本书，我们采用了 Gitbook 平台来进行协作。对于无法直接从 GitBook 导出为 PDF 的问题（我们提供了 PDF 的参考版本于 release），我们深感抱歉，我们目前没有财力为其提供所需要的企业版本（15 刀一个月）。如果您想为我们提供捐助，请加入我们的 [TG 群](https://t.me/freebsdba) 或者 QQ 群 731675387。 如果您也想参与编写，具体请参考 [WIKI](https://github.com/FreeBSD-Ask/FreeBSD-Ask/wiki/%E3%80%8AFreeBSD-%E4%BB%8E%E5%85%A5%E9%97%A8%E5%88%B0%E8%B7%91%E8%B7%AF%E3%80%8B%E7%BC%96%E8%BE%91%E6%8C%87%E5%8D%97)，关于贡献者名单请参考 第一章 第九节。

**捐赠者:**

2018-2022

以捐献时间为排序。

|用户名|金额(¥)|用途/金额结余(¥)|
|:---:|:---:|:---:|
|喜哥|100|30/70 用于`freebsdcn.org`域名（2021年度）|
|顾白（微信赞赏）|5|35|
|顾雨欣|1|36|
|鸭子 OS|1|37|
|星辰（顾白代捐）|1|38|
|邱队长102|20|58|
|bsd.so|100|158|
|星辰|2|160|
|凤淋|51.22|211.22|
|星辰|1.78|213|
|风风火火小白狼|66|80/204，其中70 用于域名`freebsdcn.org`，129 用于向 FreeBSD 基金会捐款|
|夏文纯一|10|90|
|施主|50|140|
|UniqueDing|20|160|
|耶梦加得|20|180|
|bsd.so|6.66|186.66|
|天之道|50|236.66|
|陈杉|1|237.66|
|QQ 大冰|1|238.66|
|肖语文 |100|338.66|
|王刚|300|638.66|
|andreas|50|688.66|
|🤗空空兒 ㄉㄠ ㄆㄨ🤗(微信赞赏）|9|697.66|
|bsd.so|6.66|704.32|
|星辰|0.01|704.33|
|Apple_QAQ|1.82|706.15|
|星辰、顾雨欣、顾白|0.03|706.18|
|爱睡觉的蘑菇|0.01|706.19|
|Lin🌠 |1|707.19|
|沁阳市-裴亚非 |20|0.19 新年红包/727|
|墨青|100|827|
|顾白|1|828|
|顾雨欣|1.85|0.85 新年抽奖/829|
|咕咕咕咕|50|879|
|笨小孩|50|929|
|顾白、顾雨欣|2|931|

### 激励计划

代理，bhyve，jail，zfs，UFS，dtrace，GEOM、第十六章 服务器

向大家公开征集以上章节的教程，以完善 https://book.freebsdcn.org 这本书。

要求内容正确完整清晰，遵守编写 wiki 规范。章节划分以我们的目录为准。参考部分应该给出原地址，不得抄袭他人假作原创。

奖励标准是：20 元一节，编写 3 节（不含）以上每节按 30 元计算，上不封顶。征集活动长期有效，以提供先后顺序为准，先到先得。教程直接 Pull 或者群内私聊管理员均可。

### 意见反馈

由于编写者水平所限，书中缺点和谬误之处自不可免，希望同志们随时提出批评意见，以便修正。您可以利用 Github 的各种交互功能与我们联系：提交 Issue、Pull request 或者加入 QQ 群或 TG 群直接联系（yklaxds AT gmail DOT com）等。

### TODO / Wishlist

后续还有很多需要完善的工作，包括不限于:

* 完善教程
* 整理和上传配置文件和环境
* 对教程的格式目录进行优化调整
* 积极对外宣传并寻求正式出版

### 许可证

本书采用 [BSD-3-Clause License](LICENSE/) 许可证开源。我们在编写过程吸收了一些现有的研究成果，在此表示感谢。引用本书内容时，请务必留下我们的原地址——https://book.freebsdcn.org 及署名——FreeBSD 中文社区。

### 其他

同名小说：起点网——[《FreeBSD从入门到跑路》](https://book.qidian.com/info/1031738676)&#x20;

[FreeBSD Handbook deepl 机器翻译项目](https://handbook.freebsdcn.org)

微信公众号: freebsdzh （扫码关注）

![](.gitbook/assets/qrcode_for_gh_3b263cc9b20b_258.jpg)

## 关于

### FreeBSD 中文社区的愿景

我们成立于 2018年3月17日。由贴吧——FreeBSD 吧发展到了 QQ 群（主群 731675387），Telegram 群，乃至于微信群。

我们的成员具有非常大的广泛性和普遍性，能够代表绝大多数 FreeBSD 用户的平均水平：可能根本没有听说过何为 FreeBSD，但这并不影响我们的交流与沟通，也许有人觉得这是浪费时间，但是没有新生力量的培养，何来 FreeBSD 的明天呢？谁不知道新人可能有很多坏习惯呢。

同鲁迅先生说的那样，但愿每个人都是一束光，照亮 FreeBSD 在中国大陆地区前进的光荣的荆棘路。也希望，你可以加入我们，共同组成漫天星光亦或者是星星之火。

无穷的远方，无数的人们，都和我有关。

我曾无数次眺望远山，想要找到一汪清泉，天总是不随人愿，还是没有找到。

我是谁，我们是谁？这个问题永远也不会有结果。

我们选择 FreeBSD，是因为想选择一个清晰、明了、可靠、稳固的一个操作系统在工作上给我们带来收益以及在生活中给我们带来乐趣。当然 FreeBSD 还存在很多问题，有待大家积极发现、探讨、完善，社会在进步，技术在进步，热情丝毫不减在持续，未来越来越美好。

### 黑名单

在建设 FreeBSD 中文社区的时候我们遇到了许多困难：一些 Arch linux 邪教分子的恶意挑衅，上来就说“Arch 牛逼！”；还有一些完全没有使用过 BSD 的人，张口就说 FreeBSD 没有 JAVA、没有 JNI，更没有 Eclipse；还有部分华为花粉进入社区故意借套壳安卓的鸿蒙系统，试图引发内讧。为了社区，我们建立了黑名单制度。

名单如下：

#### 2018-2021

|QQ 号|  黑名单原因|
| :---: | :---: |
| 3623404390 |过河拆桥，得到问题答案就退群，下同|
|  554412630 |管理员为了高考学子安心备考，在高考前夕，给每个面临高考的学生都送上了高考大礼包（权限到高考结束），但他却为了逃避权限退群  |
|   1354998  |侮辱 BSD 且推广 Linux |
|  156798543 |寻衅滋事|
| 1113749776 |过河拆桥，华为海狗|
| 2151722905 |进群胡言乱语装萌新，装傻充愣，名字叫数据库，疑似一个人工智能，擅长问一些乱七八糟的拼凑起来的不存在的问题：比如`汇编语言 c 语言之间，存在一门语言。被忽略了。整个IT界失去了一次另外发展的模式。`再比如`数据库表之一行记录，是可看做，某个函数的参数么？这个函数名，为什么没出现在这条记录行？是省略了函数名么？它以这个表做参数吗？它用这个表的数据流做参数吗？`又比如`编程语言，可能可以不依赖代数 不依赖几何 在更广阔的观点，编程语言可以构造代数 构造几何。只不过，暂时还没想透彻。`和`框架 ， 是什么 ？ 是设备吗？在 看vue 对列 ，是设备吗？为什么，去电脑城，可以买到cpu 内存条 磁盘。买不到 对列？`以及`假设println() 是服务性函数与main一起启动不会关闭。参数流 随时可以 写入。传统对于函数的解释，可能是错误的。实用性 可行性掩盖了粗糙性荒谬性。很可能 ，函数禁用名称 函数禁用注释，才是对劲的。（不过，现在的实用观点不允许这么说这么做）。函数无名化，函数去注释，现实无法接受。`如需更多，请提交 issue |
|  504658598 |骂人|
| 3458921559 |侮辱 BSD 且推广`ArchLinux`，认为 BSD 没有`JAVA`、没有`JNI`、没有`Eclipse`等，总之他的意思就是 FreeBSD 什么都没有，是个垃圾。拿出来被打脸又东拉西扯开始挑衅管理员，外号叫彩虹海盗，现在叫“大明酱”，精日分子，其 github 地址为 https://github.com/mingmoe |
|   2018456  |侮辱 BSD，挑衅管理员|
|  383925617 |华为海狗，侮辱管理员|
| 1510908166 |过河拆桥|
| 1771336464 |寻衅滋事|
|  595063679 |民科民哲。提出与常识不符的文史哲观点，认为金字塔是水泥造的，认为外国历史都是虚假的，我大天朝的才是正史|
|  273457914 |民科民哲。提出与常识不符的文史哲观点，不认识阿拉伯百年翻译运动就敢妄论西欧历史，且无视近现代科学发轫于西方哲学之事实，宣称同上  |
|  571060051 |屡次阴阳怪气破坏氛围，每当有人挑衅管理员就出来表演，添油加醋 |
| 3303672033 |开源邪教，擅长苦难哲学，自以为是，半瓶水晃荡，认为`LaTeX`在写小说方面优于`Word`，认为`libreoffice`不应该兼容`Word`，应该反过来由`Word`去兼容他，经典语录"你凭什么说 Libreoffice 兼容性不好?"，“你为什么不用 GIMP？为什么用 PS”，“你为什么用 Windows 10”。侮辱挑衅管理员，擅长各种举报打小报告（12321 等），造成管理员手机号被封（目前已解）|

| 微信名称 |黑名单原因|
| :---: | :---: |
| 彩虹海盗 | 侮辱 BSD 且推广`ArchLinux`。其他同上 |

| 贴吧 ID  |黑名单原因|
| :----: | :---: |
| mechrtt | 挑衅管理员，用他人教程冒充自己写的教程，无耻至极。被识破后恼羞成怒辱骂管理员是中专生（他看不起） |

#### 2022

|  QQ 号|  黑名单原因  |
| :---: | :---: |
| 1187908617 | 自以为是。Ubuntu 吧前吧主。一个活在自己的世界的人而已，以为世界得围着他转，让别人下台就下台，都得听他的。有一点权力就把他发挥到极致，更妄论自己没权。经典语录：“要么恢复帖子 要么下台”；被戳穿后：“我只是建议你轻松点而已”；小号众多，最是擅长挑拨离间，是典型的占着茅坑不拉屎的菊苣|
| 2777184456 | 无视 FreeBSD 推广之成果，视之为广告|
|            |     |
|            |     |
|            |     |

| 微信名称 | 黑名单原因 |
| :---: | :---: |
|      |       |
|      |       |

| 贴吧 ID | 黑名单原因 |
| :---: | :---: |
|       |       |
|       |       |
|       |       |

希望各大论坛 QQ 群社区引以为戒，小心上述人员的恶意破坏。黑名单用户不可解封。
