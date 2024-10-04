---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% assign author = site.author %}

{% if author.googlescholar %}
  You can also find my articles on my <a href="{{author.googlescholar}}">Google Scholar</a> profile.
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single-pub.html %}
{% endfor %}
