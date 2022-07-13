---
layout: archive
title: "Teaching"
permalink: /teaching/
author_profile: true
---

{% include base_path %}

### Current Courses (University of Toronto, IHPME)
Fall 2022: [Health Econometrics 1 (HAD 5744)](https://github.com/alex-hoagland/HAD5744_2022F)

### Previous Courses (Boston University, Economics) 

{% for post in site.teaching reversed %}
  {% include archive-single.html %}
{% endfor %}
