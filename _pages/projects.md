---
layout: page
title: research
permalink: /projects/
description: Selected research and engineering projects.
nav: true
nav_order: 3
---

{% assign projects = site.projects | sort: "importance" %}
{% for project in projects %}
## [{{ project.title }}]({{ project.url | relative_url }})

_{{ project.period }} · {{ project.role }}_

{{ project.description }}

[Read more →]({{ project.url | relative_url }})

---
{% endfor %}
