
> 有好用的工具可以投稿到这https://github.com/CuriousLearnerDev/Online_tools/issues/35

不在提供破解工具！

# 非常感谢下面的团队和信息安全研究人员的一些工具推荐

- 天启实验室
- 法克安全
- Pings
- 成都第一深情
- 还原设置
- 夜梓月
- SY
- 平平无奇的水蜜桃
- 火柬
- 向
- st.ANGER

# 该工具介绍

该工具是一个类似软件商城的工具可以进行工具下载，工具的卸载，工具的更新，工具编写了自动化的安装脚本，不用担心工具跑不起来

# 简介

工具还是依旧这么丑，真是能用就行了！

该工具投入还是比较多的，占用了大量的空闲时间，不说开发多费劲，每个工具都提供了安装和启动脚本，从写安装和启动打包下载测试一个工具起码20分钟

从去年4月份开始到现在都是免费提供下载，每个月的流量带宽费够吃一顿好的了，因为没有做下载限制大量下载链接盗用。后面可能不在提供免费下载，如果自己有服务器或者网盘或CDN，我在开发的时候专门写了一个自定义存放下载链接的接口，后面使用会详细介绍

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20240714190146471.png)

关于漏洞采集系统，最近基本上花了很长时间去写自动化漏洞采集系统他会自动化爬取微信公众号漏洞Poc，Gihtub采集漏洞代码采集，监控各种漏洞平台（x里云，x安信，x创宇，x盟等）判断采集利用Poc，会根据漏洞名称是否有POC/EXP提取关键字自动化去搜索引擎（支持谷歌、Bing）和Gihub搜索爬取和提取数据，监控xxhub、nuclei、exploitdb等漏洞利用平台

本来开发就是放工具箱里面的，最后思考决定为了安全考虑不会公开该漏洞库

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/Peek.gif)

# 现有工具（后面工具会慢慢更新增加）

现工具集成了有

- 常用工具
  - NC工具
  - BorpSuite社区版
  - BorpSuite专业版
  - sqlmap
  - nmap
  - yakit
  - hashcat
  - nuclei
  - xray
  - goby社区版

- OA/应用漏洞利用工具
  - MYExploit
  - OA-EXPTOOL
  - 通达OA利用工具
  - Nacos利用工具
  - 大华漏洞工具

- 中间件/CMS/框架漏洞利用工具
  - FastjsonScan
  - WeblogicTool
  - Struts2
  - ShiroAttack2
  - ShiroExp
  - ThinkPHP综合工具
  - ThinkPHP利用莲花
  - Jboss漏洞工具
  - SBSCAN
  - 漏洞集合工具
  - 综合类工具
  - LiqunKit
  - Full-Scanner
  - Yasso
  - Apt_t00ls
  - JNDIExploit
  - JNDIInjection

- webshell管理工具
  - 天蝎权限管理工具
  - 中国蚁剑
  - 冰蝎3.0
  - 冰蝎
  - 哥斯拉
  - webshell生成工具
  - 中国菜刀

- 内存马工具
  - arthas-boot-Linux

- 应急响应工具
  - BlueTeamTools
  - 河马webshell查杀
  - D盾
  - 火绒剑
  - PCHunter(手工杀毒)
  - Procexp(官方)
  - Procexp(中文)
  - GScan-Linux

- 代码审计工具
  - Seay
  - Code-audit

- 抓包类工具
  - Fiddler中文版
  - Charles中文版
  - Wireshark

- 爆破工具
  - 超级加解密转换
  - hydra
  - 社工密码生成器
  - SNETCracker
  - pydictor

- 数据库利用工具
  - sqlmap中文版
  - MDUT
  - ARDM

- XSS漏洞利用工具
  - XSStrike
  - dalfox

- 漏洞扫描工具
  - POC-bomber
  - afrog
  - fscan
  - Packer-Fuzzer
  - woodpecker

- 子域名探测工具
  - Layer子域名挖掘
  - subfinder
  - DnsX
  - OneForAll
  - OneLong

- 端口扫描工具
  - Naabu

- 目录扫描工具
  - 御剑后台扫描珍藏
  - Dirsearch

- 资产收集类工具
  - FofaViewer
  - Fofax
  - Search_Viewer

- 信息泄露类工具
  - 云存储泄露工具
  - SvnExploit
  - Dumpall

- 指纹识别工具
  - CMSeeK
  - Wafw00f
  - EHole

- 其他信息收集类工具
  - RouterScan中文
  - zpscan

- 插件
  - HaE
  - xiaSQL
  - nowafpls
  - LSTAR

# 下载链接滥用问题

然后有自己的下载服务器可以把文件放到下面这个地方，支持7z、zip、rar文件

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20240714190146471.png)



# 工具大小

