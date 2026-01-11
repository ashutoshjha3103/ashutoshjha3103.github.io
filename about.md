---
layout: page
title: About
permalink: /about/
---

<style>
/* --- STYLES --- */

/* Intro Text - Plain Style (No Box) */
.cv-intro {
  font-size: 1.1rem;
  line-height: 1.6;
  color: #333;
  margin-bottom: 2.5rem;
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

/* Skills Section */
.skill-category {
  font-size: 1rem;
  font-weight: 700;
  color: #24292e;
  margin-top: 1rem;
  margin-bottom: 0.5rem;
  display: block;
}

.skill-tag {
  display: inline-block;
  background-color: #f1f8ff;
  color: #0366d6;
  border: 1px solid #c8e1ff;
  padding: 4px 10px;
  border-radius: 12px;
  font-size: 0.9rem;
  margin-right: 6px;
  margin-bottom: 8px;
  transition: background 0.2s;
}

.skill-tag:hover {
  background-color: #0366d6;
  color: #fff;
  border-color: #0366d6;
}

/* --- TIMELINE STYLES --- */
.timeline {
  position: relative;
  padding: 1rem 0;
  max-width: 800px;
  margin: 0 auto;
}

/* Vertical Line */
.timeline::after {
  content: '';
  position: absolute;
  width: 3px;
  background-color: #e1e4e8;
  top: 0;
  bottom: 0;
  left: 20px; 
  margin-left: -1px;
}

.timeline-item {
  padding: 0 0 2rem 50px; /* Space for line */
  position: relative;
}

/* Timeline Dot */
.timeline-item::after {
  content: '';
  position: absolute;
  width: 16px;
  height: 16px;
  background-color: #fff;
  border: 4px solid #0366d6;
  top: 5px;
  left: 12px;
  border-radius: 50%;
  z-index: 2;
}

/* Content Box */
.timeline-content {
  background: #fff;
  border: 1px solid #e1e4e8;
  border-radius: 8px;
  padding: 1.5rem;
  transition: transform 0.2s ease, box-shadow 0.2s ease;
}

.timeline-content:hover {
  transform: translateY(-2px);
  box-shadow: 0 8px 15px rgba(0,0,0,0.05);
  border-color: #0366d6;
}

/* Typography */
.role-title { font-size: 1.2rem; font-weight: 700; color: #24292e; margin-bottom: 0.25rem; }
.org-name { font-size: 1rem; font-weight: 600; color: #444; margin-bottom: 0.25rem; }
.time-period { font-size: 0.9rem; color: #586069; font-style: italic; display: block; margin-bottom: 1rem; }

.description { font-size: 0.95rem; color: #333; line-height: 1.6; }
.description ul { margin: 0.5rem 0 0 0; padding-left: 1.2rem; }
.description a { color: #0366d6; text-decoration: none; font-weight: 500; }
.description a:hover { text-decoration: underline; }

/* Badges */
.badge {
  display: inline-block;
  padding: 2px 8px;
  border-radius: 10px;
  font-size: 0.75rem;
  font-weight: 700;
  text-transform: uppercase;
  float: right;
  margin-left: 10px;
}
.badge-edu { background: #e1f5fe; color: #0277bd; }
.badge-work { background: #e8f5e9; color: #2e7d32; }
.badge-award { background: #fff8e1; color: #fbc02d; }
.badge-cert { background: #f3e5f5; color: #7b1fa2; }
</style>

<div class="cv-intro">
  <p>
    Ashutosh is currently pursuing a Master of Science in Quantitative Data Science Methods at the Eberhard Karls University of Tübingen. He is an engineer at heart, now focused on applying statistics and machine learning to econometrics, finance, and social sciences.
  </p>
  <p style="margin-top: 1rem;">
    Previously, Ashutosh spent three years as a Software Engineer at HSBC (Global Cloud Economics), where he focused on data engineering and forecasting models. He has also conducted research at the Max Planck Institute for Intelligent Systems and interned at the financial stability of the Deutsche Bundesbank.
  </p>
</div>

<div class="section-title">Technical Capabilities</div>

<div>
  <span class="skill-category">Languages & Tools</span>
  <span class="skill-tag">Python</span>
  <span class="skill-tag">R</span>
  <span class="skill-tag">SQL</span>
  <span class="skill-tag">MATLAB</span>
  <span class="skill-tag">Git</span>
  <span class="skill-tag">Linux</span>
  <span class="skill-tag">Docker</span>

  <span class="skill-category">Domain Expertise</span>
  <span class="skill-tag">Financial Economics</span>
  <span class="skill-tag">Probabilistic ML</span>
  <span class="skill-tag">Time Series</span>
  <span class="skill-tag">Econometrics</span>
  <span class="skill-tag">Bayesian Modelling</span>
  <span class="skill-tag">Optimization</span>
</div>

<div class="section-title">My Professional & Academic Journey</div>

<div class="timeline">

  <div class="timeline-item">
    <div class="timeline-content">
      <span class="badge badge-edu">Education</span>
      <div class="role-title">Master Thesis: Optimal Transport in Linear ICA</div>
      <div class="org-name">Max Planck Institute for Intelligent Systems and University of Tuebingen</div>
      <span class="time-period">Present</span>
      <div class="description">
        Researching the application of <strong>Optimal Transport theory</strong> to solve problems in linear Independent Component Analysis (ICA).
        <br>
        <em>Supervisors: Dr. Simon Buchholz, Prof. Dr. Michel Besserve, Prof. Dr. Joachim Grammig</em>
      </div>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-content">
      <span class="badge badge-work">Experience</span>
      <div class="role-title">Intern Quantitative Analyst (Financial Stability)</div>
      <div class="org-name">Deutsche Bundesbank, Frankfurt</div>
      <span class="time-period">July 2025 – Sept 2025</span>
      <div class="description">
        <ul>
          <li>Applied machine learning and time series forecasting to analyze investment fund portfolios.</li>
          <li>Focused on financial stability insights for non-bank financial intermediaries.</li>
        </ul>
      </div>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-content">
      <span class="badge badge-edu">Education</span>
      <div class="role-title">Erasmus Exchange (Financial Economics & ML)</div>
      <div class="org-name">KU Leuven, Belgium</div>
      <span class="time-period">Feb 2025 – June 2025</span>
      <div class="description">
        Focused on Financial Economics, Causal Machine Learning and Financial Engineering.
      </div>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-content">
      <span class="badge badge-work">Experience</span>
      <div class="role-title">Student Research Assistant (Optics & Sensing)</div>
      <div class="org-name">Max Planck Institute for Intelligent Systems</div>
      <span class="time-period">July 2024 – June 2025</span>
      <div class="description">
        Developed computer vision algorithms (emotion/head orientation) for <a href="https://nice.is.tue.mpg.de/" target="_blank">NICE Software</a>.
      </div>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-content">
      <span class="badge badge-award">Award</span>
      <div class="role-title">Winner - Best Pitch & Co-creation Prize</div>
      <div class="org-name">Neckarthon (Startup Center Tübingen)</div>
      <span class="time-period">November 2024</span>
      <div class="description">
        Won dual prizes for <strong>"Tue-bi-smart,"</strong> an ML-enabled transport prototype developed for Stadtwerke Tübingen.
      </div>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-content">
      <span class="badge badge-edu">Education</span>
      <div class="role-title">M.Sc. Quantitative Data Science Methods</div>
      <div class="org-name">Eberhard Karls Universität Tübingen</div>
      <span class="time-period">Started Oct 2023</span>
      <div class="description">
        Specializing in Econometrics, Machine Learning, and Financial Economics.
      </div>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-content">
      <span class="badge badge-work">Experience</span>
      <div class="role-title">Software Engineer (Cloud Economics)</div>
      <div class="org-name">HSBC Holdings PLC, Pune</div>
      <span class="time-period">Sept 2020 – Sept 2023</span>
      <div class="description">
        <ul>
          <li>Built real-time ETL pipelines (improving latency by 4x) and designed FinOps frameworks.</li>
          <li>Developed statistical models driving $500K in cloud cost savings.</li>
        </ul>
      </div>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-content">
      <span class="badge badge-cert">Certifications</span>
      <div class="role-title">Professional Certifications (2022)</div>
      <span class="time-period">2022</span>
      <div class="description">
        <ul>
          <li><strong>IBM Data Science Professional</strong> (Coursera/IBM) <br> <a href="https://coursera.org/verify/professional-cert/87ZBBTJ8QCSL" target="_blank">View Certificate</a></li>
          <li><strong>Google Cloud Professional Data Engineer</strong> (Expired)<br> <a href="https://www.credential.net/6c937fbd-ba97-4a68-820d-23e16ae1f685?key=b713da8be058129a4efeca42ed03d4efcf7c596ffa8e183b053d84e1964eb574" target="_blank">View Certificate</a></li>
        </ul>
      </div>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-content">
      <span class="badge badge-award">Award</span>
      <div class="role-title">Star Performer Award</div>
      <div class="org-name">HSBC Technology</div>
      <span class="time-period">Q2 2021</span>
      <div class="description">
        Awarded for high performance in cloud billing automation.
        <br>
        <a href="https://drive.google.com/file/d/1llMoV5QLbmlFwYC2jtjeVHTeXbjTyQty/view?usp=sharing" target="_blank">View Award</a>
      </div>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-content">
      <span class="badge badge-cert">Certifications</span>
      <div class="role-title">Professional Certifications (2021)</div>
      <span class="time-period">2021</span>
      <div class="description">
        <ul>
          <li><strong>FinOps Certified Practitioner</strong> <br> <a href="https://verify.skilljar.com/c/e9oki5d83km7" target="_blank">View Credential</a></li>
          <li><strong>Architecting with Google Compute Engine</strong> <br> <a href="https://www.coursera.org/account/accomplishments/specialization/certificate/Z9KAN3ZWHTQT" target="_blank">View Credential</a></li>
        </ul>
      </div>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-content">
      <span class="badge badge-work">Experience</span>
      <div class="role-title">Software Engineering Intern</div>
      <div class="org-name">Nvidia Corporation, Bengaluru</div>
      <span class="time-period">Aug 2019 – Dec 2019</span>
      <div class="description">
        Built a customer-facing Python tool with real-time Plotly visualizations to analyze SoC CPU usage.
      </div>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-content">
      <span class="badge badge-work">Experience</span>
      <div class="role-title">Internship: Industrial Process Optimization</div>
      <div class="org-name">iCreate, Ahmedabad</div>
      <span class="time-period">May 2018 – July 2018</span>
      <div class="description">
        Analyzed manufacturing plants to identify automation opportunities and submitted a process optimization report.
      </div>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-content">
      <span class="badge badge-edu">Education</span>
      <div class="role-title">B.E. Electrical and Electronics Engineering</div>
      <div class="org-name">BITS Pilani, Goa Campus</div>
      <span class="time-period">2016 – 2020</span>
      <div class="description">
        <strong>Achievement:</strong> Awarded the <a href="https://drive.google.com/file/d/1x1JBkKAigeM6XwsjZt23WU38eHTBqn3g/view?usp=sharing" target="_blank">Prime Minister's Scholarship Scheme</a> (2017) for academic excellence.
      </div>
    </div>
  </div>

</div>