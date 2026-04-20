---
title: "Who Gets Which Message? Auditing Demographic Bias in LLM-Generated Targeted Text"
collection: publications
permalink: /publications/bias-llms-generated-climate-microtarget
venue: "In Findings of the 64th Annual Meeting of the Association for Computational Linguistics (ACL 2026)"
citation: '<b>Tunazzina Islam</b>. In Findings of the 64th Annual Meeting of the Association for Computational Linguistics (ACL 2026).'

---
[[arXiv]](https://arxiv.org/pdf/2601.17172)

## Abstract
Large language models (LLMs) are increasingly capable of generating personalized, persuasive text at scale, raising new questions about bias and fairness in automated communication. This paper presents the first systematic analysis of how LLMs behave when tasked with demographic-conditioned targeted messaging. We introduce a controlled evaluation framework using three leading models: GPT-4o, Llama-3.3, and Mistral-Large-2.1, across two generation settings: **Standalone Generation**, which isolates intrinsic demographic effects, and **Context-Rich Generation**, which incorporates thematic and regional context to emulate realistic targeting. We evaluate generated messages along three dimensions: *lexical content*, *language style*, and *persuasive framing*. We instantiate this framework on ***climate communication*** and find consistent age- and gender-based asymmetries across models: male- and youth-targeted messages tend to emphasize more *assertive* and *progressive* framing, while female- and senior-targeted messages more often reflect *warmth*, *care*, and *traditional* themes. Contextual prompts systematically amplify these disparities, with *persuasion* scores being higher for male-targeted messages, while age-related differences vary across models. Our findings demonstrate how demographic stereotypes can surface and intensify in LLM-generated targeted communication, underscoring the need for bias-aware generation pipelines and transparent auditing frameworks that explicitly account for demographic conditioning in socially sensitive applications.

