---
title: Enhancing Aspect-Based Sentiment Analysis using GraphBased Methods and Large Language Model
publishDate: 2020-03-04 00:00:00
img: /assets/stock-3.jpg
img_alt: Aspect based sentiment analysis
description: |
  Devoped model that predict sentiments towards aspects.
tags:
  - Python
  - NLP
  - Nural Networks
  - LLM
---

The study focuses on enhancing the accuracy of deep learning models for ABSA,
particularly in the domains of laptop reviews and restaurant data.
While traditional sentiment analysis methods provide overall sentiment of a text, they often fail
to capture nuanced perspectives on specific aspects. ABSA addresses this limitation by offering
granular insights into consumer opinions, which is vital for businesses seeking to understand
comprehensive customer feedback. Despite advancements in ABSA research, improving model
accuracy remains a significant challenge, especially in real-world scenarios with non-annotated
datasets. This study seeks to bridge this gap by enhancing existing deep learning models,
contributing to the development of more effective and adaptable ABSA techniques.

The research employs an empirical approach, implementing and comparing three distinct models
for ABSA tasks: ROBERTAGCN: A novel model combining RoBERTa's contextual embeddings with
Graph Convolutional Networks. GAT: A Graph Attention Network-based approach for capturing
structural information in text. LLaMA 3 70B: A Large Language Model. These models were trained
and evaluated on datasets for laptop and restaurant reviews. The study involved comprehensive
data preprocessing, including the creation of custom adjacency matrices for graph-based models.
Performance was assessed using standard metrics such as accuracy, precision, recall, and F1-
score.

The research yielded several key findings. The ROBERTAGCN model demonstrated strong
performance, particularly for laptop reviews, with accuracy 77.90% comparable to BERT
baselines and approaching newer models. The GAT model showed promise but struggled with
neutral sentiments, indicating the need for more sophisticated graph structures. The LLaMA 3
70B model exhibited impressive performance on 100 sample especially for positive and negative
sentiments, though it faced challenges with neutral sentiments.

These results highlight the potential of integrating graph-based approaches with pre-trained
language models for ABSA tasks. The study also underscores the capabilities of large language
models, while identifying areas for improvement, particularly in handling neutral sentiments. Key
implications include the need for more nuanced graph structures in ABSA models, the potential
of few shot learning with large language models, and the ongoing challenge of accurately
classifying neutral sentiments. These findings contribute to the broader field of NLP and data
science, offering insights for developing more accurate and adaptable ABSA techniques for real-
world applications.


