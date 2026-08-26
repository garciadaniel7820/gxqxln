最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计性能优化通用思路方法论
简介：日志切割配置防止日志丢失，配置日志切割轮转策略，日志按大小时间切割，防止日志文件丢失。
 | 原文链接：http://wiki.gzyx8e.asia/arts/537132.Doc

原标题：golang 告警推送钉钉机器人实现
简介：文件句柄耗尽资源泄露处理，定位文件句柄泄露，修复文件忘记关闭问题，解决句柄耗尽服务报错。
 | 原文链接：http://wiki.gzyx8e.asia/arts/311774.Doc

原标题：golang gorm ORM 数据库操作
简介：跨域偶现失败配置修复，解决跨域问题时而复现时而正常，定位配置漏配、请求头异常等隐性问题。
 | 原文链接：http://wiki.gzyx8e.asia/arts/122502.Doc

原标题：架构复盘：消息队列在业务系统中边界与最佳实践
简介：golang kafka 消费者组重平衡避坑，规避消费者组频繁 rebalance，减少消费抖动，保障消息消费稳定性。
 | 原文链接：http://wiki.gzyx8e.asia/arts/372186.Doc

原标题：前端国际化多语言方案落地
简介：golang 容器信号转发处理问题修复，docker/k8s 正确转发 SIGTERM 信号，保证 go 程序收到信号优雅退出。
 | 原文链接：http://wiki.gzyx8e.asia/arts/077267.Doc

原标题：golang docker 镜像构建最佳实践
简介：golang fasthttp 高性能 http 库使用，fasthttp 高性能 http 实现，适合超高 QPS 场景，对比 net/http 差异。
 | 原文链接：http://wiki.gzyx8e.asia/arts/087009.Doc

原标题：golang 系统设计 json 解析性能优化实操
简介：golang init 函数合理使用边界，少用 init，优先显式调用初始化，便于控制初始化时机。
 | 原文链接：http://wiki.gzyx8e.asia/arts/899267.Doc

原标题：golang 系统设计 tcp keepalive 参数调优实践
简介：golang os 打开文件 O_APPEND O_CREATE 标志，OpenFile 标志位，控制文件创建追加截断行为。
 | 原文链接：http://wiki.gzyx8e.asia/arts/426586.Doc

原标题：开发复盘：海量日志轮转清理脚本实践
简介：golang pprof 线上采集性能数据，线上环境采集 pprof 性能样本，不用停机，分析线上性能问题。
 | 原文链接：http://wiki.gzyx8e.asia/arts/361131.Doc

原标题：多版本开发环境共存配置
简介：golang grpc 客户端流上传数据，客户端流式请求，客户端分批上传数据到服务端，适合大文件传输。
 | 原文链接：http://wiki.gzyx8e.asia/arts/990260.Doc

原标题：零基础理解读写分离基础思想
简介：golang go 泛型使用避坑注意点，泛型与 interface 区别，泛型性能，什么时候适合使用泛型。
 | 原文链接：http://wiki.gzyx8e.asia/arts/134804.Doc

原标题：golang 系统设计单元测试边界条件覆盖思路
简介：golang http 服务并发连接数限制，自定义 listener 统计连接数量，限制最大并发连接数保护服务。
 | 原文链接：http://wiki.gzyx8e.asia/arts/175310.Doc

原标题：golang 系统设计分布式会话方案对比
简介：程序预加载加快服务启动速度，把高频使用资源提前预加载，减少请求阶段初始化，加快服务启动。
 | 原文链接：http://wiki.gzyx8e.asia/arts/419364.Doc

原标题：Debug：分布式会话时钟不同步令牌提前失效
简介：golang go 程序权限最小化运行，容器内使用普通用户运行程序，拒绝 root 运行提升安全等级。
 | 原文链接：http://wiki.gzyx8e.asia/arts/802514.Doc

原标题：批量异步处理系统业务落地
简介：golang 配置文件多环境加载，Go 多环境配置加载实现，读取配置文件环境变量，适配多套运行环境。
 | 原文链接：http://wiki.gzyx8e.asia/arts/433325.Doc

原标题：Performance：JSON序列化性能优化实践
简介：golang staticcheck 静态代码分析，staticcheck 深度静态检查，发现代码错误、性能问题、风格问题。
 | 原文链接：http://wiki.gzyx8e.asia/arts/943024.Doc

原标题：golang 系统设计 canary 金丝雀部署实操
简介：golang 信号捕获程序退出处理，Go 捕获操作系统信号，做资源回收，控制程序退出流程。
 | 原文链接：http://wiki.gzyx8e.asia/arts/756615.Doc

原标题：踩坑记录：浮点精度错误造成业务计算错误
简介：golang go 泛型约束与类型集合，泛型 type set 约束，限制泛型支持类型，写出安全泛型代码。
 | 原文链接：http://wiki.gzyx8e.asia/arts/644466.Doc

