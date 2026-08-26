最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计网关缓存静态资源实现思路
简介：golang bufio.Scanner 缓冲区调大，Scanner 默认缓冲区大小不够，读取超长行需要扩大缓冲区。
 | 原文链接：http://book.3hxem0.asia/blog/373661.Doc

原标题：浏览器内存泄漏排查前端页面
简介：业务幂等键设计防重复逻辑，讲解幂等键设计思路，选择合适业务字段作为幂等标识，实现可靠防重复。
 | 原文链接：http://book.3hxem0.asia/blog/838627.Doc

原标题：golang 系统设计传输加密 tls 配置要点
简介：网络读取超时设置连接挂起防护，设置网络读取超时时间，防止请求无限挂起不返回，占用连接资源。
 | 原文链接：http://book.3hxem0.asia/blog/079407.Doc

原标题：golang redis lua 脚本开发调试
简介：golang rate‑limiter 限流组件，封装通用 Go 限流组件，支持多算法，业务接口直接复用调用。
 | 原文链接：http://book.3hxem0.asia/blog/301689.Doc

原标题：架构复盘：多级缓存架构，本地缓存+分布式缓存
简介：golang grpc 错误状态码标准化，grpc 标准化错误返回，定义业务错误码，客户端解析处理业务异常。
 | 原文链接：http://book.3hxem0.asia/blog/144306.Doc

原标题：坑点：Git仓库过大，clone速度极慢解决方案
简介：golang 容器 OOM 被杀死排查区分，区分业务内存泄漏、容器限制过小，定位容器 OOMKilled 原因。
 | 原文链接：http://book.3hxem0.asia/blog/186035.Doc

原标题：golang 系统设计会话共享多实例部署
简介：golang url 解析路径参数提取，url.Parse 解析 url，获取协议主机路径查询参数。
 | 原文链接：http://book.3hxem0.asia/blog/062062.Doc

原标题：Git LFS 大文件推送失败解决
简介：批量操作分批处理防止 OOM，大批量数据处理不一次性加载全部数据，分批循环处理，避免内存溢出。
 | 原文链接：http://book.3hxem0.asia/blog/154389.Doc

原标题：golang 系统设计分布式事务业务选型决策思路
简介：数据库死锁成因规避方案，讲解数据库死锁产生条件，给出业务层面规避手段，减少死锁事件发生。
 | 原文链接：http://book.3hxem0.asia/blog/565312.Doc

原标题：开发复盘：内存缓存LRU淘汰策略实现实践
简介：golang kitex 超时重试熔断配置，kitex 配置调用超时、重试、熔断策略，保障微服务调用稳定性。
 | 原文链接：http://book.3hxem0.asia/blog/513381.Doc

原标题：安全笔记：JWT安全风险，签名泄露过期控制
简介：golang grpc 负载均衡客户端实现，grpc 客户端负载均衡，轮询随机权重，分发请求到多个服务实例。
 | 原文链接：http://book.3hxem0.asia/blog/076436.Doc

原标题：避坑：批量操作未分批次，一次性内存打爆
简介：版本升级服务启动失败处理，版本更新之后服务无法启动，对比新旧版本配置、依赖差异，完成故障修复。
 | 原文链接：http://book.3hxem0.asia/blog/269133.Doc

原标题：golang websocket 服务端开发
简介：golang kitex 字节微服务框架入门，kitex 开发 rpc 微服务，代码生成，服务注册发现完整流程。
 | 原文链接：http://book.3hxem0.asia/blog/034346.Doc

原标题：golang ci 流水线单元测试集成测试
简介：语义化版本依赖管理防错乱，项目依赖遵循语义版本约束，规避依赖自动升级引入不兼容变更。
 | 原文链接：http://book.3hxem0.asia/blog/364622.Doc

原标题：设计思考：业务埋点架构日志埋点设计原则
简介：golang 数据库连接耗尽排查思路，监控连接池状态，定位连接未归还，解决连接耗尽报错。
 | 原文链接：http://book.3hxem0.asia/blog/498795.Doc

原标题：golang 系统设计 git 钩子自动化校验实现
简介：服务熔断防止故障级联传播，实现服务熔断逻辑，下游故障时快速失败，阻止故障向上游链式扩散。
 | 原文链接：http://book.3hxem0.asia/blog/779538.Doc

原标题：实战项目：多实例部署会话一致性验证实践
简介：简易日志收集集中管理方案，搭建轻量日志收集方案，把多服务日志汇总，集中检索查看日志信息。
 | 原文链接：http://book.3hxem0.asia/blog/588696.Doc

