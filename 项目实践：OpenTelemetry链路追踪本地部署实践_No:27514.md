最新前沿技术资讯

一、入门教程｜Getting Started
原标题：项目实践：OpenTelemetry链路追踪本地部署实践
简介：服务健康检查告警监控体系，搭建健康检查加告警体系，服务异常及时推送告警通知运维人员。
 | 原文链接：http://zhishi.wikcr1.asia/blog/9309355.sHtML

原标题：快速上手简单的限流逻辑模拟实现
简介：全局时间标准统一逻辑错乱修复，全服务统一使用同一时间标准，不要混用本地时间 UTC，修复时间逻辑 bug。
 | 原文链接：http://zhishi.wikcr1.asia/blog/0569017.sHtML

原标题：开发复盘：批量任务进度持久化实现方案
简介：Git 子模块更新代码不全修复，正确更新 Git 子模块，拉取子模块完整代码，解决子模块目录为空问题。
 | 原文链接：http://zhishi.wikcr1.asia/blog/4991130.sHtML

原标题：开源实践：开源项目本地调试构建排坑经验
简介：golang http client 全局变量复用，http Client 不要每次请求新建，复用 Transport 提升性能。
 | 原文链接：http://zhishi.wikcr1.asia/blog/6847270.sHtML

原标题：Debug：静态资源缓存策略错误，用户看不到更新
简介：容器资源限制防止宿主机过载，设置容器 CPU 内存资源上限，避免单个容器耗尽宿主机全部硬件资源。
 | 原文链接：http://zhishi.wikcr1.asia/blog/3848804.sHtML

原标题：Issue：开源项目升级大版本后API不兼容踩坑
简介：前端权限路由动态生成实现，根据后端返回权限，动态生成前端路由菜单，实现页面权限控制。
 | 原文链接：http://zhishi.wikcr1.asia/blog/8558321.sHtML

原标题：设计思考：系统限流熔断降级完整防护体系
简介：golang jaeger 链路追踪部署对接，jaeger 接收 opentelemetry 链路数据，可视化完整调用链路。
 | 原文链接：http://zhishi.wikcr1.asia/blog/6645054.sHtML

原标题：实践：接口参数自动校验业务落地实践
简介：golang 日志脱敏敏感字段过滤，日志打印自动脱敏敏感字段，避免日志输出手机号身份证泄露隐私。
 | 原文链接：http://zhishi.wikcr1.asia/blog/5928689.sHtML

原标题：golang ci 流水线漏洞扫描依赖检查
简介：golang 漏桶算法实现接口限流，漏桶算法控制请求流出速率，平滑突发流量，削平流量峰值。
 | 原文链接：http://zhishi.wikcr1.asia/blog/6139197.sHtML

原标题：架构复盘：服务灰度发布架构设计与流量切分
简介：golang sync.Cond 条件变量使用，Cond 条件变量协程等待唤醒，复杂并发同步场景。
 | 原文链接：http://zhishi.wikcr1.asia/blog/6664272.sHtML

原标题：优化实践：LRU本地缓存优化热点访问性能
简介：OpenAPI 自动接口文档生成，集成 OpenAPI 工具，自动扫描代码生成接口文档，减少文档维护成本。
 | 原文链接：http://zhishi.wikcr1.asia/blog/7201346.sHtML

原标题：开源源码阅读拆解学习思路
简介：时间精度统一业务判断修复，统一业务使用时间戳精度，毫秒秒区分清楚，修复时间判断逻辑错误。
 | 原文链接：http://zhishi.wikcr1.asia/blog/8277517.sHtML

原标题：golang 系统设计缓存基准测试对比方案
简介：缓存过期打散防止缓存雪崩，对缓存过期时间增加随机偏移，避免大量缓存同时失效引发缓存雪崩。
 | 原文链接：http://zhishi.wikcr1.asia/blog/2436948.sHtML

原标题：安全笔记：Git仓库密钥硬编码泄露处理方案
简介：nodejs 数据库连接池配置调优，调优 Node 数据库连接池参数，平衡性能与资源占用，避免连接耗尽。
 | 原文链接：http://zhishi.wikcr1.asia/blog/5701473.sHtML

原标题：Performance：数据库join优化，大表join规避
简介：golang go 排序 sort 包自定义排序，sort 包实现自定义排序逻辑，对切片按业务规则排序。
 | 原文链接：http://zhishi.wikcr1.asia/blog/8500342.sHtML

原标题：golang defer panic 异常处理
简介：Git 混乱提交历史清理方法，针对杂乱的提交记录，使用 Git 工具整理，清理无效提交，还原整洁版本历史。
 | 原文链接：http://zhishi.wikcr1.asia/blog/2094909.sHtML

