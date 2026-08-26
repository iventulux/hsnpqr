最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计缓存基准测试对比方案
简介：大事务拆分防止连接池耗尽，将执行时间很长的大事务拆分为小事务，减少事务占用连接时长。
 | 原文链接：http://wiki.huramu.asia/arts/368798.Doc

原标题：CLI 批量处理工具文件操作开发
简介：golang redis scan 遍历 key 避免阻塞，使用 scan 迭代遍历 redis 键，不用 keys 命令，防止阻塞 redis 服务。
 | 原文链接：http://wiki.huramu.asia/arts/596883.Doc

原标题：方案设计：高可用Redis集群架构选型对比
简介：nodejs 事件循环机制完整讲解，拆解 Node.js 事件循环各个阶段，理解异步回调执行顺序。
 | 原文链接：http://wiki.huramu.asia/arts/996762.Doc

原标题：WebSocket 双向通信 demo 开发
简介：开源项目本地运行排错完整清单，汇总开源项目拉取后运行失败各类问题，给出排查思路，快速解决本地启动异常。
 | 原文链接：http://wiki.huramu.asia/arts/043214.Doc

原标题：golang 系统设计开源项目维护简单经验分享
简介：golang validator 自定义校验规则，Gin Validator 自定义校验器，实现业务特殊参数校验逻辑。
 | 原文链接：http://wiki.huramu.asia/arts/554961.Doc

原标题：golang kafka 消费者偏移量管理
简介：系统时间同步定时任务偏移，同步服务器系统时间，防止时间偏移，避免定时任务执行时间错乱。
 | 原文链接：http://wiki.huramu.asia/arts/430798.Doc

原标题：坑点：依赖缓存未更新，旧代码持续运行
简介：文件句柄上限调整上传随机失败，调高系统文件句柄上限，解决高并发上传场景随机打开文件失败。
 | 原文链接：http://wiki.huramu.asia/arts/695816.Doc

原标题：架构笔记：数据库连接池架构参数调优思路
简介：golang io.MultiReader MultiWriter 拼接流，多个 reader 拼接，多 writer 同时写入一份数据。
 | 原文链接：http://wiki.huramu.asia/arts/165439.Doc

原标题：安全复盘：CSRF跨站请求伪造防护配置
简介：golang os 主机名内核版本读取，os 读取主机名，内核信息，操作系统版本，获取运行环境信息。
 | 原文链接：http://wiki.huramu.asia/arts/663554.Doc

原标题：踩坑：数据库连接未关闭，连接池泄露
简介：golang 系统调用跟踪 strace 排查 go 程序，strace 跟踪系统调用，定位文件网络 IO 慢的底层原因。
 | 原文链接：http://wiki.huramu.asia/arts/299025.Doc

原标题：记一次分布式锁失效引发的数据错乱问题
简介：golang multipart 表单文件上传解析，服务端解析 multipart 表单，获取上传文件与表单字段。
 | 原文链接：http://wiki.huramu.asia/arts/479628.Doc

原标题：开发复盘：内存缓存LRU淘汰策略实现实践
简介：golang go 并发模式 errgroup 使用，errgroup 结合 context，协程组，任意协程出错整体取消任务。
 | 原文链接：http://wiki.huramu.asia/arts/337250.Doc

原标题：方案设计：异步解耦业务架构边界识别
简介：golang net.Listener 包装自定义监听器，包装 Listener 做连接计数、连接拦截，扩展网络能力。
 | 原文链接：http://wiki.huramu.asia/arts/035784.Doc

原标题：OpenSource：开源项目README高质量编写指南
简介：nodejs 项目 pm2 部署运维指南，使用 PM2 管理 Node 服务，进程守护、日志、重启，线上部署运维实操。
 | 原文链接：http://wiki.huramu.asia/arts/623424.Doc

原标题：实战：gRPC服务编写客户端服务端完整demo
简介：golang html 模板渲染简单示例，Go HTML 模板渲染，服务端渲染页面，填充数据输出 HTML 页面。
 | 原文链接：http://wiki.huramu.asia/arts/393802.Doc

原标题：golang 系统设计 hot‑reload 热重载 go 开发工具
简介：程序信号中断退出处理逻辑，捕获系统中断信号，执行资源释放、关闭连接，实现程序优雅退出。
 | 原文链接：http://wiki.huramu.asia/arts/229654.Doc

原标题：代码模块化组件化拆分思路
简介：WSL 内存上限限制防止资源耗尽，修改 WSL 内存上限配置，避免 WSL 占用主机大量内存资源。
 | 原文链接：http://wiki.huramu.asia/arts/444546.Doc