原标题：golang 系统设计热点数据缓存处理
简介：golang runtime.Gosched 主动让出调度，长计算循环主动 Gosched，让出调度权，防止其他协程饥饿。
 | 原文链接：http://book.3hxem0.asia/blog/232098.Doc

原标题：golang 系统设计链路追踪核心概念 trace span 讲解
简介：golang go‑pg postgres 客户端实操，go‑pg 操作 PostgreSQL 数据库，CRUD 关联查询业务开发。
 | 原文链接：http://book.3hxem0.asia/blog/927179.Doc

原标题：golang 跨域处理中间件编写
简介：golang go 爬虫请求速率控制，爬虫限频、代理轮换，设置 UA，防止爬虫被目标站点封禁 IP。
 | 原文链接：http://book.3hxem0.asia/blog/343519.Doc

原标题：踩坑记录：端口被占用导致服务启动失败
简介：API 大版本不兼容平滑迁移，API 版本迭代不兼容旧接口，设计平滑迁移方案，逐步完成版本切换。
 | 原文链接：http://book.3hxem0.asia/blog/032517.Doc

原标题：坑点：gitreset误删本地代码恢复方案
简介：golang panic 崩溃日志完整收集，捕获所有 panic，打印堆栈，记录日志，方便定位崩溃根源。
 | 原文链接：http://book.3hxem0.asia/blog/557486.Doc

原标题：golang html 模板渲染简单示例
简介：golang consul 服务发现简单示例，对接 Consul 实现服务注册发现，微服务实例自动感知。
 | 原文链接：http://book.3hxem0.asia/blog/566318.Doc

原标题：接口签名校验防篡改实现
简介：golang hmac 签名生成校验示例，hmac 生成消息签名，做接口请求签名，校验数据不被篡改。
 | 原文链接：http://book.3hxem0.asia/blog/990116.Doc

原标题：Troubleshooting：K8sPodOOMKilled完整排查流程
简介：golang 环境变量读取与类型转换，读取系统环境变量，做类型转换默认值处理，适配多环境部署。
 | 原文链接：http://book.3hxem0.asia/blog/374050.Doc

原标题：踩坑记录：CPU亲和配置不合理多核心负载不均
简介：nodejs 日志轮转生产环境配置，配置 Node 日志轮转切割，防止日志文件无限变大，适配生产环境。
 | 原文链接：http://book.3hxem0.asia/blog/302804.Doc

原标题：方案设计：短链接系统完整架构方案拆解
简介：golang hertz 反向代理与负载均衡，hertz 实现反向代理，内置负载均衡，快速搭建网关类服务。
 | 原文链接：http://book.3hxem0.asia/blog/921801.Doc

原标题：golang 系统设计 go netpoll 多路复用简单理解
简介：golang time 定时器重置 Reset 正确用法，Timer Reset 调用前提，避免 Reset 带来逻辑错误。
 | 原文链接：http://book.3hxem0.asia/blog/336412.Doc

原标题：golang 系统设计监控缺失指标补全完整流程
简介：用户敏感数据脱敏代码实现，编写数据脱敏工具，对手机号、身份证做脱敏处理，防止敏感信息直接泄露。
 | 原文链接：http://book.3hxem0.asia/blog/188838.Doc

原标题：golang mysql 行锁表锁场景区分
简介：golang yaml 解析配置加载实操，Go 解析 YAML 配置文件，读取配置参数，驱动业务运行。
 | 原文链接：http://book.3hxem0.asia/blog/594108.Doc

原标题：快速入门简单签名校验实现思路
简介：golang go 防止路径穿越攻击，文件操作校验路径，拒绝../ 路径穿越，禁止访问系统任意文件。
 | 原文链接：http://book.3hxem0.asia/blog/412478.Doc

原标题：golang redis 限流几种实现方案
简介：前端组件库按需加载性能优化，配置组件库按需引入，避免引入全部组件，减少打包产物体积。
 | 原文链接：http://book.3hxem0.asia/blog/140199.Doc

原标题：语义化版本依赖管理防错乱
简介：golang interface {} 类型断言类型转换，类型断言 ok 模式，避免断言失败触发 panic。
 | 原文链接：http://book.3hxem0.asia/blog/059932.Doc

原标题：全平台系统环境变量配置
简介：golang grpc metadata 元数据透传，metadata 传递 traceId、鉴权信息，全链路透传上下文信息。
 | 原文链接：http://book.3hxem0.asia/blog/119624.Doc

原标题：golang redis 计数器防超卖示例
简介：防火墙 IP 白名单回调接口放行，配置防火墙白名单，放行第三方回调服务器 IP，接收回调请求正常。
 | 原文链接：http://book.3hxem0.asia/blog/119831.Doc

