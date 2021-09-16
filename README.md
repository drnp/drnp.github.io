# 简历 - 张浩（互联网 - 技术 / 研发）

**电话** +86-18910299173
**邮箱** [conan.np@gmail.com](mailto:conan.np@gmail.com)

## 关于

### 基本状况

- 男  **1982**年
- IT / 互联网 / 游戏，技术研发、架构师
- 网络通讯、游戏、工程架构、云服务、研发效能管理
- 原籍 **辽宁沈阳**  现居住地 **北京市朝阳区**
- 一线 / 创业 / 自营公司经历
- 全日制本科 计算机科学与技术专业 **211/985** 院校

### 综合信息

- 2004年初起从事互联网相关软件研发工作，**网络游戏** 、 **社交** 、 **娱乐** 、**效能工具** 、**安全** 方向经验，对业务系统下层 **服务架构** 设计及实施、 **网络通讯服务** 、 **数据流处理** 等有较多实践，在 **运维基础架构** 、业务逻辑实现、互动展示（游戏类）、音视频处理等方向都有实际工作输出，曾有过 **智能硬件** 、 **工业智能系统** 、 **数字化研发度量** 相关系统设计实现经历。
- 整体工程化思维清晰，擅长架构设计、逻辑抽象、技术预研。
- 曾接触B端业务，企业办公、劳动力精细化管理及工业流程管理领域。
- 熟悉 **C** / **Lua** （通讯服务 / 游戏相关）、 **PHP** 、 **Go** （通讯服务、平台类、电子游戏、数据逻辑），有过 **AS3** 开发（非效果类）经历，短时间接触过 **C#** （unity游戏客户端）开发。熟悉 **posix类** 系统，相当数量的脚本编写经验。
- 曾在任职期间从事 **相当规模** 系统的研发设计工作，几次参与 **创业项目** ，清楚成熟公司的工作合作方式，也适应创业公司的节奏和状态。比较容易接受各种风格的团队，可以完成一些 **特殊时期** ， **特别类型** 的研发工作。
- 对某些类型的产品，有从非技术层面思考认知的能力。
- 有过开源软件开发及维护经历，有过个人 **商业软件** 的开发及售卖经历，有过外包经历。早年热衷于技术社区。
- 接触计算机软件开发时间早（>20年），基础知识系统扎实，技术视野开阔，对新技术方法工具等接受速度快，设计方法谨慎，开发标准严格，解决问题态度端正。认可 **自身属性** 与行业的匹配程度 ，行业及技术相关思考内容较多。有相当多的技术招聘 **面试** 的经历。

## 工作经历

### 平行未来 (2021/1 - 2021/8)

#### 高级架构师

- 新熊猫直播

    熊猫直播（非同名产品）继承于2016-2019年直播行业的一线产品PandaTV，寄望于原熊猫的品牌效应和用户资源助力，以MetaVersion的新思维形态，打造以虚拟形象直播、互动娱乐为主线的新熊猫直播产品。

    任职期间完成后端服务架构设计、选型、规划，基于go-micro v3的微服务架构，服务端开发流程规范，CodeReview等研发向工作。

    前期梳理终结于2019年的PandaTV的后端服务架构和数据，并从0开始推进新系统体系的落地，直到公测前状态。

    期间对各业务线提供技术支持，并主导用户体系、资产（金融）体系的服务设计和研发。

    独立完整实现用于游戏、直播消息（弹幕等）的长连接通讯服务的设计、开发与对接融合。

    **公司由于某些原因，于2021年8月停止项目支持，导致新熊猫直播并未对外发布。**

### 奇安信集团（2019/10 - 2021/1）

#### 总工办

