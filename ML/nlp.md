---
title: Natural Language Processing
has_children: false
parent: Machine Learning
nav_order: 5
---

## Textbooks

- [Foundations of Statistical Natural Language Processing](https://www.cs.vassar.edu/~cs366/docs/Manning_Schuetze_StatisticalNLP.pdf), Christopher Manning & Hinrich Schütze

   Foundational text on natural language processing. Available as free pdf online (linked)

## Introductory tutorials

- [How to solve 90% of NLP problems: a step-by-step guide](https://blog.insightdatascience.com/how-to-solve-90-of-nlp-problems-a-step-by-step-guide-fda605278e4e)

   Written by an insight alumnus. Begins with the simplest NLP method that could work, and then moves on to more nuanced solutions, such as feature engineering, word vectors, and deep learning.

- [A Review of Bert-based models](https://towardsdatascience.com/a-review-of-bert-based-models-4ffdc0f15d58)

   A blog post giving a review of BERT-based models and explains transformers at a high level.

- [What you need to know about the new 2019 Transformer Models](https://www.topbots.com/ai-nlp-research-big-language-models/)
  - XLNet: Generalized Autoregressive Pretraining for Language Understanding
  - ERNIE 2.0: A Continual Pre-training Framework for Language Understanding
  - RoBERTa: A Robustly Optimized BERT Pretraining Approach

- [Text Classification Algorithms: A Survey](https://arxiv.org/pdf/1904.08067.pdf)

    This overview covers different text feature extractions, dimensionality reduction methods, existing algorithms and techniques, and evaluations methods. Finally, the limitations of each technique and their application in real-world problems are discussed

## Methods

- [Flowchart showing which Text Classifying Method to choose](https://developers.google.com/machine-learning/guides/text-classification/step-2-5)

   A flowchart from Google showing which model to use when classifying textual data. They also have a [whole tutorial](https://developers.google.com/machine-learning/guides/text-classification) on text classification.

- [Creating text features](http://uc-r.github.io/creating-text-features)

   From UC Irvine Business Analytics programming guide. If you don’t have enough time to read through the entire post, the following hits on the key components:
  - [Bag-of-words](http://uc-r.github.io/creating-text-features#bag): How to break up long text into individual words.
  - [Filtering](http://uc-r.github.io/creating-text-features#filter): Different approaches to remove uninformative words.
  - [Bag of n-grams](http://uc-r.github.io/creating-text-features#ngrams): Retain some context by breaking long text into sequences of words.
  - [Log likelihood ratio test](http://uc-r.github.io/creating-text-features#likelihood): Identify unique combination of words that are more likely to be used together than not.
  - [Parts of speech](http://uc-r.github.io/creating-text-features#pos): Tag words with their parts of speech (i.e. noun, verb, adjective).

- [Term frequency --- Inverse Document Frequency from Scratch in Python with Real World Example](https://towardsdatascience.com/tf-idf-for-document-ranking-from-scratch-in-python-on-real-world-dataset-796d339a4089)

   Nice blogpost showing how to write your own TD-IDF algorithm to embed documents, and then retrieving documents with a matching score or cosine similarity.

- [What are Word Embeddings for Text](https://machinelearningmastery.com/what-are-word-embeddings/)

   Very brief overview of word embeddings, including using transfer learning with embeddings like [GLoVE](https://nlp.stanford.edu/projects/glove/) or [Word2Vec](https://code.google.com/archive/p/word2vec/).

   [Word Bags vs Word Sequences for Text Classification](https://towardsdatascience.com/word-bags-vs-word-sequences-for-text-classification-e0222c21d2ec)

   Sequence respecting approaches have an edge over bag-of-words implementations when the said sequence is material to classification. Long Short Term Memory (LSTM) neural nets with word sequences are evaluated against Naive Bayes with tf-idf vectors on a synthetic text corpus for classification effectiveness. Uses [Keras](https://keras.io/#you-have-just-found-keras).

## Tools

- [*spaCy*: Industrial Strength Natural Language Processing](https://spacy.io/)

   A very convenient python package with lots of pre-trained models for NLP

- [🤗 transformers: State-of-the-art NLP for everyone:](https://huggingface.co/transformers/index.html)

   🤗 Transformers (formerly known as *pytorch-transformers* and *pytorch-pretrained-bert*) provides general-purpose architectures (BERT, GPT-2, RoBERTa, XLM, DistilBert, XLNet…) for Natural Language Understanding (NLU) and Natural Language Generation (NLG) with over 32+ pre-trained models in 100+ languages and deep interoperability between TensorFlow 2.0 and PyTorch.
