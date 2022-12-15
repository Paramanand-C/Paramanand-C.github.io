---
title: "HDR imaging under non-uniform blurring"
collection: publications
permalink: /publication/2012-eccvw-HDR-imaging-under-non-uniform-blurring
date: 2012-10-08
venue: 'European Conference on Computer Vision Workshops'
paperurl: 'http://Paramanand-C.github.io/files/pdfs/eccvw_hdr_non_uniform_deblur.pdf'
authors: 'Vijay Channarayapatna Shivaram, <b>Paramanand Chandramouli</b>, Ambasamudram Narayanan Rajagopalan'
categories: [Image-Restoration]
bibtex: true
---

{{ page.authors }}

## Abstract

> Knowledge of scene irradiance is necessary in many computer vision algorithms. In this paper, we develop a technique to obtain the high dynamic range (HDR) irradiance of a scene from a set of differently exposed images captured using a hand-held camera. Any incidental motion induced by camera-shake can result in non-uniform motion blur. This is particularly true for frames captured with high exposure durations. We model the motion blur using a transformation spread function (TSF) that represents space-variant blurring as a weighted average of differently transformed versions of the latent image. We initially estimate the TSF of the blurred frames and then estimate the latent irradiance of the scene.

## Resources

{% if page.paperurl %}<a href=" {{ page.paperurl }} ">[pdf]</a>{% endif %} {% if page.arxiv %}<a href=" {{ page.arxiv }} ">[arxiv]</a>{% endif %} {% if page.code %}<a href=" {{ page.code }} ">[github]</a>{% endif %} {% if page.video %}<a href=" {{ page.video }} ">[video]</a>{% endif %} {% if poster %}<a href=" {{ page.poster }} ">[video]</a>{% endif %}


## Bibtex
@inproceedings{vijay2012hdr,
  title={HDR imaging under non-uniform blurring},
  author={Vijay, Channarayapatna Shivaram and Chandramouli, Paramanand and Ambasamudram, Rajagopalan},
  booktitle={European Conference on Computer Vision Workshops},
  pages={451--460},
  year={2012},
  organization={Springer}
}


