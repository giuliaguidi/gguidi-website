---
title: "Popcorn: Accelerating Kernel K-means on GPUs through Sparse Linear Algebra" 
date: 2025-03-05
lastmod: 2024-11-15
author: ["Julian Bellavita", "Thomas Pasquali", "Laura Del Rio", "Flavio Vella", "Giulia Guidi"]

---

---

##### Download

+ Coming soon!

<!--- + [Paper](paper1.pdf)
+ [Online appendix](appendix1.pdf)
+ [Code and data](https://github.com/pmichaillat/feru) --->

---

##### Abstract

K-means is a versatile and popular clustering algorithm with applications in numerous scientific and engineering areas, such as computational biology, economics, and machine learning. One drawback of K-means is its inability to identify non-linearly separable clusters, which may lead to inaccurate solutions in certain cases. Kernel K-means is a variant of classical K-means that can find non-linearly separable clusters. However, it scales quadratically with respect to the size of the dataset, taking several minutes to cluster even medium-sized datasets on traditional CPU-based machines.

In this paper, we present a formulation of Kernel K-means using sparse-dense matrix multiplication (SpMM) and sparse matrix-vector multiplication (SpMV), and we show that our formulation enables the rapid implementation of a performant GPU-based version of Kernel K-means with minimal programming effort. Our implementation, named Popcorn, is the first open-source GPU-based implementation of Kernel K-means.

Popcorn achieves a speedup of up to 123.8× over a CPU implementation of Kernel K-means and a speedup of up to 2.6× over a GPU implementation of Kernel K-means that does not use sparse matrix computations. Our results support the effectiveness of sparse matrices as tools for efficient parallel programming.

---

##### Citation

Bellavita, Julian, Pasquali, Thomas, Del Rio, Laura, Vella, Flavio, and Guidi, Giulia. "Popcorn: Accelerating Kernel K-means on GPUs through Sparse Linear Algebra." Proceedings of the 25th ACM SIGPLAN Symposium on Principles and Practice of Parallel Programming (PPoPP), 2025.

```BibTeX
@article{popcorn2025,
  title={{Popcorn: Accelerating Kernel K-means on GPUs through Sparse Linear Algebra}},
  author={Bellavita, Julian and Pasquali, Thomas and Del Rio, Laura and Vella, Flavio and Guidi, Giulia},
  journal={Proceedings of the 25th ACM SIGPLAN Symposium on Principles and Practice of Parallel Programming (PPoPP)},
  year={2025}
}
```

---

##### Related material

+ Coming soon!
<!---
+ [Presentation slides](presentation1.pdf) --->
