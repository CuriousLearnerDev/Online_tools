
> 有好用的工具可以投稿到这https://github.com/CuriousLearnerDev/Online_tools/issues/35



## 非常感谢下面的团队和信息安全研究人员的一些工具推荐

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
- 远方

该版本主要是增加和优化0.7.0版本

## 简介

现在是在hw期间突然通过某些漏洞攻击进来了去做应急发现工具时候没有好的工具，又突然一些排查命令记不全就很尴尬很浪费时间的这个版本增加了应急响应工具一键打包功能

全部的应急响应工具都是严格排查是否存在后门程序，避免用U盘拷到服务器上面误报毒（前几天深有体会！）

应急文章还在写，这几天会更新

这个版本最大的遗憾就是我把“搜索功能”给砍掉了后面版本会在加上

更新详情请往下看

## 工具介绍

该工具是一个类似软件商城的工具可以进行工具和各种插件下载，工具的卸载，工具的更新，工具编写了自动化的安装脚本，不用担心工具跑不起来

## 漏洞库系统介绍

关于漏洞采集系统，最近基本上花了很长时间去写自动化漏洞采集系统他会自动化爬取微信公众号漏洞Poc，Gihtub采集漏洞代码采集，监控各种漏洞平台（x里云，x安信，x创宇，x盟等）判断采集利用Poc，会根据漏洞名称是否有POC/EXP提取关键字自动化去搜索引擎（支持谷歌、Bing）和Gihub搜索爬取和提取数据，监控xxhub、nuclei、exploitdb等漏洞利用平台

目前总采集5万多个漏洞

本来开发就是放工具箱里面的，最后思考决定为了安全考虑不会公开该漏洞库

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/Peek.gif)

## 工具大小

这个是在0.7.0版本基础之上写的还是使用的python的tk总体打包起来程序很小，如下：

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20240806201420799.png)

## 严重问题修复

- 认证问题修复
- 部分地区无法打开下载卡死修复

## 新版本界面更新说明

### 1、简单的界面

第一次打开工具会有一个提示选择全显示和分类显示

1、 全工具显示

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20240806201519443.png)

2、分类显示

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20240806202008415.png)

然后后面想设置，可以在设置里面设置

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20240806202552415.png)

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20240807192057914.png)

### 2、右键查看工具使用教程

目前我还在整理现在有时候比较忙没有时间搞，后面有更新，后面你点击更新会更新工具使用教程

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20240806202639994.png)

### 3、一键打包

可以一键打包全部和打包防守工具（只打包已经下载好的）打包格式是zip格式

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20240806202818829.png)

### 4、工具优化

这个版本优化的太多了下面简单说一下

- 下载完成后安装完成提示确定点击后关闭下载窗口
- 下载完插件提示确定自动打开下载好的插件路径
- 等等等。。。。。

## 工具使用

### 全部工具命令行提供启动说明

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20240806204655198.png)

### 查看工具介绍

鼠标放到工具名上面

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20240806204849385.png)

### 工具卸载和打开目录和官方

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20240806204944294.png)

### 工具新增更新

如果想检测工具是否有更新和新增工具更新可以点击这个，他会检测你是否有工具更新，和新工具增加

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20240714194417972.png)

新工具增加

比如没有新增工具没有goby工具

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20240714194820682.png)

点击更新可以看见该工具更新增加上了

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20240714194916775.png)



### 检查工具更新

也是点击这个

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20240714194417972.png)

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20240714195634338.png)

### 添加自己下载连接

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

### 添加自己的自定义工具

这个功能我是真的写浪费了我一个周六周日周末的时间写出来的功能，真的要多多支持呀

下面我就详细说一下这个功能的使用

界面依旧很丑！

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20231209114217925.png)

我们随便点击一个添加按钮，如果我点击了是那个按钮就会自定义工具添加到选择的一行里面

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20231209114353122.png)

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

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20231209114852295.png)

然后这个工具是在这

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20231209114921894.png)

然后我添加一个大于等于2的位置他就会下面这样

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20231209115044884.png)

然后这个工具的位置就变成了这样

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20231209115215153.png)

#### 3、第三个工具图标：

这个也没有什么好说的就是工具的图标

#### 4、第四个程序启动的文件：

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20231209120224387.png)

这个启动是文件就是然后你是比如sqlmapq启动文件就是如下

下面就是sqlmap的启动文件

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20231209115717673.png)

在如果比如是冰蝎工具

下面是他的启动文件

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20231209115839323.png)

在在如果是goby

下面是他的启动文件

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20231209120015171.png)

#### 5、第五个工具版本：

这个也没有什么好说的就是工具的版本

下面这个输入什么图标版本就显示什么

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20231209120413443.png)

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20231209120449061.png)

#### 6、第六个选择启动环境

这个一共有4个选择可以选择python3.8、JDK8、JDK20、无需环境这几个选项

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20231209120819600.png)

这个选择如果你是sqlmap这样的python的运行环境你就选择运行环境

运行自定义工具的简单原理就是这样 python运行地址加工具运行地址

图片

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20231209121344595.png)

在运行源码层面上其实比这个复杂一点，如果是命令行程序会生成一个一个start的文件夹然后在创建一个文件里面会生成一个工具的启动文件，你们用户就不用了考虑怎么多选择就完事了，GUI点点就完事了

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20231209121613163.png)



#### 7、第七个选择显示方式：

这个就是你选择的工具的启动模式，如果是图形界面的就选择图形界面的，如果是命令行的就选择命令行的



#### 8、第八个添加参数

这个就是我们运行的后面的参数，比如我们运行一个nmap -h，这个-h就是我们添加的默认启动的参数（可以忽略不加也可以）

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20231209122156799.png)

简单大概下面这样

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20231209122106196.png)

#### 自定义添加工具的案例

我们还是那sqlmap做演示

我在github叫sqlmap下载下来然后解压出来了，在`C:\sqlmap-master`

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20231209132442416.png)



然后添加就这样添加

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20231209132711891.png)

添加完成这个就显示了

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20231209132744269.png)

我们就可以点击运行了

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20231209132829235.png) 



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
