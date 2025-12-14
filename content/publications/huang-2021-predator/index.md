---
title: "PREDATOR: Registration of 3D Point Clouds with Low Overlap"
date: 2021-03-19
publishDate: 2021-03-19T01:18:36.552293Z
authors: ["Shengyu Huang", "Zan Gojcic", "Mikhail Usvyatsov", 
"Andreas Wieser", "Konrad Schindler"]
featured: false
publication: "*CVPR2021*"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

abstract:
  "We introduce PREDATOR, a model for pairwise point-cloud registration with deep attention to the overlap region. Different from previous work, our model is specifically designed to handle (also) point-cloud pairs with low overlap. Its key novelty is an overlap-attention block for early information exchange between the latent encodings of the two point clouds. In this way the subsequent decoding of the latent representations into per-point features is conditioned on the respective other point cloud, and thus can predict which points are not only salient, but also lie in the overlap region between the two point clouds. The ability to focus on points that are relevant for matching greatly improves performance: PREDATOR raises the rate of successful registrations by more than 20% in the low-overlap scenario, and also sets a new state of the art for the 3DMatch benchmark with 89% registration recall."

# Summary. An optional shortened abstract.
summary: "A model for pairwise point-cloud registration with deep attention to the overlap region."

links:
- type: pdf
  url: https://arxiv.org/pdf/2011.13005.pdf
- type: code
  url: https://github.com/overlappredator/OverlapPredator

---
