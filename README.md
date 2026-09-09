### 目前在HW期间，使用该工具。如果设备发生告警wp.ahsdhanskdqwe.xyz这个地址154.21.200.69可以忽略改地址是纯静态地址。如果自己不确定可以加群联系作者免费信息分析排查

### 📦 下载方式

#### 🔗 官方发布页1.1.1最新版本

- **GitHub Releases**：https://github.com/CuriousLearnerDev/Online_tools/releases

#### ✅ 全功能打包版1.0.3

- **夸克网盘**：链接：https://pan.quark.cn/s/d09ada044927

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20260831011447853.png)

------


## 📦目前已集成 322 安全工具

每个月更新增大概4-10个工具

```
🛡️ 运维&防守工具：应急响应、内存马查杀、日志分析、流量抓包、代码审计、反编译/逆向
🔎 信息收集工具：子域名探测、端口扫描、指纹识别、目录扫描、资源发现、信息泄露
💥 漏洞利用工具：中间件/CMS/框架漏洞、OA/应用漏洞、Webshell管理、漏洞扫描、数据库漏洞、XSS漏洞
🧠 综合利用工具：综合利用、爆破&编解码、后渗透&C2控制、免杀
☁️ 云安全工具：云工具
📱 移动端工具：APP工具、小程序工具
📡 无线安全工具：无线工具
🧪 取证分析工具：内存/文件取证、隐写分析、固件分析
⚙️ 环境工具：实验环境、AI相关、运行环境
```

## 🔧 工具介绍

该工具专为运维和安全检查和学习研究设计，类似于软件商城，可以实现工具下载、更新，并提供自动化安装脚本。内置了Claude Web 终端、NyxStrike/HexStrike 社区版 可以通过AI调用里面工具实现自动化扫描。不用担心工具无法正常运行配置，提升效率。

## 🆕 0.17.x更新新增

1. AI 智能体：七个引擎Claude Code、OpenCode、Gemini CLI、Codewhale、Hermes、Codex、Cursor CLI
2. 漏洞库 6.8万+ 指纹库 1800+
3. 工具 300+ 插件 30+ 导航 180+
4. kill 40+
5. 新增AI拦截器
6. 修复AI智能体bug
7. 新增mpc
8.增量漏洞库
9. 可以监控服务器ai监控
10. 设置增加：缩放、高度设置
11. 终端复制功能
12. AI 文件夹显示优化

在详细更新可以往下：

## 🗂  程序大小

文件压缩的大小

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20260712202053947.png)

# 统领 使用手册

> **统领** — 安全工具箱 · AI 智能体 · 漏洞库
> 适用对象：安全研究人员、渗透测试工程师、CTF 选手及**获得授权**的安全测试人员
> 适用版本：Windows 

---

## 目录

1. [统领是什么]
2. [电脑配置要求]
3. [界面说明]
4. [武器库]
5. [自定义工具]
6. [AI 智能体]
7. [漏洞库]
8. [投稿箱]
9. [讨论大会]
10. [监控]
11. [设置]
12. [数据存放位置]
13. [常见问题]
14. [免责声明]

---

## 1. 统领是什么

统领是一款 **Windows 桌面安全工具箱**，把日常渗透测试、漏洞研究常用的能力集中在一个程序里，主要包含：

| 模块 | 能做什么 |
|------|----------|
| **武器库** | 浏览、下载、安装、一键启动数300+款安全工具（每月更新3-9个工具） |
| **插件库** | 管理 Burp、Cobalt Strike（CS）等平台的扩展插件 |
| **AI 智能体** | 多引擎 AI 渗透终端，辅助分析与自动化 |
| **漏洞库** | 统一检索 Nuclei 模板、Afrog POC、Exploit-DB 等 |
| **社区** | 投稿新工具、论坛讨论、公告、GitHub 版本监控 |
| **导航站** | 常用安全网站书签 |

统领为绿色便携版：解压后即可使用，无需安装到系统目录。工具、配置、日志等数据都保存在程序旁边的 `storage` 文件夹中，方便备份与迁移

---

## 2. 电脑配置要求

| 项目 | 建议 |
|------|------|
| 系统 | **Windows 10 / 11**（64 位） |
| 内存 | 4 GB 及以上；使用 AI 智能体建议 **6 GB** |
| 硬盘 | 视下载工具数量而定，建议预留 **20 GB 以上** 空闲空间 |

---

## 3. 界面说明

程序顶部为选项卡栏，各选项卡功能如下：

