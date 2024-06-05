# MoE_NN

This repository contains the PyTorch re-implementation of the sparsely-gated MoE layer described in the paper Outrageously Large Neural Networks ( arXiv:1701.06538 [cs.LG]), linked by the paper [2209.01667] A Review of Sparse Expert Models in Deep Learning (arXiv:2209.01667[cs.LG]).


The file PROGETTO_NN_MoE.ipynb illustrates how to build, train and evaluate the MoE model with inputs and outputs taken from CIFAR10. To run it:
jupyter nbconvert --execute PROGETTO_NN_MoE.ipynb  

The code is based on the TensorFlow implementation that can be found here:
tensor2tensor/tensor2tensor/utils/expert_utils.py at master · tensorflow/tensor2tensor · GitHub .
