---
layout: archive
title: "Published Research"
permalink: /publications/
author_profile: true

---

You can also find my articles on [my Google Scholar profile](https://scholar.google.com/citations?user=Ks-_ZlIAAAAJ&hl=en) or [download my CV](http://alex-hoagland.github.io/files/HoaglandCV_current.pdf).

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
