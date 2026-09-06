---
layout: page
title: Projects
permalink: /portfolio/
---

<p>Research code, coursework and engineering projects. Peer-reviewed work lives on the <a href="{{ '/publications/' | relative_url }}">publications page</a>.</p>

<div class="project-grid">

<div class="project-card">
  <div>
    <div class="project-title">Optimal Transport in Linear ICA</div>
    <div class="project-meta">Master Thesis @ MPI for Intelligent Systems and University of Tübingen</div>
    <div class="project-tags">
      <span class="project-tag">Research</span>
      <span class="project-tag">Optimal transport</span>
      <span class="project-tag">ICA</span>
    </div>
    <div class="project-desc">
      Implementation of <strong>OT-ICA</strong>, which measures non-Gaussianity by the squared Wasserstein distance to a standard Gaussian rather than by proxy contrast functions. Published at the TPM workshop at UAI 2026; evaluated on simulated data, EEG artifact removal, and econometric price discovery.
      <br><br>
      <em>Supervisors: Dr. Simon Buchholz, Prof. Dr. Michel Besserve, Prof. Dr. Joachim Grammig</em>
    </div>
  </div>
  <div class="project-links">
    <a class="link-chip" href="{{ '/publications/' | relative_url }}">Paper</a>
    <a class="link-chip" href="https://gitfront.io/r/ashutosh-jha/4gwwN1sPeeAD/ot-in-linear-ica/" target="_blank" rel="noopener noreferrer">GitFront</a>
  </div>
</div>

<div class="project-card">
  <div>
    <div class="project-title">NICE Toolbox (Computer Vision &amp; DL)</div>
    <div class="project-meta">Graduate Research Assistant @ MPI for Intelligent Systems</div>
    <div class="project-tags">
      <span class="project-tag">Deep learning</span>
      <span class="project-tag">Computer vision</span>
      <span class="project-tag">Python</span>
    </div>
    <div class="project-desc">
      Core contributor to the Nonverbal Interpersonal Communication Exploration (NICE) Toolbox. Implemented <strong>Deep Learning</strong> models for Pose Estimation, Emotion Detection, and Head Orientation. Designed the asset manager for all algorithms network weights and structured the testing and Docker containerization pipelines.
    </div>
  </div>
  <div class="project-links">
    <a class="link-chip" href="https://github.com/OSLabTools/nicetoolbox" target="_blank" rel="noopener noreferrer">GitHub</a>
  </div>
</div>

<div class="project-card">
  <div>
    <div class="project-title">Structured Product Design, Pricing &amp; Hedging (Financial Engineering)</div>
    <div class="project-meta">KU Leuven (Course: Financial Engineering)</div>
    <div class="project-tags">
      <span class="project-tag">Finance</span>
      <span class="project-tag">Monte Carlo</span>
      <span class="project-tag">Bates model</span>
    </div>
    <div class="project-desc">
      Designed, priced, and hedged a Bonus Certificate linked to Costco (COST). Used the <strong>Bates Model</strong> (stochastic volatility + jumps) with a two-stage calibration and Monte Carlo simulation for path-dependent payoff pricing.
    </div>
  </div>
  <div class="project-links">
    <a class="link-chip" href="https://github.com/ashutoshjha3103/exotic_option_pricing_fe2025" target="_blank" rel="noopener noreferrer">GitHub</a>
  </div>
</div>

<div class="project-card">
  <div>
    <div class="project-title">Probabilistic Asset Pricing</div>
    <div class="project-meta">Master Seminar @ University of Tübingen</div>
    <div class="project-tags">
      <span class="project-tag">Bayesian</span>
      <span class="project-tag">Kalman filter</span>
      <span class="project-tag">Asset pricing</span>
    </div>
    <div class="project-desc">
      Developed a Bayesian framework for estimating stock risk premia. Integrated the hybrid model of Grammig et al. (2024) with forward-looking measures from Martin &amp; Wagner (2019) using <strong>Kalman Filtering</strong> and the EM algorithm.
      <br><br>
      <em>Supervisor: Prof. Dr. Joachim Grammig</em>
    </div>
  </div>
  <div class="project-links">
    <a class="link-chip" href="https://github.com/ashutoshjha3103/probabilistic_asset_pricing" target="_blank" rel="noopener noreferrer">GitHub</a>
  </div>