原标题：架构笔记：冷热数据分离架构设计与迁移
简介：golang 自定义 pprof 扩展业务指标，扩展 pprof，输出业务自定义指标，结合性能数据分析业务状态。
 | 原文链接：http://wiki.gzyx8e.asia/arts/069288.Doc

原标题：实践：大文件分片上传后端完整实现思路
简介：开源项目构建失败排查步骤，梳理构建报错排查流程，从依赖、网络、权限、脚本多角度定位项目构建失败原因。
 | 原文链接：http://wiki.gzyx8e.asia/arts/671610.Doc

原标题：项目语义化版本号规范管理
简介：golang redis bitmap 位图业务实战，bitmap 做签到统计、用户状态标记，节省大量内存空间。
 | 原文链接：http://wiki.gzyx8e.asia/arts/320407.Doc

原标题：实践：前后端分离项目登录状态保持完整方案
简介：golang go http 安全头配置实践，设置 http 安全响应头，防范 XSS、点击劫持，提升 web 服务安全性。
 | 原文链接：http://wiki.gzyx8e.asia/arts/236667.Doc

原标题：部署复盘：配置不要硬编码进镜像最佳实践
简介：golang 数据库连接池参数调优详解，最大连接空闲连接最大生命周期，结合业务合理配置避免资源浪费。
 | 原文链接：http://wiki.gzyx8e.asia/arts/168772.Doc

原标题：golang docker 容器资源限制设置
简介：golang 配置文件多格式兼容加载，同时支持 yaml toml json 多种格式配置文件，灵活适配不同部署环境。
 | 原文链接：http://wiki.gzyx8e.asia/arts/245062.Doc

原标题：golang 系统设计配置中心核心能力梳理讲解
简介：golang go mod tidy 依赖清理，go mod tidy 自动增删依赖，整理 go.mod go.sum 文件。
 | 原文链接：http://wiki.gzyx8e.asia/arts/752045.Doc

原标题：golang 系统设计开源项目协作流程梳理
简介：HTTPS 证书过期更新操作，检测 HTTPS 证书到期，更新证书文件，恢复 HTTPS 服务正常访问。
 | 原文链接：http://wiki.gzyx8e.asia/arts/727787.Doc

原标题：Performance：避免大报文，减少内存占用优化
简介：golang redis bloom 布隆过滤器 go‑redis，go‑redis 布隆过滤器，海量数据判断是否存在，减少数据库查询。
 | 原文链接：http://wiki.gzyx8e.asia/arts/365822.Doc

原标题：golang 系统设计逻辑删除物理删除选型对比
简介：并发数据覆盖加锁安全处理，多线程并发修改同一数据，增加锁机制，防止并发覆盖丢失更新数据。
 | 原文链接：http://wiki.gzyx8e.asia/arts/351011.Doc

原标题：golang 系统设计 rest http 方法使用原则
简介：golang strings.Builder 字符串高效拼接，strings.Builder 做字符串拼接，比 += 性能更高，减少内存拷贝。
 | 原文链接：http://wiki.gzyx8e.asia/arts/678179.Doc

原标题：golang k8s 监控 prometheus 部署
简介：golang go 变量逃逸场景汇总，切片、指针、返回局部变量引发逃逸，变量分配到堆影响 GC。
 | 原文链接：http://wiki.gzyx8e.asia/arts/014227.Doc

原标题：golang mysql 字符集排序规则设置
简介：golang tcp keepalive 参数程序配置，go 程序设置 tcp keepalive，操作系统 tcp 保活参数，清理僵死连接。
 | 原文链接：http://wiki.gzyx8e.asia/arts/720655.Doc

原标题：golang 系统设计熔断降级架构讲解
简介：数据库连接及时关闭连接泄漏，确保数据库连接使用完毕释放归还连接池，杜绝连接泄漏耗尽连接。
 | 原文链接：http://wiki.gzyx8e.asia/arts/204841.Doc

原标题：golang 系统设计配置灰度下发简单实现思路
简介：golang ctx 传递规则不要存结构体，context 作为函数参数传递，禁止放入结构体字段存储。
 | 原文链接：http://wiki.gzyx8e.asia/arts/555889.Doc

原标题：实战项目：编写Dockerfile多阶段构建减小镜像体积
简介：golang context 取消传播机制，父 ctx 取消，所有派生子 context 全部被取消，理解上下文传播。
 | 原文链接：http://wiki.gzyx8e.asia/arts/145150.Doc

原标题：排错：前端sourcemap错误线上无法定位报错
简介：golang 数据库连接池参数调优详解，最大连接空闲连接最大生命周期，结合业务合理配置避免资源浪费。
 | 原文链接：http://wiki.gzyx8e.asia/arts/908763.Doc

