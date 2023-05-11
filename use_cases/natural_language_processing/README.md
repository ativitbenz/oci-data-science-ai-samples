Natural Language Processing Conda Environment Family Notebooks
==============================================================

The [Natural Language Processing conda environment family](https://docs.oracle.com/en-us/iaas/data-science/using/conda-dem-fam.htm) provides the libraries to perform cutting-edge NLP tasks. This [conda environment family]((https://docs.cloud.oracle.com/en-us/iaas/data-science/using/use-notebook-sessions.htm#conda_understand_environments) contains a set of libraries and frameworks for working with text data and performing natural language processing tasks. This environment includes libraries such as HuggingFace’s Transformers library, keybert, NLTK, Simple-Transformers, Pytorch-Ligthning and UMAP.


The notebooks in this folder are meant to be run in the [Natural Language Processing conda environment family](https://docs.oracle.com/en-us/iaas/data-science/using/conda-nlp-fam.htm) conda environments.

# Descriptions

* `Customer Review Sentiment Analysis`: This folder contains a notebook demonstrating how to perform sentiment analysis on customer reviews using OCI AI-Language service. It includes a sample dataset from a hotel chain, but can be adapted to work with other datasets by following the instructions in the folder. The notebook includes multiple visualizations to help analyzing the reviews such as geo-map of reviewers and also word clouds of the most common positive and negative words in the reviews.
* `bert_classifier_lightning.ipynb`: This notebook shows you how to fine-tune a pre-trained Bert model using PyTorch Lightning for the 20 Newsgroups dataset. You will construct a binary classification model by selecting the data on two topics, `bydate_rec.sport.baseball` and `bydate_sci.space`, to illustrate how to use PyTorch Lightning to solve a text classification task.
* `bert_keyphrase_extraction.ipynb`: This notebook demonstrates the KeyBERT package. KeyBERT enables you to take a BERT model and do keyphrase extraction with it. KeyPhrase extraction has a wide variety of use-cases and is a canonical use-case for state-of-the-art NLP techniques like transformer architecture neural networks. This notebook showcases a domain-specific Keyphrase extraction model called [SPECTER](https://arxiv.org/pdf/2004.07180.pdf) which is an effective Keyphrase extraction model for academic texts.
* `nlp_model_explanation.ipynb`: This notebook demonstrates model explanations on an NLP classifier. It does this using a surrogate model technique called Locally Interpretable Model Explanations (LIME). It focuses on training a Decision Tree multiclass classification model using the 20 Newsgroups dataset. It illustrates how to do this using two different implementations of LIME within the NLP conda pack.
* `nlp_multilabel_classification.ipynb`: This notebook demonstrates how to develop a multi-label text classification model using the Reuters Corpus.
* `pos_tagging.ipynb`: This notebook demonstrates a token classification system for tagging the part of speech.
* `simple_transformers.ipynb`: This notebook demonstrates the capabilities of the Simple Transformers package. Simple Transformers allows for the training, fine-tuning and utilization of large transformer neural network models like BERT and GPT-2. Simple Transformers is a thin wrapper over the huggingface Transformers library. As a result, everything available with Transformers is also available in Simple Transformers. This includes access to thousands of datasets and pre-trained weights.
* `text_exploration.ipynb`: This notebook demonstrates some techniques for exploring a dataset in a way that is both visually appealing and semantically meaningful. You will analyze the `20newsgroups` dataset, which is a collection of forum posts labeled by topic. It will showcase some idiosyncrasies of the dataset, as well as techniques that can be used to post-process your text to get more meaningful results. The notebook showcases the innovative dimensionality reduction library `UMAP` along with the plotting library `Bokeh` for creating 2D visualizations of the forum posts. These kinds of visualizations can be utilized to at a glance understand the general distribution of the dataset as well as the semantic similarity of posts to each other.
* `text_extraction.ipynb`: This notebook demonstrates the usage of the text extraction module in ADS. The text extraction module provides functionality to convert raw and unstructured data files into plain text that can then be further processed and/or saved conveniently as dataframes.
