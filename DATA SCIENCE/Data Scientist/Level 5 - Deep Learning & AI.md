<!--
Beacon Innovation Hub — Data Scientist Learning Path
This TXT file contains GitHub Markdown source. Copy the contents into a .md file to render on GitHub.
-->

# Level 5 --- Deep Learning & AI

> Extend strong classical Machine Learning foundations into neural
> networks and modern AI architectures.

**Status:** Advanced pathway

[← Back to Data Scientist Roadmap](README.md)

> Deep learning is not required for every Data Science problem. Always
> compare complex models with simpler baselines.

------------------------------------------------------------------------

## 1. Neural Network Foundations

### Main Video

[![PyTorch Deep
Learning](https://img.youtube.com/vi/Z_ikDlimN6A/maxresdefault.jpg)](https://www.youtube.com/watch?v=Z_ikDlimN6A)

[Watch: Learn PyTorch for Deep
Learning](https://www.youtube.com/watch?v=Z_ikDlimN6A)

### Official Tutorial

-   [PyTorch --- Learn the
    Basics](https://docs.pytorch.org/tutorials/beginner/basics/intro.html)

### Learn

-   [ ] Tensors
-   [ ] Datasets
-   [ ] DataLoaders
-   [ ] Layers
-   [ ] Activation functions
-   [ ] Forward propagation
-   [ ] Loss functions
-   [ ] Backpropagation
-   [ ] Automatic differentiation
-   [ ] Optimizers
-   [ ] Training loops
-   [ ] Validation
-   [ ] Saving/loading models

------------------------------------------------------------------------

## 2. Convolutional Neural Networks

**Use case:** Images and spatially structured data.

### Learn

-   [ ] Convolution
-   [ ] Filters / kernels
-   [ ] Feature maps
-   [ ] Padding
-   [ ] Stride
-   [ ] Pooling
-   [ ] CNN architectures
-   [ ] Image classification
-   [ ] Data augmentation
-   [ ] Overfitting controls

### Practice

Build a small image classifier and compare it against a simple baseline.

------------------------------------------------------------------------

## 3. Sequence Models

### Learn

-   [ ] Sequential data
-   [ ] Recurrent Neural Networks
-   [ ] Hidden states
-   [ ] Vanishing-gradient intuition
-   [ ] LSTM
-   [ ] GRU concepts
-   [ ] Sequence classification

> RNNs and LSTMs remain useful concepts for understanding the
> development of modern sequence modelling even when transformers are
> preferred for many current applications.

------------------------------------------------------------------------

## 4. Attention

-   [ ] Query
-   [ ] Key
-   [ ] Value
-   [ ] Attention scores
-   [ ] Self-attention
-   [ ] Multi-head attention
-   [ ] Positional information

------------------------------------------------------------------------

## 5. Transformers

### Learn

-   [ ] Transformer architecture
-   [ ] Encoder concepts
-   [ ] Decoder concepts
-   [ ] Self-attention
-   [ ] Positional encoding
-   [ ] Tokenization
-   [ ] Embeddings
-   [ ] Pretraining
-   [ ] Fine-tuning

### Recommended Conceptual Resource

-   [The Illustrated
    Transformer](https://jalammar.github.io/illustrated-transformer/)

------------------------------------------------------------------------

## 6. Transfer Learning

-   [ ] Pretrained models
-   [ ] Feature extraction
-   [ ] Fine-tuning
-   [ ] Frozen layers
-   [ ] Domain adaptation concepts
-   [ ] Dataset-size considerations

------------------------------------------------------------------------

## 7. NLP Foundations

-   [ ] Text preprocessing concepts
-   [ ] Tokenization
-   [ ] Bag-of-words concepts
-   [ ] TF-IDF
-   [ ] Word embeddings
-   [ ] Sequence representations
-   [ ] Transformer-based NLP
-   [ ] Text classification
-   [ ] Evaluation

------------------------------------------------------------------------

## 8. Computer Vision Foundations

-   [ ] Image representation
-   [ ] Classification
-   [ ] Data augmentation
-   [ ] CNNs
-   [ ] Transfer learning
-   [ ] Object-detection concepts
-   [ ] Evaluation metrics

------------------------------------------------------------------------

## 9. Generative AI Foundations

This section should remain conceptual until the learner has strong ML
and deep-learning fundamentals.

-   [ ] Generative vs discriminative models
-   [ ] Large Language Models
-   [ ] Prompting concepts
-   [ ] Embeddings
-   [ ] Retrieval concepts
-   [ ] Fine-tuning concepts
-   [ ] Hallucination
-   [ ] Evaluation
-   [ ] Safety and responsible use

------------------------------------------------------------------------

## BIH Deep Learning Lab

Choose a suitable open dataset.

Compare:

``` text
Simple Baseline
      ↓
Classical ML Model
      ↓
Neural Network
```

Answer:

1.  Did the neural network improve performance?
2.  Is the improvement practically meaningful?
3.  What additional computational cost was introduced?
4.  What new failure modes appeared?
5.  Is deep learning justified for the problem?

------------------------------------------------------------------------

## Level 5 Completion Standard

For this level ladies and gentlemen, there will be a series of implementations that one must do to move to the next level. Get access to these by clicking [CHALLENGE 5](Challenges/CHALLENGE5.md)

-   [ ] Build and train a basic neural network.
-   [ ] Explain backpropagation conceptually.
-   [ ] Understand CNN architecture.
-   [ ] Understand RNN/LSTM concepts.
-   [ ] Explain attention and transformer fundamentals.
-   [ ] Apply transfer learning at a basic level.
-   [ ] Understand NLP and computer-vision foundations.
-   [ ] Compare deep models against simpler baselines.
-   [ ] Explain limitations and computational trade-offs.

**Next:** [Level 6 --- MLOps](Level%206%20-%20MLOps.md)