原标题：golang gitlab ci 配置自动构建镜像
简介：golang 分库分表 id 路由规则设计，分库分表 id 路由算法，id 映射库表，数据均匀打散避免热点分片。
 | 原文链接：http://wiki.gzyx8e.asia/arts/333995.Doc

原标题：线上异常：时间时区问题，定时任务执行偏移
简介：golang gitlab ci go 项目流水线编写，gitlab ci 流水线执行单元测试、静态检查、构建推送镜像。
 | 原文链接：http://wiki.gzyx8e.asia/arts/787584.Doc

原标题：排错：前端打包chunk过大浏览器加载缓慢
简介：golang multipart 表单文件上传解析，服务端解析 multipart 表单，获取上传文件与表单字段。
 | 原文链接：http://wiki.gzyx8e.asia/arts/111175.Doc

原标题：从零编写简易 CLI 命令行工具
简介：静态资源 404 路径打包修复，修复打包后静态资源访问 404，调整资源输出路径，保证资源正常加载。
 | 原文链接：http://wiki.gzyx8e.asia/arts/737069.Doc

原标题：golang 系统设计分库分表中间件思路
简介：golang mysql 事务回滚异常处理，Go MySQL 事务异常捕获，正确回滚事务，保证异常场景数据回滚。
 | 原文链接：http://wiki.gzyx8e.asia/arts/055044.Doc


二、踩坑排错｜Troubleshooting
原标题：CLI 批量处理工具文件操作开发
简介：单元测试用例编写入门实操，讲解测试用例设计思路，演示基础单元测试代码，提升代码健壮性，提前发现逻辑 bug。
 | 原文链接：http://wiki.gzyx8e.asia/arts/530185.Doc

原标题：golang 系统设计定时任务分片执行分布式思路
简介：golang 漏桶算法实现接口限流，漏桶算法控制请求流出速率，平滑突发流量，削平流量峰值。
 | 原文链接：http://wiki.gzyx8e.asia/arts/753061.Doc

原标题：golang mysql 行锁表锁场景区分
简介：死信队列处理消息阻塞业务，配置死信队列，处理消费失败消息，避免失败消息阻塞整个队列业务。
 | 原文链接：http://wiki.gzyx8e.asia/arts/416577.Doc

原标题：golang 分布式锁防死锁处理
简介：golang go yaml 解析自定义类型，yaml 自定义序列化，时间、特殊类型自定义解析逻辑。
 | 原文链接：http://wiki.gzyx8e.asia/arts/845080.Doc

原标题：golang 系统设计压测工具 wrk 使用实操
简介：环境变量不生效问题修复，排查环境变量加载顺序、作用域问题，修复环境变量读取不到的异常。
 | 原文链接：http://wiki.gzyx8e.asia/arts/376548.Doc

原标题：开发复盘：搭建文件上传服务支持分片断点续传
简介：golang recover 捕获 panic 使用边界，recover 只在 defer 内部生效，协程内部必须捕获本协程 panic。
 | 原文链接：http://wiki.gzyx8e.asia/arts/088626.Doc

原标题：实战项目：实现分布式任务调度最小原型
简介：golang wasm 性能优化与内存管理，wasm 内存分配释放，减少内存拷贝，优化浏览器端性能。
 | 原文链接：http://wiki.gzyx8e.asia/arts/671641.Doc

原标题：部署复盘：服务启动顺序依赖处理方案
简介：nodejs 定时任务生产环境避坑，Node 定时任务线上踩坑汇总，集群重复执行、任务阻塞等问题解决方案。
 | 原文链接：http://wiki.gzyx8e.asia/arts/904620.Doc

原标题：golang kafka 消费者组原理讲解
简介：golang ctx 关闭之后资源释放，context 取消后，监听 Done ()，释放 goroutine 网络 IO 资源。
 | 原文链接：http://wiki.gzyx8e.asia/arts/904443.Doc

原标题：golang k8s pod 优雅关闭流程讲解
简介：Redis 大 key 拆分集群卡顿解决，拆分 Redis 超大 Key，避免大 key 操作造成 Redis 集群卡顿阻塞。
 | 原文链接：http://wiki.gzyx8e.asia/arts/682858.Doc

原标题：Troubleshoot：RPC序列化对象字段增减兼容踩坑
简介：golang excel 生成导出高性能方案，excelize 流式生成 excel，百万行数据导出，规避内存溢出。
 | 原文链接：http://wiki.gzyx8e.asia/arts/867962.Doc

原标题：golang 系统设计故障复盘模板 postmortem 参考
简介：golang sync.RWMutex 读写锁使用场景，读多写少场景读写锁，读共享写互斥，提升并发性能。
 | 原文链接：http://wiki.gzyx8e.asia/arts/318749.Doc

