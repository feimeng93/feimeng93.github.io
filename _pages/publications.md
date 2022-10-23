---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{Preprints
======
- C. LI, **F. MENG**, J. WANG\*, Max Q.-H. MENG\*. [**Relevant Region Sampling Strategy with Adaptive Heuristic Estimation for Asymptotically Optimal Motion Planning**](https://arxiv.org/abs/2111.00383).}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