原标题：golang mysql 存储过程简单使用
简介：golang defer panic 异常处理，理解 defer 延迟执行，panic 恐慌捕获，实现函数资源释放异常保护。
 | 原文链接：http://zhishi.wikcr1.asia/blog/9342878.sHtML

原标题：从零搭建简单的健康检查接口示例
简介：golang http.Server 配置参数详解，ReadTimeout WriteTimeout IdleTimeout，全方位防护慢请求攻击。
 | 原文链接：http://zhishi.wikcr1.asia/blog/8313744.sHtML

原标题：golang 系统设计告警规则阈值设置方法论
简介：golang gorm group by 分组统计，GORM 分组聚合统计，实现 count sum 等统计查询，快速完成统计业务。
 | 原文链接：http://zhishi.wikcr1.asia/blog/3068499.sHtML

原标题：架构笔记：分库分表中间件选型业务约束
简介：文件句柄上限调整上传随机失败，调高系统文件句柄上限，解决高并发上传场景随机打开文件失败。
 | 原文链接：http://zhishi.wikcr1.asia/blog/8913385.sHtML

原标题：安全实践：防止JSON解析漏洞恶意payload
简介：golang kafka 同步异步消费对比，对比 Kafka 同步消费异步消费，分析优缺点，业务选型参考。
 | 原文链接：http://zhishi.wikcr1.asia/blog/6434016.sHtML

原标题：golang go test 覆盖率统计实操
简介：缓存穿透击穿雪崩全套防护，完整梳理缓存三大问题，落地全套防护策略，保障缓存层稳定运行。
 | 原文链接：http://zhishi.wikcr1.asia/blog/9394081.sHtML

原标题：golang 系统设计 traceId 全链路透传完整方案
简介：golang http 中间件洋葱模型原理，理解 go http 中间件洋葱模型，请求响应流转顺序，编写自定义中间件。
 | 原文链接：http://zhishi.wikcr1.asia/blog/2651754.sHtML

原标题：golang 系统设计读写穿透更新缓存几种方案
简介：golang go 模板执行错误捕获，捕获模板执行错误，防止模板错误直接返回空白页面。
 | 原文链接：http://zhishi.wikcr1.asia/blog/7772121.sHtML

原标题：golang 结构体深拷贝几种实现
简介：日志驱动异常日志不输出修复，排查日志驱动配置，修复日志写入配置，恢复程序正常日志输出。
 | 原文链接：http://zhishi.wikcr1.asia/blog/9213581.sHtML

原标题：Hands‑on：简易消息推送服务开发实践
简介：golang go panic 合理使用边界，panic 只用于不可恢复程序错误，业务逻辑禁止直接 panic。
 | 原文链接：http://zhishi.wikcr1.asia/blog/8508908.sHtML

原标题：零基础理解幂等性基础概念与场景
简介：golang rsa 签名验签 pem 证书加载，加载 pem 格式密钥证书，rsa 签名与验签完整业务实现。
 | 原文链接：http://zhishi.wikcr1.asia/blog/5054098.sHtML

原标题：移动端适配 rem vw 方案对比
简介：前端组件库按需加载性能优化，配置组件库按需引入，避免引入全部组件，减少打包产物体积。
 | 原文链接：http://zhishi.wikcr1.asia/blog/4313490.sHtML

原标题：golang redis pipeline 原子性说明
简介：golang dns 自定义解析器实现，自定义 dns 解析，指定 dns 服务器，控制域名解析逻辑，适配内网环境。
 | 原文链接：http://zhishi.wikcr1.asia/blog/3401080.sHtML

原标题：主干开发团队代码合并策略
简介：golang atomic.Value 存储任意类型数据，atomic.Value 安全存储读取任意类型，配置热更新常用。
 | 原文链接：http://zhishi.wikcr1.asia/blog/9429911.sHtML

原标题：设计思考：API网关和BFF职责边界划分
简介：golang go 测试 t.Run 子测试分组，t.Run 实现子测试，分组执行用例，输出分组测试结果。
 | 原文链接：http://zhishi.wikcr1.asia/blog/4877565.sHtML

原标题：golang 系统设计 rest 分页排序过滤参数规范
简介：golang rate‑limiter 限流组件，封装通用 Go 限流组件，支持多算法，业务接口直接复用调用。
 | 原文链接：http://zhishi.wikcr1.asia/blog/5401154.sHtML

原标题：跨平台换行符统一异常修复
简介：css 变量主题切换方案实现，使用 CSS 变量实现网页主题切换，多套主题样式快速切换无需大量 CSS。
 | 原文链接：http://zhishi.wikcr1.asia/blog/6158760.sHtML

原标题：golang 系统设计请求签名校验完整方案
简介：golang interface 接口使用避坑，interface 判 nil 坑点，理解接口底层结构，避免判空逻辑失效。
 | 原文链接：http://zhishi.wikcr1.asia/blog/8063550.sHtML

