---
layout: archive
title: "Research"
collection: portfolio
permalink: /research/
author_profile: true
entries_layout: grid
---


{% include base_path %}
{% for post in site.research %}
  {% include archive-single.html %}
{% endfor %}