| 选项卡 | 功能 |
| ------ | ---- |
| **武器库** | 下载、安装、启动安全工具 |
| **插件库** | Burp 等插件扩展 |
| **AI智能体** | AI 渗透终端工作台 |
| **漏洞库** | POC 搜索与详情 |
| **投稿箱** | 向社区投稿新工具 |
| **讨论大会** | 论坛交流、工具排行榜 |
| **导航站** | 安全网站书签 |
| **公告栏** | 官方公告 |
| **监控** | GitHub 工具版本监控、AI 运行日志 |
| **设置页** | 主题、启动器、下载源等 |

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20260903223835778.png)

### 显示模式

武器库界面支持三种显示模式，可在 **设置 → 功能设置 → 显示模式** 中切换：

| 模式 | 界面特点 |
| ---- | -------- |
| **分类** | 按工具类型分栏，左侧树形导航 |
| **全显** | 不折叠分类，一屏展示更多工具卡片 |
| **搜索模式** | 类似启动器：快捷键唤起，输入即搜、回车即开 |

#### 分类模式

默认即为分类模式

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20260907125449501.png)

#### 全显模式

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20260907125424352.png)

#### 搜索模式（启动器）

搜索模式类似系统启动器：按下快捷键即可唤起，输入即搜、回车即开。唤起搜索的快捷键可在 **设置** 中修改：

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20260907125005249.png)

切换成启动模式后，它会变成一个很小的搜索框，不使用时会自动消失：

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20260907125254229.png)

搜索模式用法：

- 按 **Alt + D** 直接进入便捷搜索模式
- 面板可贴边收起为悬浮球，需要时再点开
- 在搜索框或悬浮球上 **右键** 可切换分类 / 全显显示方式

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20260907124830000.png)

搜索漏洞需先启动 AI 智能体服务，因为漏洞库的漏洞数据由 AI 智能体提供：

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20260907125233858.png)

启动相关的分类等设置可在 **设置** 中调整：

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20260907125921907.png)

---

## 4. 武器库

| 功能 | 说明 |
| ---- | ---- |
| 批量下载 | 按场景一键勾选、批量安装或更新工具 |
| 检查更新 | 同步工具列表、检测统领程序与工具是否有新版本 |
| ＋（自定义工具） | 把本机已有的 exe、脚本加入武器库 |
| 下载队列 | 查看正在下载的任务与解压进度 |

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20260903224040847.png)

打开武器库后，每个工具都自带执行说明。例如点击启动 **POC-bomber**，界面会给出运行方式：

```
***********************POC-bomber**********************

使用:  ..\Python38\python.exe pocbomber.py -h [参数]

"******************************************************
```

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20260907123236505.png)

点击工具即可开始下载：

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20260907121311580.png)

如果工具依赖运行环境，下载完成后，工具图标会提示「下载运行环境」：

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20260907123742008.png)

注意：未安装所需运行环境的工具可能无法运行。若没有提示，可到「运行环境」中自行下载：

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20260907123618612.png)

> 运行环境说明：内置的 Python、Java 等运行环境相互独立，不会添加或修改本机已有的运行环境，只服务于统领内置工具

支持批量下载与更新：

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20260907121421594.png)

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20260907121435242.png)

想查看武器库是否新增了工具、统领本身是否有更新，可点击「更新检测」：

![image-20260907122831967](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20260907122831967.png)

![image-20260907122811847](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20260907122811847.png)

---

## 5. 自定义工具

适合添加统领武器库中没有、但本机已有的程序：

1. 点击武器库右上角 **＋**，或在武器库空白处右键
2. 选择「添加工具」，填写名称、路径、分类等信息
3. 也可以新建自定义分类，方便归类管理

支持 `.exe`、`.bat`、`.cmd`、`.py`、`.jar`、快捷方式等格式：

![image-20260907123933309](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20260907123933309.png)

---

## 6. AI 智能体

AI 智能体将多种 AI 终端与渗透工具集成到一起，支持 Claude Code、Hermes、OpenCode、Codex、Gemini CLI、Cursor CLI 等多种引擎。

首次使用 AI 智能体与漏洞库前，需要先下载以下组件（会自动保存到 `storage` 目录）：

