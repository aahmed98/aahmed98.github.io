---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% assign author = site.author %}

{% if author.googlescholar %}
  You can also find my articles on <a href="{{author.googlescholar}}">my Google Scholar profile</a>.
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single-v2.html %}
{% endfor %}
