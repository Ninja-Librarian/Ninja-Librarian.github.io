---
layout: default
title: Projects
---

# Data Analytics Projects

A selection of data analysis projects demonstrating skills in SQL, Python, Tableau, Excel, data visualization, and statistical analysis.

{% assign projects = site.projects | sort: "order" %}

{% for project in projects %}

## {{ project.title }}

{{ project.description }}

[View Case Study]({{ project.url | relative_url }})

{% endfor %}
