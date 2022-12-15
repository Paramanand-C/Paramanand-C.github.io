---
title: "A Bit Too Much? High Speed Imaging from Sparse Photon Counts"
collection: publications
permalink: /publication/2019-iccp-High-Speed-Imaging-from-Sparse-Photon-Counts
date: 2019-05-15
venue: 'IEEE International Conference on Computational Photography (ICCP)'
paperurl: 'http://Paramanand-C.github.io/files/pdfs/SPAD.pdf'
authors: '<b>Paramanand Chandramouli</b>, Samuel Burri, Claudio Bruschini, Edoardo Charbon, Andreas Kolb'
teaser: /previews/spad_iccp.png
arxiv: 'https://arxiv.org/abs/1811.02396'
categories: [SPAD]
bibtex: true
---

{{ page.authors }}

<img class="pub_teaser" src="../images/previews/spad_iccp.png" alt="Teaser Image" title="teaser" />

## Abstract

> Recent advances in photographic sensing technologies have made it possible to achieve light detection in terms of a single photon. Photon counting sensors are being increasingly used in many diverse applications. We address the problem of jointly recovering spatial and temporal scene radiance from very few photon counts. Our ConvNet-based scheme effectively combines spatial and temporal information present in measurements to reduce noise. We demonstrate that using our method one can acquire videos at a high frame rate and still achieve good quality signal-to-noise ratio. Experiments show that the proposed scheme performs quite well in different challenging scenarios while the existing approaches are unable to handle them.

## Resources

{% if page.paperurl %}<a href=" {{ page.paperurl }} ">[pdf]</a>{% endif %} {% if page.arxiv %}<a href=" {{ page.arxiv }} ">[arxiv]</a>{% endif %} {% if page.code %}<a href=" {{ page.code }} ">[github]</a>{% endif %} {% if page.video %}<a href=" {{ page.video }} ">[video]</a>{% endif %} {% if poster %}<a href=" {{ page.poster }} ">[video]</a>{% endif %}


## Bibtex

@inproceedings{chandramouli2019bit,
  title={A bit too much? High speed imaging from sparse photon counts},
  author={Chandramouli, Paramanand and Burri, Samuel and Bruschini, Claudio and Charbon, Edoardo and Kolb, Andreas},
  booktitle={2019 IEEE International Conference on Computational Photography (ICCP)},
  pages={1--9},
  year={2019},
  organization={IEEE}
}

