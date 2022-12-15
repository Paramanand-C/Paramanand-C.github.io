---
title: "Motion blur for motion segmentation"
collection: publications
permalink: /publication/2013-icip-Motion-blur-for-motion-segmentation
date: 2013-09-15
venue: 'IEEE International Conference on Image Processing'
paperurl: 'http://Paramanand-C.github.io/files/pdfs/Motion_blur_for_motion_segmentation.pdf'
authors: '<b>Paramanand Chandramouli</b>, Ambasamudram Narayanan Rajagopalan'
categories: [Image-Restoration, scene-inference]
bibtex: true
---

{{ page.authors }}

## Abstract

> In this paper, we develop a method for motion segmentation using blur kernels. A blur kernel represents the apparent motion undergone by a scene point in the image plane. When the relative motion between the camera and scene is not restricted to fronto-parallel translations, the shape of the blur kernels can vary across image points. For a dynamic scene, we effectively model motion blur using transformation spread functions (TSFs) which represent the relative motions. Given a set of blur kernels that are estimated at different points across an image, we develop a method to segment them according to their relative motion. We initially group the blur kernels based on their `compatibility'. We refine this initial segmentation by jointly estimating the TSF and removing the outliers.

## Resources

{% if page.paperurl %}<a href=" {{ page.paperurl }} ">[pdf]</a>{% endif %} {% if page.arxiv %}<a href=" {{ page.arxiv }} ">[arxiv]</a>{% endif %} {% if page.code %}<a href=" {{ page.code }} ">[github]</a>{% endif %} {% if page.video %}<a href=" {{ page.video }} ">[video]</a>{% endif %} {% if poster %}<a href=" {{ page.poster }} ">[video]</a>{% endif %}


## Bibtex
@inproceedings{paramanand2013motion,
  title={Motion blur for motion segmentation},
  author={Paramanand, Chandramouli and Rajagopalan, AN},
  booktitle={2013 IEEE International Conference on Image Processing},
  pages={4244--4248},
  year={2013},
  organization={IEEE}
}


