# BusinessKit AI

BusinessKit is a native AI business operating system for retail, restaurants, hospitality, CRM, and accounting. AI agents are built into the core of the platform - not bolted on - with direct access to your operational data to automate work across every module. Built on a Bring Your Own Database (BYODB) architecture, so your business data stays in a database you own and control.

**Website:** [businesskit.io](https://businesskit.io)

---

## Download

Get the latest build from [Releases](https://github.com/businesskitai/businesskit/releases/latest).

| Platform | File |
| --- | --- |
| macOS | `.dmg` |
| Windows | `.msi` |
| Android | `.apk` |

Pick the asset for your OS from the latest release's Assets section.

## What's inside

- **AI Agent Hub** - autonomous agents with direct, secure access to your live business data. Multi-provider chat (Anthropic, OpenAI, Gemini, and more), a headless CLI runner for automated background execution (Claude Code, Antigravity, Codex), an interactive desktop terminal (PTY) for hands-on agent sessions, and a built-in MCP server that exposes the full BusinessKit toolbelt to external coding agents via [businesskit-agent](https://github.com/businesskitai/businesskit-agent).
- **Shop Suite** - retail, restaurant POS (tables, KOTs, recipes), hotel/stays (rooms, folios, rate calendar)
- **Finance & Tax** - double-entry accounting, bank reconciliation, GST/VAT/Sales Tax regimes, e-invoicing, e-way bills
- **CRM** - contacts, deals, activities, proposals, invoicing
- **Content & Social** - CMS, forms, job listings, social post scheduling

Every AI agent operates in strict isolation - scoped only to the active business profile's data, with zero access to other tenants or platform-level credentials.

## Autonomous Agent & MCP Workspace

Operate, manage, and automate your business from any external AI assistant or coding agent with the official BusinessKit Agent workspace:

👉 **[businesskitai/businesskit-agent](https://github.com/businesskitai/businesskit-agent)**

- **Claude Code**: `claude plugin add https://github.com/businesskitai/businesskit-agent`
- **Antigravity / Gemini CLI**: `agy plugin install https://github.com/businesskitai/businesskit-agent`
- **SuperConsole AI**: Install via URL in **Customize** → **Plugins** (`.superconsole-plugin/plugin.json`)
- **Cursor & VS Code**: Pre-configured with `.cursorrules`, 23 universal slash commands, and 11 domain workflow skills
- **Official MCP Registry**: [`io.github.businesskitai/agent`](https://registry.modelcontextprotocol.io) ([`@businesskit/agent`](https://www.npmjs.com/package/@businesskit/agent) on npm)

## Bring Your Own Database (BYODB)

Every profile connects to its own Turso (SQLite) database. Your business data lives in a database you control - not a shared multi-tenant table you don't have access to.

## Installation notes

- **macOS**: if Gatekeeper blocks the app, right-click → Open on first launch.
- **Windows**: SmartScreen may warn on unsigned builds - click "More info" → "Run anyway."
- **Android**: enable "install from unknown sources" for sideloaded APKs.
- **iOS**: distributed via TestFlight invite until App Store release.

## Modules & Ecosystem

- [BusinessKit Agent](https://github.com/businesskitai/businesskit-agent) - universal autonomous agent workspace, declarative skills, commands, and native MCP server
- [CRM](https://github.com/businesskitai/crm) - agent-first pipeline and deal management
- [GST ERP](https://github.com/businesskitai/gst-erp) - billing, inventory & GST compliance for India
- [B2B Commerce](https://github.com/businesskitai/b2b-commerce) - global B2B ordering, multi-currency & multi-tax

## Support

- Bug reports and issues: [GitHub Issues](https://github.com/businesskitai/businesskit/issues)
- Product updates and announcements: [businesskit.io](https://businesskit.io)

## License

© BusinessKit. All rights reserved. This repository distributes compiled application binaries only; source code is not included.
