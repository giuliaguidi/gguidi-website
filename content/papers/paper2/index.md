---
title: "BELLA: Berkeley Efficient Long-Read to Long-Read Aligner and Overlapper"
date: 2021-07-15
lastmod: 2024-11-15
author: ["Giulia Guidi", "Marquita Ellis", "Daniel Rokhsar", "Katherine Yelick", "Aydın Buluç"]

---

---

##### Download

+ [Paper](https://people.eecs.berkeley.edu/~aydin/bellasiamacda2021.pdf)
+ [GitHub](https://github.com/PASSIONLab/BELLA)

---

##### Abstract

Recent advances in long-read sequencing allow characterization of genome structure and its variation within and between species at a resolution not previously possible. Detection of overlap between reads is an essential component of many long-read genome pipelines, such as de novo genome assembly. Longer reads simplify genome assembly and improve reconstruction contiguity, but current long-read technologies are associated with moderate to high error rates. In this work, we present Berkeley Efficient Long-Read to Long-Read Aligner and Overlapper (BELLA), a novel overlap detection and alignment algorithm using sparse matrix-matrix multiplication. We introduce a notion of reliable k-mers and a new method based on Chernoff bounds to separate true overlaps from false positives. BELLA achieves high precision and recall, improving de novo assembly quality on synthetic data when coupled with the miniasm assembler.

---

##### Citation

Guidi, Giulia, Ellis, Marquita, Rokhsar, Daniel, Yelick, Katherine, and Buluç, Aydın. "BELLA: Berkeley Efficient Long-Read to Long-Read Aligner and Overlapper." SIAM Conference on Applied and Computational Discrete Algorithms (ACDA21), 2021.

```BibTeX
@article{bella2021,
  title={{BELLA: Berkeley Efficient Long-Read to Long-Read Aligner and Overlapper}},
  author={Guidi, Giulia and Ellis, Marquita and Rokhsar, Daniel and Yelick, Katherine and Buluç, Aydın},
  journal={SIAM Conference on Applied and Computational Discrete Algorithms (ACDA21)},
  year={2021}
}
```
