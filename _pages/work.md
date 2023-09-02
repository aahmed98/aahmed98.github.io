---
layout: archive
title: "Work"
permalink: /work/
author_profile: true
work:
  - name: Google
    logo: /images/google.png
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
    logo: /images/google.png
    role: Software Engineer
    startDate: May 2022
    endDate: Aug 2022
    location: Mountain View, CA
    highlights:
      - Designed, implemented, and launched an automatic pipeline that enriches clinical annotations with metadata from medical ontologies.
      - Leveraged medical knowledge to curate condition-centric insights for six chronic medical conditions, to be included in the next release of Care Studio.
      - Reduced end-to-end time to launch conditions in product by 50%.
  - name: Curai Health
    logo: /images/curai.png
    role: Machine Learning Engineering Intern
    startDate: Aug 2021
    endDate: Dec 2021
    location: Remote
    highlights:
      - Collaborated with clinicians and engineers to develop novel, clinically-informed metric for evaluation of an internal entity linking (EL) model.
      - Proposed and implemented production-level changes to the EL model, including an ML-based medical spell checker. Validated these changes using the new metric.
      - Shared results with the ML team, Clinical Innovation team, and CTO. Documented detailed next steps for future model versions.
  - name: Mass General Brigham
    logo: /images/curai.png
    role: Research Assistant
    startDate: Jun 2021
    endDate: Aug 2021
    location: Boston, MA
    highlights:
      - Trained novel medical image segmentation models using PyTorch to isolate kidneys and ureters on CT scans and grade lumbar stenosis on MRI scans.
      - Presented findings to stakeholders from GE Healthcare and MGH and packaged models into deployable microservices using Docker.
  - name: epistemic.ai
    logo: /images/curai.png
    role: Machine Learning Engineering Intern
    startDate: May 2020
    endDate: Aug 2020
    location: Remote
    highlights:
      - Researched, designed, and implemented a model using TensorFlow to generate topologically-informed embeddings for biomedical entities and relations in the system's knowledge graph.
      - Delivered proposal and proof-of-concept to the CEO and laid the foundation for integration into the product's retrieval service.
  - name: Brown AI Lab
    logo: /images/curai.png
    role: Research Assistant
    startDate: Dec 2018
    endDate: Current
    location: Providence, RI
    highlights:
      - Built de-identification system using TensorFlow/Keras with 94% accuracy at identifying HIPAA-regulated tokens in Electronic Health Records. First-author paper accepted in American Medical Informatics Association (AMIA) Informatics Summit.
      - Developed model to predict and forecast delirium phenotypes in stroke patients using time-series data collected from wrist actigraphs. First-author paper accepted in Frontiers in Neurology.
      - Led six-person team to build a search engine for clinical trials. Presented work at Text REtrieval Conference (TREC) Precision Medicine Track.
---

You can also find my work experience on [LinkedIn](https://www.linkedin.com/in/abdullah-a-ahmed/).



{% include base_path %}

{% for job in page.work %}
  {% include archive-single-work.html %}
{% endfor %}