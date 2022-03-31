# 《深入理解SAST静态应用安全测试》
SAST在安全领域极其重要，不仅是解决漏洞的有效利器，更是基础安全之上发现漏洞的有效方法。尽管SAST有时弊病百出，比如严重依赖规则、误报漏报率太高、特定漏洞无法检测等问题。但SAST的发展从根本上推动了安全漏洞的发展，弥补了DAST的不足，促进了IAST的落地。代码审计是SAST，SAST不只是代码审计！作者：[0e0w](https://github.com/0e0w)

本项目创建于2022年1月22日，最近的一次更新时间为2022年3月31日。项目会持续更新，直到海枯石烂！

- [01-SAST资源](https://github.com/ASTTeam/SAST#01-sast%E8%B5%84%E6%BA%90)
- [02-SAST工具](https://github.com/ASTTeam/SAST#02-sast%E5%B7%A5%E5%85%B7)
- [03-SAST原理](https://github.com/ASTTeam/SAST#03-sast%E5%8E%9F%E7%90%86)
- [04-SAST开发](https://github.com/ASTTeam/SAST#04-sast%E5%BC%80%E5%8F%91)
- [05-SAST未来](https://github.com/ASTTeam/SAST#05-sast%E6%9C%AA%E6%9D%A5)
- [06-SAST参考](https://github.com/ASTTeam/SAST#06-sast%E5%8F%82%E8%80%83)

## 01-SAST资源

一、书籍资源
- [ ]  [《Java代码审计-入门篇》](https://item.jd.com/10033832360716.html)@陈俊杰等
- [ ]  [《Java代码审计实战》](https://item.jd.com/13466996.html)@高昌盛等
- [ ]  [《Java安全编码标准》](https://book.douban.com/subject/24846041)@计文柯译
- [ ]  [《Java安全性编程指南》](https://github.com/HackJava/HackJava/blob/main)@庞南
- [ ]  [《Java安全》](https://github.com/HackJava/HackJava/blob/main)@奥克斯
- [ ]  [《Java编码指南》](https://www.amazon.co.uk/编写安全可靠程序的75条建议（英文版）-德鲁·莫欣达（Dhruv-C-西科德（Robert-F-萨瑟兰（Dean-弗雷德·朗（Fred/dp/B017WGUFKO)@刘先宁
- [ ]  [《Java-Web-Security》](https://play.google.com/store/books/details/Java_Web_Security_Sichere_Webanwendungen_mit_Java_?id=ZxZ4DwAAQBAJ&hl=en_US&gl=US)@Dominik Schadow
- [ ]  [《代码审计-企业级Web代码安全架构》](https://item.jd.com/10082081248.html)@尹毅
- [ ]  [《58集团白盒代码审计系统建设实践》](https://www.freebuf.com/articles/es/269266.html)@58安全

二、学术论文

三、视频资源

四、优秀资源
- [ ] https://en.wikipedia.org/wiki/Static_program_analysis
- [ ] https://en.wikipedia.org/wiki/List_of_tools_for_static_code_analysis

五、英文资源
- [ ] [《Lessons from Building Static Analysis Tools at Google》](https://cseweb.ucsd.edu/~dstefan/cse227-spring20/papers/sadowski:lessons.pdf)

六、其他资源
- 先知
- [ ] https://xz.aliyun.com/t/10216
- [ ] https://xz.aliyun.com/t/9335
- [ ] https://xz.aliyun.com/t/9429
- [ ] https://xz.aliyun.com/t/10756
- [ ] https://xz.aliyun.com/t/9531
- Github
- [ ] https://github.com/trailofbits/pip-audit
- [ ] https://github.com/rishisoni90/SECURE-PROGRAMMING-UTA
- [ ] https://github.com/RangerNJU/Static-Program-Analysis-Book
- [ ] https://github.com/lcatro/Source-and-Fuzzing
- [ ] https://github.com/pen4uin/static-analysis
- [ ] https://github.com/pen4uin/dotnet-security
- [ ] https://github.com/pen4uin/python-security
- [ ] https://github.com/pen4uin/golang-security
- [ ] https://github.com/modernizing/modernization
- [ ] https://github.com/jiangsir404/Audit-Learning
- [ ] https://github.com/twosmi1e/Static-Analysis-and-Automated-Code-Audit
- [ ] https://github.com/SummerSec/Static-Analysis
- Freebuf
- [ ] https://www.freebuf.com/sectool/240588.html
- 其他
- [ ] https://paper.seebug.org/1339
- [ ] https://evilpan.com/2022/01/22/code-audit
- [ ] https://www.softwaretestinghelp.com/tools/top-40-static-code-analysis-tools
- [ ] https://en.wikipedia.org/wiki/List_of_tools_for_static_code_analysis
- [ ] https://owasp.org/www-community/Source_Code_Analysis_Tools
- [ ] https://dzone.com/articles/top-7-static-code-analysis-tools
- [ ] https://www.incredibuild.cn/blog/top-9-c-static-code-analysis-tools

## 02-SAST工具

- https://github.com/analysis-tools-dev/static-analysis

一、优秀工具
- [ ]  https://github.com/ASTTeam/CodeQL | 基于语义的代码扫描工具 | 140
- [ ]  https://github.com/ASTTeam/Semgrep
- [ ]  https://github.com/returntocorp/semgrep
- [ ]  https://github.com/facebook/infer
- [ ]  https://github.com/joernio/joern
- [ ]  https://github.com/accurics/terrascan
- [ ]  https://github.com/SonarSource/sonarqube
- [ ]  https://github.com/MobSF/mobsfscan
- [ ]  https://github.com/Tencent/CodeAnalysis
- [ ]  https://github.com/securego/gosec
- [ ]  https://github.com/CoolerVoid/codecat

二、开源工具
- https://github.com/topics/SAST
- https://github.com/search?q=SAST
- [x]  https://github.com/FeeiCN/Cobra | 源代码安全审计 | 2.8k
- [x]  https://github.com/LoRexxar/Kunlun-M | 开源的静态白盒扫描工具 | 1.4k
- [x]  https://github.com/zsdlove/Hades | Java静态代码脆弱性检测系统 | 400
- [x]  https://github.com/ZupIT/horusec | 一条命令识别项目中的漏洞 | 661
- [x]  https://github.com/insidersec/insider | 专注于覆盖OWASP漏洞扫描 | 341
- [ ] https://github.com/ajinabraham/njsscan | Node.js代码扫描工具 | 232
- [ ] https://github.com/XianYanTechnology/RocB | Java代码审计IDEA插件SAST | 118
- [ ] https://github.com/SourceCode-AI/aura
- [ ] https://github.com/wahyuhadi/rinjani
- [ ] https://github.com/checkmarx-ts/CxAnalytix
- [ ] https://github.com/secdec/astam-correlator
- [ ] https://github.com/MagpieBridge/CryptoAnalysis-Android
- [ ] https://github.com/synopsys-sig/intelligent-security-scan
- [ ] https://github.com/MetLife/VeracodeCommunitySAST
- [ ] https://github.com/clj-holmes/clj-holmes
- [ ] https://github.com/b0n1t0/gSAST
- [ ] https://github.com/portilha/Checkmarx.API
- [ ] https://github.com/AppThreat/sast-scan-action
- [ ] https://github.com/ShiftLeftSecurity/sast-scan
- [ ] https://github.com/AppThreat/sast-scan
- [ ] https://github.com/mpast/mobileAudit
- [ ] https://github.com/ajinabraham/nodejsscan
- [ ] https://github.com/r0hi7/DockerENT
- [ ] https://github.com/ajinabraham/libsast
- [ ] https://github.com/clj-holmes/clj-holmes
- [ ] https://github.com/CloudDefenseAI/cd
- [ ] https://github.com/oversecured/oversecured-bitrise-step
- [ ] https://github.com/ivan-sincek/go-actions
- [ ] https://github.com/github/codeql-cli-binaries
- [ ] https://github.com/facebookarchive/pfff
- [ ] https://github.com/Osthanes/appscan_static_analyzer
- [ ] https://github.com/clj-holmes/clj-holmes
- [ ] https://github.com/dvelopp/SpringAngularApp
- [ ] https://github.com/jonrau1/CodeArtifactVulnScanner
- [ ] https://github.com/azharanees/OWASP-iGNITA
- [ ] https://github.com/joyliu-q/SASTAll
- [ ] https://github.com/IvanKuchin/SAST
- [ ] https://github.com/Hack23/talks
- [ ] https://github.com/rajasoun/cookiecutter-shift-left-security
- [ ] https://github.com/vwt-digital/cloudbuilder-sast
- [ ] https://github.com/adavarski/docker-bandit
- [ ] https://github.com/aramrami/iGNITA
- [ ] https://github.com/Scanner-One/Scanner-One
- [ ] https://github.com/SummerSec/SPATool
- [ ] https://github.com/checkstyle/checkstyle
- [ ] https://github.com/marcinguy/scanmycode-ce
- [ ] https://github.com/AppThreat/dep-scan
- [ ] https://github.com/murphysecurity/murphysec
- [ ] https://github.com/droidsec-cn/Alien-Intelligent-Security-Assessment-for-Android
- [ ] https://github.com/j5s/XVulnFinder
- [ ] https://github.com/magnologan/gha-devsecops
- [ ] https://github.com/we45/ThreatPlaybook
- [ ] https://github.com/SAST-skill-docers/sast-skill-docs
- [ ] https://github.com/NodeSecure/js-x-ray
- [ ] https://github.com/cxai/Checkmarx-PowerTools

三、商业产品
- [ ] [腾讯Xcheck](https://cloud.tencent.com/product/asd)
- [ ] [奇安信代码卫士]()
- [ ] [Fortify](https://www.joinfortify.com)
- [ ] https://www.woocoom.com
- [ ] https://www.microfocus.com
- [ ] [https://checkstyle.sourceforge.io](https://checkstyle.sourceforge.io/)

## 03-SAST原理

本章节介绍SAST的实现原理设计思想等内容。

一、基于正则

二、基于AST

三、基于IR/CFG

四、基于QL

五、基于......？

## 04-SAST开发

- 如何开发一款优秀的SAST工具产品？

## 05-SAST未来

- 一款优秀的SAST产品应该具备什么样的特性？

## 06-SAST参考

- https://github.com/HackJava/HackJava
- https://github.com/Hackaspx/Hackaspx
- https://github.com/FuckPHP/FuckPHP
- https://github.com/HackGolang/HackGolang

## Stargazers

[![Stargazers @ASTTeam/SAST](https://reporoster.com/stars/ASTTeam/SAST)](https://github.com/ASTTeam/SAST/stargazers)

## Forkers

[![Forkers @ASTTeam/SAST](https://reporoster.com/forks/ASTTeam/SAST)](https://github.com/ASTTeam/SAST/network/members)

[![Stargazers over time](https://starchart.cc//ASTTeam/SAST.svg)](https://starchart.cc/ASTTeam/SAST)