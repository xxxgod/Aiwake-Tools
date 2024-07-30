## 平台工具&框架

- 云：Rancher > Kubernetes(k8s) > Docker（镜像库：registry，Harbor，JFrog Artifactory）
- Jupyter: IPython Notebook, 有个子项目sparkmagic，可以和Spark集合在一起，类似spark-notebook项目
- Swagger: RESTful API设计工具，前后端分离项目必备，顺便推荐下Easy Mock
- Flutter: Google出品，高性能跨平台移动应用开发框架
- OpenZipkin: 分布式Trace系统，可用于分析服务调用链间的消耗
- Sentry: 系统监控与错误日志跟踪系统
- 基于Web技术的跨平台应用开发框架：Revery: facebook基于Reason开发，Native、Fast, tauri:Rust开发，小而快，sciter，electron
- Phabricator: 软件开发平台，Facebook出品，现已开源，CodeReview神器（从这个往下一直到GitLab之间的工具统统可以忽略了）
- Discourse: Stack Overflow的联合创始人 Jeff Atwood 推出的一个新的开源论坛项目，不少开源项目的社区基于这个项目创建
- Redmine/Trac：项目管理平台
- Jenkins/Jira(非开源)：持续集成系统（Apache Continuum，这个是Apache下的CI系统，还没来得及研究）
- git，svn：源代码版本控制系统
- GitLab/Gitorious：构建自己的GitHub服务器
- AppVeyor - 云端持续集成工具，可以与GitHub搭配使用
- Postman:RESTful，api测试工具，HTTP接口开发必备神器；可替代工具：Insomnia
- Lottie: AE动画变原生代码，设计师必备
- Sonar：代码质量管理平台
- JMeter: 测试框架，还有Locust
- Nessus: 系统漏洞扫描器
- gitbook：https://www.gitbook.io/写书的好东西，当然用来写文档也很不错的（发现不少产品的文档就是用的它）
- Travis-ci：开源项目持续集成必备，和GitHub相结合，https://travis-ci.org/
- Trello：简单高效的项目管理平台，注重看板管理
- 日志聚合：graylog、ELK（推荐新一代的graylog，基本上算作是开源的Splunk了）
- 开源测试工具、社区（Selenium、http://OpenQA.org）
- Puppet:一个自动管理引擎，可以适用于Linux、Unix以及Windows平台。所谓配置管理系统，就是管理机器里面诸如文件、用户、进程、软件包这些资源。无论是管理1台，还是上万台机器Puppet都能轻松搞定。其他类似工具：CFEngine、SaltStack、Ansible
- jumpserver: 开源堡垒机
- Prometheus 监控系统+时序数据库，一般搭配Grafana使用。类似的系统还有Nagios,Zabbix,Ganglia
- fleet：分布式init系统
- Ansible：能够大大简化Unix管理员的自动化配置管理与流程控制方式。
- GeoLite免费数据库
- haproxy: 高可用负载均衡（此外类似的系统还有nginx，lvs）
- linux OS性能分析工具：dstat，iostat，iotop，nmon
- kimono：将网页信息转换为api接口的工具
- 集群管理工具：pdsh，ClusterSSH，mussh（可以用它快速管理Hadoop集群）ipa-server做统一的认证管理
- influxdb: 分布式时序数据库，结合Grafana可以进行实时数据分析
- dot: 程序员绘图利器（是种语言，也是个工具）
- Graph::Easy: （Ascii Art工具）字符流程图绘制，实乃程序员装逼神器。其他类似的工具Asciiflow, vi插件：drawit!
- spf13-vim: 让你的vim飞起来！这货好久没更新了，安装也有问题，比较好的替换是：SpaceVim
- Kubernetes: 容器集群管理系统
- Gatling: 服务器性能压力测试工具，类似的还有wrk
- systemtap: Linux内核探测工具、内核调试神器
- Cygwin：Windows下的类UNIX模拟环境
- MinGW：Windows下的GNU工具集

## 常用工具