原标题：大事务拆分防止连接池耗尽
简介：OpenAPI 自动接口文档生成，集成 OpenAPI 工具，自动扫描代码生成接口文档，减少文档维护成本。
 | 原文链接：http://wiki.gzyx8e.asia/arts/557175.Doc

原标题：golang redis 布隆过滤器安装使用
简介：golang 滑动窗口限流算法 go 实现，滑动窗口限流，解决固定窗口临界流量突增漏洞，限流更精准。
 | 原文链接：http://wiki.gzyx8e.asia/arts/590591.Doc

原标题：新手教程：本地环境变量配置全流程
简介：多规则数据脱敏组件开发，封装通用脱敏组件，支持多种脱敏规则，项目多处复用脱敏逻辑。
 | 原文链接：http://wiki.gzyx8e.asia/arts/286810.Doc

原标题：设计思考：系统降级开关架构设计快速切流量
简介：css 动画性能优化 GPU 加速，优化 CSS 动画，使用 GPU 加速属性，避免动画过程页面卡顿掉帧。
 | 原文链接：http://wiki.gzyx8e.asia/arts/649302.Doc

原标题：golang 系统设计 README 开源文档模板
简介：文件监控服务自动重启开发，监控项目文件变更，代码修改自动重启服务，提升本地开发调试效率。
 | 原文链接：http://wiki.gzyx8e.asia/arts/672583.Doc

原标题：golang 系统设计配置回滚版本历史记录实现
简介：golang go 项目 CI github actions 配置，github actions 实现 go 项目 ci，自动测试、代码检查、编译打包镜像。
 | 原文链接：http://wiki.gzyx8e.asia/arts/376733.Doc

原标题：实战：搭建日志收集分析简易完整演示环境
简介：golang docker 多阶段构建 go 镜像，Go 项目 Docker 多阶段构建，编译与运行阶段分离，大幅度缩减最终镜像体积，提升镜像分发效率。
 | 原文链接：http://wiki.gzyx8e.asia/arts/024302.Doc

原标题：坑点：缓存过期策略不当引发业务异常
简介：golang go 包循环导入报错解决，A 导入 B B 导入 A，循环导入报错，重构代码拆分包消除循环依赖。
 | 原文链接：http://wiki.gzyx8e.asia/arts/978608.Doc

原标题：CDN 缓存刷新获取最新静态资源
简介：SDK 版本兼容线上崩溃修复，处理 SDK 版本升级之后线上崩溃，定位 API 变更，做版本兼容适配改造。
 | 原文链接：http://wiki.gzyx8e.asia/arts/415369.Doc

原标题：golang redis 持久化 RDB AOF 对比
简介：服务器 Swap 关闭提升响应速度，关闭服务器 Swap 交换分区，避免内存交换磁盘拖慢程序响应性能。
 | 原文链接：http://wiki.gzyx8e.asia/arts/693554.Doc

原标题：前端 pdf 预览渲染方案对比
简介：golang 自定义 pprof 扩展业务指标，扩展 pprof，输出业务自定义指标，结合性能数据分析业务状态。
 | 原文链接：http://wiki.gzyx8e.asia/arts/014487.Doc

原标题：golang 系统设计一致性哈希原理讲解
简介：golang wasm 性能优化与内存管理，wasm 内存分配释放，减少内存拷贝，优化浏览器端性能。
 | 原文链接：http://wiki.gzyx8e.asia/arts/399210.Doc

原标题：HelloTest：理解集成测试基础编写思路
简介：ORM 框架数据库增删改查实操，使用 ORM 框架完成数据库基础操作，减少手写 SQL，简化业务层数据库交互代码。
 | 原文链接：http://wiki.gzyx8e.asia/arts/074308.Doc

原标题：Shell 运维脚本服务器效率提升
简介：golang 时间轮算法实现延时调度，手写简易时间轮，高并发大量延时任务，降低轮询 CPU 消耗。
 | 原文链接：http://wiki.gzyx8e.asia/arts/483528.Doc

原标题：golang redis 分布式锁 redisson 思路
简介：golang lru 缓存淘汰算法编写，手写 LRU 缓存淘汰算法，实现本地缓存，淘汰最久未使用数据。
 | 原文链接：http://wiki.gzyx8e.asia/arts/307553.Doc

原标题：Troubleshoot：批量导入数据，事务过大回滚日志暴涨
简介：golang nacos go 客户端配置服务发现，nacos‑go 对接 nacos，配置管理、微服务注册发现。
 | 原文链接：http://wiki.gzyx8e.asia/arts/628080.Doc

原标题：golang 系统设计消息 partition 数量设置思路
简介：golang 负载均衡轮询加权轮询实现，手写负载均衡算法，轮询、加权轮询分发请求到后端节点。
 | 原文链接：http://wiki.gzyx8e.asia/arts/159791.Doc

