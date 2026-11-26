## Red Center Studio

A small remote studio that builds custom apps, fast websites and AI agents as code that runs in your own Cloudflare account. No platform rent, and you own what we build.

Website: https://redcenterstudio.com

### Claude connectors

Remote MCP servers you add to Claude as custom connectors. Addresses and setup steps: [claude-connectors](https://github.com/Red-Center-Studio/claude-connectors).

- **WebDesk for Claude:** build, preview and publish a small business website from Claude, with a quote form and an enquiry inbox. https://redcenterstudio.com/webdesk/claude/
- **Site Watch:** website monitoring for domain and certificate expiry, DNS and email records, AI crawler access and uptime. https://redcenterstudio.com/sitewatch/
- **VaultSheet:** fills security questionnaires from answers your team approved, word for word. https://redcenterstudio.com/vaultsheet/
- **Free website checks:** GEO audit, domain health, AI crawler access, single point of failure scan and Bubble® error decoder, no sign-in. https://redcenterstudio.com/claude-connectors/website-checks/
- **Bubble to Cloudflare App & Data Migrator:** moves a Bubble app's UI, backend, D1 database, and R2 files into your own Cloudflare account, with a free audit and 10-page preview (Small $159, Standard $299, Large $389, Developer mode $45 USD; data-only passes from $39 USD; done-for-you from $899 USD). Sign-in email goes through Cloudflare by default, and service keys are optional. https://redcenterstudio.com/app-mover/ and https://redcenterstudio.com/app-mover/?tab=data#run

### Systems we built and run

These run on Cloudflare in their own accounts. Three of them started on Bubble® and were moved with App Mover, our DIY migration of a Bubble app to the customer's own Cloudflare account.

- **SharehouseHub:** a live share housing platform for Australia, cut over from Bubble on 20 Nov 2026 with 7,999 of 7,999 records verified. Case study: https://redcenterstudio.com/work/sharehousehub/
- **TradeCatcher:** missed-call text-back, photo job intake and AI quote drafting for Australian trades businesses, moved on 23 and 24 Nov 2026 (home page HTML time to first byte 360 ms on Bubble, 101.3 ms on Cloudflare; 4,070 of 4,070 records verified). Sign-in email now goes out through Cloudflare. Case study: https://redcenterstudio.com/work/tradecatcher/
- **MyCircleHub:** a private social app for families and small groups, live on its own domain on Cloudflare. It was moved without its data because the source app had no Data API. Case study: https://redcenterstudio.com/work/mycirclehub/

How App Mover works, what it costs and what you own: https://redcenterstudio.com/app-mover/ . Moved apps send sign-in email through Cloudflare by default when the domain is in your Cloudflare account; email and other service keys are optional.

### Public repositories

- [bubble-to-cloudflare-migrator](https://github.com/Red-Center-Studio/bubble-to-cloudflare-migrator): standalone Bubble® to Cloudflare migration plugin (Claude Code & Antigravity), walkthrough video, and visual parity examples.
- [claude-connectors](https://github.com/Red-Center-Studio/claude-connectors): addresses, setup steps and MCP Registry metadata for every connector above.
- [claude-plugins](https://github.com/Red-Center-Studio/claude-plugins): a Claude plugin marketplace with the free website checks, WebDesk for Claude, Site Watch, VaultSheet, WebDesk websites built by an agent, the Bubble® to Cloudflare migrator, and the no-code app audit. Add it in Claude Code with `/plugin marketplace add Red-Center-Studio/claude-plugins`.
- [agent-tollbooth-402](https://github.com/Red-Center-Studio/agent-tollbooth-402): HTTP 402 & x402 V2 billing and Stripe Fiat Agent Wallets for Cloudflare Workers, Hono, Next.js, and MCP servers.
- [nocode-migration-audit](https://github.com/Red-Center-Studio/nocode-migration-audit): a free, read-only audit skill for Claude Code. It reads a no-code app's structure and writes a plain-language report and a neutral app spec. Bubble is supported today.
- [prestart-lite](https://github.com/Red-Center-Studio/prestart-lite): daily vehicle pre-start checks and a defect workflow for small fleets, on Cloudflare Workers.
- [catchdesk-lite](https://github.com/Red-Center-Studio/catchdesk-lite): enquiries with photos and quotes customers accept online, for small service businesses, on your own Cloudflare account.
- [sharehouse-manager-lite](https://github.com/Red-Center-Studio/sharehouse-manager-lite): rent, shared bills, chores, repairs and house rules for one shared house, on your own Cloudflare account.
- [stockroom-lite](https://github.com/Red-Center-Studio/stockroom-lite): free, open-source stock tracking for vans, storerooms, shelves and kits, on your own Cloudflare account.
- [webdesk-mcp](https://github.com/Red-Center-Studio/webdesk-mcp): WebDesk MCP server information for AI agents that build small business websites: client examples, docs links and MCP Registry metadata.
- [rcs-agent-skills](https://github.com/Red-Center-Studio/rcs-agent-skills): free Agent Skills (`SKILL.md`) for Claude Code, Cursor, and Antigravity, including `geo-audit`.

### Apps we rebuilt as code we own

PreStart, CatchDesk, StockRoom and Sharehouse Manager started on Bubble and now run as owned code on Cloudflare. Live demos: https://redcenterstudio.com/services/no-code-app-porting/#rebuilds

### Free tools

A GEO audit and a single point of failure scanner: https://redcenterstudio.com/tools/

Bubble is a registered trademark of Bubble Group, Inc. Red Center Studio is not affiliated with, endorsed by or certified by Bubble or Anthropic. Cloudflare and Workers are trademarks of Cloudflare, Inc.
