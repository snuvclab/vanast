<div align="center">

# Vanast: Virtual Try-On with Human Image Animation via Synthetic Triplet Supervision

<a href="https://arxiv.org/abs/2604.04934"><img src='https://img.shields.io/badge/arXiv-2604.04934-b31b1b.svg?style=for-the-badge' alt='arXiv'></a>
<a href="https://arxiv.org/pdf/2604.04934.pdf"><img src='https://img.shields.io/badge/Paper-PDF-green?style=for-the-badge' alt='Paper PDF'></a>
<a href="https://hyunsoocha.github.io/vanast/"><img src='https://img.shields.io/badge/Project-Page-blue?style=for-the-badge' alt='Project Page'></a>

### CVPR 2026 Highlight

[Hyunsoo Cha](https://hyunsoocha.github.io/) &nbsp;&nbsp; [Wonjung Woo](https://wonjungwoo.github.io/) &nbsp;&nbsp; [Byungjun Kim](https://bjkim95.github.io/) &nbsp;&nbsp; [Hanbyul Joo](https://jhugestar.github.io/)

Seoul National University

<br>

[https://hyunsoocha.github.io/vanast/static/images/teaser/teaser.m4v](https://github.com/user-attachments/assets/7a8954cf-dc4d-45f4-afdc-3bdf2e1996de)

</div>

---

## News

- **[2026.04]** Paper accepted to **CVPR 2026** as a **Highlight**!
- **[2026.04]** [arXiv preprint](https://arxiv.org/abs/2604.04934) and [project page](https://hyunsoocha.github.io/vanast/) are released.

## TODO

- [x] Release project page
- [x] Release arXiv paper
- [ ] Release inference code & pretrained weights (May 2026)
- [ ] Release training code
- [ ] Release Gradio demo

## Abstract

We present **Vanast**, a unified framework that generates garment-transferred human animation videos directly from a single human image, garment images, and a pose guidance video. Conventional two-stage pipelines treat image-based virtual try-on and pose-driven animation as separate processes, which often results in identity drift, garment distortion, and front-back inconsistency. Our model addresses these issues by performing the entire process in a single unified step to achieve coherent synthesis. To enable this setting, we construct large-scale triplet supervision. Our data generation pipeline includes generating identity-preserving human images in alternative outfits that differ from garment catalog images, capturing full upper and lower garment triplets to overcome the single-garment-posed video pair limitation, and assembling diverse in-the-wild triplets without requiring garment catalog images. We further introduce a **Dual Module** architecture for video diffusion transformers to stabilize training, preserve pretrained generative quality, and improve garment accuracy, pose adherence, and identity preservation while supporting zero-shot garment interpolation. Together, these contributions allow Vanast to produce high-fidelity, identity-consistent animation across a wide range of garment types.

## Citation

If you find our work useful, please consider citing:

```bibtex
@inproceedings{cha2026vanast,
  title     = {Vanast: Virtual Try-On with Human Image Animation via Synthetic Triplet Supervision},
  author    = {Cha, Hyunsoo and Woo, Wonjung and Kim, Byungjun and Joo, Hanbyul},
  booktitle = {Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)},
  year      = {2026}
}
```

## Acknowledgements

This work was conducted at [SNU VCLab](https://jhugestar.github.io/).

## License

This project is licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