原标题：golang 系统设计消息可靠性投递实现
简介：CORS 跨域问题多种解决方案，对比 CORS、代理等不同跨域方案优缺点，根据业务场景选择合适的跨域处理方式。
 | 原文链接：http://zhishi.wikcr1.asia/blog/5099766.sHtML

原标题：踩坑记录：分页逻辑错误造成数据重复输出
简介：golang 系统信号信号量处理，Go 处理系统各类信号，SIGINT、SIGTERM，实现程序可控退出。
 | 原文链接：http://zhishi.wikcr1.asia/blog/4873251.sHtML

原标题：新手指南：本地多版本环境共存配置
简介：数据库事务 ACID 原理讲解，拆解事务四大特性，理解事务隔离、原子性，明白事务如何保障数据安全。
 | 原文链接：http://zhishi.wikcr1.asia/blog/8202381.sHtML

原标题：浏览器内存泄漏排查前端页面
简介：golang go 线上故障排查完整流程，CPU 高、内存上涨、接口超时、goroutine 泄露一套排查处理流程。
 | 原文链接：http://zhishi.wikcr1.asia/blog/5217784.sHtML

原标题：Security：SSRF服务端请求伪造漏洞防御
简介：golang 自定义 http round tripper，封装 http 客户端拦截，实现请求日志、签名、重试统一处理逻辑。
 | 原文链接：http://zhishi.wikcr1.asia/blog/8647294.sHtML

原标题：golang github actions 缓存依赖提速
简介：golang atomic.Value 存储任意类型数据，atomic.Value 安全存储读取任意类型，配置热更新常用。
 | 原文链接：http://zhishi.wikcr1.asia/blog/6735081.sHtML


二、踩坑排错｜Troubleshooting
原标题：golang mysql 主从同步延迟兼容
简介：golang 反向代理 http 服务开发，手写简易 http 反向代理，转发请求，修改请求头响应头。
 | 原文链接：http://zhishi.wikcr1.asia/blog/3676249.sHtML

原标题：golang 分布式锁防死锁处理
简介：golang go 爬虫异步并发抓取，协程池控制并发抓取网页，多协程采集，提升爬虫采集速度。
 | 原文链接：http://zhishi.wikcr1.asia/blog/1942715.sHtML

原标题：nodejs http 服务性能调优实战
简介：项目语义化版本号规范管理，遵循语义化版本规范管理项目版本，明确主次版本变更含义。
 | 原文链接：http://zhishi.wikcr1.asia/blog/5385723.sHtML

原标题：Practice：实现异步回调处理通用组件封装
简介：golang go 信号处理优雅重启实现，USR2 触发程序重启，不关闭监听 socket 实现零停机升级。
 | 原文链接：http://zhishi.wikcr1.asia/blog/5222387.sHtML

原标题：nodejs 数据库连接池配置调优
简介：golang 程序崩溃 core dump 生成调试，开启 core dump，程序崩溃生成转储文件，事后分析崩溃原因。
 | 原文链接：http://zhishi.wikcr1.asia/blog/1680260.sHtML

原标题：Cookie Session 会话状态管理
简介：golang kafka 同步异步消费对比，对比 Kafka 同步消费异步消费，分析优缺点，业务选型参考。
 | 原文链接：http://zhishi.wikcr1.asia/blog/0724439.sHtML

原标题：golang http 服务性能优化调参
简介：golang time.Ticker 泄漏常见场景，忘记 Stop Ticker，导致协程泄漏，定时器资源无法释放。
 | 原文链接：http://zhishi.wikcr1.asia/blog/8537568.sHtML

原标题：golang 系统设计 issue 模板 bug 反馈模板
简介：极简方式搭建个人技术文档站点，使用轻量化工具快速部署文档站点，支持 markdown 编写，实现知识沉淀与对外分享。
 | 原文链接：http://zhishi.wikcr1.asia/blog/0897792.sHtML

原标题：排错：前端缓存304异常更新不及时
简介：golang cgo 性能开销避坑指南，cgo 调用开销，减少频繁 cgo 调用，规避 cgo 带来内存泄漏风险。
 | 原文链接：http://zhishi.wikcr1.asia/blog/1551493.sHtML

原标题：golang 工具函数库封装思路
简介：nodejs 集成测试业务流程编写，编写 Node 集成测试，调用真实接口，验证完整业务链路执行结果。
 | 原文链接：http://zhishi.wikcr1.asia/blog/4205263.sHtML

原标题：golang redis pipeline 原子性说明
简介：超大数据集分页性能优化方案，对比不同分页方案，针对海量数据集做分页性能优化，解决越翻越慢。
 | 原文链接：http://zhishi.wikcr1.asia/blog/0740408.sHtML

原标题：部署实践：Nginx高可用配置方案实践
简介：golang go 信号处理优雅重启实现，USR2 触发程序重启，不关闭监听 socket 实现零停机升级。
 | 原文链接：http://zhishi.wikcr1.asia/blog/9066721.sHtML

