---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can also find my articles on my <u><a href="https://scholar.google.com/citations?hl=en&user=y3xCsdkAAAAJ">Google Scholar profile</a></u> and <u><a href="https://www.researchgate.net/profile/Israr_Bin_M_Ibrahim">my ResearchGate profile</a>.</u>

{% include base_path %}

Agent-Based Model
------
{% for post in site.pubabm reversed %}
  {% include archive-single.html %}
{% endfor %}

Computational Biology
------
{% for post in site.pubmtrsci reversed %}
  {% include archive-single.html %}
{% endfor %}

<!-- Materials Science
------
{% for post in site.pubmtrsci reversed %}
  {% include archive-single.html %}
{% endfor %} -->
