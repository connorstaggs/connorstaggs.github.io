---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---


## "Hindu Nationalism and the New Jim Crow" (with Ashutosh Varshney). *Journal of Democracy*, January 2024. 

This paper demonstrates how the same fundamental tools - exclusionary laws, segregation, and vigilante violence - have been used to forge regimes of ethnic marginalization in both the Jim Crow-era South and in modern-day India.

[Download PDF](https://connorstaggs.github.io/assets/Hindu_nationalism_and_the_new_jim_crow_varshney_staggs.pdf)

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
