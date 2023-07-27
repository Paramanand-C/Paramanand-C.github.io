---
title: "Evaluating Adversarial Robustness of Low dose CT Recovery"
collection: publications
permalink: /publication/2023_midl
date: 2023-04-07
venue: 'Medical Imaging with Deep Learning (MIDL)'
paperurl: 'http://Paramanand-C.github.io/files/pdfs/midl_23.pdf'
authors: 'Kanchana Vaishnavi Gandikota, <b>Paramanand Chandramouli</b>, Hannah Droege, Michael Moeller '
teaser: /previews/166_Gandikota.png
categories: [Robustness]
bibtex: true
---

{{ page.authors }}

<img class="pub_teaser" src="../images/previews/ct_local_attack.png" alt="Teaser Image" title="teaser" />

## Abstract

> Low dose computer tomography (CT) acquisition using reduced radiation or sparse angle measurements is recommended to decrease the harmful effects of X-ray radiation. Recent
works successfully apply deep networks to the problem of low dose CT recovery on benchmark datasets. However, their robustness needs a thorough evaluation before use in clinical
settings. In this work, we evaluate the robustness of different deep learning approaches and classical methods for CT recovery. We show that deep networks, including model
based networks encouraging data consistency are more susceptible to untargeted attacks. Surprisingly, we observe that data consistency is not heavily affected even for these poor
quality reconstructions, motivating the need for better regularization for the networks. We demonstrate the feasibility of universal attacks and study attack transferability across
different methods. We analyze robustness to attacks causing localized changes in clinically relevant regions. Both classical approaches and deep networks are affected by such attacks
leading to change in visual appearance of localized lesions, for extremely small perturbations. As the resulting reconstructions have high data consistency with original measurements,
these localized attacks can be used to explore the solution space of CT recovery problem.

## Resources

{% if page.paperurl %}<a href=" {{ page.paperurl }} ">[pdf]</a>{% endif %} {% if page.arxiv %}<a href=" {{ page.arxiv }} ">[arxiv]</a>{% endif %} {% if page.code %}<a href=" {{ page.code }} ">[github]</a>{% endif %} {% if page.video %}<a href=" {{ page.video }} ">[video]</a>{% endif %} {% if poster %}<a href=" {{ page.poster }} ">[video]</a>{% endif %}

## Bibtex

@inproceedings{
gandikota2023evaluating,
title={Evaluating Adversarial Robustness of Low dose {CT} Recovery},
author={Kanchana Vaishnavi Gandikota and Paramanand Chandramouli and Hannah Dr{\"o}ge and Michael Moeller},
booktitle={Medical Imaging with Deep Learning},
year={2023},
url={https://openreview.net/forum?id=L-N1uAxfQk1}
}
