---
title: "Scene Inference"
collection: portfolio
--- 

## Publications

{% for post in site.publications reversed %}
  {% if post.categories contains 'scene-inference' %}
    {% include archive-single-publication.html %}
  {% endif %}
{% endfor %}

