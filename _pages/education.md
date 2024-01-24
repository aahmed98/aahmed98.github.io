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
    courses: Internal Medicine, Surgery, Psychiatry, Ophthalmology, Radiation-Oncology
  - name: Brown University
    logo: /images/brown.jpg
    startDate: Aug 2016
    endDate: May 2020
    location: Providence, RI
    major: Sc.B in Applied Mathematics-Biology
    honors: Magna Cum Laude, Sigma Xi
    thesis: Ablation study of named entity recognition (NER) taxonomies on the de-identification of free-text medical records.
    courses: Quantitative Models of Biological Systems, AI in Biomedicine, Inference in Genomics and Molecular Biology
  - name: Brown University
    logo: /images/brown.jpg
    startDate: Aug 2016
    endDate: May 2020
    location: Providence, RI
    major: A.B in Computer Science
    courses: Artifical Intelligence, Machine Learning, Language Processing, Image Understanding, Object-Oriented Programming, Discrete Structures and Probability
---

I have gotten to know Providence fairly well through Brown's Program in Liberal Medical Education (PLME), a combined 8-year BS/MD program.

{% include base_path %}

{% for school in page.education %}
  {% include archive-single-education.html %}
{% endfor %}