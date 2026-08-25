最新前沿技术资讯

一、入门教程｜Getting Started
原标题：Debug：序列化反序列化版本不一致解析失败
简介：golang 子进程执行命令标准流处理，exec.Command 执行外部命令，处理 stdout stderr，防止缓冲区阻塞卡死。
 | 原文链接：http://book.tnxmpb.asia/blog/8652175.sHtML

原标题：Issue复现：内存泄漏定位完整复盘记录
简介：静态资源 404 路径打包修复，修复打包后静态资源访问 404，调整资源输出路径，保证资源正常加载。
 | 原文链接：http://book.tnxmpb.asia/blog/0020558.sHtML

原标题：golang 单元测试 table‑driven
简介：golang go panic 合理使用边界，panic 只用于不可恢复程序错误，业务逻辑禁止直接 panic。
 | 原文链接：http://book.tnxmpb.asia/blog/2124654.sHtML

原标题：网络读取超时设置连接挂起防护
简介：布隆过滤器误判问题修正，调整布隆过滤器参数，降低误判概率，保证业务去重逻辑准确。
 | 原文链接：http://book.tnxmpb.asia/blog/0544450.sHtML

原标题：从零搭建简单的健康检查接口示例
简介：接口幂等性防重复请求实现，实现接口幂等逻辑，避免重复提交请求产生多条脏数据，保障业务数据安全。
 | 原文链接：http://book.tnxmpb.asia/blog/4350508.sHtML

原标题：开源实践：Fork上游项目，持续同步更新代码
简介：golang errgroup 协程组错误处理，errgroup 捕获协程错误，context 取消剩余协程，简化并发任务。
 | 原文链接：http://book.tnxmpb.asia/blog/1309315.sHtML

原标题：方案对比：RPC、HTTP、gRPC场景选型分析
简介：WSL 文件权限访问异常修复，处理 WSL 环境文件权限错乱，调整权限配置，实现文件正常读写访问。
 | 原文链接：http://book.tnxmpb.asia/blog/5750796.sHtML

原标题：golang 系统设计磁盘满故障应急处理步骤
简介：golang 故障演练服务模拟超时报错，程序模拟接口超时、报错，做混沌测试验证熔断降级有效性。
 | 原文链接：http://book.tnxmpb.asia/blog/3176262.sHtML

原标题：限流窗口绕过漏洞修复方案
简介：内网 DNS 不稳定随机报错排查，定位内网 DNS 抖动问题，配置备选 DNS，解决偶现域名解析失败。
 | 原文链接：http://book.tnxmpb.asia/blog/9397702.sHtML

原标题：零基础理解模块化与组件化基础思想
简介：golang 文件句柄耗尽排查处理，统计进程打开文件句柄，找到未关闭文件，修复句柄泄漏问题。
 | 原文链接：http://book.tnxmpb.asia/blog/6195213.sHtML

原标题：DevOps：GitLabCI完整流水线配置示例
简介：golang go 爬虫异步并发抓取，协程池控制并发抓取网页，多协程采集，提升爬虫采集速度。
 | 原文链接：http://book.tnxmpb.asia/blog/0177668.sHtML

原标题：golang 系统设计 rest 状态码合理使用指南
简介：golang channel 通道并发处理，讲解 Channel 用法，协程之间通过通道传递数据，做并发同步控制。
 | 原文链接：http://book.tnxmpb.asia/blog/4250577.sHtML

原标题：快速上手单元测试，写出第一个测试用例
简介：前端国际化多语言方案落地，搭建前端多语言国际化方案，切换语言，页面文本自动切换对应语种。
 | 原文链接：http://book.tnxmpb.asia/blog/9879832.sHtML

原标题：Practice：实现接口mock动态返回不同响应
简介：golang 数据库连接泄露排查，定位 Go 数据库连接泄露，连接没有归还池，导致连接耗尽报错。
 | 原文链接：http://book.tnxmpb.asia/blog/0871097.sHtML

原标题：踩坑：环境变量未生效导致线上配置错乱
简介：golang panic 崩溃日志完整收集，捕获所有 panic，打印堆栈，记录日志，方便定位崩溃根源。
 | 原文链接：http://book.tnxmpb.asia/blog/7761502.sHtML

原标题：golang 系统设计 docker compose 本地开发环境搭建
简介：golang 雪花算法 workId 自动获取，自动获取机器 workId，不用手动配置，简化分布式 id 部署。
 | 原文链接：http://book.tnxmpb.asia/blog/0390262.sHtML

原标题：踩坑记录：浮点精度错误造成业务计算错误
简介：golang 容器内读取 k8s 配置 configmap，程序读取 k8s configmap 配置，配置与镜像分离便于运维。
 | 原文链接：http://book.tnxmpb.asia/blog/6164762.sHtML

