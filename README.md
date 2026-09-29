

## 📦 下载方式

#### 🔗 官方发布页1.1.1最新版本

- **GitHub Releases**：https://github.com/CuriousLearnerDev/Online_tools/releases

#### ✅ 全功能打包版1.0.3

- **夸克网盘**：链接：https://pan.quark.cn/s/d09ada044927

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20260831011447853.png)

------


## 📦目前已集成 340 安全工具

每个月更新增大概4-10个工具

```
🛡️ 运维&防守工具：应急响应、日志分析、流量分析、代码审计、反编译/逆向
🔎 资产发现工具：子域名探测、端口扫描、指纹识别、目录扫描、资源发现、信息泄露检测
🧪 漏洞检测与验证工具：中间件/CMS/框架漏洞检测、OA/应用安全测试、Web 安全测试、数据库安全测试、XSS 检测与验证
🔬 高级安全研究工具：安全测试辅助、编解码、实验环境及其他安全研究工具
☁️ 云安全工具：云工具
📱 移动端工具：APP工具、小程序工具
📡 无线安全工具：无线工具
🧪 取证分析工具：内存/文件取证、隐写分析、固件分析
⚙️ 环境工具：实验环境、AI相关、运行环境
```

## 🔧 工具介绍

该工具专为运维、安全检查、安全研究和经授权的安全测试设计，类似于软件商城，可用于安全工具下载、更新、管理和运行环境配置。内置多种 AI 终端，并支持将 AI 用于安全分析、结果整理和工具编排；涉及高风险或可能产生实际影响的操作时，应由用户确认后执行。

## 🆕 1.x.x更新新增

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

## 🗂️ 程序大小

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
4. [工具中心]
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

## 🔐 项目定位与安全边界

**统领**定位为安全工具管理、研究辅助和安全测试工作台，不以自动化攻击为产品目标。

- AI 默认用于**信息整理、结果分析、任务规划、报告生成和工具辅助**。
- 涉及修改、删除、权限变更、漏洞验证或其他高风险操作时，建议由使用者**明确确认后执行**。
- 所有安全测试、漏洞验证和工具调用都应针对**本人拥有或已获得明确授权的目标**。
- 远程工作台、文件管理和第三方 AI 服务启用前，应先完成必要的身份认证、访问控制和数据安全配置。
- 第三方工具的功能和风险由其原作者决定，统领仅提供管理和运行入口。

## 1. 统领是什么

统领是一款 **Windows 桌面安全工具箱**，把日常安全测试、安全研究和安全运维中常用的能力集中在一个程序里，主要包含：

| 模块 | 能做什么 |
|------|----------|
| **工具中心** | 浏览、下载、安装和启动 300+ 款安全工具（每月持续更新） |
| **插件库** | 管理 Burp、Cobalt Strike（CS）等平台的扩展插件 |
| **AI 智能体** | 多引擎 AI 工作台，用于安全分析、任务辅助和工具编排 |
| **漏洞知识库** | 统一检索漏洞信息、Nuclei 模板、Afrog POC、Exploit-DB 等安全研究资料 |
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
| **工具中心** | 下载、安装、启动和管理安全工具 |
| **插件库** | Burp 等插件扩展 |
| **AI智能体** | AI 安全研究与任务辅助工作台 |
| **漏洞库** | 漏洞信息、POC 与安全研究资料检索 |
| **投稿箱** | 向社区投稿新工具 |
| **讨论大会** | 论坛交流、工具排行榜 |
| **导航站** | 安全网站书签 |
| **公告栏** | 官方公告 |
| **监控** | GitHub 工具版本监控、AI 运行日志 |
| **设置页** | 主题、启动器、下载源等 |

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20260903223835778.png)

### 显示模式

工具中心界面支持三种显示模式，可在 **设置 → 功能设置 → 显示模式** 中切换：

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

## 4. 工具中心

| 功能 | 说明 |
| ---- | ---- |
| 批量下载 | 按场景一键勾选、批量安装或更新工具 |
| 检查更新 | 同步工具列表、检测统领程序与工具是否有新版本 |
| ＋（自定义工具） | 把本机已有的 exe、脚本加入武器库 |
| 下载队列 | 查看正在下载的任务与解压进度 |

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20260903224040847.png)

打开工具中心后，每个工具都会提供基本运行说明。例如点击启动 **POC-bomber**，界面会给出运行方式：

```
***********************POC-bomber**********************

使用:  ..\Python38\python.exe pocbomber.py -h [参数]

"******************************************************
```

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20260907123236505.png)

选择工具即可开始下载：

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

1. 点击工具中心右上角 **＋**，或在工具中心空白处右键
2. 选择「添加工具」，填写名称、路径、分类等信息
3. 也可以新建自定义分类，方便归类管理

支持 `.exe`、`.bat`、`.cmd`、`.py`、`.jar`、快捷方式等格式：

![image-20260907123933309](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20260907123933309.png)

---

## 6. AI 智能体

AI 智能体将多种 AI 终端与安全研究工具集成到一起，支持 Claude Code、Hermes、OpenCode、Codex、Gemini CLI、Cursor CLI 等多种引擎。