原标题：实战：Nginx实现文件限速下载配置实践
简介：端口占用释放资源重启服务，查找占用端口进程，结束占用进程，释放端口，让服务能够正常启动监听。
 | 原文链接：http://wiki.gzyx8e.asia/arts/550155.Doc

原标题：golang prometheus 告警规则编写
简介：日志驱动异常日志不输出修复，排查日志驱动配置，修复日志写入配置，恢复程序正常日志输出。
 | 原文链接：http://wiki.gzyx8e.asia/arts/971296.Doc

原标题：架构复盘：服务灰度发布架构设计与流量切分
简介：容器软链接文件权限修复，修复容器内软链接文件权限，让程序能够正常读取软链接指向的文件。
 | 原文链接：http://wiki.gzyx8e.asia/arts/830026.Doc

原标题：golang 系统设计开源项目维护简单经验分享
简介：接口限流逻辑简单模拟实现，编写简易限流逻辑，限制接口访问频次，保护服务，避免短时间大量请求压垮系统。
 | 原文链接：http://wiki.gzyx8e.asia/arts/385188.Doc

原标题：golang 系统设计请求签名校验完整方案
简介：静态站点自动部署发布方案，配置流水线，代码更新自动构建静态站点并且部署上线，简化发布。
 | 原文链接：http://wiki.gzyx8e.asia/arts/893626.Doc

原标题：调试工具断点调试变量查看技巧
简介：接口幂等性防重复请求实现，实现接口幂等逻辑，避免重复提交请求产生多条脏数据，保障业务数据安全。
 | 原文链接：http://wiki.gzyx8e.asia/arts/703878.Doc

原标题：golang mysql 读写分离简单实现
简介：ORM 隐式慢查询问题规避，识别 ORM 框架隐式查询，避免循环查询数据库，减少不必要慢 SQL 产生。
 | 原文链接：http://wiki.gzyx8e.asia/arts/373342.Doc

原标题：golang minio 对象存储接口开发
简介：golang redis 过期时间处理技巧，设置 key 过期，监控过期事件，基于过期特性实现业务缓存逻辑。
 | 原文链接：http://wiki.gzyx8e.asia/arts/388214.Doc

原标题：日志输出规范防止磁盘爆满
简介：git rebase 整理提交历史实操，使用 rebase 整理杂乱提交记录，将多条提交合并，保持 git 提交历史干净线性。
 | 原文链接：http://wiki.gzyx8e.asia/arts/488822.Doc

原标题：实战项目：GitSubmodule管理多仓库实践
简介：配置外部化线上部署防错误，把配置从代码剥离，外部传入配置，修改配置不需要重新打包构建。
 | 原文链接：http://wiki.gzyx8e.asia/arts/822226.Doc

原标题：从零搭建简单Mock接口服务
简介：nodejs 集成测试业务流程编写，编写 Node 集成测试，调用真实接口，验证完整业务链路执行结果。
 | 原文链接：http://wiki.gzyx8e.asia/arts/312407.Doc

三、实战开发｜Practice
原标题：开发复盘：分布式会话共享多种方案实践
简介：golang go yaml 解析自定义类型，yaml 自定义序列化，时间、特殊类型自定义解析逻辑。
 | 原文链接：http://wiki.gzyx8e.asia/arts/607976.Doc

原标题：golang 系统设计 csrf 接口防护实现
简介：golang go 泛型约束与类型集合，泛型 type set 约束，限制泛型支持类型，写出安全泛型代码。
 | 原文链接：http://wiki.gzyx8e.asia/arts/833351.Doc

原标题：新手教程：gitrebase基础使用与风险提示
简介：golang redis 事务 multi exec 使用，Redis 事务 multi exec 实现批量命令原子执行，理解 redis 事务隔离特性。
 | 原文链接：http://wiki.gzyx8e.asia/arts/907925.Doc

原标题：架构复盘：服务优雅停机架构设计资源释放
简介：nodejs 流处理大文件不占内存，使用 Node.js 流处理超大文件，边读边写，不需要全部加载进内存。
 | 原文链接：http://wiki.gzyx8e.asia/arts/999332.Doc

原标题：OpenSource：大型仓库Git历史清理瘦身实操
简介：golang go xml 解析生成 xml 文档，encoding/xml 解析 xml，结构体标签映射 xml 节点属性。
 | 原文链接：http://wiki.gzyx8e.asia/arts/825030.Doc

原标题：端口占用释放资源重启服务
简介：nodejs 跨域中间件配置细节，Express 跨域中间件配置细节，处理预检请求，修复偶现跨域失效。
 | 原文链接：http://wiki.gzyx8e.asia/arts/129477.Doc

