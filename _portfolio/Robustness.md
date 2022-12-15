---
title: "Robustness"
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
