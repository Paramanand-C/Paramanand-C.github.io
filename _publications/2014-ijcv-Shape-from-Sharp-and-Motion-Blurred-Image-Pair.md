---
title: "Shape from Sharp and Motion-Blurred Image Pair"
collection: publications
permalink: /publication/2014-ijcv-Shape-from-Sharp-and-Motion-Blurred-Image-Pair
date: 2013-12-13
venue: 'International Journal of Computer Vision'
paperurl: 'http://Paramanand-C.github.io/files/pdfs/ijcv_blur.pdf'
authors: '<b>Paramanand Chandramouli</b>, Ambasamudram N Rajagopalan' 
categories: [scene-inference]
bibtex: true
---

{{ page.authors }}


## Abstract

> Motion blur due to camera shake is a common occurrence. During image capture, the apparent motion of a scene point in the image plane varies according to both camera motion and scene structure. Our objective is to infer the camera motion and the depth map of static scenes using motion blur as a cue. To this end, we use an unblurred–blurred image pair. Initially, we develop a technique to estimate the transformation spread function (TSF) which symbolizes the camera shake. This technique uses blur kernels estimated at different points across the image. Based on the estimated TSF, we recover the complete depth map of the scene within a regularization framework.
## Resources

{% if page.paperurl %}<a href=" {{ page.paperurl }} ">[pdf]</a>{% endif %} {% if page.arxiv %}<a href=" {{ page.arxiv }} ">[arxiv]</a>{% endif %} {% if page.code %}<a href=" {{ page.code }} ">[github]</a>{% endif %} {% if page.video %}<a href=" {{ page.video }} ">[video]</a>{% endif %} {% if poster %}<a href=" {{ page.poster }} ">[video]</a>{% endif %}


## Bibtex

@article{paramanand2014shape,
  title={Shape from sharp and motion-blurred image pair},
  author={Paramanand, Chandramouli and Rajagopalan, AN},
  journal={International journal of computer vision},
  volume={107},
  number={3},
  pages={272--292},
  year={2014},
  publisher={Springer}
}


