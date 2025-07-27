---
title: CryptoTL - Private, Efficient and Secure Transfer Learning
categories:
- Machine Learning
- Sentiment Analysis
- CNN
- Privacy
feature_image: "https://public.boxcloud.com/api/2.0/internal_files/774935251410/versions/832363006815/representations/png_paged_2048x2048/content/1.png?access_token=1!Gvs12-acBkpyBD2fbCkq0y84i2hUAwn_2c7GFBEixgYWc1DjimBNvV6qfLv8ZwKhUivLVm7O5-JKQmiIjKDDzAPMqRFNHJSPF93M0I1PRtdrztGIDwE7P-qoZMIIgy7Nc1LN0pPYV4AXAWMcGi6qAWYpM6bw9KdSWV9d8XsXuG13G2A2H5HPaSdGNp4j5X-XVRtM_b7ARqs7JuMHmFlvN6Pul-t0L-K0wCFaqMneLEGc9jHMsZhKAndxO7dJfQu7XyHsuhXYIC7KkUqvivgONZWPQVfAyqBP9YxE6cLNzTKdw_9u_G73m9jEGutFL8PSa8fV1AivIErLN7FMA3cMtgZzI8L-V9LC7q_OqS5OFLOfJBA3Zm-Ac62_bGuXPlSqDDPdSbFBD1oLgTfnkaNctQdHKU-1xNeJle4O3bsiCpkbtsdiriVs1Bpg0j6ESN634tPMLaB_Z0kxSuMzZ7DIyTf8JD40hvhlFsJ1nbks7pVoXSMdRktueqSbUDBSfkHbdGAZbn0XfCDWUK1e0tKdyLhPfPydHWKxdU8XC2B3Ucqkg4e35Gm3SRqdHQVO43OO3DZIxcdUkLulaQOF0_lhRP0ug_zwROZ5y2LiqkRnD-t9VQUIlugpcxYw6Cu17sWIJp0pFtFvXDG1nTpcbgd1hSKQP5sjod90fJ1L_q_OXQU.&shared_link=https%3A%2F%2Fcornell.app.box.com%2Fv%2Farxiv-logo-png&box_client_name=box-content-preview&box_client_version=3.8.0"
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
