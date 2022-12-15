---
title: "Non-uniform motion deblurring for bilayer scenes"
collection: publications
permalink: /publication/2013-cvpr-Non-uniform-motion-deblurring-for-bilayer-scenes
date: 2013-06-23
venue: 'Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition'
paperurl: 'http://Paramanand-C.github.io/files/pdfs/Paramanand_Non-uniform_Motion_Deblurring_2013_CVPR_paper.pdf'
authors: '<b>Paramanand Chandramouli</b>, Ambasamudram Narayanan Rajagopalan'
categories: [Image-Restoration]
bibtex: true
---

{{ page.authors }}

## Abstract

> We address the problem of estimating the latent image of a static bilayer scene (consisting of a foreground and a background at different depths) from motion blurred observations captured with a handheld camera. The camera motion is considered to be composed of in-plane rotations and translations. Since the blur at an image location depends both on camera motion and depth, deblurring becomes a difficult task. We initially propose a method to estimate the transformation spread function (TSF) corresponding to one of the depth layers. The estimated TSF (which reveals the camera motion during exposure) is used to segment the scene into the foreground and background layers and determine the relative depth value. The deblurred image of the scene is finally estimated within a regularization framework by accounting for blur variations due to camera motion as well as depth.

## Resources

{% if page.paperurl %}<a href=" {{ page.paperurl }} ">[pdf]</a>{% endif %} {% if page.arxiv %}<a href=" {{ page.arxiv }} ">[arxiv]</a>{% endif %} {% if page.code %}<a href=" {{ page.code }} ">[github]</a>{% endif %} {% if page.video %}<a href=" {{ page.video }} ">[video]</a>{% endif %} {% if poster %}<a href=" {{ page.poster }} ">[video]</a>{% endif %}


## Bibtex
@inproceedings{paramanand2013non,
  title={Non-uniform motion deblurring for bilayer scenes},
  author={Paramanand, Chandramouli and Rajagopalan, Ambasamudram N},
  booktitle={Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition},
  pages={1115--1122},
  year={2013}
}