原标题：踩坑记录：端口被占用导致服务启动失败
简介：Docker 容器入门镜像实操教程，介绍 Docker 基础概念，演示镜像拉取、容器启停，帮助新手建立容器化开发认知。
 | 原文链接：http://wiki.gzyx8e.asia/arts/481181.Doc

原标题：优化实践：接口批量合并减少网络请求次数
简介：前端下载导出文件功能实现，前端实现文件流下载导出，处理异常，适配浏览器不同下载行为。
 | 原文链接：http://wiki.gzyx8e.asia/arts/019155.Doc

原标题：Git 分支切换合并删除完整操作
简介：golang 命令行交互 cobra 开发 cli，cobra 库开发功能完善命令行工具，子命令参数标志解析。
 | 原文链接：http://wiki.gzyx8e.asia/arts/868441.Doc

原标题：golang 系统设计传输加密 tls 配置要点
简介：golang go regexp 正则预编译，regexp.MustCompile 预编译正则，不要循环内部编译正则，节省 CPU。
 | 原文链接：http://wiki.gzyx8e.asia/arts/690700.Doc

原标题：Debug：并发场景下数据覆盖丢失问题定位
简介：golang go 程序版本号内置编译注入，编译时注入 git commit 版本号，程序运行输出版本便于排查。
 | 原文链接：http://wiki.gzyx8e.asia/arts/131225.Doc

原标题：golang k8s 命名空间资源隔离方案
简介：golang 日志按日期切割实现方案，实现日志文件按天切割，自动归档旧日志，防止单个日志文件过大。
 | 原文链接：http://wiki.gzyx8e.asia/arts/000704.Doc

原标题：从零搭建本地开发环境完整教程
简介：golang sync.Cond 条件变量使用，Cond 条件变量协程等待唤醒，复杂并发同步场景。
 | 原文链接：http://wiki.gzyx8e.asia/arts/712730.Doc

原标题：golang es 索引生命周期管理思路
简介：手写简易 MQ 理解消息存储消费，手写极简消息队列 Demo，理解消息存储、投递、消费完整流程。
 | 原文链接：http://wiki.gzyx8e.asia/arts/061301.Doc

原标题：DevOps：Docker镜像安全扫描集成CI流程
简介：golang go 测试 t.Run 子测试分组，t.Run 实现子测试，分组执行用例，输出分组测试结果。
 | 原文链接：http://wiki.gzyx8e.asia/arts/561377.Doc

原标题：入门实践：Git分支创建切换合并完整演示
简介：日志驱动异常日志不输出修复，排查日志驱动配置，修复日志写入配置，恢复程序正常日志输出。
 | 原文链接：http://wiki.gzyx8e.asia/arts/077146.Doc

原标题：golang 系统设计字段命名类型选择最佳实践
简介：golang sftp 文件上传下载操作，sftp 协议远程文件上传下载，实现服务器之间文件传输功能。
 | 原文链接：http://wiki.gzyx8e.asia/arts/489181.Doc

原标题：开发记录：批量接口请求并发控制实践
简介：golang base64 编码解码实操，Go Base64 编码解码示例，处理业务场景 Base64 格式数据转换。
 | 原文链接：http://wiki.gzyx8e.asia/arts/363140.Doc

原标题：安全复盘：Redis未授权访问漏洞防护
简介：CLI 批量处理工具文件操作开发，开发命令行批量工具，实现批量文件处理，提升重复文件处理效率。
 | 原文链接：http://wiki.gzyx8e.asia/arts/748652.Doc

原标题：架构笔记：分库分表中间件选型业务约束
简介：golang 分布式唯一 id 多种方案对比，雪花、redis、uuid 对比各方案优缺点，指导业务选型使用。
 | 原文链接：http://wiki.gzyx8e.asia/arts/005820.Doc

原标题：golang 系统设计 jmeter 简单压测脚本编写
简介：golang 处理连接被重置 reset 错误，识别 connection reset by peer，对端关闭连接异常处理逻辑。
 | 原文链接：http://wiki.gzyx8e.asia/arts/419117.Doc

原标题：缓存过期打散防止缓存雪崩
简介：golang staticcheck 静态代码分析，staticcheck 深度静态检查，发现代码错误、性能问题、风格问题。
 | 原文链接：http://wiki.gzyx8e.asia/arts/335995.Doc

原标题：环境变量不生效问题修复
简介：golang 文件上传下载接口开发，Go 开发文件上传下载接口，校验文件，处理文件读写存储逻辑。
 | 原文链接：http://wiki.gzyx8e.asia/arts/759448.Doc

原标题：复盘总结：缓存改造业务落地踩坑复盘
简介：批量数据处理脚本编写技巧，编写脚本批量处理大量业务数据，循环处理、分批执行，提升数据处理效率。
 | 原文链接：http://wiki.gzyx8e.asia/arts/921669.Doc

