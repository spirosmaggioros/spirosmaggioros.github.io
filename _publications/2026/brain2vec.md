---
title: Brain2Vec: A Self-Supervised 3D Foundation Model
for Structural Brain MRI
date: TBA
selected: true
pub: "ArXiv"
pub_date: "2026"
abstract: Deep learning models have become essential tools in medical imaging, yet train-
ing them end-to-end for diverse tasks remains challenging due to limited labeled
data and computational constraints. To address this, we introduce Brain2Vec, a
foundation model pre-trained on 74,425 T1-weighted MRI scans pooled from
multiple studies within the iSTAGING consortium. Brain2Vec can serve both
as a weight initialization backbone for fine-tuning downstream tasks and as a
standalone feature extractor. We evaluate Brain2Vec across three dimensions:
downstream predictive performance, convergence speed, and embedding quality.
Using Brain2Vec’s pretrained weights as initialization and fine-tuning on labeled
data for a brain age prediction task, results demonstrate improved final accuracy
and faster convergence compared to random initialization. Additionally, its frozen
embeddings outperform anatomically defined volumetric features on four of five
downstream classification tasks and perform competitively with a state-of-the-
art foundation model pre-trained on substantially more data. Lastly, we show
that Brain2Vec encodes information primarily from a spatially localized and neu-
roanatomically meaningful set of brain regions, and that manipulating a subset of
latent features produces monotonic, region-specific effects on the reconstructed
anatomy. Brain2Vec code and trained models are available as an open-source pack-
age on https://github.com/CBICA/Brain2Vec. Users can apply Brain2Vec
locally by installing the package, or directly through the NiChart cloud platform
https://cloud.neuroimagingchart.com, where Brain2Vec features can be
derived without requiring local installation or specialized infrastructure.

authors:
- Spiros Maggioros
- Guray Erus
- Gareth Harman
- George Aidinis
- Pratik Chaudhari
- Aristeidis Sotiras
- Christos Davatzikos
links:
    Paper: https://drive.google.com/file/d/14sY7R_YBVky_oycJrUbeCmpqDKlmn0b_/view?usp=sharing
    Code: https://github.com/CBICA/Brain2Vec
---
