---
layout: archive
title: "Work"
permalink: /work/
author_profile: true
work:
  - name: Google
    role: Product Manager
    startDate: Aug 2022
    endDate: March 2023
    location: Mountain View, CA
    highlights: 
      - Led development of a new clinical risk scores feature that enables physicians to automatically compute scores in the context of relevant patient data.
      - Authored a product requirements document (PRD) that defined the scope, objectives, and key performance indicators (KPIs) of the feature.
      - Conducted and analyzed user research (UXR) to understand the needs and pain points of physicians regarding risk assessment.
      - Presented the feature design and roadmap to the Director of PM and VP of Google Health. Received positive feedback and approval to proceed.
  - name: Google
    role: Software Engineer
    startDate: May 2022
    endDate: Aug 2022
    location: Mountain View, CA
    highlights:
      - Designed, implemented, and launched an automatic pipeline that enriches clinical annotations with metadata from medical ontologies.
      - Leveraged medical knowledge to curate condition-centric insights for six chronic medical conditions, to be included in the next release of Care Studio.
      - Reduced end-to-end time to launch conditions in product by 50%.
  - name: Curai Health
    role: Machine Learning Engineering Intern
    startDate: Aug 2021
    endDate: Dec 2021
    location: Palo Alto, CA
    highlights:
      - Collaborated with clinicians and engineers to develop novel, clinically-informed metric for evaluation of an internal entity linking (EL) model.
      - Proposed and implemented production-level changes to the EL model, including an ML-based medical spell checker. Validated these changes using the new metric.
      - Shared results with the ML team, Clinical Innovation team, and CTO. Documented detailed next steps for future model versions.
---

You can also find my work experience on [LinkedIn](https://www.linkedin.com/in/abdullah-a-ahmed/).



{% include base_path %}

{% for job in page.work %}
  {% include archive-single-work.html %}
{% endfor %}