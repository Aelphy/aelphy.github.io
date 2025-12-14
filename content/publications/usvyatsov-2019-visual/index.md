---
title: "Visual recognition in the wild by sampling deep similarity functions"
date: 2019-01-01
publishDate: 2019-01-01T01:18:36.553870Z
authors: ["Mikhail Usvyatsov", "Konrad Schindler"]
publication_types: ["conference"]
featured: false
publication: "*2019 International Conference on Robotics and Automation (ICRA)*"
doi: "10.1109/ICRA.2019.8794162"

links:
- type: pdf
  url: https://arxiv.org/pdf/1903.06837.pdf
- type: code
  url: https://github.com/Aelphy/siamese_experiments

abstract: "Recognising relevant objects or object states in its environment is a basic capability for an autonomous robot. The dominant approach to object recognition in images and range images is classification by supervised machine learning, nowadays mostly with deep convolutional neural networks (CNNs). This works well for target classes whose variability can be completely covered with training examples. However, a robot moving in the wild, i.e., in an environment that is not known at the time the recognition system is trained, will often face \emph{domain shift}: the training data cannot be assumed to exhaustively cover all the within-class variability that will be encountered in the test data. In that situation, learning is in principle possible, since the training set does capture the defining properties, respectively dissimilarities, of the target classes. But directly training a CNN to predict class probabilities is prone to overfitting to irrelevant correlations between the class labels and the specific subset of the target class that is represented in the training set. We explore the idea to instead learn a Siamese CNN that acts as similarity function between pairs of training examples. Class predictions are then obtained by measuring the similarities between a new test instance and the training samples. We show that the CNN embedding correctly recovers the relative similarities to arbitrary class exemplars in the training set. And that therefore few, randomly picked training exemplars are sufficient to achieve good predictions, making the procedure efficient."
---
