---
title: "Depth from motion and optical blur with an unscented Kalman filter"
collection: publications
permalink: /publication/2012-tip-Depth-from-motion-and-optical-blur-with-an-unscented-Kalman-filter
date: 2013-05-23
venue: 'Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition'
paperurl: 'http://Paramanand-C.github.io/files/pdfs/Depth_From_Motion_and_Optical_Blur_With_an_Unscented_Kalman_Filter.pdf'
authors: '<b>Paramanand Chandramouli</b>, Ambasamudram Narayanan Rajagopalan'
categories: [scene-inference]
bibtex: true
---

{{ page.authors }}

## Abstract

> Space-variantly blurred images of a scene contain valuable depth information. In this paper, our objective is to recover the 3-D structure of a scene from motion blur/optical defocus. In the proposed approach, the difference of blur between two observations is used as a cue for recovering depth, within a recursive state estimation framework. For motion blur, we use an unblurred–blurred image pair. Since the relationship between the observation and the scale factor of the point spread function
associated with the depth at a point is nonlinear, we propose and develop a formulation of unscented Kalman filter for depth estimation. There are no restrictions on the shape of the blur kernel. Furthermore, within the same formulation, we address a special and challenging scenario of depth from defocus with translational jitter. The effectiveness of our approach is evaluated on synthetic as well as real data, and its performance is also compared with contemporary techniques.
## Resources

{% if page.paperurl %}<a href=" {{ page.paperurl }} ">[pdf]</a>{% endif %} {% if page.arxiv %}<a href=" {{ page.arxiv }} ">[arxiv]</a>{% endif %} {% if page.code %}<a href=" {{ page.code }} ">[github]</a>{% endif %} {% if page.video %}<a href=" {{ page.video }} ">[video]</a>{% endif %} {% if poster %}<a href=" {{ page.poster }} ">[video]</a>{% endif %}


## Bibtex
@article{paramanand2011depth,
  title={Depth from motion and optical blur with an unscented Kalman filter},
  author={Paramanand, Chandramouli and Rajagopalan, Ambasamudram N},
  journal={IEEE Transactions on Image Processing},
  volume={21},
  number={5},
  pages={2798--2811},
  year={2011},
  publisher={IEEE}
}



