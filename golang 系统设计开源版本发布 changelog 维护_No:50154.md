最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计开源版本发布 changelog 维护
简介：golang init 函数合理使用边界，少用 init，优先显式调用初始化，便于控制初始化时机。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/14361313.html

原标题：日志输出规范防止磁盘爆满
简介：golang recover 捕获 panic 使用边界，recover 只在 defer 内部生效，协程内部必须捕获本协程 panic。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/56731651.html

原标题：golang 系统设计网关鉴权鉴权转发流程讲解
简介：golang goroutine 泄露检测告警实现，监控 goroutine 数量，突增触发告警，提早发现协程泄露。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/55660967.html

原标题：实战项目：本地搭建Prometheus监控完整demo
简介：nodejs 信号处理优雅关闭服务，监听系统信号，执行资源清理，实现 Node 服务优雅停机，拒绝粗暴杀死进程。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/19304943.html

原标题：Hands‑on：简易速率限制中间件完整实现
简介：多规则数据脱敏组件开发，封装通用脱敏组件，支持多种脱敏规则，项目多处复用脱敏逻辑。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/26401892.html

原标题：golang 系统设计缓存 key 命名规范最佳实践
简介：golang 结构体零值可用性原则，go 结构体尽量做到零值可用，不用初始化直接使用提升易用性。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/04524944.html

原标题：golang 系统设计分表跨表 join 业务处理方案
简介：前端虚拟列表大数据渲染优化，实现虚拟滚动列表，只渲染可视区域 DOM，上万条数据页面流畅渲染。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/11901103.html

原标题：Security：业务操作审计日志安全留存
简介：golang go 排序 sort 包自定义排序，sort 包实现自定义排序逻辑，对切片按业务规则排序。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/00914950.html

原标题：golang 系统设计缓存更新策略 cache aside 讲解
简介：缓存基础原理与简单代码实现，讲解缓存设计思路，编写简易缓存逻辑，减少重复计算与重复请求，提升程序响应速度。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/07797020.html

原标题：GET POST 接口请求参数处理
简介：golang go 排序 sort 包自定义排序，sort 包实现自定义排序逻辑，对切片按业务规则排序。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/37643985.html

原标题：Practice：实现异步任务结果查询回调实践
简介：golang redis stream 消息队列实战，redis stream 实现可靠消息队列，消费组、ack 确认，消息不丢失。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/56578783.html

原标题：golang 速率限制令牌桶实现
简介：golang 优雅处理数据库事务，Go 数据库事务封装，正确处理事务提交回滚，保证业务数据一致性。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/37535170.html

原标题：调优方案：容器CPU内存参数压测后调优
简介：golang nats 轻量消息队列 go 开发，nats 高性能轻量消息系统，发布订阅模式异步解耦业务。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/88859547.html

原标题：golang redis stream 消息队列实践
简介：项目目录结构规范化最佳实践，梳理源码、配置、静态资源目录划分，规范项目布局，提升代码可读性和可维护性。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/41571407.html

原标题：golang 系统设计 rest http 方法使用原则
简介：消息消费重试次数限制防爆炸，限制消息最大重试次数，防止失败消息无限重试造成消息爆炸堆积。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/43573387.html

原标题：golang 系统设计网关性能压测优化简单思路
简介：SourceMap 生成线上报错定位，项目打包生成 SourceMap 文件，线上报错可以还原源码，快速定位报错位置。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/98012895.html

原标题：SDK 版本兼容线上崩溃修复
简介：golang goroutine 泄露常见场景汇总，channel 阻塞、context 忘记取消，导致协程无法退出发生泄露。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/89349126.html

原标题：golang 系统设计压测数据构造方法实现
简介：golang 高并发下锁优化减少竞争，减小锁粒度，读写锁替换互斥锁，无锁编程降低锁竞争开销。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/70156972.html

原标题：Hands‑on：简易请求转发代理中间件实现
简介：浏览器内存泄漏排查前端页面，梳理前端页面内存泄漏场景，讲解排查手段，修复页面内存持续上涨。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/59880391.html

