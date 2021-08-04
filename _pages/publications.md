---
layout: archive
title: "Ongoing & Published Research"
permalink: /publications/
author_profile: true

---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

<!--- Publications --->
<!--- ------ --->

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

<!--- Working Papers --->
<!--- ----- --->------

<!--- {% for post in site.working_papers reversed %} --->
<!--- {% include archive-single.html %} --->  
<!--- {% endfor %} --->
