---
layout: archive
title: "Work"
permalink: /work/
author_profile: true
---

{% assign author = site.author %}

{% if author.linkedin %}
  You can also find my work experience on <a href="{{author.linkedin}}">my LinkedIn</a>.
{% endif %}

{% include base_path %}

{% for job in site.work reversed %}
  {% include archive-single-work.html %}
{% endfor %}