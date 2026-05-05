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
@article{Kurniati2025,
  author  = {Kurniati, A. B. and Bakar, M. A. and Ibrahim, N. F. and Harun, H. F.},
  title   = {Enhancing artificial neural network learning efficiency through Singular Value Decomposition for solving partial differential equations},
  journal = {Results in Applied Mathematics},
  volume  = {25},
  pages   = {100522},
  year    = {2025},
  doi     = {10.1016/j.rinam.2024.100522},
  url     = {https://doi.org/10.1016/j.rinam.2024.100522},
  issn    = {2590-0374},
  publisher = {Elsevier}
}