原标题：开发记录：表单文件类型校验后端安全校验实践
简介：CI 持续集成自动构建流程，讲解 CI 基础概念，配置流水线实现代码提交后自动构建、测试，提升交付自动化。
 | 原文链接：http://book.3hxem0.asia/blog/301896.Doc

原标题：Architecture：安全防护架构XSSCSRFSQL注入防御
简介：golang go 服务压测前后性能对比，压测记录 QPS 延迟，优化前后对比，验证优化效果。
 | 原文链接：http://book.3hxem0.asia/blog/083373.Doc

原标题：Security：SSRF服务端请求伪造漏洞防御
简介：代码模块化组件化拆分思路，讲解代码拆分原则，将大业务拆分为独立模块组件，提升代码复用与维护能力。
 | 原文链接：http://book.3hxem0.asia/blog/958667.Doc

原标题：git rebase 整理提交历史实操
简介：分布式 ID 全局唯一生成方案，讲解分布式 ID 生成思路，实现全局唯一 ID，满足分布式系统主键生成需求。
 | 原文链接：http://book.3hxem0.asia/blog/638865.Doc

原标题：接口限流逻辑简单模拟实现
简介：容器资源限制防止宿主机过载，设置容器 CPU 内存资源上限，避免单个容器耗尽宿主机全部硬件资源。
 | 原文链接：http://book.3hxem0.asia/blog/999312.Doc


二、踩坑排错｜Troubleshooting
原标题：golang 系统设计定时任务分布式锁
简介：golang os/exec 安全执行外部命令，规避命令注入漏洞，参数分离，禁止拼接命令字符串执行。
 | 原文链接：http://book.3hxem0.asia/blog/309616.Doc

原标题：golang k8s 日志收集 efk 简单架构
简介：新手参与开源社区贡献指南，介绍开源社区基础规则，讲解阅读 issue、提交 PR 流程，指导开发者参与开源贡献。
 | 原文链接：http://book.3hxem0.asia/blog/217027.Doc

原标题：批量异步处理系统业务落地
简介：CI 持续集成自动构建流程，讲解 CI 基础概念，配置流水线实现代码提交后自动构建、测试，提升交付自动化。
 | 原文链接：http://book.3hxem0.asia/blog/926910.Doc

原标题：golang rate‑limiter 限流组件
简介：golang context.WithCancel 手动取消上下文，WithCancel 生成可取消 ctx，手动调用 cancel 触发取消。
 | 原文链接：http://book.3hxem0.asia/blog/875510.Doc

原标题：HelloGitHubPages：部署你的第一个静态博客
简介：全量回归测试提升代码质量，搭建全量回归测试集，版本发布执行回归测试，避免迭代引入旧 bug。
 | 原文链接：http://book.3hxem0.asia/blog/531908.Doc

原标题：golang redis 热点 key 业务规避
简介：golang rsa 非对称加密签名验签，RSA 非对称加密与签名验签，实现非对称安全通信。
 | 原文链接：http://book.3hxem0.asia/blog/527038.Doc

原标题：golang 系统设计监控大盘故障快速定位思路
简介：nodejs 读取大文件 csv 处理方案，Node 流式读取超大 CSV 文件，逐行解析，避免一次性加载全部文件。
 | 原文链接：http://book.3hxem0.asia/blog/305679.Doc

原标题：golang 系统设计 tcp 粘包拆包处理方案实现
简介：nodejs 信号处理优雅关闭服务，监听系统信号，执行资源清理，实现 Node 服务优雅停机，拒绝粗暴杀死进程。
 | 原文链接：http://book.3hxem0.asia/blog/853946.Doc

原标题：golang 系统设计网关 websocket 转发配置要点
简介：golang 延迟队列实现方案对比，时间轮、redis zset 实现延迟队列，处理延时执行业务。
 | 原文链接：http://book.3hxem0.asia/blog/428504.Doc

原标题：开发记录：实现完整用户登录鉴权业务模块
简介：golang CPU 绑定亲和性设置 go 程序，设置进程 CPU 亲和绑定核心，减少 CPU 调度开销，提升计算性能。
 | 原文链接：http://book.3hxem0.asia/blog/939689.Doc

原标题：安全复盘：Redis命令注入风险防护手段
简介：golang go 领域驱动 DDD 项目分层，go 项目 DDD 分层架构，领域层应用层基础设施层划分业务代码。
 | 原文链接：http://book.3hxem0.asia/blog/737036.Doc

