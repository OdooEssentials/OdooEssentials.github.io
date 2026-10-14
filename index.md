---
layout: splash
header:
  overlay_image: /assets/images/beyond-code-feature.jpg
  overlay_filter: 0.4
  caption: 'Photo by [Tim Bernhard](https://unsplash.com/@bernhardvisuals) / Unsplash'
  actions:
    - label: "View the Projects"
      url: /projects/
    - label: "Read the Docs"
      url: /docs/
excerpt: Beyond code, towards solutions solving real needs.
---

Practical experience on Odoo implementations, the OCA ecosystem, and the
tools behind [OdooIndex](https://odooindex.com).

## Latest posts

{% for post in site.posts limit:5 %}
- **[{{ post.title }}]({{ post.url | relative_url }})** — {{ post.date | date: "%b %-d, %Y" }}
{% endfor %}
