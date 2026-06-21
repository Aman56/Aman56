---
layout: single
author_profile: true
title: "Projects"
permalink: /projects/
---

<div class="page-nav">
  <a href="/Aman56/">Home</a> · <a href="/Aman56/publications/">Publications</a> · <a href="/Aman56/projects/">Projects</a> · <a href="/Aman56/resume/">Resume</a> · <a href="/Aman56/news/">News</a> · <a href="/Aman56/network/">Network</a>
</div>

## Research & Technical Projects

<div class="project-card">
  <h3>Mechanistic Interpretability of Grokking</h3>
  <p><strong>Status:</strong> Published (ICLR 2024)</p>
  <p><strong>Problem:</strong> The grokking phenomenon—sharp transition from memorization to generalization—lacks mechanistic explanation. Existing work treats grokking as optimization dynamics; the circuit-level view was underexplored.</p>
  <div><strong>Approach:</strong>
  <ul>
    <li>Developed sparse-dense circuit identification methodology using activation analysis and pruning</li>
    <li>Analyzed competition between subnetwork types during grokking transitions</li>
    <li>Traced circuit behavior through training on modular arithmetic and algorithmic tasks</li>
  </ul>
  </div>
  <div><strong>Outcomes:</strong>
  <ul>
    <li>Published as "A Tale of Two Circuits: Grokking as Competition of Sparse and Dense Subnetworks" at ICLR 2024</li>
    <li>Novel framework for understanding grokking through circuit competition</li>
    <li>Implications for generalization in other domains (language models, vision)</li>
  </ul>
  </div>
  <p><strong>Tech Stack:</strong> <span class="tech-tag">PyTorch</span> <span class="tech-tag">NumPy</span> <span class="tech-tag">Matplotlib</span> <span class="tech-tag">JAX</span></p>
  <p><a href="https://arxiv.org/abs/2303.11873">arXiv</a></p>
</div>

<div class="project-card">
  <h3>EmoMusic: Emotion Transfer via Neural Style</h3>
  <p><strong>Status:</strong> Research (2023)</p>
  <p><strong>Problem:</strong> Music emotion recognition is well-studied; emotion transfer (remixing a piece to convey different emotions) remains underexplored. How can we learn latent emotion-aware representations of music?</p>
  <div><strong>Approach:</strong>
  <ul>
    <li>Built representation learning pipeline combining musicological features with neural embeddings</li>
    <li>Trained encoder-decoder architecture with emotion-conditioned latent space</li>
    <li>Generated new musical pieces with controlled emotional characteristics</li>
    <li>Evaluated through perceptual studies and MIR metrics</li>
  </ul>
  </div>
  <div><strong>Outcomes:</strong>
  <ul>
    <li>Demonstrated feasibility of emotion transfer in music generation</li>
    <li>Bridged music information retrieval and deep learning interpretability</li>
    <li>Contributed to understanding representation learning in creative domains</li>
  </ul>
  </div>
  <p><strong>Tech Stack:</strong> <span class="tech-tag">PyTorch</span> <span class="tech-tag">LibROSA</span> <span class="tech-tag">MusicXML</span> <span class="tech-tag">Python</span></p>
</div>

<div class="project-card">
  <h3>OCM: Orthogonal Coordinate Mapping for Autonomous Driving</h3>
  <p><strong>Status:</strong> Completed</p>
  <p><strong>Problem:</strong> Multi-sensor fusion in autonomous vehicles requires robust coordinate transformation between camera, LiDAR, and GPS frames. Existing methods accumulate drift under challenging conditions.</p>
  <div><strong>Approach:</strong>
  <ul>
    <li>Developed orthogonal coordinate transformation framework using rotation matrices and Kalman filtering</li>
    <li>Integrated multi-sensor calibration pipeline for real-time fusion</li>
    <li>Tested on real-world driving scenarios in urban environments</li>
  </ul>
  </div>
  <div><strong>Outcomes:</strong>
  <ul>
    <li>10% improvement in coordinate accuracy over baseline methods</li>
    <li>Real-time performance on embedded systems</li>
    <li>Validated on production autonomous vehicle platform</li>
  </ul>
  </div>
  <p><strong>Tech Stack:</strong> <span class="tech-tag">C++</span> <span class="tech-tag">ROS</span> <span class="tech-tag">NumPy</span> <span class="tech-tag">Linux</span></p>
</div>

