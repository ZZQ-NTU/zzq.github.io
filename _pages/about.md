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

{% assign sorted_publications = site.publications | sort: "date" | reverse %}

{% for post in sorted_publications limit:5 %}
  {% include archive-single.html %}
{% endfor %}

[See all publications]({{ base_path }}/publications/)