原标题：golang 系统设计架构图绘图工具选型对比
简介：读懂开源项目 README 实用技巧，教你快速解析开源项目说明文档，提取安装、运行、配置关键信息，快速上手项目。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/27420656.html

原标题：新手教程：Gittag版本标签打标签实操
简介：golang gin 框架接口开发实战，Gin 框架搭建 HTTP 服务，开发增删改查接口，快速完成后端接口开发。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/71445402.html

原标题：调优方案：Web服务内核socket参数调优
简介：golang go math 大数高精度计算，math/big 处理超大整数、高精度浮点数，金额大数运算。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/54929737.html

原标题：golang 系统设计 sql 注入 xss 防护实践
简介：golang go http 服务器优雅关闭完整代码，http.Server Shutdown，等待现有请求处理完成关闭服务。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/22045485.html

原标题：golang 系统设计联合索引设计避坑要点
简介：布隆过滤器数据高效去重实现，实现布隆过滤器组件，用于海量数据去重，节省大量内存空间。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/82163549.html

原标题：nodejs 事件循环机制完整讲解
简介：golang strings.Builder 字符串高效拼接，strings.Builder 做字符串拼接，比 += 性能更高，减少内存拷贝。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/17652320.html

原标题：CI 流水线构建失败日志排查
简介：CORS 跨域问题多种解决方案，对比 CORS、代理等不同跨域方案优缺点，根据业务场景选择合适的跨域处理方式。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/06478576.html

原标题：golang 系统设计分库分表扩容平滑迁移
简介：golang time.After 内存泄漏场景，for 循环使用 time.After 会创建大量 timer，造成内存泄漏。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/65810100.html

原标题：golang 系统设计告警风暴抑制合并降噪方案
简介：golang go 测试 t.Run 子测试分组，t.Run 实现子测试，分组执行用例，输出分组测试结果。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/18692340.html

原标题：Shell 脚本自动化命令编写
简介：文件描述符优化进程卡死修复，及时关闭文件句柄，控制打开文件数量，解决文件句柄耗尽进程卡死。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/19150435.html

原标题：避坑：Nginx配置错误导致请求丢失Header
简介：golang 滑动窗口限流算法 go 实现，滑动窗口限流，解决固定窗口临界流量突增漏洞，限流更精准。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/60331218.html

原标题：golang 系统设计代码评审 checklist 清单
简介：环境变量不生效问题修复，排查环境变量加载顺序、作用域问题，修复环境变量读取不到的异常。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/83904634.html

原标题：golang 系统设计 p0 故障复盘方法论讲解
简介：请求工具封装统一异常处理，对网络请求做二次封装，统一捕获各类请求异常，标准化接口返回格式。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/30360477.html

原标题：Docker 网络模式容器互通设置
简介：golang aes cbc gcm 模式加密对比，AES‑CBC AES‑GCM 模式加密解密，理解两种模式差异选型。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/77578298.html

原标题：golang 系统设计分表跨表 join 业务处理方案
简介：golang 单元测试 mock http 请求，mock HTTP 外部接口，单元测试不依赖外部网络，保证用例稳定运行。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/42096627.html

原标题：快速入门YAML配置文件语法与示例
简介：golang snowflake 时钟回拨解决方案，雪花算法处理时钟回拨，防止生成重复 ID，保证 ID 全局唯一。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/62646019.html

原标题：golang http grpc 全链路埋点示例
简介：golang base64 编码解码实操，Go Base64 编码解码示例，处理业务场景 Base64 格式数据转换。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/67302210.html

原标题：golang 系统设计缓存 key 淘汰雪崩防护思路
简介：后端大文件分片上传接口开发，开发后端分片上传接口，接收分片，合并分片完成大文件存储。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/52494813.html

原标题：入门实践：简易进度条CLI工具实现demo
简介：golang 微服务网关简易实现，http 反向代理、路由匹配、鉴权限流，理解网关核心原理。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/13545564.html

原标题：OpenSource：开源项目README高质量编写指南
简介：golang 数据库慢查询监控实现，Go 封装 SQL 执行监控，记录慢 SQL，上报日志，发现数据库性能问题。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/12174709.html

