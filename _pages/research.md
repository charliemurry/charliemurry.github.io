---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}


### [The Effect of Retail Competition on Relationship-specific Investments: Evidence from New Car Advertising](https://www.sciencedirect.com/science/article/pii/S0167718718300341) 
International Journal of Industrial Organization, Volume 59, 2018. [working paper version]

#### Abstract

Longstanding state regulations restrict car manufacturers from terminating relationships with dealers, creating differences in retail competition across brands and markets. I use this variation to identify the causal effect of dealer competition on dealer and manufacturer local market advertising. I find that greater intra-brand dealer competition is associated with lower dealer advertising. US brand manufacturers decrease advertising with an additional same-brand dealer, but there is zero average effect for non-US brand manufacturers. The results are evidence that manufacturers can encourage retail relationship-specific investments by providing downstream market power. I discuss theories of oligopoly and vertical relationships that may explain the results and the relevance of the findings to the effects of state automobile franchise regulation and the recent financial troubles of US car manufacturers.


{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