- Radare2:逆向工程平台
- EditorConfig: 让我们在各种不同IDE或编辑器下写代码保持风格一致
- Mac下的神兵利器
- asciinema: 终端录屏神器
- Fiddler：非常好用的Web前端调试工具，当然是针对底层http协议的，一般情况使用Chrome等自带的调试工具也足够了，特殊情况还得用它去处理
- Charles: Mac上的Web代理调试工具，类似Fiddler
- fir.im免费的移动App内测托管平台
- wireshark：知名的网络数据包分析工具
- PowerCmd:替代Windows Cmd的利器，类似的还有cmder
- MobaXterm: Windows下的全能终端神器
- Xming: Windows下的X Window Server，结合putty可以实现linux的图形化软件直接跑在Windows上
- RegexBuddy:强大的正则表达式测试工具
- Source Insight：源代码阅读神器
- SublimeText：程序员最爱的编辑器
- http://Database.NET：一个通用的关系型数据库客户端，基于.NET 4.0开发的，做简单的处理还是蛮方便的
- Navicat Premium：支持MySql、PostgreSQL、Oracle、Sqlite和SQL Server的客户端，通用性上不如http://Database.NET，但性能方面比http://Database.NET好很多，自带备份功能也用于数据库定时备份。
- Synergy : 局域网内一套键盘鼠标控制多台电脑
- DameWare：远程协助工具集（我在公司主要控制大屏幕用）
- Radmin: 远程控制工具，用了一段时间的DameWare，还要破解，对Win7支持的不好，还是发现这个好用
- Listary：能极大幅度提高你 Windows 文件浏览与搜索速度效率的「超级神器」
- Clover：给资源管理器加上多标签，我平时工作的时候就用它，像Chrome一样使用资源管理器，甚是方便啊（这是Windows平台的）
- WinLaunch：模拟Mac OS的Launch工具
- OllyDbg: OD大名鼎鼎的反汇编工具，Win平台
- Fritzing：绘制电路图
- LICEcap：gif教程制作
- Enigma Virtual Box（将exe，dll等封装成一个可执行程序）
- Open DBDiff(针对SqlServer)数据库同步
- SymmetricDS：数据库同步
- BIEE,Infomatica，SPSS，weka，R语言：数据分析
- CodeSmith，LightSwitch：代码生成
- Pandoc：Markdown转换工具，出书用的。以前玩过docbook，不过现在还是Markdown盛行啊。
- Window Magnet[Mac]：增强Mac窗口管理功能，想Win7一样具有窗口拖放到屏幕边缘自动调整的功能
- log explorer：查看SqlServer日志
- dependency walker：查询Windows应用程序dll依赖项
- Shairport4w：将iPhone，iPad，iPod上的音频通过AirPlay协议传输到PC上
- ngrok：内网穿透工具
- Axure:快速原型制作工具，还有个在线作图的工具国内的一个创业团队做的，用着很不错http://www.processon.com/
- Origami: 次世代交互设计神器
- 百度脑图：http://naotu.baidu.com/
- tinyproxy:（Linux）小型的代理服务器支持http和https协议
- EaseUS Partition Master：超级简单的分区调整工具，速度还是蛮快的，C盘不够用了就用它从D盘划点空间吧，不用重装系统这么折腾哦。
- CheatEngine：玩游戏修改内存值必备神器（记得我在玩轩辕剑6的时候就用的它，超级方便呢）
- ApkIDE: Android反编译神器（类似的还有apktool）
- HandShaker: 锤子的良心之作：为解决安卓手机与Mac当中文件传输问题，专门开发的SmartFinder文件管理器改进版
- 翻、墙工具（自|由|门、天行浏览器，免费的VPN：http://www.mangovpn.com/）,发现最方便还属Lantern，免费用起来超级方便（更新于2015-08-22）
- 设计工具：Sketch、OmniGraffle
- MindManger：思维导图
- MagicDraw: Uml图工具
- innotop：MySql状态监测工具
- 墨刀：比Axure更为简单的原型工具，可以快速制作原型
- Karabiner: Mac专用，修改键盘键位的神器，机械键盘必备
- Timing：Mac专用，统计你的时间都花在哪了
- LaTeX: 基于ΤΕΧ的排版系统, 让写论文更方便
- Antlr：开源的语法分析器，可以让你毫无压力的写个小parser

## 第三方服务

- Let's Encrypt: 免费、自动化、开放的证书签发服务
- DnsPod：一个不错的智能DNS服务解析提供商
- DigitalOcean：海外的云主机提供商，价格便宜，磁盘是SSD的，用过一段时间整体上还可以，不过毕竟是海外的，网速比较慢。国内的就是阿里云了。还有个比较知名的是：Linode，据说速度上比DigitalOcean好很多
- 移动端推送服务：个推、JPush、云巴
- LeanCloud：移动应用开发服务，包括:数据存储、用户管理、消息推送、应用统计、社交分享、实时聊天等服务
- Color Hunt: 漂亮炫酷的配色网站，程序员的福音
- Heroku: PaaS平台

## 爬虫相关(好玩的工具)

- Phantomjs(Web自动化测试，服务端渲染等)
- berserkJS(基于Phantomjs的改进版本)
- SlimerJS
- CasperJS
- selenium
- HtmlUnit（开源的java 页面分析工具，也是个Headless的浏览器）

## 安全相关

- sql注入检测：sqlmap、haviji
- 端口扫描：nmap,
- masscan：据说可以6分钟中扫遍整个互联网的端口扫描器
- 渗透测试：BurpLoader
- sqltools: sql漏洞利用工具
- snort: 入侵检测
- Web服务器性能/压力测试工具/负载均衡器
- ab: ab是apache自带的一款功能强大的测试工具
- curl-loader: 真实模拟、测试Web负载
- http_load: 程序非常小，解压后也不到100K
- webbench: 是Linux下的一个网站压力测试工具，最多可以模拟3万个并发连接去测试网站的负载能力。
- Siege: 一款开源的压力测试工具，可以根据配置对一个WEB站点进行多用户的并发访问，记录每个用户所有请求过程的相应时间，并在一定数量的并发访问下重复进行。
- squid（前端缓存），nginx（负载），nodejs（没错它也可以，自己写点代码就能实现高性能的负载均衡器）：常用的负载均衡器
- Piwik：开源网站访问量统计系统
- ClickHeat：开源的网站点击情况热力图
- HAProxy：高性能TCP /HTTP负载均衡器
- ElasticSearch：搜索引擎基于Lucene
- Page Speed SDK和YSLOW
- HAR Viewer: HAR分析工具
- protractor：E2E（end to end）自动化测试工具

