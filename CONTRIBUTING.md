# Contributing to activity

For people and agents. Read this whole file before your first change here.

This repo is public. Read the rules in the Secrets section and the "Rules that are easy to break" section before you add anything.

The shared ARC rules for Plane, branches, pull requests, secrets and release are in the [ARC contribution handbook](https://github.com/arc-web/agent-config/blob/main/handbook/HANDBOOK.md). The repo standard is in [repo-standard.md](https://github.com/arc-web/agent-config/blob/main/handbook/repo-standard.md) and [STANDARD.md](https://github.com/arc-web/agent-config/blob/main/handbook/STANDARD.md).

## At a glance

| | |
|---|---|
| What this repo is | The public activity feed for Arc Web: what was built, grouped by year and month |
| Owner and approver | The ARC web owner. Anything published needs the ARC owner's approval |
| Runs live at | GitHub Pages: the pages in `docs/` are served at `https://arc-web.github.io/activity/` |
| A merge reaches live by | Merging to `main` publishes the `docs/` pages |
| Test command | No automated checks yet. Open the changed pages in a browser before you merge |
| Plane project | The AGENTS project in the todovibes workspace |

## Quick start for agents

1. Read the Plane task and its comments. No task, no change.
2. Claim the task so nobody else takes it.
3. Branch from the latest `main`, named `docs/<short-slug>`.
4. Make the smallest change that meets the task.
5. Open each changed page in a browser and say what you checked in the pull request.
6. Open a pull request with the template filled in. Link the Plane task.
7. After merge, check the live URL returns the change. Comment on the Plane task with the pull request and the live check.

## Quick start for people

Ask an agent to add a month's entry or update the current focus. You get back a branch and a pull request to review.

## What belongs here

| Change | Home |
|---|---|
| A month's activity entry | `YYYY/MM-<month>/README.md` in this repo |
| The interactive presentation | `docs/` in this repo |
| Client work details, client names, internal infrastructure | not here. This repo is public |

## Layout

- `README.md`: the front page and the index of months.
- `YYYY/MM-<month>/README.md`: one page per month.
- `TEMPLATE-WEEKLY-UPDATE.md`: the template for a weekly update.
- `docs/`: the interactive presentation pages served by GitHub Pages.
- One folder per event, each holding that event page.
- `LLM_EVALUATION_PRESENTATION.md`: an evaluation write-up.

## Set up and test

Nothing to install. There are no automated checks yet. Before you open a pull request, open `docs/index.html` and each month page you changed in a browser, and check that the links work.

## Making a change

- Keep each pull request to one month, one event, or one page.
- Use the template for weekly updates. Do not change its structure.
- Run the humanizer pass on every changed markdown file before merge, as the repo standard requires.

## Release and rollback

| Layer | Here |
|---|---|
| Dev | A branch and pull request |
| Test | Manual browser check, described above |
| Staging | None yet |
| Production | `main`, served by GitHub Pages at `https://arc-web.github.io/activity/` |

Rollback: revert the squash merge commit on a new branch with `git revert <merge sha>`, then open a pull request. Check the live URL after the revert lands.

## Rules that are easy to break

- This repo is public. Do not add client names, client figures, internal hostnames, credential names or infrastructure paths.
- Keep the month pages in the `YYYY/MM-<month>/` form. The front page links to them.

## Secrets

None. The repo must hold no secret values and no secret names that reveal internal systems.

## Getting help

Ask in the Plane project named above. Post the pull request link in the matching Discord channel.
