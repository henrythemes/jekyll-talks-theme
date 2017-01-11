---
title: Talks
---

Talks:

{% for talk in site.talks %}

**{{ talk.title }}** - [(Slides)]({{ talk.url | relative_url }})<br>
by {{ talk.author }}<br>
{{ talk.date | date: "%A, %B %d, %Y" }}

{% endfor %}


----

Powered by the [S6 slideshow templates / machinery / kit](http://slidekit.github.io).