原标题：golang 系统设计分表扩容数据平滑迁移思路
简介：golang 分布式锁 redis 实现，基于 Redis 实现 Go 分布式锁，解决多实例并发竞争资源问题。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/47108691.html


二、踩坑排错｜Troubleshooting
原标题：nodejs 事件循环机制完整讲解
简介：环境变量不生效问题修复，排查环境变量加载顺序、作用域问题，修复环境变量读取不到的异常。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/89341483.html

原标题：DevOps：制品仓库管理二进制产物版本
简介：golang lru 缓存淘汰算法编写，手写 LRU 缓存淘汰算法，实现本地缓存，淘汰最久未使用数据。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/37202625.html

原标题：数据库分表路由写入分片修正
简介：golang go 优雅处理信号丢失场景，处理信号丢失、信号被忽略，保障程序可以正常接收终止信号。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/81037276.html

原标题：Docker 网络模式容器互通设置
简介：大文件导出内存溢出防护，流式处理大文件导出，边读边写，不把全部数据加载内存，规避 OOM。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/24605705.html

原标题：golang 大文件读取内存优化
简介：多版本开发环境共存配置，实现同一工具多版本并存，快速切换不同版本，适配不同项目对版本的差异化需求。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/34474657.html

原标题：golang 参数校验业务接口处理
简介：golang GC 频繁 STW 停顿优化，减少小对象分配，调整 GOGC，降低 GC 停顿对接口延迟影响。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/22589096.html

原标题：golang 单元测试 mock http 请求
简介：golang mongodb 索引优化慢查询处理，mongodb 创建索引，分析慢查询，优化聚合查询执行性能。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/35170366.html

原标题：golang 系统设计开源项目 release 发布流程
简介：CORS 跨域问题多种解决方案，对比 CORS、代理等不同跨域方案优缺点，根据业务场景选择合适的跨域处理方式。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/90390581.html

原标题：安全实践：SQL注入产生场景与完整防御手段
简介：golang multipart 表单文件上传解析，服务端解析 multipart 表单，获取上传文件与表单字段。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/78259039.html

原标题：数据库分表路由写入分片修正
简介：多操作系统开发兼容处理，解决不同系统路径、换行符、权限差异，保证项目跨平台正常运行。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/37800354.html

原标题：golang excel 简单读写操作示例
简介：内存溢出问题现象识别排查，识别内存溢出现象，梳理排查方向，定位内存持续上涨引发服务崩溃问题。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/05920068.html

原标题：golang prometheus metrics 埋点开发
简介：golang go 程序抢占调度理解，理解 go 抢占式调度原理，长循环阻塞调度，造成协程调度延迟。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/90164737.html

原标题：GraphQL 接口查询优化实操
简介：日志驱动异常日志不输出修复，排查日志驱动配置，修复日志写入配置，恢复程序正常日志输出。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/64882948.html

原标题：golang 空接口 interface 使用技巧
简介：golang elasticsearch 客户端 golang 实操，es 客户端文档增删改查，条件搜索聚合统计对接搜索引擎。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/34803251.html

原标题：golang 系统设计大事务拆分实战思路
简介：特殊输入字符过滤解析防护，过滤用户输入特殊字符，防止解析报错，规避恶意字符带来业务异常。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/15751173.html

原标题：golang 系统设计压测环境隔离避免影响生产
简介：CI 流水线构建失败日志排查，阅读 CI 流水线输出日志，定位构建脚本、依赖、环境导致流水线失败问题。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/26289878.html

原标题：HelloTest：理解集成测试基础编写思路
简介：golang go 二进制安全 strip 减小体积，strip 剥离二进制调试符号，缩小程序二进制文件体积。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/47893483.html

原标题：TLS 版本兼容 HTTPS 握手失败
简介：golang channel 关闭规则与坑点，关闭已经关闭 channel 会 panic，判断 channel 是否关闭正确写法。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/73482217.html

原标题：css 变量主题切换方案实现
简介：nodejs 项目 pm2 部署运维指南，使用 PM2 管理 Node 服务，进程守护、日志、重启，线上部署运维实操。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/37333691.html