原标题：axios 二次封装请求拦截处理
简介：多套环境灵活切换配置方案，实现配置动态切换，通过环境变量、配置文件，快速切换开发测试生产环境。
 | 原文链接：http://wiki.huramu.asia/arts/787615.Doc

原标题：实战项目：实现分布式任务调度最小原型
简介：vue pinia 状态管理实战教程，Pinia 完整实战示例，实现状态定义修改，模块拆分替代 Vuex。
 | 原文链接：http://wiki.huramu.asia/arts/737503.Doc

原标题：排错：前端打包chunk过大浏览器加载缓慢
简介：批量数据处理脚本编写技巧，编写脚本批量处理大量业务数据，循环处理、分批执行，提升数据处理效率。
 | 原文链接：http://wiki.huramu.asia/arts/188021.Doc

原标题：部署实践：容器优雅停机配置处理信号
简介：Nginx 丢失请求头配置修正，修复 Nginx 代理转发丢失请求头配置，保证上游服务拿到完整请求头信息。
 | 原文链接：http://wiki.huramu.asia/arts/293245.Doc

原标题：golang 系统设计熔断算法 hystrix 思路
简介：golang 数据库分表策略按时间分片，按时间维度分表，历史数据拆分，单表数据量控制保证查询性能。
 | 原文链接：http://wiki.huramu.asia/arts/521917.Doc

原标题：Hands‑on：简易反向代理中间件实现
简介：golang excel 简单读写操作示例，Go 实现 Excel 简单读写，业务数据导出 Excel 报表。
 | 原文链接：http://wiki.huramu.asia/arts/230816.Doc

原标题：DevOps：Docker镜像安全扫描集成CI流程
简介：HTTP 状态码请求头完整梳理，汇总常用 HTTP 状态码与请求头含义，帮助快速看懂网络请求，排查接口通信问题。
 | 原文链接：http://wiki.huramu.asia/arts/299115.Doc

原标题：golang 系统设计短链接服务实现思路
简介：golang go 接口定义原则小接口，go 小接口设计原则，接口尽量小，只定义必要方法，提升代码灵活性。
 | 原文链接：http://wiki.huramu.asia/arts/118069.Doc

原标题：golang 系统设计大事务拆分实战思路
简介：API 大版本不兼容平滑迁移，API 版本迭代不兼容旧接口，设计平滑迁移方案，逐步完成版本切换。
 | 原文链接：http://wiki.huramu.asia/arts/921587.Doc

原标题：golang excel 简单读写操作示例
简介：golang consul 服务发现简单示例，对接 Consul 实现服务注册发现，微服务实例自动感知。
 | 原文链接：http://wiki.huramu.asia/arts/920814.Doc

原标题：golang redis zset 延时队列实现
简介：golang 错误栈捕获打印方案，捕获错误完整调用堆栈，线上日志输出堆栈，快速定位错误发生代码位置。
 | 原文链接：http://wiki.huramu.asia/arts/774960.Doc

原标题：CI 构建缓存加速编译速度
简介：golang go 输入数据校验防御，所有外部入参严格校验长度格式，防止恶意输入造成业务异常。
 | 原文链接：http://wiki.huramu.asia/arts/095076.Doc

原标题：WebSocket 断线重连稳定优化
简介：golang sftp 文件上传下载操作，sftp 协议远程文件上传下载，实现服务器之间文件传输功能。
 | 原文链接：http://wiki.huramu.asia/arts/946834.Doc

原标题：golang 系统设计数据库表设计通用规范模板
简介：golang go 基准测试 benchmark 编写，Benchmark 性能基准测试，测量函数执行耗时内存分配情况。
 | 原文链接：http://wiki.huramu.asia/arts/714636.Doc

原标题：设计思考：消息队列重复消费架构层防御手段
简介：前后端会话登录状态持久化，实现登录状态持久存储，重启服务登录状态不丢失，保障会话稳定性。
 | 原文链接：http://wiki.huramu.asia/arts/489347.Doc

原标题：golang 系统设计故障演练简单思路
简介：golang e2e 端到端测试 go 接口，编写 e2e 测试，完整模拟用户请求，校验整套业务链路正确性。
 | 原文链接：http://wiki.huramu.asia/arts/733776.Doc

原标题：golang 数据库批量更新性能优化
简介：API 大版本不兼容平滑迁移，API 版本迭代不兼容旧接口，设计平滑迁移方案，逐步完成版本切换。
 | 原文链接：http://wiki.huramu.asia/arts/194059.Doc

