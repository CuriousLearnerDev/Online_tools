### 🛡️ TrafficEye 护网工具 ：https://github.com/CuriousLearnerDev/TrafficEye

### 📦 下载方式

#### 🔗 所有版本地址：

GitHub Releases：https://github.com/CuriousLearnerDev/Online_tools/releases


#### ✅ 全打包版：
- 0.11.1 版本：
  - 夸克网盘：https://pan.quark.cn/s/51ff0477e7ca 提取码：K76N

#### 🛠 工具扩展包

- 工具列表：[全工具列表](https://github.com/CuriousLearnerDev/Online_tools/blob/master/Tools_list.md)

## 🔧 工具介绍

该工具专为运维和安全检查和学习研究设计，类似于软件商城，可以实现工具下载、更新，并提供自动化安装脚本。对于信息安全专业的学生而言，不用担心工具无法正常运行配置，提升学生学习效率。

集成了类型工具如下：

🛡️ 运维&防守工具：应急响应、内存马查杀、日志分析、流量抓包、代码审计、反编译/逆向
🔎 信息收集工具：子域名探测、端口扫描、指纹识别、目录扫描、资源发现、信息泄露
💥 漏洞利用工具：中间件/CMS/框架漏洞、OA/应用漏洞、Webshell管理、漏洞扫描、数据库漏洞、XSS漏洞

## 🆕 0.12.7更新新增

本次版本进行了重构：

- 修改美化界面
- 搜索增加筛选选项
- 添加工具点赞、工具排行
- 修改更新选项位置
- 修复资产格式不正确卡在加载界面上
- 最小化

由于此版本进行了较大改动，可能会存在一些未知问题，考虑到个人的测试能力有限，如果你在使用过程中遇到任何问题，请随时反馈

## 🗂  文件大小

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20260105172130905.png)

## 🖥️ 新版本界面更

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20260105172208805.png)

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20260108180251280.png)

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20260105172716856.png)

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20251202115945944.png)

检测工具新增和更新

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20251129162044486.png)

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20251202120037099.png)

![image-20251202120101506](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20251202120101506.png)

右键

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20251129162225861.png)

插件

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20251129162318725.png)

打开命令行工具

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20251202120147147.png)

## ☁️  工具自定义服务器（可自由扩展）

如果你有自己的服务器，可以将工具包自行上传，让平台从你的私有服务器下载，实现私有化部署。

配置文件路径：

```
storage/toollist.json
```

其中有一个 `custom` 字段，只需把你的工具包 URL 填进去即可

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20251118124006578.png)

📌 **注意：服务器中的文件夹名称必须与工具名一致**，否则无法识别

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20251118123820355.png)

## 📣 自定义工具格式（可自由扩展）

配置文件说明：

- `storage/pluginlist.json`：存储选项卡设置、插件信息、图标配置等
- `storage/toollist.json`：存储所有工具的名称、版本等详细信息

例如：toollist.json文件

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20251118151845280.png)

```json
"VulnerabilityScanning": {  // 工具分类
    "POC-bomber": {
        "position": [1,70],           // 可选，兼容老版本的位置信息
        "environment": "Python38",    // 运行环境要求
        "version": "3.0.0",           // 工具版本
        "commandLine": "True",        // 是否显示命令行界面
        "official": "https://github.com/tr0uble-mAker/POC-bomber", // 官方地址
        "introduce": "漏洞检测工具",   // 工具介绍
        "r": "",                      
        "custom": ""                  // 自定义下载地址
    }
}
```

## 兼容老版本

如果已经下载使用老版本，下载新版本解压覆盖即可

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20251118162356877.png)



## 🔮 后续AI计划（可能！）

后续计划可能会加入 **AI 自动化调度能力**：通过编写 MCP 调用Gemini-cli 或其他模型规划，并调用工具箱里所有可通过命令行运行的工具，实现批量自动化扫描。由于图形化工具无法被 AI 直接控制，目前只能调用终端类工具，这部分能力可能略显**鸡肋**，整体实现效果暂时不算理想，但仍会持续探索更好的方式。

MCP 示例

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20251118191347044.png)

Gemini-cli + MCP 调用

![](https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20251118191452702.png)


### 🧩 问题与交流交流群

<img src="https://zssnp-1301606049.cos.ap-nanjing.myqcloud.com/img/image-20250725161624253.png" width="200"/>




### 🙏 鸣谢
特别感谢以下团队与信息安全研究者对工具技术的支持与推荐（排名不分先后）：

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
- start


### ⚠️ 免责声明：
1. 本安全工具仅供技术研究和教育用途。使用该工具时，请遵守适用的法律法规及道德准则。

2. 用户应遵守《中华人民共和国网络安全法》，并且不得将该工具用于未经授权的测试或非法活动。否则，用户自行承担所有责任，与工具作者无关。

3. 本工具可能涉及安全漏洞测试和渗透测试，请仅在合法授权范围内使用，否则用户需自行承担风险，且与工具作者无关。

4. 本工具附带使用教程，仅提供学习使用。请确保仅在授权的情况下参考和执行教程内容。否则用户需自行承担风险，且与工具作者无关。

5. 如该工具涉及侵犯您的合法权益，请及时联系工具开发者，开发者将在第一时间处理并删除相关内容。

6. 使用本工具的用户应自行承担一切风险和责任。开发者不对因使用本工具产生的任何后果承担责任。

7. 使用本工具可能存在一定的风险和不确定性，用户应自行评估并承担所有相关风险。
***



✨随着时间的推移，观星者
[![Stargazers over time](https://starchart.cc/CuriousLearnerDev/Online_tools.svg?variant=adaptive)](https://starchart.cc/CuriousLearnerDev/Online_tools)
