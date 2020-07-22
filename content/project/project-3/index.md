---
date: "2020-05-09T00:00:00Z"
external_link: ""
# https://yirunwang.shinyapps.io/graft_survival_risk_calculator/
image:
  caption: image courtesy of Unsplash @nci
  focal_point: Smart
summary: Choosing the right machine learning algorithm for optimal prediction outcomes
tags:
- Genome
- Kidney transplant
- Machine Learning
- Shiny App
- R
title: Biostatistics
---

> Often times, gene expression data is used to help develop models in order to predict a patient’s rejection status after receiving a kidney transplant.

__Background__

Three machine learning algorithms are investigated, k-nearest neighbours, random forest and support vector machine. In order to find the top performing algorithm that works the best on gene expression data, 5-fold cross validation is repeated 25 times and two evaluation metrics, accuracy and F1 score, are calculated to assess the performance of each classifier.

Check out the [model evaluation app](https://yirunwang.shinyapps.io/gene_expression_data_model_eval/).

