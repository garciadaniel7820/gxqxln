最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计接口不兼容平滑迁移方案
简介：日志切割配置防止日志丢失，配置日志切割轮转策略，日志按大小时间切割，防止日志文件丢失。
 | 原文链接：http://wiki.ule6cu.asia/arts/568151.Doc

原标题：Practice：实现接口签名、验签完整示例代码
简介：golang bytes.Buffer 字节缓冲区使用，bytes.Buffer 字节内存缓冲区，拼接字节，避免频繁内存分配。
 | 原文链接：http://wiki.ule6cu.asia/arts/885282.Doc

原标题：分布式 ID 生成器高并发实现
简介：golang bufio 缓冲读写性能优化，bufio 带缓冲读写，减少系统调用，提升文件网络 IO 性能。
 | 原文链接：http://wiki.ule6cu.asia/arts/808290.Doc

原标题：优化实践：预加载与懒加载业务场景取舍
简介：golang excel 生成导出高性能方案，excelize 流式生成 excel，百万行数据导出，规避内存溢出。
 | 原文链接：http://wiki.ule6cu.asia/arts/578328.Doc

原标题：golang redis 过期策略内存淘汰
简介：golang go 初始化顺序包变量 init 函数，包级变量初始化，init 执行顺序，理解包加载执行流程。
 | 原文链接：http://wiki.ule6cu.asia/arts/544849.Doc

原标题：golang 系统设计数据库查询优化完整流程
简介：golang 分布式 ID 雪花算法实现，Go 实现雪花算法，生成分布式全局唯一 ID，适配分库分表主键。
 | 原文链接：http://wiki.ule6cu.asia/arts/182285.Doc

原标题：Redis 大 key 拆分集群卡顿解决
简介：重复提交幂等防护再次讲解，梳理前端重复点击、网络重试场景，落地接口幂等，杜绝重复业务。
 | 原文链接：http://wiki.ule6cu.asia/arts/098074.Doc

原标题：灰度发布策略服务平滑升级
简介：golang http 中间件洋葱模型原理，理解 go http 中间件洋葱模型，请求响应流转顺序，编写自定义中间件。
 | 原文链接：http://wiki.ule6cu.asia/arts/012160.Doc

原标题：系统文件描述符上限调大
简介：golang time.After 内存泄漏场景，for 循环使用 time.After 会创建大量 timer，造成内存泄漏。
 | 原文链接：http://wiki.ule6cu.asia/arts/682637.Doc

原标题：SDK 版本兼容线上崩溃修复
简介：GC 垃圾回收优化降低 CPU 占用，调整 GC 参数，优化对象创建销毁，降低垃圾回收带来 CPU 开销。
 | 原文链接：http://wiki.ule6cu.asia/arts/588874.Doc

原标题：安全复盘：定时任务权限过大风险管控
简介：轻量 API 后端接口服务快速开发，快速搭建简易 API 服务，实现基础接口能力，快速支撑小型业务需求。
 | 原文链接：http://wiki.ule6cu.asia/arts/181262.Doc

原标题：效率笔记：终端开发工具提升日常调试效率
简介：分布式事务最终一致性实现，基于可靠消息实现最终一致性，解决跨数据库跨服务业务数据一致性。
 | 原文链接：http://wiki.ule6cu.asia/arts/049099.Doc

原标题：序列化版本不一致解析失败
简介：代码模块化组件化拆分思路，讲解代码拆分原则，将大业务拆分为独立模块组件，提升代码复用与维护能力。
 | 原文链接：http://wiki.ule6cu.asia/arts/957259.Doc

原标题：Debug：Websocket频繁断开重连根因分析
简介：浏览器内存泄漏排查前端页面，梳理前端页面内存泄漏场景，讲解排查手段，修复页面内存持续上涨。
 | 原文链接：http://wiki.ule6cu.asia/arts/554404.Doc

原标题：实战：单元测试+集成测试完整项目落地实践
简介：golang context.WithCancel 手动取消上下文，WithCancel 生成可取消 ctx，手动调用 cancel 触发取消。
 | 原文链接：http://wiki.ule6cu.asia/arts/492504.Doc

原标题：运维笔记：系统文件句柄数调整生产配置
简介：golang arp 缓存读取操作，读取系统 arp 缓存表，获取 ip 对应的 mac 地址信息。
 | 原文链接：http://wiki.ule6cu.asia/arts/197601.Doc

原标题：golang 系统设计 tcc 事务简单原理业务示例
简介：golang 云存储 s3 协议对象存储，go s3 客户端，兼容 minio 阿里云 oss，实现文件上传下载签名访问。
 | 原文链接：http://wiki.ule6cu.asia/arts/995748.Doc

