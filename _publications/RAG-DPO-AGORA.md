---
title: "Retrieval Improvements Do Not Guarantee Better Answers: A Study of RAG for AI Policy QA"
collection: publications
permalink: /publications/RAG-DPO-AGORA
venue: "Preprint 2026"
citation: 'Saahil Mathur, Ryan David Rittner, Vedant Ajit Thakur, Daniel Stuart Schiff, <b>Tunazzina Islam</b>. Under Review.'

---

## Abstract
Retrieval-augmented generation (RAG) systems are increasingly used to analyze complex policy documents, but achieving sufficient reliability for expert usage remains challenging in domains characterized by dense legal language and evolving, overlapping regulatory frameworks. We study the application of RAG to AI governance and policy analysis using the AI Governance and Regulatory Archive (AGORA) corpus, a curated collection of 947 AI policy documents. Our system combines a ColBERT-based retriever fine-tuned with contrastive learning and a generator aligned to human preferences using Direct Preference Optimization (DPO). We construct synthetic queries and collect pairwise preferences to adapt the system to the policy domain. Through experiments evaluating retrieval quality, answer relevance, and faithfulness, we find that domain-specific fine-tuning improves retrieval metrics but does not consistently improve end-to-end question answering performance. In some cases, stronger retrieval counterintuitively leads to more confident hallucinations when relevant documents are absent from the corpus. These results highlight a key concern for those building policy-focused RAG systems: improvements to individual components do not necessarily translate to more reliable answers. Our findings provide practical insights for designing grounded question-answering systems over dynamic regulatory corpora.
