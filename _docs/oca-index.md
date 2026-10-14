---
title: OCA Modules Index
description: building and uploading the OCA modules index
position: 1
---

The `cloudflare-oca-indexer` repo scans OCA repositories and uploads the index
to Cloudflare AI Search and D1.

Typical workflow:

```bash
python sync_repos.py --branch all    # clone/update OCA repos
python build_index.py --branch all   # build the local index
python upload_ai.py --branch all     # upload to AI Search
python upload_d1.py                  # upload to D1
```

Full reference in the
[repository README](https://github.com/OdooEssentials/cloudflare-oca-indexer).
