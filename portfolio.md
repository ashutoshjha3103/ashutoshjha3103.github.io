---
layout: page
title: Portfolio
permalink: /portfolio/
---

<style>
/* CSS for the Portfolio Grid */
.project-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
  gap: 2rem;
  margin-top: 2rem;
}

.project-card {
  background: #fff;
  border: 1px solid #e1e4e8;
  border-radius: 8px;
  padding: 1.5rem;
  transition: transform 0.2s ease, box-shadow 0.2s ease;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
}

.project-card:hover {
  transform: translateY(-3px);
  box-shadow: 0 10px 20px rgba(0,0,0,0.1);
  border-color: #0366d6;
}

.project-title {
  font-size: 1.35rem;
  font-weight: 700;
  margin-bottom: 0.25rem;
  color: #24292e;
  line-height: 1.2;
}

.project-meta {
  font-size: 0.9rem;
  color: #586069;
  margin-bottom: 0.5rem;
  font-weight: 500;
}

.project-desc {
  font-size: 0.95rem;
  color: #333;
  line-height: 1.6;
  margin-top: 1rem;
  padding-top: 1rem;
  border-top: 1px solid #eaecef;
  flex-grow: 1;
}

.project-links {
  margin-top: 1.5rem;
}

a.card-link { text-decoration: none; color: inherit; }
</style>

<p>Here is a selection of my academic and technical projects in Financial Engineering, Econometrics, and Machine Learning.</p>

<div class="project-grid">

<div class="project-card">
  <div>
    <div class="project-title">Optimal Transport in Linear ICA</div>
    <div class="project-meta">Master Thesis @ MPI for Intelligent Systems</div>
    <div class="project-desc">
      Research applying optimal transport theory to solve problems in linear Independent Component Analysis (ICA).
      <br><br>
      <em>Supervisors: Dr. Simon Buchholz, Prof. Dr. Michel Besserve, Prof. Dr. Joachim Grammig</em>
    </div>
  </div>
  <div class="project-links">
    <a href="https://github.com/ashutoshjha3103/ot_in_linear_ica">
      <img src="https://img.shields.io/badge/GitHub-Private_Repo-lightgrey?logo=github" alt="View on GitHub">
    </a>
  </div>
</div>

<div class="project-card">
  <div>
    <div class="project-title">Structured Product Design (Bonus Certificate)</div>
    <div class="project-meta">KU Leuven (Financial Engineering)</div>
    <div class="project-desc">
      Designed, priced, and hedged a Bonus Certificate linked to Costco (COST). Used the <strong>Bates Model</strong> (stochastic volatility + jumps) with a two-stage calibration and Monte Carlo simulation for path-dependent payoff pricing.
    </div>
  </div>
  <div class="project-links">
    <a href="https://github.com/ashutoshjha3103/exotic_option_pricing-fe2025">
      <img src="https://img.shields.io/badge/GitHub-View_Project-blue?logo=github" alt="View on GitHub">
    </a>
  </div>
</div>

<div class="project-card">
  <div>
    <div class="project-title">Probabilistic Asset Pricing</div>
    <div class="project-meta">University of Tübingen</div>
    <div class="project-desc">
      Developed a Bayesian framework for estimating stock risk premia. Integrated the hybrid model of Grammig et al. (2024) with forward-looking measures from Martin & Wagner (2019) using <strong>Kalman Filtering</strong> and the EM algorithm.
      <br><br>
      <em>Supervisor: Prof. Dr. Joachim Grammig</em>
    </div>
  </div>
  <div class="project-links">
    <a href="https://github.com/ashutoshjha3103/probabilistic_asset_pricing">
      <img src="https://img.shields.io/badge/GitHub-View_Project-blue?logo=github" alt="View on GitHub">
    </a>
  </div>
</div>

<div class="project-card">
  <div>
    <div class="project-title">Empirical Asset Pricing: CBM vs UCCAPM</div>
    <div class="project-meta">University of Tübingen</div>
    <div class="project-desc">
      Comparative analysis of Consumption-Based (CBM) and Ultimate Consumption (UCCAPM) models on 25 Fama-French portfolios. Investigated model performance during COVID-19 and the impact of lagged consumption adjustment.
    </div>
  </div>
  <div class="project-links">
    <a href="https://github.com/ashutoshjha3103/cbm_asset_pricing">
      <img src="https://img.shields.io/badge/GitHub-View_Project-blue?logo=github" alt="View on GitHub">
    </a>
  </div>
</div>

<div class="project-card">
  <div>
    <div class="project-title">ARMA Process Analysis & Estimation</div>
    <div class="project-meta">University of Tübingen (Time Series)</div>
    <div class="project-desc">
      Detailed analysis of Conditional Maximum Likelihood (CML) vs Quasi-Maximum Likelihood (QML). Performed simulation studies to test stationarity, efficiency, and robustness of confidence intervals.
    </div>
  </div>
  <div class="project-links">
    <a href="https://github.com/ashutoshjha3103/time_series_analysis_arma">
      <img src="https://img.shields.io/badge/GitHub-View_Project-blue?logo=github" alt="View on GitHub">
    </a>
  </div>
</div>

<div class="project-card">
  <div>
    <div class="project-title">Ripple Down Rules Simulation</div>
    <div class="project-meta">BITS Pilani (APPCAIR Lab)</div>
    <div class="project-desc">
      Implemented a Python simulation for Ripple Down Rules (RDR), a tree-based incremental learning approach.
      <br><br>
      <em>Supervisor: Prof. Ashwin Srinivasan</em>
    </div>
  </div>
  <div class="project-links">
    <a href="https://github.com/ashutoshjha3103/rdr_py">
      <img src="https://img.shields.io/badge/GitHub-View_Project-blue?logo=github" alt="View on GitHub">
    </a>
  </div>
</div>

</div>