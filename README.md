# SAST静态应用安全测试
SAST在安全测试领域及其重要。不仅是解决漏洞的一个有效方法利器，更是基础安全之上解决漏洞的有效措施。SAST有时弊病百出，比如效果严重依赖规则库、误报漏报率太高、特定漏洞无法检测等问题。但SAST的发展确实推动了安全漏洞的发展，弥补了DAST的某些不足，甚至促进了IAST的发展。作者：[0e0w](https://github.com/0e0w)

本项目创建于2022年1月22日，最近的一次更新时间为2022年1月25日。

- [01-SAST基础资源](https://github.com/0e0w/SAST#01-sast%E5%9F%BA%E7%A1%80%E8%B5%84%E6%BA%90)
- [02-SAST工具产品](https://github.com/0e0w/SAST#02-sast%E5%B7%A5%E5%85%B7%E4%BA%A7%E5%93%81)
- [03-SAST方法思想](https://github.com/0e0w/SAST#03-sast%E6%96%B9%E6%B3%95%E6%80%9D%E6%83%B3)
- [04-SAST未来发展](https://github.com/0e0w/SAST#04-sast%E6%9C%AA%E6%9D%A5%E5%8F%91%E5%B1%95)
- [05-SAST参考资源](https://github.com/0e0w/SAST#05-sast%E5%8F%82%E8%80%83%E8%B5%84%E6%BA%90)

## 01-SAST基础资源

一、书籍资源

二、学术论文

三、其他资源

- https://xz.aliyun.com/t/10216
- https://github.com/trailofbits/pip-audit
- https://www.freebuf.com/sectool/240588.html
- https://paper.seebug.org/1339
- https://xz.aliyun.com/t/9531
- https://github.com/rishisoni90/SECURE-PROGRAMMING-UTA
- https://github.com/RangerNJU/Static-Program-Analysis-Book
- https://evilpan.com/2022/01/22/code-audit
- https://github.com/lcatro/Source-and-Fuzzing

## 02-SAST工具产品

- https://github.com/topics/SAST
- https://github.com/search?q=SAST

一、开源工具
- [ ]  https://github.com/analysis-tools-dev/static-analysis
- [ ]  https://github.com/ZupIT/horusec
- [ ]  https://github.com/ZupIT/horusec-engine
- [ ]  https://github.com/insidersec/insider
- [ ]  https://github.com/FeeiCN/Cobra
- [ ]  https://github.com/LoRexxar/Kunlun-M
- [ ]  https://github.com/returntocorp/semgrep
- [ ]  [https://checkstyle.sourceforge.io](https://checkstyle.sourceforge.io/)
- [ ]  https://github.com/j5s/XVulnFinder
- [ ] https://www.microfocus.com
- [ ] https://github.com/magnologan/gha-devsecops
- [ ] https://github.com/we45/ThreatPlaybook
- [ ] https://github.com/ajinabraham/njsscan
- [ ] https://github.com/XianYanTechnology/RocB
- [ ] https://github.com/SAST-skill-docers/sast-skill-docs
- [ ] https://github.com/NodeSecure/js-x-ray
- [ ] https://github.com/cxai/Checkmarx-PowerTools
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
- [ ] https://github.com/accurics/terrascan
- [ ] https://github.com/ajinabraham/nodejsscan
- [ ] https://github.com/r0hi7/DockerENT
- [ ] https://github.com/ajinabraham/libsast
- [ ] https://github.com/clj-holmes/clj-holmes
- [ ] https://github.com/CloudDefenseAI/cd
- [ ] https://github.com/oversecured/oversecured-bitrise-step
- [ ] https://github.com/ivan-sincek/go-actions
- [ ] https://github.com/wahyuhadi/rinjani
- [ ] https://github.com/zsdlove/Hades | 静态代码脆弱性检测系统 | 386
- [ ] https://github.com/SonarSource/sonarqube
- [ ] https://github.com/github/codeql-cli-binaries
- [ ] https://github.com/facebookarchive/pfff
- [ ] https://github.com/Osthanes/appscan_static_analyzer
- [ ] https://github.com/clj-holmes/clj-holmes
- [ ] https://github.com/dvelopp/SpringAngularApp
- [ ] https://github.com/IBM/sonarqube
- [ ] https://github.com/IBM/workshop-template
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

二、商业产品
- [ ] [Tencent Xcheck](https://cloud.tencent.com/product/asd)
- [ ] [奇安信代码卫士]()

三、Android

- [ ] https://github.com/MobSF/Mobile-Security-Framework-MobSF
- [ ] https://github.com/droidsec-cn/Alien-Intelligent-Security-Assessment-for-Android

## 03-SAST方法思想

一、基于正则

二、基于AST

三、基于IR/CFG

四、基于QL

五、基于......？

## 04-SAST未来发展

- 一款优秀的SAST产品应该具备什么样的特性？

## 05-SAST参考资源