原标题：性能复盘：消息队列大量小消息性能问题优化
简介：golang gorm group by 分组统计，GORM 分组聚合统计，实现 count sum 等统计查询，快速完成统计业务。
 | 原文链接：http://wiki.huramu.asia/arts/886333.Doc

原标题：实践：API接口文档自动导出离线文档实践
简介：WebSocket 聊天室实时通讯开发，基于 WebSocket 搭建简易聊天室，实现多人消息广播实时聊天效果。
 | 原文链接：http://wiki.huramu.asia/arts/459248.Doc

原标题：golang 系统设计创建更新时间自动维护方案
简介：golang go mod exclude 排除依赖版本，exclude 排除有问题依赖版本，规避有 bug 的第三方包。
 | 原文链接：http://wiki.huramu.asia/arts/179098.Doc

原标题：golang redis 布隆过滤器安装使用
简介：golang 图片处理 go 图片裁剪压缩，golang 图像处理库，图片缩放裁剪水印，服务端图片处理。
 | 原文链接：http://wiki.huramu.asia/arts/455021.Doc

原标题：主干开发团队代码合并策略
简介：golang recover 捕获 panic 使用边界，recover 只在 defer 内部生效，协程内部必须捕获本协程 panic。
 | 原文链接：http://wiki.huramu.asia/arts/045014.Doc

原标题：实战：WebSocket断线重连完整业务处理实践
简介：golang channel 作为函数参数方向，声明 channel 入参方向，只读 channel 只写 channel 提升代码约束。
 | 原文链接：http://wiki.huramu.asia/arts/366821.Doc


二、踩坑排错｜Troubleshooting
原标题：调优方案：数据库索引不要过度建立，权衡写性能
简介：golang 漏桶算法实现接口限流，漏桶算法控制请求流出速率，平滑突发流量，削平流量峰值。
 | 原文链接：http://wiki.huramu.asia/arts/310940.Doc

原标题：代码格式化工具团队统一风格
简介：golang 容器内读取 k8s 配置 configmap，程序读取 k8s configmap 配置，配置与镜像分离便于运维。
 | 原文链接：http://wiki.huramu.asia/arts/904643.Doc

原标题：Architecture：静态配置与动态配置架构分离
简介：nodejs 定时任务生产环境避坑，Node 定时任务线上踩坑汇总，集群重复执行、任务阻塞等问题解决方案。
 | 原文链接：http://wiki.huramu.asia/arts/452869.Doc

原标题：开发记录：短信发送服务封装，失败重试策略
简介：golang minio 私有对象存储开发，minio s3 对象存储，bucket 管理，文件上传下载权限设置。
 | 原文链接：http://wiki.huramu.asia/arts/851806.Doc

原标题：Nginx 丢失请求头配置修正
简介：golang jwt jwk 公钥验证令牌，使用 jwk 公钥校验 jwt，非对称方式签发校验令牌，提升安全性。
 | 原文链接：http://wiki.huramu.asia/arts/319466.Doc

原标题：golang defer panic 异常处理
简介：golang 容器时区设置镜像构建处理，镜像内部设置正确时区，解决容器时间与宿主机不一致。
 | 原文链接：http://wiki.huramu.asia/arts/603081.Doc

原标题：nodejs 多进程任务分发处理
简介：golang 命令行彩色输出终端，终端彩色文字输出，进度条交互，优化命令行工具用户体验。
 | 原文链接：http://wiki.huramu.asia/arts/844232.Doc

原标题：方案设计：分布式分页查询架构难点处理
简介：golang init 函数合理使用边界，少用 init，优先显式调用初始化，便于控制初始化时机。
 | 原文链接：http://wiki.huramu.asia/arts/970213.Doc

原标题：实践：Git工作流主干开发团队协作实践
简介：golang go 线上故障排查完整流程，CPU 高、内存上涨、接口超时、goroutine 泄露一套排查处理流程。
 | 原文链接：http://wiki.huramu.asia/arts/377243.Doc

原标题：Hands‑on：简易网关路由转发组件开发
简介：golang time 时间比较 Before After Equal，时间比较不要直接减，使用内置方法判断时间先后。
 | 原文链接：http://wiki.huramu.asia/arts/747256.Doc

原标题：端口占用访问失败排查方案
简介：golang channel 缓冲无缓冲区别，缓冲 channel 与无缓冲 channel，底层行为差异业务选型参考。
 | 原文链接：http://wiki.huramu.asia/arts/767586.Doc

原标题：实践：前后端分离项目登录状态保持完整方案
简介：golang os 环境变量读取设置，os.Getenv os.Setenv os.Unsetenv 读写环境变量，环境变量多值处理。
 | 原文链接：http://wiki.huramu.asia/arts/196695.Doc