原标题：golang 系统设计开源项目维护简单经验分享
简介：golang 数据库连接池参数调优详解，最大连接空闲连接最大生命周期，结合业务合理配置避免资源浪费。
 | 原文链接：http://wiki.ule6cu.asia/arts/642862.Doc

原标题：Redis 大 key 拆分集群卡顿解决
简介：golang kitex 中间件与元数据传递，kitex 自定义中间件，透传 traceId 鉴权元数据，统一处理请求。
 | 原文链接：http://wiki.ule6cu.asia/arts/986723.Doc

原标题：golang 系统设计技术文档编写最佳实践
简介：golang go 二进制安全 strip 减小体积，strip 剥离二进制调试符号，缩小程序二进制文件体积。
 | 原文链接：http://wiki.ule6cu.asia/arts/560991.Doc

原标题：快速入门消息通知简单实现方案
简介：express 请求参数校验处理，接入参数校验库，校验入参，拦截非法参数，提前拦截错误请求。
 | 原文链接：http://wiki.ule6cu.asia/arts/825100.Doc

原标题：golang 系统设计日志系统架构思路
简介：golang 系统信号信号量处理，Go 处理系统各类信号，SIGINT、SIGTERM，实现程序可控退出。
 | 原文链接：http://wiki.ule6cu.asia/arts/500563.Doc

原标题：golang etcd 租约 lease 过期机制
简介：接口限流逻辑简单模拟实现，编写简易限流逻辑，限制接口访问频次，保护服务，避免短时间大量请求压垮系统。
 | 原文链接：http://wiki.ule6cu.asia/arts/019095.Doc

原标题：HelloShell：入门常用shell脚本编写
简介：跨平台换行符统一异常修复，统一代码文件换行符，解决不同操作系统换行符不一致带来脚本执行异常。
 | 原文链接：http://wiki.ule6cu.asia/arts/648183.Doc

原标题：vite 插件开发自定义构建逻辑
简介：golang go http 文件服务器自定义，http.FileServer 自定义 FileSystem，拦截访问，增加鉴权逻辑。
 | 原文链接：http://wiki.ule6cu.asia/arts/560991.Doc

原标题：golang 系统设计接口不兼容平滑迁移方案
简介：golang 单例模式实现几种方式，Go 单例模式多种实现对比，sync.Once 等方式，实现全局唯一实例。
 | 原文链接：http://wiki.ule6cu.asia/arts/129107.Doc

原标题：实践：实现Redis分布式锁完整可运行代码
简介：golang go mod vendor 本地依赖导出，导出 vendor 目录，离线环境编译项目，无需访问外网拉依赖。
 | 原文链接：http://wiki.ule6cu.asia/arts/866239.Doc

原标题：实战：搭建日志收集分析简易完整演示环境
简介：golang 漏桶算法实现接口限流，漏桶算法控制请求流出速率，平滑突发流量，削平流量峰值。
 | 原文链接：http://wiki.ule6cu.asia/arts/825484.Doc

原标题：golang cron 定时任务防并发执行
简介：golang 雪花算法 workId 自动获取，自动获取机器 workId，不用手动配置，简化分布式 id 部署。
 | 原文链接：http://wiki.ule6cu.asia/arts/501874.Doc

原标题：预编译 SQL 防注入实现
简介：全局异常处理器接口返回统一，接入全局异常捕获，拦截业务全部异常，对外输出统一格式返回值。
 | 原文链接：http://wiki.ule6cu.asia/arts/131187.Doc

原标题：代码格式化工具团队统一风格
简介：MySQL 慢查询索引优化实战，抓取慢查询 SQL，分析执行计划，新增或者调整索引，提升 SQL 执行速度。
 | 原文链接：http://wiki.ule6cu.asia/arts/222288.Doc

原标题：WSL 文件权限访问异常修复
简介：预编译 SQL 防注入实现，使用预编译 SQL 方式，杜绝 SQL 注入风险，提升数据库访问层安全能力。
 | 原文链接：http://wiki.ule6cu.asia/arts/715079.Doc

原标题：开源实践：开源项目如何写好PullRequest
简介：golang go mod exclude 排除依赖版本，exclude 排除有问题依赖版本，规避有 bug 的第三方包。
 | 原文链接：http://wiki.ule6cu.asia/arts/813332.Doc

原标题：调优方案：前端静态资源打包性能体积优化
简介：express 请求参数校验处理，接入参数校验库，校验入参，拦截非法参数，提前拦截错误请求。
 | 原文链接：http://wiki.ule6cu.asia/arts/082027.Doc

原标题：文件读写与异常捕获代码示例
简介：golang go 项目工程目录布局标准，不同规模 go 项目目录结构，小型项目中型项目大型微服务项目布局。
 | 原文链接：http://wiki.ule6cu.asia/arts/996060.Doc

