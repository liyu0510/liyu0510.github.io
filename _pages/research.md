---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% include base_path %}

{% for post in site.research reversed %}
  {% include archive-single.html %}
{% endfor %}

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

---

## Work in progress
- Shadow Banks and Economic Instability with Two-sided Financial Frictions
- E-commerce Platforms and Inflation Pass-through, Joint with [Luise Eisfeld](https://luiseeisfeld.github.io/) and [Jun Yan](https://sites.google.com/view/jun-yan)
