# General Intelligence Review

Research on AI and its effects on work, income and human agency.

## GitHub Pages

In Settings > Pages, set Source to GitHub Actions. The included Deploy GitHub Pages workflow publishes `public/` on pushes to main and can also be run manually from Actions.

Add `generalintelligencereview.org` in Settings > Pages > Custom domain, then configure the DNS records at the registrar as directed by GitHub. Enable HTTPS once domain verification and certificate issuance complete. A private source repository requires a GitHub plan that supports Pages for private repositories.

## Updates

Research stays in the local AGI_Transition project. After acceptance and dashboard refresh, run `python3 dashboard/export_public.py /tmp/gir-next` from that project using an empty destination. Replace this repository's public files, review the diff and commit. GitHub Actions deploys the new edition. Readers receive it on their next page load.

Only the public export is stored here. Evidence dates remain separate from deployment dates.
