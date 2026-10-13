---
title: "Pareto-Dominance Supervision for Reducing Demographic Framing Disparities"
collection: publications
permalink: /publications/pareto-teacher-alignment
venue: "arXiv 2026"
citation: '<b>Tunazzina Islam</b>. Under Review.'

---

[[arXiv]](https://arxiv.org/abs/2606.10126) 

## Abstract

Large language models can tailor messages to readers of different ages or genders, but may also introduce differences in tone, confidence, and how readers are addressed. We study how to reduce measured framing disparities while preserving the requested topic and context. Our approach uses a student model and a larger teacher model to generate alternative revisions of message pairs, with each model revising both demographic versions together. It evaluates revisions using multiple measures, retains feasible candidates that are not clearly outperformed, and constructs preferences only when one revision improves at least one measure beyond a specified margin without worsening the others---a relation we call *margin-based Pareto dominance*. We use these examples for supervised fine-tuning followed by preference optimization. On climate change and vaccination messaging, the primary student reduces formality and emotional-framing disparities while improving contextual fidelity relative to its unaligned baseline. Lexical outcomes differ by demographic attribute: scores decrease on the youngest-vs-oldest comparisons for both tested students, whereas gender-associated outcomes differ between them. Persuasion-bias gains also vary by domain and configuration. These findings support dominance-derived supervision while showing why aggregate scores should be accompanied by attribute-level evaluation.