原标题：Debug：并发场景下数据覆盖丢失问题定位
简介：开发测试生产多环境配置区分，讲解三套环境配置分离思路，配置文件隔离，防止开发配置泄露到生产环境。
 | 原文链接：http://book.3hxem0.asia/blog/951589.Doc

原标题：开源项目构建失败排查步骤
简介：端口占用释放资源重启服务，查找占用端口进程，结束占用进程，释放端口，让服务能够正常启动监听。
 | 原文链接：http://book.3hxem0.asia/blog/189919.Doc

原标题：golang kafka 消息顺序性保证方案
简介：Git 误删提交代码恢复找回，使用 Git reflog 工具找回被误删除提交记录，恢复误删除代码。
 | 原文链接：http://book.3hxem0.asia/blog/845576.Doc

原标题：nodejs 信号处理优雅关闭服务
简介：跨平台换行符统一异常修复，统一代码文件换行符，解决不同操作系统换行符不一致带来脚本执行异常。
 | 原文链接：http://book.3hxem0.asia/blog/500650.Doc

原标题：golang 系统设计内网外网服务隔离方案
简介：golang csv 读写批量数据处理，Go 读写 CSV 文件，批量导入导出业务数据，处理 CSV 格式解析。
 | 原文链接：http://book.3hxem0.asia/blog/702505.Doc

原标题：Debug：异步任务堆积，服务响应越来越慢
简介：golang bytes.Buffer 字节缓冲区使用，bytes.Buffer 字节内存缓冲区，拼接字节，避免频繁内存分配。
 | 原文链接：http://book.3hxem0.asia/blog/292634.Doc

原标题：golang 系统设计线上问题复现思路简单讲解
简介：接口请求重试容错机制实现，封装请求重试逻辑，遇到临时网络故障自动重试，提升第三方调用稳定性。
 | 原文链接：http://book.3hxem0.asia/blog/117387.Doc

原标题：golang 系统设计告警风暴抑制合并降噪方案
简介：golang 日志级别动态调整热更新，不用重启程序动态修改日志输出级别，线上调试排查问题十分方便。
 | 原文链接：http://book.3hxem0.asia/blog/198544.Doc

原标题：接口签名校验防篡改实现
简介：前端静态缓存更新生效处理，修改静态资源版本标识，处理浏览器强缓存，让更新资源生效。
 | 原文链接：http://book.3hxem0.asia/blog/747119.Doc

原标题：实战项目：GitHubAction自动测试构建实践
简介：golang ctx 传递规则不要存结构体，context 作为函数参数传递，禁止放入结构体字段存储。
 | 原文链接：http://book.3hxem0.asia/blog/305278.Doc

原标题：golang 系统设计故障演练简单落地思路方法论
简介：前端静态缓存更新生效处理，修改静态资源版本标识，处理浏览器强缓存，让更新资源生效。
 | 原文链接：http://book.3hxem0.asia/blog/512583.Doc

原标题：GitHub Markdown 文档语法汇总
简介：磁盘占满服务不可用清理方案，定位磁盘占用大文件，清理日志、缓存文件，恢复磁盘可用空间。
 | 原文链接：http://book.3hxem0.asia/blog/902080.Doc

原标题：安全复盘：Redis命令注入风险防护手段
简介：golang go 项目安全检查漏洞扫描，扫描 go 项目依赖漏洞，代码安全审计，规避安全风险。
 | 原文链接：http://book.3hxem0.asia/blog/223173.Doc

原标题：golang mysql 长连接短连接对比
简介：golang 项目 makefile 脚本编写，编写 Makefile 脚本，封装编译、测试、构建命令，简化项目操作。
 | 原文链接：http://book.3hxem0.asia/blog/439506.Doc

原标题：golang ci 流水线代码质量扫描集成
简介：golang 数据库 ORM 框架选型对比，gorm xorm sqlx 对比各 ORM 优缺点，根据业务场景选型。
 | 原文链接：http://book.3hxem0.asia/blog/503325.Doc

原标题：golang ci 流水线代码质量扫描集成
简介：golang context.WithValue 传递元数据，WithValue 只传 traceId 鉴权元数据，不要传业务大对象。
 | 原文链接：http://book.3hxem0.asia/blog/989364.Doc

原标题：性能笔记：磁盘IO过高业务优化手段
简介：TCP 心跳检测清理僵死连接，开启 TCP 心跳机制，自动清理僵死无效连接，释放连接资源。
 | 原文链接：http://book.3hxem0.asia/blog/261620.Doc

原标题：OpenAPI 自动接口文档生成
简介：nestjs 拦截器过滤器管道实战，实操 Nest 拦截器、异常过滤器、管道校验，处理请求与响应统一逻辑。
 | 原文链接：http://book.3hxem0.asia/blog/568761.Doc

