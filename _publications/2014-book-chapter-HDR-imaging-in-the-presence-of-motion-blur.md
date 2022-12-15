---
title: "HDR imaging in the presence of motion blur"
collection: publications
permalink: /publication/2014-book-chapter-HDR-imaging-in-the-presence-of-motion-blur
date: 2014-05-08
venue: 'Book Chapter:Motion Deblurring: Algorithms and Systems,Cambridge University Press'
authors: 'Vijay Channarayapatna Shivaram,  <b>Paramanand Chandramouli</b>, Ambasamudram N Rajagopalan' 
categories: [Image-Restoration]
bibtex: true
---

{{ page.authors }}


## Abstract

> Digital cameras convert incident light energy into electrical signals and present them as an image after altering the signals through different processes which include sensor correction, noise reduction, scaling, gamma correction, image enhancement, color space conversion, frame-rate change, compression, and storage/transmission (Nakamura 2005). Although today’s camera sensors have high quantum efficiency and high signalto-noise ratios, they inherently have an upper limit (full well capacity) for accumulation of light energy. Also, the sensor’s least acquisition capacity depends on its pre-set sensitivity. The total variation in the magnitude of irradiance incident at a camera is called the dynamic range (DR) and is defined as DR=(maximum signal value)/(minimum signal value). Most digital cameras available in the market today are unable to account for the entire DR due to hardware limitations. Scenes with high dynamic range (HDR) either appear dark or become saturated. The solution for overcoming this limitation and estimating the original data is referred to as high dynamic range imaging (HDRI)(Debevec & Malik 1997, Mertens, Kautz & Van Reeth 2007, Nayar & Mitsunaga 2000). Over the years, several algorithmic approaches have been investigated for estimation of scene irradiance (see, for example, Debevec & Malik (1997), Mann & Picard (1995), Mitsunaga & Nayar (1999)). The basic idea in these approaches is to capture multiple images of a scene with different exposure settings and algorithmically extract HDR information from these observations.

{% if page.paperurl %}<a href=" {{ page.paperurl }} ">[pdf]</a>{% endif %} {% if page.arxiv %}<a href=" {{ page.arxiv }} ">[arxiv]</a>{% endif %} {% if page.code %}<a href=" {{ page.code }} ">[github]</a>{% endif %} {% if page.video %}<a href=" {{ page.video }} ">[video]</a>{% endif %} {% if poster %}<a href=" {{ page.poster }} ">[video]</a>{% endif %}


## Bibtex

@incollection{vijay20149,
  title={HDR imaging in the presence of motion blur},
  author={Vijay, Channarayapatna Shivaram and  Paramanand, Chandramouli and Rajagopalan, Ambasamudram N},
  editor={A N Rajagopalan, Rama Chellappa},
  booktitle={Motion Deblurring: Algorithms and Systems},
  chapter={9},
  pages={184-203},
  year={2014},
  publisher={Cambridge University Press}
}