原标题：效率笔记：VSCode插件集合后端前端开发效率
简介：golang grpc protobuf 开发实操，Go gRPC 开发，编写 Protobuf 定义，服务端客户端完整示例。
 | 原文链接：http://wiki.huramu.asia/arts/539530.Doc

原标题：Performance：后端接口性能优化完整分析流程
简介：golang http.Server 配置参数详解，ReadTimeout WriteTimeout IdleTimeout，全方位防护慢请求攻击。
 | 原文链接：http://wiki.huramu.asia/arts/147969.Doc

原标题：Troubleshooting：数据库索引失效，查询性能暴跌
简介：golang redis 过期键监听回调，监听 key 过期事件，过期触发业务逻辑，实现过期自动处理业务场景。
 | 原文链接：http://wiki.huramu.asia/arts/148491.Doc

原标题：Docker 多阶段构建镜像瘦身
简介：golang go 基准测试 benchmark 编写，Benchmark 性能基准测试，测量函数执行耗时内存分配情况。
 | 原文链接：http://wiki.huramu.asia/arts/934087.Doc

原标题：坑点：Docker资源限制未设置导致宿主机卡死
简介：业务幂等键设计防重复逻辑，讲解幂等键设计思路，选择合适业务字段作为幂等标识，实现可靠防重复。
 | 原文链接：http://wiki.huramu.asia/arts/229000.Doc

原标题：golang 系统设计密码存储哈希加盐实现
简介：golang aes cbc gcm 模式加密对比，AES‑CBC AES‑GCM 模式加密解密，理解两种模式差异选型。
 | 原文链接：http://wiki.huramu.asia/arts/633062.Doc

原标题：前后端交互跨域问题完整处理
简介：跨平台换行符统一异常修复，统一代码文件换行符，解决不同操作系统换行符不一致带来脚本执行异常。
 | 原文链接：http://wiki.huramu.asia/arts/815217.Doc

原标题：Hands‑on：实现WebSocket聊天室完整前后端demo
简介：文件描述符优化进程卡死修复，及时关闭文件句柄，控制打开文件数量，解决文件句柄耗尽进程卡死。
 | 原文链接：http://wiki.huramu.asia/arts/682383.Doc

原标题：项目实践：定时任务防重复执行落地实践
简介：golang time.Ticker 泄漏常见场景，忘记 Stop Ticker，导致协程泄漏，定时器资源无法释放。
 | 原文链接：http://wiki.huramu.asia/arts/369172.Doc

原标题：nodejs 日志轮转生产环境配置
简介：golang go yaml 解析自定义类型，yaml 自定义序列化，时间、特殊类型自定义解析逻辑。
 | 原文链接：http://wiki.huramu.asia/arts/720254.Doc

原标题：代码模块化组件化拆分思路
简介：golang proto 可选字段处理方案，protobuf 可选字段正确判断，区分未赋值与零值，业务逻辑不出现偏差。
 | 原文链接：http://wiki.huramu.asia/arts/959214.Doc

原标题：复盘总结：技术选型对比文档模板实践
简介：golang redis pipeline 批量操作，使用 Redis Pipeline 批量执行多条命令，减少网络往返，提升批量操作性能。
 | 原文链接：http://wiki.huramu.asia/arts/804832.Doc

原标题：架构复盘：供应链安全架构依赖包风险治理
简介：Git 误删提交代码恢复找回，使用 Git reflog 工具找回被误删除提交记录，恢复误删除代码。
 | 原文链接：http://wiki.huramu.asia/arts/587198.Doc

原标题：golang k8s secret 加密敏感信息
简介：golang rsa 签名验签 pem 证书加载，加载 pem 格式密钥证书，rsa 签名与验签完整业务实现。
 | 原文链接：http://wiki.huramu.asia/arts/371187.Doc

原标题：OpenSource：开源项目README高质量编写指南
简介：Docker 容器入门镜像实操教程，介绍 Docker 基础概念，演示镜像拉取、容器启停，帮助新手建立容器化开发认知。
 | 原文链接：http://wiki.huramu.asia/arts/772505.Doc

原标题：Debug：表单提交特殊字符造成接口解析失败
简介：rebase 操作防止代码丢失，讲解 rebase 风险点，操作前做好备份，规避错误操作造成代码提交丢失。
 | 原文链接：http://wiki.huramu.asia/arts/711062.Doc

原标题：Architecture：API设计RESTful最佳实践与反模式
简介：golang viper 多源配置管理实操，viper 读取配置文件环境变量命令行参数，多源配置优先级管理。
 | 原文链接：http://wiki.huramu.asia/arts/799543.Doc

