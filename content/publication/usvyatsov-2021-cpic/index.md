---
title: "Cherry-Picking Gradients: Learning Low-Rank Embeddings of Visual Data via Differentiable Cross-Approximation"
date: 2021-07-27
publishDate: 2021-07-27T01:18:36.552293Z
authors: ["Mikhail Usvyatsov",  "Anastasia Makarova", "Rafael Ballester-Ripoll", "Maxim Rakhuba", "Andreas Krause",  "Konrad Schindler"]
featured: true
publication: "*ICCV2021*"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

abstract:
  "We propose an end-to-end trainable framework that processes large-scale visual data tensors by looking at a fraction of their entries only. Our method combines a neural network encoder with a tensor train decomposition to learn a low-rank latent encoding, coupled with cross-approximation (CA) to learn the representation through a subset of the original samples. CA is an adaptive sampling algorithm that is native to tensor decompositions and avoids working with the full high-resolution data explicitly. Instead, it actively selects local representative samples that we fetch out-of-core and on-demand. The required number of samples grows only logarithmically with the size of the input. Our implicit representation of the tensor in the network enables processing large grids that could not be otherwise tractable in their uncompressed form. The proposed approach is particularly useful for large-scale multidimensional grid data (e.g., 3D tomography), and for tasks that require context over a large receptive field (e.g., predicting the medical condition of entire organs). The code is available at https://github.com/aelphy/c-pic"

# Summary. An optional shortened abstract.
summary: "An end-to-end trainable framework that processes large-scale visual data tensors by looking at a fraction of their entries only"

links:
- name: PDF
  url: https://arxiv.org/pdf/2105.14250
- icon: github
  icon_pack: fab
  name: Code
  url: https://github.com/aelphy/c-pic

---
