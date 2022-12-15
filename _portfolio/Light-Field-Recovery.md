---
title: "Light field recovery"
excerpt: "<img width='50%' src='/images/previews/lf_implicit.png'>"
collection: portfolio
---

## Research Grants

DFG Grant 'Deep Models for Light Field Acquisition' (2020-2023) 

## Publications

{% for post in site.publications reversed %}
  {% if post.categories contains 'Lightfields' %}
    {% include archive-single-publication.html %}
  {% endif %}
{% endfor %}
