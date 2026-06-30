# 你好，我是 Kris（吴鹏飞）👋

**AI Infra Lead @ 猿辅导（看云 / Kanyun）** · 北京
GitHub [@krislavten](https://github.com/krislavten) · X [@kris_wpf](https://x.com/kris_wpf)

🌏 **[English →](./README.md)**

> 从可观测工程师，到 AI 工程师。我只做一件事：把 AI 原生开发真正缺的那层基础设施补上。

我不做模型，只啃 AI Agent 落地时的工程问题：怎么让它跑起来、跑得对、出了岔子还能查。这些工具我自己每天都在用。

## 🚀 在做什么

### 平台

- **agenthub**（Pilot v2）：自研的托管 Agent 平台。Claude Code / Codex 跑在隔离沙箱里，端到端把编程任务做完（直接出 PR/MR），也能跑通用任务。底层做了四层资源模型（Project / Workload / Revision / Session）、凭据 Vault、可续传的 SSE、平台级的 Profile 版本管理，现在线上 100% 流量都走它。SDK：`@kanyun-ai-infra/agenthub`。
- **Rush**：公司的企业级 AI 应用 / Agent 平台，把想要什么说清楚，就能拿到一个带实时预览的完整 Web 应用。内部跑到现在累计 **17,000+ 项目、3,000+ 用户、50 万+ 条消息**，每月稳定有约 1,000 人在建项目，平台上沉淀了 400+ 个 Agent。我是核心维护者（512 个 PR）。
- **[OpenRush](https://github.com/kanyun-rush/open-rush)**：开源、能自己部署的 Claude Code 托管 Agent 平台，沙箱执行、Agent/Skill/MCP registry、双层凭据 Vault、流式事件协议一应俱全。

### Agent 工具链（CLI + MCP）

为了让 AI Agent 真能上手操作生产系统，我做了一组 CLI + MCP，都发到了 npm：

- **octo-cli**：可观测性，查日志、告警、链路、指标、RUM、拓扑
- **conso-cli**：Console 平台运维，管部署、服务、Pod、资源
- **docz-cli** / **rush-shimo-cli**：读写公司文档（DocSync / 石墨）
- **jira-cli**：给 Agent 用的 Jira，管 issue、sprint、board
- **qlint**：可观测查询的 linter，帮 Agent 写出正确的查询语句

### 技能、质量与基建

- **reskill**（共建）：AI Agent 的技能包管理器，用起来像 npm，`npx reskill install`
- **agent-aware**：让 Agent「看见」用户在网页里的操作（点击、滚动、卡壳），据此自动修
- **[Sparring](https://github.com/krislavten/sparring)**：对抗式的 AI 代码审查插件，让另一个 AI（Cursor / Codex / GLM / Claude）专挑 Claude 写的代码的毛病
- **[cowork-mdm](https://github.com/krislavten/cowork-mdm)**：Claude Desktop 的企业批量部署工具，逆向出了 51 个 MDM 配置项
- **rush-plugin · claude-env · env-sync**：日常工作流和环境管理的小工具

### 闭环

- **TentaClaw**：想把闭环做到写代码之外——Issue → Code → Deploy → Observe → Feedback 一整圈，每个 repo 配一个自己的 Agent。

## 🧭 怎么干活

- **工具自己造，也自己用。** Rush、agenthub、OpenRush 本身就是我用 AI Agent（Claude Code + Cursor）写出来的，质量靠 Sparring 把关。造和用之间几乎没有时差。
- **先有验证器，再谈怎么做；环境设计优先于中央调度。** 先把「怎么算做对了」想清楚，再让多个 Agent 在同一套环境里各跑各的、自然协作，而不是立一个中心去指挥。
- **节奏：** 2026 上半年提了约 971 个 PR、2,100 次 commit，光 Rush 一个仓就占 512 个。

## 🛠 之前在做什么

转 AI 之前，我花了四年做 **Octopus**——公司级的可观测平台（RUM、Logs、Trace、Alerts、LLM Observability）。所以轮到我做 AI Infra 时，「可观测」这一环不是凭空补的，是从生产里实打实踩出来的。

## 💻 技术栈

`TypeScript` · `Node.js` · `React` · `Next.js` · `Hono` · `PostgreSQL` · `Redis` · `Docker` · `K8s`
`Claude Agent SDK` · `AI SDK` · `MCP` · `Codex` · `OpenTelemetry` · `pnpm/turborepo`

## 📫 找我

- 邮箱 — [adwerrd@hotmail.com](mailto:adwerrd@hotmail.com)
- X — [@kris_wpf](https://x.com/kris_wpf)
- 小红书 — @kriiswu
