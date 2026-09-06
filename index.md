---
layout: page-plain
title: Home
permalink: /
---

<div class="hero-home">
  <div class="hero-copy">
    <span class="hero-eyebrow">PhD Student &middot; Machine Learning</span>
    <h1 class="hero-title">Hi, I'm Ashutosh Jha</h1>
    <p class="hero-tagline">Institute of AI, TU Braunschweig. Advised by Prof. Dr. Michel Besserve.</p>
    <div class="hero-lead">
      <p>I develop machine learning methods for understanding complex systems, with a focus on causality, in particular causal and probabilistic representation learning.</p>
    </div>
    <ul class="hero-actions">
      <li><a href="{{ '/publications/' | relative_url }}">Publications</a></li>
      <li><a href="{{ '/about/' | relative_url }}">CV &amp; background</a></li>
      <li><a href="https://scholar.google.com/citations?user=eF92eEgAAAAJ" target="_blank" rel="noopener noreferrer">Google Scholar</a></li>
    </ul>
  </div>
  <div class="hero-photo-wrap">
    <img class="hero-photo" src="{{ '/assets/profile.jpg' | relative_url }}" width="220" height="220" alt="Portrait of Ashutosh Jha">
  </div>
</div>

<div class="section-title">Research Interests</div>

<div class="interest-grid">
  <div class="interest-item">
    <h3 class="interest-title">Machine Learning for Complex Systems</h3>
    <p>Probabilistic representation learning: models that capture the structure behind high-dimensional data instead of only predicting it.</p>
  </div>
  <div class="interest-item">
    <h3 class="interest-title">Causality</h3>
    <p>Causal representation learning: recovering the latent variables and mechanisms that generated the observations.</p>
  </div>
  <div class="interest-item">
    <h3 class="interest-title">Applications</h3>
    <p>Sustainable energy systems, decision sciences, econometrics, and generative AI.</p>
  </div>
</div>

<div class="section-title">News</div>

{% include news-list.html limit=4 %}

<div class="section-title">Selected Publication</div>

{% include publication-list.html featured_only=true compact=true %}

<p class="section-more"><a href="{{ '/publications/' | relative_url }}">All publications &rarr;</a></p>
