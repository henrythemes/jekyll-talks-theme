---
title: Talks
---

Talks:

{% for talk in site.talks %}

**{{ talk.title }}** - [(Slides)]({{ talk.url | relative_url }})

{% endfor %}
