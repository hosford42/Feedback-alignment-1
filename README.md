# Feedback-alignment
Back propagation is perhaps one of the most iconic algorithms that has helped bring in widespread interest in deep learning. The algorithm is biologically inspired but research has shown that it is only an approximation to how the brain works. One of the problems with the "bioloical plausibility" of backpropation is famously called the weight transport problem. In this project we are investigating biological plausible implementaions of backpropagation. The algorithm performs weight updates using symmetric backward and forward weights. This kind of update is not seen anywhere between neurons. 

Recently, a paper titled "Random synaptic feedback weights support error backpropagation for deep learning" claimed that the forward and backward weights need not be symmetric. In fact, the backward weights can be a random weight matrix. This method does surprisingly great at learning almost as good as back propagation. 

This new algorithm called Random Feedback Alignment has been implemented in this repository. Feedforward and Convolutional neural networks have been investigated. Three different datasets were investigated:

1. Synthetic data: This data was made using a bunch of random matricies.
2. MNIST data
3. CIFAR-10

The files titled "ANALYSIS-" contain the results.