原标题：开发记录：接口请求日志记录完整中间件实现
简介：移动端适配 rem vw 方案对比，对比 rem 与 vw 移动端适配方案，分析优缺点，给出选型建议。
 | 原文链接：http://wiki.ule6cu.asia/arts/082898.Doc

原标题：golang redis 批量 pipeline 实践
简介：golang bufio.Scanner 按行读取大文件，Scanner 逐行读取文本文件，处理超大日志 csv。
 | 原文链接：http://wiki.ule6cu.asia/arts/157081.Doc

原标题：golang docker volume 数据持久化
简介：golang k8s 客户端 client‑go 简单示例，client‑go 操作 k8s 资源，增删改查 pod deployment 等资源对象。
 | 原文链接：http://wiki.ule6cu.asia/arts/069678.Doc

原标题：DevOps：多环境镜像标签版本管理规范
简介：golang mysql 慢查询日志程序采集解析，程序读取解析 mysql 慢查询日志，统计慢 SQL 做监控告警。
 | 原文链接：http://wiki.ule6cu.asia/arts/504187.Doc

原标题：优化实践：异步改造同步接口提升吞吐能力
简介：golang math 包常用数学函数，绝对值取整平方根三角函数，业务数学计算工具。
 | 原文链接：http://wiki.ule6cu.asia/arts/325229.Doc


二、踩坑排错｜Troubleshooting
原标题：golang 系统设计 rest api 接口设计最佳实践
简介：Git 代码冲突正确处理方式，讲解冲突产生场景，演示冲突文件修改，正确合并代码，防止代码丢失。
 | 原文链接：http://wiki.ule6cu.asia/arts/300886.Doc

原标题：golang redis set 集合去重业务
简介：数值 key 浮点匹配异常规避，避免浮点数作为 Redis 等存储的 key，防止精度问题引发 key 匹配失败。
 | 原文链接：http://wiki.ule6cu.asia/arts/270926.Doc

原标题：golang 系统设计故障复盘模板 postmortem 参考
简介：项目目录结构规范化最佳实践，梳理源码、配置、静态资源目录划分，规范项目布局，提升代码可读性和可维护性。
 | 原文链接：http://wiki.ule6cu.asia/arts/918522.Doc

原标题：新手指南：读懂项目构建脚本作用
简介：K8s 镜像拉取网络故障修复，排查 K8s 集群镜像拉取网络问题，配置镜像源，恢复镜像正常拉取。
 | 原文链接：http://wiki.ule6cu.asia/arts/163688.Doc

原标题：部署复盘：回滚策略，线上故障快速回退
简介：golang 子进程超时杀死防止挂住，context 控制子进程超时，超时强制杀掉子进程，避免子进程僵尸。
 | 原文链接：http://wiki.ule6cu.asia/arts/342355.Doc

原标题：部署实践：容器时区统一配置解决方案
简介：golang https 客户端跳过证书校验，开发测试环境跳过 tls 证书校验，仅用于内网测试禁止生产使用。
 | 原文链接：http://wiki.ule6cu.asia/arts/720725.Doc

原标题：golang 系统设计分表 id 生成策略对比
简介：golang wasm 性能优化与内存管理，wasm 内存分配释放，减少内存拷贝，优化浏览器端性能。
 | 原文链接：http://wiki.ule6cu.asia/arts/628819.Doc

原标题：golang http grpc 全链路埋点示例
简介：灰度发布策略服务平滑升级，实现灰度发布逻辑，流量逐步切到新版本，出现问题快速回滚旧版本。
 | 原文链接：http://wiki.ule6cu.asia/arts/015219.Doc

原标题：Practice：模拟主从延迟业务兼容方案实践
简介：网关集成鉴权限流日志一体化，在网关层整合鉴权、限流、请求日志，统一对入口请求做管控处理。
 | 原文链接：http://wiki.ule6cu.asia/arts/534712.Doc

原标题：调优方案：容器CPU内存参数压测后调优
简介：golang tar gz 压缩解压处理，tar.gz 归档压缩解压，服务端日志备份、文件打包场景使用。
 | 原文链接：http://wiki.ule6cu.asia/arts/781002.Doc

原标题：开发记录：业务错误告警邮件通知组件实践
简介：Shell 脚本自动化命令编写，讲解 Shell 基础语法，编写自动化脚本，完成批量执行、文件处理，解放重复手工操作。
 | 原文链接：http://wiki.ule6cu.asia/arts/452205.Doc

原标题：git stash 代码暂存切换分支
简介：golang trace 可视化分析协程阻塞，使用 trace 网页 UI，定位协程阻塞、系统调用阻塞、锁等待。
 | 原文链接：http://wiki.ule6cu.asia/arts/451437.Doc

