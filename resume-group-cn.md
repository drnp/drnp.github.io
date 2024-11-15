# 简历 - 张浩 - 黑尾科技

**Mobile** : +8618611118254 / +8618910299173

**Email** : [conan.np@gmail.com](mailto:conan.np@gmail.com)

**Wechat** : npngny

## 关于

### 张浩

- 男  **1982**年
- IT / 互联网 / 游戏，技术研发、架构师
- 网络通讯、游戏、工程架构、云服务、研发效能管理
- 原籍 **辽宁沈阳**  现居住地 **北京市朝阳区**
- 一线 / 创业 / 自营公司经历
- 全日制本科 计算机科学与技术专业 **211/985** 院校

### 黑尾科技

- 2018年组队
- 独立工作室性质
- 互联网软件研发、AI、视觉设计
- 有稳定独立的实施团队（沈阳）
- 有广阔的行业人脉和资源

### 综合信息及项目产品经历

- 2004年初起从事互联网相关软件研发工作，**网络游戏** 、 **直播** 、 **数字人** 、 **社交** 、 **娱乐** 、**效能工具** 、**安全** 方向经验，对业务系统下层 **服务架构** 设计及实施、 **网络通讯服务** 、 **数据流处理** 等有较多实践，在 **运维基础架构** 、业务逻辑实现、互动展示（游戏类）、音视频处理等方向都有实际工作输出，曾有过 **智能硬件** 、 **工业智能系统** 、 **数字化研发度量** 相关系统设计实现经历。
- 整体工程化思维清晰，擅长架构设计、逻辑抽象、技术预研。
- 曾接触B端业务，企业办公、劳动力精细化管理及工业流程管理领域。
- 接触研发效能管理、自动化**运维**、devops流水线、标准化研发流程及版本交付管理等。
- 对某些类型的产品，有从非技术层面思考认知的能力。

## 项目经历

### 站酷直播（2024）（委托定制开发）

- 新加坡客户
- 安卓、iOS、PC直播助手（基于obs）
- 直播助手支持实时换脸（DeepFace Live）
- 服务端基于go-micro v4
- 自建长连接

### Wisekin数字人（2023）（合作项目）

基于通用大模型实现的二次元陪伴型数字人。提供语音及文字对话，模拟电话聊天，人物特殊展示类动作等。

- 接入ChatGPT 3.5/4.0
- 接入通义千问
- 接入Azure TTS / STT
- 后端基于go-fiber的单体服务
- 移动端基于flutter
- 3d数字人基于MMD（Miku Miku Dance）制作，在ThreeJS中以webgl方式渲染呈现，并同步加载全3D场景，可配置的环境参数及光照，人物可拖动
- 基于腾讯云的内容过滤服务

### icePay（黑尾科技自有项目）

面向欧美的移动支付方案。

- GoSkel（基于go-fiber的服务实现）
- Symfony EasyAdminBundle
- Flutter移动客户端
- 无金额账户，基于openbanking对接本地银行通道
- 离线（无码）支付

**项目实施中，当前demo制作阶段。**

### SmartRigger（黑尾科技自有项目）

工业生产流程数据平台。配合智能电控工具，对铁路装配车间的生产状态做出实时反馈，当前用于铁路系统。

- Lumen framework
- 手持终端支持
- 树莓派驱动的现场大屏幕实时推送
- 英格索兰系列电动扭矩扳手，诺霸扭矩校验台协议适配

**项目实施中，g1版本已交付，g2迭代中。**

### LRUURL（黑尾科技自有项目）

参考short.io实现的综合性网址服务，实现地址转换，条件跳转，访问数据跟踪，分析等功能。早期为实验性质的短地址服务（上线），目前转为商业实施。

- GoSkel（基于go-fiber的服务实现）网关
- Symfony / EasyAdmin
- ClickHouse / PostgreSQL

**项目实施中，当前demo原型搭建，竞品行为分析。**

### 易玄

基于三才五格理论的姓名学计算工具

- Pure go实现
- 完整的 unihan 数据库支持，全内存加载。
- 基于拟合公式和修正值的真太阳时计算。
- 标准104年农历修正。
- 节气时刻修正。
- 夏令时修正。
- 全唐诗、宋词、四书五经数据标准化（二元读音清洗），名字的模糊匹配。
- 康熙字典、说文解字、新华字典部分元数据。
- 支持特殊字修正。
- 五格算法打分。
- 十神、太岁。

**支持的app现在运营中。**

### Link

长连接推送，需求起源于直播弹幕。

- 基于 go-micro  实现（并未使用标准的微服务间通讯模式）。
- 高度优化的 websocket  支持（syscall、epoll hack）
- 私有二进制通讯协议（配合有 android和 ios  原生客户端）
- 群发、组发
- 自定义优先级（低优先级洪水自动选择性丢弃信息以保护资源）

**支持两个公司的线上业务，移除商业依赖后的版本部分开源。**

### BS.Play

- 经历了四次迭代的游戏通讯服务，使用 **C** 开发的基础服务和 **Lua** 实现的逻辑嵌入脚本实现重逻辑的实时业务。其中实现了基于块的内存池（后移除），抽象的io复用层，静态线程池，简单自旋锁，websocket协议等基础组件，并制定了一组Lua API用于事件编写。项目曾经支持过棋牌类、策略类、休闲对战等游戏业务及行情推送等非游戏业务。

- 后由 **Go** 重构为Langer/Slater。

### 劳勤云考勤网关（企新未来自有项目）

- **Go** 语言实现的考勤服务网关，支持某系列的汉王考勤机的TCP通讯协议，支持中控702系列人脸识别考勤机的HTTP业务协议，支持劳勤云本身的打卡协议（用于GPS和SSID打卡）。网关由gateway和tasker两部分组成，其间由kafka或redis实现消息队列。
- 对接**SpringBoot**开发的基础saas接口，同步所有劳动者基本数据以及行为数据。
- 对接审批工作流系统（java）。
- 调试c#桌面客户端。

### ID5DB（内部项目）

- 基于memcached实现的数据存储，通过MMAP映射的方式将缓存中的数据写盘，并使用snappy算法压缩混淆后归档。由于归档文件的格式特殊性，项目曾用于敏感数据。