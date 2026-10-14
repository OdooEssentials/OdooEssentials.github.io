---
layout: single
title: Projects
permalink: /projects/
---

Tools for exploring and working with OCA modules.

{%- assign projects = site.projects | sort: "position" -%}
{%- for project in projects %}
## [{{ project.title }}]({{ project.url | relative_url }})

{{ project.excerpt }}
{%- endfor %}
