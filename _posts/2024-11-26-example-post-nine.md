---
title: Assessing the impact of differential privacy in transfer learning with deep neural networks and transformer language models
categories:
- Transfer Learning
- Fairness
- GPT
- Trustworthy AI
- Credit Risk Assessment
- Sentiment Analysis
- LSTM
- Convolutional Neural Networks
- Transformers
feature_image: "https://media.springernature.com/w316/springer-static/cover-hires/journal/521?as=webp"
---

**Abstract**: The realization of trustworthy artificial intelligence strongly relies on privacy, fairness, and accountability requirements. 
Although model trustworthiness results from the synergy between these requirements, some effects often clash with one another and may propagate issues into downstream tasks. 
This paper empirically indicates that optimization algorithms with differential privacy (DP), such as differentially private stochastic gradient descent (DP-SGD) and differentially private Adam (DP-Adam), disproportionately increase differences in accuracy between groups and domains in transfer learning based on convolutional neural network (CNN) and long-short-term memory (LSTM) models. 
We investigate the impact of DP-SGD and DP-Adam in transfer learning models, which receive DP noise to hinder privacy risks and perform predictions on target domain data. 
In addition, after extensive experimental evaluation, we provide evidence that fine-tuning may reduce the differences in accuracy for most groups compared to gradient boosting and ensemble methods. 
However, differentially private optimizers may reverse gains in accuracy from transfer learning for CNNs and LSTMs. Unevenly reduced model accuracy may jeopardize the predictions’ fairness, causing numerous real-world implications, such as denying credit to people in need or undermining complex language processing. 
Identifying scenarios where privacy protection conflicts with fairness for transfer learning is a problem often overlooked yet directly aligned with the accountability requirement in trustworthy artificial intelligence. 
Therefore, assessing the impact of differentially private optimizers in transfer learning is the first step to developing mitigation strategies.

_Available at [SpringerLink](https://link.springer.com/article/10.1007/s00521-024-10547-x)._