这个是把全代码给重写了，之前代码量太大了，后面越写越像粑，在往上写更是粑加粑，最后决定重写吧，应为重写导致问题增加没有有的地方没有测试到，请反馈

这个版本比较到有20多mb因为里面添加了非常多的加密算法导致该工具现在很大

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20240714201306698.png)

# 打包离线版本的方法

工具和启动环境都会下载到`storage`文件夹里面，把这三文件夹压缩就就可以了，到其他系统不需要在从工具箱里面的工具了

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20230528074624279.png)



# 老版本界面

这个会出现一个问题就行会，找不到工具的问题

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20231209124940675.png)

现在新版本全部工具分类显示

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20240719112919404.png)



# 版本说明

## 1、不在提供破解工具！

不在提供破解工具下载，不在提供破解工具下载，不在提供破解工具下载，不在提供破解工具下载，不在提供破解工具下载，不在提供破解工具下载，不在提供破解工具下载，不在提供破解工具下载，不在提供破解工具下载

## 2、右键工具

之前我是把全部功能都放到了菜单栏上面会很乱

下载我们可以右键，如下

**1、放到下载好的工具上右键**

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20240714190622697.png)

**2、右键没有下载的工具**

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20240714190813669.png)

## 3、服务端自动化监控工具更新

之前工具更新基本上都是手动更加工具很繁琐很麻烦，在服务器上写了一个自动化更新推荐的功能

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20240714192157026.png)

## 4、工具插件下载功能（比如burp插件，目前维护较少）

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20240714192701951.png)

## 5、认证下载和自定义链接下载

因为下载链接滥用问题，后面全部需要购买认证下载才可以下载。如果不认证你也可以自己提供下载链接放上去

全部的工具下载配置文件在storage/toollist.json文件里面

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20240714190146471.png)

## 6、去除打开显示cmd窗口

之前添加这个启动cmd显示是为了显示日志，下载把日志保存起来了，可以在下面地方查看

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20240714192919486.png)

## 7、应急工作上传服务器功能

这个功能是为了linux应急使用的，然后可以右键后面带有linux的字的工具右键

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20240714193436316.png)

可以配置服务器连接

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20240714193557388.png)

他会下载上传到服务器端

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20240714193947857.png)

## 8、更新工具列表

如果想检测工具是否有更新和新增工具更新可以点击这个，他会检测你是否有工具更新，和新工具增加

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20240714194417972.png)

新工具增加

比如没有新增工具没有goby工具

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20240714194820682.png)

点击更新可以看见该工具更新增加上了

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20240714194916775.png)

比如有工具更新，和之前不之前是你之前下载的工具不能打开了，必须安装新工具，下载解决了这个问题如图

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20240714195634338.png)

## 9、解压问题系统版本问题

上个版本有一个大问题就是，解压问题大部分基本上都是这个问题导致安装失败，从代码里面使用的是tar命令，大部分系统是带这个命令的，但是可能有的服务器系统是没有这个命令导致安装失败，这个版本里面叫7z程序放到代码里面了不会出现解压不了安装失败的问题了



# 工具使用

如果你光下载使用工具就不用这么看工具使用了，点击就可以下载安装，全自动化的

简单介绍工具的使用

## 查看工具介绍

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20240715135043225.png)

## 工具卸载和打开目录和官方

右键下载好的工具图标

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20240714190622697.png)

## 工具列表更新

如果想检测工具是否有更新和新增工具更新可以点击这个，他会检测你是否有工具更新，和新工具增加

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20240714194417972.png)

新工具增加

比如没有新增工具没有goby工具

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20240714194820682.png)

点击更新可以看见该工具更新增加上了

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20240714194916775.png)

## 检查工具更新

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20240714195634338.png)

## 应急上传linux服务器

这个功能是为了linux应急使用的，然后可以右键后面带有linux的字的工具右键

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20240714193436316.png)

可以配置服务器连接

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20240714193557388.png)

他会下载上传到服务器端

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20240714193947857.png)

## 添加自己下载连接

如果自己有服务器可以打包我的包然后上传服务器叫下载地址放到

全部的工具下载配置文件在storage/toollist.json文件里面里面有一个空的参数

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20240715141617548.png)

这个参数就是对用的工具自定义下载地址，支持7z、zip、rar压缩方式

演示

叫下载好的工具把上传到服务器

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20240715141746950.png)

上传到服务器上面

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20240715141953393.png)

然后叫这个下载链接放到custom里面，

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20240715142110038.png)

他就不会调用作者的下载地址了

## 添加自己的自定义工具

这个功能我是真的写浪费了我一个周六周日周末的时间写出来的功能，真的要多多支持呀

下面我就详细说一下这个功能的使用

界面依旧很丑！

