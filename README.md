# SiameseNetwork
Study about Siamese Network
## Learning Objectives
- Understand the architecture of Siamese Networks.
- Calculating loss via the Triplet Loss concept.
## Introduction
Siamese Networks are a class of neural networks designed for comparing two inputs and determining their similarity. They are particularly useful in tasks like one-shot learning where we aim to classify new inputs with very few examples. In this study, we use the Omniglot dataset, which contains images of handwritten characters from various alphabets, to train a Siamese Network for recognizing characters based on similarity.
## Dataset
The Omniglot dataset consists of 20 instances for each of the 1,623 characters from 50 different alphabets. It is often used for evaluating few-shot learning models. You can download it directly using Torchvision:
```python
from torchvision.datasets import Omniglot
train_dataset = Omniglot(root='data/', download=True, transform=your_transform)
```
## Citation
**A Comprehensive Guide to Siamese Neural Networks**:
   [Medium Article by Rinki Agarwal](https://medium.com/@rinkinag24/a-comprehensive-guide-to-siamese-neural-networks-3358658c0513)

**Research Paper**:  
   Koch, Gregory, et al. *"Siamese Neural Networks for One-shot Image Recognition."*  
   [ArXiv Link](https://arxiv.org/pdf/1707.02131)
