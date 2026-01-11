---
layout: page
title: About
permalink: /about/
---

<style>
  /* General Layout */
  .cv-intro {
    font-size: 1.1rem;
    line-height: 1.6;
    color: #333;
    margin-bottom: 3rem;
  }

  /* Section Headers */
  .section-title {
    font-size: 1.5rem;
    font-weight: 700;
    color: #24292e;
    border-bottom: 2px solid #eaecef;
    padding-bottom: 0.5rem;
    margin-top: 3rem;
    margin-bottom: 1.5rem;
  }

  /* Experience & Education Cards - UPDATED TO MATCH PORTFOLIO */
  .cv-item {
    background: #fff;
    border: 1px solid #e1e4e8;
    border-radius: 8px; /* Rounded corners */
    padding: 1.5rem;
    margin-bottom: 1.5rem;
    transition: transform 0.2s ease, box-shadow 0.2s ease, border-color 0.2s ease;
  }
  
  /* Hover effect like Portfolio cards */
  .cv-item:hover {
    transform: translateY(-3px);
    box-shadow: 0 10px 20px rgba(0,0,0,0.1);
    border-color: #0366d6;
  }

  .cv-role {
    font-size: 1.25rem;
    font-weight: 600;
    color: #24292e;
    margin-bottom: 0.5rem;
  }

  .cv-meta {
    font-size: 0.95rem;
    color: #586069;
    margin-bottom: 1rem;
    font-weight: 500;
    border-bottom: 1px solid #eaecef;
    padding-bottom: 0.75rem;
    display: flex;
    justify-content: space-between;
    flex-wrap: wrap;
  }

  .cv-desc {
    font-size: 0.95rem;
    color: #333;
    line-height: 1.6;
  }
  
  .cv-desc ul {
    margin: 0;
    padding-left: 1.2rem;
  }
  
  .cv-desc li {
    margin-bottom: 0.5rem;
  }

  /* Link styling inside description */
  .cv-desc a {
    color: #0366d6;
    text-decoration: none;
  }
  .cv-desc a:hover {
    text-decoration: underline;
  }

  /* Skill Badges */
  .skill-category {
    font-weight: 600;
    margin-bottom: 0.5rem;
    display: block;
    color: #444;
  }
  
  .skill-container {
    margin-bottom: 1.5rem;
  }

  .skill-tag {
    display: inline-block;
    background-color: #f1f8ff;
    color: #0366d6;
    border: 1px solid #c8e1ff;
    padding: 4px 10px;
    border-radius: 20px;
    font-size: 0.85rem;
    font-weight: 500;
    margin-right: 6px;
    margin-bottom: 8px;
  }
</style>

<div class="cv-intro">
  <p>
    Ashutosh is currently pursuing a Master of Science in Quantitative Data Science Methods at the Eberhard Karls University of Tübingen. He is an engineer at heart, now focused on applying statistics and machine learning to econometrics, finance, and social sciences.
  </p>
  <p>
    Previously, Ashutosh spent three years as a Software Engineer at HSBC (Global Cloud Economics), where he focused on data engineering and forecasting models. He has also conducted research at the Max Planck Institute for Intelligent Systems and interned at the financial stability of the Deutsche Bundesbank.
  </p>
</div>

<div class="section-title">Professional Experience</div>

<div class="cv-item">
  <div class="cv-role">Intern Quantitative Analyst (Financial Stability)</div>
  <div class="cv-meta">
    <span>Deutsche Bundesbank, Frankfurt</span>
    <span>July 2025 – Sept 2025</span>
  </div>
  <div class="cv-desc">
    <ul>
      <li>Applied machine learning and time series forecasting to analyze investment fund portfolios within the German financial system.</li>
      <li>Focused on financial stability insights for non-bank financial intermediaries.</li>
    </ul>
  </div>
</div>

