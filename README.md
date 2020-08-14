# Deep Learning IMooc Course Documentations

## Environment Setup
On MacOS, we will run TensorFlow and Jupyter Notebook under `virtualenv`.
* Please run in Terminal `sudo pip install --upgrade virtualenv` in Terminal to install `virtualenv`.
* Under `~/tensorflow`, create an virtualenv environment by running `virtualenv --system-site-packages ~/tensorflow`.
* Activate the `virtualenv` environment by running `source ~/tensorflow/bin/activate` and expect to see `(tensorflow) MacBook-Pro:~ yyu196$` in the next line of your command line, indicating we are inside the `virtualenv`. We can exit the `virtualenv` environment by type `deactivate` command.
* We want to also install `tensorflow` in our virtual environment by running `pip install --upgrade tensorflow`. We can confirm the version of our tensorflow by run the following command in python3.
  ```
  >>> import tensorflow as tf
  >>> print(tf.__version__)
  2.2.0
  ```
* Install and start Jupyter Notebook by running `pip install notebook` and `jupyter notebook`.

## Knowledge Summary based on Coursera Deep Learning Specializations
### [Neural Networks and Deep Learning](./Documentations/NeuralNetworksAndDeepLearning.md)
### [Improving Deep Neural Networks](./Documentations/ImprovingDeepNeuralNetworks.md)

## Project Overview
### Deep Learning with Neural Network