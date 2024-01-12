---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

## Fairness-Enhancing Machine Learning 

These works provide an overview of my research.

* **Zheng, Y.**, Wang, S., & Zhao, J. (2021). Equality of opportunity in travel behavior prediction with deep neural networks and discrete choice models. <i> Transportation Research Part C: Emerging Technologies, 132, 103410. </i> Full text available at <a href="https://doi.org/10.1016/j.trc.2021.103410"> https://doi.org/10.1016/j.trc.2021.103410 </a>

## Causal Inference and Transportation Policies


## Behavior Science and Demand Modeling

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications.fairness_ml reversed %}
  {% include archive-single.html %}
{% endfor %}
