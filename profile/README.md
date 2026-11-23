<p align="center">
  <a href="https://fastagent.sh">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/fastagent-sh/fastagent/main/assets/logo.png">
      <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/fastagent-sh/fastagent/main/assets/logo-light.png">
      <img src="https://raw.githubusercontent.com/fastagent-sh/fastagent/main/assets/logo-light.png" alt="FastAgent" width="380">
    </picture>
  </a>
</p>

<h3 align="center">The TypeScript runtime for production AI agents.</h3>

<p align="center">
  Write agents in plain Markdown, typed TypeScript tools, and MCP — built for engineers and coding agents.<br>
  Package as an npm artifact, embed in your Node.js app, self-host with Docker, or deploy to Fly.io, Railway, and AWS.
</p>

<p align="center">
  <a href="https://www.npmjs.com/package/@fastagent-sh/fastagent"><img src="https://img.shields.io/npm/v/@fastagent-sh/fastagent.svg" alt="npm version"></a>
  <a href="https://github.com/fastagent-sh/fastagent/blob/main/LICENSE"><img src="https://img.shields.io/npm/l/@fastagent-sh/fastagent.svg" alt="MIT License"></a>
  <a href="https://github.com/fastagent-sh/fastagent/stargazers"><img src="https://img.shields.io/github/stars/fastagent-sh/fastagent?style=social" alt="GitHub stars"></a>
  <a href="https://x.com/kid7st"><img src="https://img.shields.io/badge/follow-%40kid7st-000?logo=x" alt="follow @kid7st"></a>
</p>

<p align="center">
  <a href="https://fastagent.sh/docs/quickstart/"><strong>Quickstart</strong></a> ·
  <a href="https://github.com/fastagent-sh/fastagent/tree/main/examples">Examples</a> ·
  <a href="https://fastagent.sh/docs/">Docs</a> ·
  <a href="https://fastagent.sh/docs/architecture/">Architecture</a> ·
  <a href="https://github.com/fastagent-sh/fastagent/discussions">Discussions</a>
</p>

<p align="center">
  <a href="https://github.com/fastagent-sh/fastagent">
    <img src="https://cdn.jsdelivr.net/gh/fastagent-sh/fastagent@main/assets/demo.svg" alt="FastAgent workflow: write in Markdown and TypeScript, run locally with durable sessions, invoke via CLI or HTTP webhook, and deploy to any host." width="820">
  </a>
</p>

## What we build

| Project | Role | Status |
| --- | --- | --- |
| [**`fastagent`**](https://github.com/fastagent-sh/fastagent) | Open-source TypeScript & Node.js runtime (`openAgent`, CLI, durable sessions, resumable SSE, idempotent webhooks, OS sandboxing, AWS AgentCore). | Active · MIT |
| [**`kage`**](https://github.com/fastagent-sh/kage) | Native, local-first macOS workbench for FastAgent — assign work, follow long runs, and resume sessions directly from the runtime. | Early preview |
| [**`ai-agent-stack`**](https://github.com/fastagent-sh/ai-agent-stack) | Daily index measuring 2,700+ open-source AI agent projects across 16 layers — classified by a live FastAgent agent. | Updated daily |
| [**`pi-deepseek-tools`**](https://github.com/fastagent-sh/pi-deepseek-tools) | DeepSeek Search and Fetch APIs packaged as Pi tools. | Open source |

## Start in 60 seconds

```bash
npm i -g @fastagent-sh/fastagent
fastagent init my-agent && cd my-agent
fastagent dev                 # local server with hot reload & SQLite durability
fastagent invoke "hello"      # call through the Agent API
```

**Building with Claude Code, Codex, Cursor, or Pi?** Paste this into your coding agent:

> Read https://fastagent.sh/start.md and build an agent in this project.

## Production blueprints

Runnable end-to-end templates in [`fastagent/examples`](https://github.com/fastagent-sh/fastagent/tree/main/examples):

- [**Multi-Tenant SaaS Copilot**](https://github.com/fastagent-sh/fastagent/tree/main/examples/saas-copilot) — embedded in Hono with a shared PostgreSQL pool
- [**Sandboxed PR Review Agent**](https://github.com/fastagent-sh/fastagent/tree/main/examples/pr-review-agent) — read-only OS sandbox + GitHub Actions
- [**Sleep-When-Idle AI SRE**](https://github.com/fastagent-sh/fastagent/tree/main/examples/incident-triage-agent) — Fly.io scale-to-zero, webhook deduplication, live `steer`
- [**Per-User AWS MicroVM Agent**](https://github.com/fastagent-sh/fastagent/tree/main/examples/agentcore-per-user) — Amazon Bedrock AgentCore + Aurora DSQL

---

<sub>
  <strong>Open source &amp; Cloud:</strong> FastAgent is MIT-licensed and free to self-host forever.
  Prefer managed hosting? <a href="https://tally.so/r/44DVMB">Join the FastAgent Cloud waitlist →</a>
</sub>
