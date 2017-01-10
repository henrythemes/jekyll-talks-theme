---
title: Talks
---

Talks:

{% for talk in site.talks %}

**{{ talk.title }}** [(Slides)]({{ talk.url }})

{% endfor %}
