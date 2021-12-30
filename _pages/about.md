---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

**Site is under construction**

Hei! I'm a student at [Aalto University](https://www.aalto.fi/en), and I'm working towards a Bachelor's degree in Data Science.
I expect to graduate in summer 2022, probably in June.
I will undertake Master's studies in fall 2022 at the same university or elsewhere.

My undergraduate studies cover the foundations of data science: computer science, math, and statistics.
In addition, through university courses, projects, and internships, I have obtained a solid foundation of machine learning (ML),
grounded in math and statistics.

*Updates:* I'll be joining [Aalto Probabilistic ML group](https://research.cs.aalto.fi/pml/) as a research assistant.
Currently, I'm looking for summer internship opportunities in machine learning.
Although I'm leaning towards ML research since that's the focus of my ML courses,
I'm also interested in ML engineering since I think it can make a visible impact more quickly than pure research.

# Interests

## Research interests

My research interests include causality (causal inference and causal discovery), deep learning (DL), and probabilistic machine learning (PML).

With causal analysis, one can transition from pattern recognition done by normal ML methods to interventions and counterfactual reasoning, a desirable property of intelligent systems. I mainly work with causal inference assumptions and treatment effect estimation methods, such as double machine learning, doubly robust estimators, and instrumental variables. One could also estimate treatment effects with arbitrary ML models. However, to do so, one needs to be informed of which explanatory variables to include. This information is usually encoded as a directed acyclic graph (DAG), which is one type of probabilistic graphical models (PGMs).

Regarding PML, I'm interested in latent variable modeling, PGMs, Bayesian methods, variational autoencoders (VAEs), generative adversarial networks (GANs), and normalizing flows. I believe that probabilistic modeling could make ML more transparent by providing outputs augmented with uncertainty measures such as credible intervals (instead of just a number like, e.g., random forests), which would be more informative to users and decision-makers.

When it comes to DL, I like to study various models for different applications, such as natural language processing or computer vision. I'm not so interested in coming up with new modules such as attention, but rather I'd like to discover unexpected ways to successfully integrate different building blocks and build a good DL model.

At the intersection of causality, DL, and PML, I'm investigating how to encode causal relationships as inductive biases for ML models while learning how to improve the performance of causal estimators with complex ML methods such as neural networks. That is, I'd like to know how ML could help causality and vice versa. However, both causal inference and ML methods typically lack uncertainty quantification, and this is where the probabilistic modeling framework could help.

## Machine learning engineering

Today's ML research is still disconnected from the industry, whose services could affect millions of people. Whereas ML research typically focuses on inventing models with high accuracies, real-world software services need continuous deployment and updates reflecting the surrounding environment. This is especially true for ML-based services because the deployed ML model is invalid once the environment differs from data used to train the model. The emerging field of MLOps aims to address this by, e.g., providing tools for integrating ML with a larger service by leveraging best practices from software development and DevOps. As a first step towards becoming an ML engineer and bridge the gap between ML research and industry, I have recently completed a course project about MLOps and the BERT language model.

