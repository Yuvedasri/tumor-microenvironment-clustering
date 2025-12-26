
# Tumor Microenvironment Clustering using Statistical Machine Learning

## Overview
Tumors are not uniform structures; different regions within the same tumor can
exhibit distinct biological behaviors depending on local conditions such as
immune activity, oxygen availability, and growth dynamics.

This project explores tumor heterogeneity by simulating a tumor microenvironment
and applying **unsupervised statistical machine learning** to automatically
discover distinct spatial regions without predefined labels. The focus is on
**discovery-oriented analysis**, rather than prediction.

---

## Why This Project Matters
Understanding tumor microenvironment heterogeneity is critical for:
- Interpreting cancer progression
- Designing effective therapies
- Supporting exploratory biomedical research

Rather than assuming known categories, this project enables **pattern discovery**
and **serendipitous insights**, aligning with modern data-driven cancer research
approaches.

---

## Dataset Description
A biologically inspired **synthetic dataset** representing 400 tumor regions was
generated to enable controlled experimentation and interpretability.

Each tumor region is described by:
- Spatial coordinates (x, y)
- Immune activity
- Structural (stromal) support
- Oxygen availability
- Blood supply
- Cellular growth rate

Synthetic data allows validation of methodology while remaining directly
transferable to real spatial transcriptomics datasets.

---

## Methodology
- Feature standardization using `StandardScaler`
- Unsupervised clustering using **K-Means**
- Spatial visualization of discovered clusters
- Cluster-wise feature interpretation

The model is not given any biological labels and must identify structure
purely from data patterns.

---

## Results & Interpretation
The clustering process reveals distinct tumor microenvironment regions, including:
- Immune-dominant areas
- Hypoxic (low-oxygen) regions
- Support-heavy stromal zones
- Mixed transitional regions

These results demonstrate the heterogeneous nature of tumors and the value of
region-level analysis.

---

## Project Structure

