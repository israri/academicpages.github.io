---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if israrbmi.googlescholar %}
  You can also find my articles on <u><a href="{{israrbmi.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

<!-- You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a></u> and <u><a href="{{author.researchgate}}">my ResearchGate profile</a>.</u> -->

{% include base_path %}

Agent-Based Model
------

Computational Biology
------
<!-- {% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %} -->

Materials Science
------
{% for post in site.pubmtrsci reversed %}
  {% include archive-single.html %}
{% endfor %}
