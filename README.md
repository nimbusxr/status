# NimbusXR status

The public status page for every NimbusXR product, at
[status.nimbusxr.us](https://status.nimbusxr.us). Rows are named
"Product · Service"; Shout! is the first.
Built on [Upptime](https://upptime.js.org): GitHub Actions in this repo
check the endpoints in `.upptimerc.yml` every five minutes, commit the
results (`history/`, `api/`, `graphs/`), open an issue when a check
fails and close it when it recovers, and publish the site to GitHub
Pages from the `gh-pages` branch.

This repository is private; the page it publishes is public.

- **Change what is watched**: edit `sites` in `.upptimerc.yml`. Add a
  product's rows there; add Shout!'s production rows when production
  exists.
- **Post an incident note**: comment on the open issue; it renders on
  the page.
- **Secrets**: `GH_PAT`, a fine-grained personal access token for this
  repository with Contents, Issues and Workflows read/write. The default
  Actions token cannot trigger the other workflows.
- The page is on GitHub; a GitHub outage freezes it at its last result.
  Each product keeps its own independent alerting; Shout!'s is Google
  Cloud Monitoring uptime checks, see its `docs/infrastructure.md`.
