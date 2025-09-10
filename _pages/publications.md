---
layout: archive
title: "Research and mathematical writing"
permalink: /research/
author_profile: true
---

This page collects my research papers and expository mathematical writings. You can also find my papers on the [arXiv](https://arxiv.org/a/longbottom_i_1.html).

### Research

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.research reversed %}
  {% include archive-single.html %}
{% endfor %}

### Other expository writings

{% for post in site.writing reversed %}
  {% include archive-single.html %}
{% endfor %}
