---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* **Ph.D. in Computer Science**, [UC Berkeley (BAIR)](https://bair.berkeley.edu/), *Starting Fall 2025*  
  * Temporary advisors: [Aditi Krishnapriyan](https://a1k12.github.io/) and [Sergey Levine](https://people.eecs.berkeley.edu/~svlevine/)

* **B.S. in Computer Science (AI Specialization)**, [UC Irvine](https://uci.edu/), *2022 - 2024*  
  * *Graduated Summa Cum Laude*, **4.0 GPA**  
  * Graduate Courses: Deep Generative Models, Probabilistic and Bayesian Learning, Probabilistic Graphical Models

Technical Skills
======
* **Machine Learning**: Diffusion and Flow Models, Variational Inference, Bayesian Statistics and Learning, Large Language Models, Representation Learning  
* **Mathematics**: Measure and Real Analysis, Modern Probability and Statistics, Linear and Abstract Algebra  
* **Programming Languages**: Python, C++, C  

Work Experience
======
* **Student Researcher**, UC Irvine *(PI: [Padhraic Smyth](https://www.ics.uci.edu/~smyth/))*  
  * June 2023 – Present  

* **Research Assistant**, Lawrence Livermore National Laboratory *(PI: Dr. Mateusz Monterial)*  
  * June 2020 – July 2022  

* **Global Security Intern**, Lawrence Livermore National Laboratory *(PI: Dr. Mateusz Monterial)*  
  * June 2021 – August 2021  

* **Grader**, UC Irvine *(Supervisor: [Stephan Mandt](https://mandt.ai/))*  
  * January 2024 – April 2024  

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Self Study
======
Measure Theory
Probability
Real Analysis

Additional Projects
======
* **Score-Based Diffusion / Bridge Diffusion**  
  * Implemented state-of-the-art diffusion models via SDEs, including conditional diffusion, image infilling, and bridge diffusion.

* **Diffusion Forward Path Learning via RL**  
  * Learned diffusion model with trained forward paths via reinforcement learning (PPO), improving performance over DDPM on small-scale data.

* **Image Segmentation via Densely Connected Graphical Model**  
  * Implemented segmentation using a densely connected graphical model, outperforming CNNs by 5-10% on IoU and MSE.

* **Soundwave (Citrushack Winner 2023)**  
  * Developed an unsupervised music recommender using a VQ-Variational Autoencoder.

* **Super Mario Reinforcement Learning**  
  * Trained a PPO-based bot to beat Super Mario Bros., outperforming Double Deep Q-Net in training speed.

* **Protein Folding via Hidden Markov Models**  
  * Developed a variational expectation-maximization approach to improve secondary structure prediction accuracy by 70% over naive models.

* **Signal Denoising via LDPC**  
  * Implemented LDPC factor graphs using loopy BP, mean-field VI, and Metropolis Hastings, achieving near-optimal denoising.
