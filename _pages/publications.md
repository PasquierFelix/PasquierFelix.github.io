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

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

Work in Progress
======
* Fuzzy Difference-in-Differences with Multiple Groups and Multiple Time Periods (with [Clément de Chaisemartin](https://sites.google.com/site/clementdechaisemartin/) and [Xavier d'Haultfoeuille](https://faculty.crest.fr/xdhaultfoeuille/))
