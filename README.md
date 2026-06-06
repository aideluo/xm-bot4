# 🤖 wx-bot4 - 企业级 AI 数字员工与微信私域运营大脑 (Enterprise Wechat Bot & AI Agent Platform)

[![GitHub Stars](https://img.shields.io/github/stars/aideluo/xm-bot4?style=flat-square&logo=github)](https://github.com/aideluo/xm-bot4)
[![Python Version](https://img.shields.io/badge/python-3.10%2B-blue?style=flat-square&logo=python)](https://www.python.org/)
[![Rust Axum](https://img.shields.io/badge/Rust-Axum-black?style=flat-square&logo=rust)](https://github.com/tokio-rs/axum)
[![SolidJS](https://img.shields.io/badge/SolidJS-WebUI-blue?style=flat-square&logo=solid)](https://solidjs.com/)
[![License](https://img.shields.io/badge/license-Commercial-red?style=flat-square)](#💼-商业合作与源码获取)

> 🚀 **wx-bot4** 是一款专为商业化落地设计的 **企业级 AI 微信多开运营平台** 与 **AI 数字员工系统**。
> 本系统深度打通 **DeepSeek-R1 / V3、GPT-4o、Claude 3.5 Sonnet、Qwen-Max** 等顶级大语言模型，并原生支持 **Dify、Coze、FastGPT、Flowise** 等 AI Agent 平台的标准 API 接入。
> 无论是微信私域爆粉、自动化客服、拟真朋友圈 SOP 运营，还是多账号矩阵式的销售转化，wx-bot4 都是您在微信生态中 7x24 小时不知疲倦的“金牌销售冠军”。

---

## 🌟 为什么选择 wx-bot4？(Core Selling Points)

针对市面上绝大多数微信机器人“易封号、不支持多开、API功能简陋、无法商业化贴牌”等致命痛点，wx-bot4 提供了以下维度升级的终极解决方案：

*   **⚡ 源码级授权与 OEM 贴牌**：提供前端 Web UI (SolidJS)、核心引擎 (FastAPI / UIA)、云端同步网关 (Rust Axum) 及移动端 APP (UniApp) 的 **全套干净源码**。支持修改品牌、主色调、域名及 Logo，完美契合软件服务商的商业化包装与私有化部署。
*   **🔌 强大的全量 OpenAPI & Webhook**：支持双向收发文本、多媒体文件（图片/语音/视频/文件）、小程序卡片、视频号，具备好友管理、建群拉群、群公告控制、朋友圈管理等 100+ 核心 API 接口，可与企业现有的 CRM、ERP、客服系统无缝整合。
*   **🛡️ 独家安全防封机制 (Anti-Ban Technology)**：自研的沙盒运行机制 (`Sandboxie-Plus` 完美集成) 与底层 UIA 通信模拟，支持独立 IP 代理池挂载与高拟真鼠标轨迹滑动、随机行为延迟算法。告别常规 Hook 协议引发的“微信异地登录”或“外挂封号”崩溃风险。
*   **🧠 销冠级 AI 销售对话 (AI Agent)**：不仅支持基础知识库检索（RAG），更内置了多行业高情商销售话术、主动意图挖掘、情绪识别与线索捕获 SOP，能够引导客户留下联系方式或跳转购买，实现私域全自动静默成交。

---

## 🛠️ 功能大盘 (All Features Overview)

### 1. 🤖 AI 数字员工与知识库 (AI Agent & RAG)
-   **全模型支持**：无缝对接 DeepSeek、OpenAI、Anthropic、智谱、文心、通义千问等主流 LLM，支持自定义 Prompt。
-   **企业级本地知识库**：支持上传 PDF, Word, TXT, Excel, Markdown 以及网页抓取，实现毫秒级高精度问答，不捏造事实。
-   **多行业 SOPPersona 模板**：预设金融、医美、电商、SaaS、教育等 20+ 行业销冠人设，一键切换。
-   **高情商销售漏斗**：自动捕捉客户聊天中的购买意向和预算，识别线索后自动触发提醒，并写入 SCRM。

### 2. 👥 矩阵式私域裂变与好友管理 (Matrix Growth)
-   **被动加粉自动通过**：被动好友申请秒级/随机延迟自动通过，同时调用 AI 自动发送精准首聊招呼语，打上来源标签。
-   **主动加人/批量检索**：支持导入手机号、微信号、QQ 号列表进行安全频次的主动检索与加好友。
-   **入群自动欢迎**：新群成员入群自动 @ 并发送多模态欢迎语、群规，智能踢除广告推销人员，支持群内关键词警报。

### 3. 🎡 朋友圈全自动 SOP 运营 (Moments Automation)
-   **矩阵定时发圈**：支持百号矩阵定时、多账号错峰自动发布朋友圈，支持图文、网页卡片、视频等格式。
-   **AI 自动撰写朋友圈**：AI 自动根据行业热点、核心卖点自动生成高质量朋友圈文案，自动配图。
-   **朋友圈拟真互动**：自动识别好友朋友圈的文字及情绪，进行点赞或极具人情味的回复评论，维持真人活跃度。

### 4. 📩 批量智能触达与分级群发 (Smart Broadcasting)
-   **标签分群群发**：严禁盲目群发！支持按 SCRM 的“意向标签”、“互动频次”、“客户等级”进行精准定向群发，转化率提升 300%。
-   **多模态混发**：支持文本、图片、网页卡片、视频、文件、甚至模拟语音消息的多模态内容依次发送。
-   **安全频次调度 V3**：高级群发调度引擎，支持定时、定量、分批、多微信号轮巡发送，规避封号风控。

### 5. 🔌 开放式 API & 外部集成 (OpenAPI & Integration)
-   **标准 RESTful API**：向外部开放全套管理端 API，轻松实现通过 API 远程控制微信发送消息、拉群、朋友圈操作。
-   **实时 Webhook 回调**：接收到的文本消息、好友申请、群异动、朋友圈更新等，均可实时 Webhook 推送给企业内部系统。
-   **Agent 平台无缝兼容**：支持以标准插件形式无缝挂载到 Dify、Coze、FastGPT、Flowise 等主流工作流引擎中。

---

## 🏗️ 全栈技术架构 (Technology Stack)

wx-bot4 采用模块化、高性能、低耦合的异步分布式架构设计：

```mermaid
graph TD
    User((微信客户端群/好友)) <--> Bridge[UIA Protocol Bridge 协议桥接]
    Bridge <--> Orchestrator{FastAPI 业务编排中心}
    Orchestrator <--> AIService[AI Engine / Dify / DeepSeek 语义引擎]
    Orchestrator <--> SCRM[SCRM 客户及标签管理]
    Orchestrator <--> Automation[Automation Moments/Task Handler]
    AIService --- KB[(矢量知识库 Vector DB)]
    Orchestrator <--> Cloud[Rust Axum 同步网关]
    Cloud --- DB[(PostgreSQL 核心数据库)]
    Automation --- Schedule[Task V3 调度引擎]
```

-   **前端 (Frontend)**: SolidJS + UnoCSS + Web-Socke（高效流畅，无虚拟 DOM 额外开销，打包体积极小）。
-   **核心引擎 (Core Backend)**: Python FastAPI + UIA Automation + Sandboxie-Plus（模拟真人操作首选）。
-   **云同步网关 (Cloud Gate)**: Rust Axum + PostgreSQL + Redis（实现分布式多账号配置统一下发、数据聚合）。
-   **移动端 (Mobile App)**: UniApp / UTS（方便销售人员随时随地用手机监控多账号状态）。

---

## 📸 产品界面展示 (Screenshots)

<div align="center">
  <img src="./images/ScreenShot_2026-06-06_044159_574.png" width="800" alt="wx-bot4 Dashboard" />
</div>

<details open>
  <summary><b>✨ 点击查看系统全功能截图 (100% 真实系统演示)</b></summary>
  <br>
  <img src="./images/ScreenShot_2026-06-06_044159_574.png" width="800" alt="screenshot" />
  <img src="./images/ScreenShot_2026-06-06_044222_006.png" width="800" alt="screenshot" />
  <img src="./images/ScreenShot_2026-06-06_044240_982.png" width="800" alt="screenshot" />
  <img src="./images/ScreenShot_2026-06-06_044251_496.png" width="800" alt="screenshot" />
  <img src="./images/ScreenShot_2026-06-06_044302_437.png" width="800" alt="screenshot" />
  <img src="./images/ScreenShot_2026-06-06_044311_021.png" width="800" alt="screenshot" />
  <img src="./images/ScreenShot_2026-06-06_044319_062.png" width="800" alt="screenshot" />
  <img src="./images/ScreenShot_2026-06-06_044347_983.png" width="800" alt="screenshot" />
  <img src="./images/ScreenShot_2026-06-06_044400_652.png" width="800" alt="screenshot" />
  <img src="./images/ScreenShot_2026-06-06_044453_093.png" width="800" alt="screenshot" />
  <img src="./images/ScreenShot_2026-06-06_044501_959.png" width="800" alt="screenshot" />
  <img src="./images/ScreenShot_2026-06-06_044515_862.png" width="800" alt="screenshot" />
  <img src="./images/ScreenShot_2026-06-06_044526_520.png" width="800" alt="screenshot" />
  <img src="./images/ScreenShot_2026-06-06_044536_042.png" width="800" alt="screenshot" />
  <img src="./images/ScreenShot_2026-06-06_044542_741.png" width="800" alt="screenshot" />
  <img src="./images/ScreenShot_2026-06-06_102824_269.png" width="800" alt="screenshot" />
  <img src="./images/ScreenShot_2026-06-06_103001_143.png" width="800" alt="screenshot" />
  <img src="./images/ScreenShot_2026-06-06_103137_089.png" width="800" alt="screenshot" />
  <img src="./images/ScreenShot_2026-06-06_103210_254.png" width="800" alt="screenshot" />
</details>

---

## 💼 商业合作与源码获取

wx-bot4 采用模块化开发，已在多家大中型企业和私域流量团队中稳定运行。我们现面向全球商业客户开放 **全套系统源码授权** 与 **API 调用商业授权**：

### 🎁 授权权益说明
1.  **🚀 核心包源码开放**：无保留提供 SolidJS 前端、FastAPI 后端核心引擎、Rust Axum 众包分发及 UniApp UTS 全部工程源码。
2.  **🔧 高级 API 接入及定制服务**：提供完整的对接文档、SDK、Webhook 配置样例，并支持定制化私有协议对接。
3.  **🏢 OEM 贴牌授权**：支持修改软件版权信息、去除我们系统的所有标志，更换为您专属的品牌名称与公司 Logo。
4.  **🎓 专家防封部署指导**：由xm-core团队资深架构师为您远程调试，提供沙盒部署及环境指纹隔离的保姆级方案。

> **立即联系我们，开启您的 AI 微信私域革命！**

### 📞 极速联系我们

| **微信咨询 (扫码添加)** | **QQ 咨询 (扫码添加)** |
| :---: | :---: |
| <img src="./images/mmqrcode1778317011693.png" width="250" alt="微信二维码" /> | <img src="./images/qq_qrcode.jpg" width="250" alt="QQ二维码" /> |
| **微信号：(请扫码查看)** | **QQ 号：3696205806** |

---

*© 2026 wx-bot4 Team (Powered by xm-core). All rights reserved.*
