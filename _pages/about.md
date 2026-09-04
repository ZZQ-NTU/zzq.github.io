---
permalink: /
title: "Zhaoqi Zhang"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I am a PhD candidate at Nanyang Technological University (NTU), Singapore, supervised by Prof. Gao Cong and Prof. Siqiang Luo. Prior to joining NTU, I received my Bachelor's degree in Software Engineering from Dalian University of Technology.

My research interests lie broadly in **Spatiotemporal Data Mining, Representation Learning, and Causal Inference**. My research aims to develop data-driven and causal learning methods for understanding and modeling complex urban systems. Beyond academic research, I have also worked on large-scale data mining and advertising optimization problems in industry collaborations.


## Selected Publications
**(* = corresponding author)**

{% include base_path %}

{% assign sorted_publications = site.publications | sort: "order" %}

{% for post in sorted_publications limit:5 %}
  {% include archive-single.html %}
{% endfor %}

[See all publications on Google Scholar]({{ site.author.googlescholar }})


## Services

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
