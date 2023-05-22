---
layout: archive
title: "Research and mathematical writing"
permalink: /research/
author_profile: true
---

This page collects my expository writings on various subjects. I don't have any original research papers yet. 

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.research reversed %}
  {% include archive-single.html %}
{% endfor %}