原标题：布隆过滤器误判问题修正
简介：缓存过期打散防止缓存雪崩，对缓存过期时间增加随机偏移，避免大量缓存同时失效引发缓存雪崩。
 | 原文链接：http://book.tnxmpb.asia/blog/9527874.sHtML

原标题：Practice：实现异步回调处理通用组件封装
简介：golang go 单二进制文件静态编译交叉编译，交叉编译不同操作系统架构二进制文件，实现一次编译多平台运行。
 | 原文链接：http://book.tnxmpb.asia/blog/9806691.sHtML

原标题：设计思考：系统容量评估架构前期估算思路
简介：MySQL 慢查询索引优化实战，抓取慢查询 SQL，分析执行计划，新增或者调整索引，提升 SQL 执行速度。
 | 原文链接：http://book.tnxmpb.asia/blog/5943134.sHtML

原标题：Redis 内存淘汰策略数据防丢失
简介：golang grpc 客户端流上传数据，客户端流式请求，客户端分批上传数据到服务端，适合大文件传输。
 | 原文链接：http://book.tnxmpb.asia/blog/5161441.sHtML

原标题：golang ci 流水线单元测试集成测试
简介：golang go list 双向链表使用，container/list 双向链表，频繁增删节点业务场景使用。
 | 原文链接：http://book.tnxmpb.asia/blog/9007988.sHtML

原标题：文件句柄耗尽资源泄露处理
简介：golang bytes.Buffer 字节缓冲区使用，bytes.Buffer 字节内存缓冲区，拼接字节，避免频繁内存分配。
 | 原文链接：http://book.tnxmpb.asia/blog/7271581.sHtML

原标题：golang redis 批量 pipeline 实践
简介：项目语义化版本号规范管理，遵循语义化版本规范管理项目版本，明确主次版本变更含义。
 | 原文链接：http://book.tnxmpb.asia/blog/4271494.sHtML

原标题：golang consul 服务发现简单示例
简介：golang goroutine 池任务调度，实现 goroutine 池，复用协程，频繁任务场景减少协程创建销毁开销。
 | 原文链接：http://book.tnxmpb.asia/blog/0970712.sHtML

原标题：golang minio 分片上传断点续传
简介：调试工具断点调试变量查看技巧，演示断点设置、变量监视、调用栈查看，借助调试工具高效排查业务逻辑错误。
 | 原文链接：http://book.tnxmpb.asia/blog/6621688.sHtML

原标题：实战项目：WebSocket消息广播房间分组实践
简介：依赖版本冲突兼容修复方案，定位依赖版本冲突根源，通过版本约束、替换包，解决版本不兼容运行报错。
 | 原文链接：http://book.tnxmpb.asia/blog/9388212.sHtML

原标题：golang 系统设计排行榜几种实现
简介：golang gorm 索引设置与优化技巧，定义数据库索引，理解索引生效条件，避免索引失效慢查询。
 | 原文链接：http://book.tnxmpb.asia/blog/2728622.sHtML

原标题：设计思考：容器化业务应用架构改造要点
简介：golang goroutine 协程基础实操，Goroutine 基础实操案例，启动协程执行任务，理解轻量级协程特性。
 | 原文链接：http://book.tnxmpb.asia/blog/8276901.sHtML

原标题：实战：基于DockerCompose搭建本地开发栈
简介：JWT 工具封装令牌刷新过期，封装 JWT 工具类，实现令牌生成、校验、过期刷新整套令牌管理逻辑。
 | 原文链接：http://book.tnxmpb.asia/blog/3463958.sHtML

原标题：实践：分布式事务本地模拟验证实践
简介：动态定时任务业务调度实现，实现可以动态增删启停定时任务，无需重启服务调整调度任务。
 | 原文链接：http://book.tnxmpb.asia/blog/6645510.sHtML

原标题：golang 系统设计开源 pr 评审合并流程实操
简介：nestjs 框架模块化项目搭建，从零搭建 NestJS 项目，模块化拆分业务，搭建规范后端项目骨架。
 | 原文链接：http://book.tnxmpb.asia/blog/0874231.sHtML

原标题：macOS 脚本执行权限开启
简介：golang testing.TB Helper 标记辅助函数，t.Helper 标记辅助函数，报错打印真实调用位置。
 | 原文链接：http://book.tnxmpb.asia/blog/0286368.sHtML

原标题：语义化版本依赖管理防错乱
简介：golang http 中间件洋葱模型原理，理解 go http 中间件洋葱模型，请求响应流转顺序，编写自定义中间件。
 | 原文链接：http://book.tnxmpb.asia/blog/9187273.sHtML

