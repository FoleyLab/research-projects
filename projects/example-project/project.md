---
title: "Neural Network Pruning for Efficient Inference"
pi: "timothydmorton"
description: |
  Deep neural networks achieve impressive performance but are often too large
  to deploy in resource-constrained environments. This project investigates
  structured and unstructured pruning techniques that reduce model size and
  inference cost with minimal loss in accuracy.

  You will start by reproducing a baseline pruning result from a well-known
  paper, then experiment with pruning schedules and fine-tuning strategies on
  a small image classification task. The goal is to develop intuition for the
  accuracy/efficiency tradeoff and to understand where pruning succeeds and
  fails.
materials:
  - "https://arxiv.org/abs/1506.02626"
  - "https://arxiv.org/abs/1803.03635"
  - "PyTorch documentation: https://pytorch.org/tutorials/intermediate/pruning_tutorial.html"
goals:
  - "Understand the difference between structured and unstructured pruning"
  - "Reproduce a published pruning result on CIFAR-10 or a similar benchmark"
  - "Analyze the relationship between sparsity level and validation accuracy"
  - "Write a short report summarizing findings and open questions"
---
