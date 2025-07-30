This repository contains code for the paper **“The Golden Ratio Primal–Dual Algorithm with Two New Stepsize Rules for Convex–Concave Saddle‑Point Problems”** by **Santanu Soe, Matthew K. Tam, and V. Vetrivel**.

It provides **Jupyter notebooks (`.ipynb`)** for the numerical experiments evaluating **adaptive** and **partially adaptive** stepsize rules for Golden‑Ratio primal–dual algorithms (GRPDA) initially proposed by  Xiaokai Chang & Junfeng Yang. By improving the original idea of **GRPDA** to remove direct computation of parameters, we study and compare them with **E‑GRPDA**, **P‑GRPDA**, **aEGRPDA**, **Conday_VU**, and **aGRAAL**.

**Applications covered**
- **LASSO**
- **Fused Lasso** (1D total variation)
- **GraphNet** (2D grid graphs)
- **Sparse Logistic Regression** (LIBSVM datasets: `a9a`, `ijcnn1`, `mushrooms`)
- **Image Inpainting** (TV–$L_2$)

Each application has its own folder with a self‑contained notebook that reproduces the figures and results reported in the paper.