原标题：消息队列生产消费模型入门
简介：Spring 事务传播机制配置生效，理解事务传播行为，正确配置，修复事务不生效、事务失效的业务 bug。
 | 原文链接：http://zhishi.wikcr1.asia/blog/9517000.sHtML

原标题：开发复盘：海量日志轮转清理脚本实践
简介：golang 钉钉企业微信告警消息推送，go 调用企业微信钉钉接口，推送告警通知、业务消息。
 | 原文链接：http://zhishi.wikcr1.asia/blog/2788563.sHtML

原标题：nodejs 接口限流防刷代码实现
简介：golang go1.18 + 泛型基础实操，go 泛型基础语法，泛型函数泛型类型，实现通用工具函数。
 | 原文链接：http://zhishi.wikcr1.asia/blog/6991494.sHtML

原标题：性能笔记：HTTP连接复用性能优化实践
简介：golang proto 可选字段处理方案，protobuf 可选字段正确判断，区分未赋值与零值，业务逻辑不出现偏差。
 | 原文链接：http://zhishi.wikcr1.asia/blog/9949739.sHtML

原标题：架构复盘：容器资源隔离架构CPU内存限制设计
简介：golang 限制 multipart 内存大小，设置 MaxMemory，大文件写入磁盘临时文件防止内存暴涨。
 | 原文链接：http://zhishi.wikcr1.asia/blog/2492337.sHtML

原标题：文件批量导入导出功能实现
简介：golang gorm 预加载关联查询优化，GORM 预加载关联数据，避免 N+1 查询问题，提升数据库查询性能。
 | 原文链接：http://zhishi.wikcr1.asia/blog/5706148.sHtML

原标题：快速入门异步编程基础模型
简介：Nginx 请求头大小上限调整，修改 Nginx 配置，调大请求头允许最大大小，避免大 Header 请求被拒绝。
 | 原文链接：http://zhishi.wikcr1.asia/blog/4436767.sHtML

原标题：golang 系统设计缓存基准测试对比方案
简介：golang channel 关闭规则与坑点，关闭已经关闭 channel 会 panic，判断 channel 是否关闭正确写法。
 | 原文链接：http://zhishi.wikcr1.asia/blog/6392868.sHtML

原标题：golang docker 部署 mysql 注意事项
简介：大事务拆分回滚日志暴涨解决，拆分大型数据库事务，减少回滚日志生成量，避免磁盘被回滚日志占满。
 | 原文链接：http://zhishi.wikcr1.asia/blog/1976192.sHtML

原标题：实战：多版本SDK兼容业务改造实践
简介：golang gin 路由分组权限管控，Gin 路由分组，不同分组绑定鉴权中间件，实现接口权限分组管控。
 | 原文链接：http://zhishi.wikcr1.asia/blog/3761750.sHtML

原标题：golang 系统设计性能瓶颈定位完整方法论
简介：golang netlink 系统信息获取，netlink 获取系统网络信息，网卡地址，内核网络状态读取。
 | 原文链接：http://zhishi.wikcr1.asia/blog/6880216.sHtML

原标题：架构复盘：系统扩容缩容架构无状态优先原则
简介：golang go 程序权限最小化运行，容器内使用普通用户运行程序，拒绝 root 运行提升安全等级。
 | 原文链接：http://zhishi.wikcr1.asia/blog/9047279.sHtML

原标题：golang k8s liveness readiness 探针
简介：golang 项目目录分层规范设计，Go 后端项目目录分层规范，按领域分层，提高项目可读性可维护性。
 | 原文链接：http://zhishi.wikcr1.asia/blog/3091638.sHtML

原标题：golang 系统设计监控大盘故障快速定位思路
简介：golang csv 读写批量数据处理，Go 读写 CSV 文件，批量导入导出业务数据，处理 CSV 格式解析。
 | 原文链接：http://zhishi.wikcr1.asia/blog/5984386.sHtML

原标题：架构复盘：消息死信处理架构避免消息丢失
简介：golang 集成测试测试数据库回滚，集成测试结束自动回滚数据库，不污染测试环境数据。
 | 原文链接：http://zhishi.wikcr1.asia/blog/3919534.sHtML

原标题：新手避坑：第一次提交GitHub项目完整流程
简介：golang 项目目录分层规范设计，Go 后端项目目录分层规范，按领域分层，提高项目可读性可维护性。
 | 原文链接：http://zhishi.wikcr1.asia/blog/2332139.sHtML

原标题：DevOps：GitLabCI完整流水线配置示例
简介：多套环境灵活切换配置方案，实现配置动态切换，通过环境变量、配置文件，快速切换开发测试生产环境。
 | 原文链接：http://zhishi.wikcr1.asia/blog/1685490.sHtML

