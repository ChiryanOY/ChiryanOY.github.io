---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Summary
======
My research centers on **generative models**, bridging rigorous theoretical foundations with practical AI systems. I study generalization, interpretability, and low-dimensional structure in generative modeling to improve generation efficiency, controllability, and safety. I also work on large-scale AI engineering, including Slurm scheduling and DDP distributed training, and maintain strong interests in **Web3**, **prediction markets**, and **on-chain quantitative trading**.

Education
======
* **East China Normal University / Shanghai Institute of Intelligence**, Ph.D. student in Computational Mathematics, 2024-present
* **Advisors:** [Assoc. Prof. Xiangyun Zhang](https://math.ecnu.edu.cn/~xyzhang/) and [Prof. Junchi Yan](https://soai.sjtu.edu.cn/cn/facultydetails/zzjs/yanjunchi)
* **Honors:** National Scholarship for PhD Students (Top 1.5%)
* **Research Interests:** Generative Models, Prediction Markets, Web3 Quant Trading, Time Series Analysis

Selected Publications
======
* **Zhiyuan Ouyang** (First Author). [Primal-Spectral Generative Modeling: Fast Analytical Generation via Pseudoinverse Levy Inversion](https://icml.cc/virtual/2026/poster/66180). *ICML 2026 (CCF-A)*.
* **Zhiyuan Ouyang** (First Author). [A novel network for resolving subjective masking differences and accurate thyroid nodule diagnosis](https://doi.org/10.1016/j.compbiolchem.2025.108572). *Computational Biology and Chemistry*.
* **Zhiyuan Ouyang** (First Author). [Model detection for grey forecasting model with polynomial term](https://doi.org/10.1080/03610918.2023.2300362). *Communications in Statistics - Simulation and Computation*.

Projects and Experience
======
* **MimicPolymarket: On-chain Quant Router** (Independent Open Source), Feb 2026-present
  * Built a production-oriented quantitative execution engine with concurrent multi-wallet routing for Polymarket.
  * Integrated Relayer routing, POLY_1271 signatures, and Account Abstraction based deposit-wallet order flow.
  * Designed position sizing, exposure control, scaling-out, and MongoDB-backed state persistence for low-latency trading.

* **Generative Modeling** (Outstanding Ph.D. Project), Nov 2025-May 2026
  * Proposed the **PriSpecNet** architecture and a single-step Pseudoinverse Levy Inversion solver.
  * Unified generation and forecasting in time series and demonstrated strong gains on Sines, Solar, ETTh, and Stock datasets.
  * Achieved FID 1.66 on ImageNet 256x256 with only 26 Gflops and around 170x lower computation than 25-NFE DPM-Solver++.

* **Baizhi Xunlian Technology Co., Ltd.**, Head of AI Department, Sep 2023-Sep 2024
  * Led visual generation pipeline development with ComfyUI and Stable Diffusion.
  * Built on-premises enterprise AI deployment solutions and optimized inference for heterogeneous platforms.
  * Established engineering standards, technical training processes, and delivery workflows for cross-functional teams.

Technical Skills
======
* **Programming:** Python, TypeScript, Rust, C++
* **Generative AI:** PyTorch, JAX, Diffusers, Stable Diffusion, ComfyUI
* **Systems:** Slurm, DDP distributed training, TensorBoard, Docker
* **Web3 / Quant:** Ethers.js, Viem, Polymarket CLOB SDK, MongoDB
* **Engineering:** Risk-control state machines, test-driven development with Jest

Academic Services
======
* Reviewer: BSPC, JIFS
