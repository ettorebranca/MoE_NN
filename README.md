README

This repository contains the PyTorch re-implementation of the sparsely-gated MoE layer described in the paper ["Outrageously Large Neural Networks"](https://arxiv.org/abs/1701.06538), linked by the paper: ["A Review of Sparse Expert Models in Deep Learning"](https://arxiv.org/abs/2209.01667).


The file MoE.ipynb illustrates how to build, train and evaluate the MoE model with inputs and outputs taken from CIFAR10. To run it:
jupyter nbconvert --execute MoE.ipynb  

The code is based on the TensorFlow implementation that can be found here:
https://github.com/tensorflow/tensor2tensor/blob/master/tensor2tensor/utils/expert_utils.py
