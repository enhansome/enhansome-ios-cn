# Awesome iOS资源大全中文版 with stars

我想很多程序员应该记得 GitHub 上有一个 Awesome - XXX 系列的资源整理。[awesome-ios](https://github.com/vsouza/awesome-ios) ⭐ 53,230 | 🐛 25 | 🌐 Swift | 📅 2026-08-27 就是 vsouza 发起维护的 iOS 资源列表，内容包括：框架、组件、测试、Apple Store、SDK、XCode、网站、书籍等。Swift 语言写成的项目会被标记为 ★ ，AppleWatch 的项目则会被标记为 ▲。

Awesome 系列虽然挺全，但基本只对收录的资源做了极为简要的介绍，如果有更详细的中文介绍，对相应开发者的帮助会更大。这也是我们发起这个开源项目的初衷。

***

### 我们要做什么？

* 基于 awesome-ios 资源列表，我们将对各个资源项进行编译整理。
* 整理后的内容，将收录在[伯乐在线资源频道](http://hao.importnew.com/)。可参考已整理的内容：
  * 《[BlockAlertsAnd-ActionSheets：一个支持block的弹出框](http://hao.importnew.com/blockalertsand-actionsheets-ios/)》
  * 《[MBProgressHUD：一个不错的进度提示工具](http://hao.importnew.com/mbprogresshud-ios/)》
  * 《[Wonderful：不仅仅是一个酷炫的颜色库](http://hao.importnew.com/wonderful/)》

***

### 如何参与本项目？

<!-- 从下面的目录来看，本项目的工作量小不了，所以非常期待能有更多程序员一起来参与。

不过加入前，有几个小要求：

* 英文还不错，能读懂英文并用自己的话复述；
* 有 iOS 开发经验；

如有兴趣，请加 QQ：50872495。加 Q 时请注明「iOS大全」 -->

***

### 如何为列表贡献新资源？

欢迎大家为列表贡献高质量的新资源，提交PR时请参照以下要求：

* 请确保推荐的资源自己使用过
* 提交PR时请注明推荐理由

资源列表管理收到PR请求后，会定期（每周）在微博转发本周提交的PR列表，并在微博上面听取使用过这些资源的意见。确认通过后，会加入资源大全。

感谢您的贡献！

***

### 本项目的参与者

* 维护者：[tangyouhua](https://github.com/tangyouhua)

* 贡献者：[ARIGATO](https://github.com/ufolux)、[星满苍穹](http://www.importnew.com/members/zhuimengren0807004/)、[天道](http://hao.importnew.com/sound-fader-ios/)、[
  huanghui1](https://github.com/huanghui1)、[Haer不变](http://www.importnew.com/members/liushivae)、[徐健](http://www.importnew.com/members/Xcoderj/)、[西西里的仔仔](http://www.importnew.com/members/1595331303/)、[朱亚光在push的日常](http://www.importnew.com/members/2055497477/)、[zjszyms](https://github.com/zjszyms)、[patchthecode](https://github.com/patchthecode)、[KevinGong2013](https://github.com/KevinGong2013)、[张发白](http://www.importnew.com/members/shuai265/)、[冰斌](http://www.importnew.com/members/libing1209/)、[Juliesand](http://www.importnew.com/members/juliesh/)、[张发白](http://hao.importnew.com/hardcoredata/)、[yixiangboy](https://github.com/yixiangboy)

注：名单不分排名，不定期补充更新

***

<!-- ### 奖励计划

虽然奖励可能并不是你加入的主要原因，但还是有必要提一下：

* 整理超过 20 个资源后，可在伯乐在线上开通打赏；
* 每整理 20 个资源，有机会获得技术书籍或各种有意思的创意、极客产品；
* [奖励详情](http://hao.importnew.com/rewards/)

* * * -->

### 目录

* [入门](#getting-started)
* [库和框架](#libraries-and-frameworks)
  * [音频](#audio)
  * [动画](#animation)
  * [Apple TV](#apple-tv)
  * [桥接](#bridging)
  * [缓存](#cache)
  * [Core Data](#core-data)
  * [图表](#charts)
  * [数据库](#database)
  * [硬件](#hardware)
    * [动作](#motion)
    * [蓝牙](#bluetooth)
    * [位置](#location)
    * [iBeacon](#ibeacon)
  * [HUD](#hud)
  * [事件总线（ EventBus ）](#eventbus)
  * [文件](#files)
  * [JSON](#json)
  * [布局](#layout)
  * [日志](#logging)
  * [地图](#maps)
  * [媒体](#media)
    * [图片](#image)
    * [视频](#video)
    * [PDF](#pdf)
  * [消息](#messaging)
  * [网络](#networking)
  * [推送通知](#push-notifications)
  * [Passbook](#passbook)
  * [权限](#permissions)
  * [文本](#text)
  * [浏览 / 介绍 / 教程](#walkthrough--intro--tutorial)
  * [URL Scheme](#url-scheme)
  * [UI](#ui)
  * [Websocket](#websocket)
  * [代码质量](#code-quality)
  * [分析](#analytics)
  * [支付](#payments)
  * [产品化工具](#products)
  * [实用工具](#utility)
  * [安全](#security)
* [安装项目](#project-setup)
* [依赖 / 包管理](#dependency--package-manager)
* [测试](#testing)
  * [测试驱动开发（TDD） / 行为驱动开发（BDD）](#tdd--bdd)
  * [UI测试](#ui-testing)
  * [Beta 测试](#beta-distribution)
  * [其他测试](#other-testing)
* [工具链](#toolchains)
* [工具](#tools)
* [敏捷开发](#rapid-development)
* [部署](#deployment)
* [App Store](#app-store)
* [SDK](#sdk)
* [Xcode](#xcode)
  * [插件](#plugins)
  * [主题](#themes)
  * [其他 Xcode 相关](#other-xcode)
* [编码规范](#style-guides "编码规范")
* [一些好网站](#good-websites)
  * [新闻, 博客等](#news-blogs-and-more)
  * [UIKIt 文档](#uikit-references)
  * [论坛和讨论列表](#forums-and-discuss-lists)
  * [教程和 Keynotes](#tutorials-and-keynotes)
  * [原型](#prototyping)
* [Twitter](#twitter)
* [Facebook 群组](#facebook-groups)
* [播客（Podcasts）](#podcasts)
* [书籍](#books)
* [其他优秀的列表](#other-awesome-lists)
* [资源](#resources)

# <a name="getting-started"></a>入门

* Road Map iOS：开发 iOS 应用从今天开始，苹果指南。★[官网](https://developer.apple.com/library/prerelease/ios/referencelibrary/GettingStarted/DevelopiOSAppsSwift/)
* Lifehacker：我想写一个 iOS 应用，该从哪里开始？[官网](http://lifehacker.com/i-want-to-write-ios-apps-where-do-i-start-1644802175)
* Codeproject：入门 iPhone 和 iOS 应用开发。[官网](http://www.codeproject.com/Articles/88929/Getting-Started-with-iPhone-and-iOS-Development)
* Ray Wenderlich：学习 iOS 应用开发。[官网](http://www.raywenderlich.com/38557/learn-to-code-ios-apps-1-welcome-to-programming)
* Stanford：Developing Apps to iOS：斯坦福在 iTunes U 上的 iOS App 开发课程（音频和视频）。[官网](https://itunes.apple.com/us/itunes-u/developing-apps-for-ios-hd/id395605774?mt=10)
* Stanford：Developing iOS 8 Apps with Swift：斯坦福在 iTunes U 上用 Swift 开发 App 的课程（2015版）。★[官网](https://itunes.apple.com/us/course/developing-ios-8-apps-swift/id961180099)

# <a name="libraries-and-frameworks"></a>库和框架

### <a name="audio"></a>音频

* [AudioKit](http://hao.importnew.com/audiokit/)：一个强大的音频合成，处理和分析的工具集。[官网](https://github.com/audiokit/AudioKit) ⭐ 11,453 | 🐛 6 | 🌐 Swift | 📅 2026-07-26
* [EZAudio](http://hao.importnew.com/ezaudio/)：一个基于 Core Audio 的 iOS/OSX 音频可视化框架。用于实时，低延迟的音频处理和可视化功能的开发。[官网](https://github.com/syedhali/EZAudio) ⭐ 4,981 | 🐛 196 | 🌐 Objective-C | 📅 2025-09-09
* [TheAmazingAudioEngine](http://hao.importnew.com/theamazingaudioengine/)：是iOS音频处理框架，简单易用，能对音频进行处理。[官网](https://github.com/TheAmazingAudioEngine/TheAmazingAudioEngine) ⭐ 3,076 | 🐛 59 | 🌐 Objective-C | 📅 2021-05-19
* [StreamingKit](http://hao.importnew.com/streamingkit/)：一个针对 OSX 和 iOS 中 `AudioPlayer/AudioStreamer` 快捷的无缝扩展。[官网](https://github.com/tumtumtum/StreamingKit) ⭐ 2,448 | 🐛 204 | 🌐 Objective-C | 📅 2022-05-31
* [novocaine](http://hao.importnew.com/novocaine/)：应用于 OSX 和 iOS 的高性能音频框架。[官网](https://github.com/alexbw/novocaine) ⭐ 2,232 | 🐛 48 | 🌐 Objective-C | 📅 2018-11-28
* [sound-fader-ios](http://hao.importnew.com/sound-fader-ios/)：一个 Swift 写的 `AVAudioPlayer` 的声音控制器 [官网](https://github.com/evgenyneu/sound-fader-ios) ⭐ 114 | 🐛 3 | 🌐 Swift | 📅 2019-04-20★
* [QHSpeechSynthesizerQueue](http://hao.importnew.com/qhspeechsynthesizerqueue/)：一个 `AVSpeechSynthesizer`（iOS文本发音） 的队列管理系统。[官网](https://github.com/quentinhayot/QHSpeechSynthesizerQueue) ⭐ 43 | 🐛 0 | 🌐 Objective-C | 📅 2017-12-20
* [AudioBus](http://hao.importnew.com/audiobu/)：下一代 App 到 App 的实时音频路由。[官网](https://developer.audiob.us/)

### 动画

* [Pop](http://hao.importnew.com/pop/)：一个 iOS 和 OS X 动画库，可以方便地实现由物理效果的交互。[官网](https://github.com/facebook/pop) ⚠️ Archived
* [Spring](http://hao.importnew.com/spring_ios/)：一个简单的 Swift iOS 动画库。[官网](https://github.com/MengTo/Spring) ⭐ 14,054 | 🐛 164 | 🌐 Swift | 📅 2023-07-03
* [Canvas](http://hao.importnew.com/canvas/)：无需代码就可以在 Xcode 中显示动画 <http://canvaspod.io>。[官网](https://github.com/CanvasPod/Canvas) ⭐ 5,276 | 🐛 37 | 🌐 Objective-C | 📅 2019-07-14
* [RZTransitions](http://hao.importnew.com/rztransitions/)：iOS View Controller 过场动画库。[官网](https://github.com/Raizlabs/RZTransitions) ⭐ 1,860 | 🐛 11 | 🌐 Objective-C | 📅 2020-02-06
* [AnimationEngine](http://hao.importnew.com/animationengine/)：可以在 iOS 上方便地构建高级自定义动画。[官网](https://github.com/intuit/AnimationEngine) ⚠️ Archived
* [Awesome-iOS-Animation](http://hao.importnew.com/awesome-ios-animation/)：一个动画项目的集合。[官网](https://github.com/jackyzh/awesome-ios-animation) ⭐ 893 | 🐛 0 | 📅 2017-04-17
* [DCAnimationKit](http://hao.importnew.com/dcanimationkit/)：iOS 动画集合。很简单，只需要添加流水动画。[官网](https://github.com/daltoniam/DCAnimationKit) ⭐ 803 | 🐛 1 | 🌐 Objective-C | 📅 2016-02-09
* [Cheetah](http://hao.importnew.com/cheetah/)：便捷的 iOS 动画库，由 Swift2 编写。 ★[官网](https://github.com/suguru/Cheetah) ⭐ 586 | 🐛 8 | 🌐 Swift | 📅 2018-10-03
* [Fluent](http://hao.importnew.com/fluent/)：便捷的 Swift 动画框架。 ★[官网](https://github.com/matthewcheok/Fluent) ⭐ 293 | 🐛 1 | 🌐 Swift | 📅 2017-03-13
* [RadialLayer](http://hao.importnew.com/radiallayer/)：针对可点击元素的动画（类似于 Youtube Music）★[官网](https://github.com/soheil/RadialLayer) ⭐ 60 | 🐛 1 | 🌐 Swift | 📅 2015-11-21

### <a name="apple-tv"></a>Apple TV

* [Voucher](http://hao.importnew.com/voucher/)：方便 tvOS App 通过 iOS 设备上相应的程序来认证的库。[官网](https://github.com/rsattar/Voucher) ⭐ 511 | 🐛 7 | 🌐 Objective-C | 📅 2017-03-05

### <a name="bridging"></a>桥接

* [JSPatch](http://hao.importnew.com/jspatch/)：JSPatch 利用 Objective-C 运行时桥接了 Objective-C 和 Javascript。你仅需引入一个小的引擎，就可以使用 JS 调用任何 Objective-C 的类。JSPatch 通常用来对 iOS App 做热修复（hotfix）。[官网](https://github.com/bang590/JSPatch) ⭐ 11,331 | 🐛 106 | 🌐 Objective-C | 📅 2020-12-01

### <a name="cache"></a>缓存

* [Awesome Cache](http://hao.importnew.com/awesome-cache/)：让人喜爱的本地缓存 ★[官网](https://github.com/aschuch/AwesomeCache) ⭐ 1,266 | 🐛 36 | 🌐 Swift | 📅 2021-08-11
* [Carlos](http://hao.importnew.com/carlos/)：简单但却灵活的缓存 ★[官网](https://github.com/WeltN24/Carlos) ⚠️ Archived
* [SDURLCache](http://hao.importnew.com/sdurlcache/)：URLCache的子类，可以为 iPhone/iPad 应用提供的本地磁盘缓存。[官网](https://github.com/steipete/SDURLCache) ⚠️ Archived
* [mattress](http://hao.importnew.com/mattress/)：iOS Web 内容的离线缓存 ★[官网](https://github.com/buzzfeed/mattress) ⭐ 519 | 🐛 4 | 🌐 Swift | 📅 2017-08-19

### <a name="charts"></a>图表

* [ios-charts](http://hao.importnew.com/ios-charts/)：一个强大的图表框架，[MPAndroidChart](https://github.com/PhilJay/MPAndroidChart) ⭐ 38,191 | 🐛 2,191 | 🌐 Java | 📅 2025-06-05 在 iOS 上的移植。★[官网](https://github.com/danielgindi/ios-charts) ⭐ 28,013 | 🐛 977 | 🌐 Swift | 📅 2026-03-07
* [PNChart](http://hao.importnew.com/pnchart/)：一个简单漂亮的图表库，Pinner 和 CoinsMan 的iOS客户端中使用了这个框架。[官网](https://github.com/kevinzhow/PNChart) ⭐ 9,645 | 🐛 173 | 🌐 Objective-C | 📅 2018-07-02
* [JBChartView](http://hao.importnew.com/jbchartview/)：基于 iOS 的图表库，包含折线图和直方图。[官网](https://github.com/Jawbone/JBChartView) ⭐ 3,701 | 🐛 10 | 🌐 Objective-C | 📅 2018-08-06
* [BEMSimpleLineGraph](http://hao.importnew.com/bemsimplelinegraph/)：优雅的折线图框架。[官网](https://github.com/Boris-Em/BEMSimpleLineGraph) ⚠️ Archived
* [XYPieChart](http://hao.importnew.com/xypiechart/)：一个有动画的饼图框架。[官网](https://github.com/xyfeng/XYPieChart) ⭐ 1,712 | 🐛 42 | 🌐 Objective-C | 📅 2016-03-18
* [TEAChart](http://hao.importnew.com/teachart/)：简单易用的 iOS 图表库。包括了贡献图、时钟图、直方图。[官网](https://github.com/xhacker/TEAChart) ⭐ 1,189 | 🐛 0 | 🌐 Objective-C | 📅 2017-11-17
* chartee：一个为移动平台设计的图表库。[官网](https://github.com/zhiyu/chartee) ⭐ 953 | 🐛 8 | 🌐 Objective-C | 📅 2015-12-24
* [FSLineChart](http://hao.importnew.com/fslinechart/)：一个 iOS 折线图库。[官网](https://github.com/ArthurGuibert/FSLineChart) ⭐ 844 | 🐛 15 | 🌐 Objective-C | 📅 2017-08-09
* [EChart](http://hao.importnew.com/ios-echart/)：iOS/iPhone/iPad 图表。提供了事件处理和动画支持。[官网](https://github.com/zhuhuihuihui/EChart) ⭐ 644 | 🐛 15 | 🌐 Objective-C | 📅 2016-08-08
* [ANDLineChartView](http://hao.importnew.com/andlinechartview/)：使用 ANDLineChartView 可以便捷的在视图类中显示有动画效果的折线图。[官网](https://github.com/anaglik/ANDLineChartView) ⭐ 419 | 🐛 1 | 🌐 Objective-C | 📅 2017-03-26
* [TWRCharts](http://hao.importnew.com/twrcharts/)：一个 ChartJS 的 iOS 封装。结合 Obj-C 原生代码便捷地构建有动画的图表。[官网](https://github.com/chasseurmic/TWRCharts) ⭐ 359 | 🐛 13 | 🌐 Objective-C | 📅 2014-06-30
* [JTChartView](http://hao.importnew.com/jtchartview/)：JTChartView 是一个完全可定制的轻量级图表解决方案。[官网](https://github.com/kubatru/JTChartView) ⭐ 123 | 🐛 1 | 🌐 Objective-C | 📅 2016-11-18

### <a name="core-data"></a>Core Data

* [MagicalRecord](http://hao.importnew.com/magicalrecord/)：非常优秀的 CoreData 便捷存取框架。[官网](https://github.com/magicalpanda/MagicalRecord) ⭐ 10,703 | 🐛 242 | 🌐 Objective-C | 📅 2021-04-27
* [CoreStore](http://hao.importnew.com/corestore/)：强大的 CoreData 框架，解决了增量迁移、获取、观察等问题。★[官网](https://github.com/JohnEstropia/CoreStore) ⭐ 4,048 | 🐛 98 | 🌐 Swift | 📅 2026-07-29
* Mogenerator：自动生成 CoreData 代码。[官网](https://github.com/rentzsch/mogenerator) ⭐ 3,016 | 🐛 22 | 🌐 Objective-C | 📅 2025-06-27
* [Ensembles](http://hao.importnew.com/ensembles/)：一个 CoreData 同步框架。[官网](https://github.com/drewmccormack/ensembles) ⭐ 1,627 | 🐛 23 | 🌐 Objective-C | 📅 2026-08-05
* QueryKit：一个简洁的类型安全的 CoreData 查询语言 ★[官网](https://github.com/QueryKit/QueryKit) ⭐ 1,457 | 🐛 6 | 🌐 Swift | 📅 2021-06-10
* [ObjectiveRecord](http://hao.importnew.com/objectiverecord/)：ActiveRecord 的 Objective-C 版本。[官网](https://github.com/supermarin/ObjectiveRecord) ⚠️ Archived
* [encrypted-core-data](http://hao.importnew.com/encrypted-core-data/)：使用 SQLClipher 对 CoreData 的 SQLite 存储进行加密。[官网](https://github.com/project-imas/encrypted-core-data) ⭐ 780 | 🐛 101 | 🌐 Objective-C | 📅 2023-09-04
* [SSDataKit](http://hao.importnew.com/ssdatakit/)：消除使用 CoreData 产生的样板代码。[官网](https://github.com/soffes/SSDataKit) ⚠️ Archived
* ReactiveCoreData：ReactiveCoreData (RCD) 是一个将 CoreData 带入 ReactiveCocoa 世界的尝试。[官网](https://github.com/apparentsoft/ReactiveCoreData) ⭐ 249 | 🐛 4 | 🌐 Objective-C | 📅 2016-03-30
* ios-queryable：ios-queryable 是一个基于 CoreData 的 IQueryable/IEnumerable 实现。[官网](https://github.com/martydill/ios-queryable) ⚠️ Archived
* [HardCoreData](http://hao.importnew.com/hardcoredata/)：不会阻塞 UI 线程的 CoreData 栈和控制器。[官网](https://github.com/Krivoblotsky/HardCoreData) ⭐ 207 | 🐛 0 | 🌐 Objective-C | 📅 2015-06-17
* SLRESTfulCoreData：根据 Objc 命名习惯，在运行时自动生成访问器，URL替换和智能属性映射。[官网](https://github.com/OliverLetterer/SLRESTfulCoreData) ⭐ 177 | 🐛 2 | 🌐 Objective-C | 📅 2014-08-12
* CWCoreData：方便并发环境下 CoreData 框架开发的扩展与实用工具。[官网](https://github.com/jayway/CWCoreData)

### <a name="database"></a>数据库

* Realm：CoreData 和 SQLite 的替代品。简洁、现代、快速。[官网](https://github.com/realm/realm-cocoa) ⭐ 16,615 | 🐛 498 | 🌐 Objective-C | 📅 2026-06-14
* FMDB：SQLite 的 Cocoa/Objective-C 封装。[官网](https://github.com/ccgus/fmdb) ⭐ 13,837 | 🐛 270 | 🌐 Objective-C | 📅 2026-03-15
* YapDatabase：YapDatabase 是一个 iOS 和 Mac 上可扩展的数据库。[官网](https://github.com/yapstudios/YapDatabase) ⭐ 3,330 | 🐛 110 | 🌐 Objective-C | 📅 2022-09-07
* FCModel：为那些喜欢直接使用 SQL 进行数据库操作的人提供的 CoreData 的替代品。[官网](https://github.com/marcoarment/FCModel) ⭐ 1,641 | 🐛 30 | 🌐 Objective-C | 📅 2023-07-17
* Zephyr：轻松地通过 iCloud 同步 NSUserDefaults ★[官网](https://github.com/ArtSabintsev/Zephyr) ⭐ 952 | 🐛 0 | 🌐 Swift | 📅 2026-08-16
* Prephirences：Prephirences 是一个提供了有用的协议和便捷的方法来管理应用的偏好设置，配置和应用状态的 Swift 库。★[官网](https://github.com/phimage/Prephirences) ⭐ 573 | 🐛 4 | 🌐 Swift | 📅 2025-06-01
* Akaibu-NSUserDefaults：Swift 键/值存储，只需要一行代码就可以对 NSObject 对象进行归档。类的属性会自动映射和归档。[官网](https://github.com/roytang121/Akaibu-NSUserDefaults) ⭐ 15 | 🐛 1 | 🌐 Swift | 📅 2016-04-22
* Couchbase Mobile：Couchbase，有云同步支持的移动平台上的文档存储。[官网](http://developer.couchbase.com/mobile/)

### 加密

* AESCrypt-ObjC：一个简单固执的 AES 加密／解密类，然而它就是可以很好的工作。[官网](https://github.com/Gurpartap/AESCrypt-ObjC) ⚠️ Archived

### <a name="hardware"></a>硬件

##### <a name="motion"></a>动作

* [MotionKit](http://hao.importnew.com/motionkit/)：只需要两行或者很少的几行代码就可以从加速度传感器、陀螺仪和磁力传感器获取数据。现在 CoreMotion 让这些变得前所未有的简单。[官网](https://github.com/MHaroonBaig/MotionKit) ⭐ 1,081 | 🐛 17 | 🌐 Swift | 📅 2018-05-07

#####  

##### <a name="bluetooth"></a>蓝牙

* [BluetoothKit](http://hao.importnew.com/bluetoothkit/)：使用 BLE 在 iOS/OSX 设备之间通讯的框架★[官网](https://github.com/rasmusth/BluetoothKit) ⭐ 2,303 | 🐛 39 | 🌐 Swift | 📅 2023-10-06
* PeerKit：一个用于事件驱动，零配置的 Multipeer 连接应用程序的开源 Swift 框架。★[官网](https://github.com/jpsim/PeerKit) ⭐ 867 | 🐛 15 | 🌐 Swift | 📅 2018-12-18
* Discovery：这是个很简单的库，用来从附近的设备上发现和获取数据（即便 peer app 在后台工作）。[官网](https://github.com/omergul123/Discovery) ⭐ 413 | 🐛 13 | 🌐 Objective-C | 📅 2016-02-16
* [LGBluetooth](http://hao.importnew.com/lgbluetooth/)：基于 CoreBluetooth 的一个轻量级库，基于 block 制作。它能够让你程序中的 CoreBluetooth 相关的代码更加简洁。[官网](https://github.com/l0gg3r/LGBluetooth) ⭐ 177 | 🐛 12 | 🌐 Objective-C | 📅 2019-01-23
* simple-share：一个基于蓝牙 LE 共享的框架，易于实现附近设备的连接。[官网](https://github.com/lauraskelton/simple-share) ⭐ 136 | 🐛 3 | 🌐 Objective-C | 📅 2014-02-19

##### <a name="location"></a>位置

* LocationManager：实现了一次性或者持续请求当前位置的功能，提供了基于 block 的异步 API。[官网](https://github.com/intuit/LocationManager) ⭐ 2,551 | 🐛 12 | 🌐 Objective-C | 📅 2021-09-12
* [IngeoSDK](http://hao.importnew.com/ingeosdk/)：总是处于开启状态的 iOS 位置显示框架。[官网](https://github.com/IngeoSDK/ingeo-ios-sdk) ⭐ 98 | 🐛 3 | 🌐 Objective-C | 📅 2017-01-15
* [Proxitee](http://hao.importnew.com/proxitee/)：允许开发者利用 iBeacons 和地理围栏创建近场感知的应用。[官网](https://github.com/Proxitee/iOS-SDK) ⭐ 18 | 🐛 0 | 🌐 Objective-C | 📅 2015-05-29
* [LocationKit](http://hao.importnew.com/locationkit/)：高级位置 SDK － 只使用很少的电量和上下文相关的位置信息就可以提供高精确度的位置数据。[官网](https://locationkit.io)

##### <a name="ibeacon"></a>iBeacon

* BeaconEmitter：把你的 Mac 变成一个 iBeacon。[官网](https://github.com/lgaches/BeaconEmitter) ⭐ 999 | 🐛 1 | 🌐 Swift | 📅 2024-12-07
* [Vicinity](http://hao.importnew.com/vicinity/)：复制邻近的 iBeacons （通过分析RSSI），并支持在后台广播和检测 BLE 设备。[官网](https://github.com/Instrument/Vicinity) ⚠️ Archived
* [OWUProximityManager](http://hao.importnew.com/owuproximitymanager/)：一个方便的 iBeacon + CoreBluetooth 管理器。[官网](https://github.com/ohwutup/OWUProximityManager) ⭐ 360 | 🐛 2 | 🌐 Objective-C | 📅 2013-11-24
* OWUProximityManager：iBeacons + CoreBluetooth.[官网](https://github.com/ohwutup/OWUProximityManager) ⭐ 360 | 🐛 2 | 🌐 Objective-C | 📅 2013-11-24
* Proxitee：允许开发者利用 iBeacons 和地理围栏创建近场感知的应用。[官网](https://github.com/Proxitee/iOS-SDK) ⭐ 18 | 🐛 0 | 🌐 Objective-C | 📅 2015-05-29

### <a name="hud"></a>HUD

* MBProgressHUD：用于显示一个半透明的 HUD。当任务在后台线程结束时可以在上边显示一个指示器和／或者标签。[官网](https://github.com/jdg/MBProgressHUD) ⭐ 15,930 | 🐛 94 | 🌐 Objective-C | 📅 2024-08-14
* M13ProgressSuite：一个包含了很多 iOS 上用于显示进度信息工具的套装。[官网](https://github.com/Marxon13/M13ProgressSuite) ⭐ 3,900 | 🐛 48 | 🌐 Objective-C | 📅 2022-03-05
* PKHUD：用 Swift 重新实现了 Apple 的原生 HUD，支持 iOS 8 以上★[官网](https://github.com/pkluz/PKHUD) ⭐ 3,776 | 🐛 64 | 🌐 Swift | 📅 2023-02-16
* ProgressHUD：ProgressHUD 是一个轻量易用的 HUD。[官网](https://github.com/relatedcode/ProgressHUD) ⭐ 2,969 | 🐛 12 | 🌐 Swift | 📅 2026-08-02
* CozyLoadingActivity：轻量的载入动作指示 HUD ★[官网](https://github.com/goktugyil/EZLoadingActivity) ⭐ 605 | 🐛 10 | 🌐 Swift | 📅 2022-03-18
* JHProgressHUD：一个简单轻量的 Swift 框架，用于在 iOS 应用中显示★[官网](https://github.com/harikrishnant1991/JHProgressHUD) ⭐ 78 | 🐛 3 | 🌐 Swift | 📅 2021-02-27
* SVProgressHUD：一个为你的 iOS 应用制作的简洁，轻量级的进度指示 HUD。[官网](https://github.com/TransitApp/SVProgressHUD) ⭐ 6 | 🐛 0 | 📅 2024-04-04

### <a name="eventbus"></a>事件总线

* PromiseKit：iOS 和 OS X 上的 Promises 实现。[官网](https://github.com/mxcl/PromiseKit) ⭐ 14,230 | 🐛 15 | 🌐 Swift | 📅 2026-06-03
* Bolts：Bolts 是一个试图使构建移动应用更简单的一个底层库集合。包括了任务（promises）和应用关联（deep links）。[官网](https://github.com/BoltsFramework/Bolts-ObjC) ⭐ 5,621 | 🐛 42 | 🌐 Objective-C | 📅 2021-08-30
* SwiftTask：Swift 实现的 Promise + progress + pause + cancel + retry。 ★[官网](https://github.com/ReactKit/SwiftTask) ⭐ 1,923 | 🐛 5 | 🌐 Swift | 📅 2019-04-15
*   SwiftEventBus：一个针对 iOS 8 优化的发布／订阅事件总线。★[官网](https://github.com/cesarferreira/SwiftEventBus) ⭐ 1,121 | 🐛 8 | 🌐 Swift | 📅 2026-07-30
* Caravel：用于 UIWebView 和 JS 的 Swift 事件总线。★[官网](https://github.com/coshx/caravel) ⭐ 148 | 🐛 2 | 🌐 Swift | 📅 2019-05-16

### <a name="files"></a>文件

* [FileKit](http://hao.importnew.com/filekit/)：Swift 实现的简单快捷的文件管理工具。★[官网](https://github.com/nvzqz/FileKit) ⭐ 2,360 | 🐛 14 | 🌐 Swift | 📅 2024-04-09

###  

### <a name="json"></a>JSON

* SwiftyJSON：使用 Swift 处理 JSON 数据的好方法。★[官网](https://github.com/SwiftyJSON/SwiftyJSON) ⭐ 22,951 | 🐛 139 | 🌐 Swift | 📅 2026-08-18
* Mantle：面向 Cocoa 和 Cocoa Touch 的模型框架 Model 。[官网](https://github.com/Mantle/Mantle) ⭐ 11,256 | 🐛 0 | 🌐 Objective-C | 📅 2022-10-18
* ObjectMapper：在模型对象（包括 class 和 struct）和 JSON 之间转换的 Swift 框架。★[官网](https://github.com/Hearst-DD/ObjectMapper) ⭐ 9,137 | 🐛 68 | 🌐 Swift | 📅 2024-05-02
* JSONModel：神奇的基于 JSON 的数据模型化框架。创建了一系列敏捷便利，自动并且智能的模型类。[官网](https://github.com/icanzilb/JSONModel) ⭐ 6,809 | 🐛 34 | 🌐 Objective-C | 📅 2021-11-06
* JSONKit：Objective-C JSON 工具。[官网](https://github.com/johnezang/JSONKit) ⭐ 6,176 | 🐛 103 | 🌐 Objective-C | 📅 2020-11-22
* JSON-Framework：这个框架用 Objective-C 实现了一个严格的 JSON 解释器和生成器。[官网](https://github.com/stig/json-framework) ⭐ 3,717 | 🐛 1 | 🌐 Objective-C | 📅 2026-05-18
* Gloss：一个 Swift 写的 JSON 解析库。★[官网](https://github.com/hkellaway/Gloss) ⚠️ Archived
* KZPropertyMapper：以最少的代码实现数据映射和验证。[官网](https://github.com/krzysztofzablocki/KZPropertyMapper) ⭐ 1,119 | 🐛 3 | 🌐 Objective-C | 📅 2021-01-06
* JASON：性能优秀操作便捷的 JSON 解析。★[官网](https://github.com/delba/JASON) ⭐ 1,006 | 🐛 7 | 🌐 Swift | 📅 2021-02-14
* SwiftyJSONAccelerator：使用 SwiftyJSON 或者 ObjectMapper 根据 JSON 生成 Swift 模型。支持 NSCoding 并且提供了使用 JSON 来表示模型的方法。★[官网](https://github.com/insanoid/SwiftyJSONAccelerator) ⭐ 948 | 🐛 10 | 🌐 Swift | 📅 2025-11-24
* FastEasyMapping：快速地序列化和反序列化 JSON 数据。[官网](https://github.com/Yalantis/FastEasyMapping) ⭐ 544 | 🐛 18 | 🌐 Objective-C | 📅 2019-12-07
* Groot：实现呃 JSON 字典或者数组和 Core Data Mangement 对象之间的转换。[官网](https://github.com/gonzalezreal/Groot) ⭐ 535 | 🐛 15 | 🌐 Objective-C | 📅 2019-12-16
* Cereal：Swift 对象序列化 ★[官网](https://github.com/Weebly/Cereal) ⭐ 368 | 🐛 5 | 🌐 Swift | 📅 2017-10-27
* OCMapper：Objective-C & Swift 通用的快速 JSON 模型转化框架。 ★[官网](https://github.com/aryaxt/OCMapper) ⭐ 346 | 🐛 21 | 🌐 Objective-C | 📅 2022-06-20
* TouchJSON：一个 Objective-C 的 JSON 框架。[官网](https://github.com/TouchCode/TouchJSON)

### <a name="layout"></a>布局

* SnapKit：一个 iOS 和 OS X 的 Swift Autolayout 领域专用语言（DSL）。★[官网](https://github.com/SnapKit/SnapKit) ⭐ 20,349 | 🐛 9 | 🌐 Swift | 📅 2026-07-13
* Masonry：利用简单的，链式的语法发挥出自动布局 NSLayoutConstraints 的强大功能。[官网](https://github.com/SnapKit/Masonry) ⭐ 18,133 | 🐛 151 | 🌐 Objective-C | 📅 2023-04-13
* PureLayout：终极的 iOS 和 OS X 上的 Autolayout API，极其简单又异常强大。同时适用于 Objective-C 和 Swift。[官网](https://github.com/PureLayout/PureLayout) ⭐ 7,596 | 🐛 47 | 🌐 Objective-C | 📅 2023-03-16
* Cartography：一个 Swift 编写的声明式 Auto Layout 领域专用语言（DSL）。★[官网](https://github.com/robb/Cartography) ⭐ 7,325 | 🐛 64 | 🌐 Swift | 📅 2025-09-05
* FLKAutoLayout：让使用代码做约束更加简便的 UIView 类别。[官网](https://github.com/floriankugler/FLKAutoLayout) ⭐ 1,482 | 🐛 10 | 🌐 Objective-C | 📅 2021-01-13
* Façade：可编程的视图布局，一个 autolayout 的替代品。[官网](https://github.com/mamaral/Facade) ⭐ 684 | 🐛 2 | 🌐 Objective-C | 📅 2017-09-14
* ios-flexboxkit：一个封装了 Flexbox 布局的简单 UIKit 扩展。[官网](https://github.com/alexdrone/ios-flexboxkit) ⚠️ Archived
* AutoLayoutPlus：给 Auto Layout 加的一点料，由 Swift 驱动。 ★[官网](https://github.com/ruipfcosta/AutoLayoutPlus) ⭐ 27 | 🐛 1 | 🌐 Swift | 📅 2017-04-14

### <a name="logging"></a>日志

* CocoaLumberjack：一个快捷强大灵活的日志框架，可用于 iOS & Mac。[官网](https://github.com/CocoaLumberjack/CocoaLumberjack) ⭐ 13,325 | 🐛 6 | 🌐 Objective-C | 📅 2026-08-12
* NSLogger：一个高性能的日志工具，它可以显示运行在 OS X、iOS 和 Android 上客户端应用的踪迹。[官网](https://github.com/fpillet/NSLogger) ⭐ 4,980 | 🐛 50 | 🌐 Objective-C | 📅 2026-06-03
* CleanroomLogger：一个基于 Swift 可配置可扩展的日志 API，简洁、轻量并且高效。★[官网](https://github.com/emaloney/CleanroomLogger) ⭐ 1,316 | 🐛 25 | 🌐 Swift | 📅 2023-03-14
* QorumLogs：为 Xcode 和 Google Docs 设计的 Swift 日志工具。★[官网](https://github.com/goktugyil/QorumLogs) ⭐ 778 | 🐛 8 | 🌐 Swift | 📅 2018-04-25
* Aardvark：一个高性能日志框架，它使得创建可操作的 bug 报告变得非常简单。[官网](https://github.com/square/Aardvark/) ⭐ 262 | 🐛 11 | 🌐 Objective-C | 📅 2026-06-23
* BlockTypeDescription：在日志记录 block 的时候显示类型签名。[官网](https://github.com/conradev/BlockTypeDescription) ⭐ 254 | 🐛 0 | 🌐 Objective-C | 📅 2013-03-18

### <a name="maps"></a>地图

* Mapbox GL：一个 iOS 上使用 OpenGL 渲染 Mapbox 矢量地图块的框架。[官网](https://github.com/mapbox/mapbox-gl-native) ⚠️ Archived
* Route-me：iOS 开源地图框架[官网](https://github.com/route-me/route-me) ⭐ 1,316 | 🐛 100 | 🌐 Objective-C | 📅 2012-10-14
* NAMapKit：允许你在 iPhone 应用使用自定义地图，并尝试模仿 Mapkit 框架的一些行为。[官网](https://github.com/neilang/NAMapKit) ⭐ 261 | 🐛 10 | 🌐 Objective-C | 📅 2016-05-05
* CMMapLauncher：用于 iOS 中在各种地图应用中显示方向的便捷框架。[官网](https://github.com/citymapper/CMMapLauncher) ⭐ 192 | 🐛 11 | 🌐 Objective-C | 📅 2022-06-07
* [百度地图iOS SDK](http://hao.importnew.com/baidu_map_ios_sdk/)：一套功能丰富的地图开发工具包。[官网](http://lbsyun.baidu.com/index.php?title=iossdk)
* [百度鹰眼轨迹iOS SDK](http://hao.importnew.com/baidu_yingyan_ios-sdk/)：一套能够进行绑路纠偏的轨迹开发工具包。[官网](http://lbsyun.baidu.com/index.php?title=ios-yingyan)

### <a name="media"></a>媒体

##### <a name="image"></a>图片

* SDWebImage：异步的图像下载器，提供了缓存支持。以 UIImageView 类别的方式提供。[官网](https://github.com/rs/SDWebImage) ⭐ 25,634 | 🐛 131 | 🌐 Objective-C | 📅 2026-04-15
* GPU Image：一个基于 GPU 的 iOS 开源的图像和视频处理框架。[官网](https://github.com/BradLarson/GPUImage) ⭐ 20,302 | 🐛 1,000 | 🌐 Objective-C | 📅 2024-02-16
* Nuke：高级的图片管理框架。★[官网](https://github.com/kean/Nuke) ⭐ 8,663 | 🐛 13 | 🌐 Swift | 📅 2026-08-30
* FastImageCache：在滚动时快速显示图片的 iOS 框架。[官网](https://github.com/path/FastImageCache) ⭐ 8,059 | 🐛 40 | 🌐 Objective-C | 📅 2023-07-12
* HanekeSwift：一个 Swift 编写的 iOS 平台的轻量级通用缓存框架，还有对图像的更多支持。★[官网](https://github.com/Haneke/HanekeSwift) ⭐ 5,157 | 🐛 96 | 🌐 Swift | 📅 2020-11-15
* TOCropViewController：一个可以允许用户修改 UIImage 对象的视图控制器。[官网](https://github.com/TimOliver/TOCropViewController) ⭐ 4,946 | 🐛 105 | 🌐 Objective-C | 📅 2026-07-28
* PINRemoteImage：一个线程安全、高性能、特性丰富的图像获取器。[官网](https://github.com/pinterest/PINRemoteImage) ⭐ 4,025 | 🐛 62 | 🌐 Objective-C | 📅 2026-08-28
* AlamofireImage：一个为 Alamofire 制作的图像组件库。★[官网](https://github.com/Alamofire/AlamofireImage) ⭐ 4,025 | 🐛 14 | 🌐 Swift | 📅 2026-07-27
* YYWebImage：异步图像加载框架（支持 WebP，APNG，GIF 格式）。[官网](https://github.com/ibireme/YYWebImage) ⭐ 3,526 | 🐛 117 | 🌐 Objective-C | 📅 2020-11-05
* FlagKit：供 app 和 web 页面上使用的漂亮旗标。★[官网](https://github.com/madebybowtie/FlagKit) ⭐ 3,105 | 🐛 33 | 🌐 Swift | 📅 2024-04-19
* SCRecorder：类似 Vine 的点击拍摄，动画过滤器，慢镜头，片段编辑相机引擎。[官网](https://github.com/rFlex/SCRecorder) ⭐ 3,044 | 🐛 233 | 🌐 Objective-C | 📅 2021-05-25
* NYTPhotoViewer：抽屉菜单和照片查看器。[官网](https://github.com/NYTimes/NYTPhotoViewer) ⭐ 2,873 | 🐛 78 | 🌐 Objective-C | 📅 2026-02-04
* IDMPhotoBrowser：图片浏览器／查看器。[官网](https://github.com/ideaismobile/IDMPhotoBrowser) ⭐ 2,690 | 🐛 192 | 🌐 Objective-C | 📅 2024-04-11
* YLGIFImage：异步的 GIF 图像解码和图片浏览器。支持 GIF 图动画，但只消耗少量的内存。[官网](https://github.com/liyong03/YLGIFImage) ⭐ 1,764 | 🐛 14 | 🌐 Objective-C | 📅 2020-12-19
* Concorde：下载和解码连续的 JPEG 图像。[官网](https://github.com/contentful-labs/Concorde/) ⭐ 1,431 | 🐛 9 | 🌐 Objective-C | 📅 2022-02-08
* DFImageManager：从多种数据源获取图像的现代框架。无需配置，并具有高度的可定制性和扩展性。使用了 NSURLSession。[官网](https://github.com/kean/DFImageManager) ⚠️ Archived
* AsyncImageView：UIImageView 的异步图像加载和显示扩展，不会阻塞 UI 线程。[官网](https://github.com/nicklockwood/AsyncImageView) ⭐ 902 | 🐛 44 | 🌐 Objective-C | 📅 2017-10-26
* SABlurImageView：可以轻松地为图片添加模糊动画效果。★[官网](https://github.com/szk-atmosphere/SABlurImageView) ⭐ 552 | 🐛 8 | 🌐 Swift | 📅 2020-11-10
* BKAsciiImage：将图片渲染为 ASCII art 的库。[官网](https://github.com/bkoc/BKAsciiImage) ⭐ 428 | 🐛 1 | 🌐 Objective-C | 📅 2015-04-24
* UIImage DSP：iOS UIImage 处理功能，它使用 vDSP/Accelerate 框架来提高速度。[官网](https://github.com/gdawg/uiimage-dsp) ⭐ 368 | 🐛 4 | 🌐 Objective-C | 📅 2013-01-30
* MapleBacon：一个 Swift iOS 图像下载和缓存库 ★[官网](https://github.com/zalando/MapleBacon) ⭐ 345 | 🐛 0 | 🌐 Swift | 📅 2026-08-17
* YXTMotionView：一个自定义的图片视图，它实现了依靠设备运动来滚动图片。[官网](https://github.com/hanton/YXTMotionView) ⭐ 77 | 🐛 0 | 🌐 Objective-C | 📅 2015-07-16
* JTSImageViewController：iOS 交互式图片浏览器。[官网](https://github.com/jaredsinclair/JTSImageViewController) ⭐ 33 | 🐛 19 | 🌐 Objective-C | 📅 2018-03-29
* QR Code Scanner：二维码扫描器。[官网](http://www.appcoda.com/qr-code-ios-programming-tutorial/)
*   EFQRCode：一个纯 Swift 开发的艺术二维码生成库。★[官网](https://github.com/EyreFree/EFQRCode)

##### <a name="video"></a>视频

* MobilePlayer：一个强大完善且完全可定制的 iOS 媒体播放器。[官网](https://github.com/mobileplayer/mobileplayer-ios) ⭐ 3,075 | 🐛 51 | 🌐 Swift | 📅 2022-07-21
* VIMVideoPlayer：一个对 AVPlayer 和 AVPlayerLayer 类的简单封装。[官网](https://github.com/vimeo/VIMVideoPlayer) ⚠️ Archived

##### <a name="pdf"></a>PDF

* Reader：一个 iOS PDF 阅读器的核心。[官网](https://github.com/vfr/Reader) ⭐ 4,247 | 🐛 1 | 🌐 Objective-C | 📅 2019-12-30
* UIView 2 PDF：使用 UIViews （或配合着 XIB）的 PDF 生成器。[官网](https://github.com/RobertAPhillips/UIView_2_PDF) ⭐ 35 | 🐛 0 | 🌐 Objective-C | 📅 2015-09-30

### <a name="messaging"></a>消息

* XMPPFramework：一个 iOS 和 Mac 上的 XMPP 协议通讯框架。[官网](https://github.com/robbiehanson/XMPPFramework) ⭐ 5,878 | 🐛 554 | 🌐 Objective-C | 📅 2024-04-22
* LayerKit：一个对于 Layer 的 iOS 开发组件,。是将消息（文字，照片，视频，数据）添加到移动或 Web 应用中最简单的解决方案。[官网](https://github.com/layerhq/releases-ios)
* Twilio：驱动着现代的交流方式，构建下一代音频与 SMS 应用。[官网](https://www.twilio.com/)
* Plivo：SMS API、音频 API 和 全球运营商。[官网](https://www.plivo.com/)

### <a name="networking"></a>网络

* Alamofire：Alamofire 是一个 Swift 写的 HTTP 网络库，由 AFNetworking 的作者编写。★[官网](https://github.com/Alamofire/Alamofire) ⭐ 42,428 | 🐛 44 | 🌐 Swift | 📅 2026-08-31
* AFNetworking：一个得心应手的 iOS 和 OSX 上的网络请求框架。[官网](https://github.com/AFNetworking/AFNetworking) ⚠️ Archived
* CocoaAsyncSocket：用于 Mac 和 iOS 的异步 socket 网络库。[官网](https://github.com/robbiehanson/CocoaAsyncSocket) ⭐ 12,451 | 🐛 0 | 🌐 Objective-C | 📅 2026-08-30
* RestKit：RestKit 是一个 iOS Objective-C 框架，是为了让和 RESTful web 服务交互变的简单、快捷、有趣。[官网](https://github.com/RestKit/RestKit) ⭐ 10,094 | 🐛 364 | 🌐 Objective-C | 📅 2022-08-27
* Reachability.swift：用 Swift 和闭包重新实现了苹果的 Reachablility 框架。★[官网](https://github.com/ashleymills/Reachability.swift) ⭐ 7,972 | 🐛 90 | 🌐 Swift | 📅 2024-10-03
* ASIHTTPRequest：Objective-C 编写的 HTTP 网络请求库。它是对 CFNetwork 易用的封装。支持 Mac OS X 和 iPhone。[官网](https://github.com/pokeb/asi-http-request) ⭐ 5,726 | 🐛 167 | 🌐 Objective-C | 📅 2019-01-15
* NetworkEye：一个 iOS 网络调试库，可以显示 App 中的 HTTP 请求和请求的相关信息。[官网](https://github.com/coderyi/NetworkEye) ⭐ 1,402 | 🐛 19 | 🌐 Objective-C | 📅 2020-08-24
* Overcoat：小巧但是很强大的库，让创建一个 REST 客户端简便和有趣。[官网](https://github.com/Overcoat/Overcoat) ⭐ 1,093 | 🐛 25 | 🌐 Objective-C | 📅 2016-10-20
* NSRails：将客户端的对象／类映射到远程 REST API 的对象／ORM。[官网](https://github.com/dingbat/nsrails) ⚠️ Archived
* Transporter：让上传下载更便捷的小代码库。★[官网](https://github.com/nghialv/Transporter) ⭐ 447 | 🐛 7 | 🌐 Swift | 📅 2016-01-21
* FSNetworking：稳固的 iOS 网络库。[官网](https://github.com/foursquare/FSNetworking) ⭐ 379 | 🐛 9 | 🌐 Objective-C | 📅 2015-07-21
* MBNetworkMonitor：苹果 `Reachability` 类的现代化替代品，使用了 `CoreTelephony` 来传达更多[有关用户网络连接状况的信息](https://rawgit.com/emaloney/MBToolbox/master/Documentation/html/Classes/MBNetworkMonitor.html)。[官网](https://github.com/emaloney/MBToolbox/blob/master/Code/Network/MBNetworkMonitor.h) ⭐ 99 | 🐛 2 | 🌐 Objective-C | 📅 2017-12-05
* MBNetworkIndicator：提供了简单的方式[在多个请求之间协调设备网络指示器](https://rawgit.com/emaloney/MBToolbox/master/Documentation/html/Classes/MBNetworkIndicator.html)。[官网](https://github.com/emaloney/MBToolbox/blob/master/Code/Network/MBNetworkIndicator.h) ⭐ 99 | 🐛 2 | 🌐 Objective-C | 📅 2017-12-05
* ROADFramework：面向属性的 web 服务交互方式。框架有内建的 json 和 xml 请求响应序列化方法，十分方便扩展。[官网](https://github.com/epam/road-ios-framework) ⭐ 56 | 🐛 21 | 🌐 Objective-C | 📅 2018-06-09
* CDZPinger：使用方便的 ICMP Ping 框架。[官网](https://github.com/cdzombak/CDZPinger) ⚠️ Archived
* NKMultipeer：一个建立在多重链接上的可测试的抽象。★[官网](https://github.com/nathankot/NKMultipeer) ⭐ 15 | 🐛 0 | 🌐 Swift | 📅 2016-04-24
* Siesta：优雅的 RESTful 资源抽象，将状态解藕。是基于回调或者代理的网络库的替代品。★[官网](https://bustoutsolutions.github.io/siesta/)

### <a name="push-notifications"></a>推送通知

* APNS-Pusher：苹果推送通知服务的调试器。[官网](https://github.com/KnuffApp/Knuff) ⭐ 5,222 | 🐛 19 | 🌐 Objective-C | 📅 2022-09-04
* Orbiter：在 iOS 中注册推送通知。[官网](https://github.com/mattt/Orbiter) ⚠️ Archived
* PEM：为推送服务器自动生成 profile。[官网](https://github.com/fastlane/PEM) ⚠️ Archived
* Parse Push：完全免费的后台推送通知，提供了创建分段，调度甚至 A/B 测试的能力。[官网](https://parse.com/products/push)
* Urban Airship：付费的推送通知后台。[官网](https://www.urbanairship.com/products/platform#push-messages)
* Growth Push：付费的推送通知。 它是在日本最受开发者喜爱的工具之一。[官网](https://growthpush.com)

### <a name="passbook"></a>Passbook

* Dubai：生成和预览 Passbook 的 Pass。[官网](https://github.com/nomad/dubai) ⚠️ Archived
* passbook：为 Passbook 创建 pkpass 文件。[官网](https://github.com/frozon/passbook) ⭐ 231 | 🐛 25 | 🌐 Ruby | 📅 2023-01-18
* Passkit：设计、创建并验证 Passbook 的 Pass。[官网](https://passkit.com)

### <a name="permissions"></a>权限

* PermissionScope：智能的 iOS 授权 UI 和 统一的 API（支持位置、通知、照片、联系人、日历、照片、麦克风、BT、进度指示、HealthKit 和 CloudKit）。★[官网](https://github.com/nickoneill/PermissionScope) ⚠️ Archived
* Proposer：便捷地请求用户权限（支持相机、照片、麦克风、联系人、位置）。★[官网](https://github.com/nixzhu/Proposer) ⭐ 847 | 🐛 3 | 🌐 Swift | 📅 2021-12-17
* ISHPermissionKit：为 iOS 提供请求用户权限的统一方法。[官网](https://github.com/iosphere/ISHPermissionKit) ⭐ 615 | 🐛 8 | 🌐 Objective-C | 📅 2021-01-08
* VWWPermissionKit：可视化的 iOS 授权管理器。[官网](https://github.com/zakkhoyt/VWWPermissionKit) ⭐ 143 | 🐛 9 | 🌐 Objective-C | 📅 2020-03-02
* ICanHas：简化 iOS 用户权限请求（支持位置、推送通知、相机、联系人、日历、照片）。★[官网](https://github.com/wircho/ICanHas) ⭐ 91 | 🐛 2 | 🌐 Swift | 📅 2018-10-10
* JLPermissions：iOS 预授权工具，开发者用它来制作询问用户是否授权的对话框，支持日历、联系人、位置、照片、备忘录、twitter、推送通知和其他需要授权的操作。[官网](https://github.com/jlaws/JLPermissions)

### <a name="text"></a>文本

* YYText：iOS 上用于显示和编辑富文本的强大文本框架。[官网](https://github.com/ibireme/YYText) ⭐ 8,870 | 🐛 517 | 🌐 Objective-C | 📅 2024-07-16
* DTCoreText：利用 CoreText 使用 HTML 代码的方法。[官网](https://github.com/Cocoanetics/DTCoreText) ⭐ 6,393 | 🐛 0 | 🌐 Swift | 📅 2026-07-15
* PhoneNumberKit：用于解析，格式化和验证国际电话号码的 Swift 框架，由谷歌的 libphonenumber 库支持。★[官网](https://github.com/marmelroy/PhoneNumberKit) ⭐ 5,389 | 🐛 20 | 🌐 Swift | 📅 2026-05-25
* Twitter Text Obj：Twitter 的文本处理库的 Objective-C 实现。[官网](https://github.com/twitter/twitter-text) ⭐ 3,139 | 🐛 93 | 🌐 HTML | 📅 2024-04-26
* RichEditorView：RichEditorView 是一个简单、模块化的富文本编辑器视图。★[官网](https://github.com/cjwirth/RichEditorView) ⚠️ Archived
* ios-fontawesome：NSString + FontAwesome。[官网](https://github.com/alexdrone/ios-fontawesome) ⭐ 1,741 | 🐛 33 | 🌐 Objective-C | 📅 2017-01-24
* MMMarkdown：用于将 Markdown 转换为 HTML 的 Objective-C 静态库。[官网](https://github.com/mdiep/MMMarkdown) ⭐ 1,267 | 🐛 11 | 🌐 Objective-C | 📅 2020-10-24
* Money：为与钱和现金相关工作的的 Swift 值类型。★[官网](https://github.com/danthorpe/Money) ⚠️ Archived
* NSStringEmojize：一个将 Emoji 表情符号转换为等价的 Unicode 字串的 NSString 类别。[官网](https://github.com/diy/nsstringemojize) ⭐ 631 | 🐛 7 | 🌐 Objective-C | 📅 2017-06-14
* DTRichTextEditor：一个 iOS 的富文本编辑器。[官网](https://github.com/Cocoanetics/DTRichTextEditor) ⭐ 355 | 🐛 12 | 🌐 Objective-C | 📅 2024-03-26
* Pluralize.swift：强大的 Swift String 单数转换复数扩展。★[官网](https://github.com/joshualat/Pluralize.swift) ⭐ 195 | 🐛 12 | 🌐 Swift | 📅 2022-10-07
* NBEmojiSearchView：一个支持搜索并且可以集成到文本控件中的 emoji 下拉列表视图。[官网](https://github.com/neerajbaid/NBEmojiSearchView) ⭐ 83 | 🐛 1 | 🌐 Objective-C | 📅 2015-06-30
* Nimbus：Nimbus 是一个为高级 iOS 软件设计师制作工具包。[官网](http://nimbuskit.info/)

### <a name="walkthrough--intro--tutorial"></a>功能漫游 / 介绍 / 教程

* Onboard：用一点点代码就可以创建一个漂亮的吸附效果的实践。[官网](https://github.com/mamaral/Onboard) ⭐ 6,561 | 🐛 45 | 🌐 Objective-C | 📅 2025-01-01
* JazzHands：Jazz Hands 是一个简单的 UIKit 关键帧动画框架。动画是可以使用手势、滚动视图、KVO 或者 ReactiveCocoa 来控制的。[官网](https://github.com/IFTTT/JazzHands) ⭐ 6,361 | 🐛 14 | 🌐 Objective-C | 📅 2024-07-30
* Instructions：向你的 iOS 项目中添加自定义的操作方式指导的简单办法。★[官网](https://github.com/ephread/Instructions) ⭐ 5,201 | 🐛 17 | 🌐 Swift | 📅 2024-06-05
* EAIntroView：高度可定制非侵入式的欢迎页面解决方案。[官网](https://github.com/ealeksandrov/EAIntroView) ⭐ 3,731 | 🐛 20 | 🌐 Objective-C | 📅 2020-11-10
* RazzleDazzle：简单的基于关键帧的 iOS 动画框架，由 Swift 编写。最适合用于 App 的滚动介绍页面。★[官网](https://github.com/IFTTT/RazzleDazzle) ⭐ 3,346 | 🐛 23 | 🌐 Swift | 📅 2023-10-11
* BWWalkthrough：一个自定义 iOS App 的功能漫游页面的框架。★[官网](https://github.com/ariok/BWWalkthrough) ⭐ 2,745 | 🐛 4 | 🌐 Swift | 📅 2021-02-07
* MYBlurIntroductionView：在 MYIntroductionView 上完善的，用于构建可定制的 app 介绍或者教程页面的框架。[官网](https://github.com/MatthewYork/MYBlurIntroductionView) ⭐ 1,517 | 🐛 18 | 🌐 Objective-C | 📅 2017-10-30
* ICETutorial：一个很好的教程框架，类似 Path 3.X 版本的 App 中的样式。[官网](https://github.com/icepat/ICETutorial) ⭐ 786 | 🐛 9 | 🌐 Objective-C | 📅 2017-04-17
* GHWalkThrough：一个基于 UICollectionView 的非侵入式介绍页面组件。[官网](https://github.com/GnosisHub/GHWalkThrough) ⭐ 700 | 🐛 9 | 🌐 Objective-C | 📅 2017-04-18
* SwiftyWalkthrough：创建一个体验绝佳的功能漫游的最简单方法，Swift 编写。★[官网](https://github.com/ruipfcosta/SwiftyWalkthrough) ⭐ 370 | 🐛 9 | 🌐 Swift | 📅 2021-08-03

### <a name="url-scheme"></a>URL Scheme

* JLRoutes：使用了 block API 的 iOS URL 路由框架。[官网](https://github.com/joeldev/JLRoutes) ⭐ 5,704 | 🐛 12 | 🌐 Objective-C | 📅 2023-02-21
* DeepLinkKit：杰出的路由匹配框架，使用基于 block API 处理你的深链接。[官网](https://github.com/usebutton/DeepLinkKit) ⭐ 3,452 | 🐛 23 | 🌐 Objective-C | 📅 2025-11-25
* IntentKit：一个便捷的方法来在 iOS app 中处理第三方 URL schemes。[官网](https://github.com/intentkit/IntentKit) ⭐ 1,785 | 🐛 19 | 🌐 Objective-C | 📅 2017-05-24
* WAAppRouting：iOS 的路由实现。同时处理了 URL 识别和利用控制器显示解析后的参数。全部这些只要一行代码就可以搞定，控制器堆栈还会被自动保留！[官网](https://github.com/Wasappli/WAAppRouting) ⭐ 587 | 🐛 4 | 🌐 Objective-C | 📅 2016-05-19

### <a name="ui"></a>UI

* IQKeyboardManager：防止键盘滑出来遮挡住 UITextField/UITextView 的框架，非侵入，无需代码。[官网](https://github.com/hackiftekhar/IQKeyboardManager) ⭐ 16,629 | 🐛 8 | 🌐 Swift | 📅 2026-05-25
* AsyncDisplayKit：AsyncDisplayKit 是一个 iOS 框架，它能够使一个很复杂的用户界面保持平滑和反应灵敏。[官网](https://github.com/facebook/AsyncDisplayKit/) ⚠️ Archived
* Chameleon：一个 iOS 性能强大的轻量级扁平化颜色框架，可以用于 Objective-C 和 Swift。★[官网](https://github.com/ViccAlexander/Chameleon) ⚠️ Archived
* iCarousel：iOS 和 Mac OS 上简单的，高度可定制化的数据驱动 3D 跑马灯。[官网](https://github.com/nicklockwood/iCarousel) ⭐ 12,108 | 🐛 400 | 🌐 Objective-C | 📅 2024-06-27
* Eureka：使用纯 Swift 构建优雅的 iOS 表单。★[官网](https://github.com/xmartlabs/Eureka) ⭐ 11,805 | 🐛 179 | 🌐 Swift | 📅 2024-09-12
* JSQMessagesViewController：一个优雅的 iOS 聊天消息 UI 库。[官网](https://github.com/jessesquires/JSQMessagesViewController) ⚠️ Archived
* NVActivityIndicatorView：很好的加载动画集合。★[官网](https://github.com/ninjaprox/NVActivityIndicatorView) ⭐ 10,708 | 🐛 1 | 🌐 Swift | 📅 2026-03-18
* SlackTextViewController：一个非侵入式的 UIViewcontroller 子类，提供了一个可以随文字长度变化的大小的文本框和一些其他有用的消息特性。[官网](https://github.com/slackhq/SlackTextViewController) ⚠️ Archived
* FlatUIKit：适用于 iOS 的扁平化 UI 组件集合。[官网](https://github.com/Grouper/FlatUIKit) ⭐ 7,730 | 🐛 35 | 🌐 Objective-C | 📅 2016-09-29
* JTAppleCalendar: 最好的iOS版雨燕日历库 ★[官网](https://github.com/patchthecode/JTAppleCalendar) ⭐ 7,653 | 🐛 83 | 🌐 Swift | 📅 2024-07-23
* JVFloatLabeledTextField：附有浮动标签的 UITextField 子类。[官网](https://github.com/jverdi/JVFloatLabeledTextField) ⭐ 7,141 | 🐛 28 | 🌐 Objective-C | 📅 2023-04-17
* RESideMenu：受 Dribble 上的设计启发而制作的 iOS 7/8 样式的视差侧滑菜单。[官网](https://github.com/romaonthego/RESideMenu) ⭐ 7,039 | 🐛 132 | 🌐 Objective-C | 📅 2017-12-05
* MGSwipeTableCell：可以显示滑动按钮的 UITableViewCell 的子类，还支持多种过渡动画。[官网](https://github.com/MortimerGoro/MGSwipeTableCell) ⭐ 6,915 | 🐛 132 | 🌐 Objective-C | 📅 2023-03-22
* XLForm：XLForm 是最灵活强大的 iOS 库，用来创建动态的 tableview 表单，完全适用于 Swift 和 Obj-C。[官网](https://github.com/xmartlabs/XLForm) ⭐ 5,734 | 🐛 180 | 🌐 Objective-C | 📅 2024-06-03
* SCLAlertView-Swift：Swift 实现的一个漂亮的动画 Alert View。★[官网](https://github.com/vikmeup/SCLAlertView-Swift) ⭐ 5,309 | 🐛 147 | 🌐 Swift | 📅 2024-01-05
* TSMessages：在屏幕上方显示通知（比如成功、错误、警告或者消息）视图。[官网](https://github.com/KrauseFx/TSMessages) ⭐ 4,842 | 🐛 94 | 🌐 Objective-C | 📅 2023-06-01
* LNRSimpleNotifications：简单的 Swift app 内置通知。LNRSimpleNotifications 是一个 Swift [TSMessages](https://github.com/KrauseFx/TSMessages) ⭐ 4,842 | 🐛 94 | 🌐 Objective-C | 📅 2023-06-01 简化版本。 ★[官网](https://github.com/LISNR/LNRSimpleNotifications) ⭐ 202 | 🐛 4 | 🌐 Swift | 📅 2022-02-28
* ActiveLabel.swift：非侵入的 UILabel 替代品，支持 Hashtags (#), Mentions (@) 和 URL (http\:// )。 ★[官网](https://github.com/optonaut/ActiveLabel.swift) ⭐ 4,604 | 🐛 29 | 🌐 Swift | 📅 2023-10-27
* SWRevealViewController：受到 FaceBook 和 Wunderlist 应用启发的 UIViewController 子类，用于显示侧滑的视图控制器。[官网](https://github.com/John-Lluch/SWRevealViewController) ⭐ 4,482 | 🐛 348 | 🌐 Objective-C | 📅 2022-03-29
* JDStatusBarNotification：显示在顶部状态栏的通知，使用简单，可以自定义。[官网](https://github.com/jaydee3/JDStatusBarNotification) ⭐ 4,331 | 🐛 5 | 🌐 Swift | 📅 2024-12-18
* tapkulibrary：tap + haiku = tapku, 一个精心设计的 iOS 开源框架。[官网](https://github.com/devinross/tapkulibrary) ⭐ 3,861 | 🐛 69 | 🌐 Objective-C | 📅 2017-11-24
* LiquidFloatingActionButton：流体状态的 Material Design 的浮动按钮。[官网](https://github.com/yoavlt/LiquidFloatingActionButton) ⭐ 3,840 | 🐛 53 | 🌐 Swift | 📅 2022-07-08
* DGElasticPullToRefresh：iOS 弹性下拉刷新控件，Swift 实现。★[官网](https://github.com/gontovnik/DGElasticPullToRefresh) ⭐ 3,735 | 🐛 58 | 🌐 Swift | 📅 2022-06-01
* TLYShyNavBar：不像那些 UINavigationBar 那么傲慢。这个 Bar 很谦虚！可以很容易地创建自动滚动的 navigation bar。[官网](https://github.com/telly/TLYShyNavBar) ⚠️ Archived
* DOFavoriteButton：一个可爱的动画按钮。★[官网](https://github.com/okmr-d/DOFavoriteButton) ⭐ 3,584 | 🐛 32 | 🌐 Swift | 📅 2022-06-13
* CVCalendar：支持 iOS 8+ 的自定义可视化日历，Swift（2.0）实现。★[官网](https://github.com/Mozharovsky/CVCalendar) ⭐ 3,475 | 🐛 32 | 🌐 Swift | 📅 2022-02-17
* ActionSheetPicker-3.0：为 iOS App 快速制作一个下拉 UIPickerView / ActionSheet 功能。[官网](https://github.com/skywinder/ActionSheetPicker-3.0/) ⭐ 3,381 | 🐛 19 | 🌐 Objective-C | 📅 2026-06-12
* gifu：iOS 上支持动态 GIF 的 Swift 框架。★[官网](https://github.com/kaishin/gifu) ⭐ 3,213 | 🐛 28 | 🌐 Swift | 📅 2025-08-17
* DynamicColor：又一个用于操作颜色的 Swift 扩展。★[官网](https://github.com/yannickl/DynamicColor) ⭐ 3,083 | 🐛 18 | 🌐 Swift | 📅 2023-11-30
* BLKFlexibleHeightBar：创建一个高度可以自动调整的 NavigationBar，类似 Facebook ，Square Cash，Safari 中的那样。[官网](https://github.com/bryankeller/BLKFlexibleHeightBar) ⭐ 3,067 | 🐛 40 | 🌐 Objective-C | 📅 2019-05-09
* VBFPopFlatButton：基于 Facebook POP制作的，有9种不同状态动画的扁平化按钮。[官网](https://github.com/victorBaro/VBFPopFlatButton) ⭐ 3,065 | 🐛 8 | 🌐 Objective-C | 📅 2024-07-15
* RKNotificationHub：让任何 UIView 变成完善的通知中心。[官网](https://github.com/cwRichardKim/RKNotificationHub) ⭐ 3,033 | 🐛 3 | 🌐 Objective-C | 📅 2018-11-02
* GuillotineMenu：铡刀样式过渡动画的下拉菜单。★[官网](https://github.com/Yalantis/GuillotineMenu/tree/swift_2.0) ⭐ 2,881 | 🐛 0 | 🌐 Swift | 📅 2020-04-13
* FontAwesomeKit：iOS 的图标字体库，现在支持 Font-Awesome，Foundation icons，Zocial 和 ionicons。[官网](https://github.com/PrideChung/FontAwesomeKit) ⭐ 2,802 | 🐛 55 | 🌐 Objective-C | 📅 2021-01-27
* BEMCheckBox：优雅的 iOS 复选框。(Check box)[官网](https://github.com/Boris-Em/BEMCheckBox#sample-app) ⭐ 2,609 | 🐛 27 | 🌐 Swift | 📅 2023-08-03
* STPopup：STPopup 为 iPhone 和 iPad 提供了一个 popup 样式的 UINavigationController。[官网](https://github.com/kevin0571/STPopup) ⭐ 2,583 | 🐛 40 | 🌐 Objective-C | 📅 2021-12-11
* SVWebViewController：一个非侵入式的内置浏览器。[官网](https://github.com/TransitApp/SVWebViewController) ⭐ 2,555 | 🐛 74 | 🌐 Objective-C | 📅 2020-04-30
* MDCSwipeToChoose：滑动卡片来决定 "喜欢" 或者 "不喜欢" 的控件，效果类似 Tinder App。可以用于在几分钟内创建识字卡 app，图片浏览器或者其他类似应用，而不用几小时。[官网](https://github.com/modocache/MDCSwipeToChoose) ⭐ 2,541 | 🐛 49 | 🌐 Objective-C | 📅 2018-01-29
* AnimatedTransitionGallery：使用 UIViewControllerAnimatedTransitioning 协议实现了自定义 iOS 7 过渡动画。[官网](https://github.com/shu223/AnimatedTransitionGallery) ⭐ 2,504 | 🐛 1 | 🌐 Objective-C | 📅 2024-04-30
* PagingMenuController：有可定制的菜单的分页视图控制器，Swift 实现。★[官网](https://github.com/kitasuke/PagingMenuController) ⚠️ Archived
* WobbleView：WobbleView 是一个实现了流行的摇晃效果的视图。你可以在应用中方便的添加动态的用户交互和过渡效果。★[官网](https://github.com/inFullMobile/WobbleView) ⭐ 2,169 | 🐛 2 | 🌐 Swift | 📅 2017-05-30
* MMPopupView：基于 Pop-up 的视图(例如，AlertSheet)，支持方便地定制。[官网](https://github.com/adad184/MMPopupView) ⚠️ Archived
* SweetAlert：为 iOS 应用提供了实时动画效果的 AlertView，Swift 编写而成。★[官网](https://github.com/codestergit/SweetAlert-iOS) ⭐ 2,030 | 🐛 47 | 🌐 Swift | 📅 2020-03-16
* PBJVision：iOS 相机引擎，支持点击拍摄，慢动作视频和图片捕捉功能。[官网](https://github.com/piemonte/PBJVision) ⚠️ Archived
* JLToast：iOS 的 Toast 组件，提供了简单的接口。★[官网](https://github.com/devxoul/JLToast) ⭐ 1,854 | 🐛 23 | 🌐 Swift | 📅 2024-09-03
* PullToBounce：UIScrollView 的下拉刷新控件。★[官网](https://github.com/entotsu/PullToBounce) ⭐ 1,851 | 🐛 18 | 🌐 Swift | 📅 2019-11-05
* ENSwiftSideMenu：一个 Swift 写的简洁 iOS7/8 侧滑菜单。★[官网](https://github.com/evnaz/ENSwiftSideMenu) ⭐ 1,800 | 🐛 91 | 🌐 Swift | 📅 2020-04-22
* SFFocusViewLayout：支持内容聚焦的 UICollectionViewLayout。[官网](https://github.com/fdzsergio/SFFocusViewLayout) ⭐ 1,751 | 🐛 13 | 🌐 Swift | 📅 2018-09-29
* MPParallaxView：Swift 实现的 Apple TV 视差效果。★[官网](https://github.com/DroidsOnRoids/MPParallaxView) ⭐ 1,734 | 🐛 2 | 🌐 Swift | 📅 2018-06-14
* KCFloatingActionButton：简洁的 iOS 浮动操作按钮。★[官网](https://github.com/kciter/KCFloatingActionButton) ⭐ 1,585 | 🐛 59 | 🌐 Swift | 📅 2022-08-25
* SAHistoryNavigationViewController：SAHistoryNavigationViewController 实现了一个在 iOS 上的类似任务管理器的 UI，兼容 UINavigationContoller,3D Touch。★[官网](https://github.com/szk-atmosphere/SAHistoryNavigationViewController) ⚠️ Archived
* MZTimerLabel：让 UILabel 变成 倒计时器或者秒表的便利类，类似苹果的时钟应用。[官网](https://github.com/mineschan/MZTimerLabel) ⭐ 1,551 | 🐛 26 | 🌐 Objective-C | 📅 2023-05-15
* MotionBlur：MotionBlur 让你可以在 iOS 动画效果上添加模糊效果。[官网](https://github.com/fastred/MotionBlur) ⭐ 1,499 | 🐛 1 | 🌐 Objective-C | 📅 2015-04-04
* CBZSplashView：Twitter 样式的启动页（Splash Screen）视图，缩放后显示主视图。[官网](https://github.com/callumboddy/CBZSplashView) ⭐ 1,478 | 🐛 13 | 🌐 Objective-C | 📅 2017-02-01
* TKRubberIndicator：Swift 版橡胶 PageControl 指示器。 <http://tbxark.github.io> ★[官网](https://github.com/TBXark/TKRubberIndicator) ⭐ 1,465 | 🐛 7 | 🌐 Swift | 📅 2024-08-21
* ParallaxTableViewHeader：UITableView header 的视差滚动效果组件。[官网](https://github.com/Vinodh-G/ParallaxTableViewHeader) ⭐ 1,346 | 🐛 13 | 🌐 Objective-C | 📅 2019-08-19
* LiquidLoader：液体动画的加载器组件。★[官网](https://github.com/yoavlt/LiquidLoader) ⭐ 1,325 | 🐛 8 | 🌐 Swift | 📅 2020-05-18
* Cool-iOS-Camera：一个完全可定制的现代的照相机，使用 AVFoundation 框架实现。[官网](https://github.com/GabrielAlva/Cool-iOS-Camera) ⭐ 1,305 | 🐛 10 | 🌐 Objective-C | 📅 2018-05-21
* AMSmoothAlert：一个很 cool 的 AlertView。[官网](https://github.com/mtonio91/AMSmoothAlert) ⭐ 1,253 | 🐛 15 | 🌐 Objective-C | 📅 2016-02-10
* SDevIconFonts：用于 Swift 的 Fontawesome, Iconic, Ionicons, Octicon。★[官网](https://github.com/0x73/SDevIconFonts) ⭐ 1,170 | 🐛 1 | 🌐 Swift | 📅 2022-08-05
* CardAnimation：卡片翻页动画效果。★[官网](https://github.com/seedante/CardAnimation) ⭐ 1,164 | 🐛 0 | 🌐 Swift | 📅 2021-01-20
* TVButton：重新创造一个非常酷的 Apple TV 视差图标用在 iOS UIButton 上（Swift 实现）。★[官网](https://github.com/marmelroy/TVButton) ⭐ 1,151 | 🐛 7 | 🌐 Swift | 📅 2019-03-02
* Splitflap：Swift 应用的分屏显示框架。★[官网](https://github.com/yannickl/Splitflap) ⭐ 1,077 | 🐛 9 | 🌐 Swift | 📅 2023-10-06
* UIScrollView-InfiniteScroll：支持无限滚动的 UIScrollView 类别。★[官网](https://github.com/pronebird/UIScrollView-InfiniteScroll) ⭐ 1,052 | 🐛 17 | 🌐 Objective-C | 📅 2022-09-25
* GaugeKit：可定制的仪表组件，可以方便地仿制苹果样式的仪表盘。★[官网](https://github.com/skywinder/GaugeKit) ⭐ 1,022 | 🐛 2 | 🌐 Swift | 📅 2022-04-10
* BRYXBanner：Swift 的 iOS7+ 样式的下拉通知。 ★[官网](https://github.com/bryx-inc/BRYXBanner) ⭐ 1,000 | 🐛 16 | 🌐 Swift | 📅 2023-08-16
* MZFormSheetPresentationController：MZFormSheetPresentationController 提供了一个原生 iOS UIModalPresentationFormSheet 的替代品，添加了对 iPhone 的支持，并且可以自定义 controller 的尺寸和表单的外观。[官网](https://github.com/m1entus/MZFormSheetPresentationController) ⭐ 964 | 🐛 26 | 🌐 Objective-C | 📅 2021-01-18
* TKSwitcherCollection：一个动画开关集合。<http://tbxark.github.io> ★[官网](https://github.com/TBXark/TKSwitcherCollection) ⭐ 916 | 🐛 3 | 🌐 Swift | 📅 2024-08-21
* Motif：一个基于 JSON 的可定制轻量级样式表框架。[官网](https://github.com/erichoracek/Motif) ⚠️ Archived
* RAReorderableLayout：可以拖拽放置的 UICollectionView 元素。[官网](https://github.com/ra1028/RAReorderableLayout) ⚠️ Archived
* HTPressableButton：扁平化设计的可以按压的按钮。[官网](https://github.com/herinkc/HTPressableButton) ⭐ 855 | 🐛 3 | 🌐 Objective-C | 📅 2016-08-25
* TisprCardStack：卡片 UI 库。★[官网](https://github.com/tispr/tispr-card-stack) ⭐ 849 | 🐛 8 | 🌐 Swift | 📅 2022-01-28
* EZSwipeController：![](/images/pointer.png.png)类似 Snapchat/Tinder/iOS 主页的 UIPageViewController。★[官网](https://github.com/goktugyil/EZSwipeController) ⭐ 837 | 🐛 23 | 🌐 Swift | 📅 2020-10-10
* NgKeyboardTracker：iOS 的键盘跟踪 Objective-C 库。[官网](https://github.com/meiwin/NgKeyboardTracker) ⭐ 792 | 🐛 0 | 🌐 Objective-C | 📅 2016-02-13
* cariocamenu：最快的无点击菜单。★[官网](https://github.com/arn00s/cariocamenu) ⚠️ Archived
* SevenSwitch：非侵入式的 iOS7 样式的开关替代品。★[官网](https://github.com/bvogelzang/SevenSwitch) ⭐ 771 | 🐛 13 | 🌐 Swift | 📅 2019-01-02
* AMTagListView：一个可以添加一系列高度可定制化的标签的 UIScrollView 子类。[官网](https://github.com/andreamazz/AMTagListView) ⭐ 757 | 🐛 8 | 🌐 Objective-C | 📅 2019-12-19
* Swift-Prompts：用来设计自定义提示的 Swift 库，有很大的范围可供选择。★[官网](https://github.com/GabrielAlva/Swift-Prompts) ⭐ 726 | 🐛 8 | 🌐 Swift | 📅 2018-04-24
* TTGSnackbar：在屏幕底部显示简单的消息和操作按钮，支持多种动画效果。★[官网](https://github.com/zekunyan/TTGSnackbar) ⭐ 649 | 🐛 0 | 🌐 Swift | 📅 2026-06-21
* EatFit：Eat fit 是一个受 Google Fit 启发的用于漂亮地展示数据的组件。[官网](https://github.com/Yalantis/EatFit) ⭐ 648 | 🐛 0 | 🌐 Swift | 📅 2020-04-13
* NYAlertViewController：可以自定义内容视图的 iOS AlertView，可高度自定义。[官网](https://github.com/nealyoung/NYAlertViewController) ⭐ 604 | 🐛 26 | 🌐 Objective-C | 📅 2023-05-15
* DatePickerDialog：在 UIAlertView 上显示 UIDatePicker 的 Swift 库。★[官网](https://github.com/squimer/DatePickerDialog-iOS-Swift) ⭐ 589 | 🐛 41 | 🌐 Swift | 📅 2023-11-29
* DAExpandAnimation：以自定义的模态过渡效果，从 cell 中展开来呈现控制器的库。★[官网](https://github.com/ifitdoesntwork/DAExpandAnimation) ⭐ 580 | 🐛 3 | 🌐 Swift | 📅 2025-02-01
* PickerView：Swift 实现的自定义的 UIPickerView 替代品。★[官网](https://github.com/filipealva/PickerView) ⭐ 525 | 🐛 9 | 🌐 Swift | 📅 2018-12-28
* PickerView：Swift 写的可定制的 UIPickerView 替代品。[官网](https://github.com/filipealva/PickerView) ⭐ 525 | 🐛 9 | 🌐 Swift | 📅 2018-12-28
* CZPicker：iOS 的 Popup 样式的 UIPickerView.[官网](https://github.com/chenzeyu/CZPicker) ⭐ 523 | 🐛 8 | 🌐 Objective-C | 📅 2024-03-09
* WCFastCell：滚动流畅的 Tables/Collections cell (没有动画)。[官网](https://github.com/wczekalski/WCFastCell) ⭐ 522 | 🐛 0 | 📅 2016-12-04
* iOS-CircleProgressView：这个空间允许用户用代码或者 interface builder 初始化或创建并渲染一个圆形的进度条视图。★[官网](https://github.com/CardinalNow/iOS-CircleProgressView) ⭐ 514 | 🐛 5 | 🌐 Swift | 📅 2019-08-29
* ScrollPager：类似 Flipboard 的滚动翻页。★[官网](https://github.com/aryaxt/ScrollPager) ⭐ 507 | 🐛 13 | 🌐 Swift | 📅 2020-10-22
* EZAlertController：便捷的 Swift UIAlertController。★[官网](https://github.com/thellimist/EZAlertController) ⭐ 364 | 🐛 4 | 🌐 Swift | 📅 2023-05-12
* HDNotificationView：使用模仿原生的通知横幅 UI，发出任何警告。[官网](https://github.com/nhdang103/HDNotificationView) ⭐ 355 | 🐛 1 | 🌐 Swift | 📅 2018-11-29
* PMTween：优雅灵活的 iOS 渐变库。[官网](https://github.com/poetmountain/PMTween) ⭐ 343 | 🐛 0 | 🌐 Objective-C | 📅 2016-07-19
* SwiftWebVC：一个 SVWebViewController 的 Swift 实现。★[官网](https://github.com/meismyles/SwiftWebVC) ⭐ 327 | 🐛 23 | 🌐 Swift | 📅 2021-07-05
* JTMaterialSwitch：一个受 Google 的 Material Design 启发的可定制的开关 UI，有波纹效果和弹性动画。[官网](https://github.com/JunichiT/JTMaterialSwitch) ⭐ 316 | 🐛 2 | 🌐 Objective-C | 📅 2015-12-07
* MediumMenu：一个基于 Medium iOS 应用的菜单。★[官网](https://github.com/pixyzehn/MediumMenu) ⚠️ Archived
* IQDropDownTextField：提供了下拉 UIPickerView 支持的 UITextField。[官网](https://github.com/hackiftekhar/IQDropDownTextField) ⭐ 312 | 🐛 0 | 🌐 Swift | 📅 2025-02-19
* HTYTextField：一个有弹性的站位文字的 UITextField。★[官网](https://github.com/hanton/HTYTextField) ⭐ 309 | 🐛 5 | 🌐 Swift | 📅 2019-11-02
* SSBouncyButton：有弹性的 iOS7 样式按钮 UI 组件。[官网](https://github.com/StyleShare/SSBouncyButton) ⭐ 305 | 🐛 0 | 🌐 Objective-C | 📅 2016-07-28
* RadialMenu：RadialMenu 是一个提供了触控的上下文菜单（类似 iOS8 中 iMessage 的录制按钮）的自定义控件。使用 Swift 和 POP 框架构建。★[官网](https://github.com/bradjasper/radialmenu) ⭐ 302 | 🐛 5 | 🌐 Swift | 📅 2022-08-15
* SAInboxViewController：受到 "Inbox by google" 动画过渡效果启发的 UIViewController 子类。★[官网](https://github.com/szk-atmosphere/SAInboxViewController) ⚠️ Archived
* TTGEmojiRate：iOS 的类似 emoji 的评分视图。★[官网](https://github.com/zekunyan/TTGEmojiRate) ⭐ 288 | 🐛 0 | 🌐 Swift | 📅 2026-06-21
* InteractivePlayerView：自定义的 iOS 音乐播放器视图。★[官网](https://github.com/AhmettKeskin/InteractivePlayerView) ⭐ 272 | 🐛 4 | 🌐 Swift | 📅 2018-09-06
* ARAutocompleteTextView：subclass of 实时显示文本提示的 UITextView 的子类。完美支持 e-mail 格式。[官网](https://github.com/alexruperez/ARAutocompleteTextView) ⭐ 264 | 🐛 5 | 🌐 Objective-C | 📅 2019-10-26
* KCJogDial：提供控制功能的 UIView，类似一个转轮控制器。★[官网](https://github.com/kciter/KCHorizontalDial) ⭐ 213 | 🐛 3 | 🌐 Swift | 📅 2019-06-14
* HoneycombView：HoneycombView 是用来显示类似 Honyecomb 布局的 iOS UIView，由 Swift 实现。★[官网](https://github.com/suzuki-0000/HoneycombView) ⭐ 203 | 🐛 2 | 🌐 Swift | 📅 2016-03-23
* RPLoadingAnimation：Swift 实现的基于 CALayer 的加载动画。★[官网](https://github.com/naoyashiga/RPLoadingAnimation) ⭐ 197 | 🐛 1 | 🌐 Swift | 📅 2016-09-26
* NMPopUpView：用于显示浮动窗口的简单 iOS 类。支持 Swift 和 Objective-C。★[官网](https://github.com/psy2k/NMPopUpView) ⭐ 194 | 🐛 2 | 🌐 Swift | 📅 2022-11-02
* HorizontalProgress：简单的动画水平进度条。[官网](https://github.com/AliThink/HorizontalProgress) ⭐ 181 | 🐛 2 | 🌐 Objective-C | 📅 2017-02-07
* VLDContextSheet：类似 Pinterest iOS app 中的菜单。[官网](https://github.com/vangelov/VLDContextSheet) ⭐ 174 | 🐛 5 | 🌐 Objective-C | 📅 2015-09-29
* StarryStars：iOS GUI 库，用于显示和编辑评分。[官网](https://github.com/peterprokop/StarryStars?utm_campaign=explore-email\&utm_medium=email\&utm_source=newsletter\&utm_term=daily) ⭐ 173 | 🐛 5 | 🌐 Swift | 📅 2019-10-26
* phone-number-picker：一个 Swift 实现的简单易用的视图控制器，类似 WhatsApp 那样让你输入带有国家代码电话号码。★[官网](https://github.com/hughbe/phone-number-picker) ⭐ 138 | 🐛 2 | 🌐 Swift | 📅 2018-02-05
* ColorArt：从图片中取出主要颜色，类似 iTunes 11 的效果。[官网](https://github.com/vinhnx/ColorArt) ⭐ 131 | 🐛 0 | 🌐 Objective-C | 📅 2016-04-22
* ESTabBarController：一个允许高亮按钮和自定义按钮动作的 Tabbar 控制器。[官网](https://github.com/ezescaruli/ESTabBarController) ⭐ 127 | 🐛 4 | 🌐 Objective-C | 📅 2018-02-23
* JTFadingInfoView：一个基于 UIButton 的支持淡入淡出动画特性的视图。[官网](https://github.com/JunichiT/JTFadingInfoView) ⭐ 127 | 🐛 0 | 🌐 Objective-C | 📅 2015-09-30
* KCSelectionDialog：简单的选择对话框。★[官网](https://github.com/kciter/KCSelectionDialog) ⭐ 116 | 🐛 1 | 🌐 Swift | 📅 2019-10-30
* Hamburger-Menu-Button：一个高度可定制的汉堡包菜单按钮。★[官网](https://github.com/toannt/Hamburger-Menu-Button) ⭐ 112 | 🐛 3 | 🌐 Swift | 📅 2019-10-04
* JDSwiftAvatarProgress：方便自定义的异步加载展位图进度条动画。★[官网](https://github.com/JellyDevelopment/JDSwiftAvatarProgress) ⭐ 85 | 🐛 2 | 🌐 Shell | 📅 2016-09-22
* YXTPageView：一个支持 UIView 和 UITableView 之间滚动切换的 PageView。[官网](https://github.com/hanton/YXTPageView) ⭐ 68 | 🐛 1 | 🌐 Objective-C | 📅 2017-04-18
* MVAutocompletePlaceSearchTextField：一个类似 Google Places，Uber 等位置搜索的非侵入式自动完成控件。[官网](https://github.com/mrugrajsinh/MVAutocompletePlaceSearchTextField) ⭐ 67 | 🐛 8 | 🌐 Objective-C | 📅 2020-01-10
* MVMaterialView：用来模仿 Material Design 概念波纹（Ripple）效果 UI 控件的子类和 UIButton。[官网](https://github.com/mrugrajsinh/MVMaterialView) ⭐ 63 | 🐛 2 | 🌐 Objective-C | 📅 2019-05-14
* RadialLayer：可点击元素的动画。★[官网](https://github.com/soheil/RadialLayer) ⭐ 60 | 🐛 1 | 🌐 Swift | 📅 2015-11-21
* DLWBouncyView：BouncyView 是一个为所有视图都实现了最近流行的弹性效果的框架。[官网](https://github.com/cute/DLWBouncyView) ⭐ 52 | 🐛 0 | 🌐 Objective-C | 📅 2015-09-11
* Form：JSON 驱动的列表控件。[官网](https://github.com/hyperoslo/Form) ⭐ 36 | 🐛 0 | 🌐 Objective-C | 📅 2018-08-22
* JRSplitVC：自适应布局的 UISplitViewController。[官网](https://github.com/tommypeps/JRSplitVC) ⭐ 31 | 🐛 0 | 🌐 Objective-C | 📅 2015-12-21
* PJAlertView：苹果弃用了原来好用的警告视图，让我们失去了很多的定制性，这个库重新将定制性带回来。[官网](https://github.com/PrajeetShrestha/PJAlertView) ⭐ 6 | 🐛 0 | 🌐 Objective-C | 📅 2015-07-06
* BetweenKit：一个健壮的 iOS 拖拽框架。[官网](https://github.com/ice3-software/between-kit)
* NZAlertView：简单直观的 AlertView。类似推送通知的效果。[官网](https://github.com/NZN/NZAlertView)
* TGCameraViewController：基于 AVFoundation 的自定义相机。样式漂亮，轻量并且可以很容易地集成到 iOS 项目中。[官网](https://github.com/tdginternet/TGCameraViewController)
* SDevBootstrapButton：Swift 版的 Twitter Bootstrap 按钮。★[官网](https://github.com/0x73/SDevBootstrapButton)
* SDevCircleButton：Swift 实现的圆型按钮。★[官网](https://github.com/0x73/SDevCircleButton)
* SDevFlatColors：Swift 实现的扁平化颜色。★[官网](https://github.com/0x73/SDevFlatColors)
* Atlas：为 Layer 设计的原生 iOS 消息应用 UI 组件。[官网](https://github.com/layerhq/Atlas-iOS)
* Cocoa Controls：开源的 iOS 和 OS X UI 组件.[官网](https://www.cocoacontrols.com/)
* ComponentKit：受到 React 启发的 iOS 框架，Facebook 出品A React-Inspired View Framework for iOS, by Facebook.[官网](http://componentkit.org/)
* CollapsableTable：可以自定义 section header 的可折叠 tableview section。★[官网](https://github.com/rob-nash/CollapsableTable)
* EXTView：使用 IB\_DESIGNABLE 和 IBInspectable 为 Interface Builder 提供了 UIView 扩展。[官网](https://github.com/recruit-mtl/EXTView)
* UITextField-Shake：添加了摇晃动画的 UITextField 类别。[也有 Swift 版本](https://github.com/King-Wizard/UITextField-Shake-Swift) ★[官网](https://github.com/andreamazz/UITextField-Shake) ⭐ 726 | 🐛 0 | 🌐 Objective-C | 📅 2017-12-14
* Atlas-iOS：Atlas 是一个原生 iOS 对话 UI Layer 组件。[官网](https://atlas.layer.com/ios)
* YALField：使用 interface builder 更容易地创建表单 UI。包含带合法性验证的自定义字段。[官网](https://github.com/Yalantis/YALField?utm_campaign=Indie%2BiOS%2BFocus%2BWeekly\&utm_medium=email\&utm_source=Indie_iOS_Focus_Weekly_43)

### <a name="websocket"></a>WebSocket

* Socket Rocket：一个一致的 Objective-C WebSocket 客户端库。[官网](https://github.com/square/SocketRocket) ⭐ 9,608 | 🐛 190 | 🌐 Objective-C | 📅 2025-12-04

### <a name="code-quality"></a>代码质量

* SwiftLint：一个实验性的工具，用于强化 Swift 的代码风格和习惯。★[官网](https://github.com/realm/SwiftLint) ⭐ 19,717 | 🐛 501 | 🌐 Swift | 📅 2026-08-30
* Flex：一个嵌入 iOS App 的调试和探索工具。[官网](https://github.com/Flipboard/FLEX) ⭐ 14,634 | 🐛 49 | 🌐 Objective-C | 📅 2026-06-11
* [chisel](http://hao.importnew.com/chisel/)：iOS app 的辅助调试工具，提供了一系列的 LLDB 命令。[官网](https://github.com/facebook/chisel) ⭐ 9,180 | 🐛 50 | 🌐 Python | 📅 2026-03-15
* DCIntrospect：小型的 iOS 可视化调试工具库。[官网](https://github.com/domesticcatsoftware/DCIntrospect) ⭐ 2,165 | 🐛 29 | 🌐 Objective-C | 📅 2019-04-07
* KZBootstrap：一系列的脚本和注释，代码质量很差时，在编译时产生额外的错误和警告。[官网](https://github.com/krzysztofzablocki/KZBootstrap) ⭐ 2,037 | 🐛 3 | 🌐 Objective-C | 📅 2020-10-20
* Watchdog：一个用于记录阻塞主线程的过重任务的类。★[官网](https://github.com/wojteklu/Watchdog) ⭐ 1,873 | 🐛 1 | 🌐 Swift | 📅 2024-06-14
* [spacecommander](http://hao.importnew.com/spacecommander/)：像一个团队那样，提交完全格式化的 Objective-C 代码。[官网](https://github.com/square/spacecommander) ⭐ 1,122 | 🐛 14 | 🌐 Objective-C | 📅 2025-08-26
* DWURecyclingAlert：优化 UITableViewCell 的滚动流畅性。[官网](https://github.com/diwu/DWURecyclingAlert) ⭐ 557 | 🐛 1 | 🌐 Objective-C | 📅 2017-04-18
* SwiftCop：SwiftCop 是一个很实用的格式验证库，灵感来自 Ruby On Rails 清晰的活动记录验证。★[官网](https://github.com/andresinaka/SwiftCop) ⭐ 535 | 🐛 1 | 🌐 Swift | 📅 2019-04-07
* ocstyle：Objective-C 代码风格检查器。[官网](https://github.com/Cue/ocstyle) ⭐ 253 | 🐛 2 | 🌐 Python | 📅 2017-02-22
* KZAsserts：一系列的自定义断言，使用 DSL 来自动生成 NSError，允许在 Debug 时断言和在 Release 时捕获错误。[官网](https://github.com/krzysztofzablocki/KZAsserts) ⭐ 99 | 🐛 0 | 🌐 Objective-C | 📅 2023-02-22
* PSPDFUIKitMainThreadGuard：简洁的代码片段，当 UIKit 在后台线程被使用时生成断言。[官网](https://gist.github.com/steipete/5664345)
* [OCLint](http://hao.importnew.com/oclint/)：静态代码分析工具，用以提高代码质量，减少瑕疵。[官网](http://oclint.org/)
* Tailor：跨平台的 Swift 代码静态分析器，它帮助你编写更加清洁的代码，避免 bug。[官网](https://tailor.sh/)

### <a name="analytics"></a>分析

* ARAnalytics：抽象的分析框架，提供了聪明的 API 来跟踪事件和用户数据。[官网](https://github.com/orta/ARAnalytics) ⭐ 1,826 | 🐛 19 | 🌐 Objective-C | 📅 2017-09-15
* Segment：将分析继承进 iOS 应用中的简单方式。[官网](https://github.com/segmentio/analytics-ios) ⭐ 417 | 🐛 43 | 🌐 Objective-C | 📅 2025-03-27
* Flurry Analytics：免费的 App 分析 API。[官网](http://www.flurry.com)
* Parse Analytics：测量 App 的使用情况，跟踪 bug 等等。[官网](https://parse.com/products/analytics)
* Mixpanel：高级分析平台。[官网](https://mixpanel.com/)
* Localytics：将 app 的营销和数据分析结合起来。[官网](http://www.localytics.com/)
* Answers by Fabric：让你实时的洞悉用户体验。[官网](https://answers.io/)
* Liquid Analytics：通过分析和个性化的实时反馈辨认特定的行为。[官网](https://onliquid.com)
* GTrack：Google Analytics 对 iOS 的轻量级 Objective-C 封装，并且提供了一些额外的功能。[官网](https://github.com/gemr/GTrack)

### <a name="payments"></a>支付

* Venmo：在你的应用中支持和接受通过 Venmo 的支付。[官网](https://github.com/venmo/venmo-ios-sdk) ⚠️ Archived
* Stripe：将 Apple Pay 支付继承到你的应用中。很适合那些缺少后台知识的开发者。[官网](https://stripe.com)
* Braintree：提供 5 万美金的免费支付额度，需要后台支持。[官网](https://www.braintreepayments.com)
* Moltin：使用简单的 SDK 为应用添加 eCommerce，你可以创建一个销售产品的商店，不需要后端支持。[官网](https://moltin.com/ios-ecommerce-sdk)

### <a name="products"></a>生产力

* Import.io：将网页即时转换为数据。[官网](https://import.io)
* Tapglue：是用很少的代码来构建社交产品和活动的 feed。[官网](https://www.tapglue.com)

### <a name="utility"></a>工具

* DateTools：简便的 Objective-C 日期和时间工具。[官网](https://github.com/MatthewYork/DateTools) ⭐ 7,179 | 🐛 109 | 🌐 Objective-C | 📅 2024-08-21
* Async：Swift 的 GCD 异步派发语法糖。★[官网](https://github.com/duemunk/Async) ⭐ 4,556 | 🐛 4 | 🌐 Swift | 📅 2024-04-11
* Colours：这是一套与定义的颜色和颜色方法，让你的 iOS／OS X 开发更加方便。[官网](https://github.com/bennyguitar/Colours) ⭐ 3,086 | 🐛 13 | 🌐 Objective-C | 📅 2019-09-22
* EZSwiftExtensions：:smirk:标准类型和类是如何工作的。★[官网](https://github.com/goktugyil/EZSwiftExtensions) ⭐ 2,973 | 🐛 34 | 🌐 Swift | 📅 2024-04-05
* EKAlgorithms：一些知名的计算机科学算法和数据结构的 Objective-C 实现。[官网](https://github.com/EvgenyKarkan/EKAlgorithms) ⭐ 2,406 | 🐛 6 | 🌐 Objective-C | 📅 2024-09-19
* ObjectiveSugar：Ruby 风格的 ObjectiveC 附件。[官网](https://github.com/supermarin/ObjectiveSugar) ⚠️ Archived
* GroundControl：iOS 远程配置。[官网](https://github.com/mattt/GroundControl) ⚠️ Archived
* RandomKit：Swift 随机数据生成器。★[官网](https://github.com/nvzqz/RandomKit/) ⭐ 1,457 | 🐛 14 | 🌐 Swift | 📅 2022-06-09
* Underscore.m：用来操作数据的 DSL。[官网](https://github.com/robb/Underscore.m) ⚠️ Archived
* ClusterPrePermissions：可重用的预授权工具，它可以让开发者在对话中获取系统权限之前询问用户。[官网](https://github.com/clusterinc/ClusterPrePermissions) ⭐ 1,189 | 🐛 11 | 🌐 Objective-C | 📅 2017-09-26
* ChineseIDCardOCR: 利用前馈神经网络对身份证信息做OCR识别。 ★ [官网](https://github.com/KevinGong2013/ChineseIDCardOCR) ⭐ 1,025 | 🐛 5 | 🌐 Swift | 📅 2018-02-07
* Tactile：安全并且更加合乎习惯的响应收拾和控件事件的方式。★[官网](https://github.com/delba/Tactile) ⭐ 712 | 🐛 0 | 🌐 Swift | 📅 2019-11-16
* YOLOKit：让方块透过圆洞。[官网](https://github.com/mxcl/YOLOKit) ⭐ 662 | 🐛 2 | 🌐 Objective-C | 📅 2026-06-03
* SwiftRandom：随即数据生成器。★[官网](https://github.com/thellimist/SwiftRandom) ⭐ 556 | 🐛 6 | 🌐 Swift | 📅 2020-01-29
* ReflectableEnum：Objective-C 枚举的反射。[官网](https://github.com/fastred/ReflectableEnum) ⭐ 331 | 🐛 4 | 🌐 Objective-C | 📅 2017-01-28
* GCDKit：GCD 的 Swift 简化版。★[官网](https://github.com/JohnEstropia/GCDKit) ⭐ 316 | 🐛 2 | 🌐 Swift | 📅 2017-04-01
* SBConstants：生成一个包含了 storyboard 中所有 identifier 的常量文件。[官网](https://github.com/paulsamuels/SBConstants) ⭐ 312 | 🐛 10 | 🌐 Ruby | 📅 2017-04-21
* VWWPermissionKit：可视化的 iOS 权限管理器。[官网](https://github.com/zakkhoyt/VWWPermissionKit) ⭐ 143 | 🐛 9 | 🌐 Objective-C | 📅 2020-03-02
* XExtensionItem：方便地在 iOS 应用和分享扩展至简分享数据。[官网](https://github.com/tumblr/XExtensionItem) ⭐ 85 | 🐛 8 | 🌐 Objective-C | 📅 2024-04-03
* OpinionatedC：让 Objective-C 继承更多 Smalltalk 特性。[官网](https://github.com/leoschweizer/OpinionatedC) ⭐ 52 | 🐛 2 | 🌐 Objective-C | 📅 2021-06-01

### <a name="security"></a>安全

* libextobjc：一个用于扩展 Objective-C 编程语言的 Cocoa。[官网](https://github.com/jspahrsummers/libextobjc) ⚠️ Archived
* Valet：在 iOS 和 OS X 的 Keychain 中安全地存储数据，然而你无需知道 keychain 的具体工作细节。[官网](https://github.com/square/Valet) ⭐ 4,175 | 🐛 1 | 🌐 Swift | 📅 2026-07-12
* UICKeyChainStore：UICKeyChainStore 是一个对 Keychain 的简洁封装。[官网](https://github.com/kishikawakatsumi/UICKeyChainStore) ⭐ 3,085 | 🐛 24 | 🌐 Objective-C | 📅 2023-10-14
* Locksmith：方便 Keychain 使用的强大的 Swift 面向协议库。★[官网](https://github.com/matthewpalmer/Locksmith) ⭐ 2,911 | 🐛 59 | 🌐 Swift | 📅 2024-03-22
* cocoapods-keys：一个用来存储环境和应用键值的键值存储。[官网](https://github.com/orta/cocoapods-keys) ⭐ 1,548 | 🐛 50 | 🌐 Ruby | 📅 2023-09-01
* simple-touch：非常简单的生物识别认证服务（Touch ID）的 Swift 封装。[官网](https://github.com/simple-machines/simple-touch) ⭐ 121 | 🐛 2 | 🌐 Swift | 📅 2016-12-19

# <a name="project-setup"></a>项目安装

* [Darling](http://hao.importnew.com/darling/)：在 Linux 运行 OS X 二进制文件。[官网](http://www.darlinghq.org)、[GitHub](https://github.com/LubosD/darling) ⭐ 13,127 | 🐛 398 | 🌐 Objective-C | 📅 2026-08-30
* KZBootstrap：iOS 项目的 bootstrap，目的是高质量的编码。[官网](https://github.com/krzysztofzablocki/KZBootstrap) ⭐ 2,037 | 🐛 3 | 🌐 Objective-C | 📅 2020-10-20
* liftoff：另一个用于创建 iOS 项目的 CLI。[官网](https://github.com/thoughtbot/liftoff) ⚠️ Archived
* crafter：这是一个允许你使用自定义的领域专用语言（DSL）语法来配置你的 iOS 项目模版的命令行工具（CLI），使用简单但性能强大。[官网](https://github.com/krzysztofzablocki/crafter) ⭐ 548 | 🐛 7 | 🌐 Ruby | 📅 2017-03-06
* amaro：优秀的 iOS 样板。[官网](https://github.com/crushlovely/Amaro) ⚠️ Archived
* chairs：交换你的 iOS 模拟器文档。[官网](https://github.com/orta/chairs) ⭐ 226 | 🐛 6 | 🌐 Ruby | 📅 2015-05-08

# <a name="dependency--package-manager"></a>依赖 / 包管理

* Carthage：简单的分布式的 Cocoa 依赖管理器。★[官网](https://github.com/Carthage/Carthage) ⭐ 15,167 | 🐛 217 | 🌐 Swift | 📅 2025-09-10
* CocoaSeeds：Cocoa 的 Git 子模块替代品。[官网](https://github.com/devxoul/CocoaSeeds) ⚠️ Archived
* SWM (Swift Modules)：一个类似 npm（node.js的包管理器）或者 bower（Twitter 的浏览器的包管理器） 的 Swift 项目的包／依赖管理器，无需使用 Xcode。★[官网](https://github.com/jankuca/swm) ⭐ 61 | 🐛 1 | 🌐 Swift | 📅 2014-12-13
* Cocoa Pods：CocoaPods 是一个 Objective-C 项目的依赖管理工具。它拥有成千上万个库，它们可以使你的项目更加优雅。[官网](https://cocoapods.org/)
* Xcode Maven：Xcode Maven 插件，它可以将 Xcode 构建过程嵌入 Maven 的生命周期中。[官网](http://sap-production.github.io/xcode-maven-plugin/site/)
* Gradle：Xcode 的 gradle 插件，可以使用 gradle 来构建 iOS 或者 Mac OS X 项目。[官网](http://openbakery.org/gradle.html)
* Alcatraz：Xcode 包管理工具.[官网](http://alcatraz.io/)

# <a name="testing"></a>测试

### <a name="tdd--bdd"></a>测试驱动开发／行为驱动开发（TDD / BDD）

* Quick：Swift 和 Objective-C 的 BDD 框架。[官网](https://github.com/Quick/Quick) ⭐ 9,829 | 🐛 49 | 🌐 Swift | 📅 2026-05-18
* OHHTTPStubs：方便地为你的网络请求做存根（Stub）! 使用网络假数据测试你的 app ，你也可以自定义响应时间，响应代码和响应头！[官网](https://github.com/AliSoftware/OHHTTPStubs) ⭐ 5,074 | 🐛 59 | 🌐 Objective-C | 📅 2024-05-09
* Kiwi：一个用于 iOS 开发的 BDD 库。[官网](https://github.com/kiwi-bdd/Kiwi) ⭐ 4,112 | 🐛 89 | 🌐 Objective-C | 📅 2023-09-05
* Specta：轻量级 TDD / BDD Objective-C & Cocoa 开发框架。[官网](https://github.com/specta/specta) ⭐ 2,313 | 🐛 18 | 🌐 Objective-C | 📅 2022-02-27
* gh-unit：Objective-C 的测试框架。[官网](https://github.com/gh-unit/gh-unit) ⚠️ Archived
* XcodeCoverage：Xcode 项目代码覆盖率。[官网](https://github.com/jonreid/XcodeCoverage) ⭐ 854 | 🐛 1 | 🌐 Perl | 📅 2022-10-14
* LayoutTest-iOS：一个测试视图的布局的框架，支持多种配置。[官网](https://github.com/linkedin/LayoutTest-iOS) ⭐ 558 | 🐛 9 | 🌐 Objective-C | 📅 2024-05-03
* Dixie：Dixie 是一个开源的 Objective-C 测试框架。用于改变对象的行为。[官网](https://github.com/Skyscanner/Dixie) ⚠️ Archived

### <a name="ui-testing"></a>UI 测试

* Kif：一个 iOS 的函数式测试框架。[官网](https://github.com/kif-framework/KIF) ⭐ 6,249 | 🐛 56 | 🌐 Objective-C | 📅 2026-08-13
* Remote：在 Xcode 内部控制你的 iPhone 来做端到端的测试。[官网](https://github.com/johnno1962/Remote) ⭐ 886 | 🐛 0 | 🌐 Objective-C | 📅 2022-09-18
* Subliminal：一个保守的 iOS 集成测试框架。[官网](https://github.com/inkling/Subliminal) ⭐ 753 | 🐛 45 | 🌐 Objective-C | 📅 2025-05-19
* robotframework-appiumlibrary：AppiumLibrary 是一个用于 RobotFramwork 的 appium 测试框架。[官网](https://github.com/jollychang/robotframework-appiumlibrary) ⭐ 429 | 🐛 28 | 🌐 Python | 📅 2026-03-10
* CrashMonkey：iOS 平台的 Monkey 测试工具。[官网](https://github.com/mokemokechicken/CrashMonkey) ⭐ 202 | 🐛 9 | 🌐 Ruby | 📅 2020-10-01
* appium：Appium 是一个开源自动化测试框架。用于测试原生或者混合 app。[官网](http://appium.io/)
* Cucumber：iOS BDD 框架。[官网](https://cucumber.io/)
* UIAutomation：一个使用脚本在连接着的设备上测试你的用户界面元素的 JavaScript 库。[官网](https://developer.apple.com/library/ios/documentation/DeveloperTools/Reference/UIAutomationRef/)
* ios-driver：使用 Selenium / WebDriver 测试任何 iOS 原生，混合或者移动 web 应用。[官网](http://ios-driver.github.io/ios-driver/index.html)
* Zucchini：可视化的 iOS 测试框架。[官网](https://github.com/zucchini-src/zucchini)

### <a name="other-testing"></a>其他测试

* PonyDebugger：使用 Chrome 开发者工具对你的 iOS app 进行远程网络和数据调试。[官网](https://github.com/square/PonyDebugger) ⭐ 5,853 | 🐛 46 | 🌐 Objective-C | 📅 2023-03-18
* ios-snapshot-test-case：使用屏幕快照的 iOS 单元测试。[官网](https://github.com/facebook/ios-snapshot-test-case) ⚠️ Archived
* NaughtyKeyboard：一个危险字符串的大列表，当用户输入这些字符串使有很大的可能会造成 bug，这是一个用于在你的 iOS 设备上测试你 app 的键盘。[官网](https://github.com/Palleas/NaughtyKeyboard)

### <a name="beta-distribution"></a>Beta 测试版本发布

* boarding：即时为 TestFlight beta 测试者创建简单的注册页面。[官网](https://github.com/fastlane/boarding) ⭐ 881 | 🐛 54 | 🌐 Ruby | 📅 2024-03-18
* Crashlytics：一个崩溃报告和 beta 测试服务。[官网](https://try.crashlytics.com/)
* TestFlight Beta Testing：iTunes Connect 支持的 beta 测试服务。[官网](https://developer.apple.com/testflight/)
* HockeyApp：在 HockeyApp 你可以发布你 app 的 beta 测试版本，收集实时的崩溃报告，获取用户反馈，分析测试覆盖率。[官网](http://hockeyapp.net/)

# <a name="toolchains"></a>工具链

* RubyMotion：RubyMotion 是一个革命性的工具链。它可以让你快速地开发和测试原生 iOS 和 OS X 应用，全部使用 Ruby 语言。[官网](http://www.rubymotion.com/)

# <a name="tools"></a>工具

* DoraemonKit: 一款功能齐全的iOS研发助手，你值得拥有。[官网](https://www.dokit.cn/) [Github](https://github.com/didi/DoraemonKit) ⭐ 20,403 | 🐛 276 | 🌐 Java | 📅 2026-08-31
* R.swift：在 Swift 项目中，强类型的自动补全资源名称的工具，包括图片，单元格和 segue 的工具。★[官网](https://github.com/mac-cain13/R.swift) ⭐ 9,561 | 🐛 78 | 🌐 Swift | 📅 2025-04-01
* SwiftGen：一个生成 Swift 代码工具的集合（生成资源的枚举，storyboard，本地化字符串和 UIColor）。★[官网](https://github.com/AliSoftware/SwiftGen) ⭐ 9,547 | 🐛 157 | 🌐 Swift | 📅 2026-04-16
* [Laptop](http://hao.importnew.com/laptop/)：一个让Mac OS X或Linux更智能的shell脚本。[官网](https://thoughtbot.com/open-source) [Github](https://github.com/thoughtbot/laptop) ⭐ 8,555 | 🐛 1 | 🌐 Shell | 📅 2026-08-13
* Localize-Swift：Swift 2.0 实现在应用中切换语言的功能，帮助你的 APP 实现友好的本地化和国际化。★[官网](https://github.com/marmelroy/Localize-Swift) ⭐ 3,123 | 🐛 76 | 🌐 Swift | 📅 2023-09-06
* Provisioning：一个查看器插件，用于预览 .mobileprovision 文件。[官网](https://github.com/chockenberry/Provisioning) ⭐ 1,541 | 🐛 12 | 🌐 Objective-C | 📅 2017-12-21
* Blade：为 iOS 和 OS X 应用生成 Xcode 图片目录，全局图片和其他相关的东西。[官网](https://github.com/jondot/blade) ⭐ 817 | 🐛 9 | 🌐 Go | 📅 2017-12-08
* Shark：用于将 .xcassets 文件夹转换成一个类型安全枚举的 Swift 脚本。★[官网](https://github.com/kaandedeoglu/Shark) ⭐ 382 | 🐛 0 | 🌐 Swift | 📅 2026-08-21
* Retini：一个超级简单的 Retina（2x，3x）图片转换器。[官网](https://github.com/terwanerik/Retini) ⭐ 198 | 🐛 2 | 🌐 Objective-C | 📅 2021-05-09
* Strsync：自动翻译并且使 .strings 文件和默认语言同步。[官网](https://github.com/metasmile/strsync)

# <a name="rapid-development"></a>快速开发

* injectionforxcode：代码注入，支持 Swift。[官网](https://github.com/johnno1962/injectionforxcode) ⭐ 6,540 | 🐛 76 | 🌐 Objective-C | 📅 2022-08-04
* KZPlayground：Objective-C 版本的 Playground。[官网](https://github.com/krzysztofzablocki/KZPlayground) ⭐ 2,627 | 🐛 1 | 🌐 Objective-C | 📅 2022-07-19
* dyci：代码注入工具。[官网](https://github.com/DyCI/dyci-main) ⚠️ Archived
* MMBarricade：在运行时为 iOS app 配置本地服务器。[官网](https://github.com/mutualmobile/MMBarricade) ⭐ 344 | 🐛 2 | 🌐 Objective-C | 📅 2017-08-02
* NetworkObjects：根据你的 Core Data 模型生成 RESTful 服务器。[官网](https://github.com/colemancda/NetworkObjects) ⭐ 259 | 🐛 2 | 🌐 Swift | 📅 2023-08-26
* STV Framework：开发原生 iOS app 的可视化开发工具。[官网](http://www.sensiblecocoa.com)

# <a name="deployment"></a>部署

* [fastlane](https://github.com/fastlane/fastlane) ⭐ 42,047 | 🐛 664 | 🌐 Ruby | 📅 2026-08-31 将所有 iOS 部署工具整合到一个工作流中。
* [deliver](https://github.com/fastlane/deliver) ⚠️ Archived 部署截屏，app 元数据和 AppStore app 更新，这一切只需要一个命令就可以搞定。
* [snapshot](https://github.com/fastlane/snapshot) ⚠️ Archived 自动地创建全部语言和全部设备的屏幕截图。

# <a name="app-store"></a>App Store

* [Average App Store Review Times](http://appreviewtimes.com) 这个网站可以同时跟踪 AppStore 上 iOS 和 Mac 两个版本的浏览次数，使用了利用 iOS 和 Mac 开发者的众包数据。
* [Apple's Common App Rejections Styleguide](https://developer.apple.com/app-store/review/rejections/) 一些导致 app 被苹果拒绝的重要常见问题。
* [Free App Store Optimization Tool](https://www.mobileaction.co) 在关键字和竞争者的角度上，让你可视化地追踪你的 App Store 数据。

# <a name="sdk"></a>SDK

## 官方的

* [Facebook](https://github.com/facebook/facebook-ios-sdk) ⭐ 8,093 | 🐛 152 | 🌐 Swift | 📅 2026-08-31：Facebook iOS SDK。
* [ResearchKit](https://github.com/ResearchKit/ResearchKit) ⭐ 5,744 | 🐛 150 | 🌐 Objective-C | 📅 2026-07-15：ResearchKit 是一个开源的软件框架，用它可方便的构建医疗研究应用或者其他的研究项目。
* [Stripe](https://github.com/stripe/stripe-ios) ⭐ 2,568 | 🐛 281 | 🌐 Swift | 📅 2026-09-01：iOS and OS X Stripe 绑定框架。
* [AWS](https://github.com/aws/aws-sdk-ios) ⚠️ Archived：Amazon Web Services iOS 移动应用 SDK。
* [Paypal iOS SDK](https://github.com/paypal/PayPal-iOS-SDK) ⚠️ Archived：The PayPal 移动端 SDK，可以简便地在本地应用中集成 PayPal 和 信用卡支付。
* [Spotify](https://github.com/spotify/ios-sdk) ⭐ 746 | 🐛 243 | 🌐 Objective-C | 📅 2026-06-08：Spotify iOS SDK。
* [Tumblr](https://github.com/tumblr/TMTumblrSDK) ⭐ 438 | 🐛 26 | 🌐 Objective-C | 📅 2026-06-04：集成 Tumblr 数据到 iOS 或 OS X 应用中的库。
* [Evernote](https://github.com/evernote/evernote-cloud-sdk-ios) ⭐ 258 | 🐛 29 | 🌐 Objective-C | 📅 2024-08-22：Evernote iOS SDK。
* [Pocket](https://github.com/Pocket/Pocket-ObjC-SDK) ⚠️ Archived：将东西保存到 Pocket 的 SDK。
* [Venmo](https://github.com/venmo/venmo-ios-sdk) ⚠️ Archived：在你的 iOS app 通过 Venmo 生成订单并且接受支付。
* [Box](https://github.com/box/box-ios-sdk) ⭐ 129 | 🐛 11 | 🌐 Swift | 📅 2026-08-27：Box iOS 和 OS X SDK API。
* [Zendesk](https://github.com/zendesk/zendesk_sdk_ios) ⚠️ Archived：Zendesk iOS 移动应用 SDK。
* [OneDrive](https://github.com/OneDrive/onedrive-sdk-ios) ⚠️ Archived：Live iOS SDK。
* [Liquid Analytics](https://github.com/lqd-io/liquid-sdk-ios) ⭐ 24 | 🐛 2 | 🌐 Objective-C | 📅 2016-09-15：通过分析与实时的个性化的实时响应产生特定的行为。
* [Google Analytics](https://developers.google.com/analytics/devguides/collection/ios/v3/)：Google Analytics iOS SDK。
* [Adobe Creative SDK](https://creativesdk.adobe.com/)：Adobe creative tools 和 Creative Cloud SDK。
* [Dropbox](https://www.dropbox.com/developers)：Drop-ins 和 Dropbox Core API 的 SDK。
* [Fabric by Twitter](https://docs.fabric.io/ios/index.html)：iOS 的 Fabric Twitter Kit。
* [PacketZoom](https://packetzoom.com)：PacketZoom iOS SDK。
* Primer：在可视化编辑器上方便创建定制化的登陆页，注册和登录流程的 SDK，内建了 a/b/n 测试和分析。[官网](https://www.goprimer.com)

## 非官方

* STTwitter：为 Twitter REST API 1.1 制作的稳定，成熟，全面的 Objective-C 库。[官网](https://github.com/nst/STTwitter) ⭐ 990 | 🐛 24 | 🌐 Objective-C | 📅 2022-12-26
* InstagramKit：Instagram iOS SDK。[官网](https://github.com/shyambhat/InstagramKit) ⭐ 979 | 🐛 30 | 🌐 Objective-C | 📅 2020-06-12
* objectiveflickr：对象化的 Flickr， Objective-C 写的 Flickr API。[官网](https://github.com/lukhnos/objectiveflickr) ⭐ 789 | 🐛 18 | 🌐 Objective-C | 📅 2015-11-13
* FHSTwitterEngine：为 Cocoa 开发者提供的 Twitter API。[官网](https://github.com/fhsjaagshs/FHSTwitterEngine) ⭐ 214 | 🐛 9 | 🌐 Objective-C | 📅 2017-02-21
* UberKit：Objective-C 包装的简单易用的 Uber API。[官网](https://github.com/sachinkesiraju/UberKit) ⭐ 94 | 🐛 13 | 🌐 Objective-C | 📅 2016-02-13
* DribbbleSDK：Dribbble iOS SDK。[官网](https://github.com/agilie/dribbble-ios-sdk) ⭐ 73 | 🐛 0 | 🌐 Objective-C | 📅 2016-01-15
* Giphy： Giphy API 的 Objective-C iOS 客户端。[官网](https://github.com/heyalexchoi/Giphy-iOS) ⭐ 52 | 🐛 2 | 🌐 Objective-C | 📅 2017-02-07
* DropletKit：Objective-C 包装的 DigitalOcean v2 API。[官网](https://github.com/victorgama/DropletKit) ⚠️ Archived

# <a name="xcode"></a>Xcode

### <a name="plugins"></a>插件

* Chameleon：iOS （Obj-C & Swift）的扁平化颜色框架。★[官网](https://github.com/ViccAlexander/Chameleon) ⚠️ Archived
* VVDocumenter-Xcode：方便的编写标准注释的 Xcode 插件。[官网](https://github.com/onevcat/VVDocumenter-Xcode) ⚠️ Archived
* KSImageNamed-Xcode：提供了图片名称自动补全功能的插件。[官网](https://github.com/ksuther/KSImageNamed-Xcode) ⭐ 4,131 | 🐛 5 | 🌐 Objective-C | 📅 2017-03-29
* FuzzyAutocompletePlugin：提供了除前缀匹配之外的其他更加灵活的自动补全功能，支持 Xcode 5+。[官网](https://github.com/FuzzyAutocomplete/FuzzyAutocompletePlugin) ⭐ 3,224 | 🐛 18 | 🌐 Objective-C | 📅 2017-06-16
* XAlign：一个 Xcode 代码自动对齐插件，它可以使用自定义的模式来对齐任何东西。[官网](https://github.com/qfish/XAlign) ⭐ 2,844 | 🐛 57 | 🌐 Objective-C | 📅 2021-12-08
* ColorSense-for-Xcode：可视化的颜色选择插件。[官网](https://github.com/omz/ColorSense-for-Xcode) ⭐ 2,780 | 🐛 43 | 🌐 Objective-C | 📅 2016-03-22
* RTImageAssets：自动生成所需的全部 App 图标的插件。[官网](https://github.com/rickytan/RTImageAssets) ⚠️ Archived
* XToDo：一个显示项目中 TODO，FIXME，??? 和 !!! 列表的对话框。[官网](https://github.com/trawor/XToDo) ⭐ 1,536 | 🐛 27 | 🌐 Objective-C | 📅 2016-06-16
* UIColor-Hex-Swift：通过十六进制字符串创建 autorelease 颜色的便利方法。★[官网](https://github.com/yeahdongcn/UIColor-Hex-Swift) ⭐ 1,243 | 🐛 5 | 🌐 Swift | 📅 2023-11-22
* Lin：这个插件提供了 NSLocalizedString 的自动补全插件。[官网](https://github.com/questbeat/Lin) ⚠️ Archived
* XCActionBar：Xcode 的 Alfred。[官网](https://github.com/pdcgomes/XCActionBar) ⭐ 1,199 | 🐛 9 | 🌐 Objective-C | 📅 2017-07-03
* BBUncrustifyPlugin-Xcode：使用 ClangFormat 或 Uncrustify 格式化代码的插件。[官网](https://github.com/benoitsan/BBUncrustifyPlugin-Xcode) ⭐ 1,187 | 🐛 6 | 🌐 Objective-C | 📅 2019-08-12
* SCXcodeMiniMap：SCXcodeMiniMap 为 Xcode 添加了代码地图功能[官网](https://github.com/stefanceriu/SCXcodeMiniMap) ⭐ 1,015 | 🐛 9 | 🌐 Objective-C | 📅 2021-02-19
* GitDiff：将与 git 仓库中不同的代码高亮。[官网](https://github.com/johnno1962/GitDiff) ⭐ 888 | 🐛 0 | 🌐 Objective-C | 📅 2022-03-18
* Peckham：使用 #import 引用项目中的任何文件，提供代码提示。[官网](https://github.com/markohlebar/Peckham) ⭐ 712 | 🐛 18 | 🌐 Objective-C | 📅 2016-10-05
* CATweaker：一个用于创建漂亮的 CAMediaTimingFunction 曲线的插件.[官网](https://github.com/keefo/CATweaker) ⭐ 684 | 🐛 0 | 🌐 Objective-C | 📅 2016-03-24
* BBUDebuggerTuckAway：当你开始编辑的时候帮你隐藏调试器栏的 Xcode 插件。[官网](https://github.com/neonichu/BBUDebuggerTuckAway) ⭐ 667 | 🐛 2 | 🌐 Objective-C | 📅 2016-06-22
* SCXcodeSwitchExpander：SCXcodeSwitchExpander 是一个可以帮你展开 switch 语句的插件，还会自动帮你插入 case 语句。[官网](https://github.com/stefanceriu/SCXcodeSwitchExpander) ⭐ 652 | 🐛 4 | 🌐 Objective-C | 📅 2021-02-19
* MCLog：用于控制台内容筛选的插件。[官网](https://github.com/yuhua-chen/MCLog) ⭐ 584 | 🐛 13 | 🌐 Objective-C | 📅 2017-05-24
* XcodeWay：便捷地导航到多个地方。[官网](https://github.com/onmyway133/XcodeWay) ⭐ 554 | 🐛 4 | 🌐 Swift | 📅 2023-11-29
* Backlight-for-XCode：高亮当前编辑的行。[官网](https://github.com/limejelly/Backlight-for-XCode) ⭐ 406 | 🐛 20 | 🌐 Objective-C | 📅 2019-08-12
* KPRunEverywhereXcodePlugin：只需一次点击，就可以在多个 iOS 设备上构建，运行 App。[官网](https://github.com/kitschpatrol/KPRunEverywhereXcodePlugin) ⭐ 313 | 🐛 0 | 🌐 Objective-C | 📅 2026-02-07
* AdjustFontSize：使用 `⌘ +` / `⌘ -` 快捷键调整字体大小。[官网](https://github.com/zats/AdjustFontSize-Xcode-Plugin) ⭐ 272 | 🐛 1 | 🌐 Objective-C | 📅 2019-08-12
* Reveal-In-GitHub：用一个快捷键就可以跳转到 GitHub 仓库的 History, Blame, PRs, Issues, Notifications。[官网](https://github.com/lzwjava/Reveal-In-Github) ⭐ 257 | 🐛 1 | 🌐 Objective-C | 📅 2024-05-04
* Show in Github：可以直接打开 Github 上当前正在编辑的行对应的 commit 页面。[官网](https://github.com/larsxschneider/ShowInGitHub) ⭐ 237 | 🐛 3 | 🌐 Objective-C | 📅 2019-07-02
* BBUFullIssueNavigator：这个插件让 Xcode 在 issue 导航栏显示所有的 issue 内容。[官网](https://github.com/neonichu/BBUFullIssueNavigator) ⚠️ Archived
* MLAutoReplace：快速编码以及代码格式化插件，提升你的编码速度。[官网](https://github.com/molon/MLAutoReplace) ⭐ 229 | 🐛 0 | 🌐 Objective-C | 📅 2018-09-11
* RevealPlugin：将 Reveal App 和你的项目自动合为一体的 Xcode 插件。[官网](https://github.com/shjborage/Reveal-Plugin-for-Xcode) ⭐ 226 | 🐛 5 | 🌐 Objective-C | 📅 2016-09-22
* Luft：帮助你实现轻量的 View Controller 的 Xcode 插件。[官网](https://github.com/k0nserv/luft) ⭐ 171 | 🐛 0 | 🌐 Objective-C | 📅 2017-03-25
* CopyIssue：使复制 Xcode issuse 描述更简单。[官网](https://github.com/hanton/CopyIssue-Xcode-Plugin) ⭐ 169 | 🐛 1 | 🌐 Objective-C | 📅 2019-11-02
* XCSnippetr：直接上传代码片段到 Slack 和 Gist 的 Xcode 插件。[官网](https://github.com/dzenbot/XCSnippetr) ⚠️ Archived
* CleanHeaders-Xcode：类似 iSort 的头文件排序和重复消除插件，让你的头文件看起来更加有序。[官网](https://github.com/insanoid/CleanHeaders-Xcode) ⭐ 91 | 🐛 0 | 🌐 Objective-C | 📅 2016-10-28
* AutoHighlightSymbol：高亮被选中的符号对应的所有实例。[官网](https://github.com/chiahsien/AutoHighlightSymbol) ⭐ 84 | 🐛 1 | 🌐 Objective-C | 📅 2016-10-22
* JumpMarks：使用有序的书签为你的代码做导航。[官网](https://github.com/merrickp/JumpMarks) ⭐ 61 | 🐛 3 | 🌐 Objective-C | 📅 2018-02-04
* QuickJump：Xcode 快速代码导航。[官网](https://github.com/wiruzx/QuickJump) ⭐ 37 | 🐛 3 | 🌐 Swift | 📅 2018-10-26
* Aviator：这个插件将 AppCode 的 ⇧⌘T (source/test 切换) 带到 Xcode 中.[官网](https://github.com/marksands/Aviator) ⭐ 30 | 🐛 6 | 🌐 Objective-C | 📅 2019-08-12
* Cocoapods Xcode Plugin：依赖管理工具 CocoaPods 的 Xcode 插件。[官网](https://github.com/kattrali/cocoapods-xcode-plugin)
* RealmPlugin：生成 Realm 模型的 Xcode 插件。[官网](https://realm.io/docs/objc/0.81.0/#xcode-plugin)
* Rephrase：Xcode 用于本地化的插件.[官网](https://www.rephrase.io)

### <a name="themes"></a>主题

* Xcode themes list：Xcode 的多彩主题。[官网](https://github.com/hdoria/xcode-themes) ⭐ 2,411 | 🐛 1 | 🌐 Ruby | 📅 2022-11-17
* Solarized-Dark-for-Xcode：用于 Xcode5 的 Solarized Dark 主题.[官网](https://github.com/ArtSabintsev/Solarized-Dark-for-Xcode/) ⭐ 369 | 🐛 0 | 🌐 Shell | 📅 2019-08-06
* Dracula Theme：一个 Xcode 的暗色主题（仿 SublimeText）.[官网](https://github.com/zenorocha/dracula-theme) ⭐ 24 | 🐛 0 | 🌐 HTML | 📅 2016-05-30

### <a name="other-xcode"></a>其他 Xcode 插件

* Synx：一个重新组织你的 Xcode 项目的命令行工具，它能够让你的 group 和文件夹对应起来。[官网](https://github.com/venmo/synx) ⭐ 6,041 | 🐛 56 | 🌐 Ruby | 📅 2019-07-18
* dsnip：可以在本地为所有的 UIKit 协议／代理方法（UITableView,...）生成 Xcode 代码片段的工具。[官网](https://github.com/Tintenklecks/IBDelegateCodesippets)

# <a name="style-guides"></a>编码规范

* [Swift Style Guide by @raywenderlich](https://github.com/raywenderlich/swift-style-guide) ⭐ 13,160 | 🐛 16 | 📅 2025-04-01：raywenderlich.com 官方的 Swift 编码风格规范。★
* [Futurice iOS Good Practices](https://github.com/futurice/ios-good-practices) ⭐ 10,978 | 🐛 22 | 📅 2024-04-30：[@futurice](https://github.com/futurice) 介绍的 iOS 入门指南和最佳实践。
* [NY Times：Objective C Style Guide](https://github.com/NYTimes/objective-c-style-guide) ⚠️ Archived：纽约时报使用的 Objective-C 编码规范。
* [Github：Style guide & coding conventions for Swift projects](https://github.com/github/swift-style-guide) ⚠️ Archived：github 的 Swift 编码风格和习惯指南。★
* [raywenderlich Style Guide](https://github.com/raywenderlich/objective-c-style-guide) ⭐ 3,081 | 🐛 22 | 📅 2017-10-01：一个描述 raywenderlich.com 编码习惯的代码规范。
* [Github Objective-C Style Guide](https://github.com/github/objective-c-style-guide) ⚠️ Archived：Objective-C 项目的编码规范和惯用法。
* [Spotify Objective-C Coding Style](https://github.com/spotify/ios-style) ⭐ 244 | 🐛 0 | 📅 2020-08-10：Spotify 的 iOS 开发指导。
* [Objective-C Coding Convention and Best Practices](https://gist.github.com/soffes/812796)：一份描述编码习惯的 Gist。
* [Dropbox Objective-C Style Guide](https://dl.dropboxusercontent.com/s/5utnlwhr18ax05c/style-guide.html?dl=0)：Dropbox 的 Objective-C 代码风格指南。

# <a name="good-websites"></a>好网站

<h3>中文站点</h3>

* 伯乐在线 iOS 频道：分享 iOS 和 Swift 开发，应用设计和推广，iOS 相关的行业动态。[官网](http://ios.importnew.com/)

<h3>英文站点</h3>
### <a name="news-blogs-and-more"></a>新闻，播客和其他

* [iOS8-day-by-day](https://github.com/shinobicontrols/iOS8-day-by-day) ⭐ 2,578 | 🐛 11 | 🌐 Swift | 📅 2020-10-01 ★
* [iOS Developer and Designer interview](https://github.com/CameronBanga/iOS-Developer-and-Designer-Interview-Questions) ⭐ 1,577 | 🐛 0 | 📅 2017-06-01：一个用于帮助那些寻找 iOS 开发者或设计师的雇主的小指南。
* [BGR](http://bgr.com/ios-7/)
* [iMore](http://www.imore.com/)
* [Lifehacker](http://lifehacker.com/tag/ios)
* [iCode Blog](http://www.icodeblog.com/)
* [NSHipster](http://nshipster.com)
* [Objc.io](https://www.objc.io/)
* [ASCIIwwdc](http://asciiwwdc.com)
* [Natasha The Robot](https://natashatherobot.com)
* [Apple's Swift Blog](https://developer.apple.com/swift/blog/) ★
* [iOS Programming Subreddit](https://www.reddit.com/r/iosprogramming)
* [iOS Dev Weekly](https://iosdevweekly.com/)
* [iOScreator](http://www.ioscreator.com/) ★
* [Mathew Sanders](http://mathewsanders.com/) ★
* [Little Bites of Cocoa](https://littlebitesofcocoa.com/) ★
* [iOS Dev Nuggets](http://hboon.com/iosdevnuggets/) ★
* [This Week in Swift](http://swiftnews.curated.co) ★
* [iOS Goodies](http://ios-goodies.com)
* [iOS App Development on Medium](https://medium.com/ios-os-x-development)：一些关于 iOS，AppleWatch 开发的小故事和小贴士。
* [Swift Sandbox](http://swiftsandbox.io)：Swift 开发者通讯，Swift 开源新闻，项目和资源。 ★

### <a name="uikit-references"></a>UIKit 文档

* [iOS Fonts](http://iosfonts.com/)
* [UIAppearance list](https://gist.github.com/mattt/5135521)

### <a name="forums-and-discuss-lists"></a>论坛和讨论列表

* [iPhone Dev SDK Forum](http://iphonedevsdk.com/)
* ["iOS" on Stackoverflow](http://stackoverflow.com/questions/tagged/ios)

### <a name="tutorials-and-keynotes"></a>教程和 Keynotes

* [AppCoda](http://www.appcoda.com)
* [Tutorials Point](http://www.tutorialspoint.com/ios/)
* [Code with Cris](http://codewithchris.com/)
* [Cocoa with Love](http://www.cocoawithlove.com/)
* [Cocoa is my Girlfriend](http://www.cimgf.com/)
* [Code School：Try Objective-C](http://tryobjectivec.codeschool.com/)
* [Brian Advent youtube channel](https://www.youtube.com/channel/UCysEngjfeIYapEER9K8aikw/videos)：Youtube 上的 Swift 教程频道。 ★
* [RAYWENDERLICH](http://www.raywenderlich.com/tutorials)：开发者和爱好者的教程。
* [Ry’s Objective-C Tutorial](http://rypress.com/tutorials/objective-c/index)
* [Mike Ash](https://www.mikeash.com/pyblog/)
* [Big Nerd Ranch](https://www.bignerdranch.com/blog/categories/ios/) ★
* [Tuts+](http://code.tutsplus.com/categories/ios-sdk) ★
* [iOS-Blog](http://www.ios-blog.co.uk/) ★
* [Thinkster](https://thinkster.io/a-better-way-to-learn-swift) ★
* [Swift Education](https://github.com/swifteducation)：一个供教育者分享 Swift 和 app 开发学习材料的社区。★
* [Cocoa Dev Central](http://cocoadevcentral.com)
* [Use Your Loaf](http://useyourloaf.com)
* [Swift Tutorials by Jameson Quave](http://jamesonquave.com/blog/tutorials/) ★

### iOS UI 模版

* [App Icon Template](http://appicontemplate.com/ios8/)
* [iOS 8 GUI PSD Template](http://www.teehanlax.com/tools/iphone/)
* [iOS UI Design Kit](http://www.invisionapp.com/tethr)
* [iOS Design Guidelines](http://iosdesign.ivomynttinen.com/)

### <a name="prototyping"></a>原型

* [FluidUI](https://www.fluidui.com)
* [Proto.io](https://proto.io/)
* [Framer](http://framerjs.com/)
* [Pixate](http://www.pixate.com/)
* [Principle](http://principleformac.com)

<h1 id="weibo-weixin">微博、微信公众号</h1>
* iOS大全 微博：[@iOS大全](http://weibo.com/u/5314643524)
* iOS大全 微信：分享 iOS 应用开发相关行业动态、技术文章、工具资源、App 设计与推广、热门课程、高薪职位和经典书籍等。
<br><img src="http://ww4.sinaimg.cn/small/63918611gw1epb2c8cw4jj2046046ab2.jpg" width=150 height=150>

# <a name="twitter"></a>Twitter

* [@objcio](https://twitter.com/objcio)
* [@nshipster](https://twitter.com/NSHipster)
* [@CocoaPods](https://twitter.com/CocoaPods)
* [@CocoaPodsFeed](https://twitter.com/CocoaPodsFeed)
* [@RubyMotion](https://twitter.com/RubyMotion)
* [@SwiftSandbox](https://twitter.com/SwiftSandbox)：Swift 开源新闻, 项目和资源。

# <a name="facebook-groups"></a>Facebook 群组

* [HH iOS](https://www.facebook.com/groups/hhios/)
* [Sketch：Official group](https://www.facebook.com/groups/sketchformac/)
* [Design-Code](https://www.facebook.com/groups/designcode/)
* [Sketch-Design.io](https://www.facebook.com/groups/sketchdesignio)
* [Origami Community](https://www.facebook.com/groups/origami.community/)
* [Framer JS](https://www.facebook.com/groups/framerjs/)

# <a name="podcasts"></a>播客

* [The Ray Wenderlich Podcast](http://www.raywenderlich.com/rwpodcast)
* [Debug](http://www.imore.com/debug)
* [iDeveloper](http://ideveloper.co/)
* [App Story](http://www.appstorypodcast.com)
* [Mobile Couch](http://mobilecouch.co/)
* [iOS Bytes](https://iosbytes.codeschool.com/)

# <a name="books"></a>书籍

* [Programming with Objective-C by Apple](https://developer.apple.com/library/mac/documentation/Cocoa/Conceptual/ProgrammingWithObjectiveC/ProgrammingWithObjectiveC.pdf)
* [Object-Oriented Programming with Objective-C by Apple](https://developer.apple.com/library/mac/documentation/Cocoa/Conceptual/OOP_ObjC/OOP_ObjC.pdf)
* [The Swift Programming Language by Apple](https://itunes.apple.com/us/book/swift-programming-language/id881256329?mt=11) ★
* [Using Swift with Cocoa and Objective C by Apple](https://itunes.apple.com/us/book/using-swift-cocoa-objective/id888894773?mt=11) ★
* [iOS Programming: The Big Nerd Ranch Guide by Christian Keur, Aaron Hillegass, Joe Conway](https://www.bignerdranch.com/we-write/ios-programming/)
* [Programming in Objective-C by Stephen G. Kochan](http://www.amazon.com/Programming-Objective-C-6th-Developers-Library/dp/0321967607)
* [Your First iOS App by Ash Furrow](https://leanpub.com/your-first-ios-app)
* [The Complete Friday Q & A: Volume 1](https://www.mikeash.com/book.html)
* [Core Data for iOS: Developing Data-Driven Applications for the iPad, iPhone, and iPod touch](http://www.amazon.com/Core-Data-iOS-Data-Driven-Applications/dp/0321670426/)
* [Cocoa Design Patterns](http://www.amazon.com/Cocoa-Design-Patterns-Erik-Buck/dp/0321535022)

# <a name="other-awesome-lists"></a>其他优秀的列表

你可以在下面找到其他十分优秀的列表

* [Open Source apps](https://github.com/dkhamsing/open-source-ios-apps) ⭐ 51,931 | 🐛 2 | 📅 2026-08-31 开源 iOS app 列表。
* [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness) ⭐ 33,639 | 🐛 62 | 🌐 Ruby | 📅 2024-06-02 列表。
* [awesome-ios-ui](https://github.com/cjwirth/awesome-ios-ui) ⭐ 11,216 | 🐛 12 | 📅 2018-03-08：优秀的 iOS UI/UX 库列表。
* [awesome-ios-animation](https://github.com/sxyx2008/awesome-ios-animation) ⭐ 5,460 | 🐛 0 | 📅 2025-10-28：包括了 Objective-C 和 Swift 实现的 iOS 动画库列表。
* [awesome-ios-chart](https://github.com/sxyx2008/awesome-ios-chart) ⭐ 1,517 | 🐛 0 | 📅 2025-10-28：很棒的 iOS 图表库列表。包括了 Objective-C 和 Swift 两种语言。
* [awesome-gists](https://github.com/vsouza/awesome-gists#ios) ⭐ 769 | 🐛 1 | 📅 2025-06-24：很棒的 Gist 列表 (iOS 章节).
* [iOS Learning Resources](https://github.com/sanketfirodiya/iOS-learning-resources) ⭐ 495 | 🐛 3 | 📅 2022-08-28 一个高质量，频繁更新并且被很好维护的 iOS 教程网站的完整集合。
* [awesome watchkit apps](https://github.com/sanketfirodiya/sample-watchkit-apps) ⭐ 249 | 🐛 0 | 📅 2015-08-16 watchkit app 例程和教程的列表。▲
* 优秀的 Swift 列表
  * [@matteocrippa](https://github.com/matteocrippa/awesome-swift) ⭐ 26,235 | 🐛 11 | 🌐 Ruby | 📅 2026-08-03：一个优秀的 Swift 资源合集列表。
  * [@Wolg](https://github.com/Wolg/awesome-swift) ⭐ 5,885 | 🐛 111 | 📅 2026-04-12：一个很棒的 Swift 框架，库和软件的策划列表。

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-09-01._
