---
title: "Image and Video Recovery"
excerpt: "<img width='50%' src='/images/previews/spad_iccp.png'>"
collection: portfolio
--- 

## Publications

{% for post in site.publications reversed %}
  {% if post.categories contains 'Image-Restoration' %} 
    {% include archive-single-publication.html %}
  {% endif %}
  {% if post.categories contains 'SPAD' %}
    {% include archive-single-publication.html %}
  {% endif %}
{% endfor %}
