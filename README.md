# ThorSon's Land Services — Website

The official website for **ThorSon's Land Services** (exact spelling and capitalization),
a veteran-owned, family-run land services company in Camden, SC.

- Live site: https://www.thorsonslandservices.com
- Services: stump grinding, forestry mulching, bush hogging
- Phone: (803) 669-4954 · Email: chris.andres@thorsonslandservices.com

## Structure

This is a fully static, self-contained website — no build step, no dependencies to install.

- `index.html` — the entire site (HTML + CSS + JS in one file, assets inlined)

## Updating the site

1. Edit `index.html` directly (or ask Muse to make the change).
2. Commit and push to the `main` branch.
3. GitHub Pages redeploys automatically — changes are live within a minute or two.

### Conventions

- Always say **"estimate"**, never "quote".
- Never publish the home street address (service-area business only).
- Never claim "Licensed".
- Never invent years in business, certifications, reviews, or military details.
- No stock/AI photos presented as company work.

## Hosting

Hosted free with [GitHub Pages](https://pages.github.com/), deployed from the `main` branch.

Custom domain `thorsonslandservices.com` is configured in `Settings → Pages → Custom domain`,
with DNS at the domain registrar pointing to GitHub Pages:

- `A` records for the apex domain → GitHub Pages IPs
  (`185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`)
- `CNAME` for `www` → `<github-username>.github.io`
- "Enforce HTTPS" enabled in the Pages settings.

## Version history

See the commit log for the full change history.