原标题：nodejs 接口限流防刷代码实现
简介：日志敏感信息脱敏泄露防护，日志打印时自动脱敏手机号身份证，避免日志输出泄露用户隐私数据。
 | 原文链接：http://book.3hxem0.asia/blog/224792.Doc

原标题：内存溢出问题现象识别排查
简介：golang contract 契约测试微服务，微服务契约测试，保证接口变更不破坏调用方，提前发现兼容性问题。
 | 原文链接：http://book.3hxem0.asia/blog/596751.Doc

原标题：项目实践：MySQL读写分离本地模拟实践
简介：golang go‑zero 配置中心热更新，go‑zero 对接 etcd 配置中心，配置热更新无需重启服务。
 | 原文链接：http://book.3hxem0.asia/blog/372702.Doc

原标题：优化实践：序列化框架性能对比选型实践
简介：Fork 开源项目同步上游代码，Fork 开源仓库之后，配置上游源，同步官方最新代码，保持代码版本对齐。
 | 原文链接：http://book.3hxem0.asia/blog/395211.Doc

原标题：golang 系统设计消息消费 offset 管理策略
简介：golang channel 缓冲无缓冲区别，缓冲 channel 与无缓冲 channel，底层行为差异业务选型参考。
 | 原文链接：http://book.3hxem0.asia/blog/512938.Doc

原标题：序列化版本不一致解析失败
简介：Cookie Session 会话状态管理，讲解 Cookie 与 Session 原理，理解登录状态保存，实现服务端会话管理逻辑。
 | 原文链接：http://book.3hxem0.asia/blog/150174.Doc

原标题：golang 系统设计 commit 提交规范约定
简介：文件读写与异常捕获代码示例，演示文件读取写入操作，增加异常捕获逻辑，规避文件不存在、权限不足导致崩溃。
 | 原文链接：http://book.3hxem0.asia/blog/539294.Doc

原标题：架构复盘：慢查询治理架构层面优化手段
简介：golang 设置 net.Conn 读写超时，每次读写设置超时，防止连接永久阻塞挂起不返回。
 | 原文链接：http://book.3hxem0.asia/blog/701010.Doc

原标题：定时任务周期调度 demo 开发
简介：前端虚拟列表大数据渲染优化，实现虚拟滚动列表，只渲染可视区域 DOM，上万条数据页面流畅渲染。
 | 原文链接：http://book.3hxem0.asia/blog/669408.Doc

原标题：axios 二次封装请求拦截处理
简介：golang go 程序版本号内置编译注入，编译时注入 git commit 版本号，程序运行输出版本便于排查。
 | 原文链接：http://book.3hxem0.asia/blog/376290.Doc

原标题：分布式锁失效问题排查修复
简介：Shell 脚本自动化命令编写，讲解 Shell 基础语法，编写自动化脚本，完成批量执行、文件处理，解放重复手工操作。
 | 原文链接：http://book.3hxem0.asia/blog/881027.Doc

三、实战开发｜Practice
原标题：运维笔记：系统内核参数调优生产服务器
简介：golang http 文件下载断点续传服务，服务端实现断点续传，支持大文件分段下载，提升大文件下载稳定性。
 | 原文链接：http://book.3hxem0.asia/blog/632691.Doc

原标题：无用对象回收抑制内存上涨
简介：golang goroutine 泄露检测告警实现，监控 goroutine 数量，突增触发告警，提早发现协程泄露。
 | 原文链接：http://book.3hxem0.asia/blog/743216.Doc

原标题：实践：多配置文件合并加载组件实现
简介：golang 大文件读取内存优化，Go 流式读取大文件，分块处理，避免大文件一次性加载全部到内存。
 | 原文链接：http://book.3hxem0.asia/blog/560065.Doc

原标题：动态定时任务业务调度实现
简介：空指针异常判空容错处理，讲解空指针产生场景，规范判空逻辑，增加容错，避免空指针直接造成程序崩溃。
 | 原文链接：http://book.3hxem0.asia/blog/226291.Doc

原标题：golang 表单文件大小限制配置
简介：golang 分布式唯一 id 多种方案对比，雪花、redis、uuid 对比各方案优缺点，指导业务选型使用。
 | 原文链接：http://book.3hxem0.asia/blog/907056.Doc

原标题：从零学习简单分布式ID生成思路
简介：golang 分布式追踪全链路日志打印，日志打印 traceId，各个服务日志可串联，排查跨服务调用问题。
 | 原文链接：http://book.3hxem0.asia/blog/224707.Doc

