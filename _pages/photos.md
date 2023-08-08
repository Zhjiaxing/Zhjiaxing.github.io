---
layout: archive
title: "Photos"
permalink: /photos/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

## Journal Papers

+Supervised, #Corresponding

34. **Zhang P**, Yin ZY, Sheil B., 2023. [Interpretable data-driven constitutive modelling of soils with sparse data](https://www.sciencedirect.com/science/article/abs/pii/S0266352X23002689). *Computers and Geotechnics*, 160, 105511
