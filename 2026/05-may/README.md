# May 2026

Client delivery and skills infrastructure month. Cloudflare R2 deploy pipeline
matured, the first client site got extracted into its own repo, the Discord
agent stack landed in production with a working channel-reads bot, the Google
Ads agent went into active campaign rebuild, and the Claude skill library
moved into version-controlled repos.

## Public Projects Shipped

**discord-agent**
Discord management tools for the ARC team. Python CLI, API client, automated
channel report generation with LLM summarization. Pairs with the Charlie bot
for channel reads on ARC's primary server - the bot.env shipped in earlier
forks is stale and now superseded.

**google-ads-agent**
Google Ads campaign management agent. Independent repo, currently driving the
THHL search campaign rebuild - 9 ad groups staged, copy engine in place, policy
violations cleared. HITL document workflow for sign-off before any live push.

**arc-browser**
Continued from April. FlareSolverr proxy + `cf_recovery.py` integration shipped
2026-05-01 (commit `bf3f53e`). Cloudflare-protected pages now recoverable from
inside an active session instead of failing the run.

## Private Projects Advanced

**cloudflare_agent** (private)
Cloudflare R2 site management. `cf-deploy` CLI handles the full lifecycle:
deploy, update, teardown static sites on ARC-owned domains. The pipeline that
client work flows through.

**therappc-site** (private)
First client site extracted out of `cloudflare_agent` into its own repo
(2026-05-13). Sets the pattern: client sites get their own repo, the deploy
agent stays a tool, not a multi-tenant container.

**reportcard-agent** (private)
Automated report generation and quality grading. The engine behind ARC's audit
deliverables.

**google-oauth-setup** (private)
One-shot Google OAuth setup CLI for any Google account. Handles auth flow,
writes credentials to OpenBao, mirrors to 1Password. Eliminates the per-account
OAuth dance.

**todovibes** (private)
TodoVibes - AI + human project management infrastructure. Plane-based, the
internal source of truth for who's doing what.

**arc-scripts** (private)
Infrastructure scripts and shared utilities. New home for `gmail_mgmt` CLI
(replacing the gongrzhe MCP path) and other small operational tools.

**claude-skills** (private)
Claude Code skill files - the prompt libraries that live behind
`~/.claude/skills/`. Moving the skill library into git means edits get tracked,
shared, and reviewed.

**skill-find-skills** (private)
Guarded `Skills.sh find-skills` intake, audit, smoke-test, and integration
pipeline.

**skill-systematic-debugging** (private)
Guarded `Skills.sh systematic-debugging` intake, audit, smoke-test, and
integration package.

**fathom_agent** (private)
Fathom.video integration and meeting automation. Transcripts, summaries,
action items, all callable from agent workflows.

---

_Entry covers May 1 - May 15, 2026. Month in progress._
