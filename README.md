# probabilistic-bias
This repository contains some code to compute symbolic expressions for the probabilistic estimators of tensorial shape-biases, as explained in the article "Probabilistic Estimators of Lagrangian Shape Biases: Universal Relations and Physical Insights".

This repository contains the following files:
* [IA_isotropic_tensors.py](IA_isotropic_tensors.py):  This is the python module that is used to create numerical representations of the tensors, to symmetrize and orthogonalize them and to compute their algebra. It also contains useful functions to perform tensorial derivatives of the tidal-tensor pdf and compute the estimators of bias-parameters.
* [tensor_algebra.ipynb](tensor_algebra.ipynb): Shows some examples how to evaluate products between different tensors and how to obtain e.g. the covariance matrix of the tidal tensor and its (generalized) inverse. This notebook is a good place to start.
* [IA_tensor_estimators.ipynb](IA_tensor_estimators.ipynb): Shows how to use the tensor algebra to compute the bias estimators, e.g. for the tidal bias and other higher order terms
z
# Requirements
* sympy
* numpy
