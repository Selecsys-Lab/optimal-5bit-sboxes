# Optimal 5-bit S-Box Dataset

This repository provides a dataset of cryptographically optimal 5-bit bijective S-Boxes.

---

## Overview

These 5-bit S-Boxes are completely random permutations generated without any logical, mathematical, or structural constraints beyond cryptographic quality. Every S-Box in this dataset achieves optimal Differential Probability (DP), optimal Linear Probability (LP), and perfect Strict Avalanche Criterion (SAC deviation of 0.0).

The S-Boxes were discovered using a novel optimization methodology developed at SelecSys Labs. While the search framework itself is work in progress to be detailed in a future publication, this dataset is made available to accompany and support an upcoming paper that utilizes these mappings.

---

## Dataset Format

The dataset is stored in [`sboxes_5b_30k_Batch.csv`](./sboxes_5b_30k_Batch.csv):

- **Format:** Headerless CSV.
- **Content:** Each row represents a single 5-bit bijective S-Box as 32 comma-separated integer mappings $[S(0), S(1), \dots, S(31)]$ where $S(x) \in [0, 31]$.

---

## Authors & Affiliation

- **Author:** Binyamin Alony
- **Supervision:** Prof. Itamar Levi
- **Group:** SelecSys Labs
- **Institution:** Faculty of Engineering, Bar-Ilan University, Ramat Gan, Israel

---

## Citation

If you use this dataset in your research, please cite our forthcoming work (citation details will be updated upon publication):

```bibtex
@misc{alony2026optimal5bitsbox,
  author       = {Binyamin Alony and Itamar Levi},
  title        = {Optimal 5-bit S-Boxes Dataset},
  howpublished = {SelecSys Labs, Faculty of Engineering, Bar-Ilan University},
  year         = {2026},
  note         = {Companion dataset for forthcoming publication}
}
```

---

## License

This dataset is distributed under the terms of the [Creative Commons Attribution 4.0 International License (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).

Copyright (c) 2026 Binyamin Alony, Prof. Itamar Levi, SelecSys Labs, Bar-Ilan University.
