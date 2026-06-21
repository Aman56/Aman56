---
layout: single
author_profile: true
title: "Projects"
permalink: /projects/
---

<div class="page-nav">
  <a href="/">Home</a> · <a href="/publications/">Publications</a> · <a href="/projects/">Projects</a> · <a href="/resume/">Resume</a> · <a href="/news/">News</a> · <a href="/network/">Network</a>
</div>

# Featured Projects

A selection of my most impactful work spanning research, production systems, and open-source contributions.

## Production Projects

### Behavior Prediction MoE for Audience Personalization

**Resonate Networks | Oct 2023 – Present**

<div class="project-card featured">
  <div class="project-header">
    <h3>Behavior Prediction Mixture-of-Experts System</h3>
    <span class="project-status">Production</span>
  </div>
  
  <div class="project-section">
    <h4>Problem</h4>
    <p>Improve user behavior prediction quality for audience-building and downstream personalization across millions of data points and hundreds of potential behavioral signals.</p>
  </div>

  <div class="project-section">
    <h4>Approach</h4>
    <ul>
      <li>Architected mixture-of-experts style models to specialize prediction across user segments and behavioral contexts</li>
      <li>Designed iterative model and feature engineering workflows for continuous improvement</li>
      <li>Built scalable training and evaluation pipelines on AWS infrastructure</li>
    </ul>
  </div>

  <div class="project-section">
    <h4>Outcomes</h4>
    <ul>
      <li><strong>5% performance lift</strong> over previous XGBoost baselines across primary metrics</li>
      <li>Inference pipeline optimized to serve predictions over <strong>3-trillion-row datasets</strong> with SLA compliance</li>
      <li>Full stack deployed on AWS (Spark, Scala, SageMaker) supporting real-time personalization</li>
      <li>Led evaluation and productionization of ~10 candidate models from 6 different vendors</li>
    </ul>
  </div>

  <div class="project-section">
    <h4>Technical Stack</h4>
    <span class="tech-tag">Python</span>
    <span class="tech-tag">Spark/Scala</span>
    <span class="tech-tag">AWS SageMaker</span>
    <span class="tech-tag">XGBoost</span>
    <span class="tech-tag">PyTorch</span>
  </div>
</div>

---

## Research Projects

### EmoMusic: AI System for Music-Emotion Understanding

**NYU (Prof. Gus Xia) | May 2023 – Oct 2023**

<div class="project-card">
  <h3>EmoMusic: Predicting Music-Emotion Interaction</h3>
  
  <div class="project-section">
    <h4>Overview</h4>
    <p>Developed an AI system using deep learning to predict and understand the interaction between music acoustics and emotional response. Applied state-of-the-art transformer models to audio signal analysis.</p>
  </div>

  <div class="project-section">
    <h4>Methodology</h4>
    <ul>
      <li>Engineered audio preprocessing pipeline using STFT and librosa for spectrogram representation</li>
      <li>Applied DeepMoji Transformers and GoogleNet for multi-modal feature extraction</li>
      <li>Trained on curated music-emotion dataset with ground-truth annotations</li>
    </ul>
  </div>

  <div class="project-section">
    <h4>Technical Stack</h4>
    <span class="tech-tag">PyTorch</span>
    <span class="tech-tag">DeepMoji</span>
    <span class="tech-tag">librosa</span>
    <span class="tech-tag">STFT</span>
    <span class="tech-tag">GoogleNet</span>
  </div>
</div>

---

### Orthogonal Coordinate Mapping (OCM) for Autonomous Driving

**Capgemini | Jul 2018 – Dec 2020**

<div class="project-card">
  <h3>OCM Algorithm for Level 3 Autonomous Driving</h3>
  
  <div class="project-section">
    <h4>Challenge</h4>
    <p>Develop a novel algorithm for critical decision-making in Level 3 autonomous driving systems that can robustly handle coordinate transformations and spatial reasoning in real-time.</p>
  </div>

  <div class="project-section">
    <h4>Solution</h4>
    <ul>
      <li>Invented Orthogonal Coordinate Mapping algorithm that improves spatial reasoning accuracy</li>
      <li>Rebuilt automated NDS (navigation data system) map extraction framework using PostgreSQL</li>
      <li>Achieved 35% reduction in data processing time through automation and optimization</li>
      <li>Developed 150+ Python utilities for feature extraction from map data</li>
    </ul>
  </div>

  <div class="project-section">
    <h4>Technical Stack</h4>
    <span class="tech-tag">Python</span>
    <span class="tech-tag">PostgreSQL</span>
    <span class="tech-tag">Pandas</span>
    <span class="tech-tag">NumPy</span>
  </div>
</div>

---

## Open Source Contributions

### torchMoji

Fork and wrapper around the DeepMoji model for sentiment, emotion, and sarcasm analysis.

- **Repository**: [github.com/Aman56/torchMoji](https://github.com/Aman56/torchMoji)
- **Use Case**: Applied to music-emotion prediction (EmoMusic) and emotional signal extraction

### DALI Dataset

Curated dataset of synchronized audio, lyrics, and vocal notes for music analysis.

- **Repository**: [github.com/Aman56/DALI](https://github.com/Aman56/DALI)
- **Application**: Used in EmoMusic research and music understanding projects

### grok

Reference implementation and research code for grokking phenomena analysis.

- **Repository**: [github.com/Aman56/grok](https://github.com/Aman56/grok)

---

<div class="page-nav">
  <a href="/">← Back to Home</a> · <a href="/publications/">Publications</a>
</div>
