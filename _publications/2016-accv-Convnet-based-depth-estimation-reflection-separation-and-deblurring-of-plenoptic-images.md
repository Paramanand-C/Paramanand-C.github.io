---
title: "Convnet-based depth estimation, reflection separation and deblurring of plenoptic images"
collection: publications
permalink: /publication/2016-accv-Convnet-based-depth-estimation-reflection-separation-and-deblurring-of-plenoptic-images
date: 2016-11-20
venue: 'Asian Conference on Computer Vision'
paperurl: 'http://Paramanand-C.github.io/files/pdfs/accv_lf_reflect.pdf'
authors: '<b>Paramanand Chandramouli</b>, Mehdi Noroozi, Paolo Favaro'
teaser: /previews/accv_lf_reflect.png
arxiv: 'https://arxiv.org/abs/1708.06779'
categories: [Lightfields, Image-Restoration]
bibtex: true
---

{{ page.authors }}

<img class="pub_teaser" src="../images/previews/accv_lf_reflect.png" alt="Teaser Image" title="teaser" />

## Abstract

> In this paper, we address the problem of reflection removal and deblurring from a single image captured by a plenoptic camera. We develop a two-stage approach to recover the scene depth and high resolution textures of the reflected and transmitted layers. For depth estimation in the presence of reflections, we train a classifier through convolutional neural networks. For recovering high resolution textures, we assume that the scene is composed of planar regions and perform the reconstruction of each layer by using an explicit form of the plenoptic camera point spread function. The proposed framework also recovers the sharp scene texture with different motion blurs applied to each layer. We demonstrate our method on challenging real and synthetic images.
## Resources

{% if page.paperurl %}<a href=" {{ page.paperurl }} ">[pdf]</a>{% endif %} {% if page.arxiv %}<a href=" {{ page.arxiv }} ">[arxiv]</a>{% endif %} {% if page.code %}<a href=" {{ page.code }} ">[github]</a>{% endif %} {% if page.video %}<a href=" {{ page.video }} ">[video]</a>{% endif %} {% if poster %}<a href=" {{ page.poster }} ">[video]</a>{% endif %}


## Bibtex

@inproceedings{chandramouli2016convnet,
  title={Convnet-based depth estimation, reflection separation and deblurring of plenoptic images},
  author={Chandramouli, Paramanand and Noroozi, Mehdi and Favaro, Paolo},
  booktitle={Asian Conference on Computer Vision},
  pages={129--144},
  year={2016},
  organization={Springer}
}
