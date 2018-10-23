[Active Learning for Convolutional Neural Networks: A Core-Set Approach](https://arxiv.org/abs/1708.00489)

Overview
- Most active learning algorithms are heuristic, and not made for general, batch-mode learning
- Many AL algorithms are shown as not effective in batch mode settings
- Formulate this in core-set approach, but in an unsupervised way.
  - Choose representative subset, so that the model can learn with the chosen subset (with labels)
  - Start from a randomly chosen initial set, choose samples that scatters in the feature space. (greedy)

Thoughts
- Multiple Integer Programming is better than k-center-greedy algorithm, but not so much effective. k-center-greedy is good enough.
- Why random sampling is better than other AL algorithms?
  - possible correlation in the chosen samples.