| 组件 | 用途 |
| ---- | ---- |
| Python 3.11 | AI 运行环境 |
| Claude Code | AI 引擎 |
| HexStrike 引擎 | 渗透编排核心 |
| HFinger | 指纹识别 |
| NPS | 内网穿透 |
| Hermes | 辅助组件 |
| OpenCode / Codex / Gemini CLI / Cursor CLI | 多种 AI 引擎 |
| Nuclei Templates | 漏洞模板（供漏洞库使用） |
| Afrog POCs | POC 库（供漏洞库使用） |
| Exploit-DB | 漏洞利用库（供漏洞库使用） |

下载对话框中提供「下载全部可下载项（含可选引擎）」与「跳过」两个选项（跳过后部分功能不可用）。

进入 **AI 智能体** 后，顶栏和底栏会默认收起，把屏幕留给终端。需要切换其他页面时，点击页面内的 **展开** 按钮即可恢复完整界面。

点击「AI 智能体」选项卡：

![image-20260907110402829](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20260907110402829.png)

目前支持多种智能体，如 Claude Code、Hermes、OpenCode、Codex、Gemini CLI、Cursor CLI：

![image-20260907095842755](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20260907095842755.png)

如果想在浏览器中打开该界面，可点击「浏览器打开」：

![image-20260907105906246](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20260907105906246.png)

点击后会自动跳转到浏览器。

也可以切换成「桌面工作台」模式，远程访问时就像操作一个电脑桌面：

![image-20260907110056232](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20260907110056232.png)

支持同时启动多个窗口显示：

![image-20260907105944579](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20260907105944579.png)

![image-20260907113950188](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20260907113950188.png)

手机网页访问效果：

![img](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/20260706133816_392_8.png)

![img](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/20260706134321_396_81.png)

支持回滚查看历史访问记录：

- 可快速进入之前的历史会话
- 支持删除历史会话

![image-20260907095917437](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20260907095917437.png)

### AI 配置

点击这里可添加新的 API 配置：

![image-20260907095946501](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20260907095946501.png)

![image-20260904101814156](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20260904101814156.png)

如果想查看对应智能体的相关配置文件，可点击这里：

![image-20260907100022833](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20260907100022833.png)

![image-20260907100041294](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20260907100041294.png)

### 修改默认智能体的启动方式

支持设置以下项：

- 开场第一句话
- 开场提示模板（提示词）
- 网络代理（可选）
- 工作目录
- 高级配置
- 额外命令参数
- 自定义整行命令
- 是否默认全部 yes（免回车）

![image-20260907100119513](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20260907100119513.png)

如需切换项目目录，可点击选择按钮自行切换：

![image-20260907100215825](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20260907100215825.png)

如果想使用你自己系统里的智能体，可以在「命令执行」中编辑。例如想运行本机的 Claude，需要先找到它的位置，我电脑上的路径是 `C:\Users\zss\AppData\Roaming\npm\claude.cmd`：

![image-20260907101405026](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20260907101405026.png)

### 流量过滤器（拦截器）

目前最多可开启三层过滤：

规则过滤 → AI 审核 → 全流量记录

![image-20260903224657746](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20260903224657746.png)

**1. 规则拦截**

过滤内容：智能体工具调用时发出的命令 / 参数 / URL（包括 `curl -X DELETE`、`http_request`、改密接口、危险正则等）：

![image-20260904103311054](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20260904103311054.png)

**2. AI 拦截**

- 不送审：只读 GET、普通扫描探测（read / probe），以及 MITM 出站流量
- 会送审的示例：`curl -X POST/PUT/PATCH/DELETE`、改密码、删库、写配置等

![image-20260904103532126](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20260904103532126.png)

**3. 全流量记录**

会记录完整的请求与响应流量，包括与大模型的交互流量等：

![image-20260904103709052](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20260904103709052.png)

### 智能体交互分析

该功能专门用于 AI 智能体研究，可以抓包分析 Claude 的交互过程。

例如想分析 AI 智能体的执行逻辑，可启动监听（注意：抓包前需要先安装证书）：

![image-20260907102157607](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20260907102157607.png)

我让它执行「帮我查询一下当前系统有没有 curl 命令」：

![image-20260905191822338](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20260905191822338.png)

看起来它好像本来就知道，其实并非如此。通过抓包我发现，为了回答这句话，它一共发送了 3 次 HTTP 请求：

| 第几次 | 用途 | 返回 |
| ------ | ---- | ---- |
| 第 1 次 | 为新会话生成标题 | `{"title":"系统curl命令"}` |
| 第 2 次 | 真正的对话请求 | 一个要调用 PowerShell 的意图 |
| 第 3 次 | 把命令执行结果回填 | 最终的回答 |

