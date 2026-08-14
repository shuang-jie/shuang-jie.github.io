---
layout: homepage
---

## Research

<p class="lede">I build Bayesian models for high-dimensional, dependent, and non-Gaussian data — with a focus on recovering interpretable structure (interactions, dependence, causal direction) from messy biomedical measurements.</p>

<div class="topic-grid">
  <div class="topic-card">
    <i class="fas fa-project-diagram"></i>
    <h3>Structure &amp; Causal Discovery</h3>
    <p>Directed acyclic graphs, directed trees, and generalized Bayesian inference for learning how variables drive one another.</p>
  </div>
  <div class="topic-card">
    <i class="fas fa-layer-group"></i>
    <h3>Factor Models &amp; Interactions</h3>
    <p>Latent factor and graphical models that make feature interactions estimable — and let them vary with covariates.</p>
  </div>
  <div class="topic-card">
    <i class="fas fa-chart-area"></i>
    <h3>Density Regression</h3>
    <p>Semiparametric models for how a whole outcome distribution shifts with covariates, including discontinuities at thresholds.</p>
  </div>
  <div class="topic-card">
    <i class="fas fa-dna"></i>
    <h3>Microbiome &amp; Multi-omics</h3>
    <p>Methods built for sparse, zero-inflated, compositional count data, and for integrating several omics tables at once.</p>
  </div>
</div>

## Publications and Preprints

<!-- To use a real teaser figure, drop an image into assets/img/papers/ and replace
     the <i> tag inside .pub-thumb with:  <img src="./assets/img/papers/NAME.jpg" alt=""> -->

<div class="pub-list">

  <div class="pub">
    <div class="pub-thumb" style="--t1:#7aa8d4; --t2:#2c5f92;"><i class="fas fa-sitemap"></i></div>
    <div class="pub-body">
      <h3><a href="https://arxiv.org/abs/2605.03178">Structure Learning for Directed Trees with Zero-Inflated Compositional Nodes</a></h3>
      <p class="pub-authors">Zhang, S., Mallick, B., &amp; Ni, Y. (2026+)</p>
      <p class="pub-summary">Recovers directed tree structure among taxa while respecting two features that break standard methods: excess zeros and the compositional constraint of sequencing counts.</p>
      <div class="chip-row">
        <span class="chip chip--status">Submitted</span>
        <a class="chip" href="https://arxiv.org/abs/2605.03178"><i class="ai ai-arxiv"></i> arXiv:2605.03178</a>
      </div>
    </div>
  </div>

  <div class="pub">
    <div class="pub-thumb" style="--t1:#86c1b4; --t2:#2f7d6c;"><i class="fas fa-chart-area"></i></div>
    <div class="pub-body">
      <h3><a href="https://shuang-jie.github.io/files/SJ-P4.pdf">Bayesian Semiparametric Density Regression with Discontinuity</a></h3>
      <p class="pub-authors">Zheng, H.#, Zhang, S.#, Sen, R., &amp; Tokdar, S. T. (2026+)</p>
      <p class="pub-summary">Models how an entire outcome density changes with covariates while allowing the density to jump at a threshold.</p>
      <div class="chip-row">
        <a class="chip" href="https://shuang-jie.github.io/files/SJ-P4.pdf"><i class="fas fa-file-pdf"></i> PDF</a>
      </div>
    </div>
  </div>

  <div class="pub">
    <div class="pub-thumb" style="--t1:#c9a3d4; --t2:#7a4b96;"><i class="fas fa-layer-group"></i></div>
    <div class="pub-body">
      <h3><a href="https://arxiv.org/abs/2603.12352">Covariate Dependent Factor Model for Feature Interactions in Microbiome Study</a></h3>
      <p class="pub-authors">Zhang, S., Patnode, M., &amp; Lee, J. (2026+)</p>
      <p class="pub-summary">Lets factor loadings depend on covariates, so estimated interactions between microbial features can shift across host characteristics rather than being held fixed.</p>
      <div class="chip-row">
        <span class="chip chip--status">Submitted</span>
        <a class="chip" href="https://arxiv.org/abs/2603.12352"><i class="ai ai-arxiv"></i> arXiv:2603.12352</a>
      </div>
    </div>
  </div>

  <div class="pub">
    <div class="pub-thumb" style="--t1:#e0ae82; --t2:#a8622c;"><i class="fas fa-cut"></i></div>
    <div class="pub-body">
      <h3><a href="https://arxiv.org/abs/2507.05581">Density discontinuity regression</a></h3>
      <p class="pub-authors">Tokdar, S. T., Sen, R., Zheng, H., &amp; Zhang, S. (2026+)</p>
      <p class="pub-summary">Estimates and tests for a jump in a density at a cutoff — the object of interest in regression-discontinuity style designs.</p>
      <div class="chip-row">
        <span class="chip chip--status">Submitted</span>
        <a class="chip" href="https://arxiv.org/abs/2507.05581"><i class="ai ai-arxiv"></i> arXiv:2507.05581</a>
      </div>
    </div>
  </div>

  <div class="pub">
    <div class="pub-thumb" style="--t1:#8fb8e0; --t2:#2f5f9c;"><i class="fas fa-th"></i></div>
    <div class="pub-body">
      <h3><a href="https://doi.org/10.1080/01621459.2025.2449721">Sparse Bayesian Group Factor model for feature interactions in multiple count tables data</a></h3>
      <p class="pub-authors">Zhang, S., Shen, Y., Chen, I. A., &amp; Lee, J. (2025)</p>
      <p class="pub-summary">A sparse group factor model that estimates interactions within and across several count tables at once, such as paired microbiome and metabolite measurements.</p>
      <div class="chip-row">
        <span class="chip pub-venue">Journal of the American Statistical Association, 120(550), 723-736</span>
        <a class="chip" href="https://doi.org/10.1080/01621459.2025.2449721"><i class="fas fa-link"></i> DOI</a>
        <a class="chip" href="https://shuang-jie.github.io/SP-BGFM/"><i class="fas fa-cube"></i> Sp-BGFM</a>
      </div>
    </div>
  </div>

  <div class="pub">
    <div class="pub-thumb" style="--t1:#9fc9a8; --t2:#3d7a55;"><i class="fas fa-vials"></i></div>
    <div class="pub-body">
      <h3><a href="https://doi.org/10.1214/22-aoas1690">Bayesian modeling of interaction between features in sparse multivariate count data with application to microbiome study</a></h3>
      <p class="pub-authors">Zhang, S., Shen, Y., Chen, I. A., &amp; Lee, J. (2023)</p>
      <p class="pub-summary">A zero-inflated multivariate rounded log-normal model that separates true absence from undersampling when estimating feature interactions.</p>
      <div class="chip-row">
        <span class="chip pub-venue">The Annals of Applied Statistics, 17(3)</span>
        <a class="chip" href="https://doi.org/10.1214/22-aoas1690"><i class="fas fa-link"></i> DOI</a>
        <a class="chip" href="https://shuang-jie.github.io/ZI-MLN/"><i class="fas fa-cube"></i> Zi-MLN</a>
      </div>
    </div>
  </div>

