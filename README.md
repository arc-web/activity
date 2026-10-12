<div align="center">

<a href="https://arc-web.github.io/activity/">
  <img src="https://img.shields.io/badge/🎬_Interactive_Presentation-View_Live-7B2FBE?style=for-the-badge&labelColor=0F0F1A&color=7B2FBE" alt="View Interactive Presentation" />
</a>

</div>

---

# Arc Web - Activity Feed

What we're building, organized by time.

| | |
|---|---|
| Status | Live: the public feed and presentation are served from GitHub Pages |
| Owner | The ARC web owner. The ARC owner approves publishing |
| Runs at | GitHub Pages, from the `docs/` pages |
| A change goes live by | Merging to `main`; see [CONTRIBUTING.md](CONTRIBUTING.md#release-and-rollback) |
| Change something | Start with [CONTRIBUTING.md](CONTRIBUTING.md) |

> [!NOTE]
> Working with an AI agent? Its instructions are in [AGENTS.md](AGENTS.md) and [CLAUDE.md](CLAUDE.md).

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

## Current focus

Recent work: the stealth browser stack went public, the Cloudflare R2 delivery
pipeline matured, Google Ads automation entered an active campaign rebuild, and
the Claude skill library moved into version control:

- **arc-browser** - Stealth browser automation MCP for Claude Code. 21 tools, session pool, FlareSolverr + Cloudflare recovery integration
- **camofox-browser** - Stealth headless Firefox for AI agents. Drop-in Puppeteer / Playwright replacement, anti-detection built in
- **arcbao** (private) - secret management for AI agent containers
- **arc-tables** - Interactive HTML schema diagrams + plain-English database audits. One file, zero config
- **discord-agent** - Discord CLI, API client, channel reports for the ARC team. Charlie bot ships with the stack
- **google-ads-agent** - Google Ads campaign management agent. THHL search rebuild active, HITL approval workflow
- **review-workflows** + **pr-agent-settings** - Org-wide AI code review and Semgrep, one workflow file per repo
- **claude-skills** (private) - Claude Code skill library moved into git, tracked and reviewable
- **cloudflare_agent** (private) - cf-deploy CLI for R2 static site lifecycle. Pipeline behind ARC client sites
- **therappc-site** (private) - First client site extracted into its own repo, sets the multi-site pattern
- **aibrainbuilders** + **netprofitpositive** (in-flight) - Two more client marketing sites in local build, repo extraction pending
- **reportcard-agent** (private) - Automated report generation + quality grading engine for ARC audits
- **google-oauth-setup** (private) - One-shot Google OAuth CLI

---

## Archive

Past months are kept as one page per month in the year folders of this repo. The git history holds every earlier version of this page.

---

## About Arc Web

Building AI automation, CRM integrations, and marketing technology for agencies and businesses.

Focus: making AI useful in production - not demos, but systems that save hours daily.