原标题：Hands‑on：简易链路追踪原型开发实践
简介：跨域偶现失败配置修复，解决跨域问题时而复现时而正常，定位配置漏配、请求头异常等隐性问题。
 | 原文链接：http://zhishi.wikcr1.asia/blog/1941372.sHtML

原标题：开发记录：容器日志标准输出采集实践方案
简介：nodejs 消息队列消费服务开发，Node 开发消息队列消费端，监听队列消息执行业务逻辑，异步解耦业务。
 | 原文链接：http://zhishi.wikcr1.asia/blog/9006508.sHtML

原标题：golang mysql 存储过程简单使用
简介：golang go 值传递引用传递理解，go 全部为值传递，指针本质拷贝指针值，理清参数传递行为。
 | 原文链接：http://zhishi.wikcr1.asia/blog/5491167.sHtML

原标题：架构笔记：冷热数据分离架构设计与迁移
简介：空指针异常判空容错处理，讲解空指针产生场景，规范判空逻辑，增加容错，避免空指针直接造成程序崩溃。
 | 原文链接：http://zhishi.wikcr1.asia/blog/0136141.sHtML

原标题：golang redis 布隆过滤器安装使用
简介：css 变量主题切换方案实现，使用 CSS 变量实现网页主题切换，多套主题样式快速切换无需大量 CSS。
 | 原文链接：http://zhishi.wikcr1.asia/blog/5270084.sHtML

原标题：golang 令牌桶限流中间件 gin
简介：后端分页查询逻辑代码实现，编写后端分页接口，处理页码、每页条数参数，优化大数据量查询返回结果。
 | 原文链接：http://zhishi.wikcr1.asia/blog/9380105.sHtML

原标题：vue3 组合式 API 业务开发实战
简介：golang 系统调用跟踪 strace 排查 go 程序，strace 跟踪系统调用，定位文件网络 IO 慢的底层原因。
 | 原文链接：http://zhishi.wikcr1.asia/blog/2756487.sHtML

原标题：读懂开源项目 README 实用技巧
简介：全局时间标准统一逻辑错乱修复，全服务统一使用同一时间标准，不要混用本地时间 UTC，修复时间逻辑 bug。
 | 原文链接：http://zhishi.wikcr1.asia/blog/6128106.sHtML

原标题：golang mongodb 索引优化查询速度
简介：CI 构建缓存加速编译速度，开启 CI 流水线依赖缓存，复用上一次构建依赖包，缩短流水线构建耗时。
 | 原文链接：http://zhishi.wikcr1.asia/blog/7269421.sHtML

原标题：golang k8s service 服务暴露几种类型
简介：golang gin 静态资源访问配置，Gin 配置静态资源目录，直接对外提供静态文件访问服务。
 | 原文链接：http://zhishi.wikcr1.asia/blog/9739784.sHtML

原标题：Debug：长连接未设置心跳，连接僵死不回收
简介：eslint prettier 代码规范落地，配置 eslint 与 prettier，做代码检查格式化，统一前端团队代码风格。
 | 原文链接：http://zhishi.wikcr1.asia/blog/0090436.sHtML

三、实战开发｜Practice
原标题：golang 系统设计架构图绘图工具选型对比
简介：前端打包分包加载提速方案，前端打包做代码分包，拆分大 bundle，页面按需加载，提升首屏加载速度。
 | 原文链接：http://zhishi.wikcr1.asia/blog/2261900.sHtML

原标题：坑点：环境配置被打包进镜像引发安全泄露
简介：程序信号中断退出处理逻辑，捕获系统中断信号，执行资源释放、关闭连接，实现程序优雅退出。
 | 原文链接：http://zhishi.wikcr1.asia/blog/7264344.sHtML

原标题：Security：密码存储哈希加盐最佳实践
简介：服务健康检查告警监控体系，搭建健康检查加告警体系，服务异常及时推送告警通知运维人员。
 | 原文链接：http://zhishi.wikcr1.asia/blog/2703025.sHtML

原标题：接口幂等性防重复请求实现
简介：golang 错误栈捕获打印方案，捕获错误完整调用堆栈，线上日志输出堆栈，快速定位错误发生代码位置。
 | 原文链接：http://zhishi.wikcr1.asia/blog/7846500.sHtML

原标题：golang 系统设计压力测试性能测试执行流程
简介：golang 单元测试 table‑driven，表格驱动单元测试写法，批量输入多组测试用例，简化单元测试代码。
 | 原文链接：http://zhishi.wikcr1.asia/blog/3385009.sHtML

原标题：并发数据覆盖加锁安全处理
简介：golang sort 稳定排序 Stable，稳定排序保留相等元素原有顺序，业务需要稳定排序场景。
 | 原文链接：http://zhishi.wikcr1.asia/blog/9314358.sHtML

