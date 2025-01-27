# Experiments on Differentiable Bayesian Structure Learning

This repository contains code and resources for two experiments conducted to explore the principles and limitations of Differentiable Bayesian Structure Learning (DiBS). The experiments are implemented in Python using the official DiBS package by Lorch et al. (2021) ([arXiv:2105.11839](https://arxiv.org/abs/2105.11839)).

## Experiments Overview

The experiments are designed to investigate specific aspects of the DiBS framework:

1. **Experiment 1: The Importance of Selecting an Appropriate Graph Prior**

   *Objective*: Assess the impact of prior selection on the inference performance of DiBS. This experiment examines how the choice of graph prior influences the results, especially when prior knowledge is limited or absent.

2. **Experiment 2: Variability of Edge Inclusion for Different Sample Sizes**

   *Objective*: Analyze how varying sample sizes affect the posterior variance of causal structures inferred by DiBS. The focus is on understanding whether increasing the sample size leads to reduced posterior variance, resulting in more consistent edge selection and improved out-of-sample evaluation metrics.

## Repository Contents

- [`experiments.ipynb`](https://github.com/adrian-io/diff-bayes-struct-learn/blob/main/experiments.ipynb): Contains the implementation of both experiments, following the configuration outlined in the original DiBS study. The setup includes:
  - Number of nodes: \( d = 20 \)
  - Latent dimensionality: \( k = d = 20 \)
  - DiBS run for 3000 SVGD iterations using standard settings

- [`experiment_evaluation.ipynb`](https://github.com/adrian-io/diff-bayes-struct-learn/blob/main/experiment_evaluation.ipynb): Provides the evaluation metrics and plots for the experiments, offering insights into the performance and outcomes of the conducted studies.

## References

For a comprehensive understanding of the DiBS framework, please refer to the original paper:

Lorch, L., Rothfuss, J., Schölkopf, B., & Krause, A. (2021). DiBS: Differentiable Bayesian Structure Learning. *Advances in Neural Information Processing Systems*. [arXiv:2105.11839](https://arxiv.org/abs/2105.11839)

---

*Note: This repository focuses on specific experiments related to the DiBS framework. For the official DiBS package and broader applications, please consult the original DiBS repository.*