## 大数据处理/数据分析/分布式工具

- Hadoop：分布式的文件系统，结合其MapReduce编程模型可以用来做海量数据的批处理（Hive，Pig，HBase啥的就不说了），值得介绍的是Cloudera的Hadoop分支CDH5，基于YARN MRv2集成了Spark可直接用于生产环境的Hadoop，对于企业快速构建数据仓库非常有用。
- Spark：大规模数据处理框架（可以应付企业中常见的三种数据处理场景：复杂的批量数据处理（batch data processing）；基于历史数据的交互式查询（interactive query）；基于实时数据流的数据处理（streaming data processing））
- 除了Spark，其他几个不错的计算框架还有：Kylin，Flink，Drill
- Ignite: In-Memory Data Fabric
- CarbonData: 华为的孵化项目，支持索引的列式存储
- Ceph:Linux分布式文件系统（特点：无中心）
- Storm：实时流数据处理，可以看下IBM的一篇介绍 （还有个Yahoo的S4，也是做流数据处理的）
- Druid: 实时数据分析存储系统
- Ambari: 大数据平台搭建、监控利器；类似的还有CDH
- Tachyon：分布式内存文件系统
- Greenplum: 基于PostgreSQL的分布式MPP数据库
- Mesos：计算框架一个集群管理器，提供了有效的、跨分布式应用或框架的资源隔离和共享
- Impala：新一代开源大数据分析引擎，提供Sql语义，比Hive强在速度上
- presto: facebook的开源工具，大数据分布式sql查询引擎
- SNAPPY：快速的数据压缩系统，适用于Hadoop生态系统中
- Kafka:高吞吐量的分布式消息队列系统
- ActiveMQ:是Apache出品，最流行的，能力强劲的开源消息总线
- MQTT:Message Queuing Telemetry Transport，消息队列遥测传输）是IBM开发的一个即时通讯协议，有可能成为物联网的重要组成部分
- RabbitMQ：记得OpenStack就是用的这个东西吧
- ZeroMQ：宣称是将分布式计算变得更简单，是个分布式消息队列，可以看下云风的一篇文章的介绍
- 开源的日志收集系统：scribe、chukwa、kafka、flume。这有一篇对比文章
- Zookeeper：可靠的分布式协调的开源项目
- Databus：LinkedIn 实时低延迟数据抓取系统
- 数据源获取：Flume、Google Refine、Needlebase、ScraperWiki、BloomReach
- 序列化技术：JSON、BSON、Thrift、Avro、Google Protocol Buffers
- NoSql：ScyllaDB（宣称是世界上最快的NoSql）、Apache Casandra、MongoDB、Apache CouchDB、Redis、BigTable、HBase、Hypertable、Voldemort、Neo4j
- MapReduce相关：Hive、Pig、Cascading、Cascalog、mrjob、Caffeine、S4、MapR、Acunu、Flume、Kafka、Azkaban、Oozie、Greenplum
- 数据处理：R、Yahoo! Pipes、Mechanical Turk、Solr/ Lucene、ElasticSearch、Datameer、Bigsheets、Tinkerpop
- NLP自然语言处理：Natural Language Toolkit、Apache OpenNLP、Boilerpipe、OpenCalais
- 机器学习：TensorFlow（Google出品），WEKA、Mahout、scikits.learn、SkyTree
- 可视化技术：GraphViz、Processing、Protovis、Google Fusion Tables、Tableau、Highcharts、EChats（百度的还不错）、Raphaël.js
- Kettle：开源的ETL工具
- Pentaho：以工作流为核心的开源BI系统
- Mondrian：开源的Rolap服务器
- Oozie：开源hadoop的工作流调度引擎，类似的还有：Azkaban
- 开源的数据分析可视化工具：Weka、Orange、KNIME
- Cobar：阿里巴巴的MySql分布式中间件
- 数据清洗：data wrangler， Google Refine

## Python

- PyCharm：最佳Python IDE
- Eric,Eclipse+pydev,比较不错的Python IDE
- PyWin:Win32 api编程包
- numpy:科学计算包，主要用来处理大型矩阵计算等，此外还有SciPy，Matplotlib
- GUI相关：PyQt，PyQwt
- supervisor:进程监控工具
- PyGame: 基于Python的多媒体开发和游戏软件开发模块
- Web框架: Django 开源web开发框架，它鼓励快速开发,并遵循MVC设计


