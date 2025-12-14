---
title: "Inference, learning and attention mechanisms that exploit and preserve sparsity in convolutional networks"
date: 2018-01-01
publishDate: 2018-01-01T01:18:36.553322Z
authors: ["Timo Hackel", "Mikhail Usvyatsov", "Silvano Galliani", "Jan D Wegner", "Konrad Schindler"]
publication_types: ["article-journal"]
featured: false
publication: "*International Journal of Computer Vision*"
doi: "10.1007/s11263-020-01302-5"

links:
- type: pdf
  url: https://arxiv.org/pdf/1801.10585.pdf
- type: code
  url: https://github.com/TimoHackel/ILA-SCNN

abstract: "While CNNs naturally lend themselves to densely sampled data, and sophisticated implementations are available, they lack the ability to efficiently process sparse data. In this work we introduce a suite of tools that exploit sparsity in both the feature maps and the filter weights, and thereby allow for significantly lower memory footprints and computation times than the conventional dense framework when processing data with a high degree of sparsity. Our scheme provides (i) an efficient GPU implementation of a convolution layer based on direct, sparse convolution; (ii) a filter step within the convolution layer, which we call attention, that prevents fill-in, i.e., the tendency of convolution to rapidly decrease sparsity, and guarantees an upper bound on the computational resources; and (iii) an adaptation of the back-propagation algorithm, which makes it possible to combine our approach with standard learning frameworks, while still exploiting sparsity in the data and the model."
---
