<div align="center">

<a href="https://arc-web.github.io/activity/">
  <img src="https://img.shields.io/badge/🎬_Interactive_Presentation-View_Live-7B2FBE?style=for-the-badge&labelColor=0F0F1A&color=7B2FBE" alt="View Interactive Presentation" />
</a>

</div>

---

# Arc Web - Activity Feed

What we're building, organized by time.

All active development happens in private repos - client work, proprietary tools, internal systems.
This feed gives visibility into output and direction without exposing code or client details.

---

## What We Build

**AI & Automation**
MCP servers, Claude integrations, agent workflows, LLM tooling

**GoHighLevel & CRM**
Custom GHL integrations, marketing automation, API tooling

**Developer Infrastructure**
Internal frameworks, CI/CD, repo management, context optimization

**Data & Analytics**
Google Ads, SEO auditing, reporting pipelines

**SaaS Products**
Early-stage tools and community platforms built in public

---

## Current Focus (May 2026)

Six-week sprint across April and May. Stealth browser stack went public, the
Cloudflare R2 delivery pipeline matured, Google Ads automation entered active
campaign rebuild, and the Claude skill library moved into version control:

- **arc-browser** - Stealth browser automation MCP for Claude Code. 21 tools, session pool, FlareSolverr + Cloudflare recovery integration
- **camofox-browser** - Stealth headless Firefox for AI agents. Drop-in Puppeteer / Playwright replacement, anti-detection built in
- **arcbao** - OpenBao Agent sidecar proxy pattern for AI agent containers. Live secret fetching, no baked-in env vars
- **arc-tables** - Interactive HTML schema diagrams + plain-English database audits. One file, zero config
- **discord-agent** - Discord CLI, API client, channel reports for the ARC team. Charlie bot ships with the stack
- **google-ads-agent** - Google Ads campaign management agent. THHL search rebuild active, HITL approval workflow
- **review-workflows** + **pr-agent-settings** - Org-wide AI code review and Semgrep, one workflow file per repo
- **claude-skills** (private) - Claude Code skill library moved into git, tracked and reviewable
- **cloudflare_agent** (private) - cf-deploy CLI for R2 static site lifecycle. Pipeline behind ARC client sites
- **therappc-site** (private) - First client site extracted into its own repo, sets the multi-site pattern
- **reportcard-agent** (private) - Automated report generation + quality grading engine for ARC audits
- **google-oauth-setup** (private) - One-shot Google OAuth CLI, writes credentials to OpenBao + 1Password

---

## Archive

- [May 2026](2026/05-may/README.md) - Client delivery + skills infra: cf-deploy, therappc-site, discord-agent, google-ads-agent, claude-skills
- [April 2026](2026/04-april/README.md) - Stealth browser stack public, OpenBao sidecar, org-wide AI review
- [March 2026](2026/03-march/README.md) - Major output: 12 repos advanced
- [January 2026](2026/01-january/README.md) - Google platform agents
- [December 2025](2025/12-december/README.md) - Workspaces, GHL consolidation
- [November 2025](2025/11-november/README.md) - GHL MCP foundation, n8n MCP, org setup
- [October 2025](2025/10-october/README.md) - Agentic tooling
- [September 2025](2025/09-september/README.md) - Agent framework research
- [June 2025](2025/06-june/README.md) - MCP foundation, GHL initial, Supabase
- [May 2025](2025/05-may/README.md) - Database layer
- [April 2025](2025/04-april/README.md) - CRM experiments
- [March 2025](2025/03-march/README.md) - Foundation

---

## About Arc Web

Building AI automation, CRM integrations, and marketing technology for agencies and businesses.

Focus: making AI useful in production - not demos, but systems that save hours daily.
