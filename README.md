# Learning-Causal-Inference

This repository consists the journey of learning a new topic Causal Inference. Some of the major topics discussed and implemented in this repo are as follows:

- [Statistics Fundamentals](https://github.com/S-acharya57/Learning-Causal-Inference/tree/main/StatisticsAndProbability) : Has basic concepts of statistics useful in Causal Machine Learning.

- [Counterfactuals and their Meaning](https://github.com/S-acharya57/Learning-Causal-Inference/blob/main/Counterfactuals.ipynb): Contains how counterfactuals can be computed via linear regression, and compares them with the ones estimated using libraries.

- [Backdoor Criterion for Effect Estimation](https://github.com/S-acharya57/Learning-Causal-Inference/blob/main/backdoor%20criterion.ipynb) : This notebook dives into the meaning of backdoor criterion, examples of confounders, values computed via linear regression controlling confounders(that backdoor criterion does), and compares its values with that from using library.

- [Average Treatment Effect Basics](https://github.com/S-acharya57/Learning-Causal-Inference/blob/main/Causal%20Inference%20ATE.ipynb) : This implements ATE from scratch with linear regression, and compares with that from dowhy library.

- [Treatment Effect Estimation](https://github.com/S-acharya57/Learning-Causal-Inference/blob/main/Understanding%20Treatment%20Effect%20Estimation.ipynb) : This notebook implements treatment effect on a synthetic data, and explores the findings from their values. This explores difference between ATE and CATE, and why CATE is essential despite ATE is computed.

  - Use of synthetic data with treatment, outcome, and covariates
  - A causal variable that affects the outcome
  - Modeling of ATE Estimation with dowhy causal model
  - CATE for subgroups, divided from the population
  - Change of ATE and CATE, as effect of a treatment variable changes.

- [Matching and Propensity Scores](https://github.com/S-acharya57/Learning-Causal-Inference/tree/main/matching) : Implementation of matching, understanding its importance in understanding causal effects and how it minitages effects of confounders.

  - [Causality in Infant Health and Development Program Dataset ]() : EDA and Causal inference in the dataset. Implementation of propensity score matching from scratch, and comparing the estimated effect with that from the `dowhy` library.

- [Marginal Structural Models](https://github.com/S-acharya57/Learning-Causal-Inference/blob/main/Marginal%20Structural%20Models.ipynb): Implementation of inverse probability weighting to balance the control and treatment variables, without need to ignore or waste available data.