原标题：编译打包产物依赖分析解读
简介：请求重试组件退避策略实现，封装重试组件，实现指数退避策略，避免大量请求同时重试压垮下游。
 | 原文链接：http://wiki.huramu.asia/arts/332059.Doc

原标题：快速入门OpenAPI文档生成基础实践
简介：golang 子进程超时杀死防止挂住，context 控制子进程超时，超时强制杀掉子进程，避免子进程僵尸。
 | 原文链接：http://wiki.huramu.asia/arts/169506.Doc

原标题：golang prometheus 告警规则编写
简介：Cookie 跨环境登录配置调整，调整 Cookie 域、Secure 属性，适配开发测试生产环境，修复登录失效。
 | 原文链接：http://wiki.huramu.asia/arts/641058.Doc

原标题：golang 结构体 json 序列化坑点
简介：axios 二次封装请求拦截处理，对 axios 做二次封装，统一请求拦截响应拦截，处理错误、token 自动刷新。
 | 原文链接：http://wiki.huramu.asia/arts/488781.Doc

原标题：golang 系统设计日志采样降低存储开销方案
简介：nodejs 接口限流防刷代码实现，Node 层实现接口限流，限制 IP 访问频次，防护接口被恶意高频调用。
 | 原文链接：http://wiki.huramu.asia/arts/009157.Doc

原标题：Practice：实现定时任务动态启停管理接口
简介：golang go 网络编程 net 包基础，net 包 tcp udp socket 编程，监听接收连接，读写数据。
 | 原文链接：http://wiki.huramu.asia/arts/709606.Doc

原标题：坑点：gitrebase操作失误，代码提交丢失
简介：golang 路径处理 filepath 包规范写法，使用 filepath 处理路径拼接分割，自动适配操作系统路径分隔符。
 | 原文链接：http://wiki.huramu.asia/arts/316554.Doc

原标题：golang gitlab runner 部署与注册实操
简介：golang 容器 OOM 被杀死排查区分，区分业务内存泄漏、容器限制过小，定位容器 OOMKilled 原因。
 | 原文链接：http://wiki.huramu.asia/arts/656454.Doc

原标题：golang 系统设计 ci 流水线安全管控思路
简介：golang websocket 服务端开发，Go 实现 WebSocket 服务端，处理连接、消息收发，实现长连接服务。
 | 原文链接：http://wiki.huramu.asia/arts/041451.Doc

原标题：css 动画性能优化 GPU 加速
简介：golang context.Background 与 TODO 区别，Background 主流程根上下文，TODO 不确定用哪个上下文时使用。
 | 原文链接：http://wiki.huramu.asia/arts/638016.Doc

原标题：OpenSource：如何高效阅读大型开源项目源码
简介：多实例部署 Session 共享方案，多服务实例部署场景，实现 Session 共享，保证用户登录状态跨实例生效。
 | 原文链接：http://wiki.huramu.asia/arts/044648.Doc

三、实战开发｜Practice
原标题：golang 系统设计 tcp 粘包拆包处理方案实现
简介：golang 互斥锁读写锁并发安全，互斥锁读写锁实操，保护共享变量，解决多协程并发读写数据竞争。
 | 原文链接：http://wiki.huramu.asia/arts/900944.Doc

原标题：GC 垃圾回收优化降低 CPU 占用
简介：golang defer panic 异常处理，理解 defer 延迟执行，panic 恐慌捕获，实现函数资源释放异常保护。
 | 原文链接：http://wiki.huramu.asia/arts/411130.Doc

原标题：golang 系统设计定时任务失败重试告警实现
简介：配置外部化线上部署防错误，把配置从代码剥离，外部传入配置，修改配置不需要重新打包构建。
 | 原文链接：http://wiki.huramu.asia/arts/815184.Doc

原标题：开发记录：表单参数校验统一中间件实现
简介：golang sort 切片排序自定义 less，sort.Slice 切片快速排序，自定义 less 函数实现业务排序。
 | 原文链接：http://wiki.huramu.asia/arts/968613.Doc

原标题：效率笔记：批量处理文本命令行工具实战案例
简介：golang 分库分表 id 路由规则设计，分库分表 id 路由算法，id 映射库表，数据均匀打散避免热点分片。
 | 原文链接：http://wiki.huramu.asia/arts/716549.Doc

原标题：开源实践：给开源项目写单元测试贡献代码
简介：GC 垃圾回收优化降低 CPU 占用，调整 GC 参数，优化对象创建销毁，降低垃圾回收带来 CPU 开销。
 | 原文链接：http://wiki.huramu.asia/arts/605711.Doc

