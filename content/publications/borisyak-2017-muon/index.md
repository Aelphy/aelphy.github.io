---
title: "Muon trigger for mobile phones"
authors: ["Maxim Borisyak", "Mikhail Usvyatsov", "Michael Mulhearn", "Chase Shimmin", "Andrey Ustyuzhanin"]
publishDate: "2017-01-01T00:00:00Z"
publication_types: ["article-journal"]
featured: false
publication: "*Journal of Physics: Conference Series*"

abstract:
  "The CRAYFIS experiment proposes to use privately owned mobile phones as a ground detector array for Ultra High Energy Cosmic Rays. Upon interacting with Earth's atmosphere, these events produce extensive particle showers which can be detected by cameras on mobile phones. A typical shower contains minimally-ionizing particles such as muons. As these particles interact with CMOS image sensors, they may leave tracks of faintly-activated pixels that are sometimes hard to distinguish from random detector noise. Triggers that rely on the presence of very bright pixels within an image frame are not efficient in this case.
  We present a trigger algorithm based on Convolutional Neural Networks which selects images containing such tracks and are evaluated in a lazy manner: the response of each successive layer is computed only if activation of the current layer satisfies a continuation criterion. Usage of neural networks increases the sensitivity considerably comparable with image thresholding, while the lazy evaluation allows for execution of the trigger under the limited computational power of mobile phones."

# Summary. An optional shortened abstract.
summary: "Neural architecture that allows for simultaneous optimization of computational cost with per-pixel cross-entropy loss."

links:
- name: pdf
  url: https://arxiv.org/pdf/1709.08605.pdf
- type: slides
  url: https://indico.cern.ch/event/505613/contributions/2227267/attachments/1346831/2031136/Oral-261.pdf
- type: code
  url: https://github.com/Aelphy/muon_trigger

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**auger.org**](https://www.auger.org/images/Cosmic_Rays/15-scientistspr.jpg)'
  preview_only: false
---