![image-20260905194412266](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20260905194412266.png)

还原对话时，如果内容过多可能会被截取（主要是为了避免界面卡顿，后续会进一步优化该功能）。

如果想查看原始内容，可点击「原文」和「帧」：

![image-20260907102724252](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20260907102724252.png)

![image-20260907102739838](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20260907102739838.png)

### 扫描结果图谱

Claude 会话分析会读取 Claude Code 落盘的会话文件，只抽取类似扫描的工具调用，再绘制成攻击链：

![image-20260907104959889](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20260907104959889.png)

![image-20260907104456432](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20260907104456432.png)

![image-20260907104906063](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20260907104906063.png)

### 快速报告生成

需要生成报告时，点击下面这个按钮，可让 AI 快速生成测试报告并放入扫描报告目录：

![image-20260904104224316](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20260904104224316.png)

点击「生成报告」，实际就是向 AI 智能体发送一条生成报告的指令，其中包含生成位置和格式：

![image-20260907105243875](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20260907105243875.png)

下面是我生成报告的效果：

![image-20260903224740439](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20260903224740439.png)

支持导出 PDF 与 Markdown（.md）格式：

![image-20260907105553349](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20260907105553349.png)

![image-20260907105528557](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20260907105528557.png)

### 文件管理器

该功能主要面向把统领部署到服务器、通过公网网页访问的场景，支持文件预览、修改、上传等常见文件操作：

![image-20260903224856115](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20260903224856115.png)

工作台端展示：

![image-20260907114136256](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20260907114136256.png)

### 技能 Skill

说实话这个功能意义不大，导入测试后并未明显提高工作效率。

目前常见开源 Skill 已内置，点击「导入」即可使用。

注意：如果报错，可能是对应的文件夹或文件不存在，手动创建即可。

![image-20260903224950175](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20260903224950175.png)

### MCP 连接

可自行选择并导入想用的 MCP 服务：

![image-20260903225035358](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20260903225035358.png)

### 指纹库

本地 HFinger 指纹以 JSON 形式保存，统领启动时加载到内存，供搜索与 MCP 扫描使用：

![image-20260907115408279](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20260907115408279.png)

### 社交接入

目前支持 Telegram、钉钉、QQ 等请求接入到终端。由于这个功能我用得不多，可能存在较多问题，后期若有相关反馈，我会及时修复：

![image-20260713113029751](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20260713113029751.png)

### 内网穿透

该功能用于在普通家庭网络环境下，把本地端口映射到公网，方便从外部访问并调用智能体。

使用的穿透工具为 NPS，可自行下载服务端搭建使用：

![image-20260907120147052](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20260907120147052.png)

![image-20260907115840495](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20260907115840495.png)

### AI 页设置

这里可以导入字典位置，方便工具调用时使用（该功能基于二开的 HexStrike-AI），此外还有一些其他设置：

![image-20260907120227079](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20260907120227079.png)

---

## 7. 漏洞库

漏洞库基于 AI 智能体的接口，把 Nuclei 模板、Afrog POC、Exploit-DB 等内容汇总到一起，方便按关键词、CVE、产品名检索 POC 与 EXP。添加这个选项卡，正是为了方便查找漏洞的 POC / EXP。

使用漏洞库前需满足以下条件：

1. AI 智能体服务已启动（漏洞库依赖 AI 服务）
2. 已完成 AI「必下载项」中与 POC 相关的三项
3. 已在 AI 智能体页执行过「同步漏洞库 POC」

![image-20260907115317015](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20260907115317015.png)

![image-20260903224132224](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20260903224132224.png)

![image-20260903224210367](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20260903224210367.png)

---

## 8. 投稿箱

如果发现好用的安全工具，希望纳入统领武器库，可通过 **投稿箱** 提交。界面比较直观，简单说明一下：

- 投稿列表会显示 **待审核 / 已通过 / 已拒绝** 等状态，点击可查看详情
- 审核结果一般会发送到你填写的邮箱

![image-20260907124303857](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20260907124303857.png)

需要填写的内容：

- 工具名称、开发者、版本、类型
- 下载地址、官方主页、源码地址
- 运行环境（Windows/Linux 等）、GUI 或命令行
- 安装说明、工具简介
- 你的昵称、联系方式
- 图形验证码

---

## 9. 讨论大会

统领内置社区论坛，用于交流使用经验、反馈问题。

该功能目前仍处于测试阶段，如有问题欢迎多反馈。

---

## 10. 监控