</div>

<div class="project-card">
  <div>
    <div class="project-title">A Comparative Study of CBM and UCCAPM</div>
    <div class="project-meta">University of Tübingen (Empirical Asset Pricing)</div>
    <div class="project-tags">
      <span class="project-tag">Econometrics</span>
      <span class="project-tag">Fama-French</span>
      <span class="project-tag">Consumption CAPM</span>
    </div>
    <div class="project-desc">
      Comparative analysis of Consumption-Based (CBM) and Ultimate Consumption (UCCAPM) models on 25 Fama-French portfolios. Investigated model performance during COVID-19 and the impact of lagged consumption adjustment.
    </div>
  </div>
  <div class="project-links">
    <a class="link-chip" href="https://github.com/ashutoshjha3103/cbm_asset_pricing" target="_blank" rel="noopener noreferrer">GitHub</a>
  </div>
</div>

<div class="project-card">
  <div>
    <div class="project-title">ARMA Process Analysis &amp; Estimation (Time Series Analysis)</div>
    <div class="project-meta">University of Tübingen (Advanced Time Series Analysis)</div>
    <div class="project-tags">
      <span class="project-tag">Time series</span>
      <span class="project-tag">ARMA</span>
      <span class="project-tag">Simulation</span>
    </div>
    <div class="project-desc">
      Detailed analysis of Conditional Maximum Likelihood (CML) vs Quasi-Maximum Likelihood (QML). Performed simulation studies to test stationarity, efficiency, and robustness of confidence intervals.
    </div>
  </div>
  <div class="project-links">
    <a class="link-chip" href="https://github.com/ashutoshjha3103/time_series_analysis_arma" target="_blank" rel="noopener noreferrer">GitHub</a>
  </div>
</div>

<div class="project-card">
  <div>
    <div class="project-title">TuebiFit</div>
    <div class="project-meta">Cursor Hackathon 2026 · Heilbronn</div>
    <div class="project-tags">
      <span class="project-tag">Hackathon</span>
      <span class="project-tag">LLM &amp; MCP</span>
      <span class="project-tag">React</span>
      <span class="project-tag">MediaPipe</span>
      <span class="project-tag">Cloud Run</span>
    </div>
    <div class="project-desc">
      Co-developed VisionLLM based Mobile fitness companion: <strong>MediaPipe</strong> rep counting and form cues (CLI/video pipeline and in-app RepCount), an <strong>LLM agent</strong> (Featherless API) with <strong>LangChain / LangGraph</strong> calling Exercise DB and OpenNutrition <strong>MCP</strong> servers for workout and meal plans, and a <strong>React + Vite</strong> SPA. Full stack containerized and deployable to <strong>Google Cloud Run</strong>.
      <br><br>
    </div>
  </div>
  <div class="project-links">
    <a class="link-chip" href="https://github.com/ashutoshjha3103/tuebifit" target="_blank" rel="noopener noreferrer">GitHub</a>
  </div>
</div>

<div class="project-card">
  <div>
    <div class="project-title">Ripple Down Rules Simulation (Tree-based Algorithm)</div>
    <div class="project-meta">BITS Pilani (APPCAIR Lab)</div>
    <div class="project-tags">
      <span class="project-tag">Python</span>
      <span class="project-tag">RDR</span>
      <span class="project-tag">Incremental learning</span>
    </div>
    <div class="project-desc">
      Implemented a Python simulation for Ripple Down Rules (RDR), a tree-based incremental learning approach.
      <br><br>
      <em>Supervisor: Prof. Ashwin Srinivasan</em>
    </div>
  </div>
  <div class="project-links">
    <a class="link-chip" href="https://github.com/ashutoshjha3103/rdr_py" target="_blank" rel="noopener noreferrer">GitHub</a>
  </div>
</div>

</div>
