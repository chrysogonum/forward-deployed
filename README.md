# Forward Deployed

A proposal for embedded AI prototyping for small & mid-size nonprofits — an
independent forward deployed engineer who sits with each staff member, learns
the work, and either builds the tools for them or teaches them to build their own.

**Live:** https://fde.ppr3.com (moved 2026-07-28 from
`https://chrysogonum.github.io/forward-deployed/`, which now redirects here)

Single self-contained HTML file (`index.html`). No build step.

## Deploying

**`git push` is the deploy.** GitHub Pages publishes from `main` at the repo root; the site is
live at https://fde.ppr3.com about a minute after a push. No build step, no wrangler command.

⚠ **Do not delete the `CNAME` file at the repo root.** It contains `fde.ppr3.com` and is what binds the
subdomain — GitHub wrote it on 2026-07-28 when the custom domain was set, so it can read as stray.
Deleting it unbinds the domain and the site falls back to `chrysogonum.github.io/forward-deployed/` (which
currently 301-redirects here).

*Note: `PROJECT_STATE.md` is gitignored in this repo, so this guard is repeated here to survive a
fresh clone.*
