<p align="center">
  <a href="https://fastagent.sh">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/fastagent-sh/fastagent/main/assets/logo.png">
      <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/fastagent-sh/fastagent/main/assets/logo-light.png">
      <img src="https://raw.githubusercontent.com/fastagent-sh/fastagent/main/assets/logo-light.png" alt="FastAgent" width="420">
    </picture>
  </a>
</p>

<h3 align="center">Take your agent from prototype to durable service.</h3>

<p align="center">
  The durable runtime and serving layer that turns your prompts, skills, and TypeScript tools into a live service — embedded in your app or served over HTTP behind one <a href="https://fastagent.sh/docs/agent-api/">Agent API</a>.
</p>

## FastAgent

[FastAgent](https://github.com/fastagent-sh/fastagent) ships the production backend every agent needs — durable sessions, crash recovery, resumable streaming, idempotent `POST /v1/invoke`, secret isolation, optional OS sandboxing (`--harness dsh`), OpenTelemetry traces, and deployment to Docker, Fly.io, Railway, or Amazon Bedrock AgentCore.

```bash
npm i -g @fastagent-sh/fastagent
fastagent init my-agent && cd my-agent
fastagent dev                 # serve locally with live reload
fastagent invoke "hello"      # send a message through the Agent API
```

[Website](https://fastagent.sh) ·
[Documentation](https://fastagent.sh/docs/) ·
[Architecture](https://fastagent.sh/docs/architecture/) ·
[GitHub](https://github.com/fastagent-sh/fastagent) ·
[npm](https://www.npmjs.com/package/@fastagent-sh/fastagent) ·
[Discussions](https://github.com/fastagent-sh/fastagent/discussions) ·
[Contributing](https://github.com/fastagent-sh/fastagent/blob/main/CONTRIBUTING.md) ·
[Security](https://github.com/fastagent-sh/fastagent/security/policy)
