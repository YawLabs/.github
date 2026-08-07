# Yaw Labs

Developer tools for the terminal, AI, and cloud infrastructure.

---

### Products

**[Yaw Terminal](https://yaw.sh)** -- Cross-platform terminal emulator with built-in AI (9 providers), SSH/database connections (6 types), and a file editor. Free, zero telemetry.

**[Yaw Mode](https://yaw.sh/blog/claude-code-yaw-mode)** -- Per-session overlay that layers an opinionated bundle of rules, skills, and agents onto Claude Code without touching your `~/.claude/`. Two modes: **Augment** keeps your own config and adds ours on top; **Fresh** runs only the bundle. Ships inside Yaw Terminal -- toggle in Settings.

**[Yaw MCP](https://yaw.sh/mcp/)** -- MCP servers, managed locally. One CLI discovers, installs, and runs servers from a public catalog -- no account required. Smart routing, an 88-test compliance grade on every server, and cross-machine bundle sync on Pro.

**[typed](https://typed.cloud)** -- An AI CLI with more token volume per dollar and cheaper top-ups for extra usage.

---

### Books

**[MCP in Production](https://yaw.sh/mcp-in-production/)** -- The practitioner's guide to building and running Model Context Protocol servers in production. Twelve chapters drawn from shipping fourteen `@yawlabs/*` servers -- protocol, transport, schema design, auth, error handling, testing, hosting, security, and four case studies. PDF + EPUB. Free with a Token Limit News signup.

---

### Open Source

| Project | Description | Quick Start |
|---------|-------------|-------------|
| [oam](https://github.com/YawLabs/oam) | A JavaScript and TypeScript runtime built in Rust on V8 — strips and runs TypeScript instantly while a `tsgo` sidecar streams full type diagnostics concurrently, with structured ODIF output agents consume directly. Pre-alpha. | `curl -fsSL https://oamjs.org/install.sh \| sh` |
| [mcp](https://github.com/YawLabs/mcp) | One install, all your MCP servers, managed. The orchestrator for Yaw MCP — smart routing, auto-import, health-aware dispatch. | `npx @yawlabs/mcp install <claude-code\|claude-desktop\|cursor\|vscode>` |
| [mcp-compliance](https://github.com/YawLabs/mcp-compliance) | Test any MCP server for spec compliance. 88 tests across 8 categories, A-F grading, works against HTTP and stdio. | `npx @yawlabs/mcp-compliance` |
| [ctxlint](https://github.com/YawLabs/ctxlint) | Lint AI context files (CLAUDE.md, AGENTS.md, .cursorrules) against your codebase. | `npx @yawlabs/ctxlint` |
| [aws-mcp](https://github.com/YawLabs/aws-mcp) | AWS MCP server — fixes the SSO browser-spawn drop, generic CRUD over hundreds of resource types, sits next to AWS Labs' per-service servers. | `npx @yawlabs/aws-mcp` |
| [postgres-mcp](https://github.com/YawLabs/postgres-mcp) | Read-only-by-default Postgres MCP server. Query, introspect schemas, explain plans, health checks. Replaces the deprecated reference server. | `npx @yawlabs/postgres-mcp` |
| [redis-mcp](https://github.com/YawLabs/redis-mcp) | Redis MCP server — SCAN-based key exploration, TTL/memory/keyspace introspection, slowlog + INFO health, and a DBA advisor. | `npx @yawlabs/redis-mcp` |
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

---

### Links

[yaw.sh](https://yaw.sh) -- [Token Limit News](https://tokenlimit.news) (weekly AI tooling newsletter) -- [LinkedIn](https://www.linkedin.com/company/yaw-labs/) -- [Reddit](https://www.reddit.com/r/YawLabs/)
