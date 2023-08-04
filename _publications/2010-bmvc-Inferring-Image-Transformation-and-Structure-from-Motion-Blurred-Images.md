---
title: "Inferring Image Transformation and Structure from Motion-Blurred Images"
collection: publications
permalink: /publication/2010-bmvc-Inferring-Image-Transformation-and-Structure-from-Motion-Blurred-Images
date: 2010-08-30
venue: 'British Machine Vision Conference'
authors: '<b>Paramanand Chandramouli</b>, Ambasamudram Narayanan Rajagopalan'
categories: [scene-inference]
bibtex: true
---

{{ page.authors }}

## Abstract

> This paper deals with the problem of estimating structure of 3D scenes and image
transformations from observations that are blurred due to unconstrained camera motion.
Initially, we consider a fronto-parallel planar scene and relate the reference image of the
scene to its motion-blurred observation by finding the reference image transformations.
The blur kernel at every image point can be determined from these transformations. For
3D scenes, the extent of blurring in the image is related to the camera motion as well
as the scene structure. We propose a technique to estimate the scene depth with the
knowledge of the estimated image transformations. The proposed method is validated by
testing on real and synthetic experiments.

## Resources

{% if page.paperurl %}<a href=" {{ page.paperurl }} ">[pdf]</a>{% endif %} {% if page.arxiv %}<a href=" {{ page.arxiv }} ">[arxiv]</a>{% endif %} {% if page.code %}<a href=" {{ page.code }} ">[github]</a>{% endif %} {% if page.video %}<a href=" {{ page.video }} ">[video]</a>{% endif %} {% if poster %}<a href=" {{ page.poster }} ">[video]</a>{% endif %}


## Bibtex
@inproceedings{chandramouli2010inferring,
  title={Inferring Image Transformation and Structure from Motion-Blurred Images.},
  author={Paramanand, Chandramouli and Rajagopalan, Ambasamudram N},
  booktitle={BMVC},
  pages={1--12},
  year={2010}
}



