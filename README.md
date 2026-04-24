# Awesome GAN Papers 

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

## Table of Contents

* [Introduction](#introduction)
* [Latest Papers (2023–2025)](#-latest-papers-20232025)
* [Foundations](#-foundations)
* [Core Improvements](#-core-improvements)
* [Image-to-Image Translation](#-image-to-image-translation)
* [High-Quality Image Generation](#-high-quality-image-generation)
* [Text-to-Image Generation](#-text-to-image-generation)
* [Diffusion vs GANs](#-diffusion-vs-gans)
* [Training & Optimization](#-training--optimization)
* [Surveys & Reviews](#-surveys--reviews)
* [Trends](#-trends)
* [Resources](#-resources)
* [Contributing](#-contributing)
* [License](#-license)

## Introduction

Generative Adversarial Networks (GANs), introduced in 2014, are a class of deep learning models capable of generating highly realistic data such as images, audio, and text.

While GANs dominated generative modeling for years, **diffusion models and hybrid approaches** are now reshaping the field.

This repository provides a curated and structured collection of the most important papers to understand both **foundations and modern trends**.

## Latest Papers (2023–2025)

* **[GigaGAN: Scaling up GANs for Text-to-Image Synthesis](https://arxiv.org/abs/2303.05511)** (2023)

  > Large-scale GAN rivaling diffusion models with significantly faster inference.

* **[StyleGAN-T: Unlocking the Power of GANs for Text-to-Image](https://arxiv.org/abs/2301.09515)** (2023)

  > Extends StyleGAN for text-conditioned generation.

* **[Consistency Models](https://arxiv.org/abs/2303.01469)** (2023)

  > Enables fast one-step or few-step generation compared to diffusion.

* **[Diffusion-GAN: Training GANs with Diffusion](https://arxiv.org/abs/2206.02262)** (2022)

  > Combines GAN training with diffusion processes.

* **[MaskGIT](https://arxiv.org/abs/2202.04200)** (2022)

  > Iterative token-based generation as an alternative to GANs.

* **[Elucidating the Design Space of Diffusion Models](https://arxiv.org/abs/2206.00364)** (2022)

  > Explains why diffusion models outperform GANs in many scenarios.

## Foundations

* **[Generative Adversarial Networks](https://arxiv.org/abs/1406.2661)** (2014)

  > Original GAN paper introducing generator vs discriminator.

* **[Conditional GANs](https://arxiv.org/abs/1411.1784)** (2014)

  > Conditioning GANs on labels or input data.

## Core Improvements

* **[DCGAN](https://arxiv.org/abs/1511.06434)** (2015)

  > Stable convolutional GAN architecture.

* **[Improved Techniques for Training GANs](https://arxiv.org/abs/1606.03498)** (2016)

  > Feature matching, minibatch discrimination.

* **[Wasserstein GAN (WGAN)](https://arxiv.org/abs/1701.07875)** (2017)

  > Uses Wasserstein distance for stability.

* **[WGAN-GP](https://arxiv.org/abs/1704.00028)** (2017)

  > Gradient penalty for improved convergence.

## Image-to-Image Translation

* **[Pix2Pix](https://arxiv.org/abs/1611.07004)** (2017)

  > Supervised image-to-image translation.

* **[CycleGAN](https://arxiv.org/abs/1703.10593)** (2017)

  > Unpaired image-to-image translation.

## High-Quality Image Generation

* **[Progressive GAN](https://arxiv.org/abs/1710.10196)** (2018)

  > Progressive resolution training.

* **[BigGAN](https://arxiv.org/abs/1809.11096)** (2019)

  > Large-scale GAN for high fidelity images.

* **[StyleGAN](https://arxiv.org/abs/1812.04948)** (2019)

  > Style-based architecture.

* **[StyleGAN2](https://arxiv.org/abs/1912.04958)** (2020)

  > Improved image quality and artifact reduction.

## Text-to-Image Generation

* **[StackGAN](https://arxiv.org/abs/1612.03242)** (2017)

  > Multi-stage text-to-image generation.

* **[AttnGAN](https://arxiv.org/abs/1711.10485)** (2018)

  > Attention-based text-to-image generation.

## Diffusion vs GANs

* **[Diffusion Models Beat GANs on Image Synthesis](https://arxiv.org/abs/2105.05233)**

  > Landmark result demonstrating diffusion superiority.

* **[On Distillation of Guided Diffusion Models](https://arxiv.org/abs/2210.03142)**

  > Makes diffusion models faster and more practical.

* **[A Survey on Diffusion Models](https://arxiv.org/abs/2209.00796)**

  > Comprehensive overview of diffusion techniques.

* **[Ten Years of GANs: A Survey](https://arxiv.org/abs/2308.16316)**

  > Evolution of GANs and their modern relevance.

## Training & Optimization

* **[Spectral Normalization for GANs](https://arxiv.org/abs/1802.05957)**

  > Stabilizes discriminator training.

* **[Self-Attention GAN (SAGAN)](https://arxiv.org/abs/1805.08318)**

  > Introduces attention mechanisms into GANs.

## Surveys & Reviews

* **[GAN Survey](https://arxiv.org/abs/1710.07035)**
* **[GAN Applications Review](https://arxiv.org/abs/2008.02793)**
* **[Ten Years of GANs](https://arxiv.org/abs/2308.16316)**

## Trends

* Diffusion models are now dominant in image generation
* GANs remain significantly faster at inference
* Hybrid models (GAN + Diffusion) are emerging
* Multimodal generative AI is the next frontier

## Resources

* [Papers with Code – GANs](https://paperswithcode.com/method/gan)
* GAN tutorials, courses, and lectures

## Contributing

Contributions are welcome!

To add a paper:

1. Fork the repository
2. Add your paper in the appropriate section
3. Submit a Pull Request

Guidelines:

* Prefer **arXiv links**
* Add a **short description**
* Keep formatting consistent

## License

This project is licensed under the MIT License.