原标题：记一次本地运行正常，线上环境报错诡异问题
简介：golang go cover 覆盖率报告生成，go test‑cover 生成测试覆盖率，html 可视化查看未覆盖代码行。
 | 原文链接：http://wiki.gzyx8e.asia/arts/452053.Doc

原标题：ICMP 放通网络丢包问题修复
简介：golang 优雅关闭 grpc 服务示例，gRPC 服务优雅关闭，等待现有请求处理完成再停止服务。
 | 原文链接：http://wiki.gzyx8e.asia/arts/554224.Doc

原标题：golang 系统设计告警升级通知策略配置思路
简介：Spring 事务传播机制配置生效，理解事务传播行为，正确配置，修复事务不生效、事务失效的业务 bug。
 | 原文链接：http://wiki.gzyx8e.asia/arts/425530.Doc

原标题：架构笔记：业务操作审计日志系统架构设计
简介：RPC 接口字段增减兼容处理，RPC 接口新增删除字段做好向前兼容，老版本服务不会解析报错崩溃。
 | 原文链接：http://wiki.gzyx8e.asia/arts/263886.Doc

原标题：踩坑：Docker容器内时区不一致引发的时间BUG
简介：服务熔断防止故障级联传播，实现服务熔断逻辑，下游故障时快速失败，阻止故障向上游链式扩散。
 | 原文链接：http://wiki.gzyx8e.asia/arts/418697.Doc

原标题：Architecture：文件处理服务架构大文件内存规避
简介：golang 容器信号转发处理问题修复，docker/k8s 正确转发 SIGTERM 信号，保证 go 程序收到信号优雅退出。
 | 原文链接：http://wiki.gzyx8e.asia/arts/967063.Doc

原标题：Troubleshoot：批量导入数据，事务过大回滚日志暴涨
简介：golang 协程泄露问题排查方法，识别 Go 协程泄露现象，分析泄露场景，给出排查定位协程泄露手段。
 | 原文链接：http://wiki.gzyx8e.asia/arts/268876.Doc

原标题：golang mysql innodb 事务隔离级别
简介：golang 数据库分表策略按时间分片，按时间维度分表，历史数据拆分，单表数据量控制保证查询性能。
 | 原文链接：http://wiki.gzyx8e.asia/arts/926951.Doc

原标题：设计思考：系统降级开关架构设计快速切流量
简介：golang 布隆过滤器实现去重，Go 实现布隆过滤器，海量数据去重，节省内存开销，提升判断效率。
 | 原文链接：http://wiki.gzyx8e.asia/arts/537547.Doc

原标题：golang es 聚合统计查询实现
简介：golang go test 单元测试命令参数详解，gotest 参数覆盖率，指定测试用例，跳过测试，单元测试命令实操。
 | 原文链接：http://wiki.gzyx8e.asia/arts/727651.Doc

原标题：golang 系统设计 mq 消息顺序性保证思路
简介：DNS TTL 配置域名切换生效，调整 DNS 解析 TTL，缩短缓存时间，域名变更后可以快速全网生效。
 | 原文链接：http://wiki.gzyx8e.asia/arts/827639.Doc

原标题：前端骨架屏提升页面体验
简介：Git commit 钩子提交规范校验，配置 Git 提交钩子，提交代码自动校验提交信息格式，规范提交记录。
 | 原文链接：http://wiki.gzyx8e.asia/arts/574794.Doc

原标题：golang 系统设计架构图绘图工具选型对比
简介：golang goroutine 泄露常见场景汇总，channel 阻塞、context 忘记取消，导致协程无法退出发生泄露。
 | 原文链接：http://wiki.gzyx8e.asia/arts/293408.Doc

原标题：golang mysql 防止 sql 注入实践
简介：预编译 SQL 防注入实现，使用预编译 SQL 方式，杜绝 SQL 注入风险，提升数据库访问层安全能力。
 | 原文链接：http://wiki.gzyx8e.asia/arts/938461.Doc

原标题：开发记录：JWT过期刷新滑动过期实现实践
简介：golang go 模板执行错误捕获，捕获模板执行错误，防止模板错误直接返回空白页面。
 | 原文链接：http://wiki.gzyx8e.asia/arts/337927.Doc

原标题：golang docker 部署 mysql 注意事项
简介：网络读取超时设置连接挂起防护，设置网络读取超时时间，防止请求无限挂起不返回，占用连接资源。
 | 原文链接：http://wiki.gzyx8e.asia/arts/079295.Doc

四、架构设计｜Architecture
原标题：Hands‑on：简易图片压缩处理服务demo
简介：本地简易配置中心动态管理，搭建轻量本地配置中心，业务动态读取配置，修改配置不重启服务。
 | 原文链接：http://wiki.gzyx8e.asia/arts/442009.Doc

