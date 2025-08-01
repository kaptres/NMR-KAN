# Neuromanifold-Regularized KANs for Shape-fair Feature Representations
Official Code Repository for **ICCV2025**

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](#license)
[![Project Status](https://img.shields.io/badge/status-WIP-orange)](#todo--roadmap)

> **⚠️  This is the official repository and is under active development.**  
> We will push code, pretrained weights, and additional documentation **as the project matures.**  
> Stars ⭐ and watches 👀 help us prioritize public releases!

---

## Table of Contents
1. [Overview](#overview)
2. [TODO / Roadmap](#todo--roadmap)
3. [Acknowledgements](#acknowledgements)

---

## Overview
Traditional deep networks often over-fit to fine-scale textures, while unconstrained Kolmogorov-Arnold Networks (KANs) suffer the same issue because their adaptive nonlinearities remain overly expressive. Our work tackles this by constraining KANs to a low-degree neuromanifold and pairing two feature-extractor branches with a novel Style Decorrelation Loss. The resulting model—NeuroManifold-Regularized KAN (NMR-KAN)—learns shape-fair representations that separate local and global cue processing, boosting shape bias by 14.8 pp over baseline convolutional KANs and delivering extra resilience to common corruptions and adversarial attacks.


---

## Citation
If you find our work useful, please cite:

```bibtex
@inproceedings{arslan2025neuromanifold,
  title     = {Neuromanifold-Regularized KANs for Shape-fair Feature Representations},
  author    = {Mazlum Ferhat Arslan and Weihong Guo and Shuo Li},
  booktitle = {Proceedings of the International Conference on Computer Vision},
  year      = {2025},
  url       = {https://arxiv.org/abs/}
}
```

---

## Contact
For questions or collaboration:

* **Ferhat Arslan** – <mxa1328@case.edu> (corresponding)  
* Issues ⇒ use the [GitHub issue tracker](https://github.com/<user>/<repo>/issues)

---

## License
Distributed under the MIT License. See `LICENSE` for more information.

---

## TODO / Roadmap
- [ ] Clean up training scripts 🧹  
- [ ] Release full inference pipeline ⚡  
- [ ] Push pretrained weights 📦  

---

## Acknowledgements
Template inspired by [pytorch-cv](https://github.com/pytorch/vision), [OpenMMLab](https://github.com/open-mmlab), and several ICCV-2023 repos. 
