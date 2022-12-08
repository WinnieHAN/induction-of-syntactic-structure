# Induction of Syntactic Structure
This repo is constructed for collecting and categorizing papers about Induction of Syntactic Structure (Unsupervised Learning of Syntax; Unsupervised Natural Language Syntactic Parsing).
# Introduction
See [introduction](introduction.tex) 

# Catalogue
## [Introduction](#1)
### [Syntactic Parsing](#1.1)
### [Unsupervised Parsing](#1.2)
  - [Evaluating Unsupervised Parsing Approaches](#1.2.1)

## [Unsupervised Dependency Parsing](#2)
* [Motivation](#2.1)
* [Generative Modeling](#2.2)
  - [Preliminary](#2.2.1)
  - [Dependency Models](#2.2.2)
* [Learning](#2.3)
  - [Supervised Parameter Estimation](#2.3.1)
  - [Unsupervised Parameter Learning from MLE](#2.3.2)
* [Generative Approaches](#2.4)
  - [Dependency Model with Valence](#2.4.1)
  - [Neural DMV](#2.4.2)
* [Discriminative Approaches](#2.5)
  - [Autoencoders-based Approaches](#2.5.1)
  - [Variational Autoencoder-based Approaches](#2.5.2)
  - [Discriminative Clustering](#2.5.3)
  - [Self-training based Approach](#2.5.4)
  - [Searching](#2.5.5)

## [Unsupervised Constituency Parsing](#3)
* [Generative Approaches](#3.1)
  - [Structure Learning](#3.1.1)
  - [Parameter Learning](#3.1.2)
* [Discriminative Approaches](#3.2)
  - [Autoencoders-based Approaches](#3.2.1)
  - [Variational Autoencoder-based Approaches](#3.2.2)

## [Emerging Topics](#4)
* [Lexicalized Grammars](#4.1)
* [Multimodal Grammar Induction](#4.2)
* [Structurally Constrained Language Model](#4.3)
* [Syntax Probes](#4.4)
* [Multilingual Grammar Induction](#4.5)

## [Summary and Future Directions](#5)


## [1. Introduction](#6)

<p id="1"></p >

## Syntactic Parsing
<p id="1.1"></p >

## Unsupervised Parsing
<p id="1.2"></p >

### Evaluating Unsupervised Parsing Approaches
<p id="1.2.1"></p >


## [2. Unsupervised Dependency Parsing](#7)
<p id="2"></p >

## [3. Unsupervised Constituency Parsing](#8)

<p id="3"></p >


## Discriminative Approaches
<p id="3.2"></p >

### Autoencoders-based Approaches
<p id="3.2.1"></p >

Compound Probabilistic Context-Free Grammars for Grammar Induction, [paper](https://arxiv.org/abs/1906.10225), [code](https://github.com/harvardnlp/compound-pcfg).

Unsupervised Recurrent Neural Network Grammars, [paper](https://arxiv.org/abs/1904.03746), [code](https://github.com/harvardnlp/urnng).

Unsupervised Latent Tree Induction with Deep Inside-Outside Recursive Autoencoders, [paper](https://arxiv.org/abs/1904.02142), [code](https://github.com/iesl/diora).

Unsupervised Learning of PCFGs with Normalizing Flow. [paper](https://www.aclweb.org/anthology/P19-1234/). [code](https://github.com/lifengjin/acl_flow).

### Variational Autoencoder-based Approaches
<p id="3.2.1"></p >

## [4. Emerging Topics](#9)
<p id="4"></p >


## Dataset

[WSJ](https://catalog.ldc.upenn.edu/LDC99T42), [CTB](https://catalog.ldc.upenn.edu/LDC2005T01), [SPMRL](https://dokufarm.phil.hhu.de/spmrl2014/), and [UD](https://universaldependencies.org/) are widely used. You can check out [XCFG](https://github.com/zhaoyanpeng/xcfg) for treebank preprocessing.



## Grounded Grammar Induction

### Language Acquisition

Bootstrapping Language Acquisition, [paper](https://doi.org/10.1016/j.cognition.2017.02.009), [code](). 

### Visual Groundings

Visually Grounded Compound PCFGs, [paper](https://arxiv.org/abs/2009.12404), [code](https://github.com/zhaoyanpeng/vpcfg).

Visually Grounded Neural Syntax Acquisition, [paper](https://arxiv.org/abs/1906.02890), [code](https://github.com/ExplorerFreda/VGNSL).

## Syntax for Downstream Tasks

Scalable Syntax-Aware Language Models Using Knowledge Distillation. [paper](https://www.aclweb.org/anthology/P19-1337/). [code](#).

Language Modeling with Shared Grammar. [paper](https://www.aclweb.org/anthology/P19-1437/). [code](#).

Learning to Compose Task-Specific Tree Structures, [paper](https://arxiv.org/abs/1707.02786), [code](https://github.com/jihunchoi/unsupervised-treelstm).

Learning Latent Trees with Stochastic Perturbations and Differentiable Dynamic Programming, [paper](https://arxiv.org/abs/1906.09992), [code](https://github.com/FilippoC/diffdp).

## [5. Summary and Future Directions](#10)
<p id="5"></p >


[Some part forked from zhaoyanpeng/syntax-induction-in-deep-learning-era](https://github.com/zhaoyanpeng/syntax-induction-in-deep-learning-era)
