---
title: "Pareto-Guided Teacher Alignment for Fair Personalized Text Generation"
collection: publications
permalink: /publications/pareto-teacher-alignment
venue: "Preprint 2026"
citation: '<b>Tunazzina Islam</b>. Under Review.'

---

## Abstract

Personalized persuasive text generation can improve relevance and engagement, but demographic conditioning may also introduce unequal framing across
groups. We study fairness mitigation in personalized generation as a constrained multi-objective alignment problem: reduce demographic disparities 
while preserving personalization fidelity. We propose a **Pareto-guided teacher alignment** framework that combines revision-based candidate 
generation, pair-aware feasibility gating, Pareto-style candidate selection, and optional preference optimization through supervised fine-tuning and 
direct preference optimization. We evaluate the framework on climate change and vaccination persuasion tasks using a controlled context-rich 
demographic grid with matched gender and age pairs and a unified *five-audit* evaluation suite spanning persuasion bias, formality disparity, 
emotional framing disparity, lexical association disparity, and personalization fidelity. Across both domains and cross-family transfer settings, 
no single alignment strategy dominates all objectives simultaneously. Instead, methods occupy different regions of a fairness--personalization Pareto 
frontier: some achieve stronger disparity reductions, while others better preserve personalization or demographic stability. Our results show that 
fairness mitigation effects are objective-dependent and transfer inconsistently across domains and model families, motivating bounded-regression, 
multi-audit model selection over single-metric optimization for fairness-sensitive personalized generation.

