<div align="center">
    <h1 align="center">scoop-security</h1>
    <p align="center">
        scoop-security 是一个用于渗透测试和网络安全相关工具下载、安装和自动更新的Scoop软件仓库。
    </p>
    <p align="center">
        <a href="README.md">English</a> | <a href="README-CN.md">简体中文</a>
    </p>
</div>



## 安装

### 安装Scoop

[Scoop安装教程](./Install.md)

### 安装该仓库中的软件

确保你已经有 Scoop 环境，执行以下命令订阅本软件仓库:

```powershell
scoop bucket add sec https://github.com/tldro/scoop-security
```

执行以下命令安装本仓库中的软件:

```powershell
scoop install sec/x64dbg
```

## 支持软件

### Apps

| 软件        | 描述         | 安装        |
| ----------- | ----------- | ----------- |
| [afrog](https://github.com/zan8in/afrog) | afrog 是一款性能卓越、快速稳定、PoC 可定制化的漏洞扫描工具 | scoop install afrog |
| [AntSword](https://github.com/AntSwordProject/AntSword-Loader) | AntSword 加载器 | scoop install AntSword |
| [Behinder](https://github.com/rebeyond/Behinder) | “冰蝎”动态二进制加密网站管理客户端 | scoop install Behinder |
| [Godzilla](https://github.com/BeichenDream/Godzilla) | 哥斯拉 | scoop install Godzilla |
| [BlueTeamTools](https://github.com/abc123info/BlueTeamTools) | 蓝队分析研判工具箱，功能包括内存马反编译分析、各种代码格式化、网空资产测绘功能、溯源辅助、解密冰蝎流量、解密哥斯拉流量、解密Shiro/CAS/Log4j2的攻击payload、IP/端口连接分析、各种编码/解码功能、蓝队分析常用网址、java反序列化数据包分析、Java类名搜索、Fofa搜索、Hunter搜索等。 | scoop install BlueTeamTools |
| [BurpSuite](https://portswigger.net) |  | scoop install burpsuite |
| [CobaltStrike](https://www.cobaltstrike.com) |  | scoop install cobaltstrike |
| [commix](https://github.com/commixproject/commix) | 一个开源渗透测试工具，可自动检测和利用命令注入漏洞 | scoop install commix |
| [crawlergo](https://github.com/Qianlitp/crawlergo) | 一款功能强大的浏览器爬虫，用于扫描网页漏洞 | scoop install crawlergo |
| [dddd](https://github.com/SleepingBag945/dddd) | 一款高可拓展的指纹识别、供应链漏洞探测工具。支持从Hunter、Fofa批量拉取目标。 | scoop install dddd |
| [dirmap](https://github.com/H4ckForJob/dirmap) | 一个高级web目录、文件扫描工具，功能将会强于DirBuster、Dirsearch、cansina、御剑 | scoop install dirmap |
| [Dirscan](https://github.com/corunb/Dirscan) | 一款由go编写的高性能、高并发的目录扫描器，现在已经支持GET、HEAD、递归扫描、代理、爬虫等功能功能,后续努力实现更多功能。 | scoop install Dirscan |
| [dirsearch](https://github.com/maurosoria/dirsearch) | web路径扫描 | scoop install dirsearch |
| [dnsx](https://github.com/projectdiscovery/dnsx) | 一个快速和多用途的DNS工具包，用于运行DNS查询 | scoop install dnsx |
| [DudeSuite](https://github.com/x364e3ab6/DudeSuite) | Dude Suite Web 渗透测试工具集 | scoop install DudeSuite |
| [EHole](https://github.com/EdgeSecurityTeam/EHole) | 红队重点攻击系统指纹探测工具 | scoop install EHole |
| [ENScan](https://github.com/wgpsec/ENScan_GO) | 一款基于各大企业信息API的工具，解决在遇到的各种针对国内企业信息收集难题。一键收集控股公司ICP备案、APP、小程序、微信公众号等信息聚合导出。 | scoop install ENScan |
| [ffuf](https://github.com/ffuf/ffuf) | 用 Go 编写的快速 Web 模糊测试器 | scoop install ffuf |
| [fofaviewer](https://github.com/wgpsec/fofa_viewer) | 一个由WgpSec狼组安全团队开发的FoFa客户端数据查看工具，使用JavaFX编写，支持多标签查询、导出Excel文件等功能。 | scoop install fofa_viewer |
| [fscan](https://github.com/shadow1ng/fscan) | 一款内网综合扫描工具，方便一键自动化、全方位漏扫扫描。 | scoop install fscan |
| [Fvuln](https://github.com/d3ckx1/Fvuln) | 一款自动化工具，主要适用于日常安全服务、渗透测试人员和RedTeam红队人员，它集合的功能包括：存活IP探测、开放端口探测、web服务探测、web漏洞扫描、smb爆破、ssh爆破、ftp爆破、mssql爆破等其他数据库爆破工作以及大量web漏洞检测模块。 | scoop install Fvuln |
| [GDA](https://github.com/charles2gan/GDA-android-reversing-Tool) | 一个用C++实现的强大的Dalvik字节码反编译器，具有分析速度快，内存磁盘消耗低等优点，对apk、dex、odex、oat、jar、class、aar文件有较强的反编译能力 | scoop install GDA |
| [ghauri](https://github.com/r0oth3x49/ghauri) | 一款先进的跨平台工具，可自动检测和利用SQL注入安全漏洞。 | scoop install ghauri |
| [goby](https://gobysec.net) | 新一代网络安全技术，通过为目标建立完整的资产数据库，实现快速的安全应急 | scoop install goby |
| [gogo](https://github.com/chainreactors/gogo) | 面向红队的, 高度可控可拓展的自动化引擎 | scoop install gogo |
| [GooFuzz](https://github.com/m3n0sd0n4ld/GooFuzz) | GooFuzz 是一款采用 OSINT 方法进行模糊测试的工具，它能够枚举目录、文件、子域或参数，而不会在目标服务器上留下任何痕迹，并且可以通过高级 Google 搜索（Google Dorking）来实现。 | scoop install GooFuzz |
| [HackBrowserData](https://github.com/moonD4rk/HackBrowserData) | 一款可全平台运行的浏览器数据导出解密工具。 | scoop install HackBrowserData |
| [httpx](https://github.com/projectdiscovery/httpx) | httpx是一个快速且多用途的HTTP工具包，允许使用retryablehttp库运行多个探测。它旨在在增加线程数的同时保持结果可靠性。 | scoop install httpx |
| [interactsh](https://github.com/projectdiscovery/interactsh) | 一个带外交互收集服务器和客户端库。 | scoop install interactsh |
| [JNDInjector](https://github.com/rebeyond/JNDInjector) | 一个高度可定制化的JNDI和Java反序列化利用工具 | scoop install JNDInjector |
| [JYso](https://github.com/qi4L/JYso) | 它可以是JNDIExploit或ysoserial。 | scoop install JYso |
| [katana](https://github.com/projectdiscovery/katana) | 一个下一代爬虫和蜘蛛框架。 | scoop install katana |
| [kscan](https://github.com/lcvvvv/kscan) | Kscan 是一款纯 go 开发的全方位扫描器，具备端口扫描、协议检测、指纹识别，暴力破解等功能。支持协议 1200+，协议指纹 10000+，应用指纹 2000+，暴力破解协议 10 余种。 | scoop install kscan |
| [ksubdomain](https://github.com/knownsec/ksubdomain) | 子域名枚举工具，异步DNS数据包，使用pcap每秒扫描160万个子域名 | scoop install ksubdomain |
| [masscan](https://github.com/robertdavidgraham/masscan) | TCP端口扫描器，异步发送SYN数据包，可在5分钟内扫描整个互联网。 | scoop install masscan |
| [MDUT](https://github.com/SafeGroceryStore/MDUT) | MDUT - 多数据库利用工具 | scoop install MDUT |
| [mimikatz](https://github.com/gentilkiwi/mimikatz) | 一个用于Windows安全的小工具 | scoop install mimikatz |
| [naabu](https://github.com/projectdiscovery/naabu) | 一个用Go编写的快速端口扫描器，专注于可靠性和简洁性。设计用于与其他工具结合，在漏洞赏金和渗透测试中进行攻击面发现。 | scoop install naabu |
| [Neo-reGeorg](https://github.com/L-codes/Neo-reGeorg) | Neo-reGeorg是一个旨在积极重构reGeorg的项目。 | scoop install Neo-reGeorg |
| [netspy](https://github.com/shmilylty/netspy) | netspy是一款快速探测内网可达网段工具（深信服深蓝实验室天威战队强力驱动） | scoop install netspy |
| [NimScan](https://github.com/elddy/NimScan) | 快速端口扫描器 | scoop install NimScan |
| [nuclei](https://github.com/projectdiscovery/nuclei) | 基于简单YAML DSL的快速可定制漏洞扫描器 | scoop install nuclei |
| [observer_ward](https://github.com/emo-crab/observer_ward) | 侦查守卫指纹识别工具 | scoop install observer_ward |
| [OneForAll](https://github.com/shmilylty/OneForAll) | OneForAll是一款功能强大的子域收集工具 | scoop install OneForAll |
| [pagodo](https://github.com/opsdisk/pagodo) | 自动执行 Google Hacking 数据库抓取和搜索 | scoop install pagodo |
| [pocsuite3](https://github.com/knownsec/pocsuite3) | pocsuite3是知道创宇404团队开发的开源远程漏洞测试框架 | scoop install pocsuite3 |
| [quake_rs](https://github.com/360quake/quake_rs) | Quake命令行应用程序 | scoop install quake_rs |
| [rad](https://github.com/chaitin/rad) | 一款专为安全扫描而生的浏览器爬虫 | scoop install rad |
| [rustcat](https://github.com/robiot/rustcat) | 现代端口监听器和反弹shell工具。 | scoop install rustcat |
| [RustScan](https://github.com/RustScan/RustScan) | 现代端口扫描器。 | scoop install RustScan |
| [scan4all](https://github.com/GhostTroops/scan4all) | Vulnerabilities Scan；15000+PoC漏洞扫描；[ 23 ] 种应用弱口令爆破；7000+Web指纹；146种协议90000+规则Port扫描；Fuzz、HW打点、BugBounty神器... | scoop install scan4all |
| [sqlmap](https://github.com/sqlmapproject/sqlmap) | sqlmap是一个自动化的SQL注入工具，其主要功能是扫描，发现并利用给定的URL进行SQL注入 | scoop install sqlmap |
| [subfinder](https://github.com/projectdiscovery/subfinder) | Subfinder是一个子域名发现工具，用于发现网站的有效子域名。设计为被动框架，对漏洞赏金有用且对渗透测试安全。 | scoop install subfinder |
| [suo5](https://github.com/zema1/suo5) | 一款高性能 HTTP 代理隧道工具 | scoop install suo5 |
| [ToolsFx](https://github.com/Leon406/ToolsFx) | 基于kotlin+tornadoFx的跨平台密码学工具箱.包含编解码,编码转换,加解密, 哈希,MAC,签名,大数运算,压缩,二维码功能,ctf等实用功能,支持插件. | scoop install ToolsFx |
| [TscanPlus](https://github.com/TideSec/TscanPlus) | 综合性网络安全检测和运维工具,快速进行资产发现、识别、检测,发现存在的薄弱点和攻击面. | scoop install TscanPlus |
| [Webshell_Generate](https://github.com/cseroad/Webshell_Generate) | 用于生成各类免杀webshell | scoop install Webshell_Generate |
| [woodpecker](https://github.com/woodpecker-framework/woodpecker-framework-release) | 高危漏洞精准检测与深度利用框架 | scoop install woodpecker |
| [xmap](https://github.com/xvvvan/xmap) | xmap 是一个用 JavaFX 编写的用户友好的 FOFA、Hunter 客户端 | scoop install xmap |
| [xpoc](https://github.com/chaitin/xpoc) | xpoc 为供应链漏洞扫描设计的快速应急响应工具 | scoop install xpoc |
| [xray](https://github.com/chaitin/xray) | 一款完善的安全评估工具，支持常见 web 安全问题扫描和自定义 poc | scoop install xray |
| [yakit](https://github.com/yaklang/yakit) | 网络安全一体化平台 | scoop install yakit |
| [jar-analyzer](https://github.com/jar-analyzer/jar-analyzer) | 一个JAR包分析工具，批量分析搜索，方法调用关系搜索，字符串搜索，Spring分析，CFG分析，JVM Stack Frame分析，远程分析Tomcat，进阶表达式搜索，自定义SQL查询，字节码查看，命令行分析，使用简易RASP保护 | scoop install jar-analyzer |
| [jar-obfuscator](https://github.com/jar-analyzer/jar-obfuscator) | 一个 JAR/CLASS 字节码混淆工具，支持包名/类名/方法名/字段名/参数名引用分析和重命名混淆方式，支持字符串加密/整型异或混淆/垃圾代码花指令混淆/等方式，支持方法和字段的隐藏，支持 NATIVE 层的 JVMTI 代码加密，配置简单，文档教程齐全，容易上手 | scoop install jar-obfuscator |
| [java-echo-generator](https://github.com/pen4uin/java-echo-generator) | 一款支持高度自定义的 Java 回显载荷生成工具 | scoop install java-echo-generator |
| [java-memshell-generator](https://github.com/pen4uin/java-memshell-generator) | 一款支持高度自定义的 Java 内存马生成工具 | scoop install java-memshell-generator |
| [proguard](https://github.com/Guardsquare/proguard) | ProGuard 是一个免费的 Java 字节码压缩器、优化器、混淆器和预验证器 | scoop install proguard |
| [mitan](https://github.com/kkbo8005/mitan) | 密探渗透测试工具包含资产信息收集，子域名爆破，搜索语法，资产测绘（FOFA，Hunter，quake, ZoomEye），指纹识别，敏感信息采集，文件扫描、密码字典等功能 | scoop install mitan |
| [proxify](https://github.com/projectdiscovery/proxify) | 一个多功能便携式代理，用于捕获、操纵和重放HTTP/HTTPS流量。 | scoop install proxify |
| [xapp](https://github.com/chaitin/xapp) | 专注于web指纹识别的工具 | scoop install xapp |
| [XiebroC2](https://github.com/INotGreen/XiebroC2) | 支持多人协作渗透测试图形框架。 | scoop install XiebroC2 |
| [feroxbuster](https://github.com/epi052/feroxbuster) | 一个用 Rust 编写的快速，简单，递归的内容发现工具。 | scoop install feroxbuster |
| [SharpScan](https://github.com/INotGreen/SharpScan) | C#开发的内网资产扫描器，方便内网横向移动和域内信息收集。 | scoop install SharpScan |
| [jadx](https://github.com/skylot/jadx) | 一个从Android Dex到Java的反编译器 | scoop install jadx |
| [ImHex](https://github.com/WerWolv/ImHex) | 十六进制编辑器 | scoop install ImHex |
| [x64dbg](https://github.com/x64dbg/x64dbg) | 一个开源的Windows动态反汇编调试器 | scoop install x64dbg |
| [P1finger](https://github.com/P001water/P1finger) | 红队行动下的重点资产指纹识别工具 | scoop install P1finger |
| [poc-runner](https://github.com/4ra1n/poc-runner) | 基于 XRAY YAML 规则的超轻量快速漏洞扫描引擎 | scoop install poc-runner |
| [qscan](https://github.com/qi4L/qscan) | 一个比Fscan更快，且免杀的内网扫描器 | scoop install qscan |
| [ysoserial](https://github.com/frohoff/ysoserial) | 一个概念验证工具，用于生成利用不安全Java对象反序列化的有效载荷。 | scoop install ysoserial |
| [JavaGadgetGenerator](https://github.com/Lotus6/JavaGadgetGenerator) | JavaGadgetGenerator 工具，支持 ysoserial，Hessian，字节码，Expr/SSTI，Shiro，JDBC 等 Gadget 生成，封装，混淆，出网延迟探测，内存马注入等... | scoop install JavaGadgetGenerator |
| [JDumpSpider](https://github.com/whwlsfb/JDumpSpider) | HeapDump敏感信息提取工具 | scoop install JDumpSpider |
| [JDumpSpiderGUI](https://github.com/DeEpinGh0st/JDumpSpiderGUI) | JDumpSpiderGUI 是一个用于 Java 堆转储文件分析的工具，支持命令行和 JavaFX 图形界面两种模式。该工具主要是在原工具上添加了图形化的界面 | scoop install JDumpSpiderGUI |
| [Ingram](https://github.com/jorhelp/Ingram) | 网络摄像头漏洞扫描工具 | scoop install Ingram |
| [hfinger](https://github.com/HackAllSec/hfinger) | 一个用于web框架、CDN和CMS指纹识别的高性能命令行工具。 | scoop install hfinger |
| [Hawkeye](https://github.com/mir1ce/Hawkeye) | Windows应急响应工具---Hawkeye(鹰眼)。集Windows日志分析，进程扫描，主机信息于一体的综合应急响应分析工具 | scoop install Hawkeye |
| [HashcatGui](https://github.com/7797777977/HashcatGui) | Hashcat GUI是一个为Hashcat密码破解工具设计的现代化图形用户界面，旨在简化密码破解过程，提供友好的用户体验。本工具采用PyQt5构建，具有暗色主题界面，使用户能够轻松地利用GPU加速进行高效的密码破解操作。 | scoop install HashcatGui |
| [fine](https://github.com/fasnow/fine) | 网络空间资产测绘、ICP备案、天眼查股权结构图、IP138域名解析与IP反查、外部HTTP调用与小程序反编译。 | scoop install fine |
| [EZ](https://github.com/m-sec-org/EZ) | EZ是一款集信息收集、端口扫描、服务暴破、URL爬虫、指纹识别、被动扫描为一体的跨平台漏洞扫描器。 | scoop install EZ |
| [EquationToolsGUI](https://github.com/abc123info/EquationToolsGUI) | 本程序为美国NSA的方程式工具包图形界面版，由ABC_123于2017年开始编写，仅用来扫描和验证MS17-010、MS09-050、MS08-067漏洞，并可协助管理员修复系统漏洞。 | scoop install EquationToolsGUI |
| [DockerAPITool](https://github.com/Janhsu/DockerAPITool) | DockerRemoteAPI未授权访问(2375端口)利用工具，支持容器逃逸 | scoop install DockerAPITool |
| [DockerApiRCE](https://github.com/0xchang/DockerApiRCE) | DockerApiRCE | scoop install DockerApiRCE |
| [Docker-Registry-exp](https://github.com/mhtsec/Docker-Registry-exp) | 一款功能强大的Docker Registry 5000端口未授权浏览、下载和安全测试工具，集成了镜像管理、认证爆破、敏感信息搜索等多项实用功能。 | scoop install Docker-Registry-exp |
| [cloudTools](https://github.com/dark-kingA/cloudTools) | 云资产管理工具 目前工具定位是云安全相关工具，目前是两个模块 云存储工具、云服务工具， 云存储工具主要是针对oss存储、查看、删除、上传、下载、预览等等 云服务工具主要是针对rds、服务器的管理，查看、执行命令、接管等等 | scoop install cloudTools |
| [AuxTools](https://github.com/doimet/AuxTools) | 图形化渗透测试辅助工具 数据收集、信息收集、站点扫描、端口扫描、漏洞利用、命令生成、命令分析、网段合并、DNS记录、Host碰撞、ChatGPT、数据解密、口令查询、编码解码、加密解密、随机生成、汉拼转换、接口测试、WebSocket | scoop install AuxTools |
| ...                                                       | ...                                                          | ...                         |



### Burp Suite Extensions

> 增加部分BurpSuite插件自动更新，BurpSuite 添加插件时，请选择插件目录中`current`文件夹下的程序，避免版本更新后需重复添加插件的问题

| 软件        | 描述         | 安装        |
| ----------- | ----------- | ----------- |
| [BurpShiroPassiveScan](https://github.com/pmiaowu/BurpShiroPassiveScan) | 一款基于BurpSuite的被动式shiro检测插件                       | scoop install BurpShiroPassiveScan  |
| [BurpFastJsonScan](https://github.com/pmiaowu/BurpFastJsonScan) | 一款基于BurpSuite的被动式FastJson检测插件                    | scoop install BurpFastJsonScan      |
| [sqlmap4burp-plus-plus](https://github.com/c0ny1/sqlmap4burp-plus-plus) | burp联动sqlmap插件                                           | scoop install sqlmap4burp-plus-plus |
| [HaE](https://github.com/gh0stkey/HaE)                       | HaE是一款可以快速挖掘目标指纹和关键信息高亮显示的Burp插件 | scoop install HaE                   |
| [CaA](https://github.com/gh0stkey/CaA)                       | CaA是一个基于BurpSuite Java插件API开发的流量收集和分析插件   | scoop install CaA                   |
| [RouteVulScan](https://github.com/F6JO/RouteVulScan)         | 递归式被动检测脆弱路径的burp插件</br>Route Vulnerable scanning | scoop install RouteVulScan          |
| [TsojanScan](https://github.com/Tsojan/TsojanScan)           | 一个集成的BurpSuite漏洞探测插件           |
| [OneScan](https://github.com/vaycore/OneScan)                | OneScan是递归目录扫描的BurpSuite插件                         | scoop install OneScan               |
| [BypassPro](https://github.com/0x727/BypassPro)              | 对权限绕过自动化bypass的burpsuite插件                        | scoop install BypassPro             |
| [HopLa](https://github.com/synacktiv/HopLa)                  | 一个自动添加，填充测试片段的BurpSuite插件。 | scoop install HopLa                 |
| [CloudX](https://github.com/cloud-jie/CloudX)         | 一个基于规则的加解密破签工具 | scoop install CloudX          |
| [BurpCrypto](https://github.com/whwlsfb/BurpCrypto)           | 支持多种加密算法或直接执行JS代码的用于爆破前端加密的BurpSuite插件 | scoop install BurpCrypto            |
| [Fiora](https://github.com/bit4woo/Fiora)                | 漏洞PoC框架Nuclei的图形版。快捷搜索PoC、一键运行Nuclei。即可作为独立程序运行，也可作为burp插件使用。                         | scoop install Fiora               |
| [RVScan](https://github.com/XF-FS/RVScan)              | RVScan 是一个功能强大的 Burp Suite 扩展插件，专为自动化Web应用程序安全测试和漏洞扫描而设计。它提供全面的路径发现、绕过技术、EHole指纹识别和可定制的扫描规则。                        | scoop install RVScan             |
| [turbo-intruder](https://github.com/PortSwigger/turbo-intruder)                  | Turbo Intruder 是一个 Burp Suite 扩展，用于发送大量 HTTP 请求并分析结果。 | scoop install turbo-intruder                 |
| [Axon](https://github.com/tldrw/Axon) | Burp Suite 常用工具集快捷菜单插件 | scoop install Axon |
| [DetSql](https://github.com/saoshao/DetSql) | 基于 Burp Suite 的 SQL 注入检测插件，支持 sqlmap 集成。 | scoop install DetSql |
| [Galaxy](https://github.com/outlaws-bai/Galaxy) | Burp插件，让你测试加密报文时像明文一样简单，支持用js/python/java实现hook脚本或任意语言实现grpc/http hook服务来自动解密报文。 | scoop install Galaxy |
| [OssScan](https://github.com/hookdd/OssScan) | burp插件,Oss漏洞被动扫描 | scoop install OssScan |
| [Upload_Auto_Fuzz](https://github.com/T3nk0/Upload_Auto_Fuzz) | 本Burp Suite插件专为文件上传漏洞检测设计，提供自动化Fuzz测试，共300+条payload。 | scoop install Upload_Auto_Fuzz |
| [burp-variables](https://github.com/0xceba/burp_variables) | Burp Suite变量管理插件，用于在渗透测试过程中管理和使用变量。 | scoop install burp-variables |
| [nowafpls](https://github.com/assetnote/nowafpls) | 一个基于 Burp Suite 的 WAF 绕过插件，通过插入垃圾数据绕过 WAF 限制。 | scoop install nowafpls |
| [xia_tan](https://github.com/mapl3miss/xia_tan) | xia_tan（瞎探）- BurpSuite 多漏洞自动化探测插件 | scoop install xia_tan |
| ...                                                          | ...                                                          | ...                                 |



### Other Apps

| 软件        | 描述         | 安装        |
| ----------- | ----------- | ----------- |
| [openjdk](https://openjfx.io)                                | 解决部分软件在高版本JAVA运行时缺少javafx依赖的问题           | scoop install openjdk          |
| [notify](https://github.com/projectdiscovery/notify)         | 辅助多个工具的输出并通知到受支持的平台                       | scoop install notify           |
| [npcap](https://npcap.com)                                   | 专为 Windows 开发的一款网络抓包 SDK                          | scoop install npcap            |
| [winscp](https://winscp.net)                                 | 一个Windows环境下使用SSH的开源图形化SFTP客户端               | scoop install winscp           |
| [HashCalculator](https://github.com/hrpzcf/HashCalculator)   | 文件哈希值批量计算器                                         | scoop install HashCalculator   |
| [RevokeMsgPatcher](https://github.com/huiyadanli/RevokeMsgPatcher) | PC版微信/QQ/TIM防撤回补丁                                    | scoop install RevokeMsgPatcher |
| [Everything](https://www.voidtools.com)                      | 文件搜索工具，基于名称快速定位文件和文件夹。 | scoop install Everything       |
| [RustDesk](https://github.com/rustdesk/rustdesk)             | 一个用 Rust 语言编写专为自托管而设计的开源远程桌面软件。 | scoop install RustDesk         |
| [SublimeText](https://www.sublimetext.com/)                  | 一个文本编辑器。                          | scoop install SublimeText      |
| [TinyRDM](https://redis.tinycraft.cc/)                       | 一款现代轻量级跨平台 Redis 桌面管理器。          |
| ...                                                          | ...                                                          | ...                            |



## 疑问
**1. 我想要某个软件，这个仓库里没有！**

开 [issue]，描述你的需求。


**2. 仓库中的某个软件版本落后了，求更新！**

欢迎 Fork 本仓库，修改落后的软件清单，并提交你的拉取请求。



## 致谢
感谢以下仓库在本仓库部分软件规则编写时提供了参考：
- [ScoopInstaller/Scoop: A command-line installer for Windows.](https://github.com/ScoopInstaller/Scoop)
- [chawyehsu/dorado: 🐟 Yet Another bucket for lovely Scoop](https://github.com/chawyehsu/dorado)
- [ScoopInstaller/Extras: 📦 The Extras bucket for Scoop.](https://github.com/ScoopInstaller/Extras)
- [arch3rPro/PST-Bucket](https://github.com/arch3rPro/PST-Bucket)



[issue]: https://github.com/tldro/scoop-security/issues
