---
title: "Bilayer Blind Deconvolution With the Light Field Camera"
collection: publications
permalink: /publication/2015-iccvw-Bilayer-Blind-Deconvolution-With-the-Light-Field-Camera
date: 2015-12-07
venue: ' IEEE International Conference on Computer Vision Workshops'
paperurl: 'http://Paramanand-C.github.io/files/pdfs/iccvw_lf_blind_deconv.pdf'
authors: 'Meiguang Jin, <b>Paramanand Chandramouli</b>, Paolo Favaro'
categories: [Lightfields, Image-Restoration]
bibtex: true
---

{{ page.authors }}

## Abstract

> In this paper we propose a solution to blind deconvolution of a scene with two layers (foreground/background). We show that the reconstruction of the support of these two layers from a single image of a conventional camera is not possible. As a solution we propose to use a light field camera. We demonstrate that a single light field image captured with a Lytro camera can be successfully deblurred. More specifically, we consider the case of space-varying motion blur, where the blur magnitude depends on the depth changes in the scene. Our method employs a layered model that handles occlusions and partial transparencies due to both motion blur and out of focus blur of the plenoptic camera. We reconstruct each layer support, the corresponding sharp textures, and motion blurs via an optimization scheme. The performance of our algorithm is demonstrated on synthetic as well as real light field images.
## Resources

{% if page.paperurl %}<a href=" {{ page.paperurl }} ">[pdf]</a>{% endif %} {% if page.arxiv %}<a href=" {{ page.arxiv }} ">[arxiv]</a>{% endif %} {% if page.code %}<a href=" {{ page.code }} ">[github]</a>{% endif %} {% if page.video %}<a href=" {{ page.video }} ">[video]</a>{% endif %} {% if poster %}<a href=" {{ page.poster }} ">[video]</a>{% endif %}


## Bibtex

 @InProceedings{Jin_2015_ICCV_Workshops,
author = {Jin, Meiguang and Chandramouli, Paramanand and Favaro, Paolo},
title = {Bilayer Blind Deconvolution With the Light Field Camera},
booktitle = {Proceedings of the IEEE International Conference on Computer Vision (ICCV) Workshops},
month = {December},
year = {2015}
}

