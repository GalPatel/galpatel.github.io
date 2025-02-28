---
title: "On Neurons Invariant to Sentence Structural Changes in Neural Machine Translation"
collection: publications
permalink: /publication/2021-10-01-on-neurons-invariant-to-sentence-structural-changes-in-neural-machine-translation
excerpt: 'This paper is about the detection and control of neuron activation patterns when meaning-preserving paraphrases are given as input.'
venue: 'CoNLL 2022'
paperurl: 'https://arxiv.org/abs/2110.03067'
author: 'Gal Patel, Leshem Choshen and Omri Abend'
---
This paper is about the detection and control of neuron activation patterns when meaning-preserving paraphrases are given as input.

[[arXiv](https://arxiv.org/abs/2110.03067)]

## Abstract
To gain insight into the role neurons play, we study the activation patterns corresponding to meaning preserving paraphrases (e.g., active-passive). We compile a dataset of controlled syntactic paraphrases in English with their reference German translations and demonstrate our model-agnostic approach on the Transformer translation model. First, we identify neurons that correlate across paraphrases and examine the observed correlation for possible confounds. Although lower-level components (e.g., position embeddings) are found as the cause of similar activations, we identify no localizable set of neurons that specifically encode these paraphrases. We further manipulate neuron activations to influence translation towards a particular syntactic form. We find that a simple value shift is effective, and more so when many neurons are modified. This may suggest that complex syntactic constructions are indeed encoded in the model. We conclude by discussing how to better manipulate it using the correlations we first obtained.