原标题：开发记录：业务错误告警邮件通知组件实践
简介：golang testify mock 模拟接口，mock 接口生成 mock 对象，单元测试模拟外部依赖行为。
 | 原文链接：http://book.tnxmpb.asia/blog/1937075.sHtML

原标题：golang 系统设计分表分页排序业务实现难点
简介：golang 图片处理 go 图片裁剪压缩，golang 图像处理库，图片缩放裁剪水印，服务端图片处理。
 | 原文链接：http://book.tnxmpb.asia/blog/9521757.sHtML

原标题：优化实践：序列化框架性能对比选型实践
简介：golang go 单二进制文件静态编译交叉编译，交叉编译不同操作系统架构二进制文件，实现一次编译多平台运行。
 | 原文链接：http://book.tnxmpb.asia/blog/3175216.sHtML

原标题：移动端适配 rem vw 方案对比
简介：golang sort 切片排序自定义 less，sort.Slice 切片快速排序，自定义 less 函数实现业务排序。
 | 原文链接：http://book.tnxmpb.asia/blog/1426278.sHtML

原标题：golang 系统设计 p0 故障复盘方法论讲解
简介：Git commit 钩子提交规范校验，配置 Git 提交钩子，提交代码自动校验提交信息格式，规范提交记录。
 | 原文链接：http://book.tnxmpb.asia/blog/5225043.sHtML

原标题：实践：接口参数自动校验业务落地实践
简介：golang 数据库连接池参数调优详解，最大连接空闲连接最大生命周期，结合业务合理配置避免资源浪费。
 | 原文链接：http://book.tnxmpb.asia/blog/7189800.sHtML


二、踩坑排错｜Troubleshooting
原标题：golang 系统设计服务优雅停机完整流程
简介：golang gin 获取客户端真实 IP，多层代理场景正确拿到用户真实访问 IP，避免拿到网关代理内网地址。
 | 原文链接：http://book.tnxmpb.asia/blog/6742401.sHtML

原标题：接口签名校验防篡改实现
简介：golang go‑zero 中间件鉴权限流，go‑zero 自定义中间件，实现鉴权、限流、日志打印通用能力。
 | 原文链接：http://book.tnxmpb.asia/blog/2321839.sHtML

原标题：golang 系统设计压测工具 wrk 使用实操
简介：golang go yaml 解析自定义类型，yaml 自定义序列化，时间、特殊类型自定义解析逻辑。
 | 原文链接：http://book.tnxmpb.asia/blog/1135229.sHtML

原标题：golang mysql limit 大分页优化
简介：TCP 心跳检测清理僵死连接，开启 TCP 心跳机制，自动清理僵死无效连接，释放连接资源。
 | 原文链接：http://book.tnxmpb.asia/blog/2364411.sHtML

原标题：入门实践：本地简单代理服务搭建
简介：golang yaml 解析配置加载实操，Go 解析 YAML 配置文件，读取配置参数，驱动业务运行。
 | 原文链接：http://book.tnxmpb.asia/blog/8483684.sHtML

原标题：开发记录：表单文件类型校验后端安全校验实践
简介：模拟登录鉴权权限判断示例，实现简易登录流程，会话状态维护，完成接口权限校验，理解身份鉴权基础逻辑。
 | 原文链接：http://book.tnxmpb.asia/blog/2431075.sHtML

原标题：golang 系统设计分布式锁可重入实现思路
简介：golang go url url.Values 参数编码，url.Values 构建 url 查询参数，自动处理参数 url 编码。
 | 原文链接：http://book.tnxmpb.asia/blog/3008953.sHtML

原标题：golang 系统设计服务优雅停机完整流程
简介：开源项目构建失败排查步骤，梳理构建报错排查流程，从依赖、网络、权限、脚本多角度定位项目构建失败原因。
 | 原文链接：http://book.tnxmpb.asia/blog/9573164.sHtML

原标题：golang 分库分表简单路由实现
简介：golang tcp keepalive 参数程序配置，go 程序设置 tcp keepalive，操作系统 tcp 保活参数，清理僵死连接。
 | 原文链接：http://book.tnxmpb.asia/blog/4948725.sHtML

原标题：golang 系统设计传输加密 tls 配置要点
简介：golang gorm select 指定查询字段，指定查询字段，避免查询全部字段，减少数据传输，提升查询性能。
 | 原文链接：http://book.tnxmpb.asia/blog/8029750.sHtML

原标题：快速上手简单信号处理脚本编写
简介：golang testify mock 模拟接口，mock 接口生成 mock 对象，单元测试模拟外部依赖行为。
 | 原文链接：http://book.tnxmpb.asia/blog/6147457.sHtML

原标题：golang 系统设计代码仓库权限管理方案
简介：golang go 二进制安全 strip 减小体积，strip 剥离二进制调试符号，缩小程序二进制文件体积。
 | 原文链接：http://book.tnxmpb.asia/blog/5307063.sHtML

