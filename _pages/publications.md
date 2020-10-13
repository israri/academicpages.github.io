---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

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
