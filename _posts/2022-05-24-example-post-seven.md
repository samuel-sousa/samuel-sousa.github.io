---
title: CryptoTL - Private, Efficient and Secure Transfer Learning
categories:
- Machine Learning
- Sentiment Analysis
- Convolutional Neural Networks
- Privacy
feature_image: "https://cornell.app.box.com/v/arxiv-logo-png"
---

**Abstract**: Big data has been a pervasive catchphrase in recent years, but dealing with data scarcity has become a crucial question for many real-world deep learning (DL) applications. 
A popular methodology to efficiently enable the training of DL models to perform tasks in scenarios with low availability of data is transfer learning (TL). 
TL allows to transfer knowledge from a general domain to a specific target one. However, such a knowledge transfer may put privacy at risk when it comes to sensitive or private data. 
With CryptoTL we introduce a solution to this problem, and show for the first time a cryptographic privacy-preserving TL approach based on homomorphic encryption that is efficient and feasible for real-world use cases. 
We achieve this by carefully designing the framework such that training is always done in plain while still profiting from the privacy gained by homomorphic encryption. 
To demonstrate the efficiency of our framework, we instantiate it with the popular CKKS HE scheme and apply CryptoTL to classification tasks with small datasets and show the applicability of our approach for sentiment analysis and spam detection. 
Additionally, we highlight how our approach can be combined with differential privacy to further increase the security guarantees. Our extensive benchmarks show that using CryptoTL leads to high accuracy while still having practical fine-tuning and classification runtimes despite using homomorphic encryption. 
Concretely, one forward-pass through the encrypted layers of our setup takes roughly 1s on a notebook CPU.

_Available at [Arxiv](https://arxiv.org/abs/2205.11935)._
