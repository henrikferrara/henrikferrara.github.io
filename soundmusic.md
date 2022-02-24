---
layout: "page"
title: "sound and music"
---

{% for item in site.music %}
<p><a href="https://henrikferrara.github.io/soundmusic.html/{{ item.url }}">{{ item.title }}</a></p>
<p>{{ item.description }}</p>

{% endfor %}
