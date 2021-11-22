---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

The following are a selection of (all unpublished) mathematical essays I have written for various courses and projects. 

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