原标题：golang k8s secret 加密敏感信息
简介：golang 时间时区处理避坑指南，Go 时间时区常见坑，时区转换，时间比较，规避时间逻辑错误。
 | 原文链接：http://wiki.huramu.asia/arts/985160.Doc

原标题：Performance：数据库join优化，大表join规避
简介：golang 项目 go mod 依赖管理，Go Mod 管理项目依赖，下载、升级、清理依赖，解决依赖版本管理。
 | 原文链接：http://wiki.huramu.asia/arts/598380.Doc

原标题：golang 系统设计布隆过滤器原理与落地
简介：golang 命令行参数解析开发，解析命令行入参，开发自定义 CLI 程序，读取启动参数配置服务。
 | 原文链接：http://wiki.huramu.asia/arts/304673.Doc

原标题：架构笔记：分布式事务方案对比与业务取舍
简介：golang grpc 客户端流上传数据，客户端流式请求，客户端分批上传数据到服务端，适合大文件传输。
 | 原文链接：http://wiki.huramu.asia/arts/569144.Doc

原标题：零基础理解HTTP常用请求头与状态码
简介：浏览器内存泄漏排查前端页面，梳理前端页面内存泄漏场景，讲解排查手段，修复页面内存持续上涨。
 | 原文链接：http://wiki.huramu.asia/arts/125175.Doc

原标题：安全实践：容器最小化镜像减少攻击面
简介：golang 分页查询封装通用工具，封装 Go 通用分页工具，统一处理分页参数，简化业务分页接口开发。
 | 原文链接：http://wiki.huramu.asia/arts/218058.Doc

原标题：GitHub Markdown 文档语法汇总
简介：异步任务堆积消费能力优化，处理消息任务堆积问题，提升消费处理速度，恢复队列正常处理水位。
 | 原文链接：http://wiki.huramu.asia/arts/858480.Doc

原标题：实践：API接口文档自动导出离线文档实践
简介：golang staticcheck 静态代码分析，staticcheck 深度静态检查，发现代码错误、性能问题、风格问题。
 | 原文链接：http://wiki.huramu.asia/arts/661481.Doc

原标题：坑点：缓存穿透，大量无效请求打穿数据库
简介：golang redis pipeline 与 txpipeline 区别，区分普通管道与事务管道，根据业务场景选择合适批量执行方案。
 | 原文链接：http://wiki.huramu.asia/arts/678054.Doc

原标题：Practice：JWT工具封装，刷新令牌完整逻辑
简介：golang go 优雅处理信号丢失场景，处理信号丢失、信号被忽略，保障程序可以正常接收终止信号。
 | 原文链接：http://wiki.huramu.asia/arts/269982.Doc

原标题：开发复盘：大列表内存分批读取避免OOM实践
简介：golang defer 执行顺序与坑点，defer 后进先出，循环内部 defer 陷阱，资源释放正确写法。
 | 原文链接：http://wiki.huramu.asia/arts/771913.Doc

原标题：golang 系统设计单元测试表驱动测试 table‑driven
简介：golang 错误处理最佳实践汇总，Go 错误处理规范，包装错误，堆栈携带，拒绝简单忽略错误。
 | 原文链接：http://wiki.huramu.asia/arts/314618.Doc

原标题：坑点：缓存过期策略不当引发业务异常
简介：项目依赖安全扫描漏洞防范，扫描项目第三方依赖包，修复存在安全漏洞依赖，防范供应链攻击。
 | 原文链接：http://wiki.huramu.asia/arts/522187.Doc

原标题：golang 系统设计 id 生成器选型对比
简介：golang minio 私有对象存储开发，minio s3 对象存储，bucket 管理，文件上传下载权限设置。
 | 原文链接：http://wiki.huramu.asia/arts/646943.Doc

原标题：提交第一个开源 PR 完整流程
简介：HTTP 状态码请求头完整梳理，汇总常用 HTTP 状态码与请求头含义，帮助快速看懂网络请求，排查接口通信问题。
 | 原文链接：http://wiki.huramu.asia/arts/133667.Doc

原标题：正则表达式优化 CPU 占满问题
简介：golang channel 作为函数参数方向，声明 channel 入参方向，只读 channel 只写 channel 提升代码约束。
 | 原文链接：http://wiki.huramu.asia/arts/931879.Doc

原标题：golang 系统设计缓存优化落地实操指南
简介：golang 数据库连接耗尽排查思路，监控连接池状态，定位连接未归还，解决连接耗尽报错。
 | 原文链接：http://wiki.huramu.asia/arts/824315.Doc