原标题：golang alertmanager 钉钉告警推送
简介：golang go 排序 sort 包自定义排序，sort 包实现自定义排序逻辑，对切片按业务规则排序。
 | 原文链接：http://zhishi.wikcr1.asia/blog/7207468.sHtML

原标题：从零搭建简单定时任务demo
简介：golang go 输入数据校验防御，所有外部入参严格校验长度格式，防止恶意输入造成业务异常。
 | 原文链接：http://zhishi.wikcr1.asia/blog/0432862.sHtML

原标题：golang es 聚合统计查询实现
简介：golang 时间时区处理避坑指南，Go 时间时区常见坑，时区转换，时间比较，规避时间逻辑错误。
 | 原文链接：http://zhishi.wikcr1.asia/blog/1610535.sHtML

原标题：golang 系统设计重试退避策略业务落地
简介：golang redis hyperloglog 基数统计，hyperloglog 统计 UV 基数，海量数据去重统计，极低内存开销。
 | 原文链接：http://zhishi.wikcr1.asia/blog/5310977.sHtML

原标题：Redis 内存淘汰策略数据防丢失
简介：nestjs 权限守卫鉴权实现方案，使用 Nest 守卫实现接口鉴权，角色权限控制，拦截未授权接口访问。
 | 原文链接：http://zhishi.wikcr1.asia/blog/9135625.sHtML

原标题：golang 系统设计时间字段选型 datetime timestamp
简介：golang 分布式锁防死锁实现要点，锁超时、续期、锁持有者校验，避免锁死锁，保障分布式锁可靠性。
 | 原文链接：http://zhishi.wikcr1.asia/blog/2679534.sHtML

原标题：nodejs 全局异常捕获进程防护
简介：golang 链路追踪简易实现方案，简易链路追踪实现，传递 traceId，记录调用链路，方便排查慢调用。
 | 原文链接：http://zhishi.wikcr1.asia/blog/3698880.sHtML

原标题：golang redis zset 排行榜业务实现
简介：git cherry‑pick 规范操作防 bug，规范 cherry‑pick 使用流程，处理冲突，避免错误引入不兼容代码。
 | 原文链接：http://zhishi.wikcr1.asia/blog/6981931.sHtML

原标题：文件锁正确使用避免死锁
简介：golang bufio.Scanner 按行读取大文件，Scanner 逐行读取文本文件，处理超大日志 csv。
 | 原文链接：http://zhishi.wikcr1.asia/blog/3770106.sHtML

原标题：golang etcd 配置中心简单使用
简介：golang sftp 文件上传下载操作，sftp 协议远程文件上传下载，实现服务器之间文件传输功能。
 | 原文链接：http://zhishi.wikcr1.asia/blog/4863596.sHtML

原标题：快速入门：API接口调试完整实操步骤
简介：golang go mod vendor 本地依赖导出，导出 vendor 目录，离线环境编译项目，无需访问外网拉依赖。
 | 原文链接：http://zhishi.wikcr1.asia/blog/6636096.sHtML

原标题：性能笔记：TCP参数内核调优服务高并发场景
简介：golang 结构体 json 序列化坑点，梳理 Go 结构体 JSON 序列化高频坑点，字段大小写、零值处理问题。
 | 原文链接：http://zhishi.wikcr1.asia/blog/7754178.sHtML

原标题：Practice：实现接口mock动态返回不同响应
简介：golang go 爬虫代理池轮换使用，http 代理池轮换，请求自动切换代理 IP，突破访问限制。
 | 原文链接：http://zhishi.wikcr1.asia/blog/3423617.sHtML

原标题：golang 系统设计开源项目自动化 ci 配置示例
简介：golang time.Ticker 泄漏常见场景，忘记 Stop Ticker，导致协程泄漏，定时器资源无法释放。
 | 原文链接：http://zhishi.wikcr1.asia/blog/3630811.sHtML

原标题：golang 大文件读取内存优化
简介：golang lru 缓存淘汰算法编写，手写 LRU 缓存淘汰算法，实现本地缓存，淘汰最久未使用数据。
 | 原文链接：http://zhishi.wikcr1.asia/blog/0982437.sHtML

原标题：Troubleshooting：WSL文件权限问题大量踩坑
简介：golang testify mock 模拟接口，mock 接口生成 mock 对象，单元测试模拟外部依赖行为。
 | 原文链接：http://zhishi.wikcr1.asia/blog/8611379.sHtML

原标题：golang channel 通道并发处理
简介：Nginx 请求头大小上限调整，修改 Nginx 配置，调大请求头允许最大大小，避免大 Header 请求被拒绝。
 | 原文链接：http://zhishi.wikcr1.asia/blog/1316273.sHtML

原标题：golang alertmanager 钉钉告警推送
简介：系统字符集统一乱码修复，统一数据库、程序、操作系统字符集，解决中文乱码显示异常问题。
 | 原文链接：http://zhishi.wikcr1.asia/blog/5383343.sHtML

