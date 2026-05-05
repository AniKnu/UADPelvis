## Abstract

**Purpose:** To establish a disease- and parameter-agnostic framework for 
unsupervised anomaly detection in pelvic MRI, enabling real-time-compatible 
identification of pathological regions without labeled pathological data.

**Methods:** 294 (2,820 slices) exclusively healthy sagittal T2-weighted pelvic 
scans acquired across a wide range of imaging protocols were augmented with 
synthetically generated data. A residual variational autoencoder was trained on 
this healthy cohort, and during inference, reconstruction error heatmaps highlight 
deviations from learned healthy anatomy. Model performance was evaluated 
quantitatively on the publicly available Uterine Myoma MRI Dataset (UMD) and 
through inter-observer clinical assessment across endometrial cancer, 
endometriosis, and adenomyosis cases.

**Results:** The framework achieved an AUC of 0.736, with sensitivity of 0.828 
and specificity of 0.692 on the UMD dataset, at a reconstruction speed of 
~92.6 frames per second. Inter-observer evaluation revealed the influence of 
anatomical heterogeneity and observer variability on performance interpretation 
across additional pathologies.

**Conclusions:** The proposed framework establishes a baseline for real-time 
unsupervised anomaly detection in the female pelvis, supporting future clinical 
integration without disease-specific training. Prospective datasets are available 
for academic collaboration.

---

**Code:** will be made available soon
