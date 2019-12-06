# The Bible of Time Series

Aim of this repo is to provide a useful benchmark to compare state of the art techniques in the filed of time series forecast

### What to expect

This is not a library. The central core of this work is the notebook which is intended both for testing the code but also to provide some documentation and explanation.

Therefore the notebook itself has been structured to cover many important aspects of time series forecast, nevertheless despite the ironical title of the repo it is not a Bible, in the sense that it cannot contains everything. I've done my best to be as exhaustive as possible but basically my main goal was to be practical and to provide concise and practical instructions to people that are already familiar with many concepts beheind and help others to apply advanced concepts (in those cases where there could be necessary) to time series analysis

### Structure of the notebook

The notebook is divided in conceptually separated sections

 - a theoretical introduction with basic concepts of time series
 - main data visualization and exploration techniques
 - a review of classical techniques
 - a review of state of the art architectures for deep learning techniques
 - yet to come:
	 - multivariate prediction
	 - machine learning techniques (with features engineering)

### Practical advices

If you have a GPU that support CUDA you can install tensorflow GPU (up to this date informations, new release of tensorflow will support both CPU and GPU) in this way you can train the networks using GPU computing

The notebook can be better viewed using _jupyter contrib nbextension_, here the link to the docs:

https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/install.html

if you use anaconda you can easily install the extensions with the command

> conda install -c conda-forge jupyter_contrib_nbextensions

Using tensorboard you can compare training performances of different NN architectures by pointing to the logs folder where I have placed the logs of the tests I performed