原标题：Practice：模拟缓存雪崩缓存击穿验证防护策略
简介：golang base64 大文件流式编解码，大文件流式 base64 转换，不用一次性加载全部文件进入内存。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/21823095.html

原标题：部署实践：服务器防火墙安全组配置实践
简介：golang go get 升级降级依赖版本，go get 指定版本升级降级依赖包，管理第三方库版本。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/37916117.html

原标题：内网 DNS 不稳定随机报错排查
简介：golang docker compose 开发环境 go 服务，docker compose 编排 go 服务与中间件，本地一键拉起整套开发环境。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/34034314.html

原标题：golang 系统设计死信队列 dlq 业务落地完整流程
简介：golang go get 升级降级依赖版本，go get 指定版本升级降级依赖包，管理第三方库版本。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/63488994.html

原标题：复盘总结：系统压测报告模板与分析思路
简介：vue pinia 状态管理实战教程，Pinia 完整实战示例，实现状态定义修改，模块拆分替代 Vuex。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/97959354.html

原标题：性能笔记：连接池参数调优数据库RPC连接池
简介：OAuth2 第三方登录服务搭建，搭建 OAuth2 服务，支持第三方账号登录，实现授权登录能力。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/32137186.html

原标题：方案对比：同步事务vs事务消息最终一致性
简介：golang 模糊测试 go fuzz 基础编写，Fuzz 测试函数，自动生成随机输入，发现代码崩溃 panic。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/79342043.html

原标题：golang net/http 超时全套配置
简介：程序性能指标 CPU 内存监控，讲解基础性能指标含义，简单实现监控采集，初步定位程序运行性能瓶颈。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/30134691.html

原标题：新手指南：本地多版本环境共存配置
简介：缓存基础原理与简单代码实现，讲解缓存设计思路，编写简易缓存逻辑，减少重复计算与重复请求，提升程序响应速度。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/59737943.html

原标题：用户敏感数据脱敏代码实现
简介：golang go select 多路等待 channel，select 等待多个 channel，default 非阻塞，超时等待 channel。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/78534271.html

原标题：新手教程：Gittag版本标签打标签实操
简介：golang clickhouse go 客户端数据写入，clickhouse‑go 客户端写入查询，海量时序数据分析业务。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/67847857.html

原标题：快速上手简单的限流逻辑模拟实现
简介：静态网页 HTML CSS 快速入门实战，通过简单页面案例讲解标签、样式布局，从零编写页面，理解网页基础渲染原理。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/53497858.html

原标题：部署复盘：回滚策略，线上故障快速回退
简介：golang rabbitmq go 客户端生产消费，streadway/amqp 实现 rabbitmq 生产者消费者，队列交换机绑定。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/99391621.html

原标题：安全实践：敏感信息加密存储传输完整方案
简介：golang 容器健康检查接口开发，Go 开发 HTTP 健康接口，供容器编排工具探测实例存活状态。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/88416006.html

原标题：批量数据处理脚本编写技巧
简介：简易网关请求路由过滤模拟，模拟网关基础能力，实现请求路由转发、简单过滤，理解网关核心工作逻辑。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/98388620.html

原标题：RPC 报文大小上限调优大请求
简介：golang go mod exclude 排除依赖版本，exclude 排除有问题依赖版本，规避有 bug 的第三方包。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/41289725.html

原标题：性能笔记：布隆过滤器减少无效数据库查询
简介：死信队列处理消息阻塞业务，配置死信队列，处理消费失败消息，避免失败消息阻塞整个队列业务。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/08083433.html

原标题：实践：Git大仓库历史清理减小仓库体积实践
简介：nodejs 信号处理优雅关闭服务，监听系统信号，执行资源清理，实现 Node 服务优雅停机，拒绝粗暴杀死进程。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/21556434.html

原标题：文件批量导入导出功能实现
简介：golang http 文件下载断点续传服务，服务端实现断点续传，支持大文件分段下载，提升大文件下载稳定性。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/22534209.html

原标题：golang 系统设计 commit 提交规范约定
简介：golang 路径处理 filepath 包规范写法，使用 filepath 处理路径拼接分割，自动适配操作系统路径分隔符。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/31981550.html

