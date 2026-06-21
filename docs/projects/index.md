---
layout: single
author_profile: true
title: "Projects"
permalink: /projects/
---

<div class="page-nav">
  <a href="/">Home</a> · <a href="/publications/">Publications</a> · <a href="/projects/">Projects</a> · <a href="/resume/">Resume</a> · <a href="/news/">News</a> · <a href="/network/">Network</a>
</div>

## Production Projects

<div class="project-card">
  <h3>Audience Personalization via Synthetic Respondents</h3>
  <p><strong>Organization:</strong> Resonate Networks | <strong>Status:</strong> Production</p>
  <p><strong>Problem:</strong> Traditional audience segmentation relies on limited demographic data and fails to capture nuanced behavioral preferences. Existing models achieve modest accuracy on holdout user populations.</p>
  <p><strong>Approach:</strong> Built an end-to-end personalization pipeline grounded in survey science:
  <ul>
    <li>Adaptive survey framework to elicit user preferences and behavioral signals</li>
    <li>Synthetic respondent generator using deep learning (multi-task DNN with auxiliary objectives)</li>
    <li>Inference pipeline serving personalized predictions to 3 trillion example rows on AWS (using PyTorch with distributed training)</li>
    <li>Monitoring and retraining infrastructure to track model drift and sustain performance</li>
  </ul>
  <p><strong>Outcomes:</strong>
  <ul>
    <li>+5% lift over XGBoost baseline on held-out user populations</li>
    <li>3T-row inference deployment on AWS, sustaining <200ms p99 latency</li>
    <li>Measurable business impact: 12% improvement in campaign targeting precision</li>
    <li>2025 preprint documenting framework and methodology</li>
  </ul>
  <p><strong>Tech Stack:</strong> <span class="tech-tag">PyTorch</span> <span class="tech-tag">Python</span> <span class="tech-tag">AWS</span> <span class="tech-tag">PostgreSQL</span> <span class="tech-tag">Redis</span> <span class="tech-tag">FastAPI</span> <span class="tech-tag">Docker</span></p>
</div>

<div class="project-card">
  <h3>Mechanistic Interpretability of Grokking</h3>
  <p><strong>Organization:</strong> NYU / Research | <strong>Status:</strong> Published (ICLR 2024)</p>
  <p><strong>Problem:</strong> The grokking phenomenon—sharp transition from memorization to generalization—lacks mechanistic explanation. Existing work treats grokking as optimization dynamics; the circuit-level view was underexplored.</p>
  <p><strong>Approach:</strong>
  <ul>
    <li>Developed sparse-dense circuit identification methodology using activation analysis and pruning</li>
    <li>Analyzed competition between subnetwork types during grokking transitions</li>
    <li>Traced circuit behavior through training on modular arithmetic and algorithmic tasks</li>
    <li>Grounded explanations in mechanistic interpretability literature (Anthropic, Distill)</li>
  </ul>
  <p><strong>Outcomes:</strong>
  <ul>
    <li>Published at ICLR 2024 (top-tier ML venue)</li>
    <li>Novel framework for understanding grokking through circuit competition</li>
    <li>Implications for generalization in other domains (language models, vision)</li>
    <li>Contributed to interpretability research community (cited in follow-up work)</li>
  </ul>
  <p><strong>Tech Stack:</strong> <span class="tech-tag">PyTorch</span> <span class="tech-tag">NumPy</span> <span class="tech-tag">Matplotlib</span> <span class="tech-tag">JAX</span></p>
</div>

<div class="project-card">
  <h3>EmoMusic: Emotion Transfer via Neural Style</h3>
  <p><strong>Organization:</strong> NYU / Research | <strong>Status:</strong> Research (2023)</p>
  <p><strong>Problem:</strong> Music emotion recognition is well-studied; emotion transfer (remixing a piece to convey different emotions) remains underexplored. How can we learn latent emotion-aware representations of music?</p>
  <p><strong>Approach:</strong>
  <ul>
    <li>Built representation learning pipeline combining musicological features with neural embeddings</li>
    <li>Trained encoder-decoder architecture with emotion-conditioned latent space</li>
    <li>Generated new musical pieces with controlled emotional characteristics</li>
    <li>Evaluated through perceptual studies and MIR metrics</li>
  </ul>
  <p><strong>Outcomes:</strong>
  <ul>
    <li>Demonstrated feasibility of emotion transfer in music generation</li>
    <li>Bridged music information retrieval and deep learning interpretability</li>
    <li>Contributed to understanding representation learning in creative domains</li>
  </ul>
  <p><strong>Tech Stack:</strong> <span class="tech-tag">PyTorch</span> <span class="tech-tag">LibROSA</span> <span class="tech-tag">MusicXML</span> <span class="tech-tag">Python</span></p>
</div>

<div class="project-card">
  <h3>Orthogonal Coordinate Mapping for Autonomous Driving</h3>
  <p><strong>Organization:</strong> Capgemini / Internship | <strong>Status:</strong> Completed</p>
  <p><strong>Problem:</strong> Multi-sensor fusion in autonomous vehicles requires robust coordinate transformation between camera, LiDAR, and GPS frames. Existing methods accumulate drift under challenging conditions.</p>
  <p><strong>Approach:</strong>
  <ul>
    <li>Developed orthogonal coordinate transformation framework using rotation matrices and Kalman filtering</li>
    <li>Integrated multi-sensor calibration pipeline for real-time fusion</li>
    <li>Tested on real-world driving scenarios in urban environments</li>
  </ul>
  <p><strong>Outcomes:</strong>
  <ul>
    <li>10% improvement in coordinate accuracy over baseline methods</li>
    <li>Real-time performance on embedded systems</li>
    <li>Validated on production autonomous vehicle platform</li>
  </ul>
  <p><strong>Tech Stack:</strong> <span class="tech-tag">C++</span> <span class="tech-tag">ROS</span> <span class="tech-tag">NumPy</span> <span class="tech-tag">Linux</span></p>
</div>

## Open Source Contributions

<div class="project-card">
  <h3>Interpretability Research Framework</h3>
  <p>Tools for circuit analysis, activation visualization, and mechanistic interpretability. Used in multiple published papers.</p>
  <p><a href="https://github.com/Aman56">GitHub</a></p>
</div>

<div class="project-card">
  <h3>PyTorch ML Infrastructure</h3>
  <p>Utilities for distributed training, model serving, and monitoring. Deployed in production at Resonate.</p>
  <p><a href="https://github.com/Aman56">GitHub</a></p>
</div>

<div class="project-card">
  <h3>Data Pipeline Tools</h3>
  <p>ETL and feature engineering libraries for large-scale ML workflows on AWS.</p>
  <p><a href="https://github.com/Aman56">GitHub</a></p>
</div>

---

<div class="page-nav">
  <a href="/">Home</a> · <a href="/publications/">Publications</a> · <a href="/projects/">Projects</a> · <a href="/resume/">Resume</a> · <a href="/news/">News</a> · <a href="/network/">Network</a>
</div>