原标题：golang 单元测试 mock http 请求
简介：golang go regexp 正则预编译，regexp.MustCompile 预编译正则，不要循环内部编译正则，节省 CPU。
 | 原文链接：http://book.tnxmpb.asia/blog/6303923.sHtML

原标题：golang 系统设计并发控制协程池任务池实现
简介：开发环境变量配置全平台教程，区分 Windows、macOS、Linux 系统，讲解环境变量配置、加载优先级与常见失效原因。
 | 原文链接：http://book.tnxmpb.asia/blog/5337616.sHtML

原标题：golang 系统设计熔断降级架构讲解
简介：golang 数据库连接泄露排查，定位 Go 数据库连接泄露，连接没有归还池，导致连接耗尽报错。
 | 原文链接：http://book.tnxmpb.asia/blog/4882501.sHtML

原标题：golang 系统设计本地缓存与分布式缓存
简介：golang go‑zero rpc 微服务开发，go‑zero 定义 proto，生成 rpc 服务代码，实现微服务调用。
 | 原文链接：http://book.tnxmpb.asia/blog/3283723.sHtML

原标题：golang docker compose 环境变量
简介：golang hystrix 模式简易熔断实现，简易熔断组件，错误率达到阈值触发熔断，快速失败保护下游。
 | 原文链接：http://book.tnxmpb.asia/blog/9854255.sHtML

原标题：复盘总结：缓存改造业务落地踩坑复盘
简介：本地简易配置中心动态管理，搭建轻量本地配置中心，业务动态读取配置，修改配置不重启服务。
 | 原文链接：http://book.tnxmpb.asia/blog/7000722.sHtML

原标题：安全复盘：业务数据脱敏防止泄露实践
简介：前端图片懒加载性能优化，实现图片懒加载，页面可视区域才加载图片，减少页面初始网络请求。
 | 原文链接：http://book.tnxmpb.asia/blog/5653541.sHtML

原标题：开发复盘：大事务拆分优化业务性能实践
简介：git stash 代码暂存切换分支，使用 stash 暂存未提交代码，切换其他分支处理紧急任务，再恢复原有工作进度。
 | 原文链接：http://book.tnxmpb.asia/blog/0539854.sHtML

原标题：golang 系统设计 grpc http2 多路复用讲解
简介：请求工具封装统一异常处理，对网络请求做二次封装，统一捕获各类请求异常，标准化接口返回格式。
 | 原文链接：http://book.tnxmpb.asia/blog/1324214.sHtML

原标题：golang lru 缓存淘汰算法编写
简介：分布式锁失效问题排查修复，分析分布式锁失效场景，修复锁超时、续期问题，保证锁逻辑可靠。
 | 原文链接：http://book.tnxmpb.asia/blog/3238908.sHtML

原标题：运维笔记：服务器Swap分区调优生产实践
简介：golang go race 竞态检测工具，‑race 检测数据竞争，编译运行检测并发读写数据竞争 bug。
 | 原文链接：http://book.tnxmpb.asia/blog/1595611.sHtML

原标题：golang redis 大 key 识别处理方案
简介：K8s 镜像拉取网络故障修复，排查 K8s 集群镜像拉取网络问题，配置镜像源，恢复镜像正常拉取。
 | 原文链接：http://book.tnxmpb.asia/blog/7947129.sHtML

原标题：架构复盘：热点数据防护架构防止节点过载
简介：无用对象回收抑制内存上涨，优化对象生命周期，及时释放不再使用对象，抑制内存持续不断增长。
 | 原文链接：http://book.tnxmpb.asia/blog/6847422.sHtML

原标题：golang redis 分布式计数器开发
简介：golang 配置文件多环境加载，Go 多环境配置加载实现，读取配置文件环境变量，适配多套运行环境。
 | 原文链接：http://book.tnxmpb.asia/blog/1759147.sHtML

原标题：golang 系统设计 protobuf 命名规范最佳实践
简介：golang 压缩 zip 文件生成解压，golang 实现 zip 压缩打包，解压 zip 归档文件，处理批量文件归档。
 | 原文链接：http://book.tnxmpb.asia/blog/8272909.sHtML

原标题：golang 系统设计 ide 配置 go 开发效率提升技巧
简介：golang 程序崩溃 core dump 生成调试，开启 core dump，程序崩溃生成转储文件，事后分析崩溃原因。
 | 原文链接：http://book.tnxmpb.asia/blog/5324002.sHtML

原标题：安全复盘：日志打印敏感信息泄露治理
简介：golang systemd 配置 go 服务部署，编写 systemd unit 文件管理 go 服务，开机自启、崩溃自动重启。
 | 原文链接：http://book.tnxmpb.asia/blog/7282860.sHtML

