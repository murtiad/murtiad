---
layout: archive
title: "Selected Publications"
permalink: /publications/
author_profile: true
---


You can also find a complete list of my articles (60+) on [my Google Scholar profile](https://scholar.google.fr/citations?user=JoXowwQAAAAJ&hl=en).


{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
