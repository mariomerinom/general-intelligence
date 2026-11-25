# General Intelligence Review

Research on AI and its effects on work, income and human agency.

## Deploy

Import this repository into Netlify. Leave the build command empty and set the publish directory to `public` (also configured in netlify.toml). Add `generalintelligencereview.org` in domain management, then use the DNS records Netlify supplies at your registrar.

## Update

Research stays in the local AGI_Transition project. After acceptance and dashboard refresh, run `python3 dashboard/export_public.py /tmp/gir-next` from that project, using a new empty output directory. Replace this repository's `public/` files with the export, review the diff, and commit. Netlify deploys the commit automatically. Readers get the new edition on their next page load.

This repository contains the public export only. Evidence dates are preserved independently of deployment dates.
