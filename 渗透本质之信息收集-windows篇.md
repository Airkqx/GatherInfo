# 信息广度收集: 
## Whois信息
+ 站长之家: http://whois.chinaz.com
+ Bugscaner: http://whois.bugscaner.com
+ 国外在线: https://bgp.he.net
## 一级域名
+ 企查查: https://www.qichacha.com
+ 天眼查: https://www.tianyancha.com
+ 爱企查: https://aiqicha.baidu.com
## 子域名
+ Amass: https://github.com/OWASP/Amass
+ OneForAll: https://github.com/shmilylty/OneForAll
+ ksubdomain: https://github.com/knownsec/ksubdomain
+ subDomainsBrute: https://github.com/lijiejie/subDomainsBrute
+ Sonar: https://omnisint.io/
+ 查子域: https://chaziyu.com/ (在线)
## 旁站
+ 在线: http://stool.chinaz.com/same
+ 在线: https://site.ip138.com
## 真实ip
+ 全球ping: https://www.wepcc.com
+ dns检测: https://tools.ipip.net/dns.php
+ Xcdn: https://github.com/3xp10it/xcdn
+ 在线: https://ipchaxun.com
## 端口+C段
+ Nmap: https://nmap.org
+ Fscan: https://github.com/shadow1ng/fscan
+ Txportmap: https://github.com/4dogs-cn/TXPortMap
+ Masscan: https://github.com/robertdavidgraham/masscan
## 敏感信息
### Googlehack语法
1. 后台地址
+ site:xxx.com intitle:管理|后台|登陆|管理员|系统|内部
+ site:xxx.com inurl:login|admin|system|guanli|denglu|manage|admin_login|auth|dev
2. 敏感文件
+ site:xxx.com (filetype:doc OR filetype:ppt OR filetype:pps OR filetype:xls OR filetype:docx OR filetype:pptx OR filetype:ppsx OR filetype:xlsx OR filetype:odt OR filetype:ods OR filetype:odg OR filetype:odp OR filetype:pdf OR filetype:wpd OR filetype:svg OR filetype:svgz OR filetype:indd OR filetype:rdp OR filetype:sql OR filetype:xml OR filetype:db OR filetype:mdb OR filetype:sqlite OR filetype:log OR filetype:conf)
3. 测试环境
+ site:xxx.com inurl:test|ceshi
+ site:xxx.com intitle:测试
4. 邮箱
+ site:xxx.com (intitle:"Outlook Web App" OR intitle:"邮件" OR inurl:"email" OR inurl:"webmail")
5. 其他
+ site:xxx.com inurl:api|uid=|id=|userid=|token|session
+ site:xxx.com intitle:index.of "server at"
### Github
+ @xxx.com password/secret/credentials/token/config/pass/login/ftp/ssh/pwd
+ @xxx.com security_credentials/connetionstring/JDBC/ssh2_auth_password/send_keys
### 网盘引擎
+ 超能搜: https://www.chaonengsou.com
## 空间引擎搜索
+ FOFA: https://fofa.so
+ Quake: https://quake.360.cn/quake/#/index
+ Hunter: https://hunter.qianxin.com
+ Shadon: https://www.shodan.io
+ ZoomEye: https://www.zoomeye.org
## 历史漏洞
+ 乌云镜像: https://wooyun.x10sec.org
+ Seebug: https://www.seebug.org
+ Exploit Database: https://www.exploit-db.com
+ Vulners: https://vulners.com
+ Sploitus: https://sploitus.com
## APP
+ 小蓝本: https://www.xiaolanben.com/pc
+ 七麦: https://www.qimai.cn
+ AppStore: https://www.apple.com/app-store
## 公众号
+ 微信直接搜索
+ 搜狗: https://weixin.sogou.com
## 小程序
+ 微信直接搜索
+ 小蓝本: https://www.xiaolanben.com/pc
# 信息深度收集: 
## 指纹识别
+ 火狐插件: Wappalyzer
+ 云悉: http://www.yunsee.cn
+ EHole: https://github.com/EdgeSecurityTeam/EHole
+ TideFinger: https://github.com/TideSec/TideFinger
+ ObserverWard:https://github.com/0x727/ObserverWard_0x727
## Title识别
+ WebBatchRequest: https://github.com/ScriptKid-Beta/WebBatchRequest
+ Bscan: https://github.com/broken5/bscan
## 目录扫描
+ Dirmap: https://github.com/H4ckForJob/dirmap
+ dirsearch: https://github.com/maurosoria/dirsearch
## JS接口
+ JSFinder: https://github.com/Threezh1/JSFinder
+ LinkFinder: https://github.com/GerbenJavado/LinkFinder
+ Packer-Fuzzer: https://github.com/rtcatc/Packer-Fuzzer (webpack)
+ 搜索关键接口
1. config/api
2. method:"get"
3. http.get("
4. method:"post"
5. http.post("
6. $.ajax
7. service.httppost
8. service.httpget
## WAF识别
+ WhatWaf: https://github.com/Ekultek/WhatWaf
+ wafw00f: https://github.com/EnableSecurity/wafw00f
# 综合利用工具
+ Goby: https://gobies.org
+ Xray: https://github.com/chaitin/xray
+ Nuclei: https://github.com/projectdiscovery/nuclei
