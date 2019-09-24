---
layout: archive
title: "Data and Code"
permalink: /dataandcode/
author_profile: true
---

### Replication Codes
Each of these contains a link to a GitHub repository with replication files for the indicated project. 

* [Who Do Innovations Reach? The Impact of Trainings on Mental Health Treatments](https://github.com/alex-hoagland/innovations-mental-health)

{% include base_path %}

{% for post in site.dataandcode reversed %}
  {% include archive-single.html %}
{% endfor %}
