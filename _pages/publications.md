---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Here is a list of my recent publications. You can find the complete list of my articles on <u><a href="https://scholar.google.fr/citations?user=k6--GlAAAAAJ&hl=en">my Google Scholar profile</a>.</u>

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
