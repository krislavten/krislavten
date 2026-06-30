# Hi, I'm Kris 👋

**AI Infra Lead @ Yuanfudao (猿辅导 / Kanyun)** · Beijing
GitHub [@krislavten](https://github.com/krislavten) · X [@kris_wpf](https://x.com/kris_wpf)

🌏 **[中文版本 →](./README.zh-CN.md)**

> From observability engineer to AI engineer — building the infrastructure that makes AI-native software development possible.

I don't train models — I build the ground that lets AI agents run, run correctly, and stay observable. And I'm the heaviest user of my own tools.

## 🚀 What I'm Building

### Platforms

- **agenthub** (Pilot v2) — Self-built **managed-agents platform**: sandboxed Claude Code / Codex agents running coding (Git → PR/MR) and general (artifacts) tasks end-to-end. Four-layer resource model (Project / Workload / Revision / Session), credential Vault, resumable SSE, platform-level versioned Profile Registry — now serving **100% of production traffic**. SDK: `@kanyun-ai-infra/agenthub`.
- **Rush** — Enterprise AI app/agent platform: describe what you want, get a full web app with live preview. **17,000+ projects, 3,000+ users, 500K+ messages** internally; ~1,000 monthly active creators, 400+ agents. Core maintainer (512 PRs).
- **[OpenRush](https://github.com/kanyun-rush/open-rush)** — Open-source, self-hosted managed-agents platform for Claude Code: sandboxed execution, Agent/Skill/MCP registry, dual-layer credential Vault, streaming event contract.

### Agent Toolchain — CLI + MCP

Tools so AI agents can operate real systems — all published to npm:

- **octo-cli** — Observability (logs / alerts / traces / metrics / RUM / topology)
- **conso-cli** — Console-platform ops (deploy / services / pods / resources)
- **docz-cli** / **rush-shimo-cli** — Company-docs access (DocSync / Shimo)
- **jira-cli** — Jira for agents (issue / sprint / board)
- **qlint** — Observability query linter — helps agents generate correct queries

### Skills, Quality & Infra

- **reskill** *(co-built)* — Git-based skills package manager for AI agents — `npx reskill install`
- **agent-aware** — Lets agents perceive user behavior (clicks / scroll / frustration) in web apps
- **[Sparring](https://github.com/krislavten/sparring)** — Adversarial AI code-review plugin: a second AI (Cursor / Codex / GLM / Claude) hunts bugs in Claude's output
- **[cowork-mdm](https://github.com/krislavten/cowork-mdm)** — Claude Desktop enterprise deployment toolkit (reverse-engineered 51 MDM keys)
- **rush-plugin · claude-env · env-sync** — Workflow & dev-env tooling

### Loop

- **TentaClaw** — Closing the loop beyond coding: Issue → Code → Deploy → Observe → Feedback, one agent per repo.

## 🧭 How I Work

- **I build the tools and live in them.** Rush, agenthub and OpenRush are themselves built by AI agents (Claude Code + Cursor), with Sparring as the quality gate — a tight build/use feedback loop.
- **Verifier-first; environment design over central orchestration.** Define "how to verify it's correct" first, then let multiple agents self-coordinate through a shared environment instead of a central orchestrator.
- **Pace:** ~971 PRs / ~2,100 commits in H1 2026 (512 on Rush alone).

## 🛠 Background

Before AI, 4 years building **Octopus** — Yuanfudao's company-wide observability platform (RUM / Logs / Trace / Alerts / LLM Observability). That's why the "Observe" loop is grounded in real production pain, not theory.

## 💻 Tech

`TypeScript` · `Node.js` · `React` · `Next.js` · `Hono` · `PostgreSQL` · `Redis` · `Docker` · `K8s`
`Claude Agent SDK` · `AI SDK` · `MCP` · `Codex` · `OpenTelemetry` · `pnpm/turborepo`

## 📫 Connect

- Email — [adwerrd@hotmail.com](mailto:adwerrd@hotmail.com)
- X — [@kris_wpf](https://x.com/kris_wpf)
- 小红书 — @kriiswu