![image-20231209114217925](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20231209114217925.png)

我们随便点击一个添加按钮，如果我点击了是那个按钮就会自定义工具添加到选择的一行里面

![image-20231209114353122](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20231209114353122.png)

- 第一个工具名称：这个没有什么好说的就是添加的工具名称
- 第二个工具显示位置：我们叫图标的显示的位置
- 第三个工具图标：这个也没有什么好说的就是工具的图标
- 第四个程序启动的文件：我们的启动程序的文件
- 第六个选择启动环境：就是启动程序的需要的环境，这个一共有4个选择可以选择python3.8、JDK8、JDK20、无需环境这几个选项（使用的是工具内部的环境然后没有安装会自动下载）
- 第七个选择显示方式：这个就是你选择的工具的启动模式，然后是图形界面的就选择图形界面的，如果是命令行的就选择命令行的
- 第八个添加参数：这个就是我们运行的后面的参数，比如我们运行一个nmap -h，这个-h就是我们添加的默认启动的参数



下面是详细的说明


#### 1、第一个工具名称：

这个没有什么好说的就是添加的工具名称

#### 2、第二个工具显示位置：

这个我演示一下应该就可以明白了

比如我添加一个工具位置是1

![image-20231209114852295](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20231209114852295.png)

然后这个工具是在这

![image-20231209114921894](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20231209114921894.png)

然后我添加一个大于等于2的位置他就会下面这样

![image-20231209115044884](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20231209115044884.png)

然后这个工具的位置就变成了这样

![image-20231209115215153](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20231209115215153.png)

#### 3、第三个工具图标：

这个也没有什么好说的就是工具的图标

#### 4、第四个程序启动的文件：

![image-20231209120224387](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20231209120224387.png)

这个启动是文件就是然后你是比如sqlmapq启动文件就是如下

下面就是sqlmap的启动文件

![image-20231209115717673](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20231209115717673.png)

在如果比如是冰蝎工具

下面是他的启动文件

![image-20231209115839323](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20231209115839323.png)

在在如果是goby

下面是他的启动文件

![image-20231209120015171](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20231209120015171.png)

#### 5、第五个工具版本：

这个也没有什么好说的就是工具的版本

下面这个输入什么图标版本就显示什么

![image-20231209120413443](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20231209120413443.png)

![image-20231209120449061](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20231209120449061.png)

#### 6、第六个选择启动环境

这个一共有4个选择可以选择python3.8、JDK8、JDK20、无需环境这几个选项

![image-20231209120819600](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20231209120819600.png)

这个选择如果你是sqlmap这样的python的运行环境你就选择运行环境

运行自定义工具的简单原理就是这样 python运行地址加工具运行地址

图片

![image-20231209121344595](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20231209121344595.png)

在运行源码层面上其实比这个复杂一点，如果是命令行程序会生成一个一个start的文件夹然后在创建一个文件里面会生成一个工具的启动文件，你们用户就不用了考虑怎么多选择就完事了，GUI点点就完事了

![image-20231209121613163](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20231209121613163.png)



#### 7、第七个选择显示方式：

这个就是你选择的工具的启动模式，如果是图形界面的就选择图形界面的，如果是命令行的就选择命令行的



#### 8、第八个添加参数

这个就是我们运行的后面的参数，比如我们运行一个nmap -h，这个-h就是我们添加的默认启动的参数（可以忽略不加也可以）

![image-20231209122156799](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20231209122156799.png)

简单大概下面这样

![image-20231209122106196](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20231209122106196.png)

#### 自定义添加工具的案例

我们还是那sqlmap做演示

我在github叫sqlmap下载下来然后解压出来了，在`C:\sqlmap-master`

![image-20231209132442416](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20231209132442416.png)



然后添加就这样添加

![image-20231209132711891](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20231209132711891.png)

添加完成这个就显示了

![image-20231209132744269](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20231209132744269.png)

我们就可以点击运行了

![image-20231209132829235](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20231209132829235.png) 

# 之前版本

## 0.5.0公测版本新功能添加

### 增加新工具

- yakit
- SBSCAN

### 更新了什么

这个版本更新很多功能，下面我就说一下改动比较大的一些功能

- 自定义工具添加
- 改成了点击图标启动工具，下载工具，更新工具
- 添加自定义界面的设置
- 全局快捷键工具的搜索，可以按`alt+d`键快速弹出
- 下载卸载更新添加自动刷新界面
- 代码的运行优化



## 0.4.0公测版本新功能添加

增加了工具搜索功能，可以按`alt+d`键快速弹出

![image-20231105122208946](Explanationphoto/image-20231105122208946.png)

![image-20231105124818870](Explanationphoto/image-20231105124818870.png)

## v0.3.5增加新工具

