---
title: spark-udacityml
tags:
---

<!-- vim-markdown-toc GFM -->

* [Spark-Udacity ML](#spark-udacity-ml)
    * [ML in Spark](#ml-in-spark)
    * [Numeric Features:](#numeric-features)

<!-- vim-markdown-toc -->

# Spark-Udacity ML 
This post contains notes related to ML module of Spark Udacity Course

## ML in Spark
There are two libraries in Spark: Spark.ml, Spark.Mllib. In due course of time (Spark 3.0), Spark.mllib will be obsolete
MLlib has:
 - Supervised Learning
 - UnSupervised Learning
 - Feature Computation
 - Hyperparameter tuning
 - Model Evaluation

I have read about / worked with the first two Supervised Learning, Unsupervised learning. But don't have much info about the other features. Hope rest of the course gives some insight into those.

There are two parallelisation in Machine learning:

    * Data Parallelization:
        In this method, large data set is divided into smaller set and trained on the same model. The driver program combined the results.

    * Task Parallelization:
        In this the data is trained multiple different models. Usually models are smaller in this case.

## Numeric Features:
   Scalers, Indexers
