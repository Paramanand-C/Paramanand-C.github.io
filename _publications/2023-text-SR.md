---
title: 'Exploring Open Domain Image Super-Resolution through Text'
collection: publications
permalink: /publication/2023-text-SR
date: 2023-07-29
venue: 'ICML 2023 Workshop on Artificial Intelligence & Human-Computer Interaction'
paperurl: 'http://Paramanand-C.github.io/files/pdfs/aihci_23.pdf'
authors: 'Kanchana Vaishnavi Gandikota*, <b>Paramanand Chandramouli*</b>'
teaser: /previews/aihci.png
categories: [Text-Image,Image-Restoration]
bibtex: true
---

{{ page.authors }}

<img class="pub_teaser" src="../images/previews/aihci.png" alt="Teaser Image" title="teaser" />

## Abstract

>  In this work, we propose for the first time a zero-shot approach for flexible open domain extreme super-resolution of images which allows users to interactively explore plausible solutions by using language prompts. Our approach exploits a recent diffusion based text-to-image (T2I) generative model. We modify the generative process of the T2I diffusion model to analytically enforce data consistency of the solution and explore diverse contents of null-space using text guidance. Our approach results in diverse solutions which are simultaneously consistent with input text and the low resolution images.

## Resources

{% if page.paperurl %}<a href=" {{ page.paperurl }} ">[pdf]</a>{% endif %} {% if page.arxiv %}<a href=" {{ page.arxiv }} ">[arxiv]</a>{% endif %} {% if page.code %}<a href=" {{ page.code }} ">[github]</a>{% endif %} {% if page.video %}<a href=" {{ page.video }} ">[video]</a>{% endif %} {% if poster %}<a href=" {{ page.poster }} ">[video]</a>{% endif %}

## Bibtex

@misc{
gandikota2023exploring,
title={Exploring Open Domain Image Super-Resolution through Text},
author={Kanchana Vaishnavi Gandikota and Paramanand Chandramouli},
booktitle={ICML 2023 Workshop on Artificial Intelligence & Human-Computer Interaction},
year={2023}
}
