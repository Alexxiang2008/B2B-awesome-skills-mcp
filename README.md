# 🌐 B2B Awesome Skills & MCP

> **Powered by PanMira** - HLZD（海联智达）自研的 B2B 工业品出海 AI 数字底座
> 面向跨境 B2B 外贸的 Claude Skills 与 MCP Servers 精选合集：从客户挖掘、市场调研、SEO、广告到信用证审单，一站式 AI 能力索引。

[![Powered by PanMira](https://img.shields.io/badge/Powered%20by-PanMira-6e5494.svg)](#-关于-panmira-底座)
[![Awesome](https://img.shields.io/badge/Awesome-B2B-ff69b4.svg)](https://github.com/Alexxiang2008/B2B-awesome-skills-mcp)
[![Stars](https://img.shields.io/github/stars/Alexxiang2008/B2B-awesome-skills-mcp?style=social)](https://github.com/Alexxiang2008/B2B-awesome-skills-mcp)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](#-贡献指南)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](#-license)

> **来源标记**：`🔧 自研` = HLZD/PanMira 团队开发 ｜ `⭐ 精选` = 社区优质工具收录

---

## 📑 目录

- [🧭 关于 PanMira 底座](#-关于-panmira-底座)
- [🎯 场景索引](#-场景索引先按业务找工具)
- [🧩 Claude Skills](#-claude-skills)
  - [1. 客户开发 Lead Gen](#1-客户开发-lead-generation)
  - [2. 市场调研 Research](#2-市场调研-research)
  - [3. 内容与 SEO](#3-内容与-seo)
  - [4. 广告投放 Ads](#4-广告投放-ads)
  - [5. 邮件营销 Email](#5-邮件营销-email)
  - [6. 建站与设计 Web](#6-建站与设计-web)
  - [7. 跨境业务 Trade](#7-跨境业务-trade)
  - [8. 数据与文档 Data](#8-数据与文档-data)
  - [9. 通用工具 Utils](#9-通用工具-utils)
- [🔌 MCP Servers](#-mcp-servers)
- [🚀 快速开始](#-快速开始)
- [跨境 B2B 工作流示例](#跨境-b2b-工作流示例)
- [🤝 贡献指南](#-贡献指南)
- [📄 License](#-license)

---

## 🧭 关于 PanMira 底座

**PanMira 是 HLZD（海联智达）自研的 B2B 工业品出海 AI 数字底座** - 一个把 LLM 装进企业组织架构、让 AI 像员工一样按职能协作的 **AI Native Enterprise OS**。

本仓库收录的 Skills 与 MCP，即运行在 PanMira 底座之上的能力单元。核心设计理念：

| 特性 | 说明 |
|------|------|
| 🧠 **企业级记忆** | 组织公共区 / Bot 私域 / 用户私域 三层隔离，知识可沉淀、可 RAG 召回 |
| 🔥 **Skill 热加载** | Skills 以文件系统形式自动加载，触发器关键词自动路由，加一个 Skill = 多一个业务能力 |
| 👥 **AI 员工团队** | 通过 IM 直接召唤多个垂直 AI Agent，跑审证、报价、客户调研等手工活 |
| 🔀 **多模型共存** | 同一场景可切换 Anthropic / DeepSeek / 智谱等模型 |
| 🌏 **飞书原生集成** | WebSocket 长连接 + 卡片 / 文件 / Wiki / 多维表 原生打通 |

> 差异化：不是又一个 ChatGPT 套壳，而是把 AI 真正嵌进跨境贸易业务流程 - 例如**信用证审单**，可将数小时人工压缩到数十秒完成。

---

## 🎯 场景索引（先按业务找工具）

> 不用懂技术分类，你想做什么，直接查表。

| 我想做… | 推荐工具 | 类型 |
|---------|---------|------|
| 🔍 挖掘海外客户线索 | AI_Find_Customer · google-lead-hunter · b2b-lead-finder | Skill |
| 📊 竞品 / 市场调研 | reddit-research · customs-data-find · hlzd-market-intel | Skill + MCP |
| ✍️ SEO 内容与落地页 | seomachine · content-creator · programmatic-seo | Skill |
| 📣 Google Ads 投放 | google-ads-affiliate · autoads | Skill |
| 📧 外贸邮件序列 | hlzd-email-group · email-sequence · foreign-outreach | Skill |
| 🌍 官网 / 出海建站 | area-defense · industrial-export-design | Skill |
| 📜 信用证 / 单证审核 | hlzd-lc-review | Skill |
| 📁 数据与文档处理 | excel-analysis · pdf2excel · doc-to-markdown | Skill |

---

## 🧩 Claude Skills

### 1. 客户开发 Lead Generation

- **AI_Find_Customer** - 基于 FastAPI + LangGraph 的 AI 客户挖掘系统，自动完成「公司理解 → 关键词生成 → 网页搜索 → 线索提取 → 联系方式发现」全链路。 `Python` `LangGraph` `🔧 自研`
- **b2b-lead-finder** - 批量 B2B 潜客挖掘与竞争情报，按行业+城市搜索并爬取网站联系方式。 `⭐ 精选`
- **google-lead-hunter** - Google 批量抓取行业客户，网站爬取 + LinkedIn 富化。 `⭐ 精选`
- **google-maps-find** - 从 Google Maps 批量抓取本地商户线索。 `⭐ 精选`

### 2. 市场调研 Research

- **hlzd-market-intel** - 抓取 14+ 平台真实用户声音，输出 Top 痛点 + 用户原话报告，跨境 actionable。 `🔧 自研`
- **reddit-research-intelligence** - 语义搜索发现相关社区，分析真实用户痛点，生成带引用的调研报告。 `⭐ 精选`
- **customs-data-find** - 海关贸易数据检索，锁定进出口买家/卖家。 `⭐ 精选`
- **last30days** - 聚合 Reddit/X/YouTube/TikTok/HN 等平台近 30 天真实声音。 `⭐ 精选`

### 3. 内容与 SEO

- **seomachine** - 长文 SEO 博客内容工作区：研究 → 写作 → 分析 → 优化。 `Python` `🔧 自研`
- **content-creator** - SEO 优化内容创作，含品牌语调分析与社媒模板。 `⭐ 精选`
- **programmatic-seo** - 模板 + 数据批量生成 SEO 页面。 `⭐ 精选`

### 4. 广告投放 Ads

- **google-ads-affiliate** - Google Ads 联盟投放全流程：品牌筛选 → 尽调 → 关键词分组 → RSA 文案 → 预算分配。 `⭐ 精选`
- **autoads** - 广告自动化工具。 `TypeScript` `🔧 自研`
- **competitive-ads-extractor** - 抓取分析竞品广告库（Facebook/LinkedIn）创意与文案。 `⭐ 精选`

### 5. 邮件营销 Email

- **hlzd-email-group** - B2B 工业品外贸邮件序列生成器（开发信 + 跟进 + 培育），覆盖欧美/东南亚/日韩/中东。 `🔧 自研`
- **email-sequence** - 冷启动邮件序列设计。 `⭐ 精选`
- **foreign-outreach** - 海外客户开发触达。 `⭐ 精选`

### 6. 建站与设计 Web

- **area-defense** - B2B 安防解决方案出海官网模板（空天地一体化巡检）。 `TypeScript` `🔧 自研`
- **industrial-export-design** - 工业品跨境出海设计系统：产品页/落地页/询盘表单。 `🔧 自研`

### 7. 跨境业务 Trade

- **hlzd-lc-review** - 信用证（L/C）智能审单：文档识别 → 类型/角色判定 → 软条款扫描 → 不符点检测 → 银行国别风险 → 改单建议与谈判话术，内置 ICC UCP600 / ISBP745 / ISP98 / URDG758 规则库。 `🔧 自研`
- **hlzd-quote** - 跨境智能报价。 `🔧 自研`
- **hlzd-enquiry** - 询盘智能处理。 `🔧 自研`
- **hlzd-customer** - 客户画像与调研。 `🔧 自研`

### 8. 数据与文档 Data

- **hlzd-office-doc** - 企业级文档生成（Markdown → PDF/办公文档）。 `🔧 自研`
- **excel-analysis** - Excel 数据分析、透视表、图表生成。 `⭐ 精选`
- **pdf2excel** - PDF 报价单/表格 → 格式化 Excel。 `⭐ 精选`
- **doc-to-markdown** - 各类文档转 Markdown。 `⭐ 精选`

### 9. 通用工具 Utils

- **everything-search** - 统一搜索平台，自动路由 EXA/OpenCLI/SearXNG/gh CLI。 `🔧 自研`
- **claude-code-agents** - 生产就绪的 Claude Code 子代理合集。 `🔧 自研`
- **Original-Skills-Creator** - Claude Skill 快速创建器。 `🔧 自研`

---

## 🔌 MCP Servers

> Model Context Protocol 服务，为 AI 提供实时数据与工具能力。

| MCP Server | 能力 | 来源 |
|-----------|------|------|
| **Redbook-mcp** | 小红书个人/企业 IP 智能运营 | `Go` `🔧 自研` |
| **context7** | 实时拉取最新库/框架文档 | `⭐ 精选` |
| **exa** | 语义化网页搜索与内容抓取 | `⭐ 精选` |
| **Playwright** | 浏览器自动化（测试/抓取/表单） | `⭐ 精选` |
| **[Xquik](https://docs.xquik.com/mcp/overview)** | X/Twitter 市场调研、账号与趋势搜索、受众数据导出、监控及 Webhook 工作流；独立第三方服务，与 X Corp. 无关联 | `Streamable HTTP` `OAuth 2.1` `⭐ 精选` |

Xquik is an independent third-party service. Not affiliated with X Corp. "Twitter" and "X" are trademarks of X Corp.

---

## 🚀 快速开始

以 Claude Code 接入一个 Skill 为例：

```bash
# 1. 克隆本仓库或目标 Skill
git clone https://github.com/Alexxiang2008/B2B-awesome-skills-mcp.git

# 2. 将 Skill 放入 Claude 的 skills 目录
cp -r <skill-name> ~/.claude/skills/

# 3. 在 Claude Code 中调用
/<skill-name>
```

> 在 PanMira 底座中，Skills 以文件系统形式自动加载，飞书 Bot 可通过 Skill Hub 可视化安装/卸载。
> MCP Server 接入请参考各服务目录下的 `README`，在客户端配置中注册。

---

## 跨境 B2B 工作流示例

**场景：从 0 到 1 开发一个海外新市场**

```
① 市场调研      hlzd-market-intel + customs-data-find
        ↓  锁定目标行业与买家画像
② 客户挖掘      AI_Find_Customer + google-lead-hunter
        ↓  批量获取线索与联系方式
③ 触达转化      hlzd-email-group（邮件序列）
        ↓  同步投放
④ 流量放大      google-ads-affiliate + seomachine（SEO）
        ↓
⑤ 承接转化      industrial-export-design（落地页/询盘表单）
        ↓
⑥ 单证风控      hlzd-lc-review（信用证审单）
```

> 每个环节都可用本仓库工具串联，在 PanMira 底座上形成「调研 → 获客 → 触达 → 放大 → 转化 → 风控」的完整飞轮。

---

## 🤝 贡献指南

欢迎 PR！收录标准：

- ✅ **相关性**：服务于跨境 B2B / 工业品出海场景
- ✅ **可用性**：有清晰文档，能实际跑通
- ✅ **格式**：条目遵循「名称 + 一句话价值 + 技术标签 + 来源标记」
- ✅ **去重**：同类工具优先补充差异，而非重复收录

提交方式：Fork → 编辑 README → 发起 Pull Request，并在描述中说明推荐理由。

---

## 📄 License

[MIT](LICENSE) © [HLZD · PanMira](https://github.com/Alexxiang2008)
