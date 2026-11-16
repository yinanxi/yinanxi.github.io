---
layout: page
title: "TMPO: Diffusion Alignment"
permalink: /projects/tmpo/
importance: 1
period: "Spring 2026"
role: "MAIR Lab, HUST"
description: "Trajectory-level reward-distribution matching for diverse and efficient diffusion alignment."
---

Advisors: **Zhiyuan Ma** and **Bowen Zhou**.

TMPO addresses reward hacking and mode collapse by matching reward distributions across denoising trajectories. The framework combines a **Softmax Trajectory Balance** objective with **Dynamic Stochastic Tree Sampling**, sharing denoising prefixes and branching at dynamically scheduled steps.

We evaluated TMPO on human preference, compositional generation, and text rendering, achieving a **9.1% diversity improvement** over prior state-of-the-art methods while retaining competitive reward and efficiency.

**NeurIPS 2026 · Poster.**

[Paper](https://arxiv.org/abs/2605.10983) · [Code](https://github.com/MAIR-Lab-HUST/TMPO) · [Project website](https://mair-lab-hust.github.io/TMPO/)
