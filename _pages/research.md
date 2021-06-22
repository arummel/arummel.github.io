---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% include base_path %}

My dissertation work is focused on the physiology of bat muscles in relation to the unique thermal environment imposed by flight. Flying animals must contend with  

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}
