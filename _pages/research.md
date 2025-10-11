---
title: "" 
permalink: /research/ 
author_profile: true
---
Research Overview
======
My research interests broadly lie in **AI for Societal Impact**, at the intersection of **Natural Language Processing (NLP)** and **Computational Social Science (CSS)**. My research has been published in prominent venues such as AAAI ICWSM, NAACL, EMNLP, AAAI, ACL, AAAI/ACM AIES, ACM WebSci, IEEE Big Data. 
<!-- My research is increasingly centered on exploring how **Generative AI (GenAI)** can power scalable and socially responsible insight, including (but not limited to): -->
<!-- My research interest lies in the intersection of **Natural Language Processing (NLP)** and **Computational Social Science (CSS)**. -->
<div>
<img src="/images/research.png" style="width: 950px; height: auto;">
</div>
<br>

### Understanding and Analyzing Microtargeting Patterns
We now live in a world where we can reach people directly through social media without relying on traditional media such as television, radio, and print. These platforms not only facilitate massive reach but also collect extensive user data, enabling highly targeted advertising. While *microtargeting* can improve content relevance, it also raises serious concerns: manipulation of user behavior, creation of echo chambers, and amplification of polarization. My research is motivated by the fact that some of these risks can be mitigated by providing transparency, identifying conflicting or harmful messaging choices, and indicating bias introduced in messaging in a nuanced way <a href="https://ojs.aaai.org/index.php/AAAI/article/view/35212" style="color: #8B4513;" > [AAAI'25]</a>. Understanding microtargeting patterns is essential to foster healthier public discourse in the digital age and support a more cohesive society. Analyzing microtargeting and activity patterns presents major technical challenges. First, messaging strategies are dynamic, context-dependent, and often opaque. Second, user identities and motivations are typically hidden or ambiguous. To address these challenges, I develop ***NLP*** and ***LLM-based methods*** to understand and analyze microtargeting dynamics: *what messages are sent*, *to whom*, and *how they are received*. My research focuses on developing computational methods for:
- **Characterizing users and their motivations** for engaging with digital platforms, especially when identity signals are sparse or ambiguous <a href="https://ojs.aaai.org/index.php/ICWSM/article/view/19298" style="color: #8B4513;" > [ICWSM'22]</a> <a href="https://ojs.aaai.org/index.php/ICWSM/article/view/18057" style="color: #8B4513;" > [ICWSM'21] </a> <a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9364605" style="color: #8B4513;" > [ICSC 2021] </a> <a href="https://ieeexplore.ieee.org/document/9378461" style="color: #8B4513;" > [IEEE BigData 2020] </a>.
- **Analyzing message content and user interaction**, capturing how individuals engage with targeted messaging across diverse contexts <a href="https://ojs.aaai.org/index.php/ICWSM/article/view/22156" style="color: #8B4513;" > [ICWSM'23]</a> <a href="https://dl.acm.org/doi/10.1145/3600211.3604665" style="color: #8B4513;" > [AIES'23]</a> <a href="https://ieeexplore.ieee.org/document/10021123" style="color: #8B4513;" > [IEEE BigData'22] </a>.
- **Extracting latent thematic and argumentative structures** to capture the nuances of messaging <a href="https://aclanthology.org/2025.findings-naacl.413.pdf" style="color: #8B4513;" > [NAACL'25]</a> <a href="https://ojs.aaai.org/index.php/ICWSM/article/view/35850" style="color: #8B4513;" > [ICWSM'25]</a>.

### Responsible AI Integration:
Building on my work understanding microtargeting patterns, I have a complementary line of research that audits both platform practices and AI-generated messaging, revealing how bias, fairness, and transparency emerge in algorithmic and AI-mediated communication.

- Opaque platform practices prevent external stakeholders (researchers, auditors, policymakers) from auditing microtargeting. To bridge this gap, I developed an LLM-based post-hoc auditing framework that reverse-engineers messaging practices, explains targeting choices, and surfaces demographic disparities. This framework demonstrates how ads differentially target young adults, women, and older populations in the climate debate, while fairness analysis reveals biases in model predictions, particularly affecting senior citizens and male audiences <a href="https://arxiv.org/pdf/2410.05401" style="color: #8B4513;" > [EMNLP’25]</a>.
- My work presents the first systematic audit of age and gender bias in LLM-generated persuasive climate messaging. Using GPT-4o, Llama-3.3, and Mistral-Large-2.1, this work contrasts intrinsic versus context-driven bias, showing how male/youth-targeted messages emphasize agency and innovation, while female/senior ones stress care and tradition. Findings highlight the need for bias-aware generation pipelines and transparent auditing in socially sensitive communication <a href="http://tunazislam.github.io/publications/bias-llms-generated-climate-microtarget" style="color: #8B4513;">[Preprint'25c]</a>.

### Human‑AI Collaboration:
My research develops human–AI collaborative frameworks that position AI as partners to amplify, not replace, human expertise.

- I developed a holistic framework for social media posts, integrating stance, reason, and moral sentiment analysis with minimal supervision. This work studies how to model the dependencies between the different levels of analysis and incorporate **human insights** into the learning process <a href="https://aclanthology.org/2022.naacl-main.427.pdf" style="color: #8B4513;" > [NAACL'22]</a>. I further advanced this with an *interactive* framework to extract nuanced arguments <a href="https://aclanthology.org/2022.dash-1.13.pdf" style="color: #8B4513;" > [DASH @EMNLP'22]</a> 
and a *concept learning* framework for theme discovery validated by experts <a href="https://aclanthology.org/2023.findings-acl.313/" style="color: #8B4513;" > [ACL'23]</a>.

- I explored how LLMs can assist human annotators in identifying morality frames in vaccination debates on social media. Findings showed that LLM-assisted workflows improve annotation quality, reduce task difficulty, lower cognitive load, and speed up the annotation process <a href="https://arxiv.org/pdf/2502.01991" style="color: #8B4513;" > [ACM WebSci'25]</a>.
  
- ***ChiPT: A Human-in-the-Loop GenAI Assistant for Manufacturing Training***– In industry settings, I have designed a domain-specific Retrieval-Augmented Generation (RAG) system with scalable human-in-the-loop feedback that assists workers with real-time training, troubleshooting, and skill development. ChiPT leverages process manuals, expert feedback, and verified responses to enhance knowledge transfer (from retiring experts to new employees) and reduce expert workload [Preprint'25c].


### AI-Driven Discourse Analysis: 
*How can LLMs uncover latent discourse, generate semantically rich topic labels, and serve as unsupervised annotators for large-scale social media texts?* 
- Integrating LLMs with advanced clustering algorithms enhances semantic coherence, supports unsupervised annotation and enables scalable analysis of vegan discourse <a href="http://tunazislam.github.io/publications/vegan-llms" style="color: #8B4513;">[Preprint'25a]</a>
- Combining clustering with prompt-based labeling, LLMs iteratively build topic taxonomies and annotate moral framing in political messaging—without seed sets or domain expertise <a href="http://tunazislam.github.io/publications/topic-synthesis-election2024-llms" style="color: #8B4513;">[Preprint'25b]</a>

These contributions yield both ***CS artifacts***—*datasets*, *models*, *human-in-the-loop*, *machine-in-the-loop*, *bias auditing (including post-hoc auditing of platform practices and GenAI bias evaluation)* frameworks—and ***empirical insights*** grounded in *real-world data*. I have applied these methods to a wide range of socially significant domains, including *election*, *climate debate*, *COVID-19 vaccine debate*, *lifestyle choices* (*yoga*, *keto*, *veganism*), *immigration*.  