原标题：golang 大文件 http 下载服务
简介：golang 结构体零值可用性原则，go 结构体尽量做到零值可用，不用初始化直接使用提升易用性。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/29093780.html

三、实战开发｜Practice
原标题：排错：DockerCompose依赖顺序启动顺序坑
简介：golang 跨平台系统差异处理方案，处理 windows linux mac 路径、信号、文件权限差异，代码跨平台兼容。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/07520532.html

原标题：HTTPS 证书过期更新操作
简介：Nginx 丢失请求头配置修正，修复 Nginx 代理转发丢失请求头配置，保证上游服务拿到完整请求头信息。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/96415022.html

原标题：语义化版本依赖管理防错乱
简介：golang prometheus 指标埋点开发，业务埋点计数器、仪表盘、直方图，对接 prometheus 采集监控指标。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/41545377.html

原标题：nestjs 权限守卫鉴权实现方案
简介：golang redis hash 结构业务实战，使用 Redis Hash 存储对象数据，适合对象字段频繁更新业务场景。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/33893902.html

原标题：golang 系统设计链路查询定位慢请求实操技巧
简介：golang feishu 飞书机器人消息发送，调用飞书 webhook 机器人，发送文本卡片消息，实现业务告警通知。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/07827504.html

原标题：性能笔记：RPC超时参数优化防止级联阻塞
简介：磁盘占满服务不可用清理方案，定位磁盘占用大文件，清理日志、缓存文件，恢复磁盘可用空间。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/34889462.html

原标题：golang 系统设计密钥轮换安全实践思路
简介：项目目录结构规范化最佳实践，梳理源码、配置、静态资源目录划分，规范项目布局，提升代码可读性和可维护性。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/89047051.html

原标题：极简 API 网关路由转发实现
简介：容器软链接文件权限修复，修复容器内软链接文件权限，让程序能够正常读取软链接指向的文件。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/52371421.html

原标题：方案设计：分布式分页查询架构难点处理
简介：nodejs 进程间通信 IPC 实操，演示 Node.js 主进程子进程 IPC 通信，进程之间传递消息数据。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/29806111.html

原标题：安全实践：接口速率限制防止暴力破解
简介：golang mysql 长连接检测保活设置，配置 mysql 连接保活检测，剔除失效连接，避免拿到断开无效数据库连接。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/52497141.html

原标题：项目实践：分布式会话Redis存储落地实践
简介：golang excel 大文件读取流式解析，流式读取大 excel 文件，逐行解析数据，不加载全部内容进内存。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/32858903.html

原标题：开源实践：开源项目如何写好PullRequest
简介：golang time.Ticker 泄漏常见场景，忘记 Stop Ticker，导致协程泄漏，定时器资源无法释放。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/78667094.html

原标题：golang cpu pprof 性能分析实操
简介：golang docker compose 开发环境 go 服务，docker compose 编排 go 服务与中间件，本地一键拉起整套开发环境。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/77815770.html

原标题：开发记录：搭建CI/CD流水线自动构建部署项目
简介：golang rsa 非对称加密签名验签，RSA 非对称加密与签名验签，实现非对称安全通信。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/22549127.html

原标题：坑点：依赖包内部携带恶意代码供应链风险
简介：golang goroutine 池任务调度，实现 goroutine 池，复用协程，频繁任务场景减少协程创建销毁开销。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/60515373.html

原标题：线上接口超时故障排查思路
简介：站内邮件消息通知功能开发，实现站内消息、邮件通知推送，业务事件触发通知，提醒用户业务状态变更。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/30819084.html

原标题：golang 系统设计 README 开源文档模板
简介：golang 系统资源限制读取 cpu 内存，读取系统容器 cpu 内存限制，程序适配容器资源配额做业务调优。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/33845492.html

原标题：运维笔记：系统监控指标大盘搭建实操
简介：golang context.WithValue 传递元数据，WithValue 只传 traceId 鉴权元数据，不要传业务大对象。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/93137736.html

原标题：golang 系统设计 git 分支流程 gitflow 实操
简介：golang ssh 客户端远程命令执行，golang ssh 连接远程服务器，执行 shell 命令，获取命令输出结果。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/94582500.html

