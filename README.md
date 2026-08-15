# Awesome-Redteam with stars

<p align="left">
  <a href="https://github.com/Threekiii/Awesome-Redteam">
    <img src="https://badgen.net/github/stars/Threekiii/Awesome-Redteam?color=yellow&icon=github" alt="stars">
  </a>
  <a href="https://github.com/Threekiii/Awesome-Redteam">
    <img src="https://badgen.net/github/forks/Threekiii/Awesome-Redteam?color=blue&icon=github" alt="forks">
  </a>
  <a href="https://github.com/Threekiii/Awesome-Redteam">
    <img src="https://badgen.net/github/last-commit/Threekiii/Awesome-Redteam?color=green" alt="last-commit">
  </a>
</p>

**❗【免责声明】本项目所涉及的技术、思路和工具仅供学习，任何人不得将其用于非法用途和盈利，不得将其用于非授权渗透测试，否则后果自行承担，与本项目无关。 使用本项目前请先阅读 [法律法规](https://github.com/Threekiii/Awesome-Laws) ⭐ 254 | 🐛 0 | 📅 2026-01-05。**

*Disclaimer: The technologies, concepts, and tools provided in this Git repository are intended for educational and research purposes only. Any use for illegal activities, unauthorized penetration testing, or commercial purposes is strictly prohibited. Please read the [Awesome-Laws](https://github.com/Threekiii/Awesome-Laws) ⭐ 254 | 🐛 0 | 📅 2026-01-05 before using this repository.*

📖 一个攻防知识库。*A knowledge base for red teaming and offensive security.*

👍 means recommend 推荐使用

## *Roadmap*

![](images/README/Awesome-Redteam-20260603.png)

## 目录 *Contents*

* [项目导航 *Project Navigation*](#%E9%A1%B9%E7%9B%AE%E5%AF%BC%E8%88%AA-project-navigation)
  * [速查文档 *CheatSheets*](#%E9%80%9F%E6%9F%A5%E6%96%87%E6%A1%A3-cheatsheets)
  * [一些代码 *Scripts*](#%E4%B8%80%E4%BA%9B%E4%BB%A3%E7%A0%81-scripts)
  * [攻防知识 *Tips*](#%E6%94%BB%E9%98%B2%E7%9F%A5%E8%AF%86-tips)
* [开源导航 *Open-Source Navigation*](#%E5%BC%80%E6%BA%90%E5%AF%BC%E8%88%AA-open-source-navigation)
  * [编解码/加解密 *Cryptography*](#%E7%BC%96%E8%A7%A3%E7%A0%81%E5%8A%A0%E8%A7%A3%E5%AF%86-cryptography)
    * [在线工具 *Online Tools*](#%E5%9C%A8%E7%BA%BF%E5%B7%A5%E5%85%B7-online-tools)
    * [离线工具 *Offline Tools*](#%E7%A6%BB%E7%BA%BF%E5%B7%A5%E5%85%B7-offline-tools)
    * [编码/解码 *Encode/Decode*](#%E7%BC%96%E7%A0%81%E8%A7%A3%E7%A0%81-encodedecode)
    * [正则表达式 *Regular Expressions*](#%E6%AD%A3%E5%88%99%E8%A1%A8%E8%BE%BE%E5%BC%8F-regular-expressions)
    * [哈希算法 *Hash Algorithms*](#%E5%93%88%E5%B8%8C%E7%AE%97%E6%B3%95-hash-algorithms)
    * [公钥密码算法 *RSA*](#%E5%85%AC%E9%92%A5%E5%AF%86%E7%A0%81%E7%AE%97%E6%B3%95-rsa)
    * [国密算法 *SM Algorithms*](#%E5%9B%BD%E5%AF%86%E7%AE%97%E6%B3%95-sm-algorithms)
  * [网络空间测绘 *Cyberspace Search Engine*](#%E7%BD%91%E7%BB%9C%E7%A9%BA%E9%97%B4%E6%B5%8B%E7%BB%98-cyberspace-search-engine)
    * [综合工具 *Nice Tools*](#%E7%BB%BC%E5%90%88%E5%B7%A5%E5%85%B7-nice-tools)
    * [网页/端口 *Web/Ports*](#%E7%BD%91%E9%A1%B5%E7%AB%AF%E5%8F%A3-webports)
    * [谷歌搜索 *Google Hacking*](#%E8%B0%B7%E6%AD%8C%E6%90%9C%E7%B4%A2-google-hacking)
    * [Github 搜索 *Github Dork*](#github-%E6%90%9C%E7%B4%A2-github-dork)
  * [开源情报 *Open-Source Intelligence*](#%E5%BC%80%E6%BA%90%E6%83%85%E6%8A%A5-open-source-intelligence)
    * [综合工具 *Nice Tools*](#%E7%BB%BC%E5%90%88%E5%B7%A5%E5%85%B7-nice-tools)
    * [威胁情报 *Threat Intelligence*](#%E5%A8%81%E8%83%81%E6%83%85%E6%8A%A5-threat-intelligence)
    * [漏洞披露 *Disclosed Vulnerabilities*](#%E6%BC%8F%E6%B4%9E%E6%8A%AB%E9%9C%B2-disclosed%C2%A0vulnerabilities)
    * [接口检索 *API Search*](#%E6%8E%A5%E5%8F%A3%E6%A3%80%E7%B4%A2-api-search)
    * [源代码检索 *Source Code Search*](#%E6%BA%90%E4%BB%A3%E7%A0%81%E6%A3%80%E7%B4%A2-source-code-search)
  * [开源资源 *Open-Source Resources*](#%E5%BC%80%E6%BA%90%E8%B5%84%E6%BA%90-open-source-resources)
    * [社区/知识库 *Communities/Knowledge Base*](#%E7%A4%BE%E5%8C%BA%E7%9F%A5%E8%AF%86%E5%BA%93-communitiesknowledge-base)
    * [思维导图/备忘录 *Mindmap/Cheat Sheets*](#%E6%80%9D%E7%BB%B4%E5%AF%BC%E5%9B%BE%E5%A4%87%E5%BF%98%E5%BD%95-mindmapcheat-sheets)
    * [进攻性安全 *Red Teaming and Offensive Security*](#%E8%BF%9B%E6%94%BB%E6%80%A7%E5%AE%89%E5%85%A8-red-teaming-and-offensive-security)
    * [防御性安全 *Blue Teaming and Defensive Security*](#%E9%98%B2%E5%BE%A1%E6%80%A7%E5%AE%89%E5%85%A8-blue-teaming-and-defensive-security)
    * [操作安全 *Operation Security*](#%E6%93%8D%E4%BD%9C%E5%AE%89%E5%85%A8-operation-security)
    * [实战平台 *Learning and Practice Platforms*](#%E5%AE%9E%E6%88%98%E5%B9%B3%E5%8F%B0-learning-and-practice-platforms)
* [信息收集 *Reconnaissance*](#%E4%BF%A1%E6%81%AF%E6%94%B6%E9%9B%86-reconnaissance)
  * [综合工具 *Nice Tools*](#%E7%BB%BC%E5%90%88%E5%B7%A5%E5%85%B7-nice-tools)
  * [IP/域名/子域名 *IP/Domain/Subdomain*](#ip%E5%9F%9F%E5%90%8D%E5%AD%90%E5%9F%9F%E5%90%8D-ipdomainsubdomain)
  * [指纹 *Fingerprint*](#%E6%8C%87%E7%BA%B9-fingerprint)
    * [指纹库 *Fingerprint Collection*](#%E6%8C%87%E7%BA%B9%E5%BA%93-fingerprint-collection)
    * [指纹识别 *Fingerprint Reconnaissance*](#%E6%8C%87%E7%BA%B9%E8%AF%86%E5%88%AB-fingerprint-reconnaissance)
    * [WAF 识别 *Waf Checks*](#waf-%E8%AF%86%E5%88%AB-waf-checks)
  * [扫描/爆破 *Brute Force*](#%E6%89%AB%E6%8F%8F%E7%88%86%E7%A0%B4-brute-force)
    * [扫描/爆破工具 *Brute Force Tools*](#%E6%89%AB%E6%8F%8F%E7%88%86%E7%A0%B4%E5%B7%A5%E5%85%B7-brute-force-tools)
    * [扫描/爆破字典 *Brute Force Dictionaries*](#%E6%89%AB%E6%8F%8F%E7%88%86%E7%A0%B4%E5%AD%97%E5%85%B8-brute-force-dictionaries)
    * [字典生成 *Generate a Custom Dictionary*](#%E5%AD%97%E5%85%B8%E7%94%9F%E6%88%90-generate-a-custom-dictionary)
    * [默认口令查询 *Default Credentials*](#%E9%BB%98%E8%AE%A4%E5%8F%A3%E4%BB%A4%E6%9F%A5%E8%AF%A2-default-credentials)
  * [社会工程学 *Social Engineering*](#%E7%A4%BE%E4%BC%9A%E5%B7%A5%E7%A8%8B%E5%AD%A6-social-engineering)
    * [凭据泄露 *Leaked Credentials*](#%E5%87%AD%E6%8D%AE%E6%B3%84%E9%9C%B2-leaked-credentials)
    * [邮箱 *Email*](#%E9%82%AE%E7%AE%B1-email)
    * [短信 *SMS Online*](#%E7%9F%AD%E4%BF%A1-sms-online)
    * [钓鱼 *Phishing*](#%E9%92%93%E9%B1%BC-phishing)
  * [移动端 *Mobile*](#%E7%A7%BB%E5%8A%A8%E7%AB%AF-mobile)
* [漏洞研究 *Vulnerability Research*](#%E6%BC%8F%E6%B4%9E%E7%A0%94%E7%A9%B6-vulnerability-research)
  * [漏洞环境 *Vulnerable Environments*](#%E6%BC%8F%E6%B4%9E%E7%8E%AF%E5%A2%83-vulnerable-environments)
    * [基础漏洞 *Basic Vulnerabilities*](#%E5%9F%BA%E7%A1%80%E6%BC%8F%E6%B4%9E-basic-vulnerabilities)
    * [综合漏洞 *Comprehensive Vulnerabilities*](#%E7%BB%BC%E5%90%88%E6%BC%8F%E6%B4%9E-comprehensive-vulnerabilities)
    * [工控环境 *Vulnerable IoT Environment*](#%E5%B7%A5%E6%8E%A7%E7%8E%AF%E5%A2%83-vulnerable-iot-environment)
    * [域环境 *Vulnerable Active Directory Environment*](#%E5%9F%9F%E7%8E%AF%E5%A2%83-vulnerable-active-directory-environment)
    * [云环境 *Vulnerable Cloud Environments*](#%E4%BA%91%E7%8E%AF%E5%A2%83-vulnerable-cloud-environments)
  * [PoC *Proof of Concept*](#poc-proof-of-concept)
    * [PoC/ExP](#pocexp)
    * [PoC 模板 *PoC Templates*](#poc-%E6%A8%A1%E6%9D%BF-poc-templates)
* [漏洞利用 *Vulnerability Exploits*](#%E6%BC%8F%E6%B4%9E%E5%88%A9%E7%94%A8-vulnerability-exploits)
  * [综合工具 *Nice Tools*](#%E7%BB%BC%E5%90%88%E5%B7%A5%E5%85%B7-nice-tools)
  * [代码审计 *Code Audit*](#%E4%BB%A3%E7%A0%81%E5%AE%A1%E8%AE%A1-code-audit)
  * [序列化 *Serialization*](#%E5%BA%8F%E5%88%97%E5%8C%96-serialization)
    * [Java](#java)
  * [反序列化 *Deserialization*](#%E5%8F%8D%E5%BA%8F%E5%88%97%E5%8C%96-deserialization)
    * [Java](#java)
    * [PHP](#php)
  * [数据库 *Database*](#%E6%95%B0%E6%8D%AE%E5%BA%93-database)
    * [Redis](#redis)
    * [MySQL](#mysql)
    * [Oracle](#oracle)
    * [MSSQL](#mssql)
  * [信息泄露 *Information Disclosure*](#%E4%BF%A1%E6%81%AF%E6%B3%84%E9%9C%B2-information-disclosure)
  * [CMS/OA 漏洞 *CMS/OA*](#cmsoa-%E6%BC%8F%E6%B4%9E-cmsoa)
  * [中间件/应用层 *Middleware/Application*](#%E4%B8%AD%E9%97%B4%E4%BB%B6%E5%BA%94%E7%94%A8%E5%B1%82-middlewareapplication)
* [渗透测试 *Penetration Testing*](#%E6%B8%97%E9%80%8F%E6%B5%8B%E8%AF%95-penetration-testing)
  * [综合工具 *Nice Tools*](#%E7%BB%BC%E5%90%88%E5%B7%A5%E5%85%B7-nice-tools)
  * [渗透插件 *Extensions*](#%E6%B8%97%E9%80%8F%E6%8F%92%E4%BB%B6-extensions)
    * [Chrome](#chrome)
    * [Burp Suite](#burp-suite)
    * [Yakit](#yakit)
  * [辅助工具 *Auxiliary Tools*](#%E8%BE%85%E5%8A%A9%E5%B7%A5%E5%85%B7-auxiliary-tools)
    * [工具集 *Open-Source Toolkit*](#%E5%B7%A5%E5%85%B7%E9%9B%86-open-source-toolkit)
    * [带外通道 *DNSLog*](#%E5%B8%A6%E5%A4%96%E9%80%9A%E9%81%93-dnslog)
    * [终端优化 *Command Line*](#%E7%BB%88%E7%AB%AF%E4%BC%98%E5%8C%96-command-line)
    * [代码美化 *Beautifier*](#%E4%BB%A3%E7%A0%81%E7%BE%8E%E5%8C%96-beautifier)
    * [生成器 *Generator*](#%E7%94%9F%E6%88%90%E5%99%A8-generator)
  * [SQL 注入 *SQL Injection*](#sql-%E6%B3%A8%E5%85%A5-sql-injection)
  * [访问控制 *Access Control*](#%E8%AE%BF%E9%97%AE%E6%8E%A7%E5%88%B6-access-control)
    * [403 绕过 *Bypass 40X errors*](#403-%E7%BB%95%E8%BF%87-bypass-40x-errors)
  * [跨站脚本 *XSS*](#%E8%B7%A8%E7%AB%99%E8%84%9A%E6%9C%AC-xss)
  * [文件包含 *File Inclusion*](#%E6%96%87%E4%BB%B6%E5%8C%85%E5%90%AB-file-inclusion)
  * [服务端请求伪造 *SSRF*](#%E6%9C%8D%E5%8A%A1%E7%AB%AF%E8%AF%B7%E6%B1%82%E4%BC%AA%E9%80%A0-ssrf)
  * [移动端安全 *Mobile Security*](#%E7%A7%BB%E5%8A%A8%E7%AB%AF%E5%AE%89%E5%85%A8-mobile-security)
    * [小程序 *Mini Program*](#%E5%B0%8F%E7%A8%8B%E5%BA%8F-mini-program)
    * [应用程序 *APK*](#%E5%BA%94%E7%94%A8%E7%A8%8B%E5%BA%8F-apk)
    * [SessionKey 解密 *SessionKey*](#sessionkey-%E8%A7%A3%E5%AF%86-sessionkey)
  * [载荷与绕过 *Payload and Bypass*](#%E8%BD%BD%E8%8D%B7%E4%B8%8E%E7%BB%95%E8%BF%87-payload-and-bypass)
* [内网渗透 *Red Teaming and Offensive Security*](#%E5%86%85%E7%BD%91%E6%B8%97%E9%80%8F-red-teaming-and-offensive-security)
  * [基础设施 *Infrastructure*](#%E5%9F%BA%E7%A1%80%E8%AE%BE%E6%96%BD-infrastructure)
  * [信息收集 *Reconnaissance*](#%E4%BF%A1%E6%81%AF%E6%94%B6%E9%9B%86-reconnaissance)
  * [凭证获取 *Credential Access*](#%E5%87%AD%E8%AF%81%E8%8E%B7%E5%8F%96-credential-access)
    * [凭证转储 *Credential Dumping*](#%E5%87%AD%E8%AF%81%E8%BD%AC%E5%82%A8-credential-dumping)
    * [本地枚举 *Local Enumeration*](#%E6%9C%AC%E5%9C%B0%E6%9E%9A%E4%B8%BE-local-enumeration)
    * [哈希破解 *NTLM Cracking*](#%E5%93%88%E5%B8%8C%E7%A0%B4%E8%A7%A3-ntlm-cracking)
  * [后渗透 *Post Exploitation*](#%E5%90%8E%E6%B8%97%E9%80%8F-post-exploitation)
    * [综合工具 *Nice Tools*](#%E7%BB%BC%E5%90%88%E5%B7%A5%E5%85%B7-nice-tools)
    * [二进制库 *Binaries and Libraries*](#%E4%BA%8C%E8%BF%9B%E5%88%B6%E5%BA%93-binaries-and-libraries)
  * [权限维持 *Persistence*](#%E6%9D%83%E9%99%90%E7%BB%B4%E6%8C%81-persistence)
    * [内存马 *MemShell*](#%E5%86%85%E5%AD%98%E9%A9%AC-memshell)
    * [Webshell 管理 *Webshell Management*](#webshell-%E7%AE%A1%E7%90%86-webshell-management)
    * [Webshell 免杀 *Webshell Bypass*](#webshell-%E5%85%8D%E6%9D%80-webshell-bypass)
    * [反弹 Shell 管理 *Reverse Shell Management*](#%E5%8F%8D%E5%BC%B9-shell-%E7%AE%A1%E7%90%86-reverse-shell-management)
  * [权限提升 *Privilege Escalation*](#%E6%9D%83%E9%99%90%E6%8F%90%E5%8D%87-privilege-escalation)
    * [Linux 本地枚举 *Linux Local Enumeration*](#linux-%E6%9C%AC%E5%9C%B0%E6%9E%9A%E4%B8%BE-linux-local-enumeration)
    * [Windows 本地枚举 *Windows Local Enumeration*](#windows-%E6%9C%AC%E5%9C%B0%E6%9E%9A%E4%B8%BE-windows-local-enumeration)
    * [Windows 提权 *Windows Exploits*](#windows-%E6%8F%90%E6%9D%83-windows-exploits)
    * [Linux 提权 *Linux Exploits*](#linux-%E6%8F%90%E6%9D%83-linux-exploits)
    * [数据库提权 *Database Exploits*](#%E6%95%B0%E6%8D%AE%E5%BA%93%E6%8F%90%E6%9D%83-database-exploits)
  * [防御规避 *Defense Evasion*](#%E9%98%B2%E5%BE%A1%E8%A7%84%E9%81%BF-defense-evasion)
    * [Linux 防御规避 *Linux Defense Evasion*](#linux-%E9%98%B2%E5%BE%A1%E8%A7%84%E9%81%BF-linux-defense-evasion)
    * [Windows 防御规避 *Windows Defense Evasion*](#windows-%E9%98%B2%E5%BE%A1%E8%A7%84%E9%81%BF-windows-defense-evasion)
  * [内网穿透 *Proxy*](#%E5%86%85%E7%BD%91%E7%A9%BF%E9%80%8F-proxy)
    * [代理客户端 *Proxy Client*](#%E4%BB%A3%E7%90%86%E5%AE%A2%E6%88%B7%E7%AB%AF-proxy-client)
    * [代理工具 *Proxy Tools*](#%E4%BB%A3%E7%90%86%E5%B7%A5%E5%85%B7-proxy-tools)
    * [DNS 隧道 *DNS Tunnel*](#dns-%E9%9A%A7%E9%81%93-dns-tunnel)
    * [ICMP 隧道 *ICMP Tunnel*](#icmp-%E9%9A%A7%E9%81%93-icmp-tunnel)
    * [端口转发 *Port Forwarding*](#%E7%AB%AF%E5%8F%A3%E8%BD%AC%E5%8F%91-port-forwarding)
  * [操作安全 *Operation Security*](#%E6%93%8D%E4%BD%9C%E5%AE%89%E5%85%A8-operation-security)
* [域渗透 *Active Directory Penetration*](#%E5%9F%9F%E6%B8%97%E9%80%8F-active-directory-penetration)
  * [域内信息收集 *Collection and Discovery*](#%E5%9F%9F%E5%86%85%E4%BF%A1%E6%81%AF%E6%94%B6%E9%9B%86-collection-and-discovery)
  * [域内权限提升 *Privilege Escalation*](#%E5%9F%9F%E5%86%85%E6%9D%83%E9%99%90%E6%8F%90%E5%8D%87-privilege-escalation)
  * [域内漏洞利用 *Known Exploited Vulnerabilities*](#%E5%9F%9F%E5%86%85%E6%BC%8F%E6%B4%9E%E5%88%A9%E7%94%A8-known-exploited-vulnerabilities)
    * [MS14-068](#ms14-068)
    * [noPac](#nopac)
    * [Zerologon](#zerologon)
    * [ProxyLogon/ProxyShell](#proxylogonproxyshell)
    * [ProxyNotShell](#proxynotshell)
    * [Printnightmare](#printnightmare)
  * [域内渗透方式 *Methodology*](#%E5%9F%9F%E5%86%85%E6%B8%97%E9%80%8F%E6%96%B9%E5%BC%8F-methodology)
    * [Coerce and Relay](#coerce-and-relay)
    * [Delegation](#delegation)
    * [ADCS](#adcs)
    * [ACLs and ACEs](#acls-and-aces)
* [防御性安全 *Blue Teaming and Defensive Security*](#%E9%98%B2%E5%BE%A1%E6%80%A7%E5%AE%89%E5%85%A8-blue-teaming-and-defensive-security)
  * [内存马查杀 *Memshell Detection*](#%E5%86%85%E5%AD%98%E9%A9%AC%E6%9F%A5%E6%9D%80-memshell-detection)
  * [Webshell 查杀 *Webshell Detection*](#webshell-%E6%9F%A5%E6%9D%80-webshell-detection)
  * [攻击研判 *Blue Teaming*](#%E6%94%BB%E5%87%BB%E7%A0%94%E5%88%A4-blue-teaming)
  * [基线加固 *Enforcement*](#%E5%9F%BA%E7%BA%BF%E5%8A%A0%E5%9B%BA-enforcement)
  * [应急响应 *Incident Response*](#%E5%BA%94%E6%80%A5%E5%93%8D%E5%BA%94-incident-response)
  * [勒索病毒 *Ransomware*](#%E5%8B%92%E7%B4%A2%E7%97%85%E6%AF%92-ransomware)
    * [搜索引擎 *Search Engine*](#%E6%90%9C%E7%B4%A2%E5%BC%95%E6%93%8E-search-engine)
    * [解密工具 *Decryption Tools*](#%E8%A7%A3%E5%AF%86%E5%B7%A5%E5%85%B7-decryption-tools)
  * [开源蜜罐 *Open-Source Honeypot*](#%E5%BC%80%E6%BA%90%E8%9C%9C%E7%BD%90-open-source-honeypot)
  * [逆向工程 *Reverse Engineering*](#%E9%80%86%E5%90%91%E5%B7%A5%E7%A8%8B-reverse-engineering)
    * [综合工具 *Nice Tools*](#%E7%BB%BC%E5%90%88%E5%B7%A5%E5%85%B7-nice-tools)
    * [静态分析 *Static Analysis*](#%E9%9D%99%E6%80%81%E5%88%86%E6%9E%90-static-analysis)
    * [动态调试 *Dynamic Analysis*](#%E5%8A%A8%E6%80%81%E8%B0%83%E8%AF%95-dynamic-analysis)
    * [Java](#java)
    * [Mobile](#mobile)
    * [Python](#python)
    * [Rust/Go/.NET](#rustgonet)
* [云安全 *Cloud Security*](#%E4%BA%91%E5%AE%89%E5%85%A8-cloud-security)
  * [开源资源 *Resources*](#%E5%BC%80%E6%BA%90%E8%B5%84%E6%BA%90-resources)
  * [云安全矩阵 *Cloud Threat Matrix*](#%E4%BA%91%E5%AE%89%E5%85%A8%E7%9F%A9%E9%98%B5-cloud-threat-matrix)
  * [云服务 *Cloud Services*](#%E4%BA%91%E6%9C%8D%E5%8A%A1-cloud-services)
    * [云管平台 *Management Tools*](#%E4%BA%91%E7%AE%A1%E5%B9%B3%E5%8F%B0-management-tools)
    * [AK/SK 利用 *AK/SK Exploit*](#aksk-%E5%88%A9%E7%94%A8-aksk-exploit)
  * [云原生 *Cloud Native*](#%E4%BA%91%E5%8E%9F%E7%94%9F-cloud-native)
    * [综合工具 *Nice Tools*](#%E7%BB%BC%E5%90%88%E5%B7%A5%E5%85%B7-nice-tools)
    * [容器 *Docker*](#%E5%AE%B9%E5%99%A8-docker)
    * [集群 *Kubernetes*](#%E9%9B%86%E7%BE%A4-kubernetes)
* [提高生产力的使用姿势](#%E6%8F%90%E9%AB%98%E7%94%9F%E4%BA%A7%E5%8A%9B%E7%9A%84%E4%BD%BF%E7%94%A8%E5%A7%BF%E5%8A%BF)
  * [如何快速使用 alias](#%E5%A6%82%E4%BD%95%E5%BF%AB%E9%80%9F%E4%BD%BF%E7%94%A8-alias)
  * [如何优化原生终端](#%E5%A6%82%E4%BD%95%E4%BC%98%E5%8C%96%E5%8E%9F%E7%94%9F%E7%BB%88%E7%AB%AF)
  * [如何解决终端中文乱码](#%E5%A6%82%E4%BD%95%E8%A7%A3%E5%86%B3%E7%BB%88%E7%AB%AF%E4%B8%AD%E6%96%87%E4%B9%B1%E7%A0%81)

## 项目导航 *Project Navigation*

### 速查文档 *CheatSheets*

戳这里 [Click Here](https://github.com/Threekiii/Awesome-Redteam/blob/master/cheatsheets/) ⭐ 4,302 | 🐛 2 | 🌐 Python | 📅 2026-06-23

```
DefaultCreds-Cheat-Sheet.csv
Huawei-iBMC-DefaultCreds.csv
Huawei-Product-Cheat-Sheet.csv
WeakPassword-Cheat-Sheet.csv
安全厂商及官网链接速查.txt
```

### 一些代码 *Scripts*

戳这里 [Click Here](https://github.com/Threekiii/Awesome-Redteam/blob/master/scripts/) ⭐ 4,302 | 🐛 2 | 🌐 Python | 📅 2026-06-23

```
ShellcodeWrapper: Shellcode加密
AntivirusScanner: 杀软进程检测脚本
runtime-exec-payloads.html: java.lang.Runtime.exec() Payloads生成 
Ascii2Char: ASCII码和字符互相转换脚本 修改webshell文件名密码 
Weakpass_Generator: 在线弱密码生成工具 汉化版
Godzilla_Decryptor: 哥斯拉流量解密
Behinder4_Key_Bruteforce: 冰蝎4密钥爆破
Flask_Session_Decryptor: Flask session注入解密
```

### 攻防知识 *Tips*

戳这里 [Click Here](https://github.com/Threekiii/Awesome-Redteam/blob/master/tips/) ⭐ 4,302 | 🐛 2 | 🌐 Python | 📅 2026-06-23

```
信息收集-敏感信息收集
内网渗透-免杀
内网渗透-隐藏
内网渗透-Pentesting AD Mindmap
安全架构-网络攻击与防御图谱
平台搭建-DNS Log
流量分析-CobaltStrike
流量分析-Webshell
社会工程学-钓鱼邮件主题汇总
逆向分析-微信小程序反编译
```

## 开源导航 *Open-Source Navigation*

### 编解码/加解密 *Cryptography*

#### 在线工具 *Online Tools*

* <http://www.ip33.com/>
* <http://www.metools.info/>
* <https://www.107000.com/>
* <http://www.hiencode.com/>
* <http://www.atoolbox.net/>
* <https://www.sojson.com/>
* <https://the-x.cn/>

#### 离线工具 *Offline Tools*

* <https://github.com/gchq/CyberChef> ⭐ 35,587 | 🐛 564 | 🌐 JavaScript | 📅 2026-08-14 👍
* <https://github.com/Ciphey/Ciphey> ⭐ 21,579 | 🐛 2 | 🌐 Rust | 📅 2026-08-10
* <https://github.com/guyoung/CaptfEncoder> ⭐ 1,291 | 🐛 63 | 🌐 JavaScript | 📅 2023-10-16
* <https://github.com/wangyiwy/oktools> ⭐ 368 | 🐛 5 | 🌐 JavaScript | 📅 2023-06-01
* <http://1o1o.xyz/bo_ctfcode.html>

#### 编码/解码 *Encode/Decode*

* <http://code.mcdvisa.com/> 标准中文电码
* <https://www.compart.com/en/unicode/> 万国码
* <http://web.chacuo.net/charsetuuencode> UU 编码
* <https://tool.chinaz.com/tools/escape.aspx> 转义/反转义
* <https://zh.rakko.tools/tools/21/> HTML 实体编码

#### 正则表达式 *Regular Expressions*

* <https://github.com/any86/any-rule> ⭐ 8,650 | 🐛 72 | 🌐 TypeScript | 📅 2024-07-21
* <https://github.com/VincentSit/ChinaMobilePhoneNumberRegex> ⭐ 4,768 | 🐛 4 | 📅 2022-05-17
* <https://regex101.com/>

#### 哈希算法 *Hash Algorithms*

* <https://www.cmd5.org/>
* <https://www.somd5.com/>
* <https://www.onlinehashcrack.com/>
* <https://crackstation.net/>
* <https://crack.sh/>
* <https://passwordrecovery.io/>
* <https://md5decrypt.net/en/Sha256/>
* <https://hashes.com/en/decrypt/hash>

#### 公钥密码算法 *RSA*

* <https://www.ssleye.com/ssltool/>
* <https://www.lddgo.net/en/encrypt/rsa> 支持 .pem 格式

#### 国密算法 *SM Algorithms*

* hutool-crypto: <https://github.com/dromara/hutool> ⭐ 30,277 | 🐛 2 | 🌐 Java | 📅 2026-08-13 hutool-crypto 模块，提供对称、非对称和摘要算法封装
* GmSSL: <https://github.com/guanzhi/GmSSL> ⭐ 6,136 | 🐛 400 | 🌐 C | 📅 2026-06-30 SM2/SM3/SM4/SM9/SSL
* gmssl-python: <https://github.com/gongxian-ding/gmssl-python> ⭐ 75 | 🐛 10 | 🌐 Python | 📅 2020-09-22 SM2/SM3/SM4/SM9
* SM4: <https://www.toolhelper.cn/SymmetricEncryption/SM4>

### 网络空间测绘 *Cyberspace Search Engine*

#### 综合工具 *Nice Tools*

* Fofa: <https://fofa.info/>
* Shodan: <https://www.shodan.io/>
* ZoomEye: <https://www.zoomeye.org/>
* Hunter: <https://hunter.qianxin.com/>
* Ditecting: <https://www.ditecting.com/>
* Quake: <https://quake.360.cn/quake/>
* Censys: <https://search.censys.io/>
* Netlas: <https://app.netlas.io/domains/>

#### 网页/端口 *Web/Ports*

* Wayback Machine: <https://web.archive.org/> 历史网页存档
* VisualPing: <https://visualping.io/> 网站变更监控
* Dark Web Exposure: <https://www.immuniweb.com/darkweb/>
* SG TCP/IP: <https://www.speedguide.net/ports.php> 端口数据库

#### 谷歌搜索 *Google Hacking*

* <https://github.com/cipher387/Dorks-collections-list> ⭐ 2,726 | 🐛 2 | 📅 2025-04-11 Google Hacking 数据库
* <https://github.com/obheda12/GitDorker> ⭐ 2,572 | 🐛 22 | 🌐 Python | 📅 2024-08-03 Google Hacking 命令行工具
* <https://github.com/six2dez/dorks_hunter> ⭐ 345 | 🐛 0 | 🌐 Python | 📅 2026-07-14 Google Hacking 命令行工具
* <https://github.com/Pa55w0rd/google-hacking-assistant> ⭐ 148 | 🐛 0 | 🌐 TypeScript | 📅 2025-10-16 Chrome 扩展程序
* <https://www.exploit-db.com/google-hacking-database> Google Hacking 数据库
* <https://cxsecurity.com/dorks/> Google Hacking 数据库
* <https://dorks.faisalahmed.me/> Google Hacking 在线工具
* <https://pentest-tools.com/information-gathering/google-hacking> Google Hacking 在线工具
* <http://advangle.com/> Google Hacking 在线工具
* <https://0iq.me/gip/> Google Hacking 在线工具

#### Github 搜索 *Github Dork*

* <https://github.com/obheda12/GitDorker> ⭐ 2,572 | 🐛 22 | 🌐 Python | 📅 2024-08-03 Github Dork
* <https://github.com/damit5/gitdorks_go> ⭐ 230 | 🐛 5 | 🌐 Go | 📅 2022-04-21 Github Dork
* <https://github.com/search/advanced> Github Dork

### 开源情报 *Open-Source Intelligence*

#### 综合工具 *Nice Tools*

* OSINT Resource List: <https://start.me/p/rx6Qj8/nixintel-s-osint-resource-list>
* OSINT Framework: <https://osintframework.com/>
* OSINT Handbook: <https://i-intelligence.eu/uploads/public-documents/OSINT_Handbook_2020.pdf>

#### 威胁情报 *Threat Intelligence*

* Virustotal: <https://www.virustotal.com/>
* 腾讯哈勃分析系统: <https://habo.qq.com/tool/index>
* 微步在线威胁情报: <https://x.threatbook.com/>
* 奇安信威胁情报: <https://ti.qianxin.com/>
* 360 威胁情报: <https://ti.360.net/>
* 网络安全威胁信息共享平台: <https://share.anva.org.cn/web/publicity/listPhishing>
* 安恒威胁情报: <https://ti.dbappsecurity.com.cn/>
* 火线安全平台: <https://www.huoxian.cn>
* 知道创宇黑客新闻流: <https://hackernews.cc/>
* SecWiki 安全信息流: <https://www.sec-wiki.com/>

#### 漏洞披露 *Disclosed Vulnerabilities*

* 国家信息安全漏洞库: <https://www.cnnvd.org.cn/>
* 国家互联网应急中心: <https://www.cert.org.cn/>
* 360 网络安全响应中心: <https://cert.360.cn/>
* 知道创宇漏洞库: <https://www.seebug.org/>
* 长亭漏洞库: <https://stack.chaitin.com/vuldb/>
* 阿里云漏洞库: <https://avd.aliyun.com/high-risk/list>
* PeiQi 漏洞库: <https://peiqi.wgpsec.org/>
* Hackerone: <https://www.hackerone.com/>
* CVE: <https://cve.mitre.org/>
* National Vulnerability Database: <https://nvd.nist.gov/>
* Vulnerability & Exploit Database: <https://www.rapid7.com/db/>
* Packet Storm's file archive: <https://packetstormsecurity.com/files/tags/exploit>
* Shodan: <https://cvedb.shodan.io/cves> 实时更新 CVE 漏洞信息 `curl https://cvedb.shodan.io/cves | jq '[.cves[] | select(.cvss > 8)]'`
* CVEShield: <https://www.cveshield.com/> 最新热门漏洞

#### 接口检索 *API Search*

* <https://www.postman.com/explore/> 公共 API
* <https://rapidapi.com/> 公共 API
* <https://serene-agnesi-57a014.netlify.app/> 发现 API keys

#### 源代码检索 *Source Code Search*

* <https://publicwww.com/>
* <https://searchcode.com/>

### 开源资源 *Open-Source Resources*

#### 社区/知识库 *Communities/Knowledge Base*

* 先知社区: <https://xz.aliyun.com/>
* Infocon: <https://infocon.org/>
* ffffffff0x 安全知识框架: <https://github.com/ffffffff0x/1earn> ⭐ 5,702 | 🐛 1 | 🌐 C++ | 📅 2024-06-06
* 狼组公开知识库: <https://wiki.wgpsec.org/>
* Mitre ATT\&CK matrices: <https://attack.mitre.org/matrices/enterprise>
* Mitre ATT\&CK techniques: <http://attack.mitre.org/techniques/enterprise/>
* Hacking Articles: <https://www.hackingarticles.in/>
* PostSwigger Blog: <https://portswigger.net/blog>
* InGuardians Labs Blog: <https://www.inguardians.com/>
* Pentest Workflow: <https://pentest.mxhx.org/>
* Pentest Cheatsheet: <https://pentestbook.six2dez.com/>

#### 思维导图/备忘录 *Mindmap/Cheat Sheets*

* <https://github.com/Ignitetechnologies/Mindmap/> ⭐ 9,194 | 🐛 15 | 📅 2026-07-21 网络安全思维导图
* <https://github.com/WADComs/WADComs.github.io> ⭐ 1,703 | 🐛 5 | 🌐 HTML | 📅 2025-08-29 Windows/域速查表 👍
* <https://cheatsheets.zip/> 开发者速查表
* <https://learnxinyminutes.com/> 编程/工具/命令/操作系统/快捷键速查表
* <https://html5sec.org/> HTML5 安全速查表
* <https://orange-cyberdefense.github.io/ocd-mindmaps/img/mindmap_ad_dark_classic_2025.03.excalidraw.svg> 域攻防思维导图

#### 进攻性安全 *Red Teaming and Offensive Security*

* <https://www.ired.team/>
* <https://www.thehacker.recipes/>
* <https://ppn.snovvcrash.rocks/>
* <https://book.hacktricks.xyz/>
* <https://blog.harmj0y.net/>
* <https://hausec.com/domain-penetration-testing/>
* <https://dirkjanm.io/>
* <https://casvancooten.com/>
* <https://evasions.checkpoint.com/>
* <https://redteam.guide/docs/definitions>
* <https://github.com/HadessCS/Red-team-Interview-Questions> ⭐ 774 | 🐛 2 | 📅 2025-04-11

#### 防御性安全 *Blue Teaming and Defensive Security*

* <https://github.com/Purp1eW0lf/Blue-Team-Notes> ⭐ 1,768 | 🐛 0 | 📅 2026-08-09

#### 操作安全 *Operation Security*

* <https://github.com/WesleyWong420/OPSEC-Tradecraft> ⭐ 333 | 🐛 0 | 🌐 PowerShell | 📅 2026-03-24

#### 实战平台 *Learning and Practice Platforms*

* Cybrary: <https://www.cybrary.it/>
* HacktheBox: <https://www.hackthebox.com/>
* TryHackMe: <https://tryhackme.com/>
* Try2Hack: <https://try2hack.me/>
* Vulnmachines: <https://www.vulnmachines.com/>
* RangeForce: <https://www.rangeforce.com/>
* Root Me: <https://www.root-me.org/>
* ichunqiu: <https://yunjing.ichunqiu.com/>
* echoCTF: <https://github.com/echoCTF/echoCTF.RED> ⭐ 149 | 🐛 23 | 🌐 PHP | 📅 2026-08-14 适用于 CTF 竞赛
* Vulnhub: <https://www.vulnhub.com/>

Mac M1 使用 Vulnhub 等 ova 格式镜像，需要将 ova 格式转为 qcow2，再通过 UTM 运行：

* <https://github.com/utmapp/UTM> ⭐ 35,015 | 🐛 1,095 | 🌐 Swift | 📅 2026-08-05
* <https://github.com/qemu/qemu> ⭐ 13,574 | 🐛 0 | 🌐 C | 📅 2026-08-14

## 信息收集 *Reconnaissance*

### 综合工具 *Nice Tools*

* Amass: <https://github.com/owasp-amass/amass> ⭐ 14,983 | 🐛 236 | 🌐 Go | 📅 2026-07-19
* fscan: <https://github.com/shadow1ng/fscan> ⭐ 14,253 | 🐛 23 | 🌐 Go | 📅 2026-07-15
* OneForAll: <https://github.com/shmilylty/OneForAll> ⭐ 9,989 | 🐛 107 | 🌐 Python | 📅 2026-05-11
* kscan: <https://github.com/lcvvvv/kscan> ⭐ 4,291 | 🐛 52 | 🌐 Go | 📅 2023-08-22
* TscanPlus: <https://github.com/TideSec/TscanPlus> ⭐ 4,191 | 🐛 22 | 📅 2026-08-14
* ShuiZe: <https://github.com/0x727/ShuiZe_0x727> ⭐ 4,019 | 🐛 163 | 🌐 Python | 📅 2024-06-13
* dddd: <https://github.com/SleepingBag945/dddd> ⭐ 1,923 | 🐛 56 | 🌐 Go | 📅 2024-08-02
* Fofa Viewer: <https://github.com/wgpsec/fofa_viewer> ⭐ 1,801 | 🐛 20 | 🌐 Java | 📅 2025-12-26
* AlliN: <https://github.com/P1-Team/AlliN> ⭐ 1,287 | 🐛 2 | 🌐 Python | 📅 2025-08-22
* qscan: <https://github.com/qi4L/qscan> ⭐ 1,202 | 🐛 1 | 🌐 Go | 📅 2026-05-24
* Kunyu: <https://github.com/knownsec/Kunyu> ⭐ 1,073 | 🐛 31 | 🌐 Python | 📅 2025-02-06
* FofaX: <https://github.com/xiecat/fofax> ⭐ 836 | 🐛 2 | 🌐 Go | 📅 2026-03-06
* ApolloScanner: <https://github.com/b0bac/ApolloScanner> ⭐ 746 | 🐛 18 | 🌐 JavaScript | 📅 2026-02-05
* ENScan\_GO: <https://github.com/wgpsec/ENScan_GO>

### IP/域名/子域名 *IP/Domain/Subdomain*

* IP:
  * <https://www.ipuu.net/>
  * <https://site.ip138.com/>
  * <https://myip.ms/>
  * <https://ipwhois.cnnic.net.cn>
* Multi Ping:
  * <https://ping.chinaz.com/>
  * <https://www.host-tracker.com/>
  * <https://www.webpagetest.org/>
  * <https://dnscheck.pingdom.com/>
* IP to Domain:
  * <https://site.ip138.com/>
  * <https://x.threatbook.cn/>
  * <https://www.virustotal.com/>
* Whois:
  * <https://whois.chinaz.com/>
  * <https://whois.aliyun.com/>
  * <https://who.is/>
  * <https://www.whoxy.com/>
* DNS:
  * <https://hackertarget.com/find-dns-host-records>
  * <https://dnsdumpster.com>
  * <https://dnsdb.io/zh-cn>
  * <https://centralops.net/co/>
  * <https://viewdns.info/>
  * <https://dnsdumpster.com/>
  * <https://rapiddns.io/>
* ASN:
  * <https://wq.apnic.net/>
  * <https://bgp.he.net/>
  * <https://bgpview.io/>
* TLS/SSL 证书:
  * <https://censys.io>
  * <https://crt.sh>

### 指纹 *Fingerprint*

#### 指纹库 *Fingerprint Collection*

* <https://github.com/0x727/FingerprintHub> ⭐ 1,431 | 🐛 0 | 🌐 Rust | 📅 2026-08-15
* <https://github.com/r0eXpeR/fingerprint> ⭐ 526 | 🐛 0 | 🌐 Ruby | 📅 2021-11-03

#### 指纹识别 *Fingerprint Reconnaissance*

* <https://github.com/EdgeSecurityTeam/EHole> ⭐ 3,509 | 🐛 43 | 🌐 Go | 📅 2024-04-02
* <https://github.com/zhzyker/dismap> ⭐ 2,163 | 🐛 23 | 🌐 Go | 📅 2024-01-29
* <https://github.com/EASY233/Finger> ⭐ 1,725 | 🐛 20 | 🌐 Python | 📅 2023-12-22
* <https://github.com/lemonlove7/EHole_magic> ⭐ 971 | 🐛 5 | 🌐 Go | 📅 2024-03-06
* <https://github.com/TideSec/TideFinger_Go> ⭐ 334 | 🐛 8 | 📅 2025-02-07
* <https://github.com/0x727/ObserverWard>
* <https://www.webshell.cc/4697.html>
* <http://www.yunsee.cn/> online

#### WAF 识别 *Waf Checks*

* <https://github.com/EnableSecurity/wafw00f> ⭐ 6,517 | 🐛 0 | 🌐 Python | 📅 2026-04-19
* <https://github.com/stamparm/identYwaf> ⭐ 743 | 🐛 0 | 🌐 Python | 📅 2024-06-25
* <https://github.com/MISP/misp-warninglists> ⭐ 643 | 🐛 46 | 🌐 Python | 📅 2026-08-14

### 扫描/爆破 *Brute Force*

#### 扫描/爆破工具 *Brute Force Tools*

* Port:
  * <https://github.com/antirez/hping> ⭐ 1,710 | 🐛 67 | 🌐 C | 📅 2024-07-10
* Subdomain:
  * <https://github.com/projectdiscovery/subfinder> ⭐ 14,208 | 🐛 9 | 🌐 Go | 📅 2026-08-12
  * <https://github.com/knownsec/ksubdomain> ⭐ 2,391 | 🐛 29 | 🌐 Go | 📅 2022-03-16
* Web:
  * <https://github.com/OJ/gobuster> ⭐ 13,992 | 🐛 20 | 🌐 Go | 📅 2026-08-13
  * <https://github.com/xmendez/wfuzz> ⭐ 6,554 | 🐛 116 | 🌐 Python | 📅 2026-01-21
  * <https://github.com/s0md3v/Arjun> ⭐ 6,380 | 🐛 21 | 🌐 Python | 📅 2025-02-20
  * <https://github.com/pingc0y/URLFinder> ⭐ 3,165 | 🐛 44 | 🌐 Go | 📅 2026-06-17
  * <https://github.com/jaeles-project/gospider> ⭐ 2,992 | 🐛 57 | 🌐 Go | 📅 2024-04-21
* Directory:
  * <https://github.com/ffuf/ffuf> ⭐ 16,531 | 🐛 231 | 🌐 Go | 📅 2026-07-19
  * <https://github.com/maurosoria/dirsearch> ⭐ 14,629 | 🐛 30 | 🌐 Python | 📅 2026-08-14
  * <https://github.com/H4ckForJob/dirmap> ⭐ 3,373 | 🐛 41 | 🌐 Python | 📅 2025-10-21
* Password:
  * <https://github.com/vanhauser-thc/thc-hydra> ⭐ 12,166 | 🐛 49 | 🌐 C | 📅 2026-07-30
  * <https://github.com/evilsocket/legba/> ⭐ 1,927 | 🐛 1 | 🌐 Rust | 📅 2026-08-14
  * <https://github.com/galkan/crowbar> ⭐ 1,527 | 🐛 46 | 🌐 Python | 📅 2023-12-19 支持 sshkey 和 openvpn
* Hash 破解:
  * <https://github.com/hashcat/hashcat> ⭐ 26,550 | 🐛 386 | 🌐 C | 📅 2026-08-15
  * <https://github.com/openwall/john> ⭐ 13,499 | 🐛 512 | 🌐 C | 📅 2026-08-01
  * <https://github.com/HashPals/Name-That-Hash> ⭐ 1,663 | 🐛 7 | 🌐 Python | 📅 2025-12-19 哈希类型识别
  * <https://github.com/noraj/haiti> ⭐ 1,001 | 🐛 3 | 🌐 Ruby | 📅 2026-08-10 哈希类型识别
  * <https://hashcat.net/wiki/doku.php?id=example_hashes> hashcat 示例
* Json web token (JWT):
  * <https://github.com/ticarpi/jwt_tool> ⭐ 6,743 | 🐛 74 | 🌐 Python | 📅 2025-05-01
  * <https://github.com/brendan-rius/c-jwt-cracker> ⭐ 2,559 | 🐛 16 | 🌐 C | 📅 2023-06-02
  * <https://github.com/wallarm/jwt-secrets/blob/master/jwt.secrets.list> ⭐ 1,137 | 🐛 3 | 📅 2025-03-12
  * <https://github.com/hahwul/jwt-hack> ⭐ 1,015 | 🐛 0 | 🌐 Rust | 📅 2026-08-13
  * <https://github.com/mazen160/jwt-pwn> ⭐ 333 | 🐛 1 | 🌐 Python | 📅 2026-03-13
  * <https://github.com/Sjord/jwtcrack> ⭐ 257 | 🐛 3 | 🌐 Python | 📅 2026-03-13
  * <https://jwt.io/>

#### 扫描/爆破字典 *Brute Force Dictionaries*

* Wordlists for All:
  * <https://github.com/danielmiessler/SecLists> ⭐ 72,861 | 🐛 12 | 🌐 PHP | 📅 2026-08-15 46.4k star
  * <https://github.com/rapid7/metasploit-framework/tree/master/data/wordlists> ⭐ 38,812 | 🐛 611 | 🌐 Ruby | 📅 2026-08-13
  * <https://github.com/TheKingOfDuck/fuzzDicts> ⭐ 8,418 | 🐛 0 | 🌐 Python | 📅 2023-11-13
  * <https://github.com/Bo0oM/fuzz.txt> ⭐ 3,317 | 🐛 8 | 📅 2026-07-28
  * <https://github.com/gh0stkey/Web-Fuzzing-Box> ⭐ 2,787 | 🐛 0 | 🌐 HTML | 📅 2026-03-23
  * <https://github.com/insightglacier/Dictionary-Of-Pentesting> ⭐ 2,070 | 🐛 0 | 🌐 Shell | 📅 2023-07-21
  * <https://github.com/a3vilc0de/PentesterSpecialDict> ⭐ 1,910 | 🐛 1 | 🌐 PHP | 📅 2025-06-17
  * <https://github.com/assetnote/wordlists> ⭐ 1,717 | 🐛 3 | 🌐 CSS | 📅 2026-02-27
  * <https://github.com/SexyBeast233/SecDictionary> ⭐ 1,578 | 🐛 2 | 📅 2026-03-17 + ffuf
* Web Fuzz Wordlists:
  * <https://github.com/xmendez/wfuzz/tree/master/wordlist> ⭐ 6,554 | 🐛 116 | 🌐 Python | 📅 2026-01-21
  * <https://github.com/lutfumertceylan/top25-parameter> ⭐ 1,846 | 🐛 2 | 📅 2024-06-09
* Others (not frequently used):
  * <https://github.com/danielmiessler/SecLists/tree/master/Discovery/Web-Content> ⭐ 72,861 | 🐛 12 | 🌐 PHP | 📅 2026-08-15
  * <https://github.com/google/fuzzing/tree/master/dictionaries> ⚠️ Archived
  * <https://github.com/six2dez/OneListForAll> ⭐ 3,227 | 🐛 1 | 🌐 Go | 📅 2026-03-11
  * <https://github.com/random-robbie/bruteforce-lists> ⭐ 1,426 | 🐛 1 | 📅 2026-04-30
  * <https://github.com/assetnote/commonspeak2-wordlists/tree/master/wordswithext> ⭐ 545 | 🐛 1 | 📅 2018-08-23

#### 字典生成 *Generate a Custom Dictionary*

* Online:
  * Generate wordlists: <https://weakpass.com/generate>
  * Generate subdomains and wordlists: <https://weakpass.com/generate/domains>
  * 汉字转拼音: <https://www.aies.cn/pinyin.htm>
  * 密码猜解: <https://www.hacked.com.cn/pass.html>
* Private Deployment:
  * Generate wordlists(offline): <https://github.com/zzzteph/weakpass> ⭐ 731 | 🐛 0 | 🌐 Vue | 📅 2026-08-06
  * Generate subdomains and wordlists(offline): <https://github.com/zzzteph/probable_subdomains> ⚠️ Archived
* Offline:
  * pydictor: <https://github.com/LandGrey/pydictor/> ⭐ 3,648 | 🐛 13 | 🌐 Python | 📅 2024-12-05
  * crunch:
    * Windows: <https://github.com/shadwork/Windows-Crunch> ⭐ 58 | 🐛 1 | 🌐 C | 📅 2015-07-01
    * Kali/Linux: <https://sourceforge.net/projects/crunch-wordlist>

#### 默认口令查询 *Default Credentials*

* Default Credentials Cheat Sheet: <https://github.com/ihebski/DefaultCreds-cheat-sheet> ⭐ 6,714 | 🐛 0 | 🌐 Python | 📅 2026-07-09 3468 条默认口令
* datarecovery: <https://datarecovery.com/rd/default-passwords/> online
* cirt.net: <https://cirt.net/passwords> online
* Online Router Passwords:
  * <https://www.routerpasswords.com/>
  * <https://portforward.com/router-password/>
  * <https://www.cleancss.com/router-default/>
  * <https://www.toolmao.com/baiduapp/routerpwd/>
  * <https://datarecovery.com/rd/default-passwords/>

### 社会工程学 *Social Engineering*

#### 凭据泄露 *Leaked Credentials*

* <https://have-ibeenpwned.com/>
* <https://breachdirectory.org/>

#### 邮箱 *Email*

* Temporary Email:
  * <http://24mail.chacuo.net/>
  * <https://www.guerrillamail.com/>
  * <https://rootsh.com/>
* Snov.io: <https://app.snov.io>
* Phonebook: 同时支持子域名和 URL <https://phonebook.cz>
* Skymem: <https://www.skymem.info>
* Hunter: <https://hunter.io>
* email-format: <https://www.email-format.com/i/search/>
* 搜邮箱: <https://souyouxiang.com/find-contact/>
* theHarvester: 同时支持子域名查询 <https://github.com/laramies/theHarvester> ⭐ 17,062 | 🐛 8 | 🌐 Python | 📅 2026-08-15
* Verify emails: <https://tools.emailhippo.com/>
* Accounts registered by email: <https://emailrep.io/>

#### 短信 *SMS Online*

* <https://sms-activate.io> 👍 覆盖 180+ 国家
* <https://www.supercloudsms.com/en/>
* <https://getfreesmsnumber.com/>
* <https://www.zusms.com/>
* <https://yunduanxin.net/>
* <https://www.free-sms-receive.com/>
* <https://receive-sms.cc/#google_vignette>
* <https://bestsms.xyz/>
* <https://smscodeonline.com/>

#### 钓鱼 *Phishing*

* gophish: <https://github.com/gophish/gophish> ⭐ 14,124 | 🐛 752 | 🌐 Go | 📅 2024-09-23 开源钓鱼工具包
* SpoofWeb: <https://github.com/5icorgi/SpoofWeb> ⭐ 143 | 🐛 0 | 📅 2020-06-06 部署钓鱼网站

### 移动端 *Mobile*

* <https://www.xiaolanben.com/>
* <https://www.qimai.cn/>

## 漏洞研究 *Vulnerability Research*

### 漏洞环境 *Vulnerable Environments*

#### 基础漏洞 *Basic Vulnerabilities*

* DVWA: <https://github.com/digininja/DVWA> ⭐ 13,499 | 🐛 7 | 🌐 PHP | 📅 2026-08-07
* WebGoat: <https://github.com/WebGoat/WebGoat> ⭐ 9,278 | 🐛 35 | 🌐 JavaScript | 📅 2026-08-14
* Sqli-labs: <https://github.com/Audi-1/sqli-labs> ⭐ 5,828 | 🐛 33 | 🌐 PHP | 📅 2023-12-11
* Upload-labs: <https://github.com/c0ny1/upload-labs> ⭐ 4,183 | 🐛 26 | 🌐 PHP | 📅 2023-06-26
* encrypt-labs: <https://github.com/SwagXz/encrypt-labs> ⭐ 578 | 🐛 2 | 🌐 PHP | 📅 2025-06-17 AES/DES/RSA
* Xss-labs: <https://github.com/do0dl3/xss-labs> ⭐ 342 | 🐛 1 | 📅 2024-03-14

#### 综合漏洞 *Comprehensive Vulnerabilities*

* Vulfocus: <https://github.com/fofapro/vulfocus> ⭐ 3,495 | 🐛 74 | 🌐 Vue | 📅 2025-09-09
* Vulstudy: <https://github.com/c0ny1/vulstudy> ⭐ 2,452 | 🐛 19 | 🌐 Shell | 📅 2020-03-25 基于 Docker 的 17 个漏洞平台
* FastJsonParty: <https://github.com/lemono0/FastJsonParty> ⭐ 1,245 | 🐛 4 | 🌐 Python | 📅 2024-07-12
* Vulhub: <https://vulhub.org/>
* PortSwigger Web Security Academy: <https://portswigger.net/web-security>
* OWASP Top10: <https://owasp.org/www-project-juice-shop/>

#### 工控环境 *Vulnerable IoT Environment*

* IoT-vulhub: <https://github.com/firmianay/IoT-vulhub> ⭐ 1,294 | 🐛 14 | 🌐 Python | 📅 2023-07-30

#### 域环境 *Vulnerable Active Directory Environment*

* Game of active directory: <https://github.com/Orange-Cyberdefense/GOAD> ⭐ 8,195 | 🐛 147 | 🌐 PowerShell | 📅 2026-03-12
* BadBlood: <https://github.com/davidprowe/BadBlood> ⭐ 2,258 | 🐛 8 | 🌐 PowerShell | 📅 2023-06-07 创建你自己的示例 Active Directory 环境

#### 云环境 *Vulnerable Cloud Environments*

* Kubernetes Goat: <https://github.com/madhuakula/kubernetes-goat> ⭐ 5,747 | 🐛 28 | 🌐 HTML | 📅 2026-04-16
* CloudGoat: <https://github.com/RhinoSecurityLabs/cloudgoat> ⭐ 3,694 | 🐛 23 | 🌐 Python | 📅 2026-04-28
* Awesome-CloudSec-Labs: <https://github.com/iknowjason/Awesome-CloudSec-Labs> ⭐ 2,176 | 🐛 5 | 📅 2025-10-01
* AWSGoat: <https://github.com/ine-labs/AWSGoat> ⭐ 2,041 | 🐛 12 | 🌐 PHP | 📅 2025-05-20
* Metarget: <https://github.com/Metarget/metarget> ⭐ 1,411 | 🐛 44 | 🌐 Python | 📅 2026-07-22
* badPods: <https://github.com/BishopFox/badPods> ⭐ 707 | 🐛 0 | 🌐 Shell | 📅 2025-12-30
* TerraformGoat: <https://github.com/HXSecurity/TerraformGoat> ⭐ 638 | 🐛 8 | 🌐 HCL | 📅 2022-11-30
* K8s Lan Party: <https://www.k8slanparty.com/>
* Attack Defense: <https://attackdefense.pentesteracademy.com/listing?labtype=cloud-services&subtype=cloud-services-amazon-s3>

### PoC *Proof of Concept*

> Be careful Malware，POC 库最新的 CVE 可能存在投毒风险。

#### PoC/ExP

* <https://github.com/trickest/cve> ⭐ 8,000 | 🐛 21 | 🌐 HTML | 📅 2026-08-15
* <https://github.com/nomi-sec/PoC-in-GitHub> ⭐ 7,969 | 🐛 17 | 📅 2026-08-15
* <https://github.com/Mr-xn/Penetration_Testing_POC> ⭐ 7,453 | 🐛 0 | 🌐 HTML | 📅 2026-08-11
* <https://github.com/coffeehb/Some-PoC-oR-ExP> ⭐ 2,502 | 🐛 2 | 🌐 Python | 📅 2025-06-24
* <https://github.com/helloexp/0day> ⭐ 2,364 | 🐛 5 | 🌐 C | 📅 2023-09-12
* <https://github.com/ycdxsb/PocOrExp_in_Github> ⭐ 1,190 | 🐛 1 | 🌐 Python | 📅 2026-08-15
* <https://github.com/DawnFlame/POChouse> ⭐ 1,107 | 🐛 1 | 🌐 Python | 📅 2022-11-11
* <https://github.com/lal0ne/vulnerability> ⭐ 971 | 🐛 1 | 🌐 Go | 📅 2025-07-27
* <https://github.com/luck-ying/Library-POC> ⭐ 882 | 🐛 0 | 🌐 Python | 📅 2024-04-12
* <https://github.com/wy876/POC>
* <https://sploitus.com/> 本周漏洞利用集合
* <https://www.exploit-db.com/> 配合 `searchsploit <关键词>` 使用

#### PoC 模板 *PoC Templates*

* <https://github.com/projectdiscovery/nuclei-templates/> ⭐ 12,801 | 🐛 137 | 🌐 JavaScript | 📅 2026-08-15 offline
* <https://github.com/zeoxisca/gamma-gui> ⭐ 110 | 🐛 4 | 🌐 JavaScript | 📅 2023-03-17 online
* <https://poc.xray.cool/>

## 漏洞利用 *Vulnerability Exploits*

### 综合工具 *Nice Tools*

* <https://github.com/projectdiscovery/nuclei> ⭐ 30,522 | 🐛 105 | 🌐 Go | 📅 2026-08-15
* <https://github.com/chaitin/xray> ⭐ 11,704 | 🐛 70 | 🌐 Vue | 📅 2024-10-29
* <https://github.com/zan8in/afrog> ⭐ 4,368 | 🐛 109 | 🌐 Go | 📅 2026-08-04
* <https://github.com/zhzyker/vulmap> ⭐ 3,523 | 🐛 31 | 🌐 Python | 📅 2023-04-26
* <https://github.com/chaitin/xpoc> ⭐ 1,184 | 🐛 35 | 📅 2024-07-19

### 代码审计 *Code Audit*

* tabby: <https://github.com/wh1t3p1g/tabby> ⭐ 1,656 | 🐛 10 | 🌐 Java | 📅 2026-01-17

### 序列化 *Serialization*

#### Java

* <https://github.com/phith0n/zkar> ⭐ 653 | 🐛 11 | 🌐 Go | 📅 2026-04-19

### 反序列化 *Deserialization*

#### Java

* <https://github.com/frohoff/ysoserial> ⭐ 9,022 | 🐛 47 | 🌐 Java | 📅 2025-12-04
* <https://github.com/mbechler/marshalsec> ⭐ 3,705 | 🐛 5 | 🌐 Java | 📅 2025-01-09
* <https://github.com/welk1n/JNDI-Injection-Exploit> ⭐ 2,826 | 🐛 10 | 🌐 Java | 📅 2023-03-22
* <https://github.com/Java-Chains/web-chains> ⭐ 2,144 | 🐛 1 | 🌐 Shell | 📅 2026-08-15
* <https://github.com/qi4L/JYso> ⭐ 1,759 | 🐛 0 | 🌐 Java | 📅 2026-06-14
* <https://github.com/wh1t3p1g/ysomap> ⭐ 1,248 | 🐛 5 | 🌐 Java | 📅 2025-02-17
* <https://github.com/Y4er/ysoserial> ⭐ 778 | 🐛 0 | 🌐 Java | 📅 2026-05-26
* <https://github.com/rebeyond/JNDInjector> ⭐ 476 | 🐛 5 | 📅 2023-01-17
* <https://github.com/A-D-Team/attackRmi> ⭐ 231 | 🐛 0 | 📅 2022-01-03
* <https://github.com/vulhub/JNDIExploit> ⭐ 53 | 🐛 0 | 🌐 Java | 📅 2023-04-29
* <https://github.com/DeEpinGh0st/ysoserial> ⭐ 4 | 🐛 0 | 📅 2024-01-24
* <https://github.com/WhiteHSBG/JNDIExploit>

#### PHP

* <https://github.com/ambionics/phpggc> ⭐ 3,873 | 🐛 21 | 🌐 PHP | 📅 2025-09-29 PHP 反序列化漏洞利用载荷

### 数据库 *Database*

#### Redis

* <https://github.com/qishibo/AnotherRedisDesktopManager> ⭐ 34,637 | 🐛 158 | 🌐 JavaScript | 📅 2026-08-13
* <https://github.com/cinience/RedisStudio> ⭐ 1,543 | 🐛 29 | 🌐 C++ | 📅 2025-07-01
* <https://github.com/n0b0dyCN/redis-rogue-server> ⭐ 1,171 | 🐛 6 | 🌐 C | 📅 2023-09-24
* <https://github.com/Ridter/redis-rce> ⭐ 979 | 🐛 2 | 🌐 Python | 📅 2021-11-30
* <https://github.com/yuyan-sec/RedisEXP> ⭐ 946 | 🐛 0 | 🌐 Go | 📅 2025-01-26
* <https://github.com/r35tart/RedisWriteFile> ⭐ 719 | 🐛 3 | 🌐 Python | 📅 2020-05-25

#### MySQL

* <https://github.com/SafeGroceryStore/MDUT> ⭐ 2,254 | 🐛 0 | 📅 2026-07-23 多数据库利用工具
* <https://github.com/fnmsd/MySQL_Fake_Server> ⭐ 1,379 | 🐛 10 | 🌐 Python | 📅 2021-11-18
* <https://github.com/4ra1n/mysql-fake-server> ⚠️ Archived
* <https://github.com/dushixiang/evil-mysql-server> ⭐ 101 | 🐛 0 | 🌐 Go | 📅 2022-10-23

#### Oracle

* odat: <https://github.com/quentinhardy/odat> ⭐ 1,773 | 🐛 10 | 🌐 Python | 📅 2026-03-31 远程代码执行
* sqlplus: <https://www.oracle.com/database/technologies/instant-client/linux-x86-64-downloads.html> 以 sysdba 身份执行

#### MSSQL

* <https://github.com/uknowsec/SharpSQLTools> ⭐ 972 | 🐛 6 | 🌐 C# | 📅 2021-08-05
* <https://github.com/Ridter/PySQLTools> ⭐ 279 | 🐛 0 | 🌐 Python | 📅 2023-08-07

### 信息泄露 *Information Disclosure*

* gitleaks: <https://github.com/gitleaks/gitleaks> ⭐ 28,741 | 🐛 462 | 🌐 Go | 📅 2026-07-29
* trufflehog: <https://github.com/trufflesecurity/trufflehog> ⭐ 27,477 | 🐛 515 | 🌐 Go | 📅 2026-08-14 发现、验证并分析泄露的凭据
* git-dumper: <https://github.com/arthaud/git-dumper> ⭐ 2,639 | 🐛 10 | 🌐 Python | 📅 2026-07-09
* Hawkeye: <https://github.com/0xbug/Hawkeye> ⭐ 2,033 | 🐛 58 | 🌐 Vue | 📅 2022-05-21 GitHub 敏感信息泄露监控爬虫
* dvcs-ripper: <https://github.com/kost/dvcs-ripper> ⭐ 1,781 | 🐛 11 | 🌐 Perl | 📅 2024-07-19 .svn、.hg、.cvs 信息泄露
* ds\_store\_exp: <https://github.com/lijiejie/ds_store_exp> ⭐ 1,739 | 🐛 16 | 🌐 Python | 📅 2023-05-06 .DS\_Store 信息泄露

### CMS/OA 漏洞 *CMS/OA*

* Apt\_t00ls: <https://github.com/White-hua/Apt_t00ls> ⭐ 1,831 | 🐛 3 | 🌐 Java | 📅 2025-02-12
* OA-EXPTOOL: <https://github.com/LittleBear4/OA-EXPTOOL> ⭐ 1,346 | 🐛 24 | 🌐 Python | 📅 2023-10-28
* DecryptTools: <https://github.com/wafinfo/DecryptTools> ⭐ 1,326 | 🐛 25 | 📅 2025-03-02 22 种加解密
* PassDecode-jar: <https://github.com/Rvn0xsy/PassDecode-jar> ⭐ 363 | 🐛 1 | 🌐 Java | 📅 2021-07-29 帆软/致远解密
* TongdaScan\_go: <https://github.com/Fu5r0dah/TongdaScan_go> ⭐ 219 | 🐛 1 | 🌐 Go | 📅 2023-05-27
* LandrayDES: <https://github.com/zhutougg/LandrayDES> ⭐ 95 | 🐛 1 | 🌐 Java | 📅 2020-12-21 蓝凌 OA 解密
* ncDecode: <https://github.com/1amfine2333/ncDecode> ⭐ 27 | 🐛 1 | 📅 2021-06-20 用友 NC 解密
* ezOFFICE\_Decrypt: <https://github.com/wafinfo/ezOFFICE_Decrypt> ⭐ 21 | 🐛 0 | 📅 2023-12-03 万户解密

### 中间件/应用层 *Middleware/Application*

**Confluence**

* ConfluenceMemshell: <https://github.com/Lotus6/ConfluenceMemshell> ⭐ 566 | 🐛 1 | 📅 2024-02-01
* CVE-2022-26134 Memshell: <https://github.com/BeichenDream/CVE-2022-26134-Godzilla-MEMSHELL> ⭐ 340 | 🐛 2 | 🌐 Java | 📅 2022-06-07
* CVE-2023-22527 Memshell: <https://github.com/Boogipop/CVE-2023-22527-Godzilla-MEMSHELL> ⭐ 76 | 🐛 0 | 🌐 Java | 📅 2024-02-21

**Druid**

* druid\_sessions: <https://github.com/yuyan-sec/druid_sessions> ⭐ 323 | 🐛 4 | 🌐 Java | 📅 2025-04-04
* DruidCrack: <https://github.com/rabbitmask/DruidCrack> ⭐ 137 | 🐛 0 | 🌐 Java | 📅 2020-12-09

**Fastjson**

* fastjson-exp: <https://github.com/amaz1ngday/fastjson-exp> ⭐ 330 | 🐛 2 | 📅 2022-03-15

**GitLab**

* CVE-2021-22205: <https://github.com/Al1ex/CVE-2021-22205/> ⭐ 285 | 🐛 1 | 🌐 Python | 📅 2022-11-16

**Nacos**

* NacosRce: <https://github.com/c0olw/NacosRce/> ⭐ 857 | 🐛 13 | 🌐 Java | 📅 2023-07-07
* nacosleak: <https://github.com/a1phaboy/nacosleak> ⭐ 119 | 🐛 4 | 🌐 Go | 📅 2024-06-28
* nacosScan: <https://github.com/Whoopsunix/nacosScan> ⭐ 43 | 🐛 0 | 🌐 Python | 📅 2023-08-09
* NacosExploitGUI: <https://github.com/charonlight/NacosExploitGUI>

**Nps**

* nps-auth-bypass: <https://github.com/carr0t2/nps-auth-bypass>

**Java**

* jdwp-shellifier: python2 <https://github.com/IOActive/jdwp-shellifier> ⭐ 917 | 🐛 8 | 🌐 Python | 📅 2023-12-24
* jdwp-shellifier: <https://github.com/Lz1y/jdwp-shellifier>
* jascypt encryption & decryption: <https://www.devglan.com/online-tools/jasypt-online-encryption-decryption> Jasypt 加解密工具

**Shiro**

* ShiroExploit: <https://github.com/feihong-cs/ShiroExploit-Deprecated> ⭐ 1,957 | 🐛 17 | 🌐 Java | 📅 2021-06-04
* shiro\_rce\_tool: <https://github.com/wyzxxz/shiro_rce_tool> ⭐ 1,593 | 🐛 22 | 📅 2024-05-21
* ShiroExp: <https://github.com/safe6Sec/ShiroExp> ⭐ 654 | 🐛 10 | 🌐 Java | 📅 2023-04-15
* shiro\_key: <https://github.com/yanm1e/shiro_key> ⭐ 183 | 🐛 0 | 📅 2022-03-20 1000+ key
* Shiro rememberMe Decrypt: <https://vulsee.com/tools/shiroDe/shiroDecrypt.html>
* shiro\_attack: <https://github.com/j1anFen/shiro_attack>

**Struts**

* Struts2VulsTools: <https://github.com/shack2/Struts2VulsTools> ⭐ 431 | 🐛 5 | 🌐 C# | 📅 2019-09-27

**Spring Boot**

* SpringBootVulExploit: <https://github.com/LandGrey/SpringBootVulExploit> ⭐ 6,144 | 🐛 5 | 🌐 Java | 📅 2021-03-10
* SpringBoot-Scan: <https://github.com/AabyssZG/SpringBoot-Scan> ⭐ 2,337 | 🐛 2 | 🌐 Python | 📅 2025-11-09
* JDumpSpider: <https://github.com/whwlsfb/JDumpSpider> ⭐ 1,679 | 🐛 2 | 🌐 Java | 📅 2025-12-15
* heapdump\_tool: <https://github.com/wyzxxz/heapdump_tool> ⭐ 1,453 | 🐛 15 | 📅 2024-05-21
* swagger-exp: <https://github.com/lijiejie/swagger-exp> ⭐ 1,383 | 🐛 10 | 🌐 JavaScript | 📅 2024-06-07
* CVE-2022-22947/CVE-2022-22963: <https://github.com/savior-only/Spring_All_Reachable> ⭐ 681 | 🐛 2 | 🌐 Java | 📅 2026-06-26
* CVE-2022-22963 <https://github.com/mamba-2021/EXP-POC/tree/main/Spring-cloud-function-SpEL-RCE> ⭐ 26 | 🐛 0 | 🌐 Python | 📅 2023-01-11
* Memory Analyzer: <https://eclipse.dev/mat/download/>

**Tomcat**

* ClassHound: <https://github.com/LandGrey/ClassHound> ⭐ 710 | 🐛 0 | 🌐 Python | 📅 2021-05-10
* CVE-2020-1938: <https://github.com/YDHCUI/CNVD-2020-10487-Tomcat-Ajp-lfi>

**Thinkphp**

* ThinkphpGUI: <https://github.com/Lotus6/ThinkphpGUI> ⭐ 1,593 | 🐛 16 | 🌐 Java | 📅 2022-06-01
* thinkphp\_gui\_tools: <https://github.com/bewhale/thinkphp_gui_tools> ⭐ 790 | 🐛 8 | 🌐 PHP | 📅 2022-07-02

**Weblogic**

* CVE-2020-14882: <https://github.com/zhzyker/exphub/blob/master/weblogic/cve-2020-14882_rce.py> ⭐ 4,291 | 🐛 3 | 🌐 Python | 📅 2021-04-04
* WeblogicScan: <https://github.com/rabbitmask/WeblogicScan> ⭐ 2,262 | 🐛 9 | 🌐 Python | 📅 2023-05-22
* weblogicScanner: <https://github.com/0xn0ne/weblogicScanner> ⭐ 2,072 | 🐛 4 | 🌐 Python | 📅 2023-11-24
* WeblogicTool: <https://github.com/KimJun1010/WeblogicTool> ⭐ 1,800 | 🐛 4 | 📅 2023-11-01
* WeblogicScan: <https://github.com/dr0op/WeblogicScan> ⭐ 964 | 🐛 5 | 🌐 Python | 📅 2024-06-16
* weblogic-framework: <https://github.com/sv3nbeast/weblogic-framework> ⭐ 44 | 🐛 1 | 📅 2021-12-09

**WebSocket**

* wscat: <https://github.com/websockets/wscat> ⭐ 2,771 | 🐛 36 | 🌐 JavaScript | 📅 2025-05-03

**vCenter**

* VcenterKiller: <https://github.com/Schira4396/VcenterKiller> ⭐ 1,483 | 🐛 4 | 🌐 Go | 📅 2024-04-25
* VcenterKit: <https://github.com/W01fh4cker/VcenterKit> ⭐ 1,270 | 🐛 0 | 🌐 Python | 📅 2025-10-24
* vcenter\_saml\_login: <https://github.com/horizon3ai/vcenter_saml_login> ⭐ 530 | 🐛 13 | 🌐 Python | 📅 2023-09-01 提取身份提供商（IdP）证书

**Zookeeper**

* ZooInspector: <https://issues.apache.org/jira/secure/attachment/12436620/ZooInspector.zip>
* apache-zookeeper: <https://archive.apache.org/dist/zookeeper/zookeeper-3.5.6/> zkCli.sh 命令行工具

## 渗透测试 *Penetration Testing*

### 综合工具 *Nice Tools*

* Yakit: <https://github.com/yaklang/yakit> ⭐ 7,680 | 🐛 135 | 🌐 TypeScript | 📅 2026-08-14
* Burpsuite: <https://portswigger.net/burp>

### 渗透插件 *Extensions*

#### Chrome

* immersive-translate: <https://github.com/immersive-translate/immersive-translate/> ⭐ 18,479 | 🐛 400 | 📅 2026-08-14 翻译工具
* ZeroOmega: <https://github.com/zero-peak/ZeroOmega> ⭐ 7,802 | 🐛 242 | 🌐 CoffeeScript | 📅 2026-05-23 适配 manifest v3 的 proxy switchyOmega
* json-formatter: <https://github.com/callumlocke/json-formatter> ⭐ 4,129 | 🐛 0 | 🌐 TypeScript | 📅 2026-02-26
* Heimdallr: <https://github.com/Ghr07h/Heimdallr> ⭐ 1,679 | 🐛 4 | 🌐 JavaScript | 📅 2023-01-19 蜜罐检测工具
* markdown-viewer: <https://github.com/simov/markdown-viewer> ⭐ 1,648 | 🐛 94 | 🌐 JavaScript | 📅 2025-12-29
* Cookie-Editor: <https://github.com/Moustachauve/cookie-editor> ⭐ 1,644 | 🐛 66 | 🌐 JavaScript | 📅 2026-08-14
* anti-honeypot:<https://github.com/cnrstar/anti-honeypot> ⭐ 891 | 🐛 5 | 🌐 JavaScript | 📅 2024-08-05 蜜罐检测工具
* Hack Bar: <https://github.com/0140454/hackbar> ⭐ 575 | 🐛 1 | 🌐 Vue | 📅 2026-01-22
* FindSomething: <https://github.com/ResidualLaugh/FindSomething> ⭐ 180 | 🐛 0 | 🌐 JavaScript | 📅 2024-11-17 在源代码或 javascript 中查找内容
* serp-analyzer: <https://leadscloud.github.io/serp-analyzer/> 显示域名/IP
* Wappalyzer: <https://www.wappalyzer.com/> 识别网站使用的技术栈
* EditThisCookie: <https://www.editthiscookie.com/>
* Disable JavaScript: <https://github.com/dpacassi/disable-javascript>
* relingo: <https://cn.relingo.net/en/> 翻译工具

#### Burp Suite

* HaE: <https://github.com/gh0stkey/HaE> ⭐ 4,364 | 🐛 0 | 📅 2026-07-31 高亮和提取工具
* domain hunter: <https://github.com/bit4woo/domain_hunter_pro> ⭐ 2,145 | 🐛 14 | 🌐 Java | 📅 2026-06-23 域名收集工具
* BurpCrypto: <https://github.com/whwlsfb/BurpCrypto> ⭐ 1,647 | 🐛 16 | 🌐 Java | 📅 2023-08-04 支持 AES/RSA/DES/ExecJs 加密解密
* autoDecoder: <https://github.com/f0ng/autoDecoder> ⭐ 1,423 | 🐛 8 | 🌐 Java | 📅 2026-04-14 加解密
* RouteVulScan: <https://github.com/F6JO/RouteVulScan> ⭐ 1,334 | 🐛 11 | 🌐 Java | 📅 2026-07-10 路由漏洞扫描工具
* Log4j2Scan: <https://github.com/whwlsfb/Log4j2Scan> ⭐ 836 | 🐛 12 | 🌐 Java | 📅 2023-08-04 Log4j 漏洞扫描工具
* BurpAppletPentester: <https://github.com/mrknow001/BurpAppletPentester> ⭐ 335 | 🐛 0 | 🌐 Java | 📅 2023-05-08 sessionkey 解密工具

#### Yakit

* HaeToYakit: <https://github.com/youmulijiang/HaeToYakit> ⭐ 87 | 🐛 0 | 🌐 Python | 📅 2024-09-10

### 辅助工具 *Auxiliary Tools*

#### 工具集 *Open-Source Toolkit*

* <https://forum.ywhack.com/bountytips.php?tools>
* <https://github.com/knownsec/404StarLink> ⭐ 11,059 | 🐛 7 | 📅 2026-07-31
* <https://pentest-tools.com/>

#### 带外通道 *DNSLog*

* DNSLog-GO: <https://github.com/lanyi1998/DNSlog-GO> ⭐ 1,300 | 🐛 0 | 🌐 Go | 📅 2026-06-26
* Alphalog: dns/http/rmi/ldap <https://github.com/AlphabugX/Alphalog> ⭐ 464 | 🐛 4 | 🌐 Go | 📅 2025-08-20
* dig.pm: <https://dig.pm/>
* ceye.io: <http://ceye.io/>
* dnslog.cn: <http://dnslog.cn/>
* DNS rebinding: <https://lock.cmpxchg8b.com/rebinder.html>

#### 终端优化 *Command Line*

* <https://github.com/ohmyzsh/ohmyzsh> ⭐ 189,213 | 🐛 592 | 🌐 Shell | 📅 2026-08-11 zsh 命令行增强工具
* <https://github.com/jlevy/the-art-of-command-line> ⭐ 162,123 | 🐛 256 | 📅 2024-06-25
* <https://github.com/Eugeny/tabby> ⭐ 73,934 | 🐛 2,850 | 🌐 TypeScript | 📅 2026-08-12 适用于 Windows 的终端工具
* <https://github.com/BurntSushi/ripgrep> ⭐ 67,311 | 🐛 176 | 🌐 Rust | 📅 2026-08-04 面向行的搜索工具（速度更快）
* <https://github.com/warpdotdev/Warp> ⭐ 64,239 | 🐛 5,000 | 🌐 Rust | 📅 2026-08-15 适用于 Mac 的终端工具
* <https://github.com/zellij-org/zellij> ⭐ 34,917 | 🐛 1,862 | 🌐 Rust | 📅 2026-08-13 终端复用器
* <https://github.com/chrisant996/clink> ⭐ 5,434 | 🐛 1 | 🌐 C++ | 📅 2026-08-15 cmd.exe 命令行增强工具
* <https://github.com/hanslub42/rlwrap> ⭐ 3,126 | 🐛 19 | 🌐 C | 📅 2026-05-24 readline 包装器
* <https://github.com/tomnomnom/anew> ⭐ 1,653 | 🐛 9 | 🌐 Go | 📅 2024-01-12 向文件添加新行并跳过重复项的工具
* <https://github.com/tmux> 终端复用器
* Linux command line:
  * <https://github.com/jaywcjlove/linux-command> ⭐ 36,584 | 🐛 81 | 🌐 Markdown | 📅 2026-08-11 在线查询工具
  * <https://github.com/chenjiandongx/how> ⭐ 127 | 🐛 1 | 🌐 Python | 📅 2020-05-10 python 版本
  * <https://github.com/chenjiandongx/pls> ⭐ 84 | 🐛 3 | 🌐 Go | 📅 2021-06-16 go 版本
* <https://explainshell.com/> 解释 shell 命令含义

#### 代码美化 *Beautifier*

* <http://web.chacuo.net/formatsh>
* <https://beautifier.io/>
* <http://jsnice.org/>

#### 生成器 *Generator*

* reverse-shell-generator: <https://github.com/0dayCTF/reverse-shell-generator> ⭐ 4,036 | 🐛 25 | 🌐 JavaScript | 📅 2026-04-27
* File-Download-Generator: <https://github.com/r0eXpeR/File-Download-Generator> ⭐ 32 | 🐛 0 | 🌐 HTML | 📅 2021-03-30
* revshells: <https://www.revshells.com/>
* reverse-shell: <https://forum.ywhack.com/reverse-shell/>
* reverse-shell-generator: <https://tex2e.github.io/reverse-shell-generator/index.html>

### SQL 注入 *SQL Injection*

* <https://github.com/sqlmapproject/sqlmap> ⭐ 38,199 | 🐛 32 | 🌐 Python | 📅 2026-08-15
* <https://github.com/payloadbox/sql-injection-payload-list>

### 访问控制 *Access Control*

#### 403 绕过 *Bypass 40X errors*

* <https://github.com/lobuhi/byp4xx> ⭐ 1,882 | 🐛 6 | 🌐 Go | 📅 2023-07-03
* <https://github.com/devploit/nomore403> ⭐ 1,831 | 🐛 3 | 🌐 Go | 📅 2026-06-21
* <https://github.com/Dheerajmadhukar/4-ZERO-3> ⭐ 1,662 | 🐛 11 | 🌐 Shell | 📅 2022-06-06
* <https://github.com/yunemse48/403bypasser> ⭐ 957 | 🐛 17 | 🌐 Python | 📅 2026-01-13

### 跨站脚本 *XSS*

* XSS Chop: <https://xsschop.chaitin.cn/demo/>
* XSS/CSRF: <https://evilcos.me/lab/xssor/>

### 文件包含 *File Inclusion*

* <https://github.com/mzfr/liffy> ⭐ 979 | 🐛 1 | 🌐 Python | 📅 2026-05-19
* <https://github.com/hansmach1ne/lfimap> ⭐ 336 | 🐛 1 | 🌐 Python | 📅 2024-12-31

### 服务端请求伪造 *SSRF*

* <https://github.com/tarunkant/Gopherus> ⭐ 3,407 | 🐛 11 | 🌐 Python | 📅 2023-04-18 适用于 py2 的 Gopherus 工具
* <https://github.com/Esonhugh/Gopherus3> ⭐ 89 | 🐛 1 | 🌐 Python | 📅 2026-07-31 适用于 py3 的 Gopherus 工具
* <https://portswigger.net/web-security/ssrf/url-validation-bypass-cheat-sheet>

### 移动端安全 *Mobile Security*

#### 小程序 *Mini Program*

* <https://github.com/wux1an/wxapkg> ⭐ 3,975 | 🐛 9 | 🌐 Vue | 📅 2026-04-28
* ~~\[wxappUnpacker: <https://github.com/xuedingmiaojun/wxappUnpacker> ⭐ 2,430 | 🐛 39 | 📅 2023-04-08]~~
* <https://github.com/eeeeeeeeee-code/e0e1-wx> ⭐ 2,207 | 🐛 10 | 🌐 Python | 📅 2026-05-26
* <https://github.com/Cherrison/CrackMinApp> ⭐ 1,343 | 🐛 25 | 🌐 JavaScript | 📅 2020-04-21
* <https://github.com/mrknow001/API-Explorer> ⭐ 793 | 🐛 6 | 🌐 Python | 📅 2024-10-15 ak/sk 获取工具

#### 应用程序 *APK*

* <https://github.com/iBotPeaches/Apktool> ⭐ 25,294 | 🐛 76 | 🌐 Java | 📅 2026-08-11
* <https://github.com/kelvinBen/AppInfoScanner> ⭐ 3,552 | 🐛 28 | 🌐 Python | 📅 2022-12-18

#### SessionKey 解密 *SessionKey*

* <https://github.com/mrknow001/wx_sessionkey_decrypt> ⭐ 187 | 🐛 2 | 🌐 Python | 📅 2023-02-10

### 载荷与绕过 *Payload and Bypass*

* PayloadsAllTheThings: <https://github.com/swisskyrepo/PayloadsAllTheThings> ⭐ 80,073 | 🐛 34 | 🌐 Python | 📅 2026-08-09
* CVE-2021-44228-PoC-log4j-bypass-words: <https://github.com/Puliczek/CVE-2021-44228-PoC-log4j-bypass-words> ⭐ 950 | 🐛 1 | 🌐 Java | 📅 2022-01-15
* PHPFuck: <https://github.com/splitline/PHPFuck> ⭐ 439 | 🐛 4 | 🌐 Python | 📅 2021-02-05
* IP to Decimal: <https://www.browserling.com/tools/ip-to-dec> IP 转十进制（127.0.0.1 >>> 2130706433）
* java.lang.Runtime.exec() Payload: <https://payloads.net/Runtime.exec/>
* JSFuck: <http://www.jsfuck.com/>
* JavaScript Deobfuscator and Unpacker: <https://lelinhtinh.github.io/de4js/> JavaScript 反混淆和解包工具

## 内网渗透 *Red Teaming and Offensive Security*

### 基础设施 *Infrastructure*

* rocketchat: <https://github.com/RocketChat/Rocket.Chat> ⭐ 45,986 | 🐛 3,965 | 🌐 TypeScript | 📅 2026-08-15
* mattermost: <https://github.com/mattermost/mattermost> ⭐ 38,812 | 🐛 983 | 🌐 TypeScript | 📅 2026-08-15
* cloudreve: <https://github.com/cloudreve/Cloudreve> ⭐ 28,555 | 🐛 151 | 🌐 Go | 📅 2026-08-02 支持多云的自建文件管理系统
* codimd: <https://github.com/hackmdio/codimd> ⭐ 10,132 | 🐛 351 | 🌐 JavaScript | 📅 2025-10-02
* hedgedoc: <https://github.com/hedgedoc/hedgedoc> ⭐ 7,371 | 🐛 270 | 🌐 TypeScript | 📅 2026-08-11
* updog: <https://github.com/sc0tfree/updog> ⭐ 3,390 | 🐛 13 | 🌐 Python | 📅 2025-11-16 通过 HTTP/S 上传下载文件
* f8x: <https://github.com/ffffffff0x/f8x> ⭐ 2,155 | 🐛 1 | 🌐 Shell | 📅 2026-07-25 红队/蓝队环境自动化部署工具
* openvpn-install: <https://github.com/hwdsl2/openvpn-install> ⭐ 1,722 | 🐛 0 | 🌐 Shell | 📅 2026-08-15 OpenVPN 服务器安装脚本

### 信息收集 *Reconnaissance*

* netspy: <https://github.com/shmilylty/netspy> ⭐ 2,237 | 🐛 8 | 🌐 Go | 📅 2023-07-25 内网网段探测
* smbmap: <https://github.com/ShawnDEvans/smbmap> ⭐ 2,061 | 🐛 32 | 🌐 Python | 📅 2026-01-06 SMB 枚举
* SharpHostInfo: <https://github.com/shmilylty/SharpHostInfo> ⭐ 635 | 🐛 5 | 🌐 C# | 📅 2022-12-15
* SharpHunter: <https://github.com/lintstar/SharpHunter> ⭐ 555 | 🐛 1 | 🌐 C# | 📅 2025-04-15 自动化主机信息搜集工具
* SharpScan: <https://github.com/INotGreen/SharpScan> ⭐ 479 | 🐛 5 | 🌐 C# | 📅 2024-11-20

### 凭证获取 *Credential Access*

#### 凭证转储 *Credential Dumping*

* regsecrets & dpapidump: <https://github.com/fortra/impacket/pull/1898> ⭐ 16,001 | 🐛 320 | 🌐 Python | 📅 2026-08-14 已在 Windows 11 和 Server 2022 测试无问题
* LaZagne: <https://github.com/AlessandroZ/LaZagne> ⭐ 10,959 | 🐛 17 | 🌐 Python | 📅 2025-09-18
* pypykatz: <https://github.com/skelsec/pypykatz> ⭐ 3,350 | 🐛 50 | 🌐 Python | 📅 2026-04-09 纯 Python 实现的 mimikatz
* lsassy: <https://github.com/login-securite/lsassy> ⭐ 2,210 | 🐛 2 | 🌐 Python | 📅 2026-03-23
* SharpDPAPI: <https://github.com/GhostPack/SharpDPAPI> ⭐ 1,446 | 🐛 13 | 🌐 C# | 📅 2024-06-27
* DonPAPI: <https://github.com/login-securite/DonPAPI> ⭐ 1,416 | 🐛 23 | 🌐 Python | 📅 2025-03-24
* Pillager: <https://github.com/qwqdanchun/Pillager/> ⭐ 1,292 | 🐛 4 | 🌐 C# | 📅 2024-09-07
* searchall: <https://github.com/Naturehi666/searchall> ⭐ 996 | 🐛 9 | 🌐 Go | 📅 2024-11-23
* PPLdump: <https://github.com/itm4n/PPLdump> ⚠️ Archived 受保护进程 LSASS 读取
* dploot: <https://github.com/zblurx/dploot> ⭐ 556 | 🐛 8 | 🌐 Python | 📅 2026-07-31 DPAPI
* WirelessKeyView: <https://www.nirsoft.net/utils/wireless_key.html>
* Windows credential manager: <https://www.nirsoft.net/utils/credentials_file_view.html>

#### 本地枚举 *Local Enumeration*

* HackBrowserData: <https://github.com/moonD4rk/HackBrowserData> ⭐ 14,422 | 🐛 31 | 🌐 Go | 📅 2026-08-07
* firefox: <https://github.com/unode/firefox_decrypt> ⭐ 2,470 | 🐛 3 | 🌐 Python | 📅 2026-02-23
* BrowserGhost: <https://github.com/QAX-A-Team/BrowserGhost> ⭐ 1,452 | 🐛 5 | 🌐 C# | 📅 2022-05-21
* sunflower: <https://github.com/wafinfo/Sunflower_get_Password> ⭐ 924 | 🐛 9 | 🌐 Python | 📅 2021-11-01
* navicat: <https://github.com/HyperSine/how-does-navicat-encrypt-password> ⭐ 641 | 🐛 3 | 🌐 C | 📅 2026-03-02
* mobaxterm: <https://github.com/HyperSine/how-does-MobaXterm-encrypt-password> ⭐ 352 | 🐛 6 | 🌐 Python | 📅 2022-10-12
* sundeskQ: sunflower & todesk <https://github.com/milu001/sundeskQ> ⭐ 338 | 🐛 4 | 📅 2024-10-29
* FindToDeskPass: <https://github.com/yangliukk/FindToDeskPass> ⭐ 242 | 🐛 0 | 📅 2024-09-09
* navicat: <https://github.com/Zhuoyuan1/navicat_password_decrypt> ⭐ 146 | 🐛 0 | 🌐 Java | 📅 2023-08-17
* securreCRT: <https://github.com/depau/shcrt> ⭐ 10 | 🐛 0 | 🌐 Shell | 📅 2021-05-01
* chrome: <http://www.nirsoft.net/utils/chromepass.html>
* foxmail: <https://securityxploded.com/foxmail-password-decryptor.php>
* xshell:
  * <https://github.com/JDArmy/SharpXDecrypt> ⭐ 947 | 🐛 4 | 🌐 C# | 📅 2023-06-08
  * <https://github.com/RowTeam/SharpDecryptPwd> ⭐ 837 | 🐛 3 | 🌐 C# | 📅 2022-03-04 本地解密
  * <https://github.com/HyperSine/how-does-Xmanager-encrypt-password> ⭐ 290 | 🐛 5 | 🌐 Python | 📅 2024-07-03 版本 < 7.0

#### 哈希破解 *NTLM Cracking*

* NetNTLMv1: <https://ntlmv1.com/> 在线破解
* LM + NTLM hashes and corresponding plaintext passwords:
  * <https://openwall.info/wiki/_media/john/pw-fake-nt.gz> 3107
  * <https://openwall.info/wiki/_media/john/pw-fake-nt100k.gz> 100k

### 后渗透 *Post Exploitation*

#### 综合工具 *Nice Tools*

* <https://github.com/rapid7/metasploit-framework> ⭐ 38,812 | 🐛 611 | 🌐 Ruby | 📅 2026-08-13
* <https://github.com/fortra/impacket> ⭐ 16,001 | 🐛 320 | 🌐 Python | 📅 2026-08-14 👍
* <https://github.com/PowerShellMafia/PowerSploit> ⚠️ Archived
* <https://github.com/samratashok/nishang> ⭐ 10,055 | 🐛 22 | 🌐 PowerShell | 📅 2024-04-25 PowerShell 专用
* <https://github.com/byt3bl33d3r/CrackMapExec> ⚠️ Archived 👍
* <https://github.com/Pennyw0rth/NetExec> ⭐ 5,784 | 🐛 166 | 🌐 Python | 📅 2026-08-13
* <https://github.com/k8gege/Ladon> ⭐ 5,320 | 🐛 44 | 🌐 C# | 📅 2025-03-24
* <https://github.com/GhostPack/Rubeus> ⭐ 5,129 | 🐛 48 | 🌐 C# | 📅 2026-05-21
* <https://github.com/Kevin-Robertson/Powermad> ⭐ 1,499 | 🐛 7 | 🌐 PowerShell | 📅 2023-01-11
* <https://github.com/XiaoliChan/wmiexec-Pro> ⭐ 1,295 | 🐛 1 | 🌐 Python | 📅 2026-04-26 基于 wmiexec.py 的免杀执行
* <https://github.com/ghost-ng/slinger> ⭐ 60 | 🐛 0 | 🌐 Python | 📅 2026-08-15 轻量级 impacket 命令行工具，单会话整合多种实用功能
* <https://docs.microsoft.com/en-us/sysinternals/downloads/pstools>
* Cobaltstrike Extensions:
  * Awesome CobaltStrike: <https://github.com/zer0yu/Awesome-CobaltStrike> ⭐ 4,432 | 🐛 1 | 📅 2023-09-20
  * Erebus: <https://github.com/DeEpinGh0st/Erebus> ⭐ 1,568 | 🐛 8 | 🌐 PowerShell | 📅 2021-10-28
  * pystinger: <https://github.com/FunnyWolf/pystinger> ⭐ 1,426 | 🐛 4 | 🌐 Python | 📅 2021-09-29
  * LSTAR: <https://github.com/lintstar/LSTAR> ⭐ 1,266 | 🐛 5 | 🌐 PowerShell | 📅 2022-01-30
  * ElevateKit: <https://github.com/rsmudge/ElevateKit> ⭐ 931 | 🐛 0 | 🌐 PowerShell | 📅 2020-06-22
  * C2ReverseProxy: <https://github.com/Daybr4ak/C2ReverseProxy> ⭐ 492 | 🐛 1 | 🌐 Go | 📅 2023-04-26

#### 二进制库 *Binaries and Libraries*

* GTFOBins: <https://github.com/GTFOBins/GTFOBins.github.io> ⭐ 13,546 | 🐛 27 | 🌐 YAML | 📅 2026-05-27 Unix 二进制利用
* LOLBAS: <https://github.com/LOLBAS-Project/LOLBAS-Project.github.io> ⭐ 89 | 🐛 1 | 🌐 JavaScript | 📅 2026-07-31 Windows 自带二进制与脚本

### 权限维持 *Persistence*

#### 内存马 *MemShell*

* <https://github.com/tennc/webshell> ⭐ 10,769 | 🐛 0 | 🌐 PHP | 📅 2024-12-24
* <https://github.com/pen4uin/java-memshell-generator> ⭐ 2,229 | 🐛 12 | 🌐 Java | 📅 2025-08-21 👍
* <https://github.com/ReaJason/MemShellParty> ⭐ 1,576 | 🐛 21 | 🌐 Java | 📅 2026-08-08
* <https://github.com/veo/wsMemShell> ⭐ 1,491 | 🐛 0 | 🌐 Java | 📅 2023-04-10
* <https://github.com/ce-automne/TomcatMemShell> ⭐ 519 | 🐛 1 | 🌐 Java | 📅 2022-08-31
* <https://github.com/BeichenDream/GodzillaMemoryShellProject> ⭐ 314 | 🐛 0 | 🌐 Java | 📅 2025-02-27
* <https://github.com/novysodope/RMI_Inj_MemShell> ⭐ 256 | 🐛 3 | 🌐 Java | 📅 2023-07-12
* <https://github.com/1ucky7/jmg-for-Godzilla> ⭐ 245 | 🐛 1 | 📅 2024-06-06
* <https://github.com/X1r0z/Godzilla-Suo5MemShell>

#### Webshell 管理 *Webshell Management*

* <https://github.com/rebeyond/Behinder> ⭐ 6,188 | 🐛 179 | 📅 2023-08-24
* <https://github.com/BeichenDream/Godzilla> ⭐ 4,453 | 🐛 47 | 📅 2024-07-17
* <https://github.com/shack2/skyscorpion> ⭐ 385 | 🐛 2 | 📅 2021-03-22

#### Webshell 免杀 *Webshell Bypass*

* <https://github.com/AabyssZG/WebShell-Bypass-Guide> ⭐ 1,841 | 🐛 0 | 📅 2025-05-24
* <https://github.com/cseroad/Webshell_Generate> ⭐ 1,318 | 🐛 5 | 📅 2026-01-08
* <http://bypass.tidesec.com/web/>

#### 反弹 Shell 管理 *Reverse Shell Management*

* <https://github.com/calebstewart/pwncat> ⭐ 2,914 | 🐛 68 | 🌐 Python | 📅 2024-08-09 Python 3.9+
* <https://github.com/WangYihang/Platypus> ⭐ 1,653 | 🐛 89 | 🌐 Go | 📅 2026-07-10

### 权限提升 *Privilege Escalation*

#### Linux 本地枚举 *Linux Local Enumeration*

* <https://github.com/carlospolop/privilege-escalation-awesome-scripts-suite> ⭐ 20,326 | 🐛 0 | 🌐 C# | 📅 2026-08-14
* <https://github.com/carlospolop/PEASS-ng/releases/latest/download/linpeas.sh> ⭐ 20,326 | 🐛 0 | 🌐 C# | 📅 2026-08-14
* <https://github.com/rebootuser/LinEnum> ⭐ 8,002 | 🐛 25 | 🌐 Shell | 📅 2023-09-06
* <https://github.com/DominicBreuker/pspy> ⭐ 6,150 | 🐛 3 | 🌐 Go | 📅 2026-03-01 无 root 监控 Linux 进程
* <https://github.com/mostaphabahadou/postenum> ⭐ 295 | 🐛 0 | 🌐 Shell | 📅 2026-01-05

#### Windows 本地枚举 *Windows Local Enumeration*

* <https://github.com/carlospolop/PEASS-ng/blob/master/winPEAS/winPEASbat/winPEAS.bat> ⭐ 20,326 | 🐛 0 | 🌐 C# | 📅 2026-08-14
* <https://github.com/PowerShellMafia/PowerSploit/blob/dev/Recon/PowerView.ps1> ⚠️ Archived
* <https://github.com/S3cur3Th1sSh1t/WinPwn> ⭐ 3,690 | 🐛 3 | 🌐 PowerShell | 📅 2025-08-28
* <https://github.com/dafthack/MailSniper> ⭐ 3,270 | 🐛 21 | 🌐 PowerShell | 📅 2025-08-07
* <https://github.com/Flangvik/SharpCollection> ⭐ 2,958 | 🐛 2 | 📅 2026-07-30
* <https://github.com/dafthack/DomainPasswordSpray> ⭐ 2,080 | 🐛 23 | 🌐 PowerShell | 📅 2024-07-11
* <https://github.com/S3cur3Th1sSh1t/PowerSharpPack> ⭐ 1,705 | 🐛 0 | 🌐 PowerShell | 📅 2025-04-14

#### Windows 提权 *Windows Exploits*

* <https://github.com/peass-ng/PEASS-ng/blob/master/winPEAS/winPEASexe/README.md> ⭐ 20,326 | 🐛 0 | 🌐 C# | 📅 2026-08-14
* <https://github.com/SecWiki/windows-kernel-exploits> ⭐ 8,716 | 🐛 10 | 🌐 C | 📅 2021-06-11
* <https://github.com/bitsadmin/wesng> ⭐ 4,918 | 🐛 10 | 🌐 Python | 📅 2026-08-14
* <https://github.com/AonCyberLabs/Windows-Exploit-Suggester> ⚠️ Archived
* <https://github.com/itm4n/PrivescCheck> ⭐ 3,910 | 🐛 2 | 🌐 PowerShell | 📅 2026-07-15
* <https://github.com/gtworek/PSBits/blob/master/Misc/EnableSeBackupPrivilege.ps1> ⭐ 3,520 | 🐛 0 | 🌐 C | 📅 2026-08-13
* <https://github.com/Ascotbe/Kernelhub> ⭐ 3,199 | 🐛 0 | 🌐 C | 📅 2023-02-15
* <https://github.com/BeichenDream/BadPotato/> ⭐ 902 | 🐛 4 | 🌐 C# | 📅 2020-05-10
* <https://github.com/Al1ex/WindowsElevation> ⭐ 669 | 🐛 0 | 🌐 C | 📅 2022-02-19
* <https://github.com/giuliano108/SeBackupPrivilege> ⭐ 465 | 🐛 2 | 🌐 C# | 📅 2013-07-29
* <https://i.hacking8.com/tiquan/> online

#### Linux 提权 *Linux Exploits*

* <https://github.com/peass-ng/PEASS-ng/tree/master/linPEAS> ⭐ 20,326 | 🐛 0 | 🌐 C# | 📅 2026-08-14
* <https://github.com/liamg/traitor> ⭐ 7,163 | 🐛 22 | 🌐 Go | 📅 2024-03-12
* <https://github.com/The-Z-Labs/linux-exploit-suggester> ⭐ 6,589 | 🐛 24 | 🌐 Shell | 📅 2026-03-20
* <https://github.com/InteliSecureLabs/Linux_Exploit_Suggester> ⭐ 1,814 | 🐛 4 | 🌐 Perl | 📅 2014-05-19

#### 数据库提权 *Database Exploits*

* <https://github.com/Hel10-Web/Databasetools> ⭐ 867 | 🐛 12 | 🌐 Go | 📅 2023-08-30

### 防御规避 *Defense Evasion*

#### Linux 防御规避 *Linux Defense Evasion*

* libprocesshider: <https://github.com/gianlucaborello/libprocesshider> ⭐ 1,132 | 🐛 11 | 🌐 C | 📅 2019-08-02 使用 ld 预加载隐藏 Linux 进程
* Linux Kernel Hacking: <https://github.com/xcellerator/linux_kernel_hacking> ⭐ 770 | 🐛 10 | 🌐 C | 📅 2024-04-10
* tasklist /svc && ps -aux: <https://tasklist.ffffffff0x.com/>

#### Windows 防御规避 *Windows Defense Evasion*

* BypassAntiVirus: <https://github.com/TideSec/BypassAntiVirus> ⭐ 5,119 | 🐛 1 | 🌐 XSLT | 📅 2024-09-14
* hoaxshell: <https://github.com/t3l3machus/hoaxshell> ⭐ 3,482 | 🐛 20 | 🌐 Python | 📅 2025-01-19
* AV\_Evasion\_Tool: <https://github.com/1y0n/AV_Evasion_Tool> ⭐ 2,760 | 🐛 31 | 🌐 C# | 📅 2025-08-18
* shellcodeloader: <https://github.com/knownsec/shellcodeloader> ⭐ 1,747 | 🐛 11 | 🌐 C++ | 📅 2020-12-11
* yetAnotherObfuscator: <https://github.com/0xb11a1/yetAnotherObfuscator> ⭐ 826 | 🐛 6 | 🌐 C# | 📅 2023-06-04
* GolangBypassAV: <https://github.com/safe6Sec/GolangBypassAV> ⭐ 814 | 🐛 6 | 🌐 Go | 📅 2022-04-11
* bypassAV: <https://github.com/pureqh/bypassAV> ⭐ 453 | 🐛 1 | 🌐 Python | 📅 2021-05-18
* rpeloader: <https://github.com/Teach2Breach/rpeloader> ⭐ 30 | 🐛 0 | 🌐 Rust | 📅 2025-01-23 在没有安装的情况下在 Windows 上使用 Python
* tasklist/systeminfo: <https://www.shentoushi.top/av/av.php>

### 内网穿透 *Proxy*

#### 代理客户端 *Proxy Client*

* Proxifier: <https://www.proxifier.com/>
* Proxychains: <https://github.com/haad/proxychains> ⭐ 7,930 | 🐛 16 | 🌐 C | 📅 2024-06-08

#### 代理工具 *Proxy Tools*

* frp: <https://github.com/fatedier/frp> ⭐ 108,809 | 🐛 52 | 🌐 Go | 📅 2026-08-14
* nps: <https://github.com/ehang-io/nps> ⭐ 34,162 | 🐛 525 | 🌐 Go | 📅 2024-05-30
* gost: <https://github.com/ginuerzh/gost> ⭐ 18,172 | 🐛 291 | 🌐 Go | 📅 2024-12-31
* Viper: <https://github.com/FunnyWolf/Viper> ⭐ 5,260 | 🐛 6 | 📅 2026-05-31
* ligolo-ng: <https://github.com/nicocha30/ligolo-ng> ⭐ 4,846 | 🐛 17 | 🌐 Go | 📅 2026-08-11 TUN 接口
* Stowaway: <https://github.com/ph4ntonn/Stowaway> ⭐ 3,411 | 🐛 6 | 🌐 Go | 📅 2026-03-03
* Neo-reGeorg: <https://github.com/L-codes/Neo-reGeorg> ⭐ 3,394 | 🐛 8 | 🌐 Python | 📅 2026-08-14
* reGeorg: <https://github.com/sensepost/reGeorg> ⭐ 3,182 | 🐛 20 | 🌐 Python | 📅 2025-03-06
* suo5: <https://github.com/zema1/suo5> ⭐ 2,791 | 🐛 2 | 🌐 Go | 📅 2026-07-14
* rakshasa: <https://github.com/Mob2003/rakshasa> ⭐ 1,057 | 🐛 7 | 🌐 Go | 📅 2023-04-23
* frpModify: <https://github.com/uknowsec/frpModify> ⭐ 399 | 🐛 5 | 📅 2020-12-31

#### DNS 隧道 *DNS Tunnel*

* iodine: <https://github.com/yarrick/iodine> ⭐ 7,944 | 🐛 21 | 🌐 C | 📅 2025-09-04
* dnscat2: <https://github.com/iagox86/dnscat2> ⭐ 3,952 | 🐛 98 | 🌐 PHP | 📅 2024-03-14
* DNS-Shell: <https://github.com/sensepost/DNS-Shell> ⭐ 531 | 🐛 2 | 🌐 Python | 📅 2020-10-11

#### ICMP 隧道 *ICMP Tunnel*

* icmpsh: <https://github.com/bdamele/icmpsh> ⭐ 1,624 | 🐛 10 | 🌐 C | 📅 2018-04-06

#### 端口转发 *Port Forwarding*

* tcptunnel: <https://github.com/vakuum/tcptunnel> ⭐ 381 | 🐛 4 | 🌐 C | 📅 2022-07-04 内网 → dmz → 攻击机

### 操作安全 *Operation Security*

* <https://privacy.sexy/> 在 Windows、macOS、Linux 上强化隐私与安全最佳实践
* <https://transfer.sh/> 匿名文件传输
* <https://a.f8x.io/> 短链接服务

## 域渗透 *Active Directory Penetration*

### 域内信息收集 *Collection and Discovery*

* <https://github.com/wh0amitz/SharpADWS> ⭐ 602 | 🐛 2 | 🌐 C# | 📅 2024-03-19 基于 Active Directory Web Services (ADWS) 协议
* <https://github.com/lzzbb/Adinfo> ⭐ 418 | 🐛 0 | 🌐 Go | 📅 2022-09-16
* BloodHound:
  * <https://github.com/SpecterOps/BloodHound-Legacy/blob/master/Collectors/SharpHound.ps1> ⭐ 10,606 | 🐛 93 | 🌐 PowerShell | 📅 2026-03-02
  * <https://github.com/SpecterOps/BloodHound> ⭐ 3,312 | 🐛 127 | 🌐 Go | 📅 2026-08-15
  * <https://github.com/dirkjanm/BloodHound.py> ⭐ 2,431 | 🐛 32 | 🌐 Python | 📅 2025-10-24
  * <https://github.com/AD-Security/AD_Miner> ⭐ 1,558 | 🐛 10 | 🌐 JavaScript | 📅 2026-03-18
  * <https://github.com/BloodHoundAD/SharpHound> ⭐ 1,327 | 🐛 38 | 🌐 C# | 📅 2026-08-11
  * <https://github.com/NH-RED-TEAM/RustHound> ⭐ 1,167 | 🐛 9 | 🌐 Rust | 📅 2024-10-21
  * <https://github.com/FalconForceTeam/SOAPHound> ⭐ 895 | 🐛 6 | 🌐 C# | 📅 2024-02-03
  * <https://github.com/CompassSecurity/BloodHoundQueries> ⚠️ Archived
* LDAP:
  * <https://github.com/dirkjanm/ldapdomaindump> ⭐ 1,423 | 🐛 27 | 🌐 Python | 📅 2025-04-06
  * <https://github.com/franc-pentest/ldeep> ⭐ 601 | 🐛 1 | 🌐 Python | 📅 2026-06-24
  * <https://github.com/yaap7/ldapsearch-ad> ⭐ 338 | 🐛 0 | 🌐 Python | 📅 2024-12-10
* DNS:
  * <https://github.com/dirkjanm/adidnsdump> ⭐ 1,177 | 🐛 4 | 🌐 Python | 📅 2025-04-04
* SCCM:
  * <https://github.com/garrettfoster13/sccmhunter> ⭐ 937 | 🐛 6 | 🌐 Python | 📅 2026-06-25
  * <https://github.com/Mayyhem/SharpSCCM> ⭐ 702 | 🐛 6 | 🌐 C# | 📅 2026-03-30
* Brute force users:
  * <https://github.com/ropnop/kerbrute> ⭐ 3,418 | 🐛 44 | 🌐 Go | 📅 2024-08-20

### 域内权限提升 *Privilege Escalation*

* <https://github.com/CravateRouge/bloodyAD> ⭐ 2,263 | 🐛 4 | 🌐 Python | 📅 2026-08-05

### 域内漏洞利用 *Known Exploited Vulnerabilities*

#### MS14-068

* <https://github.com/fortra/impacket/blob/master/examples/goldenPac.py> ⭐ 16,001 | 🐛 320 | 🌐 Python | 📅 2026-08-14
* <https://github.com/SecWiki/windows-kernel-exploits/blob/master/MS14-068/pykek/ms14-068.py> ⭐ 8,716 | 🐛 10 | 🌐 C | 📅 2021-06-11
* <https://github.com/SpiderLabs/Responder/blob/master/tools/FindSMB2UPTime.py> ⚠️ Archived

#### noPac

> CVE-2021-42278/CVE-2021-42287

* <https://github.com/Ridter/noPac> ⭐ 1,020 | 🐛 7 | 🌐 Python | 📅 2023-01-29
* <https://github.com/Amulab/advul> ⭐ 75 | 🐛 0 | 🌐 Python | 📅 2023-12-21

#### Zerologon

> CVE-2020-1472

* <https://github.com/SecuraBV/CVE-2020-1472/blob/master/zerologon_tester.py> ⭐ 1,827 | 🐛 9 | 🌐 Python | 📅 2025-06-27
* <https://github.com/dirkjanm/CVE-2020-1472> ⭐ 1,316 | 🐛 1 | 🌐 Python | 📅 2020-11-03
* <https://github.com/risksense/zerologon> ⭐ 705 | 🐛 7 | 🌐 Python | 📅 2020-10-15
* <https://github.com/XiaoliChan/zerologon-Shot> ⭐ 146 | 🐛 0 | 🌐 Python | 📅 2024-03-15
* <https://github.com/Potato-py/Potato/tree/03c3551e4770db440b27b0a48fc02b0a38a1cf04/exp/cve/CVE-2020-1472> ⭐ 100 | 🐛 0 | 🌐 Python | 📅 2021-12-22
* <https://github.com/StarfireLab/AutoZerologon> ⭐ 100 | 🐛 0 | 🌐 Python | 📅 2023-09-20

#### ProxyLogon/ProxyShell

> CVE-2021-34473

* <https://github.com/dirkjanm/privexchange/> ⭐ 1,076 | 🐛 2 | 🌐 Python | 📅 2020-01-23
* <https://github.com/dmaasland/proxyshell-poc/blob/main/proxyshell_rce.py> ⚠️ Archived
* <https://github.com/hausec/ProxyLogon> ⭐ 298 | 🐛 0 | 🌐 Python | 📅 2024-07-02
* <https://github.com/Jumbo-WJB/PTH_Exchange> ⭐ 77 | 🐛 1 | 🌐 Python | 📅 2021-10-21

#### ProxyNotShell

> CVE-2022-41040/CVE-2022-41082

* <https://github.com/testanull/ProxyNotShell-PoC> ⭐ 412 | 🐛 3 | 🌐 Python | 📅 2022-11-18

#### Printnightmare

> CVE-2021-34527/CVE-2021-1675

* <https://github.com/cube0x0/CVE-2021-1675> ⭐ 1,999 | 🐛 38 | 🌐 C# | 📅 2021-07-20
* <https://github.com/calebstewart/CVE-2021-1675> ⭐ 1,104 | 🐛 7 | 🌐 PowerShell | 📅 2021-07-05
* <https://github.com/nemo-wq/PrintNightmare-CVE-2021-34527> ⭐ 175 | 🐛 0 | 🌐 C | 📅 2021-09-13

### 域内渗透方式 *Methodology*

#### Coerce and Relay

* ntlmrelayx: <https://github.com/fortra/impacket/blob/master/examples/ntlmrelayx.py> ⭐ 16,001 | 🐛 320 | 🌐 Python | 📅 2026-08-14
* Responder: <https://github.com/lgandx/Responder> ⭐ 6,541 | 🐛 29 | 🌐 Python | 📅 2026-06-10
* Coercer: <https://github.com/p0dalirius/Coercer> ⭐ 2,305 | 🐛 9 | 🌐 Python | 📅 2026-04-24
* PetitPotam: <https://github.com/topotam/PetitPotam> ⭐ 2,263 | 🐛 0 | 🌐 C | 📅 2024-08-15
* KrbRelayUp: <https://github.com/Dec0ne/KrbRelayUp> ⭐ 1,655 | 🐛 18 | 🌐 C# | 📅 2022-08-06
* kerbrelayx: <https://github.com/dirkjanm/krbrelayx> ⭐ 1,652 | 🐛 19 | 🌐 Python | 📅 2026-03-11
* PrinterBug: <https://github.com/leechristensen/SpoolSample> ⭐ 1,139 | 🐛 0 | 🌐 C# | 📅 2024-05-29
* PrivExchange: <https://github.com/dirkjanm/privexchange/> ⭐ 1,076 | 🐛 2 | 🌐 Python | 📅 2020-01-23
* DFSCoerce: <https://github.com/Wh04m1001/DFSCoerce> ⭐ 846 | 🐛 4 | 🌐 Python | 📅 2022-09-09
* Responder-Windows: <https://github.com/lgandx/Responder-Windows> ⭐ 574 | 🐛 6 | 🌐 Python | 📅 2024-07-30
* WSPCoerce: <https://github.com/slemire/WSPCoerce> ⭐ 306 | 🐛 0 | 🌐 C# | 📅 2023-09-07
* ShadowCoerce: <https://github.com/ShutdownRepo/ShadowCoerce> ⭐ 304 | 🐛 0 | 🌐 Python | 📅 2021-12-30
* cannon: <https://github.com/Amulab/cannon> ⭐ 12 | 🐛 0 | 🌐 Python | 📅 2023-07-21

#### Delegation

* findDelegation: <https://github.com/fortra/impacket/blob/master/examples/findDelegation.py> ⭐ 16,001 | 🐛 320 | 🌐 Python | 📅 2026-08-14
* Impacket rbcd.py: <https://github.com/fortra/impacket/blob/master/examples/rbcd.py> ⭐ 16,001 | 🐛 320 | 🌐 Python | 📅 2026-08-14
* PowerView: <https://github.com/PowerShellMafia/PowerSploit/blob/dev/Recon/PowerView.ps1> ⚠️ Archived
* Delegations: <https://github.com/TheManticoreProject/Delegations> ⭐ 222 | 🐛 0 | 🌐 Go | 📅 2026-07-08
* SharpRBCD: <https://github.com/Kryp7os/SharpRBCD> ⭐ 50 | 🐛 0 | 🌐 C# | 📅 2025-03-10

#### ADCS

> Active Directory Certificate Services

* PassTheCert: <https://github.com/AlmondOffSec/PassTheCert> ⭐ 769 | 🐛 1 | 🌐 C# | 📅 2025-09-03
* Active Directory Certificate Services(AD CS) 枚举与利用:
  * Certipy: <https://github.com/ly4k/Certipy> ⭐ 3,628 | 🐛 23 | 🌐 Python | 📅 2026-07-30
  * Certify: <https://github.com/GhostPack/Certify> ⭐ 2,020 | 🐛 0 | 🌐 C# | 📅 2026-08-12
  * PKINITtools: <https://github.com/dirkjanm/PKINITtools> ⭐ 924 | 🐛 6 | 🌐 Python | 📅 2025-01-03
  * ADCSPwn: <https://github.com/bats3c/ADCSPwn> ⭐ 878 | 🐛 2 | 🌐 C# | 📅 2023-03-20
  * certi: <https://github.com/zer1t0/certi> ⭐ 324 | 🐛 4 | 🌐 Python | 📅 2023-02-06

#### ACLs and ACEs

* <https://github.com/ShutdownRepo/pywhisker> ⭐ 924 | 🐛 3 | 🌐 Python | 📅 2026-06-17
* <https://github.com/ShutdownRepo/targetedKerberoast> ⭐ 677 | 🐛 4 | 🌐 Python | 📅 2024-12-16
* <https://github.com/n00py/DCSync> ⭐ 118 | 🐛 0 | 🌐 Python | 📅 2022-05-02

## 防御性安全 *Blue Teaming and Defensive Security*

### 内存马查杀 *Memshell Detection*

* <https://github.com/alibaba/arthas> ⭐ 37,486 | 🐛 490 | 🌐 Java | 📅 2026-08-14
* <https://github.com/c0ny1/java-memshell-scanner> ⭐ 1,010 | 🐛 7 | 🌐 Java | 📅 2023-03-09
* <https://github.com/LandGrey/copagent> ⭐ 503 | 🐛 1 | 🌐 Java | 📅 2021-05-17
* <https://github.com/yzddmr6/ASP.NET-Memshell-Scanner> ⭐ 285 | 🐛 3 | 🌐 JavaScript | 📅 2023-08-22

### Webshell 查杀 *Webshell Detection*

* <https://webshellchop.chaitin.cn/demo/>
* <http://www.shellpub.com>
* <https://github.com/jvoisin/php-malware-finder> ⚠️ Archived
* <https://www.d99net.net/>

### 攻击研判 *Blue Teaming*

* BlueTeamTools: <https://github.com/abc123info/BlueTeamTools> ⭐ 1,853 | 🐛 25 | 📅 2026-07-25
* CobaltStrike Decrypt: <https://github.com/5ime/CS_Decrypt> ⭐ 39 | 🐛 1 | 🌐 Python | 📅 2023-10-02
* IP Logger: <https://iplogger.org/> 记录并追踪 IP 地址

### 基线加固 *Enforcement*

* <https://github.com/xiaoyunjie/Shell_Script> ⭐ 461 | 🐛 0 | 🌐 Shell | 📅 2022-08-08
* <https://github.com/AV1080p/Benchmarks>

### 应急响应 *Incident Response*

* <https://github.com/grayddq/GScan> ⭐ 2,821 | 🐛 15 | 🌐 Python | 📅 2022-08-07
* <https://github.com/al0ne/LinuxCheck> ⭐ 2,093 | 🐛 1 | 🌐 Shell | 📅 2024-06-19
* <https://github.com/T0xst/linux> ⭐ 474 | 🐛 6 | 🌐 Shell | 📅 2025-04-22
* <https://github.com/ppabc/security_check> ⭐ 182 | 🐛 0 | 🌐 Shell | 📅 2017-01-24

### 勒索病毒 *Ransomware*

#### 搜索引擎 *Search Engine*

* 360: <http://lesuobingdu.360.cn>
* 腾讯: <https://guanjia.qq.com/pr/ls>
* 启明星辰: <https://lesuo.venuseye.com.cn>
* 奇安信: <https://lesuobingdu.qianxin.com>
* 深信服: <https://edr.sangfor.com.cn/#/information/ransom_search>

#### 解密工具 *Decryption Tools*

* 腾讯: <https://habo.qq.com/tool>
* 金山毒霸: <http://www.duba.net/dbt/wannacry.html>
* 瑞星: <http://it.rising.com.cn/fanglesuo/index.html>
* 卡巴斯基: <https://noransom.kaspersky.com/>
* <https://www.nomoreransom.org/zh/index.html>
* <https://id-ransomware.malwarehunterteam.com>
* <https://www.avast.com/ransomware-decryption-tools>
* <https://www.emsisoft.com/en/ransomware-decryption/>
* <https://github.com/jiansiting/Decryption-Tools> ⭐ 957 | 🐛 2 | 📅 2023-11-30

### 开源蜜罐 *Open-Source Honeypot*

* awesome-honeypots: <https://github.com/paralax/awesome-honeypots> ⭐ 10,523 | 🐛 21 | 🌐 Python | 📅 2026-06-01 蜜罐资源汇总列表
* HFish: <https://github.com/hacklcx/HFish> ⭐ 4,532 | 🐛 70 | 📅 2026-03-13
* conpot: <https://github.com/mushorg/conpot> ⭐ 1,512 | 🐛 103 | 🌐 Python | 📅 2026-08-05 工业控制系统（ICS）专用蜜罐
* Ehoney: <https://github.com/seccome/Ehoney> ⭐ 1,270 | 🐛 40 | 🌐 Go | 📅 2023-10-17
* MysqlHoneypot: <https://github.com/qigpig/MysqlHoneypot> ⭐ 218 | 🐛 5 | 🌐 Python | 📅 2021-03-23 基于 MySQL 蜜罐获取微信号

### 逆向工程 *Reverse Engineering*

#### 综合工具 *Nice Tools*

* UPX: <https://github.com/upx/upx> ⭐ 17,781 | 🐛 26 | 🌐 C++ | 📅 2026-08-15
* IDA Pro MCP: <https://github.com/mrexodia/ida-pro-mcp> ⭐ 11,366 | 🐛 47 | 🌐 Python | 📅 2026-08-09 集成 AI 的 IDA Pro 工具
* Angr: <https://github.com/angr/angr> ⭐ 9,012 | 🐛 718 | 🌐 Python | 📅 2026-08-15 二进制分析平台
* OpenArk: <https://github.com/BlackINT3/OpenArk> 反 Rootkit 工具
* python arsenal for RE: <https://pythonarsenal.com/> 逆向工程工具集
* IDA Pro: <https://hex-rays.com/ida-pro/>
* Cutter: <https://cutter.re/> 开源逆向工程平台

#### 静态分析 *Static Analysis*

* Detect-It-Easy: <https://github.com/horsicq/Detect-It-Easy> ⭐ 11,356 | 🐛 33 | 🌐 JavaScript | 📅 2026-08-15
* checksec: <https://github.com/slimm609/checksec> ⭐ 2,363 | 🐛 3 | 🌐 Go | 📅 2026-08-04
* ExeinfoPE: <https://github.com/ExeinfoASL/ASL> ⭐ 1,136 | 🐛 8 | 📅 2026-08-08
* PEiD: <https://www.aldeid.com/wiki/PEiD>
* bindiff: <https://www.zynamics.com/software.html>
* 在线编译器: <https://godbolt.org/>

#### 动态调试 *Dynamic Analysis*

* Ollydbg: <https://www.ollydbg.de/>
* x64dbg: <https://x64dbg.com/>

#### Java

* jadx: <https://github.com/skylot/jadx> ⭐ 50,079 | 🐛 443 | 🌐 Java | 📅 2026-08-05
* jd-gui: <https://github.com/java-decompiler/jd-gui> ⭐ 15,174 | 🐛 248 | 🌐 Java | 📅 2024-07-08
* GDA: <https://github.com/charles2gan/GDA-android-reversing-Tool> ⭐ 4,805 | 🐛 63 | 🌐 Python | 📅 2026-04-10
* jar-analyzer: <https://github.com/jar-analyzer/jar-analyzer/> ⭐ 2,154 | 🐛 20 | 🌐 Java | 📅 2026-08-08
* JEB: <https://www.pnfsoftware.com/>

#### Mobile

* scrcpy: <https://github.com/Genymobile/scrcpy> ⭐ 147,704 | 🐛 2,879 | 🌐 C | 📅 2026-08-14
* android-reverse: <https://github.com/WuFengXue/android-reverse> ⭐ 1,979 | 🐛 0 | 📅 2025-04-27

#### Python

* pyinstaller: <https://github.com/pyinstaller/pyinstaller> ⭐ 13,066 | 🐛 289 | 🌐 Python | 📅 2026-08-15 py->exe
* pyinstxtractor: <https://github.com/extremecoders-re/pyinstxtractor> ⭐ 4,438 | 🐛 21 | 🌐 Python | 📅 2026-07-22 exe->pyc
* pycDcode: <https://github.com/rocky/python-uncompyle6/> ⭐ 4,317 | 🐛 42 | 🌐 Python | 📅 2026-04-24 pyc->py
* unpy2exe: <https://github.com/matiasb/unpy2exe> ⭐ 284 | 🐛 6 | 🌐 Python | 📅 2023-02-24 exe->pyc
* pycDcode: <https://github.com/BarakAharoni/pycDcode> ⭐ 41 | 🐛 3 | 🌐 Python | 📅 2026-05-11
* py2exe: <https://www.py2exe.org/> py->exe

#### Rust/Go/.NET

* <https://github.com/dnSpy/dnSpy> ⚠️ Archived for .NET
* <https://github.com/sibears/IDAGolangHelper> ⭐ 1,090 | 🐛 16 | 🌐 Python | 📅 2023-12-19 for golang
* <https://github.com/strazzere/golang_loader_assist> ⭐ 660 | 🐛 1 | 🌐 Python | 📅 2020-06-22 for golang
* <https://github.com/cha5126568/rust-reversing-helper> ⚠️ Archived for rust
* <https://www.jetbrains.com/zh-cn/decompiler/> for .NET

#### JavaScript

* <https://github.com/jxhczhl/JsRpc> ⭐ 2,343 | 🐛 26 | 🌐 Go | 📅 2026-06-08
* <https://github.com/0xsdeo/AntiDebug_Breaker> ⭐ 2,100 | 🐛 10 | 🌐 JavaScript | 📅 2026-06-16

## 云安全 *Cloud Security*

### 开源资源 *Resources*

* Awesome-CloudSec-Labs: <https://github.com/iknowjason/Awesome-CloudSec-Labs> ⭐ 2,176 | 🐛 5 | 📅 2025-10-01
* TeamsSix:
  * <https://github.com/teamssix/awesome-cloud-security> ⭐ 2,109 | 🐛 2 | 📅 2024-10-28
  * <https://wiki.teamssix.com/>
* lzCloudSecurity:
  * <https://github.com/EvilAnne/lzCloudSecurity> ⭐ 1,058 | 🐛 2 | 📅 2023-11-05
  * <https://lzcloudsecurity.gitbook.io/yun-an-quan-gong-fang-ru-men/>
* CSA Research: <https://c-csa.cn/research/results/>
* HackTricks Cloud: <https://cloud.hacktricks.xyz/>
* Aliyun OpenAPI: <https://next.api.aliyun.com/api/>
* Cloud Native Landscape: <https://landscape.cncf.io/>
* Cloud Vulnerabilities and Security Issues Database: <https://www.cloudvulndb.org/> 云漏洞与安全问题数据库

### 云安全矩阵 *Cloud Threat Matrix*

* <https://attack.mitre.org/matrices/enterprise/cloud/>
* <https://cloudsec.huoxian.cn/>
* <https://cloudsec.tencent.com/home/>
* <https://owasp.org/www-project-kubernetes-top-ten/> OWASP Kubernetes 十大风险 - 2022 版
* <https://www.microsoft.com/en-us/security/blog/2021/03/23/secure-containerized-environments-with-updated-threat-matrix-for-kubernetes/> Kubernetes 威胁矩阵

### 云服务 *Cloud Services*

> 三大云服务提供商：
> \- Amazon Web Services (AWS) / Microsoft Azure / Google Cloud Platform (GCP)
> \- 阿里云 / 腾讯云 / 华为云

#### 云管平台 *Management Tools*

* <https://github.com/aliyun/oss-browser> ⭐ 3,599 | 🐛 157 | 🌐 JavaScript | 📅 2024-07-26 基于阿里云 CLI 的图形化工具
* <https://github.com/aliyun/aliyun-cli> ⭐ 1,080 | 🐛 47 | 🌐 Go | 📅 2026-08-14 适用于阿里云 OSS
* <https://github.com/qiniu/kodo-browser> ⭐ 198 | 🐛 41 | 🌐 TypeScript | 📅 2024-11-25 适用于七牛云 OSS
* <https://github.com/TencentCloud/tencentcloud-cli> ⭐ 129 | 🐛 18 | 🌐 Python | 📅 2026-08-13 基于腾讯云 CLI
* <https://github.com/TencentCloud/cosbrowser> ⭐ 98 | 🐛 33 | 📅 2025-10-24 适用于腾讯云 COS
* <https://yun.cloudbility.com/> 云存储图形化管理平台
* <https://support.huaweicloud.com/browsertg-obs/obs_03_1003.html> 适用于华为云 OBS
* <https://www.ctyun.cn/document/10000101/10006768> 适用于天翼云 OBS
* <https://www.ctyun.cn/document/10306929/10132519> 适用于天翼云媒体服务
* <https://docsv4.qingcloud.com/user_guide/development_docs/cli/install/install/> 基于青云 CLI

#### AK/SK 利用 *AK/SK Exploit*

* <https://github.com/UzJu/Cloud-Bucket-Leak-Detection-Tools> ⭐ 1,266 | 🐛 9 | 🌐 Python | 📅 2025-03-28 云存储桶泄露检测工具
* <https://github.com/mrknow001/aliyun-accesskey-Tools> ⭐ 1,231 | 🐛 11 | 🌐 Python | 📅 2022-04-08 阿里云 AccessKey 专用工具
* <https://github.com/dark-kingA/cloudTools> ⭐ 1,167 | 🐛 13 | 📅 2026-02-26 支持三大云 + 优刻得的安全工具
* <https://github.com/iiiusky/alicloud-tools> ⭐ 880 | 🐛 2 | 🌐 Go | 📅 2023-03-02 阿里云安全工具集
* <https://github.com/wyzxxz/aksk_tool> ⭐ 789 | 🐛 10 | 📅 2025-02-13 支持三大云 + AWS/优刻得/京东云/百度云/七牛云
* <https://github.com/CloudExplorer-Dev/CloudExplorer-Lite> ⚠️ Archived fit2cloud 云资源管理工具
* <https://github.com/wgpsec/cloudsword> ⭐ 618 | 🐛 2 | 🌐 Go | 📅 2026-02-03 云服务安全测试工具
* <https://github.com/libaibaia/cloudSec> ⭐ 602 | 🐛 5 | 🌐 Java | 📅 2024-12-19 支持三大云 + AWS/七牛云的 Web 工具
* <https://github.com/NS-Sp4ce/AliyunAccessKeyTools> ⭐ 152 | 🐛 1 | 🌐 C# | 📅 2021-07-16 阿里云 AccessKey 利用工具
* <https://github.com/freeFV/Tencent_Yun_tools> ⭐ 37 | 🐛 0 | 📅 2021-12-26 腾讯云安全工具集
* <https://wiki.teamssix.com/cf/> 漏洞利用框架 v0.5.0（开源）

### 云原生 *Cloud Native*

#### 综合工具 *Nice Tools*

* <https://github.com/HummerRisk/HummerRisk> ⭐ 1,511 | 🐛 47 | 🌐 Java | 📅 2024-12-26 开源云原生安全平台

#### 容器 *Docker*

* <https://github.com/wagoodman/dive> ⭐ 54,453 | 🐛 209 | 🌐 Go | 📅 2025-12-15 探索 Docker 镜像各层结构
* <https://github.com/docker/docker-bench-security> ⭐ 9,687 | 🐛 29 | 🌐 Shell | 📅 2026-06-04 Docker 安全基准测试工具
* <https://github.com/cdk-team/CDK> ⭐ 4,731 | 🐛 15 | 🌐 Go | 📅 2026-05-01 容器渗透测试工具包
* <https://github.com/chaitin/veinmind-tools> ⭐ 1,651 | 🐛 24 | 🌐 Go | 📅 2024-01-10 容器安全工具集
* <https://github.com/eliasgranderubio/dagda/> ⭐ 1,248 | 🐛 25 | 🌐 Python | 📅 2023-05-23 Docker 镜像/容器静态分析工具（检测漏洞、木马、病毒等恶意威胁）
* <https://github.com/teamssix/container-escape-check> ⭐ 667 | 🐛 2 | 🌐 Shell | 📅 2022-04-19 容器逃逸检测工具
* <https://github.com/brant-ruan/awesome-container-escape> ⭐ 71 | 🐛 0 | 📅 2021-03-23 容器逃逸技术汇总

#### 集群 *Kubernetes*

* <https://github.com/etcd-io/etcd> ⭐ 52,127 | 🐛 310 | 🌐 Go | 📅 2026-08-15 分布式键值存储（K8s 核心组件）
* <https://github.com/derailed/k9s> ⭐ 34,358 | 🐛 111 | 🌐 Go | 📅 2026-08-14 Kubernetes 终端管理 CLI 工具
* <https://github.com/kubernetes/minikube> ⭐ 32,036 | 🐛 536 | 🌐 Go | 📅 2026-08-15 本地 Kubernetes 集群搭建工具
* <https://github.com/kubernetes-sigs/kind> ⭐ 15,420 | 🐛 239 | 🌐 Go | 📅 2026-08-11 基于 Docker 的本地 Kubernetes 集群工具
* <https://github.com/docker/docker-bench-security> ⭐ 9,687 | 🐛 29 | 🌐 Shell | 📅 2026-06-04 Docker CIS 基准测试分析工具
* <https://github.com/aquasecurity/kube-bench> ⭐ 8,141 | 🐛 94 | 🌐 Go | 📅 2026-08-10 Kubernetes CIS 基准测试分析工具
* <https://github.com/aquasecurity/kube-hunter> ⭐ 5,076 | 🐛 82 | 🌐 Python | 📅 2024-03-19 Kubernetes 安全弱点探测工具
* <https://github.com/kubernetes/kubeadm> ⭐ 3,994 | 🐛 39 | 🌐 Go | 📅 2026-08-09 生产/测试环境 Kubernetes 集群部署工具
* <https://github.com/kubernetes-sigs/cri-tools> ⭐ 2,006 | 🐛 17 | 🌐 Go | 📅 2026-08-14 Kubelet 容器运行时接口（CRI）工具集
* <https://github.com/inguardians/peirates> ⭐ 1,471 | 🐛 25 | 🌐 Go | 📅 2026-07-03 Kubernetes 渗透测试工具
* <https://github.com/DataDog/KubeHound> ⭐ 986 | 🐛 29 | 🌐 Go | 📅 2026-08-10 Kubernetes 攻击路径自动化分析工具
* <https://github.com/lightspin-tech/red-kube> ⭐ 828 | 🐛 4 | 🌐 Python | 📅 2021-05-28 基于 kubectl 的红队 K8s 对抗模拟工具
* <https://kubernetes.io/docs/tasks/tools/> Kubernetes 官方工具文档

## 提高生产力的使用姿势

### 如何快速使用 alias

Windows 创建 alias.bat，激活 conda 虚拟环境，在隔离环境下运行程序或工具。双击 alias.bat，重启 cmd，配置生效。

```
@echo off
:: Software
@DOSKEY ida64=activate base$t"D:\CTFTools\Cracking\IDA_7.7\ida64.exe"

:: Tools
@DOSKEY fscan=cd /d D:\Software\HackTools\fscan$tactivate security$tdir
```

将 alias.bat 配置为开机自启动：

* 注册表进入 `计算机\HKEY_CURRENT_USER\Software\Microsoft\Command Processor`；
* 创建字符串值 `autorun`，赋值为 alias.bat 所在位置，例如 `D: \Software\alias.bat`；
* 重启系统，配置生效。

MacOS 编辑 .zshrc，重启 shell，配置生效：

```
# 3. Control and Command
alias behinder="cd /Users/threekiii/HackTools/C2/Behinder_v4.1/ && /Library/Java/JavaVirtualMachines/jdk-1.8.jdk/Contents/Home/bin/java -jar Behinder.jar "
alias godzilla="cd /Users/threekiii/HackTools/C2/Godzilla_v4.0.1/ && /Library/Java/JavaVirtualMachines/jdk-1.8.jdk/Contents/Home/bin/java -jar godzilla.jar "
```

### 如何优化原生终端

Windows 通过 tabby + clink 优化原生终端，实现命令自动补全、vps ssh/ftp/sftp、输出日志记录等功能：

* tabby: <https://github.com/Eugeny/tabby> ⭐ 73,934 | 🐛 2,850 | 🌐 TypeScript | 📅 2026-08-12
* warp: <https://github.com/warpdotdev/Warp> ⭐ 64,239 | 🐛 5,000 | 🌐 Rust | 📅 2026-08-15 👍
* clink: <https://github.com/chrisant996/clink> ⭐ 5,434 | 🐛 1 | 🌐 C++ | 📅 2026-08-15

MacOS 通过 warp + ohmyzsh 优化原生终端，warp 自带命令自动补全，引入“块”概念，提供了更现代化的编程体验（Modern UX and Text Editing）：

* ohmyzsh: <https://github.com/ohmyzsh/ohmyzsh> ⭐ 189,213 | 🐛 592 | 🌐 Shell | 📅 2026-08-11
* warp: <https://github.com/warpdotdev/Warp> ⭐ 64,239 | 🐛 5,000 | 🌐 Rust | 📅 2026-08-15 👍

### 如何解决终端中文乱码

Windows 注册表进入 `计算机\HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Command Processor`，创建字符串值 `autorun`，赋值为 `chcp 65001`。

![Stargazers over time](https://starchart.cc/Threekiii/Awesome-Redteam.svg?background=%23FFFFFF\&axis=%23333333\&line=%23009307)

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-15._
