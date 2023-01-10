---
layout: archive
title: "Selected Publications"
permalink: /publications/
author_profile: true
---


You can also find a complete list of my articles (60+) on <a href="https://scholar.google.fr/citations?user=JoXowwQAAAAJ&hl=en" target="_blank">my Google Scholar profile</a>.


{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