原标题：实战项目：前端资源打包体积优化完整实操
简介：golang 容器健康检查接口开发，Go 开发 HTTP 健康接口，供容器编排工具探测实例存活状态。
 | 原文链接：http://zhishi.wikcr1.asia/blog/8133943.sHtML

原标题：优化实践：接口返回字段裁剪减少报文大小
简介：数据库主从延迟业务兼容处理，业务适配主从复制延迟，避免读取从库拿到还未同步完成旧数据。
 | 原文链接：http://zhishi.wikcr1.asia/blog/1849791.sHtML

原标题：安全实践：API密钥管理轮换最佳实践
简介：golang 网卡 ip 读取网络信息获取，程序读取本机网卡 IP，多网卡环境筛选业务使用 IP 地址。
 | 原文链接：http://zhishi.wikcr1.asia/blog/0170413.sHtML

原标题：golang docker compose 依赖启动顺序
简介：业务幂等键设计防重复逻辑，讲解幂等键设计思路，选择合适业务字段作为幂等标识，实现可靠防重复。
 | 原文链接：http://zhishi.wikcr1.asia/blog/1069653.sHtML

原标题：开发复盘：实现定时任务调度服务支持动态任务
简介：git rebase 整理提交历史实操，使用 rebase 整理杂乱提交记录，将多条提交合并，保持 git 提交历史干净线性。
 | 原文链接：http://zhishi.wikcr1.asia/blog/6863911.sHtML

原标题：数值类型溢出错乱问题修复
简介：golang time duration 解析时间字符串，time.ParseDuration 解析 1h30m 时间间隔字符串。
 | 原文链接：http://zhishi.wikcr1.asia/blog/7584530.sHtML

原标题：golang 系统设计数据库连接池调优实践
简介：golang go mod 私有 git 仓库配置，配置 go mod 拉取私有仓库代码，处理私有模块依赖拉取问题。
 | 原文链接：http://zhishi.wikcr1.asia/blog/7900565.sHtML

原标题：线上异常：线程池队列拒绝策略配置错误丢任务
简介：golang go mod 私有 git 仓库配置，配置 go mod 拉取私有仓库代码，处理私有模块依赖拉取问题。
 | 原文链接：http://zhishi.wikcr1.asia/blog/8547592.sHtML

原标题：开发记录：分布式ID生成器实现与压力测试
简介：WSL 文件权限访问异常修复，处理 WSL 环境文件权限错乱，调整权限配置，实现文件正常读写访问。
 | 原文链接：http://zhishi.wikcr1.asia/blog/5623021.sHtML

原标题：部署实践：Nginx反向代理传递真实客户端IP
简介：golang channel 作为函数参数方向，声明 channel 入参方向，只读 channel 只写 channel 提升代码约束。
 | 原文链接：http://zhishi.wikcr1.asia/blog/9998983.sHtML

原标题：Hands‑on：简易ID生成雪花算法完整实现
简介：全量回归测试提升代码质量，搭建全量回归测试集，版本发布执行回归测试，避免迭代引入旧 bug。
 | 原文链接：http://zhishi.wikcr1.asia/blog/8585083.sHtML

原标题：前端虚拟列表大数据渲染优化
简介：golang io.MultiReader MultiWriter 拼接流，多个 reader 拼接，多 writer 同时写入一份数据。
 | 原文链接：http://zhishi.wikcr1.asia/blog/8504151.sHtML

原标题：架构笔记：批量任务系统架构防重复、断点续跑
简介：静态博客部署 GitHub Pages 教程，将静态博客项目部署至 GitHub Pages，完成线上访问，快速搭建个人技术博客站点。
 | 原文链接：http://zhishi.wikcr1.asia/blog/8940499.sHtML

原标题：安全复盘：业务接口越权测试与修复实践
简介：文件批量导入导出功能实现，开发批量导入导出接口，处理大量文件数据，完成业务数据批量迁移与导出。
 | 原文链接：http://zhishi.wikcr1.asia/blog/1980391.sHtML

原标题：调优方案：MySQL缓冲池参数性能调优实践
简介：时间同步修复令牌提前过期，服务器时间不同步导致 JWT 令牌提前过期，同步系统时间解决异常。
 | 原文链接：http://zhishi.wikcr1.asia/blog/8065464.sHtML

原标题：Security：服务器最小权限账号运维实践
简介：golang kitex 超时重试熔断配置，kitex 配置调用超时、重试、熔断策略，保障微服务调用稳定性。
 | 原文链接：http://zhishi.wikcr1.asia/blog/5057193.sHtML

四、架构设计｜Architecture
原标题：静态资源 404 路径打包修复
简介：golang k8s 客户端 client‑go 简单示例，client‑go 操作 k8s 资源，增删改查 pod deployment 等资源对象。
 | 原文链接：http://zhishi.wikcr1.asia/blog/7798136.sHtML

