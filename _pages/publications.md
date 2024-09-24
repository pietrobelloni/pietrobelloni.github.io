---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<img src="/images/moher.jpg"/> Cliffs of Moher, Ireland - September 2019

## Preprints

-   A. Sottosanti, P. Belloni, E. Bovo, G. Boccuzzo. *Bayesian Mapping of Mortality Clusters*. arXiv preprint (2024). <https://arxiv.org/abs/2407.19135>

{% if author.googlescholar %} You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u> {% endif %}

{% include base_path %}

{% for post in site.publications reversed %} {% include archive-single.html %} {% endfor %}
