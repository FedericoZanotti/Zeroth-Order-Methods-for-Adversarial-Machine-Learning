# Zeroth Order Methods for Adversarial Machine Learning
**Source Code**:  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1wFLxumXQa2iKW_kLNbzbgCd6fuvu4f1X)

In this work a colleague and I implemented three algorithms:
- Zeroth-Order Stochastic Conditional Gradient Method (**ZSCG**)
- Faster Zeroth-Order Frank-Wolfe Method (**FZFW**)
- Faster Zeroth-Order Conditional Gradient Sliding Method (**FZCGS**)

The first algorithm is defined in [Zeroth-order (Non)-Convex Stochastic Optimization
via Conditional Gradient and Gradient Updates](https://proceedings.neurips.cc/paper/2018/file/36d7534290610d9b7e9abed244dd2f28-Paper.pdf) while the others are defined in [Can Stochastic Zeroth-Order Frank-Wolfe Method Converge Faster for Non-Convex Problems?](http://proceedings.mlr.press/v119/gao20b/gao20b.pdf).

This work focuses on implementing the algorithms in Adversarial Machine Learning scenarios. In particular the **MINST** database is used and the task was to find the universal perturbation &delta such that the Deep Neural Network makes an incorrect classification. To achieve this objective a loss function is optimized by ZSCG, FZFW, FZCGS:

&alfa; | &#968; | Greek small letter psi | ψ |                                                                         


