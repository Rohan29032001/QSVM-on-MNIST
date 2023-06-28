# QSVM-on-MNIST
We implement Quantum Support Vector Machines using Qiskit to classify images of handwritten digits of 4 vs 9.

We choose 4 and 9 since they look quite similar. So a good model must perform well in classifying these rightly.
This repository contains the following notebooks:
- [Introduction](https://github.com/Rohan29032001/QSVM-on-MNIST/blob/main/QSVM_Introduction_.ipynb): This notebook familiarizes the users with the idea of QSVM.
- [Baselines](https://github.com/Rohan29032001/QSVM-on-MNIST/blob/main/Classical%20Baselines.ipynb): This notebook contains results obtained by various classical kernels.
- [Best results](https://github.com/Rohan29032001/QSVM-on-MNIST/blob/main/QSVM_zz_fm.ipynb): This notebook contains the quantum kernel with the best results.

## Conclusion:
We observe that the quantum kernel's results are very close to the results obtained by the RBF kernel.