首次使用 AI 智能体与漏洞库前，需要先下载以下组件（会自动保存到 `storage` 目录）：

| 组件 | 用途 |
| ---- | ---- |
| Python 3.11 | AI 运行环境 |
| Claude Code | AI 引擎 |
| HexStrike 引擎 | 安全工具编排与分析组件 |
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

### AI 操作安全控制（拦截器）

目前最多可开启三层安全控制：

规则检查 → AI 审核 → 操作记录

![image-20260903224657746](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20260903224657746.png)

**1. 规则拦截**

检查内容：智能体工具调用时产生的命令 / 参数 / URL（包括 `curl -X DELETE`、`http_request`、改密接口、危险正则等）：

![image-20260904103311054](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20260904103311054.png)

**2. AI 拦截**

- 默认低风险：只读请求、普通信息获取和分析操作
- 需要重点审核的示例：数据修改、删除、账号权限变更、配置写入等可能产生实际影响的操作

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

### 安全测试结果图谱

Claude 会话分析会读取 Claude Code 落盘的会话文件，只抽取类似扫描的工具调用，再绘制成安全测试流程图：

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

该功能主要面向远程工作场景，支持文件预览、修改、上传等常见文件操作。若部署到服务器并通过公网访问，请务必配置身份认证、访问控制和网络隔离，避免将工作台直接暴露给互联网。

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

### 远程访问

该功能用于远程访问本地工作台。启用公网访问前，请确认访问端已完成身份认证，并结合防火墙、反向代理、访问白名单等方式限制来源。不要在没有认证和访问控制的情况下直接将 AI 工作台暴露到公网。

使用的穿透工具为 NPS，可自行下载服务端搭建使用：

![image-20260907120147052](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20260907120147052.png)

![image-20260907115840495](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20260907115840495.png)

### AI 页设置

这里可以导入字典位置，方便经授权的安全测试和研究任务调用（该功能基于二开的 HexStrike-AI），此外还有一些其他设置：

![image-20260907120227079](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20260907120227079.png)

---

## 7. 漏洞知识库

漏洞知识库基于 AI 智能体接口，汇总漏洞信息、Nuclei 模板、Afrog POC、Exploit-DB 等安全研究资料，方便按关键词、CVE、产品名进行检索和分析。相关验证内容应仅用于获得授权的测试环境或实验环境。

使用漏洞库前需满足以下条件：

1. AI 智能体服务已启动（漏洞库依赖 AI 服务）
2. 已完成 AI「必下载项」中与 POC 相关的三项
3. 已在 AI 智能体页执行过「同步漏洞库 POC」

![image-20260907115317015](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20260907115317015.png)

![image-20260903224132224](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20260903224132224.png)

![image-20260903224210367](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20260903224210367.png)

---

## 8. 投稿箱

如果发现适合纳入统领工具中心的安全工具，可通过 **投稿箱** 提交。界面比较直观，简单说明一下：

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


### ⚠️ 使用与安全说明

1. **使用范围**：本项目面向安全研究、安全运维、开发测试、CTF 以及获得明确授权的安全测试场景。使用者应确保目标、数据和测试行为均处于合法授权范围内。

2. **AI 与工具执行**：AI 输出可能存在错误。涉及数据修改、删除、账号权限变更、配置写入、漏洞验证或其他可能影响目标系统的操作时，应由使用者进行人工确认并承担相应的操作责任。

3. **第三方工具**：本项目提供工具管理、下载和运行入口，部分工具由第三方开发和维护。请在使用前阅读对应项目的许可证、使用说明和安全要求，并遵守其许可条件。

4. **漏洞与验证资料**：项目中的漏洞信息、检测模板和验证资料用于安全研究和授权测试。不得将其用于未经授权的系统、服务或数据。

5. **远程访问**：如将 AI 工作台、文件管理或其他服务部署到服务器并开放远程访问，应自行配置身份认证、访问控制、网络隔离和日志审计。不要在没有必要的情况下直接暴露管理接口。

6. **网络与数据安全**：AI 对话、工具输出、请求响应和运行日志可能包含敏感信息。使用前请根据实际环境评估数据泄露风险，并避免向不可信的第三方服务提交敏感数据。

7. **项目责任边界**：本项目是安全工具管理与研究辅助软件，不保证第三方工具、AI 模型或外部服务始终正确、安全或可用。使用者应根据实际环境进行验证，并自行承担其具体使用行为产生的法律与安全责任。

8. **问题反馈**：如发现项目中存在明显的安全问题、侵权内容或不适当的资源，可通过项目提供的渠道反馈。
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


<a href="https://www.star-history.com/?repos=CuriousLearnerDev%2FOnline_tools&type=date">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/chart?repos=CuriousLearnerDev/Online_tools&type=date&theme=dark" />
    <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/chart?repos=CuriousLearnerDev/Online_tools&type=date" />
    <img alt="Star History Chart" src="https://api.star-history.com/chart?repos=CuriousLearnerDev/Online_tools&type=date" />
  </picture>
</a>


*本手册面向统领 Windows 便携版（exe）用户编写。界面随版本更新可能略有差异，以您使用的实际程序为准*
