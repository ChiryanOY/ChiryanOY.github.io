---
permalink: /
title: "Zhiyuan Ouyang"
author_profile: false
landing_page: true
excerpt: "Ph.D. researcher in generative modeling, large-scale AI systems, and on-chain execution infrastructure."
redirect_from: 
  - /about/
  - /about.html
---

<div class="homepage">
  <section class="home-hero">
    <div class="home-hero__grid">
      <div>
        <div class="home-kicker">Generative Models · AI Systems · Web3 Execution</div>
        <h1 class="home-hero__title">Zhiyuan Ouyang</h1>
        <p class="home-hero__subtitle">
          Second-year Ph.D. in Computational Mathematics at
          <a href="https://math.ecnu.edu.cn/">East China Normal University</a> /
          <a href="https://www.sii.edu.cn/">Shanghai Institute of Intelligence</a>.
          I build analytical generative models, optimize large-scale distributed training systems,
          and design resilient on-chain execution infrastructure for real-world trading workflows.
        </p>
        <div class="home-chip-list">
          <span class="home-chip">ICML 2026 First Author</span>
          <span class="home-chip">256 x H200 Distributed Training</span>
          <span class="home-chip">ComfyUI Production Pipelines</span>
          <span class="home-chip">Polymarket Execution Systems</span>
        </div>
        <div class="home-cta">
          <a class="home-btn home-btn--primary" href="{{ '/resume_en.pdf' | relative_url }}" download>Download CV PDF</a>
          <a class="home-btn home-btn--secondary" href="{{ '/publications/' | relative_url }}">View Publications</a>
          <a class="home-btn home-btn--ghost" href="{{ '/cv/' | relative_url }}">Open Web CV</a>
        </div>
      </div>
      <aside class="home-hero__aside">
        <img class="home-portrait" src="{{ '/images/photo.jpg' | relative_url }}" alt="Portrait of Zhiyuan Ouyang">
        <div class="home-portrait__meta">
          <div class="home-portrait__label">Research Focus</div>
          <div class="home-portrait__text">
            Generative modeling theory, topology-aware generalization, efficient controllable generation,
            large-scale AI engineering, and on-chain quantitative execution.
          </div>
        </div>
      </aside>
    </div>

    <div class="home-metrics">
      <div class="home-metric">
        <div class="home-metric__value">ICML 2026</div>
        <div class="home-metric__label">First-authored conference paper on analytical generative modeling.</div>
      </div>
      <div class="home-metric">
        <div class="home-metric__value">256 x H200</div>
        <div class="home-metric__label">Hands-on scheduling, tuning, and concurrent training with Slurm + DDP.</div>
      </div>
      <div class="home-metric">
        <div class="home-metric__value">170x</div>
        <div class="home-metric__label">Computation reduction versus 25-NFE DPM-Solver++ in ImageNet 256 generation.</div>
      </div>
      <div class="home-metric">
        <div class="home-metric__value">352%</div>
        <div class="home-metric__label">Monthly PnL achieved by a live account on the MimicPolymarket routing stack.</div>
      </div>
    </div>
  </section>

  <section class="home-section">
    <div class="home-summary">
      <div>
        <div class="home-section__eyebrow">Overview</div>
        <h2 class="home-section__title">Research depth meets execution-layer engineering.</h2>
        <p class="home-section__lead">
          My work spans from generative model theory to production deployment. On the research side,
          I focus on spectral and topological viewpoints for faster, more controllable generation.
          On the engineering side, I build distributed training systems, customizable visual generation
          pipelines, and low-latency on-chain routers for strategy execution.
        </p>
      </div>
      <div>
        <div class="home-section__eyebrow">Themes</div>
        <div class="home-summary__tags">
          <span class="home-summary__tag">Spectral Generative Modeling</span>
          <span class="home-summary__tag">Stochastic Interpolation</span>
          <span class="home-summary__tag">Distributed Training</span>
          <span class="home-summary__tag">ComfyUI Deployment</span>
          <span class="home-summary__tag">Prediction Markets</span>
          <span class="home-summary__tag">Account Abstraction</span>
        </div>
      </div>
    </div>
  </section>

  <section class="home-section">
    <div class="home-section__header">
      <div class="home-section__eyebrow">Selected Publications</div>
      <h2 class="home-section__title">Three papers that define my recent research arc.</h2>
      <p class="home-section__lead">
        The publication line connects theoretical generative modeling, medical AI, and statistical forecasting.
      </p>
    </div>
    <div class="home-pubs">
      <a class="home-link-card home-pub-card" href="{{ '/publication/2026-05-01-primal-spectral-generative-modeling' | relative_url }}">
        <div class="home-card__meta">ICML 2026 · Conference</div>
        <div class="home-card__title">Primal-Spectral Generative Modeling: Fast Analytical Generation via Pseudoinverse Levy Inversion</div>
        <div class="home-card__copy">
          Introduces PriSpecNet and a 1-NFE PiLI solver that turns sampling into a closed-form analytical problem,
          with strong gains on time-series generation and ImageNet 256.
        </div>
        <div class="home-link-card__arrow">Open publication page →</div>
      </a>
      <a class="home-link-card home-pub-card" href="https://doi.org/10.1016/j.compbiolchem.2025.108572">
        <div class="home-card__meta">Computational Biology and Chemistry · Journal</div>
        <div class="home-card__title">A Novel Network for Resolving Subjective Masking Differences and Accurate Thyroid Nodule Diagnosis</div>
        <div class="home-card__copy">
          Develops a medical AI network that reduces subjective masking differences and improves diagnostic accuracy
          through more robust feature extraction.
        </div>
        <div class="home-link-card__arrow">Read paper →</div>
      </a>
      <a class="home-link-card home-pub-card" href="https://doi.org/10.1080/03610918.2023.2300362">
        <div class="home-card__meta">Communications in Statistics · Journal</div>
        <div class="home-card__title">Model Detection for Grey Forecasting Model with Polynomial Term</div>
        <div class="home-card__copy">
          Studies model detection for grey forecasting with polynomial terms and validates the method across simulation
          and real forecasting cases.
        </div>
        <div class="home-link-card__arrow">Read paper →</div>
      </a>
    </div>
  </section>

  <section class="home-section">
    <div class="home-section__header">
      <div class="home-section__eyebrow">Projects & Experience</div>
      <h2 class="home-section__title">From analytical models to production systems.</h2>
      <p class="home-section__lead">
        I care about shipping research ideas into robust, measurable, and auditable systems.
      </p>
    </div>
    <div class="home-experience">
      <div class="home-exp-card">
        <div class="home-card__meta">Outstanding Ph.D. Project · Nov 2025 - May 2026</div>
        <div class="home-card__title">Generative Modeling</div>
        <ul class="home-card__list">
          <li>Built a spectral route from primal data distributions to characteristic functions with convergence guarantees.</li>
          <li>Designed PriSpecNet and a single-step PiLI solver that preserves compatibility with stochastic interpolation.</li>
          <li>Achieved FID 1.66 on ImageNet 256 with only 26 Gflops and major Context-FID reductions across time-series datasets.</li>
        </ul>
      </div>
      <div class="home-exp-card">
        <div class="home-card__meta">Head of AI Department · Sep 2023 - Sep 2024</div>
        <div class="home-card__title">Baizhi Xunlian Technology Co., Ltd.</div>
        <ul class="home-card__list">
          <li>Led controllable image-generation pipelines based on ComfyUI and Stable Diffusion for enterprise clients.</li>
          <li>Planned and deployed on-premises AI production environments with optimization for heterogeneous inference platforms.</li>
          <li>Established engineering standards, technical training, and agile delivery for cross-functional AI teams.</li>
        </ul>
      </div>
      <div class="home-exp-card">
        <div class="home-card__meta">Independent Open Source · Feb 2026 - Present</div>
        <div class="home-card__title">MimicPolymarket</div>
        <ul class="home-card__list">
          <li>Designed a concurrent multi-wallet execution engine for EOA, Safe, and deposit wallet runtimes.</li>
          <li>Integrated Polymarket relayer routing and POLY_1271 signature flow for account-abstraction execution.</li>
          <li>Built risk controls, order aggregation, MongoDB persistence, retries, and state replay for an auditable trading loop.</li>
        </ul>
      </div>
    </div>
  </section>

  <section class="home-section">
    <div class="home-section__header">
      <div class="home-section__eyebrow">Technical Skills</div>
      <h2 class="home-section__title">A compact map of the stack I work across.</h2>
      <p class="home-section__lead">
        My technical profile combines analytical research, systems engineering, and execution infrastructure.
      </p>
    </div>
    <div class="home-skills">
      <div class="home-skill-card">
        <div class="home-card__meta">Programming & Systems</div>
        <div class="home-card__title">Python, TypeScript, Rust, C++</div>
        <div class="home-card__copy">
          Use Python for modeling and exploration, and TypeScript / Rust / C++ for high-performance execution layers,
          production services, and multi-language architecture design.
        </div>
      </div>
      <div class="home-skill-card">
        <div class="home-card__meta">Deep Learning & Generative Models</div>
        <div class="home-card__title">PyTorch, JAX, Diffusers, TensorBoard</div>
        <div class="home-card__copy">
          Experienced with core algorithm R&amp;D, visual generation systems, experiment tracking,
          and large-scale training orchestration on distributed clusters.
        </div>
      </div>
      <div class="home-skill-card">
        <div class="home-card__meta">Cluster Engineering</div>
        <div class="home-card__title">Slurm, DDP, performance tuning</div>
        <div class="home-card__copy">
          Comfortable with concurrent training, scheduler-level resource control, debugging bottlenecks,
          and keeping large GPU workloads stable and efficient.
        </div>
      </div>
      <div class="home-skill-card">
        <div class="home-card__meta">Web3 & Execution</div>
        <div class="home-card__title">Ethers.js, Viem, Polymarket CLOB SDK, MongoDB, Docker</div>
        <div class="home-card__copy">
          Build on-chain execution systems with account abstraction, relayer integration, slippage protection,
          trade aggregation, containerized deployment, and test-driven delivery.
        </div>
      </div>
    </div>
  </section>

  <section class="home-section">
    <div class="home-section__header">
      <div class="home-section__eyebrow">Contact & CV</div>
      <h2 class="home-section__title">Everything important is one click away.</h2>
      <p class="home-section__lead">
        Reach out for research collaboration, AI systems work, or Web3 execution infrastructure.
      </p>
    </div>
    <div class="home-contact__grid">
      <a class="home-link-card" href="mailto:zhiyuanouyang@sii.edu.cn">
        <div class="home-card__meta">Email</div>
        <div class="home-card__title">zhiyuanouyang@sii.edu.cn</div>
        <div class="home-card__copy">Preferred channel for academic communication, collaborations, and speaking invitations.</div>
        <div class="home-link-card__arrow">Send email →</div>
      </a>
      <a class="home-link-card" href="https://github.com/ChiryanOY">
        <div class="home-card__meta">GitHub</div>
        <div class="home-card__title">ChiryanOY</div>
        <div class="home-card__copy">Source code, experiments, and open-source projects including MimicPolymarket.</div>
        <div class="home-link-card__arrow">Open GitHub →</div>
      </a>
      <a class="home-link-card" href="https://x.com/Chiryan_OY">
        <div class="home-card__meta">X / Twitter</div>
        <div class="home-card__title">@Chiryan_OY</div>
        <div class="home-card__copy">Follow updates on research milestones, systems work, and open-source releases.</div>
        <div class="home-link-card__arrow">Open profile →</div>
      </a>
      <a class="home-link-card" href="{{ '/resume_en.pdf' | relative_url }}" download>
        <div class="home-card__meta">Formal CV</div>
        <div class="home-card__title">Download resume_en.pdf</div>
        <div class="home-card__copy">A printable PDF resume aligned with the latest publications, projects, and technical skills.</div>
        <div class="home-link-card__arrow">Download PDF →</div>
      </a>
    </div>
    <div class="home-contact">
      <div class="home-contact__note">
        Advisors:
        <a href="https://math.ecnu.edu.cn/~xyzhang/">Assoc. Prof. Xiangyun Zhang</a>
        and
        <a href="https://thinklab.sjtu.edu.cn/">Prof. Junchi Yan</a>.
        Honors include the National Scholarship for PhD Students in China and a provincial first prize in a collegiate C/C++ programming contest.
      </div>
      <div class="home-contact__links">
        <a class="home-btn home-btn--primary" href="{{ '/resume_en.pdf' | relative_url }}" download>Download CV PDF</a>
        <a class="home-btn home-btn--secondary" href="https://github.com/ChiryanOY/MimicPolymarket">See Open Source Project</a>
      </div>
    </div>
  </section>
</div>
