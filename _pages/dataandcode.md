---
layout: archive
title: "Data and Code"
permalink: /dataandcode/
author_profile: true
---

### Replication Codes
Each of these contains a link to a GitHub repository with replication files for the indicated project. 

* ["Innovations and Inequities in Access to Medical Services"](https://github.com/alex-hoagland/Innovations-Inequities-TAVR)
* ["Comparison of Postpartum Health Care Use and Spending Among Individuals with Medicaid-Paid Births Enrolled in Continuous Medicaid vs Commercial Insurance" and "Extended Postpartum Medicaid Eligibility Is Associated With Improved Continuity Of Coverage In The Postpartum Year"](https://github.com/alex-hoagland/ColoradoMedicaidProjects)
* ["An Ounce of Prevention or a Pound of Cure? The Value of Health Risk Information"](https://github.com/alex-hoagland/Caretaker_Spending) (under construction)
* ["Who Do Innovations Reach? The Impact of Trainings on Mental Health Treatments"](https://github.com/alex-hoagland/innovations-mental-health) (under construction)

{% include base_path %}

{% for post in site.dataandcode reversed %}
  {% include archive-single.html %}
{% endfor %}