原标题：不必要字符转义关闭业务异常
简介：前端防抖节流高频事件处理，封装防抖节流工具，处理滚动、输入框输入等高频触发事件减少执行次数。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/85652261.html

原标题：golang http 服务性能优化调参
简介：golang select 随机分支执行特性，多个 channel 就绪 select 随机选择，理解 select 行为特性。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/88526270.html

原标题：重复提交幂等防护再次讲解
简介：golang mqtt 客户端 go 开发物联网，paho.mqtt.golang 实现 mqtt 客户端，物联网设备消息收发。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/66431008.html

原标题：golang 系统设计 protobuf 默认值坑点梳理
简介：golang go decimal 定点小数金额计算，decimal 库处理金额，规避 float64 精度丢失，财务计算。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/71805502.html

原标题：安全复盘：消息队列未授权访问安全加固
简介：golang 性能压测 wr 工具实操指南，wr 压测工具对 Go 接口压测，观察 QPS 延迟，定位接口性能瓶颈。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/82229516.html

原标题：golang 系统设计定时任务执行超时中断防护
简介：业务错误码完整落地实践，落地完整业务错误码，枚举全部业务异常，统一返回，配套文档说明。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/82669139.html

原标题：golang docker 网络模式桥接 host
简介：Cookie Session 会话状态管理，讲解 Cookie 与 Session 原理，理解登录状态保存，实现服务端会话管理逻辑。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/99650758.html

原标题：序列化版本不一致解析失败
简介：golang context.WithTimeout 超时上下文，WithTimeout 设置超时时间，超时自动 cancel 释放协程。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/52276655.html

原标题：golang 系统设计告警升级通知策略配置思路
简介：本地运行正常线上报错排查，对比本地与线上环境差异，从配置、系统版本、文件权限定位线上独有的 bug。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/29833591.html

原标题：开发复盘：搭建文件上传服务支持分片断点续传
简介：golang 系统调用跟踪 strace 排查 go 程序，strace 跟踪系统调用，定位文件网络 IO 慢的底层原因。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/52878893.html

原标题：golang 系统设计唯一索引业务使用场景
简介：golang go 排序 sort 包自定义排序，sort 包实现自定义排序逻辑，对切片按业务规则排序。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/34543886.html

原标题：golang 系统设计 canary 金丝雀部署实操
简介：SSH 密钥配置 GitHub 免密登录，分步生成配置 SSH 密钥，实现 GitHub 免密推送拉取，免去重复输入账号密码的麻烦。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/95411444.html

原标题：Hands‑on：本地模拟消息重复消费处理实践
简介：golang 结构体零值可用性原则，go 结构体尽量做到零值可用，不用初始化直接使用提升易用性。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/22766677.html

原标题：HelloShell：入门常用shell脚本编写
简介：分布式任务调度集群原型开发，开发简易分布式调度原型，集群多节点运行，保证任务只执行一次。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/87167806.html

原标题：golang 系统设计消息体序列化选型对比
简介：golang sort 稳定排序 Stable，稳定排序保留相等元素原有顺序，业务需要稳定排序场景。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/11874097.html

原标题：缓存穿透防护保护数据库
简介：golang goroutine 泄露检测告警实现，监控 goroutine 数量，突增触发告警，提早发现协程泄露。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/45920007.html

原标题：golang 系统设计重试退避策略业务落地
简介：项目脚手架模板生成工具，搭建项目模板脚手架，一键生成标准化项目骨架，减少重复初始化工作。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/22301947.html

原标题：golang 系统设计网关路由规则动态配置实现
简介：MySQL 慢查询索引优化实战，抓取慢查询 SQL，分析执行计划，新增或者调整索引，提升 SQL 执行速度。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/22808469.html

原标题：golang nginx 反向代理 go 服务配置
简介：golang mongodb 索引优化慢查询处理，mongodb 创建索引，分析慢查询，优化聚合查询执行性能。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/54288192.html

原标题：HelloTest：理解集成测试基础编写思路
简介：JWT 令牌过期异常处理，捕获 JWT 过期、篡改异常，编写业务处理逻辑，引导用户重新获取令牌。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/34512775.html

