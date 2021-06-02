# Analysis of classifiers robust to noisy labels

![Paper](https://arxiv.org/abs/2106.00274)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1jv1smzbxTI9vVtgZ962vpO2rMYb7Tx1G?usp=sharing)

We explore contemporary robust classification algorithms for overcoming class-dependant labelling noise: Forward, Importance Reweighting and T-revision. The classifiers are trained and evaluated on class-conditional random label noise data while the final test data is clean. We demonstrate methods for estimating the transition matrix in order to obtain better classifier performance when working with noisy data. We apply deep learning to three data-sets and derive an end-to-end analysis with unknown noise on the CIFAR dataset from scratch. The effectiveness and robustness of the classifiers are analysed, and we compare and contrast the results of each experiment are using top-1 accuracy as our criterion.