原标题：架构笔记：分布式事务方案对比与业务取舍
简介：golang 服务注册 etcd 简单示例，etcd 实现服务注册发现，微服务实例注册元数据，客户端发现节点。
 | 原文链接：http://wiki.gzyx8e.asia/arts/345336.Doc

原标题：快速上手简单性能监控指标查看
简介：golang init 函数合理使用边界，少用 init，优先显式调用初始化，便于控制初始化时机。
 | 原文链接：http://wiki.gzyx8e.asia/arts/050518.Doc

原标题：golang 系统设计日志采样降低存储开销方案
简介：Nginx 反向代理路由配置实战，配置 Nginx 反向代理，实现请求转发、路由分发，掌握 Nginx 基础配置能力。
 | 原文链接：http://wiki.gzyx8e.asia/arts/804709.Doc

原标题：golang 系统设计 canary 金丝雀部署实操
简介：golang sql 注入风险规避要点，参数化查询杜绝 sql 注入，禁止字符串拼接 SQL 语句执行。
 | 原文链接：http://wiki.gzyx8e.asia/arts/553152.Doc

原标题：golang 系统设计自动化测试 ci 流水线集成实操
简介：golang os 文件权限 mode，os.FileMode 文件权限，读写执行权限位，跨平台权限注意事项。
 | 原文链接：http://wiki.gzyx8e.asia/arts/062727.Doc

原标题：golang 系统设计基准测试 benchmark 编写
简介：浏览器缓存强制刷新方案，设置 HTTP 缓存头，处理浏览器缓存旧静态资源，让用户加载更新后的页面。
 | 原文链接：http://wiki.gzyx8e.asia/arts/338651.Doc

原标题：开发记录：分布式锁超时业务安全处理实践
简介：golang go 模板缓存预编译模板，预编译 html 模板，程序启动加载，避免每次请求解析模板损耗性能。
 | 原文链接：http://wiki.gzyx8e.asia/arts/370559.Doc

原标题：golang k8s 本地 minikube 调试应用
简介：WebSocket 聊天室实时通讯开发，基于 WebSocket 搭建简易聊天室，实现多人消息广播实时聊天效果。
 | 原文链接：http://wiki.gzyx8e.asia/arts/090750.Doc

原标题：golang minio 存储桶权限管控配置
简介：golang go 基准测试 benchmark 编写，Benchmark 性能基准测试，测量函数执行耗时内存分配情况。
 | 原文链接：http://wiki.gzyx8e.asia/arts/221784.Doc

原标题：安全实践：API密钥管理轮换最佳实践
简介：golang k8s secret 敏感配置加载，加载 k8s secret 存储密钥密码，敏感信息不存放配置文件。
 | 原文链接：http://wiki.gzyx8e.asia/arts/286166.Doc

原标题：golang 分布式锁防死锁处理
简介：批量数据处理脚本编写技巧，编写脚本批量处理大量业务数据，循环处理、分批执行，提升数据处理效率。
 | 原文链接：http://wiki.gzyx8e.asia/arts/162569.Doc

原标题：Git 分支管理多人协作实战教程
简介：golang grafana 面板 go 业务指标可视化，prometheus 指标对接 grafana，配置监控面板可视化业务状态。
 | 原文链接：http://wiki.gzyx8e.asia/arts/486842.Doc

原标题：Debug：表单提交特殊字符造成接口解析失败
简介：golang 静态编译缩小镜像体积，Go 程序静态编译，不依赖系统库，产出单二进制文件，缩小镜像。
 | 原文链接：http://wiki.gzyx8e.asia/arts/456256.Doc

原标题：JWT 工具封装令牌刷新过期
简介：golang 消息队列实现事务消息方案，基于 kafka 实现事务消息，业务执行成功才对外投递消息。
 | 原文链接：http://wiki.gzyx8e.asia/arts/612130.Doc

原标题：设计思考：消息队列重复消费架构层防御手段
简介：开源项目构建失败排查步骤，梳理构建报错排查流程，从依赖、网络、权限、脚本多角度定位项目构建失败原因。
 | 原文链接：http://wiki.gzyx8e.asia/arts/337905.Doc

原标题：项目依赖安全扫描漏洞防范
简介：依赖安装失败全方位排错，从网络、镜像源、权限、版本多角度，定位依赖安装失败，给出对应修复手段。
 | 原文链接：http://wiki.gzyx8e.asia/arts/413587.Doc

原标题：golang 系统设计故障定位排查通用步骤方法论
简介：golang go 死锁检测工具，静态检查、运行检测，发现 channel 锁导致死锁问题。
 | 原文链接：http://wiki.gzyx8e.asia/arts/233107.Doc

?
