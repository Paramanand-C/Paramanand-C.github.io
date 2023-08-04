---
title: "Non-Uniform Deblurring in HDR Image Reconstruction"
collection: publications
permalink: /publication/2013-tip-Non-Uniform-Deblurring-in-HDR-Image-Reconstruction
date: 2013-10-01
venue: 'IEEE Transactions on Image Processing'
authors: 'Vijay Channarayapatna Shivaram, <b>Paramanand Chandramouli</b>, Ambasamudram Narayanan Rajagopalan, Rama Chellappa'
categories: [Image-Restoration]
bibtex: true
---

{{ page.authors }}

## Abstract

> Hand-held cameras inevitably result in blurred images caused by camera-shake, and even more so in high dynamic range imaging applications where multiple images are captured over a wide range of exposure settings. The degree of blurring depends on many factors such as exposure time, stability
of the platform, and user experience. Camera shake involves not only translations but also rotations resulting in nonuniform blurring. In this paper, we develop a method that takes input non-uniformly blurred and differently exposed images to extract the deblurred, latent irradiance image. We use transformation spread function (TSF) to effectively model the blur caused by camera motion. We first estimate the TSFs of the blurred images from locally derived point spread functions by exploiting their
linear relationship. The scene irradiance is then estimated by minimizing a suitably derived cost functional. Two important cases are investigated wherein 1) only the higher exposures are blurred and 2) all the captured frames are blurred.

## Resources

{% if page.paperurl %}<a href=" {{ page.paperurl }} ">[pdf]</a>{% endif %} {% if page.arxiv %}<a href=" {{ page.arxiv }} ">[arxiv]</a>{% endif %} {% if page.code %}<a href=" {{ page.code }} ">[github]</a>{% endif %} {% if page.video %}<a href=" {{ page.video }} ">[video]</a>{% endif %} {% if poster %}<a href=" {{ page.poster }} ">[video]</a>{% endif %}


## Bibtex
@article{vijay2013non,
  title={Non-uniform deblurring in HDR image reconstruction},
  author={Vijay, Channarayapatna Shivaram and Paramanand, Chandramouli and Rajagopalan, Ambasamudram Narayanan and Chellappa, Rama},
  journal={IEEE transactions on image processing},
  volume={22},
  number={10},
  pages={3739--3750},
  year={2013},
  publisher={IEEE}
}