原标题：线程调度优化减少上下文切换
简介：golang go mod vendor 本地依赖导出，导出 vendor 目录，离线环境编译项目，无需访问外网拉依赖。
 | 原文链接：http://zhishi.wikcr1.asia/blog/5738752.sHtML

原标题：Performance：JSON序列化性能优化实践
简介：Nginx 丢失请求头配置修正，修复 Nginx 代理转发丢失请求头配置，保证上游服务拿到完整请求头信息。
 | 原文链接：http://zhishi.wikcr1.asia/blog/6798247.sHtML

原标题：分布式 ID 全局唯一生成方案
简介：golang json number 数字不转 float64，使用 json.Number 保留原始数字字符串，防止大数字精度丢失。
 | 原文链接：http://zhishi.wikcr1.asia/blog/8657460.sHtML

原标题：golang 系统设计性能瓶颈定位完整方法论
简介：golang bytes.Buffer 字节缓冲区使用，bytes.Buffer 字节内存缓冲区，拼接字节，避免频繁内存分配。
 | 原文链接：http://zhishi.wikcr1.asia/blog/8689601.sHtML

原标题：调优方案：消息队列消费速度优化处理堆积
简介：golang 多协程任务池并发控制，实现协程任务池，控制并发协程数量，防止无限制创建 goroutine。
 | 原文链接：http://zhishi.wikcr1.asia/blog/9466565.sHtML

原标题：golang 系统设计避免索引失效书写 sql 原则
简介：后端分页查询逻辑代码实现，编写后端分页接口，处理页码、每页条数参数，优化大数据量查询返回结果。
 | 原文链接：http://zhishi.wikcr1.asia/blog/0092486.sHtML

原标题：HelloCI：理解持续集成基础工作流程
简介：golang rsa 公钥加密私钥解密，rsa 非对称加密，大文件分块加密，处理非对称加密长度限制。
 | 原文链接：http://zhishi.wikcr1.asia/blog/2735897.sHtML

原标题：踩坑记录：时间戳精度不一致引发判断错误
简介：后端登录鉴权模块完整开发，实现完整登录模块，包含账号校验、令牌发放、接口鉴权整套能力。
 | 原文链接：http://zhishi.wikcr1.asia/blog/7176974.sHtML

原标题：排错：多实例部署session共享失效登录失效
简介：golang 优雅处理数据库事务，Go 数据库事务封装，正确处理事务提交回滚，保证业务数据一致性。
 | 原文链接：http://zhishi.wikcr1.asia/blog/1817761.sHtML

原标题：GitHub Markdown 文档语法汇总
简介：多套环境灵活切换配置方案，实现配置动态切换，通过环境变量、配置文件，快速切换开发测试生产环境。
 | 原文链接：http://zhishi.wikcr1.asia/blog/6388433.sHtML

原标题：DevOps：CI构建产物缓存复用加速编译
简介：golang go 程序抢占调度理解，理解 go 抢占式调度原理，长循环阻塞调度，造成协程调度延迟。
 | 原文链接：http://zhishi.wikcr1.asia/blog/7149799.sHtML

原标题：不必要字符转义关闭业务异常
简介：golang redis zset 实现延时任务队列，zset 存储任务到期时间，轮询到期任务执行，简易延迟队列。
 | 原文链接：http://zhishi.wikcr1.asia/blog/6354270.sHtML

原标题：golang 系统设计缓存与数据库一致性权衡
简介：golang strings 常用函数业务实战，字符串分割替换包含判断前缀后缀，掌握 strings 包高频函数。
 | 原文链接：http://zhishi.wikcr1.asia/blog/2603899.sHtML

原标题：MySQL 慢查询索引优化实战
简介：内网 DNS 不稳定随机报错排查，定位内网 DNS 抖动问题，配置备选 DNS，解决偶现域名解析失败。
 | 原文链接：http://zhishi.wikcr1.asia/blog/9782460.sHtML

原标题：安全实践：容器最小化镜像减少攻击面
简介：golang context 取消传播机制，父 ctx 取消，所有派生子 context 全部被取消，理解上下文传播。
 | 原文链接：http://zhishi.wikcr1.asia/blog/0369892.sHtML

原标题：实战项目：前端资源打包体积优化完整实操
简介：golang context 包标准用法规范，context 传递请求元数据、超时、取消，函数第一个参数传入 ctx。
 | 原文链接：http://zhishi.wikcr1.asia/blog/7195828.sHtML

原标题：golang zap 日志按日期切割方案
简介：golang gzip 压缩 http 响应，服务端开启 gzip 压缩，减小接口响应体积，降低网络传输耗时。
 | 原文链接：http://zhishi.wikcr1.asia/blog/5167317.sHtML

?
