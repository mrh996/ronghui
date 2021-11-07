---
layout: archive
title: "Sparse Adversarial VideoAttacks with Spatial Transformations In preceeding of The 32nd British Machine Vision Conference (BMVC)"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
