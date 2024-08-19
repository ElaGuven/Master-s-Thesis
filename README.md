# A Comparative Analysis of Autoencoders for Credit Card Fraud Detection

## Overview

This repository contains the code and analysis for the master's thesis titled "A Comparative Analysis of Autoencoders for Credit Card Fraud Detection." The study explores the effectiveness of various autoencoder models, integrated with a Multilayer Perceptron (MLP) classifier, in detecting fraudulent credit card transactions using the European Cardholders dataset from Kaggle.

## Abstract

The increase in credit card usage has led to a rise in fraudulent transactions, resulting in significant financial losses for institutions and governments. This study investigates the effectiveness of different autoencoder models combined with a Multilayer Perceptron (MLP) classifier for credit card fraud detection. The research focuses on addressing the class imbalance in the dataset using the Borderline-SMOTE technique and compares three models:

1. **Standalone MLP**
2. **MLP with Standard Autoencoder**
3. **MLP with Variational Autoencoder (VAE)**

### Key Findings

- The **Standalone MLP** model achieved the best overall performance with a precision of 0.77, a recall of 0.82, and an F1 score of 0.79.
- Integrating a **Standard Autoencoder** with the MLP did not significantly enhance performance, showing lower precision and recall.
- The **VAE-integrated MLP** model outperformed the standard autoencoder model by better capturing complex data patterns, achieving a precision of 0.82 and a recall of 0.66.
- Both the autoencoder and VAE models exhibited high recall but low precision across different transaction amounts and temporal intervals.

### Conclusion

This study highlights the potential of the VAE-integrated model in capturing meaningful representations from the dataset. The findings suggest that future research should explore the strengths of VAEs and MLPs within hybrid models for more effective fraud detection systems.