监控页有两个标签：**GitHub 监控** 和 **AI 日志**。

### GitHub 监控

自动对比武器库中的工具与其 GitHub 仓库的最新 Release（该检测由服务器端的自动化脚本完成，结果仅供参考）：

| 状态 | 含义 |
| ---- | ---- |
| 已最新 | 本地版本与远程一致或更新 |
| 可能更新 | 远程可能有新版本 |
| 检测失败 | 网络或仓库访问异常 |

可按状态筛选列表。发现可更新的工具后，可到武器库或「检查更新」中升级：

![image-20260907124534104](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20260907124534104.png)

### AI 日志

查看 AI 智能体相关的运行日志。服务端有一个自动更新的 AI Agent，便于排查终端会话、服务启动等问题：

![image-20260907124724484](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20260907124724484.png)

---

## 11. 设置

打开顶栏 **设置页**，左侧可切换不同的设置分类：

| 设置项 | 说明 |
| ------ | ---- |
| 显示模式 | 分类 / 全显 / 搜索模式 |
| UI 主题 | 暗色（Mocha）/ 亮色（Light） |
| 界面缩放 | 75%～150%，适应不同分辨率 |
| 主窗口大小 | 默认约 1650×900，可自定义 |
| 武器库布局 | 图标大小、间距、每排数量、默认排序 |
| 下载浮窗 | 是否显示、是否默认展开 |
| **关闭全部外网请求** | 开启后认证、下载、更新、公告、外链均不访问外网（仅本机功能可用，适合 HW / 隔离环境） |

![image-20260907125530263](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20260907125530263.png)

其中「关闭全部外网请求」是一个独立的开关。之所以提供该选项，是因为拉取更新、获取公告等操作可能触发安全设备的告警，建议在 HW 等环境开启。开启后，程序将完全处于离线状态：

![image-20260907125610759](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20260907125610759.png)

**搜索模式** 的快捷键、悬浮球等用法见[界面说明](#3-界面说明)。首次使用时的 **新手引导** 中也有三种模式的示意图，可先预览再选择。

---

## 12. 数据存放位置

统领为绿色便携软件，用户数据与下载内容主要保存在 **程序目录旁的 `storage` 文件夹**：

```
├── main.exe
├── resources/              ← 程序本体，请勿手动修改
├── storage/                ← 你的数据都在这里
│   ├── （各安全工具安装目录）
│   ├── nuclei-templates/   ← 漏洞模板
│   ├── afrog-pocs/
│   ├── exploitdb/
│   ├── 配置文件、日志等
│   └── …
└── …
```

| 内容 | 位置 |
| ---- | ---- |
| 已下载的安全工具 | `storage` 下各工具子文件夹 |
| 漏洞库 POC 数据 | `storage` 内对应目录 |
| 个人设置 | 由程序自动管理，设置页底部可查看配置文件路径 |
| 运行日志 | **设置 → 运行日志**，按日期查看 |

**备份建议**：定期复制整个 `storage` 文件夹；换电脑或重装系统时，连同统领程序一起拷贝，即可恢复环境

---


### ⚠️ 免责声明：
1. 本安全工具仅供技术研究和教育用途。使用该工具时，请遵守适用的法律法规及道德准则。

2. 用户应遵守《中华人民共和国网络安全法》，并且不得将该工具用于未经授权的测试或非法活动。否则，用户自行承担所有责任，与工具作者无关。

3. 本工具可能涉及安全漏洞测试和渗透测试，请仅在合法授权范围内使用，否则用户需自行承担风险，且与工具作者无关。

4. 本工具附带使用教程，仅提供学习使用。请确保仅在授权的情况下参考和执行教程内容。否则用户需自行承担风险，且与工具作者无关。

5. 如该工具涉及侵犯您的合法权益，请及时联系工具开发者，开发者将在第一时间处理并删除相关内容。

6. 使用本工具的用户应自行承担一切风险和责任。开发者不对因使用本工具产生的任何后果承担责任。

7. 使用本工具可能存在一定的风险和不确定性，用户应自行评估并承担所有相关风险。
***

**W啥都学出品**
![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/zuozgzh.png)

✨随着时间的推移，观星者
[![Stargazers over time](https://starchart.cc/CuriousLearnerDev/Online_tools.svg?variant=adaptive)](https://starchart.cc/CuriousLearnerDev/Online_tools)


*本手册面向统领 Windows 便携版（exe）用户编写。界面随版本更新可能略有差异，以您使用的实际程序为准*