原标题：golang 系统设计字符串拼接性能优化技巧
简介：业务幂等键设计防重复逻辑，讲解幂等键设计思路，选择合适业务字段作为幂等标识，实现可靠防重复。
 | 原文链接：http://wiki.ule6cu.asia/arts/632071.Doc

原标题：部署实践：Nginx高可用配置方案实践
简介：nestjs 权限守卫鉴权实现方案，使用 Nest 守卫实现接口鉴权，角色权限控制，拦截未授权接口访问。
 | 原文链接：http://wiki.ule6cu.asia/arts/122629.Doc

原标题：Practice：模拟第三方接口超时服务降级验证
简介：golang 速率限制令牌桶实现，Go 实现令牌桶限流算法，可复用限流器，控制业务调用速率。
 | 原文链接：http://wiki.ule6cu.asia/arts/203425.Doc

原标题：golang 系统设计配置灰度下发简单实现思路
简介：Git 分支切换合并删除完整操作，实操分支全生命周期操作，包含切换、合并、删除，熟悉日常开发分支处理流程。
 | 原文链接：http://wiki.ule6cu.asia/arts/914562.Doc

原标题：golang mysql limit 大分页优化
简介：golang 数据库连接池参数调优详解，最大连接空闲连接最大生命周期，结合业务合理配置避免资源浪费。
 | 原文链接：http://wiki.ule6cu.asia/arts/426017.Doc

原标题：golang 系统设计 gob msgpack 序列化对比
简介：golang nilnil interface 陷阱复现，interface 包含类型不为 nil 值为 nil，判 ==nil 返回 false 经典坑。
 | 原文链接：http://wiki.ule6cu.asia/arts/996979.Doc

原标题：运维笔记：服务器定时任务运维脚本编写
简介：golang jwt 鉴权中间件完整示例，Gin JWT 鉴权中间件，令牌校验，解析用户信息，接口鉴权拦截。
 | 原文链接：http://wiki.ule6cu.asia/arts/960147.Doc

原标题：内存泄漏定位分析完整流程
简介：golang hertz http 框架快速上手，hertz 高性能 http 框架，路由中间件参数校验快速开发接口服务。
 | 原文链接：http://wiki.ule6cu.asia/arts/897045.Doc

原标题：日志敏感信息脱敏泄露防护
简介：golang 时间时区处理避坑指南，Go 时间时区常见坑，时区转换，时间比较，规避时间逻辑错误。
 | 原文链接：http://wiki.ule6cu.asia/arts/895640.Doc

