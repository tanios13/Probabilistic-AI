# Projects in Probabilistic Artificial Intelligence

## Project 0
The task is to implement Bayesian inference in a simple setting. In particular, the setting is as follows. You are given a set of data points which are sampled i.i.d. from one of the following three distributions:

![Alt text](images/task0.png)

In \(35\%\) of the cases, the dataset is drawn from the normal distribution, in \(25\%\) of the cases from the Laplace distribution, and in \(40\%\) of the cases from the Student's t-distribution. Let \(H_i\) denote the event that the data was sampled from \(p_i\) for \(i = 1, 2, 3\). Your task is to implement a Bayes-optimal predictor that, given the dataset \(X\), outputs the posterior probabilities \(P(H_i | X)\) for \(i = 1, 2, 3\).