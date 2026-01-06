---
title: "Reasoning-Based Refinement of Unsupervised Text Clusters with LLMs"
collection: publications
permalink: /publications/reasoning-vegan
venue: "Preprint 2026"
citation: '<b>Tunazzina Islam</b>. Preprint 2026. Under Review.'

---
<!--- [[arXiv]](https://arxiv.org/pdf/2404.10259.pdf) -->

## Abstract
Unsupervised methods are widely used to induce latent semantic structure from large text collections, yet their outputs often contain incoherent, 
redundant, or poorly grounded clusters that are difficult to validate without labeled data. We propose a **reasoning-based refinement framework** 
that leverages large language models (LLMs) not as embedding generators, but as semantic judges that validate and restructure the outputs of arbitrary 
unsupervised clustering algorithms. Our framework introduces three reasoning stages: (i) **coherence verification**, where LLMs assess whether 
cluster summaries are supported by their member texts; (ii) **redundancy adjudication**, where candidate clusters are merged or rejected based on 
semantic overlap; and (iii) **label grounding**, where clusters are assigned interpretable labels in a fully unsupervised manner. This design 
decouples representation learning from structural validation and mitigates common failure modes of embedding-only approaches. We evaluate the framework 
on real-world social media corpora from two platforms with distinct interaction models, demonstrating consistent improvements in cluster coherence and 
human-aligned labeling quality over classical topic models and recent representation-based baselines. Human evaluation shows strong agreement with 
LLM-generated labels, despite the absence of gold-standard annotations. We further conduct robustness analyses under matched temporal and volume 
conditions to assess cross-platform stability. Beyond empirical gains, our results suggest that LLM-based reasoning can serve as a general mechanism 
for validating and refining unsupervised semantic structure, enabling more reliable and interpretable analyses of large text collections without supervision. 
