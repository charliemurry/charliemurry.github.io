---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}


#### [The Effect of Retail Competition on Relationship-specific Investments: Evidence from New Car Advertising](https://www.sciencedirect.com/science/article/pii/S0167718718300341) 
International Journal of Industrial Organization, Volume 59, 2018. [working paper version]

#### Abstract


{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