原标题：Practice：模拟磁盘满，验证服务降级表现
简介：前端骨架屏提升页面体验，实现页面骨架屏，数据未加载完成展示占位，优化页面白屏感知体验。
 | 原文链接：http://wiki.huramu.asia/arts/922516.Doc

原标题：静态博客部署 GitHub Pages 教程
简介：golang os 打开文件 O_APPEND O_CREATE 标志，OpenFile 标志位，控制文件创建追加截断行为。
 | 原文链接：http://wiki.huramu.asia/arts/767934.Doc

原标题：业务错误码体系设计方案
简介：golang 压缩 zip 文件生成解压，golang 实现 zip 压缩打包，解压 zip 归档文件，处理批量文件归档。
 | 原文链接：http://wiki.huramu.asia/arts/292322.Doc

原标题：静态网页 HTML CSS 快速入门实战
简介：golang 开发环境快速搭建指南，快速完成 Golang 开发环境配置，工具链安装，环境变量设置，准备开发。
 | 原文链接：http://wiki.huramu.asia/arts/414153.Doc

原标题：实践：前后端时间格式统一规范落地实践
简介：Nginx 透传真实客户端 IP 配置，配置 Nginx 把真实客户端 IP 传递后端服务，后端拿到访问者真实 IP。
 | 原文链接：http://wiki.huramu.asia/arts/855367.Doc

原标题：数值 key 浮点匹配异常规避
简介：golang http 重定向策略自定义，CheckRedirect 自定义重定向逻辑，限制重定向次数，防止死循环。
 | 原文链接：http://wiki.huramu.asia/arts/721282.Doc

原标题：golang redis 热点 key 业务规避
简介：golang 时间戳秒毫秒纳秒转换，Unix UnixMilli UnixNano 互相转换，区分单位避免时间逻辑 bug。
 | 原文链接：http://wiki.huramu.asia/arts/517245.Doc

原标题：后端登录鉴权模块完整开发
简介：golang defer 闭包变量捕获坑，defer 捕获循环变量引用，变量被复写，理解闭包变量捕获规则。
 | 原文链接：http://wiki.huramu.asia/arts/229812.Doc

原标题：浏览器本地存储安全使用技巧
简介：golang time.Ticker 泄漏常见场景，忘记 Stop Ticker，导致协程泄漏，定时器资源无法释放。
 | 原文链接：http://wiki.huramu.asia/arts/260354.Doc

原标题：CI 持续集成自动构建流程
简介：golang testify mock 模拟接口，mock 接口生成 mock 对象，单元测试模拟外部依赖行为。
 | 原文链接：http://wiki.huramu.asia/arts/848436.Doc

原标题：golang 系统设计定时任务调度时间校准要点
简介：service‑worker 离线缓存实践，使用 ServiceWorker 实现静态资源离线缓存，弱网环境页面依然可访问。
 | 原文链接：http://wiki.huramu.asia/arts/587218.Doc

原标题：golang redis 缓存雪崩完整处理
简介：service‑worker 离线缓存实践，使用 ServiceWorker 实现静态资源离线缓存，弱网环境页面依然可访问。
 | 原文链接：http://wiki.huramu.asia/arts/425955.Doc

原标题：golang 系统设计分布式锁红锁优缺点梳理
简介：golang tcp 四次挥手 go 程序行为，理解 tcp 四次挥手，处理连接关闭、重置、RST 包异常场景。
 | 原文链接：http://wiki.huramu.asia/arts/692327.Doc

原标题：echarts 大数据渲染性能调优
简介：golang redis pipeline 批量操作，使用 Redis Pipeline 批量执行多条命令，减少网络往返，提升批量操作性能。
 | 原文链接：http://wiki.huramu.asia/arts/290471.Doc

原标题：golang 系统设计覆盖索引减少回表查询实现
简介：golang snowflake 时钟回拨解决方案，雪花算法处理时钟回拨，防止生成重复 ID，保证 ID 全局唯一。
 | 原文链接：http://wiki.huramu.asia/arts/881626.Doc

原标题：golang 分布式 ID 雪花算法实现
简介：golang rabbitmq go 客户端生产消费，streadway/amqp 实现 rabbitmq 生产者消费者，队列交换机绑定。
 | 原文链接：http://wiki.huramu.asia/arts/110771.Doc

原标题：安全复盘：CSRF跨站请求伪造防护配置
简介：golang dns 自定义解析器实现，自定义 dns 解析，指定 dns 服务器，控制域名解析逻辑，适配内网环境。
 | 原文链接：http://wiki.huramu.asia/arts/625362.Doc

四、架构设计｜Architecture
原标题：项目实践：实现统一接口返回封装与全局异常处理
简介：golang word 文档生成处理 go 方案，go 生成 word 文档报表，填充文本表格，输出 docx 文件。
 | 原文链接：http://wiki.huramu.asia/arts/144746.Doc

