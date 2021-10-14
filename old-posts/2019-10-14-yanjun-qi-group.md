---
layout: post
title: Two Short Talks from Prof. Yanjun Qi's Group
---

- **Date**: Friday October 18, 2019
- **Time**: 12:00PM
- **Location**: Rice 242

**Title**: Neural Message Passing for Multi-Label Classification<br>
**Speaker**: [Jack Lanchantin](http://www.cs.virginia.edu/~jjl5sw/)

**Abstract**: Multi-label classification (MLC) is the task of assigning a set of target labels for a given sample. Modeling the combinatorial label interactions in MLC has been a long-haul challenge. We propose Label Message Passing (LaMP) Neural Networks to efficiently model the joint prediction of multiple labels. LaMP treats labels as nodes on a label-interaction graph and computes the hidden representation of each label node conditioned on the input using attention-based neural message passing. Attention enables LaMP to assign different importance to neighbor nodes per label, learning how labels interact (implicitly). The proposed models are simple, accurate, interpretable, structure-agnostic, and applicable for predicting dense labels since LaMP is incredibly parallelizable. We validate the benefits of LaMP on seven real-world MLC datasets, covering a broad spectrum of input/output types and outperforming the state-of-the-art results. Notably, LaMP enables intuitive interpretation of how classifying each label depends on the elements of a sample and at the same time rely on its interaction with other labels.

**Title**: FastGSK: Fast and Efficient SequenceAnalysis using Gapped String Kernels<br>
**Speaker**: Derrick Blakely

**Abstract**: Character-level string kernel methods achieve strong classification performance on DNA, protein, and text data using modestly-sized training sets. However, existing methods suffer from slow kernel computation time and overfitting, owing to the exponential dependence between the alphabet size and n-gram length. In this work, we introduce a new character-level string kernel algorithm using gapped n-grams, called FastGSK. We formulate the kernel function as a series of independent counting operations, which we sample to obtain a fast approximation algorithm. This work enables state-of-the-art string kernel methods to scale to any alphabet size (DNA, protein, or natural language) and use longer features. Moreover, we use a modern software architecture with a multithreaded implementation backend and a PyPi package frontend. We experimentally show that FastGSK matches or outperforms existing string kernel methods, as well as recurrent neural networks, across a variety of sequence analysis tasks.
