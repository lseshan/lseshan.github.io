---
title: machineLearn-part1
draft: true
tags:
---

# Machine Learning

I would like to undertand the Machine Learning infrastructure. What it takes to build a machine learning pipeline? What does it take to train a model?
In the process of answering all the questions related to ML Infra, ML Ops, I am writing down the gist of what I read.

## Pytorch vs Tensor
 
<TO Do Expand more on Pytorch and Tensro>
 Both of them are ML infra.
 Tensor is developed by Google. While pytorch came from meta. Currently Pytorch is the most favoured infra among ML engineers.

### why pytorch won? (did it or the contest is still on)

Pytorch is felxible. There are two modes  
Eager mode:
This is similar to python scripted execution. Execute it line by line 

Graph Mode:
  There are two phases where you collect the represent the  operation as a computation graph in the first phase.
  In the second phase, you execute the optimised graph.

Pytorch used Eager mode by default.

Nearly every generative model is Pytorch based. And even google generative model is Jax based, another google ML framework.

### Did Eager mode solved all the problem of ML training?
   Eager mode required lot of back and forth in fetching data from memory for compute.
   Over the years FLOPS improved in GPUs but  memory did not improve at the same rate.
   This is mainly due to the inverted memory pyramid. Cheap Memory is slow while a fast memory is costly.
   <Memory wall>

