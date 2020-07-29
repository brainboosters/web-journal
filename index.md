---
layout: default
title: "Home"
---
<nav>
  {% for item in site.data.nav %}
    <a href="{{ item.link }}" {% if page.url == item.link %}class="active"{% endif %}>{{ item.name }}</a>
  {% endfor %}
</nav>
# United Geekdom's web journal
**Hello world!** This is the new web journal of my site. I will log my changes and describe other programming projects here.
This journal was made with [Jekyll](https://jekyllrb.com/). I am just a beginner at markdown and YAML, hence this is a work-in-progress.