原标题：接口签名验签完整安全方案
简介：golang go‑zero 分布式锁组件使用，go‑zero 内置 redis 分布式锁，业务直接调用实现并发控制。
 | 原文链接：http://book.tnxmpb.asia/blog/8800543.sHtML

原标题：踩坑记录：UTC时间与本地时间混用逻辑错乱
简介：golang 容器内读取 k8s 配置 configmap，程序读取 k8s configmap 配置，配置与镜像分离便于运维。
 | 原文链接：http://book.tnxmpb.asia/blog/7447513.sHtML

原标题：新手向：Mac/Windows开发环境差异踩坑
简介：golang redis lua 脚本原子操作，使用 Lua 脚本实现原子逻辑，减少网络往返，保障多命令原子执行。
 | 原文链接：http://book.tnxmpb.asia/blog/8372716.sHtML

原标题：踩坑：Docker容器内时区不一致引发的时间BUG
简介：golang http 服务优雅关闭完整示例，接收终止信号，停止接收新请求，等待现有请求处理完毕后退出服务。
 | 原文链接：http://book.tnxmpb.asia/blog/4989325.sHtML

原标题：Hands‑on：代码生成器，一键生成CRUD模板
简介：golang sync.RWMutex 读写锁使用场景，读多写少场景读写锁，读共享写互斥，提升并发性能。
 | 原文链接：http://book.tnxmpb.asia/blog/4812063.sHtML

原标题：入门实践：本地简单代理服务搭建
简介：任务执行锁防止并发重复调度，增加任务执行锁，多实例环境，防止同一个定时任务并发多次运行。
 | 原文链接：http://book.tnxmpb.asia/blog/5314727.sHtML

原标题：多线程线程安全脏数据规避
简介：内网 DNS 不稳定随机报错排查，定位内网 DNS 抖动问题，配置备选 DNS，解决偶现域名解析失败。
 | 原文链接：http://book.tnxmpb.asia/blog/8055461.sHtML

原标题：新手向：开源项目依赖安装失败排查
简介：golang 空接口 interface {} 类型处理，interface {} 存储任意类型，类型转换，处理泛型之前通用数据。
 | 原文链接：http://book.tnxmpb.asia/blog/3837499.sHtML

原标题：设计思考：防雪崩，系统过载保护架构设计
简介：golang nilnil interface 陷阱复现，interface 包含类型不为 nil 值为 nil，判 ==nil 返回 false 经典坑。
 | 原文链接：http://book.tnxmpb.asia/blog/1577455.sHtML

原标题：golang 配置热更新不重启服务
简介：golang go decimal 定点小数金额计算，decimal 库处理金额，规避 float64 精度丢失，财务计算。
 | 原文链接：http://book.tnxmpb.asia/blog/7017180.sHtML

原标题：golang 系统设计 ci 流水线安全管控思路
简介：短信服务封装失败自动重试，封装短信发送组件，处理发送失败自动重试，兼容多短信服务商。
 | 原文链接：http://book.tnxmpb.asia/blog/0436845.sHtML

三、实战开发｜Practice
原标题：代码格式化工具团队统一风格
简介：布隆过滤器误判问题修正，调整布隆过滤器参数，降低误判概率，保证业务去重逻辑准确。
 | 原文链接：http://book.tnxmpb.asia/blog/9700483.sHtML

原标题：golang 系统设计 mq 消息积压解决方案
简介：golang grpc 服务端流推送数据，服务端流式响应，服务端持续向客户端推送多条响应消息。
 | 原文链接：http://book.tnxmpb.asia/blog/3055431.sHtML

原标题：实践：OpenAPI自动生成接口文档完整实践
简介：golang go 并发模式 fan‑out fan‑in，fanout 分发任务 fanin 汇总结果，多协程并发处理任务。
 | 原文链接：http://book.tnxmpb.asia/blog/2757003.sHtML

原标题：Git 代码冲突正确处理方式
简介：golang gorm 子查询嵌套查询写法，Gorm 实现子查询、嵌套查询，复杂条件查询简化代码编写。
 | 原文链接：http://book.tnxmpb.asia/blog/8109503.sHtML

原标题：WSL 文件权限访问异常修复
简介：golang http.Server 配置参数详解，ReadTimeout WriteTimeout IdleTimeout，全方位防护慢请求攻击。
 | 原文链接：http://book.tnxmpb.asia/blog/9115609.sHtML

原标题：踩坑记录：分页逻辑错误造成数据重复输出
简介：nodejs 全局异常捕获进程防护，捕获未捕获异常与 Promise 拒绝，尽量保护进程不因为异常直接退出。
 | 原文链接：http://book.tnxmpb.asia/blog/3581630.sHtML

