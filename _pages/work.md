---
layout: archive
title: "Work"
permalink: /work/
author_profile: true
---

{% assign author = site.author %}

{% if author.linkedin %}
  You can find my up-to-date work experience on my <a href="{{author.linkedin}}">LinkedIn</a>.
{% endif %}

{% include base_path %}

{% for job in site.work reversed %}
  {% include archive-single-work.html %}
{% endfor %}