原标题：从零搭建简单的健康检查接口示例
简介：golang go mod exclude 排除依赖版本，exclude 排除有问题依赖版本，规避有 bug 的第三方包。
 | 原文链接：http://book.3hxem0.asia/blog/023930.Doc

原标题：golang es 分页深分页性能优化
简介：ORM 隐式慢查询问题规避，识别 ORM 框架隐式查询，避免循环查询数据库，减少不必要慢 SQL 产生。
 | 原文链接：http://book.3hxem0.asia/blog/595622.Doc

原标题：nodejs 集群模式多核利用实现
简介：游标分页大数据查询性能提升，使用游标分页替代偏移分页，解决大数据 offset 分页性能越来越差问题。
 | 原文链接：http://book.3hxem0.asia/blog/035696.Doc

原标题：golang 系统设计技术债务识别登记治理思路
简介：golang os 文件目录操作大全，文件创建删除重命名，目录遍历，文件信息读取，完成各类文件系统操作。
 | 原文链接：http://book.3hxem0.asia/blog/977400.Doc

原标题：复盘总结：技术选型对比文档模板实践
简介：数据库主从延迟业务兼容处理，业务适配主从复制延迟，避免读取从库拿到还未同步完成旧数据。
 | 原文链接：http://book.3hxem0.asia/blog/853303.Doc

原标题：golang 系统设计消息发送确认机制配置实操
简介：golang json omitempty 零值坑，omitempty 会忽略零值，区分业务是否需要输出零值字段。
 | 原文链接：http://book.3hxem0.asia/blog/506999.Doc

原标题：架构复盘：容器资源隔离架构CPU内存限制设计
简介：golang cobra 命令行参数配置绑定，cobra 绑定配置文件环境变量命令行参数，多源配置合并。
 | 原文链接：http://book.3hxem0.asia/blog/937716.Doc

原标题：记一次字符集编码不一致乱码问题全排查
简介：golang redis zset 实现延时任务队列，zset 存储任务到期时间，轮询到期任务执行，简易延迟队列。
 | 原文链接：http://book.3hxem0.asia/blog/617398.Doc

原标题：Performance：后端接口性能优化完整分析流程
简介：golang go 随机数安全与非安全，math/rand 伪随机与 crypto/rand 密码学安全随机，区分业务场景。
 | 原文链接：http://book.3hxem0.asia/blog/905821.Doc

原标题：开发复盘：实现定时任务调度服务支持动态任务
简介：浏览器缓存强制刷新方案，设置 HTTP 缓存头，处理浏览器缓存旧静态资源，让用户加载更新后的页面。
 | 原文链接：http://book.3hxem0.asia/blog/316811.Doc

原标题：CI 持续集成自动构建流程
简介：golang go 程序敏感信息禁止打印日志，密钥密码禁止输出日志，防止敏感信息日志泄露。
 | 原文链接：http://book.3hxem0.asia/blog/263406.Doc

原标题：golang http 服务性能优化调参
简介：前端组件库按需加载性能优化，配置组件库按需引入，避免引入全部组件，减少打包产物体积。
 | 原文链接：http://book.3hxem0.asia/blog/851808.Doc

原标题：golang 系统设计 git 钩子自动化校验实现
简介：golang 数据库连接耗尽排查思路，监控连接池状态，定位连接未归还，解决连接耗尽报错。
 | 原文链接：http://book.3hxem0.asia/blog/154237.Doc

原标题：golang 系统设计服务优雅停机完整流程
简介：后端分页查询逻辑代码实现，编写后端分页接口，处理页码、每页条数参数，优化大数据量查询返回结果。
 | 原文链接：http://book.3hxem0.asia/blog/990699.Doc

原标题：Security：限流防爬虫防恶意攻击防护体系
简介：golang go 时间 time.Timer time.Ticker，定时器与周期定时器，Stop Reset 正确使用，防止资源泄漏。
 | 原文链接：http://book.3hxem0.asia/blog/858665.Doc

原标题：线上故障：消息队列重复消费业务处理异常
简介：golang feishu 飞书机器人消息发送，调用飞书 webhook 机器人，发送文本卡片消息，实现业务告警通知。
 | 原文链接：http://book.3hxem0.asia/blog/766421.Doc

原标题：部署复盘：配置不要硬编码进镜像最佳实践
简介：golang ssh 客户端远程命令执行，golang ssh 连接远程服务器，执行 shell 命令，获取命令输出结果。
 | 原文链接：http://book.3hxem0.asia/blog/333832.Doc

