---
layout: single
author_profile: true
title: "Publications"
permalink: /publications/
---

<div class="page-nav">
  <a href="/Aman56/">Home</a> · <a href="/Aman56/publications/">Publications</a> · <a href="/Aman56/projects/">Projects</a> · <a href="/Aman56/resume/">Resume</a> · <a href="/Aman56/news/">News</a> · <a href="/Aman56/network/">Network</a>
</div>

## Featured Publications

<div class="pub-item featured">
  <span class="pub-title">A Tale of Two Circuits: Grokking as Competition of Sparse and Dense Subnetworks</span>
  <p class="pub-authors">William Merrill, Nikolaos Tsilivis, <strong>Aman Shukla</strong></p>
  <span class="pub-venue">ICLR 2024</span>
  <p>This paper investigates grokking through the lens of mechanistic interpretability. We identify sparse and dense circuit structures that emerge during training and show how their competitive dynamics drive the grokking phenomenon.</p>
  <div class="pub-impact">
    <strong>Impact:</strong> Appeared in ICLR 2024 (tier-1 ML venue). Advances understanding of circuit competition and generalization dynamics in neural networks.
  </div>
  <a href="https://arxiv.org/abs/2303.11873" class="pub-link">arXiv</a> · <a href="https://iclr.cc" class="pub-link">ICLR</a> · <a href="https://scholar.google.com/citations?user=dtBDI_oAAAAJ&hl=en&oi=ao" class="pub-link">Scholar</a>
</div>

<div class="pub-item featured">
  <span class="pub-title">Modeling User Behavior from Adaptive Surveys with Supplemental Context</span>
  <p class="pub-authors"><strong>Aman Shukla</strong>, David P. Scantlebury, Ritesh Kumar</p>
  <span class="pub-venue">2025 Preprint</span>
  <p>A framework for personalization grounded in adaptive survey design and synthetic respondent modeling. We demonstrate +5% lift on audience prediction tasks and deploy inference at scale (3T rows on AWS).</p>
  <div class="pub-impact">
    <strong>Impact:</strong> Production-validated approach combining deep learning with survey science. Currently deployed at Resonate Networks.
  </div>
  <a href="https://arxiv.org/abs/2507.20919" class="pub-link">arXiv</a> · <a href="https://scholar.google.com/citations?user=dtBDI_oAAAAJ&hl=en&oi=ao" class="pub-link">Scholar</a>
</div>

## All Publications

<table class="pub-table">
  <thead>
    <tr>
      <th>Title</th>
      <th>Venue</th>
      <th>Year</th>
      <th>Links</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>A Tale of Two Circuits: Grokking as Competition of Sparse and Dense Subnetworks</td>
      <td>ICLR</td>
      <td>2024</td>
      <td><a href="https://arxiv.org/abs/2303.11873">arXiv</a> · <a href="https://scholar.google.com/citations?user=dtBDI_oAAAAJ&hl=en&oi=ao">Scholar</a></td>
    </tr>
    <tr>
      <td>Modeling User Behavior from Adaptive Surveys with Supplemental Context</td>
      <td>Preprint</td>
      <td>2025</td>
      <td><a href="https://arxiv.org/abs/2507.20919">arXiv</a> · <a href="https://scholar.google.com/citations?user=dtBDI_oAAAAJ&hl=en&oi=ao">Scholar</a></td>
    </tr>
  </tbody>
</table>

## Research Themes

### Mechanistic Interpretability
Understanding the internal mechanisms of neural networks through circuit analysis, with focus on sparse-dense competition, grokking phenomena, and generalization dynamics.

**Key Questions:** How do subnetworks specialize? What drives the transition from memorization to generalization? How can we interpret learned behaviors at scale?

### Personalization at Scale
Grounded personalization through adaptive survey design, synthetic respondent modeling, and audience understanding. Deployed in production ML systems handling billions of data points.

**Key Questions:** How can we reliably model user preferences from limited signals? What inference architectures scale to trillions of examples? How do we measure and sustain model lift?

### Production ML Infrastructure
End-to-end design of reliable model pipelines: training, serving, and monitoring at scale on AWS. Focus on model robustness, latency, and cost optimization for real-world deployment.

**Key Questions:** How do we handle model drift? What infrastructure patterns enable rapid experimentation? How do we maintain model quality under scale?
