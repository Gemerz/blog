title: tvOS, tizen  与 webos 路在何况 ？
date: 2020-08-28
author: Gemer
categories:
- travel
tags: [tizen,webos]

--------

在如今看，tizen与webos这对韩国半代工技术的电视平台的由于廉价的原因，可以说在电视OS的如手机的apple与google两家阵型，但是随着技术的发展，加上apple OS与andoird TV的发力，在全球份额来说，Samsung与LG的份额也随着减少与被挑战，而更有趣的方面是，samsung随着手机市场的失控，近来的TV的tizen可说的没有什么突破，更严重来说，一直就那里，反观，LG上，技术由于一定利用开源linux做为基核，随着来说，体验稳定，稍为有好转，份额有所增加，但是这对难受在2020第一季节占根据statista的市场调查数据显示，tizen为11%, webos为 7%。
从2019年在公司所有看到tizen 15%，webos为6%的信息，tizen是有所下降的。

![WX20201130-141931@2x](https://user-images.githubusercontent.com/60084718/100586429-1cd07a80-332a-11eb-8c6f-8ea8c48427af.png)


以下从技术发展来谈谈这对这两平台发展方向：




## 技术体系：

|       | Samsung tizen           | LG Webos          | 总结|
|----------|-------------------------|-------------------|------ |
| 开发语言 | 1\. Web/js 2.native C++ | 1.Web/js 2.QT QML  | C++/QML有难度 市场偏少，总体是以js开发为主,人工成本低| |
| 开发IDE | Tizen studio  | None | Tizen studio是eclispe二次开发，内存性能不足，证书配置难度大，要samsung account (3.7),不建议以Tizen开发 |
| 开发及开发者周边   |  官方文档，社区开发帮助不大，欠维护      | 官方文档，有开源OSE, github上多个方向 | 大部分在stackflow有相关 |
| 开发调试 |  有新开发工具wits   |   有ares-cli  | 调试相对低来说， LG更显得理念好一些，都有自家的CLI| |
| 模似器  |  都是基本java的vitrual linux image  |  都是基本java的vitrual linux image  | 模似器除旧，与真机出入都很大，对于官方部doc spec有效 建议大多数真机 |



### 以上是两个平台的技术要数：

#### Samsung
 samsung的自家播放avplayer 可以讲各种问题，buffer 与codec的MSE各版本不一，假如片源有许多不一的flag, 或者没有自己HLS的优化体系，在三星可以讲各种小问题出现。

### LG
总体来说，对开源的播放器支持的蛮好的。




## 上线周期：

由于三星与LG都是同一样市场合作模式，因为电视都是parent合作模式，都是使用人工QA模式，所以上线从提交到发布最起码在一个月间，假如中途取消，要起码一个月为计数。



# 总结

由全球的OTT团队中都是他们的合作伙伴，以AWS，GOOGLE, NETFLEX, flex, disney都是他们的顶级合作伙伴，留意到是这些顶级合作伙伴的QA是比我现在的团队快出半个月时间左右。对于这两平台的前景发展及分析，大部分都只是到维持这个产品完整度的一个水平，随着技术的更新，加上电视的寿命的周期长，导致技术更新水平过慢。

但是近年从sony转战androidTV平台，及samsung自家也有意放弃，未来一定在tizen平台慢慢放弃。

反观APPLE TV+以及google也有意对TV的增加资源，我觉得更重要的一点，现行这两家技术难以支持往后4K或6K，8K的时代，apple与google TV的market现在也有各种审核机制可能对mobile来说是delay那一两天时间，所以从技术与市场及准入管理来说，apple与google TV的份额一定逐年提高。


## 国内：
 因为由于我们国内的布局好，现行是android自家定制的独大，appleTV的没有进入加上版权问题，也有tencent与芒果TV布局这两个小市场，但国内的审核机制也应该如此。
 
 
 以上只个人一些理解， 这两平台会随着技术更新与慢慢淡去。



 