原标题：golang 系统设计定时任务执行超时中断防护
简介：请求工具封装统一异常处理，对网络请求做二次封装，统一捕获各类请求异常，标准化接口返回格式。
 | 原文链接：http://wiki.huramu.asia/arts/407540.Doc

原标题：记一次第三方SDK版本兼容引发线上故障
简介：代码模块化组件化拆分思路，讲解代码拆分原则，将大业务拆分为独立模块组件，提升代码复用与维护能力。
 | 原文链接：http://wiki.huramu.asia/arts/338350.Doc

原标题：golang 日志与链路 ID 关联打印
简介：数据库连接池参数调优，调整连接池最大最小连接数，空闲超时，避免连接耗尽或者资源浪费。
 | 原文链接：http://wiki.huramu.asia/arts/834848.Doc

原标题：axios 二次封装请求拦截处理
简介：Nginx 丢失请求头配置修正，修复 Nginx 代理转发丢失请求头配置，保证上游服务拿到完整请求头信息。
 | 原文链接：http://wiki.huramu.asia/arts/184559.Doc

原标题：入门实践：简单的请求封装与异常捕获
简介：golang 分布式锁防死锁实现要点，锁超时、续期、锁持有者校验，避免锁死锁，保障分布式锁可靠性。
 | 原文链接：http://wiki.huramu.asia/arts/754279.Doc

原标题：Troubleshooting：代理环境下证书校验失败HTTPS报错
简介：golang grpc 客户端流上传数据，客户端流式请求，客户端分批上传数据到服务端，适合大文件传输。
 | 原文链接：http://wiki.huramu.asia/arts/951353.Doc

原标题：golang mysql exists in 性能对比
简介：golang go mod tidy 依赖清理，go mod tidy 自动增删依赖，整理 go.mod go.sum 文件。
 | 原文链接：http://wiki.huramu.asia/arts/481987.Doc

原标题：性能复盘：热点key导致RedisCPU飙升优化
简介：分布式任务调度集群原型开发，开发简易分布式调度原型，集群多节点运行，保证任务只执行一次。
 | 原文链接：http://wiki.huramu.asia/arts/058024.Doc

原标题：golang gin 框架接口开发实战
简介：golang 网卡 ip 读取网络信息获取，程序读取本机网卡 IP，多网卡环境筛选业务使用 IP 地址。
 | 原文链接：http://wiki.huramu.asia/arts/465994.Doc

原标题：golang 系统设计内部 rpc 接口设计原则梳理
简介：golang goreleaser 自动版本发布打包，goreleaser 自动化打包发布，生成多平台二进制归档文件。
 | 原文链接：http://wiki.huramu.asia/arts/462060.Doc

原标题：golang rate‑limiter 限流组件
简介：golang sync.Pool 对象池复用对象，sync.Pool 复用临时对象，减少内存分配，降低 GC 频率提升性能。
 | 原文链接：http://wiki.huramu.asia/arts/962543.Doc

原标题：golang 系统设计 span 埋点业务代码最小侵入思路
简介：golang json number 数字不转 float64，使用 json.Number 保留原始数字字符串，防止大数字精度丢失。
 | 原文链接：http://wiki.huramu.asia/arts/076035.Doc

原标题：快速上手搭建简易内网测试服务
简介：跨库查询性能优化处理，减少跨库关联查询，做数据冗余或者中间表，规避跨库查询性能低下。
 | 原文链接：http://wiki.huramu.asia/arts/172779.Doc

原标题：缓存基础原理与简单代码实现
简介：golang aes 对称加密解密示例，AES 对称加密解密实现，业务敏感数据加密存储传输。
 | 原文链接：http://wiki.huramu.asia/arts/003842.Doc

原标题：golang redis 五种数据结构实战
简介：golang hertz http 框架快速上手，hertz 高性能 http 框架，路由中间件参数校验快速开发接口服务。
 | 原文链接：http://wiki.huramu.asia/arts/906101.Doc

原标题：架构复盘：网关层、应用层、数据库层层限流架构
简介：golang context 超时取消实战案例，使用 context 控制协程、http 请求超时，自动终止超时任务，避免协程无限阻塞。
 | 原文链接：http://wiki.huramu.asia/arts/858058.Doc

原标题：安全实践：备份文件访问权限安全管控
简介：golang strings 常用函数业务实战，字符串分割替换包含判断前缀后缀，掌握 strings 包高频函数。
 | 原文链接：http://wiki.huramu.asia/arts/921012.Doc

?
