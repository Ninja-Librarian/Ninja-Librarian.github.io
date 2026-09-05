---
layout: default
title: Projects
---

# Data Analytics Projects

A selection of data analysis projects demonstrating experience with SQL, Python, Tableau, Excel, statistical analysis, and machine learning.

{% assign projects = site.projects | sort: "order" %}

{% for project in projects %}

## {{ project.title }}

{{ project.description }}

[View Case Study]({{ project.url | relative_url }})

{% endfor %}
