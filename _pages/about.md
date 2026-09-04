---
permalink: /
title: "Zhaoqi Zhang"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I am a Ph.D. candidate in Computer Science at Nanyang Technological University (NTU), Singapore, supervised by Prof. Gao Cong and Prof. Siqiang Luo.

My research interests lie broadly in **urban computing, spatiotemporal data mining, graph learning, multimodal representation learning, and causal inference**. My research aims to develop data-driven and causal learning methods for understanding and modeling complex urban systems.

My Ph.D. research focuses on three interconnected directions:

- **Spatiotemporal Data Mining** 
- **Spatiotemporal and Graph Learning**
- **Causal Inference**

I have also worked on large-scale data mining and advertising optimization problems in collaboration with industry.


## News

- **2026:** Our work on causal modeling for cold-start POI forecasting was accepted by **SIGKDD 2026**.
- **2026:** Our work on multiscale urban foundation models was accepted by **IEEE TKDE**.
- **2026:** Our work on guaranteed display advertising was accepted by **SIGIR 2026**.

## Selected Publications

{% include base_path %}

{% assign sorted_publications = site.publications | sort: "order" %}

{% for post in sorted_publications limit:5 %}
  {% include archive-single.html %}
{% endfor %}

[See all publications]({{ base_path }}/publications/)


## Professional Service

### Conference Reviewer

- AAAI 2027, KDD 2027, WSDM 2027
- AAAI 2026, KDD 2026, WWW 2026
- KDD 2025, WWW 2025

### Journal Reviewer

- IEEE Transactions on Knowledge and Data Engineering
- IEEE Transactions on Audio, Speech and Language Processing
- Data & Knowledge Engineering
- Data Science and Engineering


## Teaching

- **SC2005 / CE2005 / CZ2005** *Operating Systems* — 22 Spring
- **CZ3003** *Software System Analysis and Design* — 22 Spring
- **SC2006 / CE2006 / CZ2006** *Software Engineering* — 22 Fall, 23 Spring
- **SC2207 / CZ2007** *Introduction to Databases* — 25 Spring
