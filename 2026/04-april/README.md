# April 2026

Infrastructure-and-glue month. The stealth browser stack went public as two
companion repos, the OpenBao sidecar pattern was extracted into its own project,
AI code review went org-wide, and a single-file schema audit tool shipped.

## Public Projects Shipped

**arc-browser**
Stealth browser automation MCP for Claude Code. Session pool, anti-detection,
human-like interaction, autonomous browsing. 21 tools exposed over MCP. Pairs
with the Camofox Firefox sidecar - drop the renamed `ghost-browser` history,
this is the productionized agent-facing surface.

**camofox-browser**
Stealth headless Firefox for AI agents. Bypass Cloudflare, bot detection, and
anti-scraping. Drop-in Puppeteer / Playwright replacement. Built so the stealth
layer is reusable by anything, not locked to `arc-browser`.

**arcbao**
OpenBao Agent sidecar proxy pattern for AI agent containers. Live secret
fetching at any point in a session - no baked-in env vars, no token rotation
headaches. The pattern is the product.

**arc-tables**
Interactive schema diagrams + plain-English database audits. Output is one HTML
file, zero config. Point it at a database, get a shareable audit page.

**review-workflows**
Reusable GitHub Actions workflows for AI review and Semgrep. Centralized so any
repo in the org gets the same review surface by referencing one workflow file.

**pr-agent-settings**
Organization-wide PR-Agent configuration for AI code review. Companion to
`review-workflows` - the workflow runs the agent, this repo defines how it
behaves.

**advertising-report-card**
Moonraker client proposals. Public-facing proposal repo for ARC's outbound work.

## Private Projects Advanced

**arc-ecosystem-vps** (private)
Internal VPS ecosystem orchestration. Container layout, sidecar wiring,
provisioning state.

**n8n-data-stored** (private)
n8n backup and migration snapshot. Render service backup captured 2026-04-27,
arc-web fork v2.12.3. Preserved so any future n8n rebuild has a known-good
restoration point.
