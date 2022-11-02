---
layout: archive
title: "Working Papers"
permalink: /working-papers/
author_profile: true

---

You can also find my articles on [my Google Scholar profile](https://scholar.google.com/citations?user=Ks-_ZlIAAAAJ&hl=en) or [download my CV](http://alex-hoagland.github.io/files/HoaglandCV_current.pdf).

{% for post in site.workingpapers reversed %} 
{% include archive-single.html %}
{% endfor %}