<div class="cv-item">
  <div class="cv-role">Student Research Assistant (Optics & Sensing Lab)</div>
  <div class="cv-meta">
    <span>Max Planck Institute for Intelligent Systems, Tübingen</span>
    <span>July 2024 – June 2025</span>
  </div>
  <div class="cv-desc">
    <ul>
      <li>Developed and tested computer vision algorithms (emotion and head orientation detection) for the NICE (Non-verbal Interpersonal Communication Exploration) software: <a href="https://github.com/OSLabTools/nicetoolbox" target="_blank">GitHub-NICE</a>.</li>
    </ul>
  </div>
</div>

<div class="cv-item">
  <div class="cv-role">Software Engineer (Cloud Economics & FinOps)</div>
  <div class="cv-meta">
    <span>HSBC Holdings PLC, Pune</span>
    <span>Sept 2020 – Sept 2023</span>
  </div>
  <div class="cv-desc">
    <ul>
      <li>Built real-time ETL pipelines (improving latency by 4x) and designed FinOps cost-benefit frameworks.</li>
      <li>Developed statistical models driving $500K in cloud cost savings and negotiated vendor discounts for AWS, GCP, and Azure.</li>
    </ul>
  </div>
</div>

<div class="cv-item">
  <div class="cv-role">Software Engineering Intern (Automotive Software)</div>
  <div class="cv-meta">
    <span>Nvidia Corporation, Bengaluru</span>
    <span>Aug 2019 – Dec 2019</span>
  </div>
  <div class="cv-desc">
    <ul>
      <li>Built a customer-facing Python tool with real-time Plotly visualizations to analyze SoC CPU usage, accelerating root-cause analysis.</li>
    </ul>
  </div>
</div>

<div class="section-title">Education</div>

<div class="cv-item">
  <div class="cv-role">M.Sc. Quantitative Data Science Methods (Econometrics)</div>
  <div class="cv-meta">
    <span>Eberhard Karls Universität Tübingen, Germany</span>
    <span>Oct 2023 – Present</span>
  </div>
</div>

<div class="cv-item">
  <div class="cv-role">Erasmus Exchange (Financial Economics & ML)</div>
  <div class="cv-meta">
    <span>Katholieke Universiteit Leuven, Belgium</span>
    <span>Feb 2025 – June 2025</span>
  </div>
</div>

<div class="cv-item">
  <div class="cv-role">B.E. Electrical and Electronics Engineering</div>
  <div class="cv-meta">
    <span>BITS Pilani, Goa Campus, India</span>
    <span>Aug 2016 – May 2020</span>
  </div>
</div>

<div class="section-title">Technical Skills</div>

<div class="skill-container">
  <span class="skill-category">Languages & Tools</span>
  <span class="skill-tag">Python</span>
  <span class="skill-tag">R</span>
  <span class="skill-tag">SQL</span>
  <span class="skill-tag">MATLAB</span>
  <span class="skill-tag">Git</span>
  <span class="skill-tag">Linux</span>
  <span class="skill-tag">Docker</span>
  <span class="skill-tag">LaTeX</span>
</div>

<div class="skill-container">
  <span class="skill-category">Cloud & BI</span>
  <span class="skill-tag">AWS</span>
  <span class="skill-tag">GCP</span>
  <span class="skill-tag">Microsoft Power BI</span>
  <span class="skill-tag">Excel VBA</span>
</div>

<div class="skill-container">
  <span class="skill-category">Core Competencies</span>
  <span class="skill-tag">Probabilistic Machine Learning</span>
  <span class="skill-tag">Causal Machine Learning</span>
  <span class="skill-tag">Deep Learning</span>
  <span class="skill-tag">Financial Economics</span>
  <span class="skill-tag">Time Series Analysis</span>
  <span class="skill-tag">Econometrics</span>
  <span class="skill-tag">Financial Engineering</span>
  <span class="skill-tag">Bayesian Modelling</span>
  <span class="skill-tag">Optimization</span>
</div>