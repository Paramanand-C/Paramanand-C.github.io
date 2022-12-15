---
title: "Unscented transformation for depth from motion-blur in videos"
collection: publications
permalink: /publication/2010-cvprw-Unscented-transformation-for-depth-from-motion-blur-in-videos
date: 2010-06-13
venue: 'IEEE Conference on Computer Vision and Pattern Recognition-Workshops'
paperurl: 'http://Paramanand-C.github.io/files/pdfs/cvprw_unscentend_blur.pdf'
authors: '<b>Paramanand Chandramouli</b>, Ambasamudram Narayanan Rajagopalan'
categories: [scene-inference]
bibtex: true
---

{{ page.authors }}

## Abstract

> In images and videos of a 3D scene, blur due to camera shake can be a source of depth information. Our objective is to find the shape of the scene from its motion-blurred observations without having to restore the original image. In this paper, we pose depth recovery as a recursive state estimation problem. We show that the relationship between the observation and the scale factor of the motion-blur kernel associated with the depth at a point is nonlinear and propose the use of the unscented Kalman filter for state estimation. The performance of the proposed method is evaluated on many examples.

## Resources

{% if page.paperurl %}<a href=" {{ page.paperurl }} ">[pdf]</a>{% endif %} {% if page.arxiv %}<a href=" {{ page.arxiv }} ">[arxiv]</a>{% endif %} {% if page.code %}<a href=" {{ page.code }} ">[github]</a>{% endif %} {% if page.video %}<a href=" {{ page.video }} ">[video]</a>{% endif %} {% if poster %}<a href=" {{ page.poster }} ">[video]</a>{% endif %}


## Bibtex
@inproceedings{paramanand2010unscented,
  title={Unscented transformation for depth from motion-blur in videos},
  author={Paramanand, Chandramouli and Rajagopalan, Ambasamudram N},
  booktitle={IEEE Conference on Computer Vision and Pattern Recognition-Workshops},
  pages={38--44},
  year={2010},
  organization={IEEE}
}