原标题：golang 系统设计分库分表本地测试调试技巧
简介：限流规则误拦截正常请求修复，修正限流规则阈值，避免合法用户被限流拦截，兼顾防护与可用性。
 | 原文链接：http://book.3hxem0.asia/blog/788612.Doc

原标题：Issue复现：内存泄漏定位完整复盘记录
简介：golang makefile 多平台编译脚本，makefile 一键交叉编译多平台二进制，打包镜像，执行测试。
 | 原文链接：http://book.3hxem0.asia/blog/314882.Doc

原标题：Hands‑on：模拟RPC超时重试业务异常场景
简介：golang 日志级别动态调整热更新，不用重启程序动态修改日志输出级别，线上调试排查问题十分方便。
 | 原文链接：http://book.3hxem0.asia/blog/187086.Doc

原标题：Architecture：事件溯源架构模式适用业务场景
简介：vue pinia 状态管理实战教程，Pinia 完整实战示例，实现状态定义修改，模块拆分替代 Vuex。
 | 原文链接：http://book.3hxem0.asia/blog/028566.Doc

原标题：新手避坑：第一次提交GitHub项目完整流程
简介：golang wasm 浏览器 js 交互，go wasm 与 js 互相调用，浏览器端 go 程序操作 dom 调用 js 函数。
 | 原文链接：http://book.3hxem0.asia/blog/693553.Doc

原标题：golang 重试退避机制代码实现
简介：站内邮件消息通知功能开发，实现站内消息、邮件通知推送，业务事件触发通知，提醒用户业务状态变更。
 | 原文链接：http://book.3hxem0.asia/blog/880902.Doc

原标题：golang 单例模式实现几种方式
简介：golang 容器健康检查接口开发，Go 开发 HTTP 健康接口，供容器编排工具探测实例存活状态。
 | 原文链接：http://book.3hxem0.asia/blog/904072.Doc

原标题：golang 系统设计 vscode go 插件调试配置实操
简介：极简 API 网关路由转发实现，开发极简网关服务，完成请求路由转发，理解网关基础实现原理。
 | 原文链接：http://book.3hxem0.asia/blog/295492.Doc

原标题：golang redis 地理位置 geo 使用
简介：业务幂等键设计防重复逻辑，讲解幂等键设计思路，选择合适业务字段作为幂等标识，实现可靠防重复。
 | 原文链接：http://book.3hxem0.asia/blog/040093.Doc

原标题：站内邮件消息通知功能开发
简介：golang 容器 OOM 被杀死排查区分，区分业务内存泄漏、容器限制过小，定位容器 OOMKilled 原因。
 | 原文链接：http://book.3hxem0.asia/blog/200338.Doc

原标题：golang 系统设计压力测试性能测试执行流程
简介：数值类型溢出错乱问题修复，选择合适数值存储类型，处理数值溢出，避免数据存储错乱结果异常。
 | 原文链接：http://book.3hxem0.asia/blog/494746.Doc

原标题：golang 系统设计 protobuf json 性能对比
简介：golang 多协程任务池并发控制，实现协程任务池，控制并发协程数量，防止无限制创建 goroutine。
 | 原文链接：http://book.3hxem0.asia/blog/966824.Doc

原标题：包管理器依赖冲突解决方案
简介：缓存穿透击穿雪崩全套防护，完整梳理缓存三大问题，落地全套防护策略，保障缓存层稳定运行。
 | 原文链接：http://book.3hxem0.asia/blog/721434.Doc

原标题：接口请求重试容错机制实现
简介：golang channel 通道并发处理，讲解 Channel 用法，协程之间通过通道传递数据，做并发同步控制。
 | 原文链接：http://book.3hxem0.asia/blog/330597.Doc

原标题：golang 单元测试 mock http 请求
简介：golang 系统资源限制读取 cpu 内存，读取系统容器 cpu 内存限制，程序适配容器资源配额做业务调优。
 | 原文链接：http://book.3hxem0.asia/blog/639889.Doc

原标题：OpenSource：开源项目许可证License选型指南
简介：golang time.After 内存泄漏场景，for 循环使用 time.After 会创建大量 timer，造成内存泄漏。
 | 原文链接：http://book.3hxem0.asia/blog/071772.Doc

原标题：Troubleshooting：数据库主从延迟带来查询数据不一致
简介：ORM 隐式慢查询问题规避，识别 ORM 框架隐式查询，避免循环查询数据库，减少不必要慢 SQL 产生。
 | 原文链接：http://book.3hxem0.asia/blog/374601.Doc

四、架构设计｜Architecture
原标题：Security：接口鉴权越权漏洞检测与修复
简介：golang pdf 生成 go 服务端生成 pdf，服务端动态生成 pdf 报表文件，直接输出下载给到前端。
 | 原文链接：http://book.3hxem0.asia/blog/299698.Doc