- 2019/10-2020/04：Hiner - 奇安信制品分发系统
  
    Hiner是集团对外的制品统一发布系统，分为内部发布介面及对外的分发（下载）两部分。于可配置的工作流模式上完成文件的归集、本地上行、存储备份、散列白名单、CDN等。目前支持集团各业务线的制品发布及下载管理，是软件制品交付的官方认可的唯一渠道。

    完成系统的整体架构设计、评审，带领团队实现需求分析及功能开发、测试、落地及对使用方（集团几乎所有产线）的支持与技术服务。

    系统由go语言实现，以多子服务的方式部署于Docker Swarm集群中，完全通过消息队列耦合。系统对内实现了大文件分片上传、校验、安全扫描（接入天擎、锡安平台。VirusTotal由于成本问题未正式接入），制品包完全递归解压并添加至安全软件的扫描白名单（天擎、安全卫士），CDN推送及自动预热（白山云、金山云、阿里云完整适配），分发权限管理、版本树管理等。对外提供制品索引、版本升级助手等。

    后期由于自动化分发的流程需求，对集团内其它工程系统提供对接支持，完成Jfrog Artifactory和裸S3的直接存取支持，跨平台的分发前端工具以及第三方权限对接。

    Hiner上线后，替换了旧有的发布系统，承接每天几百次的分发流水线申请，单个超过500GB的制品包，以及递归解压后文件数量放大30万倍的特殊制品包的分发。

- 2020/04-2021/01 Fusion - 研发效能数字化度量及流水线平台

    聚变（fusion）平台是集团数字化体系中的重要部分，提供研发类数据指标度量及devops流水线实现，对研发效能管理提供直接重要的量化支持。

    研发流程始于VCS动作，通过git hook和gitlab webhook触发fusion流水线执行。流水线以可配置的方式，下层基于jenkins，串联了sonarqube、开源卫士等代码审查工具、安全扫描工具、自动化测试等，并将结果归集至fusion平台中。

    Fusion集中了两种维度的数据，一类是代码资产、一类是流水线执行结果。平台以插件形式，对数据进行各种维度的统计分析，并做可视化展现，包括产线的代码质量统计排行、问题修复时长统计评估、扫描报告等。

    同时fusion对接了集团高度定制化的jira流水线，将测试问题与代码本身实现关联。以及集团内部自研的腾云平台，将开发者工时管理与代码工程质量实现关联。

    实时通知接入蓝信（奇安信集团的安全IM）。

    CI流水线同时支持gitlab-ci和jenkins job，CD出口支持接入Hiner制品分发。由于集团的大部分产品，研发最终输出的是制品或实体设备，并不强依赖于部署。

    工程数据覆盖集团近4000研发人员，万余代码库，超过20万开发分支，百万次提交行为，代码文本行数超百亿，每日静默分析行为平均4000-5000次。

    平台服务化实现，服务端使用go语言、postgresql数据库，部署于Swarm集群、前端主要vue实现。

### 奇虎360（2014/12 - 2017/12）

#### PC网游事业部  服务端架构师

- 2014/12-2015/04 : 轻游戏平台，PC端加速球游戏内容服务，玩家服务。

    由于360用户本身没有特别的社交属性，也没有娱乐粘性和过往积累的内容吸引力。所以规划了本意在利用PC端（安全产品、浏览器等）入口通过互动小游戏的方式增加游戏用户活跃度，提供给终端用户更多的内容体验并实现游戏平台的导流。实现轻度游戏的积分、排行、匹配等接口层服务。

    部分后端接口，使用PHP开发。

- 2014/12-2015/06 : **PVR** 游戏（ **酷跑系列** 等，后端Record及积分服务）。

    PVR 即Person VS Record，是“人与记录影像对战”的游戏互动方式，这种方式通常用在玩家操作没有相互影响的同场景竞技类（如跑酷、简化型赛车）游戏中（PVR这个词是我生造）。用以提供在某种游戏场景下更有效率更及时的对战匹配体验。Record服务后端服务由PHP开发。正常的Record不是视频或小波录像，只是玩家操作行为与恒定帧的对应关系。

    酷跑系列在2015年春节期间汇聚了相当的流量，并完成了一部分的平台 **用户转化** 。

- 2015/03 - 2015/07 : **实时游戏** 服务端引擎 / **多人** 俄罗斯方块。

    为了提供更多的休闲游戏类型支持，完成更好的对抗体验而设计的实时游戏服务。架构继承自之前的个人项目，使用 **C** 开发网络通讯服务，并嵌入由 **Lua** 编写的游戏业务逻辑，完成对游戏实时体验的支持。

    开发了AS3的通讯客户端包，使用 **私有的二进制协议** 提供数据承载和校验。游戏项目本身参考自2003年腾讯游戏大厅上线的“火拼俄罗斯”系列，由于客户端的技术限制，并没有完整地设计火拼系列的操作体验，但是安排了更合理的基于战绩的匹配机制。后期由于项目安排及人员变动，游戏 **未正式上线** 。

