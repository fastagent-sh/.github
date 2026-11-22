<p align="center">
  <a href="https://fastagent.sh">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/fastagent-sh/fastagent/main/assets/logo.png">
      <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/fastagent-sh/fastagent/main/assets/logo-light.png">
      <img src="https://raw.githubusercontent.com/fastagent-sh/fastagent/main/assets/logo-light.png" alt="FastAgent" width="420">
    </picture>
  </a>
</p>

<h3 align="center">Take your AI agent from prototype to production — without a black-box framework.</h3>

<p align="center">
  Open-source TypeScript &amp; Node.js runtime for embedded, background, and self-hosted AI agents. Embed in Next.js, Hono, or Express keeping your own auth and database — with durable sessions, idempotent webhooks, MCP tools, OS sandboxing, OpenTelemetry, and scale-to-zero deployment.
</p>

## FastAgent

[FastAgent](https://github.com/fastagent-sh/fastagent) lets you build agents with plain Markdown (`SYSTEM.md`, `AGENTS.md`, `skills/`) and typed TypeScript tools, then run them reliably in production — embedded in your Node.js app, on Docker / Fly.io / Railway, or in per-user AWS Bedrock AgentCore microVMs.

```bash
npm i -g @fastagent-sh/fastagent
fastagent init my-agent && cd my-agent
fastagent dev                 # serve locally with live reload
fastagent invoke "hello"      # send a message
```

[Website](https://fastagent.sh) ·
[Examples](https://github.com/fastagent-sh/fastagent/tree/main/examples) ·
[Documentation](https://fastagent.sh/docs/) ·
[Architecture](https://fastagent.sh/docs/architecture/) ·
[GitHub](https://github.com/fastagent-sh/fastagent) ·
[npm](https://www.npmjs.com/package/@fastagent-sh/fastagent) ·
[Discussions](https://github.com/fastagent-sh/fastagent/discussions)
