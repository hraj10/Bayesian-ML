# Bayesian-ML
One in seven women will at some point be diagnosed with breast cancer. With 2.3 million new cases in 2020 alone, breast cancer is the world’s most prevalent cancer type among women and was responsible for close to 700 000 deaths (Ferlay et al. (2020)). In high-income countries (HIC), cancer has overtaken cardiovascular disease as the most common cause of mortality among people aged 35–70 years. Even though especially HICs were able to significantly decrease mortality rates related to breast cancer over the last few years and achieve survival rates of 90% five years beyond the first diagnosis, low-income countries (LIC) lag behind, with countries such as India and South Africa attaining merely 66% and 40%, respectively. In an attempt to reason this gap, The World Health Organisation (2021) concluded that early detec- tion and treatment have been the key to HIC’s success, speeding up recovery and thus reducing mortality. Therefore, especially in the early stages, reliable classification algorithms can play a fundamental role in the battle against breast cancer.

Generally speaking, breast cancer is a disease where a group of abnormal or damaged breast cells grows uncontrollably and spreads to other body parts. These cells may divide rapidly and form lumps of tissue, which are also referred to as tumours. Two types of tumours can be distinguished: benign and malignant. A benign or non-cancerous tumour is typically a slow- growing lump that remains at a certain location and does not invade other, nearby tissues. As the name suggests, these tumours are generally not life-threatening and once removed, they usually don’t grow back. A malignant tumour, on the other hand, is cancerous and may spread into other parts of the body potentially forming new tumours. If not treated early and aggressively, those invading tumours can be lethal and are gradually harder to remove as time passes on. Given its shape, texture and size at a certain stage, a tumour originating from the breast area can thus be classified as a benign lump or breast cancer, after which the appropriate steps have to be taken to provide optimal treatment.

Therefore, for an assignment at LSE, I deployed and evaluated a number of Bayesian machine-learning techniques based on their capabilities to correctly distinguish benign from malignant tumours through the use of multiple control variables. Following previous research, I used the benchmark dataset for many machine learning applications, the Wisconsin Breast Cancer dataset. 

This repository contains two main files: 

## Bayesian classification on Wisconsin breast cancer data.ipynb 

This file addresses the following models:

Classification:

- Naive Bayes
- Gaussian Process Classification

Regression:

- Logistic Regression
- Gaussian Process Regression

## BNN.ipynb

This file considers several neural networks, going from a benchmark neural network to a fully Bayesian neural network:

- A standard neural network not mentioned in the paper but purely used as a benchmark
- A deterministic BNN, containing a probabilistic layer but a deterministic output layer
- A fully probabilistic BNN