</div>

<p class="footnote"><em># denotes equal contribution.</em></p>

## In Progress

* Zhang, S., Ok, S., & Ni, Y. Bayesian Longitudinal Modeling of Microbiome Interaction.
* Zhang, S., Luo, H., Mallick, B., & Ni, Y. Generalized Bayesian Compositional Directed Acyclic Graph.
* Li, X.#, Zhang, S.#, Zhang, Q., & Ma, S. Measurement Error Analysis in Multi-omic Data.
* Zhu, Z., Zhang, S., Tang, X., & Zhang, L. Phylogeny-Guided Selection of Microbiome Features using Bayesian Prevalence-Aware Multinomial Logit Normal Regression.

## Software

<div class="soft-grid">
  <div class="soft-card">
    <h3><i class="fas fa-cube"></i>Sp-BGFM</h3>
    <p>Sparse Bayesian Group Factor Model for Multiple Count Tables.</p>
    <div class="chip-row">
      <a class="chip" href="https://shuang-jie.github.io/SP-BGFM/"><i class="fas fa-globe"></i> Website</a>
      <a class="chip" href="https://github.com/shuang-jie/SP-BGFM"><i class="fab fa-github"></i> GitHub</a>
    </div>
  </div>
  <div class="soft-card">
    <h3><i class="fas fa-cube"></i>BCAIA</h3>
    <p>Bayesian Covariate-Varying Interaction Analysis for Multivariate Count Data.</p>
    <div class="chip-row">
      <a class="chip" href="https://shuang-jie.github.io/BCAIA/"><i class="fas fa-globe"></i> Website</a>
      <a class="chip" href="https://github.com/shuang-jie/BCAIA"><i class="fab fa-github"></i> GitHub</a>
    </div>
  </div>
  <div class="soft-card">
    <h3><i class="fas fa-cube"></i>Zi-MLN</h3>
    <p>Zero-Inflated Multivariate Rounded Log-Normal Model.</p>
    <div class="chip-row">
      <a class="chip" href="https://shuang-jie.github.io/ZI-MLN/"><i class="fas fa-globe"></i> Website</a>
      <a class="chip" href="https://github.com/shuang-jie/ZI-MLN"><i class="fab fa-github"></i> GitHub</a>
    </div>
  </div>
</div>
