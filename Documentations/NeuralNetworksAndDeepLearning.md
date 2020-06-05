# Neural Networks and Deep Learning
## Neural Network Basics
  Given $X$, we want to calculate $\hat{y}=P(y=1|X)$. We know $X \in R^{n_X}$, in which $n_X$ is the number of features. Parameters $W \in R^{n_X}$ and $b \in R$. We define the output of a neuron to be\
  $$\hat{y} = \sigma(W^TX + b)$$ (1)