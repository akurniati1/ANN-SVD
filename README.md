# ANN-SVD

**ANN-SVD** is a hybrid computational framework that integrates *Artificial Neural Networks (ANN)* with *Singular Value Decomposition (SVD)* to improve the efficiency and convergence of solving Partial Differential Equations (PDEs).

The framework incorporates SVD into the neural network architecture by decomposing the weight matrix between the first and second hidden layers. Specifically, **Thin SVD**, **Compact SVD**, and **Truncated SVD** are employed to reduce redundancy in the parameter space while preserving the essential structure of the learned representations.


---

## Key Idea

The core idea of ANN-SVD is to approximate the weight matrix using singular value decomposition:

$$
W \approx U \Sigma V^T
$$

This decomposition enables a more compact representation of the model parameters and facilitates more stable and efficient training.

---

## Publication

The full publication can be accessed via the following DOI:

https://doi.org/10.1016/j.rinam.2024.100522

This work is published in *Results in Applied Mathematics* (Elsevier).

---
## Intellectual Property

Patent ID: LY2024CO6999

Registered at: Malaysia Intellectual Property Office (MyIPO)

---

## Citation

If this work is used in academic research, please cite it as follows:

```bibtex
@article{ANN_SVD_2024,
  title   = {ANN-SVD: A Hybrid Neural Network Framework with Singular Value Decomposition for PDE Solving},
  journal = {Results in Applied Mathematics},
  year    = {2024},
  doi     = {10.1016/j.rinam.2024.100522}
}