原标题：设计思考：系统容量评估架构前期估算思路
简介：golang 信号量控制并发数量，使用信号量控制并发，限制同时执行任务数量，保护下游资源。
 | 原文链接：http://book.tnxmpb.asia/blog/2481647.sHtML

原标题：golang 数据库慢查询监控实现
简介：异步任务堆积消费能力优化，处理消息任务堆积问题，提升消费处理速度，恢复队列正常处理水位。
 | 原文链接：http://book.tnxmpb.asia/blog/4575492.sHtML

原标题：golang k8s 网络策略网络隔离设置
简介：golang go 程序权限最小化运行，容器内使用普通用户运行程序，拒绝 root 运行提升安全等级。
 | 原文链接：http://book.tnxmpb.asia/blog/3770615.sHtML

原标题：golang mysql 存储过程简单使用
简介：GraphQL 接口查询优化实操，体验 GraphQL 查询方式，按需获取字段，减少冗余数据传输，优化接口请求效率。
 | 原文链接：http://book.tnxmpb.asia/blog/1501895.sHtML

原标题：Practice：实现业务唯一流水号生成组件实践
简介：golang go 测试文件命名规范，_test.go 测试文件，TestXxx 单元测试函数命名规范。
 | 原文链接：http://book.tnxmpb.asia/blog/2833203.sHtML

原标题：开发复盘：分库分表本地模拟与数据路由实践
简介：分布式锁失效问题排查修复，分析分布式锁失效场景，修复锁超时、续期问题，保证锁逻辑可靠。
 | 原文链接：http://book.tnxmpb.asia/blog/7042784.sHtML

原标题：新手指南：本地防火墙端口访问失败排查
简介：动态定时任务业务调度实现，实现可以动态增删启停定时任务，无需重启服务调整调度任务。
 | 原文链接：http://book.tnxmpb.asia/blog/3468163.sHtML

原标题：分布式 ID 生成器高并发实现
简介：gitignore 文件编写过滤规则，讲解 gitignore 语法，编写过滤配置，忽略缓存、编译产物、密钥文件，保持仓库整洁。
 | 原文链接：http://book.tnxmpb.asia/blog/9627732.sHtML

原标题：文件锁正确使用避免死锁
简介：golang 集成测试测试数据库回滚，集成测试结束自动回滚数据库，不污染测试环境数据。
 | 原文链接：http://book.tnxmpb.asia/blog/6456956.sHtML

原标题：架构复盘：业务系统中如何合理使用分库分表
简介：golang json 解析未知动态 json 结构，解析到 map [string] any 处理未知 json，动态读取字段。
 | 原文链接：http://book.tnxmpb.asia/blog/8641986.sHtML

原标题：golang 系统设计日志规范结构化日志落地
简介：golang delve 远程调试 go 线上程序，delve 远程调试，线上环境附加进程调试排查线上 bug。
 | 原文链接：http://book.tnxmpb.asia/blog/4885526.sHtML

原标题：golang 简易埋点日志上报实现
简介：golang strings.Builder 字符串高效拼接，strings.Builder 做字符串拼接，比 += 性能更高，减少内存拷贝。
 | 原文链接：http://book.tnxmpb.asia/blog/8454816.sHtML

原标题：golang 时间时区处理避坑指南
简介：ICMP 放通网络丢包问题修复，放开 ICMP 协议，解决 MTU 问题导致网络丢包，修复网络不稳定现象。
 | 原文链接：http://book.tnxmpb.asia/blog/2306065.sHtML

原标题：golang kafka 批量发送消费优化
简介：golang go 泛型实现通用数据结构，泛型实现通用栈队列，复用逻辑支持多种数据类型。
 | 原文链接：http://book.tnxmpb.asia/blog/6189878.sHtML

原标题：优化实践：分页查询性能优化解决offset问题
简介：golang defer 闭包变量捕获坑，defer 捕获循环变量引用，变量被复写，理解闭包变量捕获规则。
 | 原文链接：http://book.tnxmpb.asia/blog/7582671.sHtML

原标题：部署复盘：静态资源版本哈希缓存策略
简介：nodejs 项目 pm2 部署运维指南，使用 PM2 管理 Node 服务，进程守护、日志、重启，线上部署运维实操。
 | 原文链接：http://book.tnxmpb.asia/blog/2648920.sHtML

原标题：部署复盘：容器资源限制CPU内存配置实践
简介：golang go toml 配置注释保留，toml 解析保留注释，修改配置后写回保留原有注释。
 | 原文链接：http://book.tnxmpb.asia/blog/8278431.sHtML

原标题：golang redis 缓存预热实现思路
简介：文件分片上传断点续传功能，实现文件分片上传，记录上传进度，支持断点续传大文件上传。
 | 原文链接：http://book.tnxmpb.asia/blog/6737983.sHtML

