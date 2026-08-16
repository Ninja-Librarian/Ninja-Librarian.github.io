---
layout: default
title: Projects
---

# Data Analytics Projects

A selection of data analysis projects demonstrating skills in SQL, Python, Tableau, Excel, data visualization, and statistical analysis.

{% for project in site.projects %}

## {{ project.title }}

{{ project.description }}

[View Case Study]({{ project.url | relative_url }})

{% endfor %}
