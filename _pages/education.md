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
    major: M.D. Candidate
  - name: Brown University
    logo: /images/brown.jpg
    startDate: Aug 2016
    endDate: May 2020
    location: Providence, RI
    major: Sc.B in Applied Mathematics-Biology, A.B in Computer Science
    honors: Magna Cum Laude, Sigma Xi
---

I have gotten to know Providence fairly well through Brown's Program in Liberal Medical Education (PLME), a combined 8-year BS/MD program.

{% include base_path %}

{% for school in page.education %}
  {% include archive-single-education.html %}
{% endfor %}