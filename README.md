# Awesome Dynamic Inference [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
A curated list for **Dynamic Inference** research in deep learning, including: **dynamic routing networks**, **early prediction networks** and **conditional computation networks**.

Inspired by [awesome-deep-vision](https://github.com/kjw0612/awesome-deep-vision), [awesome-adversarial-machine-learning](https://github.com/yenchenlin/awesome-adversarial-machine-learning), [awesome-deep-learning-papers](https://github.com/terryum/awesome-deep-learning-papers), [awesome-AutoDL](https://github.com/D-X-Y/Awesome-AutoDL.git) and [awesome-architecture-search](https://github.com/markdtw/awesome-architecture-search).

Please feel free to [pull requests](https://github.com/huanyuhello/Awesome-DynamicInference/pulls) or [open an issue](https://github.com/huanyuhello/Awesome-DynamicInference/issues) to add papers.

## Table of Contents

- [Awesome Blogs](#awesome-blogs)

- [Deep Learning-based NAS and HPO](#deep-learning-based-nas-and-hpo)
  - [2020 Venues](#2020)
  - [2019 Venues](#2019)
  - [2018 Venues](#2018)
  - [2017 Venues](#2017)
  - [Previous Venues](#2012-2016)

- [Awesome Surveys](#awesome-surveys)

## Awesome Blogs
- [AutoML info](http://automl.chalearn.org/) and [AutoML Freiburg-Hannover](https://www.automl.org/)
- [What’s the deal with Neural Architecture Search?](https://determined.ai/blog/neural-architecture-search/)
- [Google Could AutoML](https://cloud.google.com/vision/automl/docs/beginners-guide) and [PocketFlow](https://pocketflow.github.io/)
- [AutoML Challenge](http://automl.chalearn.org/) and [AutoDL Challenge](https://autodl.chalearn.org/)

## Related Awesome Libraies
- [Keras Tuner](https://keras-team.github.io/keras-tuner/)
- [NNI](https://github.com/microsoft/nni)
- [AutoGluon](https://autogluon.mxnet.io/)
- [Auto-PyTorch](https://github.com/automl/Auto-PyTorch)
- [AutoDL-Projects](https://github.com/D-X-Y/AutoDL-Projects)
- [awesome-AutoDL](https://github.com/D-X-Y/Awesome-AutoDL.git)

## Dynamic Inference Network methods

|Type| Dynamic Routing (R)|Eraly Prediction (E)|Condictional Computation (C)|Others (O)|
|:------------|:--------------:|:----------------------:|:-----------------------:|:----------------------:|
| Explanation | Skip unnecessary units | Predict with intermediate features |  |  other types |

### 2020


|  Title  |   Venue  |   Type   |   Code   |
|:--------|:--------:|:--------:|:--------:|
| [Learning Dynamic Routing for Semantic Segmentation]() | CVPR | O | - |
| [ScopeFlow: Dynamic Scene Scoping for Optical Flow]() | CVPR | C | - |
| [Dynamic Convolution: Attention over Convolution Kernels]() | CVPR | C | - |
| [Dynamic Convolutions: Exploiting Spatial Sparsity for Faster Inference]() | CVPR | C | - |
| [S2DNAS: Transforming Static CNN Model for Dynamic Inference via Neural Architecture Search]() | CVPR | O | - |
| [Dynamic Graph Message Passing Networks]() | CVPR | C | - |
| [Conditional Channel Gated Networks for Task-Aware Continual Learning]() | CVPR | R | - |
| [Resolution Adaptive Networks for Efficient Inference]() | CVPR | O | - |
| [Dynamic Representations Toward Efficient Inference on Deep Neural Networks by Decision Gates]() | CVPRW | E | - |
| [BATCH-SHAPING FOR LEARNING CONDITIONAL CHANNEL GATED NETWORKS]() | ICLR | R | - |
| [MutualNet: Adaptive ConvNet via Mutual Learning from Network Width and Resolution]() | ECCV | O | - |
| [CoDiNet: Path Distribution Modeling with Consistency and Diversity for Dynamic Routing](https://arxiv.org/abs/2005.14439) | UnKnown | R | - | 
| [Fully Dynamic Inference with Deep Neural Networks]() | UnKnown | R | - |
| [Optimizing Neural Architecture Search using Limited GPU Time in a Dynamic Search Space: A Gene Expression Programming Approach]() | UnKnown | C | - |
| [Dynamic ReLU]() | UnKnown | C | - |
| [Computation on sparse neural networks: an inspiration for future hardware]() | UnKnown | R | - |
| [Spatially adaptive inference with stochastic feature sampling and interpolation]() | UnKnown | R | - |
| [Multi-scale dense networks for resource efficient image classification]() | ICLR | E | - |
| [Dynamic group convolution for accelerating convolutional neural networks]() | | R | - |
| [Discriminative layer pruning for convolutional neural networks]() | | R | - |
| [Dynamic region aware convolution]() | | R | - |
### 2019
|  Title  |   Venue  |   Type   |   Code   |
|:--------|:--------:|:--------:|:--------:|
| [BlockDrop: Dynamic Inference Paths in Residual Networks]() | CVPR | R | - |
| [Improved Techniques for Training Adaptive Deep Networks]() | ICCV | E | - |
| [Universally slimmable networks and improved training techniques]() | ICCV | R | - |

### 2018
|  Title  |   Venue  |   Type   |   Code   |
|:--------|:--------:|:--------:|:--------:|
| [SkipNet: Learning Dynamic Routing in Convolutional Networks]() | ECCV | R | - |
| [Online Multi-Object Tracking with Instance-Aware Tracker and Dynamic Model Refreshment]() | ECCV | C | - |
| [Convolutional Networks with Adaptive Inference Graphs]() | ECCV | R | - | 
| [Slimmable neural networks]() |  | R | - |
| [Multi-scale dense networks for resource efficient image classification]() | ICLR | E | - |
| [Hydranets: Specialized dynamic architectures for efficient inference]() | CVPR | E | - |

### 2012-2017
|  Title  |   Venue  |   Type   |   Code   |
|:--------|:--------:|:--------:|:--------:|
| [Branchynet: Fast inference via early exiting from deep neural networks]() | ICPR | E | - |
| [Adaptive computation time for recurrent neural networks]()| | E | - |
| [Spatially adaptive computation time for residual networks]()| CVPR | C | - |
| [Recurrent segmentation for variable computational budgets]() | CVPR | E | - |
| [Improved techniques for training adaptive deep networks]() | ICCV | E | - |
| [Dynamic channel pruning: Feature boosting and suppression]() | ICLR | C | - |

## Surveys

|  Title  |   Venue  |   Year   |
|:--------|:--------:|:--------:|
