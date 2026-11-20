---
title: "When Objectives and Evaluators Disagree: Evaluating Transfer for Post-hoc Demographic Framing Mitigation"
collection: publications
permalink: /publications/posthoc-mitigation-transfer-evaluation
venue: "20th Conference of the European Chapter of the Association for Computational Linguistics (EACL 2027)"
citation: '<b>Tunazzina Islam</b>. Proceedings of the 20th Conference of the European Chapter of the Association for Computational Linguistics (EACL 2027).'

---

[[arXiv]](https://arxiv.org/pdf/2611.25258) 

## Abstract
Post-hoc rewriting is used to reduce demographic disparities in LLM-generated text when the source model is inaccessible. A rewrite can look successful merely because it improved its own target or satisfied its selector. We study this as a transfer problem on 660 gender pairs and 1,980 age contrasts of demographic-conditioned climate messages. A rewriter proposes edits, a selection model chooses among constraint-satisfying candidates, and an independent evaluator uninvolved in either rates pairwise framing disparity. A fixed policy that always targets the message with the lower Persuasion Bias Index (PBI) transfers inconsistently across axes and outcome aggregations. An adaptive policy that proposes edits on both sides but accepts at most one significantly improves on that rule, applied to the same candidates, in seven of eight comparisons across two evaluator families, mostly by editing more pairs, not by guided direction choice, at higher preservation risk. A policy editing both messages gives the largest point reductions on fewer pairs. These two policies reduce disparity across a preservation-threshold sweep; absolute ratings vary across evaluator families and prompts. Shrinking the PBI gap increases dimension-mean disparity under both evaluator families. Mitigation should be reported as transfer across objectives, evaluators and their prompts, and editing policies.

