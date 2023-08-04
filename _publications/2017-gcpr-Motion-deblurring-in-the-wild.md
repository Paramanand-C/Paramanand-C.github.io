---
title: "Motion Deblurring in the Wild"
collection: publications
permalink: /publication/2017-gcpr-Motion-deblurring-in-the-wild
date: 2017-08-15
venue: 'German Conference on Pattern Recognition'
authors: 'Mehdi Noroozi, <b>Paramanand Chandramouli</b>, Paolo Favaro'
teaser: /previews/gcpr_wild_deblur.png
arxiv: 'https://arxiv.org/abs/1701.01486'
categories: [Image-Restoration]
bibtex: true
---

{{ page.authors }}

<img class="pub_teaser" src="../images/previews/gcpr_wild_deblur.png" alt="Teaser Image" title="teaser" />

## Abstract

>We propose a deep learning approach to remove motion blur from a single image captured in the wild, i.e., in an uncontrolled setting. Thus, we consider motion blur degradations that are due to both camera and object motion, and by occlusion and coming into view of objects. In this scenario, a model-based approach would require a very large set of parameters, whose fitting is a challenge on its own. Hence, we take a data-driven approach and design both a novel convolutional neural network architecture and a dataset for blurry images with ground truth. The network produces directly the sharp image as output and is built into three pyramid stages, which allow to remove blur gradually from a small amount, at the lowest scale, to the full amount, at the scale of the input image. To obtain corresponding blurry and sharp image pairs, we use videos from a high frame-rate video camera. For each small video clip we select the central frame as the sharp image and use the frame average as the corresponding blurred image. Finally, to ensure that the averaging process is a sufficient approximation to real blurry images we estimate optical flow and select frames with pixel displacements smaller than a pixel. We demonstrate state of the art performance on datasets with both synthetic and real images.
## Resources

{% if page.paperurl %}<a href=" {{ page.paperurl }} ">[pdf]</a>{% endif %} {% if page.arxiv %}<a href=" {{ page.arxiv }} ">[arxiv]</a>{% endif %} {% if page.code %}<a href=" {{ page.code }} ">[github]</a>{% endif %} {% if page.video %}<a href=" {{ page.video }} ">[video]</a>{% endif %} {% if poster %}<a href=" {{ page.poster }} ">[video]</a>{% endif %}

## Bibtex

   @inproceedings{noroozi2017motion,
  title={Motion deblurring in the wild},
  author={Noroozi, Mehdi and Chandramouli, Paramanand and Favaro, Paolo},
  booktitle={German conference on pattern recognition},
  pages={65--77},
  year={2017},
  organization={Springer}
}