原标题：Fork 开源项目同步上游代码
简介：golang http client 连接池调优，调优 Go HTTP Client 连接池参数，复用 TCP 连接，减少连接创建开销。
 | 原文链接：http://book.tnxmpb.asia/blog/3264689.sHtML

原标题：nestjs 框架模块化项目搭建
简介：golang toml 配置文件解析教程，Go 解析 Toml 格式配置，适用于项目配置管理场景。
 | 原文链接：http://book.tnxmpb.asia/blog/1983916.sHtML

原标题：golang 重试退避机制代码实现
简介：golang 定时任务 cron 使用指南，Go 使用 Cron 库实现定时任务，配置 corn 表达式调度业务任务。
 | 原文链接：http://book.tnxmpb.asia/blog/1018461.sHtML

原标题：项目实践：多租户数据隔离三种方案实操对比
简介：golang redis pipeline 与 txpipeline 区别，区分普通管道与事务管道，根据业务场景选择合适批量执行方案。
 | 原文链接：http://book.tnxmpb.asia/blog/5375505.sHtML

原标题：记一次分布式锁失效引发的数据错乱问题
简介：golang 配置中心 apollo go 客户端，apollo go sdk 读取配置，配置变更自动热更新无需重启服务。
 | 原文链接：http://book.tnxmpb.asia/blog/1794210.sHtML

原标题：golang 系统设计依赖版本升级风险评估
简介：文件读写与异常捕获代码示例，演示文件读取写入操作，增加异常捕获逻辑，规避文件不存在、权限不足导致崩溃。
 | 原文链接：http://book.tnxmpb.asia/blog/3405085.sHtML

原标题：Security：限流防爬虫防恶意攻击防护体系
简介：golang os 文件权限 mode，os.FileMode 文件权限，读写执行权限位，跨平台权限注意事项。
 | 原文链接：http://book.tnxmpb.asia/blog/7920086.sHtML

原标题：golang 系统设计错误码体系完整设计
简介：golang go 爬虫异步并发抓取，协程池控制并发抓取网页，多协程采集，提升爬虫采集速度。
 | 原文链接：http://book.tnxmpb.asia/blog/9251022.sHtML

原标题：时间精度统一业务判断修复
简介：golang systemd 配置 go 服务部署，编写 systemd unit 文件管理 go 服务，开机自启、崩溃自动重启。
 | 原文链接：http://book.tnxmpb.asia/blog/1001335.sHtML

原标题：golang 系统设计代码评审高效沟通原则思路
简介：golang 数据库连接耗尽排查思路，监控连接池状态，定位连接未归还，解决连接耗尽报错。
 | 原文链接：http://book.tnxmpb.asia/blog/0809113.sHtML

原标题：Practice：实现请求大小限制中间件防护大报文
简介：golang 单元测试 table‑driven，表格驱动单元测试写法，批量输入多组测试用例，简化单元测试代码。
 | 原文链接：http://book.tnxmpb.asia/blog/1667283.sHtML

原标题：golang redis 批量 pipeline 实践
简介：golang 模糊测试 go fuzz 基础编写，Fuzz 测试函数，自动生成随机输入，发现代码崩溃 panic。
 | 原文链接：http://book.tnxmpb.asia/blog/2650954.sHtML

原标题：TLS 版本兼容 HTTPS 握手失败
简介：golang redis bitmap 位图业务实战，bitmap 做签到统计、用户状态标记，节省大量内存空间。
 | 原文链接：http://book.tnxmpb.asia/blog/3834579.sHtML

原标题：golang prometheus histogram 指标
简介：golang 消息队列中间件选型对比，kafka redis‑stream rabbitmq，对比吞吐量可靠性选型参考。
 | 原文链接：http://book.tnxmpb.asia/blog/9620526.sHtML

原标题：Issue：定时任务并发执行未加锁重复执行业务
简介：golang hmac 签名生成校验示例，hmac 生成消息签名，做接口请求签名，校验数据不被篡改。
 | 原文链接：http://book.tnxmpb.asia/blog/8053621.sHtML

原标题：Practice：实现限流之后友好业务返回处理
简介：数据库读写分离性能优化，讲解读写分离原理，主库写入从库查询，分担数据库查询压力，提升查询性能。
 | 原文链接：http://book.tnxmpb.asia/blog/4168442.sHtML

四、架构设计｜Architecture
原标题：golang 系统设计大流量削峰处理方案
简介：golang 工具函数库封装思路，Go 通用工具库封装思路，错误处理、类型转换，业务项目复用工具代码。
 | 原文链接：http://book.tnxmpb.asia/blog/1581356.sHtML