原标题：优化实践：接口批量合并减少网络请求次数
简介：golang defer 闭包变量捕获坑，defer 捕获循环变量引用，变量被复写，理解闭包变量捕获规则。
 | 原文链接：http://book.3hxem0.asia/blog/429810.Doc

原标题：记一次分布式锁失效引发的数据错乱问题
简介：短信服务封装失败自动重试，封装短信发送组件，处理发送失败自动重试，兼容多短信服务商。
 | 原文链接：http://book.3hxem0.asia/blog/311114.Doc

原标题：vue3 组合式 API 业务开发实战
简介：golang 滑动窗口限流算法 go 实现，滑动窗口限流，解决固定窗口临界流量突增漏洞，限流更精准。
 | 原文链接：http://book.3hxem0.asia/blog/799497.Doc

原标题：golang redis 缓存预热实现思路
简介：golang tcp 连接泄露排查定位，netstat 查看连接状态，找出未正常关闭连接，定位连接泄漏代码。
 | 原文链接：http://book.3hxem0.asia/blog/642783.Doc

原标题：快速入门Nginx基础配置，反向代理示例
简介：golang bufio 缓冲读写性能优化，bufio 带缓冲读写，减少系统调用，提升文件网络 IO 性能。
 | 原文链接：http://book.3hxem0.asia/blog/891814.Doc

原标题：方案对比：定时任务框架选型与架构对比
简介：golang redis 过期时间处理技巧，设置 key 过期，监控过期事件，基于过期特性实现业务缓存逻辑。
 | 原文链接：http://book.3hxem0.asia/blog/433366.Doc

原标题：golang prometheus histogram 指标
简介：线程调度优化减少上下文切换，优化线程数量，减少线程频繁切换，降低 CPU 上下文切换开销。
 | 原文链接：http://book.3hxem0.asia/blog/200082.Doc

原标题：Security：Docker镜像安全扫描漏洞修复
简介：golang 协程泄露问题排查方法，识别 Go 协程泄露现象，分析泄露场景，给出排查定位协程泄露手段。
 | 原文链接：http://book.3hxem0.asia/blog/129776.Doc

原标题：入门实践：简单错误码设计与使用规范
简介：程序预加载加快服务启动速度，把高频使用资源提前预加载，减少请求阶段初始化，加快服务启动。
 | 原文链接：http://book.3hxem0.asia/blog/585810.Doc

原标题：新手教程：如何给开源项目提交第一个PR
简介：容器内存扩容 OOM 被杀死修复，调高容器内存限制，优化程序内存占用，避免程序被 OOM 终止。
 | 原文链接：http://book.3hxem0.asia/blog/163624.Doc

原标题：golang 系统设计容器 OOM 故障完整排查
简介：容器内存扩容 OOM 被杀死修复，调高容器内存限制，优化程序内存占用，避免程序被 OOM 终止。
 | 原文链接：http://book.3hxem0.asia/blog/941184.Doc

原标题：缓存过期打散防止缓存雪崩
简介：golang regexp 正则捕获分组提取数据，正则捕获分组提取子匹配内容，拿到需要业务字段。
 | 原文链接：http://book.3hxem0.asia/blog/851784.Doc

原标题：DNS TTL 配置域名切换生效
简介：golang mqtt 客户端 go 开发物联网，paho.mqtt.golang 实现 mqtt 客户端，物联网设备消息收发。
 | 原文链接：http://book.3hxem0.asia/blog/984195.Doc

原标题：API 接口调试与异常处理实战
简介：golang 优雅处理数据库事务，Go 数据库事务封装，正确处理事务提交回滚，保证业务数据一致性。
 | 原文链接：http://book.3hxem0.asia/blog/583144.Doc

原标题：全局本地依赖隔离冲突规避
简介：golang websocket 服务端开发，Go 实现 WebSocket 服务端，处理连接、消息收发，实现长连接服务。
 | 原文链接：http://book.3hxem0.asia/blog/753392.Doc

原标题：golang 系统设计 id 生成器选型对比
简介：golang context 超时取消实战案例，使用 context 控制协程、http 请求超时，自动终止超时任务，避免协程无限阻塞。
 | 原文链接：http://book.3hxem0.asia/blog/778671.Doc

原标题：数据库索引重建提升查询速度
简介：Nginx 静态代理负载均衡全套配置，一套 Nginx 配置示例，覆盖静态资源、反向代理、负载均衡场景。
 | 原文链接：http://book.3hxem0.asia/blog/965394.Doc

?