- 2015/09 - 2016/09 : 通讯服务 / 实时游戏服务端实现 / 技术性 **日常事务** 。

    在不承载游戏项目本身的情况下继续推进实时游戏的服务端研发，由于部门的人力投入转移，自研型业务基本由 **个人** 推进。期间有部分精力投入于部门其它技术项目上。

- 2016/09 - 2017/01 : 游戏平台基础设施 **容器化** 调研及实施。

    本次容器化改造尝试了当时流行的各种技术方案，涉及服务治理、编排、集群、**网络** 等，并最终在 **docker swarm** （由于当时kubernetes的版本跳跃及文档完备性的问题，并未最终采纳）方案上进行了实施操作，迁移了部分服务至swarm集群。在调研过程中，开发了用于nginx（非pro）的配置工具“gourd”的两个版本（ **C** 和 **Lua** ），后业务网关改由 **traefik** 代替。调研中实践了大量组件如etcd，flannel，register等。

- 2017/02 - 2017/07 : 实时 **游戏引擎** 设计开发，休闲手游《Color&Color》。

    设计并实现通用实时游戏服务端引擎 **langer** 和游戏逻辑容器 **slater** ，并实现游戏《Color&Color》的部分逻辑。langer和slater在之前PVP游戏服务的设计基础上完全由 **Go** 语言重新实现，由于没有嵌入式动态脚本，slater并不适合逻辑频繁修改的业务型游戏，但很适合以房间为组织形式的休闲类游戏。Langer包括完整的认证服务、Dispatcher、Gateway和状态存储，并与slater之间保持稳定的网状通讯。

    《Color&Color》是类似“围城”的一款io游戏，在实现服务端同时，第一次尝试使用 **C#** （Mono）开发了适合 **unity** 的langer客户端，以及游戏GUI调试工具（Windows）。在游戏实现中期，制作了游戏的 **BGM** 及音效。

### 炫游在线 / 奇游互动（2012/04 - 2014/12）

#### 架构师 / OPS / 技术支持

- 2012/05 : FakeSAE，SinaAppEngine服务模拟实现。

    《微三国》游戏从新浪SAE平台向其它的iaas公有云迁移时遇到了SAE非通用服务的限制。在相对有限的时间里开发上线了模拟真实SAE的HTTP队列和计划任务服务 **FakeSAE** ，使得原有游戏业务代码可以几乎0侵入地迁移至其它公有云平台。FakeSaeQueue依赖redis提供队列存储，实现了SAE自身支持的顺序和并发（乱序）队列，使用 **C** 开发，利用 **静态线程池** 实现HTTP消费前置，用 **Lua** 作为配置脚本，并消除了SAE原有的队列长度限制。自上线服务后稳定运行至2018年游戏下线。

    《微三国》系列作为网页游戏，获得了盈利运营超过7年的成绩。

- 2013/01 - 2013/04 : 实时游戏服务，《三国霸业》游戏战斗逻辑。

    《三国霸业》是公司另外策划的一款三国题材的网页游戏，设计风格相比于微三国更为写实，战斗系统包含实时逻辑。继承自之前的个人项目开发的 **通讯服务** 及 **毫秒级定时器** 对游戏战斗逻辑提供基础支持，使用 **C** 开发服务主体，并嵌入 **Lua** 编写的逻辑脚本。游戏于内测后因为业务调整中断。

- 负责公司整体的 **运维** 工作及公司内部 **IT管理** （公司人数较少）。

    管理维护线上及开发测试用服务器及其它资源，制定 **发布流程** 和资源评估。实施完整的内部权限系统，基于 **LDAP** 的日常认证机制，串联所有开发资源及公司日常 **人事管理** 等。

### 无线天利（2010/06 - 2012/04）

#### 架构师

- 实时推送服务的设计及实施，应用于 **运财网** 投顾平台中。服务依然继承自早先的游戏项目，使用 **C** 开发。
- 业务平台的 **技术选型** ，方案设计，展示层业务使用 **PHP** 实现，数据层基于JAVA（未参与JAVA项目）和Oracle数据库。
- 太平洋保险项目实时通讯支持。

### 美嘉传媒（2005/12 - 2006/08  2007/10 - 2010/04）

#### PHP后端开发 / 游戏服务端开发

