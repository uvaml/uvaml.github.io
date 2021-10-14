---
layout: post
title: An Empirical Comparison on Imitation Learning and Reinforcement Learning for Paraphrase Generation
---

Wanyu Du<br>
Department of Computer Science<br>
University of Virginia

- **Date**: Friday September 27th, 2019
- **Time**: 12:00PM
- **Location**: Rice 242

**Abstract** Paraphrase generation is a fundamental research problem that can benefit many other downstream NLP tasks, such as machine translation, text generation, document summarization, and question answering. Previous methods mainly use supervised learning to learn a paraphrase decoder. Given a source sentence, a decoder will decode the target words step by step from a large vocabulary. However, this type of learning and decoding method always suffers from the exposure bias: the current prediction is conditioned on the ground-truth during training but on previous predictions during decoding, and it may lead to propagating and accumulating errors when decoding the text. To deal with this challenge, both reinforcement learning (RL) and imitation learning (IL) have been widely studied, but the lack of direct comparison leads to only a partial image on their benefits. In this work, we present an empirical study on how RL and IL can help boost the performance of generating paraphrases, with the pointer-generator as a base model. And our experiments on the benchmark datasets show that: (1) imitation learning can constantly perform better than reinforcement learning, and (2) the pointer-generator model with imitation learning can outperform the state-of-the-art methods with a large margin.
