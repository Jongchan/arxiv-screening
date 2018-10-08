[Arxiv link](https://arxiv.org/pdf/1810.02492.pdf)

Keyword

- Multi-modal input, Feature fusion, Lung cancer, PET, CT

Overview

- PET and CT are important differently among cases. For example, PET is sensitive in detecting abnormal regions and localize with CT.
- This paper propose to combine PET / CT feature maps with spatially-varying fusion map (probably an attention / gate map?)
- Validated on lung cancer region detection task, compared with baselines (pre-fused inputs, multi-branch, multi-channel)

Thoughts

- Learnable feature fusion.
- It is an important technique. but not so many tasks have paired inputs.
- Can we use hallucination technique to robustly predict with single modality?
- The baselines seems to be too simple.
