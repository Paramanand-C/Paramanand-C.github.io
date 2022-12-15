---
title: "Robustness"
excerpt: "<img width='50%' src='/images/previews/adv_deblur.png'>"
collection: portfolio
--- 

## Publications

{% for post in site.publications reversed %}
  {% if post.categories contains 'Robustness' %}
    {% include archive-single-publication.html %}
  {% endif %}
{% endfor %}

## Current Work
Robustness of CT reconstruction

Improving robustness of histopathological image classification