- cs 4.9
- nuclei
- woodpecker_framework
- EHole
- 天蝎权限管理工具
- ARDM（AnotherRedisDesktopManager）
- MYExploit
- Cloud_Bucket_Leak_Detection_Tools
- SvnExploit
- dumpall
- FastjsonScan
- dalfox
- fiddler中文版
- Charles中文版
- Seay
- Wireshark
新功能添加

这个版本添加了一个网盘检测功能，可以检测网盘的工具包的状况，这个是因为在之前版本里面很多下载不了，或者是安装失败，基本上都是工具网盘的问题，所以添加了这个检测的功能

![image-20231029210550464](Explanationphoto/image-20231029210550464.png)

![image-20231029210626424](Explanationphoto/image-20231029210626424.png)

## v0.3.1公测试版更新功能

增加新工具
- Yasso
- Fofax
- zpscan
- pydictor
- mdut（Multiple Database Utilization Tools）
- Apt_t00ls
- 中国菜刀2016

新功能添加

1. 取消了运行cmd的状态窗口

   取消了下面的cmd运行状态窗口

2. 下载功能更新

   增加显示到了状态里面

   ![image-20230722183455076](Explanationphoto/image-20230722183455076.png)

   3. 工具卸载功能

   ![image-20230722182133585](Explanationphoto/image-20230722182133585.png)

![image-20230722182217086](Explanationphoto/image-20230722182217086.png)

4. 在线工具箱本身更新检查
   ![image-20230722182752832](Explanationphoto/image-20230722182752832.png)

5. 两个工具页

   应为新的工具一页放不下增加了一页

6. 解压功能

   解压的时候会弹出解压框，解压完成自动关闭解压框
   


## v0.22.1修复公测试版更新功能

1. **网盘出现问题在0.22之前的全部版本都不能下载工具了**，这几天很多人说工具下载不了了，这几天加班解决这个问题

   出现这个不能下载工具的原因是应为工具存储的网盘有改变，网盘用的是阿里云的、用的AList调用的，AList的策略更新了下载地址有变化，程序无法文件下载的文件名导致的这个问题

2. 还有就是下载工具的时候调用的系统命令进行下载的新版本的windows系统下载可能没有问题但是老版本的windows系统就无法下载，然后增加了内置下载程序无需在调用系统命令进行下载

![image-20230701112129639](Explanationphoto/image-20230701112129639.png)

## v0.22测试版更新功能

上一个版本窗口太大了这个版本窗口字体和图标变小

工具添加：SNETCracker工具、Jboss漏洞检查工具、OA漏洞检查工具、Naabu、DnsX、subfinder 

## v0.2测试版更新功能

1. 鼠标放到工具图标上可以看见工具的简单说明

   ![image-20230528073006886](Explanationphoto/image-20230528073006886.png)

2. 添加了更新功能、点击查看更新、里面的工具是可以官方版本更新我在推送到网盘里面你们可以进行工具的更新

   <font color=FF0000> （工具箱里面的工具如果作者更新频繁、我这边会添加到可以更新名单里面、如果半年多以上没有更新的我没有添加更新列表里面） </font>

   ![image-20230528073138197](Explanationphoto/image-20230528073138197.png)

   点击检查更新

   ![image-20230528073531842](Explanationphoto/image-20230528073531842.png)

   我们就可以进行工具的升级

   ![image-20230528073653497](Explanationphoto/image-20230528073653497.png)

3. 下面好的工具我们可以叫鼠标放到按钮上查看工具版本

   ![image-20230528074047012](Explanationphoto/image-20230528074047012.png)

4. 添加测试网盘是否正常，很多不可控因素不正常你们工具就下载不了，不正常可以联系我，会进行修复

   如果是没有连接网络会报下面的情况

   ![image-20230528074509194](Explanationphoto/image-20230528074509194.png)





## v0.1

该工具是在线下载工具，用到什么工具就可以下载安装什么工具

工具本来是做linux工具箱用的，开发开发就开发到windows上了，开发一个星期左右完成

工具大小非常小！！！！py打包的文件很大5555

![image-20230516210735728](Explanationphoto/image-20230516210735728.png)

## 免责声明：

***
### 1. 该安全工具仅供技术研究和教育用途。使用该工具时，请遵守适用的法律法规和道德准则。

### 2. 该工具可能会涉及安全漏洞的测试和渗透测试，但请在授权的范围内使用，否则和作者无关

### 3. 使用该工具可能会涉及到一定的风险和不确定性，用户应该自行承担使用该工具所带来的风险。
### 4. 工具箱的工具有您合法权益问题可以联系我第一时间删除。
### 5. 使用本工具的用户应自行承担一切风险和责任。开发者对于用户使用本工具所产生的后果不承担任何责任。