- 2005/12 - 2006/08 : “5jia1”社交平台。

    国内较早一批的社交平台，主打校园社团，为早期的web2.0雏形模式，使用 **PHP** 实现后端逻辑。负责实现 **图像存储** ， **论坛** 等社交模块的业务设计及开发，教育网各名校论坛的热贴 **爬虫** 及清洗重现，后期进行一些框架梳理工作。

- 2007/10 - 2008/08 : 棋牌游戏通用服务端，《BlackJack》。

   第一个版本的实时游戏服务，使用 **C** 开发通讯基础部分，嵌入 **Lua** 开发的业务逻辑，基于 **AS3** （非flex）的Flash客户端。 **独立** 完成服务的实现并参与了第一个基于它的棋牌游戏《BlackJack》的业务逻辑开发，并在uspace上线运营。后因法规限制下架。

- 2008/07 - 2009/03 : 真人围棋。

    真人围棋的业务实现，这个版本并算不上严格意义的游戏，更趋向于 **仿真** ，严格遵守19线围棋的规则实现双人对奕。在完全不懂围棋的情况下，用 **Lua** 实现了完整的围棋规则，并实现了Flash版客户端的主要部分。项目上线维持了一段时间并保持了一定的用户活跃程度（由于用户群的特殊性，并不适用常规游戏的衡量标准）。

- 2009/03 - 2010/04 : 迷你围棋游戏《Batoo》。

    与韩方合作的游戏项目，非标准围棋规则，而是11/13线的短时制游戏。在文档不完整且无源码的情况下，分析整理韩方的游戏服务的二进制数据协议 ，并用 **AS3** 重写了一个客户端，以支持batoo的web版实现。最终flash版可以与客户端版本实现完全同步并混合游戏。Batoo的国服运营至2010年后关闭。

### 新浪网（2006/09 - 2007/09）

#### 研发中心 / 互动社区 服务端开发

- 新浪博客用户行为分析。

    通过日志跟踪计算的方式统计了当时博客的用户登录状态，浏览时间，登录后行为等细节数值，用于运营支撑。

- 博客计数器服务。

    基于 **memcached** 1.1x改造的数据落地实现，使用 **BerkeleyDB** 用于实际存储，依赖memcached的原子操作进行post维度的访问量统计。服务为后期新浪开源的 **memcachedb** 项目的实现雏形。

### 上海群智文化（2004/02 - 2005/03）

## 独立项目

### Link（黑尾）

- 发展自熊猫直播长连接服务的社区版本，提供集群形式的单双工websocket、UDP帧同步及带有逻辑脚本支持的TCP网关，和相应的简单用户体系和运行时统计。

- 基于go-micro V3开发

### BS.Play

- 经历了四次迭代的游戏通讯服务，使用 **C** 开发的基础服务和 **Lua** 实现的逻辑嵌入脚本实现重逻辑的实时业务。其中实现了基于块的内存池（后移除），抽象的io复用层，静态线程池，简单自旋锁，websocket协议等基础组件，并制定了一组Lua API用于事件编写。项目曾经支持过棋牌类、策略类、休闲对战等游戏业务及行情推送等非游戏业务。

- 后由 **Go** 重构为Langer/Slater。

### 劳勤云考勤网关（内部项目）

- **Go** 语言实现的考勤服务网关，支持某系列的汉王考勤机的TCP通讯协议，支持中控702系列人脸识别考勤机的HTTP业务协议，支持劳勤云本身的打卡协议（用于GPS和SSID打卡）。网关由gateway和tasker两部分组成，其间由kafka或redis实现消息队列。

### ID5DB（内部项目）

- 基于memcached实现的数据存储，通过MMAP映射的方式将缓存中的数据写盘，并使用snappy算法压缩混淆后归档。由于归档文件的格式特殊性，项目曾用于敏感数据。

### AudioMixer

- **C** 实现的PCM音频文件混轨工具，基于libmpg123，支持对等及对数比例叠加，自动消顶，不依赖播放设备，曾用于音乐类游戏的合成结果导出。

### BS.Gallery相册（商业转开源）

- 早期由PHP开发的Web相册，实现了完整的图片存储展示系统的大部分功能。2005年曾经有销售行为。

## 教育及其它

- 东北大学 计算机科学与技术 全日制本科 2000-2005
- 2003年 信息产业部 计算机技术与软件专业技术资格（水平）考试 高级程序员
- 1998年 NOI 赛区一等奖
- 音乐编曲、制作、后期。曾经执行游戏BGM
