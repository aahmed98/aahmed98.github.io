---
layout: archive
title: "Education"
permalink: /education/
author_profile: true
education:
  - name: Brown Medical School
    logo: /images/brown.jpg
    startDate: Aug 2020
    endDate: May 2025
    location: Providence, RI
    major: MD
  - name: Brown University
    logo: /images/brown.jpg
    startDate: Aug 2016
    endDate: May 2020
    location: Providence, RI
    major: ScB in Applied Mathematics-Biology, AB in Computer Science
    honors: Magna Cum Laude
---

{% include base_path %}

{% for school in page.education %}
  {% include archive-single-education.html %}
{% endfor %}