---
title: OCA Module Search
description: the search UI and JSON API endpoints
position: 2
---

The `oca-search-api` repo serves the search UI and a JSON API on Cloudflare
Pages.

API endpoints:

- `GET /api/search?q=...` — search modules
- `GET /api/module?id=<technical_name>/<version>` — module detail
- `GET /api/module/versions?name=<technical_name>` — available versions

Setup and local preview instructions are in the
[repository README](https://github.com/OdooEssentials/oca-search-api).
