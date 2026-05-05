# Yaw Labs

Developer tools for the terminal, AI, and cloud infrastructure.

---

### Products

**[Yaw Terminal](https://yaw.sh)** -- Cross-platform terminal emulator with built-in AI (9 providers), SSH/database connections (6 types), and a file editor. Free, zero telemetry.

**[Claude Code Yaw Mode](https://yaw.sh/blog/claude-code-yaw-mode)** -- Per-session overlay that layers an opinionated bundle of rules, skills, and agents onto Claude Code without touching your `~/.claude/`. Two modes: **Augment** keeps your own config and adds ours on top; **Fresh** runs only the bundle. Ships inside Yaw Terminal -- toggle in Settings.

**[mcp.hosting](https://mcp.hosting)** -- MCP is the USB-C for LLM tool use. One config in the cloud, syncs to every MCP client you use. Smart routing, an 88-test compliance grade on every server, and a free tier for up to 3 servers.

---

### Books -- The Yaw Labs Production Series

Four books on the discipline of shipping AI tooling -- the work that separates "I built it" from "I run it in production." PDF + EPUB. Free updates.

| Volume | Title | About |
|--------|-------|-------|
| I | [MCP in Production](https://yaw.sh/mcp-in-production/) | The practitioner's guide to building and running Model Context Protocol servers in production. Twelve chapters drawn from shipping fourteen `@yawlabs/*` servers -- protocol, transport, schema design, auth, error handling, testing, hosting, security, and four case studies. |
| II | [Claude Code in Production](https://yaw.sh/claude-code-in-production/) | The power user's guide to shipping production software with Claude Code. Twelve chapters of operator-side discipline -- the CLAUDE.md contract, the harness, subagents, memory, capacity, scope, the seven hazards, and what survives across teams. |
| III | [Semantic Search in Production](https://yaw.sh/semantic-search-in-production/) | The practitioner's guide to shipping retrieval after the v0. Twelve chapters on hybrid search, eval discipline, drift, and re-embedding -- the work nobody warned you about. |
| IV | [A2A in Production](https://yaw.sh/a2a-in-production/) (early access) | The discipline guide to running multi-agent systems after the v0. Twelve chapters on orchestration, auth across agent boundaries, federated memory, and partial failure -- four readable today, eight as drafts complete. |

---

### Open Source

| Project | Description | Quick Start |
|---------|-------------|-------------|
| [mcph](https://github.com/YawLabs/mcph) | One install, all your MCP servers. The local agent for mcp.hosting — smart routing, auto-import, health-aware dispatch. | `npx @yawlabs/mcph install <claude-code\|claude-desktop\|cursor\|vscode>` |
| [mcp-compliance](https://github.com/YawLabs/mcp-compliance) | Test any MCP server for spec compliance. 88 tests across 8 categories, A-F grading, works against HTTP and stdio. | `npx @yawlabs/mcp-compliance` |
| [ctxlint](https://github.com/YawLabs/ctxlint) | Lint AI context files (CLAUDE.md, AGENTS.md, .cursorrules) against your codebase. | `npx @yawlabs/ctxlint` |
| [aws-mcp](https://github.com/YawLabs/aws-mcp) | AWS MCP server — fixes the SSO browser-spawn drop, generic CRUD over hundreds of resource types, sits next to AWS Labs' per-service servers. | `npx @yawlabs/aws-mcp` |
| [postgres-mcp](https://github.com/YawLabs/postgres-mcp) | Read-only-by-default Postgres MCP server. Query, introspect schemas, explain plans, health checks. Replaces the deprecated reference server. | `npx @yawlabs/postgres-mcp` |
| [tailscale-mcp](https://github.com/YawLabs/tailscale-mcp) | MCP server for managing Tailscale tailnets. 89 tools covering the full Tailscale v2 API, HuJSON-safe ACLs. | `npx @yawlabs/tailscale-mcp` |
| [fetch-mcp](https://github.com/YawLabs/fetch-mcp) | Comprehensive HTTP fetch MCP server with SSRF protection, HTML-to-markdown, reader-mode extraction, and robots.txt awareness. | `npx @yawlabs/fetch-mcp` |
| [ssh-mcp](https://github.com/YawLabs/ssh-mcp) | SSH operations with built-in diagnostics for AI assistants. | `npx @yawlabs/ssh-mcp` |
| [npmjs-mcp](https://github.com/YawLabs/npmjs-mcp) | npm registry intelligence — package info, versions, downloads, security audits. | `npx @yawlabs/npmjs-mcp` |
| [lemonsqueezy-mcp](https://github.com/YawLabs/lemonsqueezy-mcp) | Manage your LemonSqueezy store from AI assistants. Products, variants, subscriptions, webhooks. | `npx @yawlabs/lemonsqueezy-mcp` |
| [electron-mcp](https://github.com/YawLabs/electron-mcp) | Electron.js MCP server — IPC scaffolding, security auditing, build tooling. | `npx @yawlabs/electron-mcp` |
| [caddy-mcp](https://github.com/YawLabs/caddy-mcp) | MCP server for managing Caddy web server from AI assistants. | `npx @yawlabs/caddy-mcp` |
| [electron-optimize](https://github.com/YawLabs/electron-optimize) | Drop-in optimization utilities for Electron apps. | `npm i @yawlabs/electron-optimize` |
| [a2a-webhook-security](https://github.com/YawLabs/a2a-webhook-security) | A2A Webhook Security Profile (AWSP) — open spec plus reference implementations in TS, Python, Go, Java, and .NET. | [Spec + reference impls](https://github.com/YawLabs/a2a-webhook-security) |
| [lemonsqueezy-webhook-sink](https://github.com/YawLabs/lemonsqueezy-webhook-sink) | Durable webhook sink for LemonSqueezy — HMAC verify, SQLite dedupe, pull-based reconciliation. | [Docs](https://github.com/YawLabs/lemonsqueezy-webhook-sink) |
| [mcp-hosting-deploy](https://github.com/YawLabs/mcp-hosting-deploy) | Self-host mcp.hosting with Docker Compose, Helm, CloudFormation, or Terraform. Team subscription required. | [Docs](https://github.com/YawLabs/mcp-hosting-deploy) |

---

### Links

[yaw.sh](https://yaw.sh) -- [Token Limit News](https://tokenlimit.news) (weekly AI tooling newsletter) -- [Forum](https://forum.yaw.sh) -- [LinkedIn](https://www.linkedin.com/company/yaw-labs/) -- [Reddit](https://www.reddit.com/r/YawLabs/)