原标题：排错：本地[localhost](https://localhost)可以，127001访问失败
简介：golang testing.TB Helper 标记辅助函数，t.Helper 标记辅助函数，报错打印真实调用位置。
 | 原文链接：http://wiki.ule6cu.asia/arts/106221.Doc

原标题：golang 协程泄露问题排查方法
简介：golang 日志输出 stdout 标准输出规范，容器环境日志输出到 stdout，由容器平台统一采集日志文件。
 | 原文链接：http://wiki.ule6cu.asia/arts/628033.Doc

原标题：golang 系统设计限流算法原理代码实现
简介：缓存穿透击穿雪崩全套防护，完整梳理缓存三大问题，落地全套防护策略，保障缓存层稳定运行。
 | 原文链接：http://wiki.ule6cu.asia/arts/753522.Doc

原标题：golang 系统设计 mq 消息顺序性保证思路
简介：golang ip2regionIP 地址解析实战，集成 ip2region 库，根据 IP 解析归属地城市，实现 IP 地域解析。
 | 原文链接：http://wiki.ule6cu.asia/arts/232552.Doc

原标题：效率笔记：gitlog高效查询历史提交技巧
简介：项目构建脚本编译打包解析，解读项目构建脚本，理清编译、压缩、资源复制流程，理解打包后产物如何生成。
 | 原文链接：http://wiki.ule6cu.asia/arts/786688.Doc

原标题：性能复盘：消息队列大量小消息性能问题优化
简介：golang 项目 makefile 脚本编写，编写 Makefile 脚本，封装编译、测试、构建命令，简化项目操作。
 | 原文链接：http://wiki.ule6cu.asia/arts/823359.Doc

原标题：golang 系统设计接口幂等架构设计
简介：golang go 项目依赖冲突解决完整思路，定位冲突包，replace、exclude、升级降级解决版本冲突。
 | 原文链接：http://wiki.ule6cu.asia/arts/531455.Doc

原标题：golang 系统设计消息 partition 数量设置思路
简介：golang mysql 事务回滚异常处理，Go MySQL 事务异常捕获，正确回滚事务，保证异常场景数据回滚。
 | 原文链接：http://wiki.ule6cu.asia/arts/896322.Doc

原标题：css 变量主题切换方案实现
简介：golang icmp ping 程序实现，go 实现 ping 工具发送 icmp 报文，检测网络连通性。
 | 原文链接：http://wiki.ule6cu.asia/arts/074720.Doc

原标题：提交第一个开源 PR 完整流程
简介：golang 文件句柄耗尽排查处理，统计进程打开文件句柄，找到未关闭文件，修复句柄泄漏问题。
 | 原文链接：http://wiki.ule6cu.asia/arts/332658.Doc

原标题：Debug：长连接未设置心跳，连接僵死不回收
简介：golang go 服务日志输出 journald，systemd journald 接收程序 stdout 日志，统一管理服务日志。
 | 原文链接：http://wiki.ule6cu.asia/arts/752589.Doc

原标题：golang 系统设计大表结构变更不停机方案
简介：golang hertz 反向代理与负载均衡，hertz 实现反向代理，内置负载均衡，快速搭建网关类服务。
 | 原文链接：http://wiki.ule6cu.asia/arts/402757.Doc

原标题：golang 重试退避机制代码实现
简介：项目目录结构规范化最佳实践，梳理源码、配置、静态资源目录划分，规范项目布局，提升代码可读性和可维护性。
 | 原文链接：http://wiki.ule6cu.asia/arts/375054.Doc

原标题：站内邮件消息通知功能开发
简介：golang rsa 签名验签 pem 证书加载，加载 pem 格式密钥证书，rsa 签名与验签完整业务实现。
 | 原文链接：http://wiki.ule6cu.asia/arts/387200.Doc

原标题：安全笔记：依赖包漏洞检测供应链安全
简介：时间精度统一业务判断修复，统一业务使用时间戳精度，毫秒秒区分清楚，修复时间判断逻辑错误。
 | 原文链接：http://wiki.ule6cu.asia/arts/155336.Doc

原标题：Practice：从零实现轻量后端接口服务完整实践
简介：golang 延迟队列实现方案对比，时间轮、redis zset 实现延迟队列，处理延时执行业务。
 | 原文链接：http://wiki.ule6cu.asia/arts/345251.Doc

原标题：坑点：npm/pip全局版本与项目本地版本冲突
简介：游标分页大数据查询性能提升，使用游标分页替代偏移分页，解决大数据 offset 分页性能越来越差问题。
 | 原文链接：http://wiki.ule6cu.asia/arts/758140.Doc

原标题：golang 系统设计监控缺失指标补全完整流程
简介：缓存基础原理与简单代码实现，讲解缓存设计思路，编写简易缓存逻辑，减少重复计算与重复请求，提升程序响应速度。
 | 原文链接：http://wiki.ule6cu.asia/arts/415588.Doc

原标题：golang 雪花 id 重复问题排查
简介：MySQL 慢查询索引优化实战，抓取慢查询 SQL，分析执行计划，新增或者调整索引，提升 SQL 执行速度。
 | 原文链接：http://wiki.ule6cu.asia/arts/192171.Doc

三、实战开发｜Practice
原标题：Issue：浏览器缓存ServiceWorker导致旧页面常驻
简介：golang 服务限流熔断降级监控完整实践，微服务防护体系，限流熔断降级指标监控告警整套落地。
 | 原文链接：http://wiki.ule6cu.asia/arts/141734.Doc

原标题：快速上手阅读开源项目源码的入门思路
简介：golang go1.18 + 泛型基础实操，go 泛型基础语法，泛型函数泛型类型，实现通用工具函数。
 | 原文链接：http://wiki.ule6cu.asia/arts/943007.Doc

原标题：新手指南：本地防火墙端口访问失败排查
简介：golang 日志 zap 结构化日志实践，接入 Zap 结构化日志库，打印结构化日志，方便日志检索解析。
 | 原文链接：http://wiki.ule6cu.asia/arts/355258.Doc

原标题：golang 系统设计缓存大 key 拆分优化实操
简介：分布式 ID 生成器高并发实现，实现高性能分布式 ID 生成器，适配高并发业务，生成全局唯一 ID。
 | 原文链接：http://wiki.ule6cu.asia/arts/415488.Doc

原标题：golang 系统设计防重复提交实现
简介：Git 误删提交代码恢复找回，使用 Git reflog 工具找回被误删除提交记录，恢复误删除代码。
 | 原文链接：http://wiki.ule6cu.asia/arts/333887.Doc

原标题：从零搭建简单的身份登录模拟示例
简介：缓存过期打散防止缓存雪崩，对缓存过期时间增加随机偏移，避免大量缓存同时失效引发缓存雪崩。
 | 原文链接：http://wiki.ule6cu.asia/arts/297092.Doc

原标题：安全复盘：业务接口越权测试与修复实践
简介：golang 接口限流中间件开发，Gin 开发限流中间件，接口层实现访问频率限制，防护接口流量。
 | 原文链接：http://wiki.ule6cu.asia/arts/041006.Doc

原标题：golang mysql exists in 性能对比
简介：Git 代码冲突正确处理方式，讲解冲突产生场景，演示冲突文件修改，正确合并代码，防止代码丢失。
 | 原文链接：http://wiki.ule6cu.asia/arts/685077.Doc

原标题：golang 优雅处理 http 超时设置
简介：golang sort 切片排序自定义 less，sort.Slice 切片快速排序，自定义 less 函数实现业务排序。
 | 原文链接：http://wiki.ule6cu.asia/arts/694353.Doc

原标题：优化实践：接口返回字段裁剪减少报文大小
简介：CORS 跨域问题多种解决方案，对比 CORS、代理等不同跨域方案优缺点，根据业务场景选择合适的跨域处理方式。
 | 原文链接：http://wiki.ule6cu.asia/arts/290267.Doc

原标题：ORM 隐式慢查询问题规避
简介：golang embed 目录读取文件列表，embed 嵌入整个目录，读取目录下全部文件，做静态资源服务。
 | 原文链接：http://wiki.ule6cu.asia/arts/931097.Doc

原标题：Hands‑on：shell脚本批量自动化运维小工具
简介：golang httptest 模拟 http 请求单元测试，httptest 模拟 http 请求，测试 http handler 逻辑不用启动服务。
 | 原文链接：http://wiki.ule6cu.asia/arts/082119.Doc

原标题：项目实践：实现统一接口返回封装与全局异常处理
简介：数据库主从延迟业务兼容处理，业务适配主从复制延迟，避免读取从库拿到还未同步完成旧数据。
 | 原文链接：http://wiki.ule6cu.asia/arts/081337.Doc

原标题：golang 系统设计密码存储哈希加盐实现
简介：golang go 第三方库选型评估要点，评估库活跃度维护情况、性能、依赖数量，选择合适开源库。
 | 原文链接：http://wiki.ule6cu.asia/arts/314744.Doc

原标题：golang toml 配置文件解析教程
简介：跨平台 uniapp 多端开发实操，uniapp 开发一套代码，编译多端，梳理多端差异处理与适配技巧。
 | 原文链接：http://wiki.ule6cu.asia/arts/152588.Doc

原标题：安全复盘：消息队列未授权访问安全加固
简介：golang math 包常用数学函数，绝对值取整平方根三角函数，业务数学计算工具。
 | 原文链接：http://wiki.ule6cu.asia/arts/301281.Doc

原标题：安全实践：敏感信息加密存储传输完整方案
简介：golang go 第三方库选型评估要点，评估库活跃度维护情况、性能、依赖数量，选择合适开源库。
 | 原文链接：http://wiki.ule6cu.asia/arts/926310.Doc

原标题：Hands‑on：简易短链接服务完整开发实践
简介：golang 半关闭 tcp 连接 shutdown，tcp 连接 shutdown 半关闭，单向关闭读或者写，理解 tcp 关闭流程。
 | 原文链接：http://wiki.ule6cu.asia/arts/699051.Doc

原标题：golang 大文件 http 下载服务
简介：golang go get 升级降级依赖版本，go get 指定版本升级降级依赖包，管理第三方库版本。
 | 原文链接：http://wiki.ule6cu.asia/arts/269139.Doc

原标题：golang docker 部署 mysql 注意事项
简介：CI 构建缓存加速编译速度，开启 CI 流水线依赖缓存，复用上一次构建依赖包，缩短流水线构建耗时。
 | 原文链接：http://wiki.ule6cu.asia/arts/049670.Doc

原标题：零基础理解读写分离基础思想
简介：简易网关请求路由过滤模拟，模拟网关基础能力，实现请求路由转发、简单过滤，理解网关核心工作逻辑。
 | 原文链接：http://wiki.ule6cu.asia/arts/989689.Doc

原标题：入门实践：简单数据脱敏处理示例
简介：golang proto 默认值坑点梳理，梳理 Protobuf 默认值坑，零值字段区分未赋值，避免业务逻辑错误。
 | 原文链接：http://wiki.ule6cu.asia/arts/401705.Doc

原标题：nodejs 读取大文件 csv 处理方案
简介：golang 系统 IO 阻塞 goroutine 场景，理解系统调用阻塞 M，P 会调度其他 M，掌握 go 调度行为。
 | 原文链接：http://wiki.ule6cu.asia/arts/243392.Doc

原标题：Cookie 跨环境登录配置调整
简介：golang goroutine 泄露常见场景汇总，channel 阻塞、context 忘记取消，导致协程无法退出发生泄露。
 | 原文链接：http://wiki.ule6cu.asia/arts/573759.Doc

原标题：golang 系统设计消息队列解耦削峰
简介：golang websocket 服务端开发，Go 实现 WebSocket 服务端，处理连接、消息收发，实现长连接服务。
 | 原文链接：http://wiki.ule6cu.asia/arts/983826.Doc

原标题：golang prometheus 告警规则编写
简介：golang 容器健康检查接口开发，Go 开发 HTTP 健康接口，供容器编排工具探测实例存活状态。
 | 原文链接：http://wiki.ule6cu.asia/arts/118006.Doc

原标题：架构笔记：WebSocket大规模连接服务架构
简介：golang goroutine 泄露检测告警实现，监控 goroutine 数量，突增触发告警，提早发现协程泄露。
 | 原文链接：http://wiki.ule6cu.asia/arts/894715.Doc

原标题：Hands‑on：简易请求转发代理中间件实现
简介：前端骨架屏提升页面体验，实现页面骨架屏，数据未加载完成展示占位，优化页面白屏感知体验。
 | 原文链接：http://wiki.ule6cu.asia/arts/880292.Doc

原标题：webpack chunk 分包策略详解
简介：代码模块化组件化拆分思路，讲解代码拆分原则，将大业务拆分为独立模块组件，提升代码复用与维护能力。
 | 原文链接：http://wiki.ule6cu.asia/arts/329389.Doc

原标题：Security：接口鉴权越权漏洞检测与修复
简介：golang go time 时区数据库内置，go 内置时区数据库，不用系统时区文件，容器时区不依赖系统。
 | 原文链接：http://wiki.ule6cu.asia/arts/315430.Doc

原标题：golang 系统设计自动化测试 ci 流水线集成实操
简介：前端下载导出文件功能实现，前端实现文件流下载导出，处理异常，适配浏览器不同下载行为。
 | 原文链接：http://wiki.ule6cu.asia/arts/499522.Doc

原标题：快速入门容器基础概念，理解镜像与容器
简介：WebSocket 断线重连稳定优化，增加 WebSocket 断线自动重连逻辑，处理网络抖动，维持长连接稳定。
 | 原文链接：http://wiki.ule6cu.asia/arts/996084.Doc

原标题：golang 分布式 ID 雪花算法实现
简介：golang websocket 服务端开发，Go 实现 WebSocket 服务端，处理连接、消息收发，实现长连接服务。
 | 原文链接：http://wiki.ule6cu.asia/arts/419684.Doc

原标题：Troubleshooting：WSL文件权限问题大量踩坑
简介：Shell 脚本自动化命令编写，讲解 Shell 基础语法，编写自动化脚本，完成批量执行、文件处理，解放重复手工操作。
 | 原文链接：http://wiki.ule6cu.asia/arts/542873.Doc

原标题：零基础理解内存溢出基础现象与表现
简介：简易日志收集集中管理方案，搭建轻量日志收集方案，把多服务日志汇总，集中检索查看日志信息。
 | 原文链接：http://wiki.ule6cu.asia/arts/085666.Doc

原标题：golang 系统设计分布式任务调度
简介：golang go 程序敏感信息禁止打印日志，密钥密码禁止输出日志，防止敏感信息日志泄露。
 | 原文链接：http://wiki.ule6cu.asia/arts/723200.Doc

原标题：记一次分库分表路由计算错误数据写入错误分片
简介：golang k8s secret 敏感配置加载，加载 k8s secret 存储密钥密码，敏感信息不存放配置文件。
 | 原文链接：http://wiki.ule6cu.asia/arts/224080.Doc

原标题：静态博客部署 GitHub Pages 教程
简介：nestjs 权限守卫鉴权实现方案，使用 Nest 守卫实现接口鉴权，角色权限控制，拦截未授权接口访问。
 | 原文链接：http://wiki.ule6cu.asia/arts/757744.Doc

原标题：消息队列消费堆积扩容处理
简介：数据库连接池参数调优，调整连接池最大最小连接数，空闲超时，避免连接耗尽或者资源浪费。
 | 原文链接：http://wiki.ule6cu.asia/arts/323857.Doc

原标题：运维笔记：系统文件句柄数调整生产配置
简介：golang gif 图片帧处理操作，解析 gif 图片帧，压缩、拆分 gif 动图，处理动图业务。
 | 原文链接：http://wiki.ule6cu.asia/arts/809003.Doc

四、架构设计｜Architecture
原标题：服务健康检查告警监控体系
简介：正则表达式优化 CPU 占满问题，优化正则表达式写法，避免回溯，防止正则运算 CPU 占用 100%。
 | 原文链接：http://wiki.ule6cu.asia/arts/899533.Doc

原标题：golang 系统设计内部服务调用超时设置要点
简介：容器软链接文件权限修复，修复容器内软链接文件权限，让程序能够正常读取软链接指向的文件。
 | 原文链接：http://wiki.ule6cu.asia/arts/318471.Doc

原标题：性能复盘：磁盘Swap大量使用系统卡顿优化
简介：golang systemd 配置 go 服务部署，编写 systemd unit 文件管理 go 服务，开机自启、崩溃自动重启。
 | 原文链接：http://wiki.ule6cu.asia/arts/267874.Doc

原标题：Git 误提交撤销回退实操教程
简介：golang time 时间比较 Before After Equal，时间比较不要直接减，使用内置方法判断时间先后。
 | 原文链接：http://wiki.ule6cu.asia/arts/932841.Doc

原标题：性能笔记：HTTP连接复用性能优化实践
简介：浏览器本地存储安全使用技巧，讲解 localStorage、sessionStorage 使用边界，规避 XSS 泄露存储数据。
 | 原文链接：http://wiki.ule6cu.asia/arts/349557.Doc

原标题：golang 系统设计会话共享多实例部署
简介：golang delve 远程调试 go 线上程序，delve 远程调试，线上环境附加进程调试排查线上 bug。
 | 原文链接：http://wiki.ule6cu.asia/arts/523456.Doc

原标题：入门实践：搭建简单的热更新开发环境
简介：webpack chunk 分包策略详解，讲解 webpack chunk 分包策略，拆分第三方包与业务代码，优化缓存复用。
 | 原文链接：http://wiki.ule6cu.asia/arts/048657.Doc

原标题：性能笔记：操作系统文件句柄、虚拟内存调优
简介：配置外部化线上部署防错误，把配置从代码剥离，外部传入配置，修改配置不需要重新打包构建。
 | 原文链接：http://wiki.ule6cu.asia/arts/558868.Doc

原标题：新手向：开源项目依赖安装失败排查
简介：MySQL 慢查询索引优化实战，抓取慢查询 SQL，分析执行计划，新增或者调整索引，提升 SQL 执行速度。
 | 原文链接：http://wiki.ule6cu.asia/arts/783866.Doc

原标题：golang 系统设计 git 钩子自动化校验实现
简介：golang fasthttp 服务开发完整示例，fasthttp 搭建 http 服务，路由、参数读取、响应返回完整业务。
 | 原文链接：http://wiki.ule6cu.asia/arts/291305.Doc

原标题：Practice：实现数据库连接池简易模拟实现
简介：nestjs 权限守卫鉴权实现方案，使用 Nest 守卫实现接口鉴权，角色权限控制，拦截未授权接口访问。
 | 原文链接：http://wiki.ule6cu.asia/arts/864349.Doc

原标题：golang 系统设计压测工具 wrk 使用实操
简介：Nginx 反向代理路由配置实战，配置 Nginx 反向代理，实现请求转发、路由分发，掌握 Nginx 基础配置能力。
 | 原文链接：http://wiki.ule6cu.asia/arts/935713.Doc

原标题：数据库分表存储大表优化方案
简介：golang 单元测试 mock http 请求，mock HTTP 外部接口，单元测试不依赖外部网络，保证用例稳定运行。
 | 原文链接：http://wiki.ule6cu.asia/arts/864696.Doc

原标题：golang 系统设计指标聚合计算存储选型对比
简介：本地简易配置中心动态管理，搭建轻量本地配置中心，业务动态读取配置，修改配置不重启服务。
 | 原文链接：http://wiki.ule6cu.asia/arts/807364.Doc

原标题：golang git 提交信息规范校验
简介：webpack chunk 分包策略详解，讲解 webpack chunk 分包策略，拆分第三方包与业务代码，优化缓存复用。
 | 原文链接：http://wiki.ule6cu.asia/arts/752115.Doc

原标题：本地运行正常线上报错排查
简介：数据库分表路由写入分片修正，修复分表路由逻辑，保证数据写入正确分片，不会出现数据丢失错乱。
 | 原文链接：http://wiki.ule6cu.asia/arts/137983.Doc

原标题：避坑：预编译SQL失效，出现SQL注入风险
简介：golang 探测文件真实内容类型，读取文件头部字节判断真实文件格式，规避后缀伪造。
 | 原文链接：http://wiki.ule6cu.asia/arts/411694.Doc

原标题：简易日志收集集中管理方案
简介：golang grafana 面板 go 业务指标可视化，prometheus 指标对接 grafana，配置监控面板可视化业务状态。
 | 原文链接：http://wiki.ule6cu.asia/arts/533527.Doc

?
