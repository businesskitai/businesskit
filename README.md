# BusinessKit

BusinessKit is a native AI business operating system for retail, restaurants, hospitality, CRM, and accounting. AI agents are built into the core of the platform — not bolted on — with direct access to your operational data to automate work across every module. Built on a Bring Your Own Database (BYODB) architecture, so your business data stays in a database you own and control.

**Website:** [businesskit.io](https://businesskit.io)

---

## Download

Get the latest build from [Releases](https://github.com/businesskitai/businesskit/releases/latest).

| Platform | File |
|---|---|
| macOS | `.dmg` |
| Windows | `.msi` |
| iOS | `.ipa` (TestFlight / sideload) |
| Android | `.apk` / `.aab` |

Pick the asset for your OS from the latest release's Assets section.

## What's inside

- **AI Agent Hub** — autonomous agents with direct, secure access to your live business data. Multi-provider chat (Anthropic, OpenAI, Gemini, and more), a headless CLI runner for automated background execution (Claude Code, Antigravity, Codex), an interactive desktop terminal (PTY) for hands-on agent sessions, and a built-in MCP server that exposes the full BusinessKit toolbelt to external coding agents
- **Shop Suite** — retail, restaurant POS (tables, KOTs, recipes), hotel/stays (rooms, folios, rate calendar)
- **Finance & Tax** — double-entry accounting, bank reconciliation, GST/VAT/Sales Tax regimes, e-invoicing, e-way bills
- **CRM** — contacts, deals, activities, proposals, invoicing
- **Content & Social** — CMS, forms, job listings, social post scheduling

Every AI agent operates in strict isolation — scoped only to the active business profile's data, with zero access to other tenants or platform-level credentials.

## Bring Your Own Database (BYODB)

Every profile connects to its own Turso (SQLite) database. Your business data lives in a database you control — not a shared multi-tenant table you don't have access to.

## Installation notes

- **macOS**: if Gatekeeper blocks the app, right-click → Open on first launch.
- **Windows**: SmartScreen may warn on unsigned builds — click "More info" → "Run anyway."
- **Android**: enable "install from unknown sources" for sideloaded APKs.
- **iOS**: distributed via TestFlight invite until App Store release.

## Support

- Bug reports and issues: [GitHub Issues](https://github.com/businesskitai/businesskit/issues)
- Product updates and announcements: [businesskit.io](https://businesskit.io)

## License

© BusinessKit. All rights reserved. This repository distributes compiled application binaries only; source code is not included.
