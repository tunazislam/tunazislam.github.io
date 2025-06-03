---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
I am a Visiting Assistant Professor in the [Department of Computer Science (CS)](https://www.cs.purdue.edu/) at [Purdue University](https://www.purdue.edu/). My research interest lies in the intersection of **Natural Language Processing (NLP)** and **Computational Social Science (CSS)**. I earned my Ph.D. in CS from Purdue University, advised by [Dr. Dan Goldwasser](https://www.cs.purdue.edu/homes/dgoldwas/). I obtained M.Sc. in [Computer Science (CS)](https://odu.edu/compsci) from [Old Dominion University (ODU)](https://www.odu.edu/#prospective). Prior to joining ODU, I worked as a software developer on the R&D team of [Dohatec New Media](http://www.dohatec.com/) for two years. I completed my B.Sc in [Computer Science and Engineering (CSE)](https://cse.buet.ac.bd/) from [Bangladesh University of Engineering and Technology (BUET)](http://www.buet.ac.bd/).

Research Overview
======
We now live in a world where we can reach people directly through social media without relying on traditional media such as television, radio, and print. These platforms not only facilitate massive reach but also collect extensive user data, enabling highly targeted advertising. While *microtargeting* can improve content relevance, it also raises serious concerns: manipulation of user behavior, creation of echo chambers, and amplification of polarization. My research is motivated by the fact that some of these risks can be mitigated by providing transparency, identifying conflicting or harmful messaging choices, and indicating bias introduced in messaging in a nuanced way. I develop ***NLP*** and ***LLM-based methods*** to understand and analyze microtargeting dynamics: *what messages are sent*, *to whom*, and *how they are received*. My research delivers both ***CS artifacts***—*datasets*, *models*, *human-in-the-loop* & *machine-in-the-loop frameworks*—and ***empirical insights*** grounded in *real-world data*.  

Understanding microtargeting and activity patterns presents major technical challenges. Messaging strategies are dynamic, context-dependent, and often opaque. Furthermore, user identities and motivations are typically hidden or ambiguous. My work addresses these challenges through several core research directions: 
- **Characterizing users and their motivations** for engaging with digital platforms, especially when identity signals are sparse or ambiguous. 
<a href="https://ojs.aaai.org/index.php/ICWSM/article/view/19298" style="color: #8B4513;" > [ICWSM'22]</a> <a href="https://ojs.aaai.org/index.php/ICWSM/article/view/18057" style="color: #8B4513;" > [ICWSM'21] </a> <a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9364605" style="color: #8B4513;" > [ICSC'21] </a> <a href="https://ieeexplore.ieee.org/document/9378461" style="color: #8B4513;" > [IEEE BigData'20] </a>
- **Analyzing message content and user interaction**, capturing how individuals engage with targeted messaging across diverse contexts.
<a href="https://ojs.aaai.org/index.php/ICWSM/article/view/22156" style="color: #8B4513;" > [ICWSM'23]</a> <a href="https://dl.acm.org/doi/10.1145/3600211.3604665" style="color: #8B4513;" > [AIES'23]</a> <a href="https://ieeexplore.ieee.org/document/10021123" style="color: #8B4513;" > [IEEE BigData'22] </a>
- **Extracting deep thematic and argumentative structures** from content to reveal underlying discourse patterns. 
<a href="https://aclanthology.org/2025.findings-naacl.413.pdf" style="color: #8B4513;" > [NAACL'25]</a> <a href="https://arxiv.org/pdf/2403.10707.pdf" style="color: #8B4513;" > [ICWSM'25]</a> <a href="https://aclanthology.org/2023.findings-acl.313/" style="color: #8B4513;" > [ACL'23]</a> <a href="https://aclanthology.org/2022.dash-1.13.pdf" style="color: #8B4513;" > [DASH @EMNLP'22]</a> <a href="https://aclanthology.org/2022.naacl-main.427.pdf" style="color: #8B4513;" > [NAACL'22]</a>

A growing focus of my research is on the role of LLMs in enabling scalable and socially responsible analysis. This includes (but not limited to): 

**Responsible AI Integration:** *How can LLMs function as post-hoc (third-party) tools to analyze patterns in targeted communication, especially when internal platform logic is not transparent?* While platforms have white-box access, external stakeholders (researchers, auditors, policymakers) do not. My method offers an explainable approach to reverse-engineer targeting practices and uncover potential bias or messaging disparities.  
- Example: Post-hoc analysis of climate microtargeting. <a href="https://arxiv.org/pdf/2410.05401" style="color: #8B4513;" > [Preprint 2024]</a>

**Human‑AI collaboration:** *Can LLMs support a broader range of psycholinguistic tasks across diverse domains and social issues, particularly in contexts with varying data availability and complexity?* 
- Example:  Exploring how LLMs can assist human annotators in identifying morality frames within vaccination debates on social media. <a href="https://arxiv.org/pdf/2502.01991" style="color: #8B4513;" > [ACM WebSci 2025]</a>

**Unsupervised Topic Synthesis:** *How can LLMs uncover latent discourse, generate semantically rich topic labels, and serve as unsupervised annotators for large-scale social media texts?* 
- Examples: Integrating LLMs with advanced clustering algorithms enhances semantic coherence, supports unsupervised annotation and enables scalable analysis of vegan discourse <a href="http://tunazislam.github.io/publications/vegan-llms" style="color: #8B4513;">[Preprint 2025]</a>; Combining clustering with prompt-based labeling, LLMs iteratively build topic taxonomies and annotate moral framing in political messaging—without seed sets or domain expertise <a href="http://tunazislam.github.io/publications/topic-synthesis-election2024-llms" style="color: #8B4513;">[Preprint 2025]</a>. 

<!-- My primary research interest lies in **computational social science (CSS)**, **natural language processing (NLP)**, **social
media mining and analysis**. We now live in a world where we can reach people directly through social media without relying on traditional media such as television and radio. On the other hand, social media platforms collect vast amounts of data and create very specific profiles of different users
through targeted advertising. While effective in enhancing content relevance, *microtargeting* poses risks of manipulating user behavior, creating echo chambers, and fostering polarization. My research vision is to understand ***microtargeting*** and ***activity patterns*** on social media
by developing computational approaches and frameworks blending CSS, NLP, and artificial intelligence (AI). 

A significant challenge lies in understanding the messaging and how it changes depending on the targeted user groups. Another challenge arises when we do not know who the users are and what their motivations are for engaging with content. I address these challenges by developing computational approaches for (1) **characterizing user types and their motivations
for engaging with content** <a href="https://ojs.aaai.org/index.php/ICWSM/article/view/19298" style="color: #8B4513;" > [ICWSM 2022]</a> <a href="https://ojs.aaai.org/index.php/ICWSM/article/view/18057" style="color: #8B4513;" > [ICWSM 2021] </a> <a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9364605" style="color: #8B4513;" > [ICSC 2021] </a> <a href="https://ieeexplore.ieee.org/document/9378461" style="color: #8B4513;" > [IEEE BigData 2020] </a>;
(2) **analyzing the messaging consumed by users and their responses to it** <a href="https://ojs.aaai.org/index.php/ICWSM/article/view/22156" style="color: #8B4513;" > [ICWSM 2023]</a> <a href="https://dl.acm.org/doi/10.1145/3600211.3604665" style="color: #8B4513;" > [AIES 2023]</a> <a href="https://ieeexplore.ieee.org/document/10021123" style="color: #8B4513;" > [IEEE BigData 2022] </a>; (3) **delving into the deeper understanding
of the theme and arguments involved in the content** 
<a href="https://aclanthology.org/2025.findings-naacl.413.pdf" style="color: #8B4513;" > [NAACL 2025]</a> <a href="https://arxiv.org/pdf/2403.10707.pdf" style="color: #8B4513;" > [ICWSM 2025]</a> <a href="https://aclanthology.org/2023.findings-acl.313/" style="color: #8B4513;" > [ACL 2023]</a> <a href="https://aclanthology.org/2022.dash-1.13.pdf" style="color: #8B4513;" > [DASH @EMNLP 2022]</a> <a href="https://aclanthology.org/2022.naacl-main.427.pdf" style="color: #8B4513;" > [NAACL 2022]</a>. 

A major challenge is understanding the harmful effects of messaging choices when it comes to reinforcing ***bias*** and ***stereotypes***. Doing that requires us to scale up this analysis and adapt to ongoing continuous changing messaging. I study leveraging **large language models (LLMs)** to analyze societal opinions <a href="https://aclanthology.org/2025.findings-naacl.413.pdf" style="color: #8B4513;" > [NAACL 2025]</a>; as a tool to analyze microtargeting focusing on Thematic Insights and Fairness Evaluation <a href="https://arxiv.org/pdf/2410.05401" style="color: #8B4513;" > [Preprint 2024]</a>; foster human-AI collaboration in complex psycho-linguistic tasks <a href="https://arxiv.org/pdf/2502.01991" style="color: #8B4513;" > [ACM WebSci 2025]</a>; create AI-driven insights that inform policymaking and promote positive societal change. 

I am a Visiting Assistant Professor in the [Department of Computer Science (CS)](https://www.cs.purdue.edu/) at [Purdue University](https://www.purdue.edu/). I completed my Ph.D. in CS from [Purdue University](https://www.purdue.edu/), advised by [Dr. Dan Goldwasser](https://www.cs.purdue.edu/homes/dgoldwas/). I am fortunate to collaborate with [Dr. Ming Yin](https://mingyin.org/), [Dr. Ruqi Zhang](https://ruqizhang.github.io/), and [Dr. Lyle Ungar](https://www.cis.upenn.edu/~ungar/).
I obtained M.Sc. in [Computer Science (CS)](https://odu.edu/compsci) from [Old Dominion University (ODU)](https://www.odu.edu/#prospective) in 2018. Prior to joining ODU, I worked as a software developer on the R&D team of [Dohatec New Media](http://www.dohatec.com/) for two years. I completed my B.Sc in [Computer Science and Engineering (CSE)](https://cse.buet.ac.bd/) department from [Bangladesh University of Engineering and Technology (BUET)](http://www.buet.ac.bd/) in the year 2013.  -->


<!-- <span style="color: red">I’m on the academic job market 2024. I welcome any potential opportunities to connect and discuss how I can be a good fit for potential roles.</span>
<a href="https://tunazislam.github.io/files/CV_Tunazzina_Islam.pdf" style="color: blue;" > [CV]</a>
<a href="https://tunazislam.github.io/files/Research_Statement_Tunazzina_Islam.pdf" style="color: blue;" > [Research Statement]</a>
<a href="https://tunazislam.github.io/files/Teaching_Statement_Tunazzina_Islam.pdf" style="color: blue;" > [Teaching Statement]</a> -->
<!-- <a href="https://tunazislam.github.io/files/Diversity_Statement_Tunazzina_Islam.pdf" style="color: blue;" > [Diversity Statement]</a> -->



See my <a href="https://tunazislam.github.io/publications/" style="color: #8B4513;" > <b>publications here </b> </a> 
======
My <a href="https://scholar.google.com/citations?user=YNChCGMAAAAJ&hl=en" style="color: #8B4513;" > <b> Google Scholar </b> </a> and <a href="https://www.researchgate.net/profile/Tunazzina_Islam" style="color: #8B4513;" > <b> ResearchGate </b> </a> profile.

Recent News
======
* May 22, 2025: Senior Program Committee (SPC) of ICWSM 2026.
* May 20-23, 2025: Attended [WebSci'25](https://www.websci25.org/) and presented our work [Can LLMs Assist Annotators in Identifying Morality Frames? - Case Study on Vaccination Debate on Social Media](https://dl.acm.org/doi/10.1145/3717867.3717902). 
* April 29-May 04, 2025: Attended [NAACL 2025](https://2025.naacl.org/) and presented our work [Uncovering Latent Arguments in Social Media Messaging by Employing LLMs-in-the-Loop Strategy](https://aclanthology.org/2025.findings-naacl.413/). Also, I organized BoF session on <span style="color:red">"Understanding and Analyzing Microtargeting Patterns on Social Media"</span>.
* April 15-16, 2025: Attended [Midwest Speech and Language Days (MSLD)](https://nlp.nd.edu/msld25/) 2025 at the University of Notre Dame to present two posters.
* &#x1F3C6; April 11, 2025: Received Graduate Women in Science Program (WISP) award from College of Science, Purdue University.
* March 26, 2025: <span style="color:red">Organizer and Chair</span> of [Birds of a Feather (BoF) session](https://2025.naacl.org/calls/affinity/) in [NAACL 2025](https://2025.naacl.org/) on <span style="color:red">"Understanding and Analyzing Microtargeting Patterns on Social Media"</span>. Please join on May 2 (Friday), 9:00-10:30 MST, Room: 230 -Pecos, Albuquerque Convention Center.
* &#x1F3C6; March 19, 2025: Received NAACL 2025 Diversity and Inclusion Award (D&I Award).
* &#x1F4F0; March 11, 2025: My research and interview were featured in [AIhub](https://aihub.org/2025/03/11/interview-with-tunazzina-islam-understand-microtargeting-and-activity-patterns-on-social-media/).
<!--- * March 10, 2025: Joined as AI Forge Visiting Assistant Professor at [Purdue Computer Science](https://www.cs.purdue.edu/). -->
* &#x1F3C6; February 26, 2025: <span style="color:red"> My Ph.D. thesis proposal won the **best poster award in 2025 AAAI/SIGAI Doctoral Consortium**</span>. <a href="https://tunazislam.github.io/files/AAAI 2025 DC best poster.pdf" style="color: #5f5147;" onmouseover="this.style.color='black';" onmouseout="this.style.color='#5f5147';">[Announcement]</a> <a href="https://tunazislam.github.io/images/Best_Poster_Award_AAAI_DC_2025.jpeg" style="color: #5f5147;" onmouseover="this.style.color='black';" onmouseout="this.style.color='#5f5147';">[Photo]</a>
* February 25-March 04, 2025: Attending [AAAI 2025](https://aaai.org/conference/aaai/aaai-25/) and presenting my Ph.D. Thesis Proposal at <a style="color:red" href="https://aaai.org/conference/aaai/aaai-25/doctoral-consortium-call/">AAAI-25 Doctoral Consortium</a>.
* &#x1F393; February 07, 2025: <span style="color:red"> Defended my Ph.D. dissertation</span>.
* &#x1F4DD; January 31, 2025: Long paper accepted to publish in [ACM WebSci 2025](https://www.websci25.org/).
* &#x1F4DD; January 22, 2025: Long paper accepted to publish in Findings of [NAACL 2025](https://2025.naacl.org/).
* &#x1F3C6; November 02, 2024: Ph.D. Thesis Proposal accepted at <a style="color:red" href="https://aaai.org/conference/aaai/aaai-25/doctoral-consortium-call/">AAAI-25 Doctoral Consortium</a>.
* October 29-31, 2024: Attended at [2024 Academic Data Science Alliance (ADSA)](https://academicdatascience.org/adsa-meetings/2024-adsa-annual-meeting/) Annual Meeting and <span style="color:red"> organized Tutorial on "Analyzing Microtargeting on Social Media"</span>.
* October 04, 2024: <a style="color:red" href="https://www.icwsm.org/2025/organization/index.html#">Tutorial Co-Chair ICWSM 2025</a>. Please submit your proposal by January 15, 2025. cfp: [https://www.icwsm.org/2025/submit/index.html](https://www.icwsm.org/2025/submit/index.html)
* &#x1F4DD; July 15, 2024: Long paper accepted to publish in [ICWSM-2025](https://www.icwsm.org/2025/).
* July 7, 2024: Session proposal accepted at [2024 Academic Data Science Alliance (ADSA)](https://academicdatascience.org/adsa-meetings/2024-adsa-annual-meeting/) Annual Meeting.
* June 14-15, 2024: Attended [2024 Mexican NLP Summer School](https://ampln.github.io/escuelaverano2024/).
* June 12, 2024: Associate Chair (AC) of [CSCW 2025](https://cscw.acm.org/2025/).
* June 9, 2024: Associate Chair (AC) of [CSCW 2024](https://cscw.acm.org/2024/).
* May 20-21, 2024: Attended [Midwest Machine Learning Symposium (MMLS)](https://midwest-ml.org/2024/), 2024.
* May 09, 2024: Became Ambassador for ICWSM.
* April 15-16, 2024: Attended [Midwest Speech and Language Days (MSLD)](https://ai.engin.umich.edu/news/midwest-speech-and-language-days/) 2024 at the University of Michigan, Ann Arbor to give a talk.
* &#x1F3C6; March 28, 2024: Received Graduate School Summer Research Grant Award.
* February 6, 2024: Guest lecture **Natural Language Processing, Purdue University**.
* December 13, 2023: Passed prelim and became Ph.D. candidate.
* August 08-10, 2023: Attended [AIES-2023](https://www.aies-conference.com/2023/), Montreal, Canada.
* June 05-08, 2023: Attended [ICWSM-2023](https://www.icwsm.org/2023/index.html/), Limassol, Cyprus.
* &#x1F4DD; May 05, 2023: Long paper accepted in [AIES-2023](https://www.aies-conference.com/2023/) as oral presentation.
* &#x1F4DD; May 02, 2023: Long paper accepted in Findings of [ACL 2023](https://2023.aclweb.org/).
* &#x1F3C6; April 14, 2023: Received Graduate Teaching Award from Purdue CS department.
* December 17-20, 2022: Attended [IEEE BigData 2022](https://bigdataieee.org/BigData2022/), Osaka, Japan (Virtually).
* December 7-11, 2022: Attended [EMNLP 2022](https://2022.emnlp.org/), Abu Dhabi, UAE (Virtually).
* &#x1F4DD; October 24, 2022: Regular paper accepted to publish in [IEEE BigData 2022](https://bigdataieee.org/BigData2022/).
* &#x1F4DD; July 16, 2022: Long paper accepted to publish in [ICWSM-2023](https://www.icwsm.org/2023/index.html/).
* June 06-09, 2022: Attended [ICWSM-2022](https://www.icwsm.org/2022/index.html), Atlanta, Georgia.
* &#x1F3C6; May 9, 2022: Received [ACM-W scholarship](https://women.acm.org/scholars/acm-w-scholars/tunazzina-islam/) to attend ICWSM'22, a **one-time** award.
* May 9, 2022: Received ICWSM2022 travel grant.
* &#x1F3C6; April 11, 2022: Received Graduate School Summer Research Grant Award.
* &#x1F4DD; April 7, 2022: Long paper accepted to publish in [NAACL 2022](https://2022.naacl.org/).
* &#x1F4DD; July 15, 2021: Long paper accepted to publish in [ICWSM-2022](https://www.icwsm.org/2022/index.html/).
* June 08-10, 2021: Attended [ICWSM-2021](https://www.icwsm.org/2021/index.html), Atlanta, Georgia (Virtually).
* &#x1F3C6; March 30, 2021: Received Graduate School Summer Research Grant Award.
* &#x1F4DD; March 15, 2021: Long paper accepted to publish in [ICWSM-2021](https://www.icwsm.org/2021/index.html).
* January 27-29, 2021: Attended [IEEE ICSC 2021](https://semanticcomputing.wixsite.com/icsc2021), Irvine, California (Virtually).
* December 10-13, 2020: Attended [IEEE BigData 2020](https://bigdataieee.org/BigData2020/), Atlanta, Georgia (Virtually).
* &#x1F4DD; December 06, 2020: Short paper accepted to publish in [ICSC-2021](https://www.semanticcomputing.org/).
* August 31, 2020: Submitted Ph.D. Plan of Study.
* December 17, 2019: Passed Ph.D. qualifier.

<!---
* December 10-13, 2020: Attended [IEEE BigData 2020](https://bigdataieee.org/BigData2020/), Atlanta, Georgia (Virtually).
* August 31, 2020: Submitted Ph.D. Plan of Study.
* December 17, 2019: Passed Ph.D. qualifier.
* August 10-16, 2019: Attended [IJCAI-2019](https://ijcai19.org/), Macao, China.
* August 04-08, 2019: Attended [KDD 2019](https://www.kdd.org/kdd2019/), Anchoarge, Alaska.
* July 07-12, 2019: Attended International HPC Summer School [IHPCSS2019](https://ss19.ihpcss.org/), Kobe, Japan.
* January 7, 2019: Started Ph.D. in [Computer Science](https://www.cs.purdue.edu/) at [Purdue University, West Lafayette](https://www.purdue.edu/).
* October 15, 2018: Got admission offer for Ph.D. in [Computer Science](https://www.cs.purdue.edu/) from [Purdue University](https://www.purdue.edu/) beginning in Spring 2019. 
* June 07, 2019 : Paper accepted to publish in [WISDOM'19](https://sentic.net/wisdom/#wisdom2019) co-located with [KDD'19](https://www.kdd.org/kdd2019/), Anchorage, Alaska. 
* May 18, 2019 : Paper accepted for a presentation in [SocialNLP 2019](https://sites.google.com/site/socialnlp2019/) [@ IJCAI-2019](https://ijcai19.org/), Macao, China. 
* April 30, 2019: [Journal paper](https://ieeexplore.ieee.org/document/8703093) named "Analysis of Subtelomeric REXTAL Assemblies Using QUAST" is available online.
* April 12-13, 2019: Attended CRA-W Graduate Cohort Workshop, Chicago, IL.
* March 15, 2019: Selected to participate in the [IHPCSS2019](https://ss19.ihpcss.org/), Kobe, Japan.
* January 30, 2019: Paper accepted to publish in [TCBB journal](https://www.computer.org/web/tcbb).
* January 7, 2019: Started Ph.D. in [Computer Science](https://www.cs.purdue.edu/) at [Purdue University, West Lafayette](https://www.purdue.edu/).
* December 13-14, 2018: Attended [SCEC 2018](https://scec18.github.io/) in Delhi, India.
* October 15, 2018: Got admission offer for Ph.D. in [Computer Science](https://www.cs.purdue.edu/) from [Purdue University](https://www.purdue.edu/) with a Research Assistantship beginning in Spring 2019. 
* October 4, 2018: Awarded travel funding to attend Second Workshop on Software Challenges to Exascale Computing [SCEC 2018](https://scec18.github.io/).
* September 29, 2018: Attended [UM Explore Graduate Studies in CSE 2018 Workshop](https://www.eecs.umich.edu/cse/Explore_Grad_Studies/).
* Sepetember 26-28, 2018: Attended [GHC 2018](https://ghc.anitab.org/2018-attend/schedule-overview/poster-session/#biotech) in Houston, TX to present my research Poster.
* August 2018: Graduated with Master's degree in [Computer Science](https://odu.edu/compsci) from [Old Dominion University](https://www.odu.edu/#prospective), Norfolk, VA.
* July 26, 2018: Received travel award to attend [UM Explore Graduate Studies in CSE 2018 Workshop](https://www.eecs.umich.edu/cse/Explore_Grad_Studies/).
* April 24, 2018: Awarded as [Computer Science Outstanding Graduate Researcher](https://twitter.com/oducs/status/988885970081714176).
* March 25, 2018: A Paper titled "REXTAL: Regional Extension of Assemblies Using Linked-Reads" was accepted in [ISBRA 2018](http://alan.cs.gsu.edu/isbra18/), Beijing, China.
* September 22, 2017: Won **2nd prize** in [Tapia Student Poster Competition](https://twitter.com/Tunaz_Islam/status/911624351400767490) in ACM Richard Tapia Celebration of Diversity in Computing Conference, Atlanta, GA.
* June 16, 2017: A paper titled "Quantification of Twist from the Central Lines of β-strands" was accepted in [Journal of Computational Biology](https://home.liebertpub.com/publications/journal-of-computational-biology/31/overview).
* October 19-21, 2016: Attended GHC 2016 as a [GHC Scholar](https://ghc.anitab.org/2016-student-academic/scholarships/2016-ghc-scholars/attachment/tunazzina-islam-1/) in Houston, TX and presented my research Poster.
* September 14-17, 2016: Attended with the travel grant at ACM Richard Tapia Celebration of Diversity in Computing Conference, Austin, TX.
* April 15-16, 2016: Attended CRA-W Graduate Cohort Workshop, San Diego, CA.
-->

