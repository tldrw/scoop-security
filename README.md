<div align="center">
    <h1 align="center">scoop-security</h1>
    <p align="center">
        Scoop bucket for Penetration Testing and Cybersecurity related tools.
    </p>
    <p align="center">
        <a href="README.md">English</a> | <a href="README-CN.md">简体中文</a>
    </p>
</div>


## Installation

### Install Scoop

[Installation](./Install.md)

### Install software from this bucket

After making sure you have Scoop environment, execute the following command in PowerShell to subscribe to this bucket:

```powershell
scoop bucket add sec https://github.com/tldro/scoop-security
```

Once this is done, you can install any app from this bucket (check the list of files in the [`bucket/` directory](https://github.com/tldro/scoop-security/tree/main/bucket)). For instance, use the following command:

```powershell
# Don't include the .json file extension in the app name
scoop install sec/x64dbg
```

## Featured Apps

### Apps

| Manifest    | Description | Install     |
| ----------- | ----------- | ----------- |
| [afrog](https://github.com/zan8in/afrog) | A high-performance, fast, stable, and PoC-customizable vulnerability scanning tool | scoop install afrog |
| [AntSword](https://github.com/AntSwordProject/AntSword-Loader) | AntSword Loader | scoop install AntSword |
| [Behinder](https://github.com/rebeyond/Behinder) | Dynamic binary encrypted webshell management client | scoop install Behinder |
| [Godzilla](https://github.com/BeichenDream/Godzilla) | Godzilla webshell management tool | scoop install Godzilla |
| [BlueTeamTools](https://github.com/abc123info/BlueTeamTools) | Blue team analysis toolkit featuring memory webshell decompilation, code formatting, cyberspace asset mapping, attribution assistance, decryption of Behinder/Godzilla traffic, decryption of Shiro/CAS/Log4j2 attack payloads, IP/port connection analysis, encoding/decoding utilities, Java deserialization packet analysis, Java class name search, Fofa search, Hunter search, and more. | scoop install BlueTeamTools |
| [BurpSuite](https://portswigger.net) |  | scoop install BurpSuite |
| [CobaltStrike](https://www.cobaltstrike.com) |  | scoop install CobaltStrike |
| [commix](https://github.com/commixproject/commix) | An open-source penetration testing tool that automatically detects and exploits command injection vulnerabilities | scoop install commix |
| [crawlergo](https://github.com/Qianlitp/crawlergo) | A powerful browser crawler for web vulnerability scanning | scoop install crawlergo |
| [dddd](https://github.com/SleepingBag945/dddd) | A highly extensible fingerprint recognition and supply chain vulnerability detection tool. Supports batch target retrieval from Hunter and Fofa. | scoop install dddd |
| [dirmap](https://github.com/H4ckForJob/dirmap) | An advanced web directory and file scanning tool, more powerful than DirBuster, Dirsearch, cansina, and similar tools | scoop install dirmap |
| [Dirscan](https://github.com/corunb/Dirscan) | A high-performance, high-concurrency directory scanner written in Go, supporting GET, HEAD, recursive scanning, proxy, crawler, and more features. | scoop install Dirscan |
| [dirsearch](https://github.com/maurosoria/dirsearch) | Web path scanner | scoop install dirsearch |
| [dnsx](https://github.com/projectdiscovery/dnsx) | A fast and multi-purpose DNS toolkit for running DNS queries | scoop install dnsx |
| [DudeSuite](https://github.com/x364e3ab6/DudeSuite) | Dude Suite Web Penetration Testing Toolkit | scoop install DudeSuite |
| [EHole](https://github.com/EdgeSecurityTeam/EHole) | Red team fingerprint detection tool for key target systems | scoop install EHole |
| [ENScan](https://github.com/wgpsec/ENScan_GO) | A tool based on various enterprise information APIs for solving enterprise information collection challenges. One-click collection of holding company ICP filings, apps, mini programs, WeChat official accounts, and other aggregated information export. | scoop install ENScan |
| [ffuf](https://github.com/ffuf/ffuf) | A fast web fuzzer written in Go | scoop install ffuf |
| [fofaviewer](https://github.com/wgpsec/fofa_viewer) | A FoFa client data viewer developed by WgpSec security team, written in JavaFX, supporting multi-tab queries, Excel export, and more. | scoop install fofa_viewer |
| [fscan](https://github.com/shadow1ng/fscan) | An all-in-one intranet scanning tool for automated, comprehensive vulnerability scanning. | scoop install fscan |
| [Fvuln](https://github.com/d3ckx1/Fvuln) | An automation tool for security services, penetration testers, and red teams. Features include live IP detection, open port scanning, web service detection, web vulnerability scanning, SMB/SSH/FTP/MSSQL brute-force, and extensive web vulnerability detection modules. | scoop install Fvuln |
| [GDA](https://github.com/charles2gan/GDA-android-reversing-Tool) | A powerful Dalvik bytecode decompiler implemented in C++, featuring fast analysis speed, low memory/disk consumption, and strong decompilation capabilities for apk, dex, odex, oat, jar, class, and aar files | scoop install GDA |
| [ghauri](https://github.com/r0oth3x49/ghauri) | An advanced cross-platform tool that automates the process of detecting and exploiting SQL injection security flaws. | scoop install ghauri |
| [goby](https://gobysec.net) | Next-generation cybersecurity technology that builds complete asset databases for rapid security emergency response | scoop install goby |
| [gogo](https://github.com/chainreactors/gogo) | A highly controllable and extensible automation engine for red teams | scoop install gogo |
| [GooFuzz](https://github.com/m3n0sd0n4ld/GooFuzz) | GooFuzz is a tool to perform fuzzing with an OSINT approach. | scoop install GooFuzz |
| [HackBrowserData](https://github.com/moonD4rk/HackBrowserData) | A cross-platform browser data export and decryption tool. | scoop install HackBrowserData |
| [httpx](https://github.com/projectdiscovery/httpx) | httpx is a fast and multi-purpose HTTP toolkit that allows running multiple probes using the retryablehttp library. It is designed to maintain result reliability with an increased number of threads | scoop install httpx |
| [interactsh](https://github.com/projectdiscovery/interactsh) | An OOB interaction gathering server and client library. | scoop install interactsh |
| [JNDInjector](https://github.com/rebeyond/JNDInjector) | A highly customizable JNDI and Java deserialization exploitation tool | scoop install JNDInjector |
| [JYso](https://github.com/qi4L/JYso) | It can be either a JNDIExploit or a ysoserial. | scoop install JYso |
| [katana](https://github.com/projectdiscovery/katana) | A next-generation crawling and spidering framework. | scoop install katana |
| [kscan](https://github.com/lcvvvv/kscan) | Kscan is an all-in-one scanner written in pure Go, featuring port scanning, protocol detection, fingerprint recognition, and brute-force attacks. Supports 1200+ protocols, 10000+ protocol fingerprints, 2000+ application fingerprints, and 10+ brute-force protocols. | scoop install kscan |
| [ksubdomain](https://github.com/knownsec/ksubdomain) | Subdomain enumeration tool, asynchronous dns packets, use pcap to scan 1600,000 subdomains in 1 second | scoop install ksubdomain |
| [masscan](https://github.com/robertdavidgraham/masscan) | TCP port scanner, spews SYN packets asynchronously, scanning entire Internet in under 5 minutes. | scoop install masscan |
| [MDUT](https://github.com/SafeGroceryStore/MDUT) | MDUT - Multiple Database Utilization Tools | scoop install MDUT |
| [mimikatz](https://github.com/gentilkiwi/mimikatz) | A little tool to play with Windows security | scoop install mimikatz |
| [naabu](https://github.com/projectdiscovery/naabu) | projectdiscovery/naabu: A fast port scanner written in go with a focus on reliability and simplicity. Designed to be used in combination with other tools for attack surface discovery in bug bounties and pentests | scoop install naabu |
| [Neo-reGeorg](https://github.com/L-codes/Neo-reGeorg) | Neo-reGeorg is a project that seeks to aggressively refactor reGeorg. | scoop install Neo-reGeorg |
| [netspy](https://github.com/shmilylty/netspy) | netspy is a fast tool for detecting reachable internal network segments (powered by Sangfor DeepBlue Lab Tianwei Team) | scoop install netspy |
| [NimScan](https://github.com/elddy/NimScan) | Fast Port Scanner | scoop install NimScan |
| [nuclei](https://github.com/projectdiscovery/nuclei) | Fast and customizable vulnerability scanner based on simple YAML based DSL | scoop install nuclei |
| [observer_ward](https://github.com/emo-crab/observer_ward) | Observer Ward fingerprint recognition tool | scoop install observer_ward |
| [OneForAll](https://github.com/shmilylty/OneForAll) | OneForAll is a powerful subdomain collection tool | scoop install OneForAll |
| [pagodo](https://github.com/opsdisk/pagodo) | Automate Google Hacking Database scraping and searching | scoop install pagodo |
| [pocsuite3](https://github.com/knownsec/pocsuite3) | pocsuite3 is an open-source remote vulnerability testing framework developed by Knownsec 404 Team | scoop install pocsuite3 |
| [quake_rs](https://github.com/360quake/quake_rs) | Quake Command-Line Application | scoop install quake_rs |
| [rad](https://github.com/chaitin/rad) | A browser crawler designed specifically for security scanning | scoop install rad |
| [rustcat](https://github.com/robiot/rustcat) | The modern Port listener and Reverse shell. | scoop install rustcat |
| [RustScan](https://github.com/RustScan/RustScan) | The Modern Port Scanner. | scoop install RustScan |
| [scan4all](https://github.com/GhostTroops/scan4all) | Vulnerability scanner with 15000+ PoC checks, 23 application weak password brute-force, 7000+ web fingerprints, 146 protocols with 90000+ rules port scanning; ideal for fuzzing, red team exercises, and bug bounty. | scoop install scan4all |
| [sqlmap](https://github.com/sqlmapproject/sqlmap) | sqlmap is an automated SQL injection tool that scans, discovers, and exploits SQL injection vulnerabilities in given URLs | scoop install sqlmap |
| [subfinder](https://github.com/projectdiscovery/subfinder) | Subfinder is a subdomain discovery tool that discovers valid subdomains for websites. Designed as a passive framework to be useful for bug bounties and safe for penetration testing. | scoop install subfinder |
| [suo5](https://github.com/zema1/suo5) | A high-performance HTTP proxy tunneling tool | scoop install suo5 |
| [ToolsFx](https://github.com/Leon406/ToolsFx) | A cross-platform cryptography toolkit based on Kotlin and TornadoFX. Includes encoding/decoding, cipher conversion, encryption/decryption, hash, MAC, signature, big number operations, compression, QR code, CTF utilities, and plugin support. | scoop install ToolsFx |
| [TscanPlus](https://github.com/TideSec/TscanPlus) | A comprehensive cybersecurity detection and operations tool for rapid asset discovery, identification, and detection, revealing vulnerabilities and attack surfaces. | scoop install TscanPlus |
| [Webshell_Generate](https://github.com/cseroad/Webshell_Generate) | Tool for generating various AV-evasion webshells | scoop install Webshell_Generate |
| [woodpecker](https://github.com/woodpecker-framework/woodpecker-framework-release) | Precise detection and deep exploitation framework for high-risk vulnerabilities | scoop install woodpecker |
| [xmap](https://github.com/xvvvan/xmap) | xmap is a user-friendly FOFA and Hunter client written in JavaFX | scoop install xmap |
| [xpoc](https://github.com/chaitin/xpoc) | xpoc is a rapid emergency response tool designed for supply chain vulnerability scanning | scoop install xpoc |
| [xray](https://github.com/chaitin/xray) | A comprehensive security assessment tool supporting common web security issue scanning and custom PoCs | scoop install xray |
| [yakit](https://github.com/yaklang/yakit) | Cyber Security ALL-IN-ONE Platform | scoop install yakit |
| [jar-analyzer](https://github.com/jar-analyzer/jar-analyzer) | A JAR package analysis tool with batch analysis, method call relationship search, string search, Spring analysis, CFG analysis, JVM Stack Frame analysis, remote Tomcat analysis, advanced expression search, custom SQL queries, bytecode viewing, command-line analysis, and simple RASP protection | scoop install jar-analyzer |
| [jar-obfuscator](https://github.com/jar-analyzer/jar-obfuscator) | A JAR/CLASS bytecode obfuscation tool supporting package/class/method/field/parameter name reference analysis and renaming obfuscation, string encryption, integer XOR obfuscation, junk code and opaque predicate injection, method and field hiding, NATIVE layer JVMTI code encryption. Easy to configure with comprehensive documentation. | scoop install jar-obfuscator |
| [java-echo-generator](https://github.com/pen4uin/java-echo-generator) | A highly customizable Java echo payload generation tool | scoop install java-echo-generator |
| [JMG](https://github.com/pen4uin/java-memshell-generator) | A highly customizable Java memory webshell generation tool | scoop install JMG |
| [proguard](https://github.com/Guardsquare/proguard) | ProGuard is a free Java bytecode shrinker, optimizer, obfuscator, and preverifier | scoop install proguard |
| [mitan](https://github.com/kkbo8005/mitan) | Mitan penetration testing tool featuring asset information collection, subdomain brute-force, search syntax, asset mapping (FOFA, Hunter, Quake, ZoomEye), fingerprint recognition, sensitive information collection, file scanning, and password dictionary. | scoop install mitan |
| [proxify](https://github.com/projectdiscovery/proxify) | A versatile and portable proxy for capturing, manipulating, and replaying HTTP/HTTPS traffic on the go. | scoop install proxify |
| [xapp](https://github.com/chaitin/xapp) | A tool focused on web fingerprint recognition | scoop install xapp |
| [XiebroC2](https://github.com/INotGreen/XiebroC2) | Supports multi-person collaborative penetration testing graphical framework. | scoop install XiebroC2 |
| [feroxbuster](https://github.com/epi052/feroxbuster) | A fast, simple, recursive content discovery tool written in Rust. | scoop install feroxbuster |
| [SharpScan](https://github.com/INotGreen/SharpScan) | An intranet asset scanner developed in C#, facilitating lateral movement and domain information collection. | scoop install SharpScan |
| [jadx](https://github.com/skylot/jadx) | Dex to Java decompiler. | scoop install jadx |
| [ImHex](https://github.com/WerWolv/ImHex) | Hex editor | scoop install ImHex |
| [x64dbg](https://github.com/x64dbg/x64dbg) | An open-source x64/x32 debugger for windows. | scoop install x64dbg |
| [P1finger](https://github.com/P001water/P1finger) | Key asset fingerprint recognition tool for red team operations | scoop install P1finger |
| [poc-runner](https://github.com/4ra1n/poc-runner) | Small & Fast Vulnerability Scanner Engine based on XRAY YAML Rule | scoop install poc-runner |
| [qscan](https://github.com/qi4L/qscan) | An intranet scanner faster than Fscan with AV-evasion capabilities | scoop install qscan |
| [ysoserial](https://github.com/frohoff/ysoserial) | A proof-of-concept tool for generating payloads that exploit unsafe Java object deserialization. | scoop install ysoserial |
| [JavaGadgetGenerator](https://github.com/Lotus6/JavaGadgetGenerator) | JavaGadgetGenerator supports ysoserial, Hessian, bytecode, Expr/SSTI, Shiro, JDBC gadget generation, packaging, obfuscation, outbound delay detection, memory webshell injection, and more. | scoop install JavaGadgetGenerator |
| [JDumpSpider](https://github.com/whwlsfb/JDumpSpider) | HeapDump sensitive information extraction tool | scoop install JDumpSpider |
| [JDumpSpiderGUI](https://github.com/DeEpinGh0st/JDumpSpiderGUI) | JDumpSpiderGUI is a Java heap dump analysis tool supporting both command-line and JavaFX GUI modes. It adds a graphical interface to the original tool. | scoop install JDumpSpiderGUI |
| [Ingram](https://github.com/jorhelp/Ingram) | Webcam vulnerability scanning tool | scoop install Ingram |
| [hfinger](https://github.com/HackAllSec/hfinger) | A high-performance command-line tool for web framework, CDN and CMS fingerprinting. | scoop install hfinger |
| [Hawkeye](https://github.com/mir1ce/Hawkeye) | Windows incident response tool - Hawkeye. A comprehensive emergency response analysis tool integrating Windows log analysis, process scanning, and host information. | scoop install Hawkeye |
| [HashcatGui](https://github.com/7797777977/HashcatGui) | Hashcat GUI is a modern graphical user interface designed for the Hashcat password cracking tool, aiming to simplify the password cracking process with a user-friendly experience. Built with PyQt5, featuring a dark theme interface for efficient GPU-accelerated password cracking operations. | scoop install HashcatGui |
| [fine](https://github.com/fasnow/fine) | Cyberspace asset mapping, ICP filing, equity structure diagrams, IP138 domain resolution and reverse IP lookup, external HTTP calls, and mini-program decompilation. | scoop install fine |
| [EZ](https://github.com/m-sec-org/EZ) | EZ is a cross-platform vulnerability scanner integrating information collection, port scanning, service brute-force, URL crawling, fingerprint recognition, and passive scanning. | scoop install EZ |
| [EquationToolsGUI](https://github.com/abc123info/EquationToolsGUI) | A GUI version of the NSA Equation Group toolkit, developed by ABC_123 since 2017. Used for scanning and verifying MS17-010, MS09-050, MS08-067 vulnerabilities, and assisting administrators in patching system vulnerabilities. | scoop install EquationToolsGUI |
| [DockerAPITool](https://github.com/Janhsu/DockerAPITool) | Docker Remote API unauthorized access (port 2375) exploitation tool, supporting container escape | scoop install DockerAPITool |
| [DockerApiRCE](https://github.com/0xchang/DockerApiRCE) | DockerApiRCE | scoop install DockerApiRCE |
| [Docker-Registry-exp](https://github.com/mhtsec/Docker-Registry-exp) | A powerful Docker Registry port 5000 unauthorized browsing, downloading, and security testing tool, integrating image management, authentication brute-force, sensitive information search, and other practical features. | scoop install Docker-Registry-exp |
| [cloudTools](https://github.com/dark-kingA/cloudTools) | Cloud asset management tool for cloud security. Two modules: cloud storage tool (OSS storage viewing, deletion, upload, download, preview, etc.) and cloud service tool (RDS and server management, viewing, command execution, takeover, etc.) | scoop install cloudTools |
| [AuxTools](https://github.com/doimet/AuxTools) | GUI-based penetration testing auxiliary tool featuring data collection, information gathering, site scanning, port scanning, vulnerability exploitation, command generation, command analysis, subnet merging, DNS records, Host collision, ChatGPT, data decryption, credential lookup, encoding/decoding, encryption/decryption, random generation, pinyin conversion, API testing, WebSocket. | scoop install AuxTools |
| ...                                                       | ...                                                          | ...                         |



### Burp Suite Extensions

> Add some Burp Suite extensions. When adding extension to Burp Suite, please select the programs under `current` folder in the extension directory to avoid the problem of adding extension repeatedly after version update.

| Manifest    | Description | Install     |
| ----------- | ----------- | ----------- |
| [BurpShiroPassiveScan](https://github.com/pmiaowu/BurpShiroPassiveScan) | A BurpSuite-based passive Shiro detection plugin                       | scoop install BurpShiroPassiveScan  |
| [BurpFastJsonScan](https://github.com/pmiaowu/BurpFastJsonScan) | A BurpSuite-based passive FastJson detection plugin                    | scoop install BurpFastJsonScan      |
| [sqlmap4burp-plus-plus](https://github.com/c0ny1/sqlmap4burp-plus-plus) | Burp Suite integration plugin for sqlmap                                           | scoop install sqlmap4burp-plus-plus |
| [HaE](https://github.com/gh0stkey/HaE)                       | Highlighter and Extractor, Empower ethical hacker for efficient operations | scoop install HaE                   |
| [CaA](https://github.com/gh0stkey/CaA)                       | CaA is a traffic collection and analysis plugin developed based on BurpSuite Java Plugin API   | scoop install CaA                   |
| [RouteVulScan](https://github.com/F6JO/RouteVulScan)         | Route Vulnerable scanning | scoop install RouteVulScan          |
| [TsojanScan](https://github.com/Tsojan/TsojanScan)           | An integrated BurpSuite vulnerability detection plug-in. | scoop install TsojanScan            |
| [OneScan](https://github.com/vaycore/OneScan)                | OneScan is a BurpSuite plugin for recursive directory scanning                         | scoop install OneScan               |
| [BypassPro](https://github.com/0x727/BypassPro)              | A BurpSuite plugin for automated authorization bypass                        | scoop install BypassPro             |
| [HopLa](https://github.com/synacktiv/HopLa)                  | Adds autocompletion support and useful payloads in Burp Suite. | scoop install HopLa                 |
| [CloudX](https://github.com/cloud-jie/CloudX)         | A rule-based encryption/decryption and signature-breaking tool | scoop install CloudX          |
| [BurpCrypto](https://github.com/whwlsfb/BurpCrypto)           | BurpCrypto is a collection of burpsuite encryption plug-ins, support AES/RSA/DES/ExecJs(execute JS encryption code in burpsuite). | scoop install BurpCrypto            |
| [Fiora](https://github.com/bit4woo/Fiora)                | A GUI version of the Nuclei vulnerability PoC framework. Quickly search PoCs, run Nuclei with one click. Can run as a standalone program or as a Burp plugin.                         | scoop install Fiora               |
| [RVScan](https://github.com/XF-FS/RVScan)              | RVScan is a powerful Burp Suite extension designed for automated web application security testing and vulnerability scanning. It provides comprehensive path discovery, bypass techniques, EHole fingerprint recognition, and customizable scanning rules.                        | scoop install RVScan             |
| [turbo-intruder](https://github.com/PortSwigger/turbo-intruder)                  | Turbo Intruder is a Burp Suite extension for sending large numbers of HTTP requests and analyzing the results. | scoop install turbo-intruder                 |
| [Axon](https://github.com/tldrw/Axon) | Burp Suite Operations Toolkit Shortcut Menu Extension. | scoop install Axon |
| [DetSql](https://github.com/saoshao/DetSql) | DetSql is a Burp Suite-based SQL injection detection plugin with sqlmap integration support. | scoop install DetSql |
| [Galaxy](https://github.com/outlaws-bai/Galaxy) | A Burp plugin that makes testing encrypted messages as simple as plain text, supporting the use of js/python/java to implement hook scripts or any language to implement grpc/http hook services to automatically decrypt messages. | scoop install Galaxy |
| [OssScan](https://github.com/hookdd/OssScan) | A Burp plugin for passive OSS vulnerability scanning | scoop install OssScan |
| [Upload_Auto_Fuzz](https://github.com/T3nk0/Upload_Auto_Fuzz) | This Burp Suite plugin is designed for file upload vulnerability detection, providing automated fuzz testing with 300+ payloads. | scoop install Upload_Auto_Fuzz |
| [burp-variables](https://github.com/0xceba/burp_variables) | Burp Suite variable management plugin for managing and using variables during penetration testing. | scoop install burp-variables |
| [nowafpls](https://github.com/assetnote/nowafpls) | A Burp Suite-based WAF bypass plugin that bypasses WAF restrictions by inserting junk data. | scoop install nowafpls |
| [xia_tan](https://github.com/mapl3miss/xia_tan) | xia_tan - BurpSuite multi-vulnerability automated detection plugin | scoop install xia_tan |
| ...                                                          | ...                                                          | ...                                 |



### Other Apps

| Manifest    | Description | Install     |
| ----------- | ----------- | ----------- |
| [openjdk](https://openjfx.io)                                | Resolves missing JavaFX dependency issues when running some software on newer Java versions           | scoop install openjdk          |
| [notify](https://github.com/projectdiscovery/notify)         | Relays output from multiple tools and notifies supported platforms                       | scoop install notify           |
| [npcap](https://npcap.com)                                   | A network packet capture SDK developed specifically for Windows                          | scoop install npcap            |
| [winscp](https://winscp.net)                                 | An open-source graphical SFTP client using SSH for Windows               | scoop install winscp           |
| [HashCalculator](https://github.com/hrpzcf/HashCalculator)   | Batch file hash value calculator                                         | scoop install HashCalculator   |
| [RevokeMsgPatcher](https://github.com/huiyadanli/RevokeMsgPatcher) | Anti-recall patch for PC WeChat/QQ/TIM                                    | scoop install RevokeMsgPatcher |
| [Everything](https://www.voidtools.com)                      | Locate files and folders by name instantly. | scoop install Everything       |
| [RustDesk](https://github.com/rustdesk/rustdesk)             | An open-source remote desktop application designed for self-hosting. | scoop install RustDesk         |
| [SublimeText](https://www.sublimetext.com/)                  | A text editor.                          | scoop install SublimeText      |
| [TinyRDM](https://redis.tinycraft.cc/)                       | A modern lightweight cross-platform Redis Desktop Manager. | scoop install TinyRDM          |
| ...                                                          | ...                                                          | ...                            |



## Question
**1. I want some other apps!**

Please open new app request [issue].

**2. Some apps are outdated, please update it!**

Be a contributor! Fork it, update the outdated apps app manifest, and file pull-request.



## Thanks
- [ScoopInstaller/Scoop: A command-line installer for Windows.](https://github.com/ScoopInstaller/Scoop)
- [chawyehsu/dorado: 🐟 Yet Another bucket for lovely Scoop](https://github.com/chawyehsu/dorado)
- [ScoopInstaller/Extras: 📦 The Extras bucket for Scoop.](https://github.com/ScoopInstaller/Extras)
- [arch3rPro/PST-Bucket](https://github.com/arch3rPro/PST-Bucket)



## Star
[![Stargazers over time](https://starchart.cc/tldro/scoop-security.svg?variant=adaptive)](https://starchart.cc/tldro/scoop-security)




[issue]: https://github.com/tldro/scoop-security/issues