原标题：简易日志收集集中管理方案
简介：golang go 容器 heap 堆实现优先队列，实现 heap 接口，构建优先队列，任务优先级调度。
 | 原文链接：http://book.tnxmpb.asia/blog/8056064.sHtML

原标题：golang 系统设计 mq 消息顺序性保证思路
简介：golang 空接口 interface {} 类型处理，interface {} 存储任意类型，类型转换，处理泛型之前通用数据。
 | 原文链接：http://book.tnxmpb.asia/blog/1925056.sHtML

原标题：调优方案：消息批量消费提升MQ处理吞吐量
简介：golang prometheus http 接口暴露指标，暴露 prometheus metrics 接口，输出业务运行指标，接入监控告警系统。
 | 原文链接：http://book.tnxmpb.asia/blog/2879174.sHtML

原标题：运维笔记：系统内核参数调优生产服务器
简介：接口限流逻辑简单模拟实现，编写简易限流逻辑，限制接口访问频次，保护服务，避免短时间大量请求压垮系统。
 | 原文链接：http://book.tnxmpb.asia/blog/0130687.sHtML

原标题：项目实践：实现统一接口返回封装与全局异常处理
简介：golang gitlab ci go 项目流水线编写，gitlab ci 流水线执行单元测试、静态检查、构建推送镜像。
 | 原文链接：http://book.tnxmpb.asia/blog/4208652.sHtML

原标题：方案设计：接口版本管理架构向前兼容策略
简介：golang 单元测试 mock http 请求，mock HTTP 外部接口，单元测试不依赖外部网络，保证用例稳定运行。
 | 原文链接：http://book.tnxmpb.asia/blog/1394848.sHtML

原标题：日志切割配置防止日志丢失
简介：golang gorm 软删除实现逻辑，Gorm 开启软删除，删除数据仅标记，数据保留可恢复，满足业务数据留存。
 | 原文链接：http://book.tnxmpb.asia/blog/0895531.sHtML

原标题：数据库主从延迟业务兼容处理
简介：golang testify mock 模拟接口，mock 接口生成 mock 对象，单元测试模拟外部依赖行为。
 | 原文链接：http://book.tnxmpb.asia/blog/0103982.sHtML

原标题：踩坑：大报文传输，RPC消息超过大小限制
简介：业务幂等键设计防重复逻辑，讲解幂等键设计思路，选择合适业务字段作为幂等标识，实现可靠防重复。
 | 原文链接：http://book.tnxmpb.asia/blog/9683536.sHtML

原标题：开发复盘：导出大文件避免内存溢出实现方案
简介：golang context.WithCancel 手动取消上下文，WithCancel 生成可取消 ctx，手动调用 cancel 触发取消。
 | 原文链接：http://book.tnxmpb.asia/blog/9922277.sHtML

原标题：开源实践：维护开源项目Issue管理经验总结
简介：开发测试生产多环境配置区分，讲解三套环境配置分离思路，配置文件隔离，防止开发配置泄露到生产环境。
 | 原文链接：http://book.tnxmpb.asia/blog/1241328.sHtML

原标题：新手向：配置项目eslint/prettier代码格式化
简介：golang ioutil 已废弃替换方案，ioutil 废弃之后替换为 os io 包函数，更新旧项目代码。
 | 原文链接：http://book.tnxmpb.asia/blog/3652470.sHtML

原标题：ServiceWorker 缓存页面更新清理
简介：nestjs 权限守卫鉴权实现方案，使用 Nest 守卫实现接口鉴权，角色权限控制，拦截未授权接口访问。
 | 原文链接：http://book.tnxmpb.asia/blog/1574983.sHtML

原标题：golang 系统设计分布式锁可重入实现思路
简介：nodejs 流处理大文件不占内存，使用 Node.js 流处理超大文件，边读边写，不需要全部加载进内存。
 | 原文链接：http://book.tnxmpb.asia/blog/2516843.sHtML

原标题：安全笔记：CORS跨域配置错误安全风险
简介：数据库事务 ACID 原理讲解，拆解事务四大特性，理解事务隔离、原子性，明白事务如何保障数据安全。
 | 原文链接：http://book.tnxmpb.asia/blog/2729466.sHtML

原标题：项目实践：消息队列消息确认机制业务实践
简介：golang prometheus 指标埋点开发，业务埋点计数器、仪表盘、直方图，对接 prometheus 采集监控指标。
 | 原文链接：http://book.tnxmpb.asia/blog/4254905.sHtML

原标题：运维笔记：磁盘inode耗尽故障排查处理
简介：golang golangci‑lint 静态代码检查配置，golangci‑lint 静态检查，代码规范检测，提前发现代码隐患。
 | 原文链接：http://book.tnxmpb.asia/blog/4462421.sHtML

?