原标题：golang base64 编码解码实操
简介：golang https 客户端跳过证书校验，开发测试环境跳过 tls 证书校验，仅用于内网测试禁止生产使用。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/60067399.html

四、架构设计｜Architecture
原标题：内存泄漏定位分析完整流程
简介：golang prometheus 指标埋点开发，业务埋点计数器、仪表盘、直方图，对接 prometheus 采集监控指标。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/68690034.html

原标题：性能笔记：磁盘IO过高业务优化手段
简介：golang 本地消息表实现最终一致性，本地消息表 + 定时任务轮询，可靠消息实现分布式事务。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/31980567.html

原标题：Hands‑on：简易短链接服务完整开发实践
简介：golang go 模板缓存预编译模板，预编译 html 模板，程序启动加载，避免每次请求解析模板损耗性能。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/63875721.html

原标题：开发复盘：大事务拆分优化业务性能实践
简介：golang 钉钉企业微信告警消息推送，go 调用企业微信钉钉接口，推送告警通知、业务消息。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/51619426.html

原标题：Practice：模拟缓存雪崩缓存击穿验证防护策略
简介：golang go ring 环形容器循环队列，ring 环形链表实现循环队列，环形缓冲区业务场景。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/84186587.html

原标题：RPC 报文大小上限调优大请求
简介：RPC 报文大小上限调优大请求，调大 RPC 框架报文最大限制，支持传输大体积请求报文不被截断。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/38551040.html

原标题：golang 分布式锁防死锁处理
简介：golang redis scan 遍历 key 避免阻塞，使用 scan 迭代遍历 redis 键，不用 keys 命令，防止阻塞 redis 服务。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/20428352.html

原标题：架构复盘：热点数据防护架构防止节点过载
简介：git rebase 整理提交历史实操，使用 rebase 整理杂乱提交记录，将多条提交合并，保持 git 提交历史干净线性。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/29896433.html

原标题：静态网页 HTML CSS 快速入门实战
简介：Nginx 缓冲区调优大文件上传，调大 Nginx 请求缓冲区，支持客户端上传大体积文件，避免上传被截断。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/90895173.html

原标题：开发复盘：大数据量分页避免offset性能问题
简介：golang grpc 客户端拦截器封装，grpc 客户端拦截器实现请求统一签名、重试、链路信息透传。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/59720075.html

原标题：开发复盘：搭建文件上传服务支持分片断点续传
简介：读懂开源项目 README 实用技巧，教你快速解析开源项目说明文档，提取安装、运行、配置关键信息，快速上手项目。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/20946925.html

原标题：golang 分布式上下文传递方案
简介：golang clickhouse go 客户端数据写入，clickhouse‑go 客户端写入查询，海量时序数据分析业务。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/09687682.html

原标题：安全复盘：业务登录暴力破解防护完整方案
简介：nodejs 脚手架工具开发完整教程，从零开发 Node 命令行脚手架，实现项目模板生成，理解 CLI 开发。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/84386879.html

原标题：部署实践：内网开发环境代理配置实践
简介：大事务拆分回滚日志暴涨解决，拆分大型数据库事务，减少回滚日志生成量，避免磁盘被回滚日志占满。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/53738138.html

原标题：开发复盘：数据库批量更新优化性能实践
简介：golang json 自定义 MarshalJSON UnmarshalJSON，自定义 json 序列化反序列化逻辑，处理特殊格式字段。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/49057338.html

原标题：避坑：版本升级之后项目直接无法启动
简介：golang time 时间格式化避坑，Go 时间格式化参考时间牢记，处理时间解析格式化，解决时间输出错乱。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/61945775.html

原标题：golang 系统设计压测环境隔离避免影响生产
简介：消息队列重复消费业务处理，实现消息消费幂等，处理重复投递消息，保证多次消费业务结果一致。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/97190097.html

原标题：Hands‑on：简易验证码生成校验后端实践
简介：golang http client Transport 参数调优，Transport 最大连接空闲连接，TLS 配置，http 客户端调优。
 | 原文链接：http://www.blog.nodlc.cn/jingyingd/92619848.html

?
