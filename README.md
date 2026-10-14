# odoo-essentials.github.io

Source for [OdooEssentials.com](https://odoo-essentials.github.io) — Odoo
Development Essentials and Beyond. Jekyll site (Minima theme) hosted on
GitHub Pages.

## Local preview

```bash
bundle install
bundle exec jekyll serve
```

## Setup checklist

- **Giscus comments** — enable GitHub Discussions on this repo, then get the
  `repo_id` and `category_id` from <https://giscus.app> and fill them in
  `_config.yml` under `giscus:`. Comments stay off until both are set.
- **Cloudflare Web Analytics** — create a Web Analytics site in the Cloudflare
  dashboard and put the token in `cloudflare_analytics_token` in `_config.yml`.
- **Custom domain** — add a `CNAME` file containing `odooessentials.com` once
  the domain's DNS is configured to point to GitHub Pages.

## Structure

- `_posts/` — blog posts
- `_projects/` — project pages (listed on `/projects/`)
- `_docs/` — tool documentation (listed on `/docs/`)
- `about.md`, `index.md` — top-level pages
