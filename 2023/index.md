---
title: NLP-OSS 2023
layout: default
---

# 3rd Workshop for Natural Language Processing Open Source Software (NLP-OSS) <br>

### 6 Dec 2023 @ [EMNLP 2023](https://2023.emnlp.org/) in Singapore

<br><br>With great scientific breakthrough comes solid engineering and open communities. The Natural Language Processing (NLP) community has benefited greatly from the open culture in sharing knowledge, data, and software. The primary objective of this workshop is to further the sharing of insights on the engineering and community aspects of creating, developing, and maintaining NLP open source software (OSS), which we seldom talk about in scientific publications. Our secondary goal is to promote synergies between different open source projects and encourage cross-software collaborations and comparisons.

There are many workshops focusing on the creation and curation of open language resources and annotations (e.g. BUCC, GWN, LAW, LOD, WAC). Moreover, we have the flagship LREC conference dedicated to linguistic resources. However, the engineering aspects of NLP-OSS are overlooked and under-discussed within the community. There are open source conferences and venues (such as FOSDEM, OSCON, Open Source Summit) where discussions range from operating system kernels to air traffic control hardware but the representation of NLP related presentations is limited. In the Machine Learning (ML) field, the Journal of Machine Learning Research - Machine Learning Open Source Software (JMLR-MLOSS) is a forum for discussions and dissemination of ML OSS topics. We envision that the Workshop for NLP-OSS becomes a similar avenue for NLP-OSS discussions.

Recently there have been successful Big Science workshop series which examine and promote open science in NLP. While important and complementary, the goals of Big Science are distinct from those of NLP-OSS which focuses more on the community of practice in open-source software in support of NLP and language technologies. We expect many who participated in the BigScience workshop to participate in NLP-OSS as many of the participants are former PC members in past editions of NLP-OSS. Another grassroot community movement, Eleuther AI started with the researchers attempting to replicate commercial language models and has since grown to an active decentralized community of volunteer researchers, engineers, and developers focused on AI alignment, scaling, and open source AI research.

With the rise of open source startups like Huggingface, the democratization of NLP gives researchers and the general public easy access to language models once available only to a handful of industrial research labs. This acceleration of NLP tools availability creates new synergies between cloud integrations, e.g. Huggingface x AWS Sagemaker, that allows engineers and researchers to train and deploy live applications with minimal infrastructure setups. Building on the shoulders of giants, the scikit-learn and Huggingface ecosystems are now interoperable under the skops framework.
We want to highlight these emergent communities and synergies in the NLP-OSS workshop and promote future collaborations with like-minded open source NLP researchers in the third NLP-OSS workshop. We hope that the NLP-OSS workshop could also be hosted in an *ACL conference, and be the intellectual forum to collate this type of knowledge, announce new software/features, promote the open source culture and OSS best practices.


## Call for Papers

We invite full papers (8 pages) or short papers (4 pages) on topics related to NLP-OSS broadly categorized into (i) software development, (ii) scientific contribution and (iii) NLP-OSS case studies.

 - **Software Development**
   - Designing and developing NLP-OSS
   - Licensing issues in NLP-OSS
   - Backward compatibility and stale code in NLP-OSS
   - Growing, maintaining and motivating an NLP-OSS community
   - Best practices for NLP-OSS documentation and testing
   - Contribution to NLP-OSS without coding
   - Incentivizing OSS contributions in NLP
   - Commercialization and Intellectual Property of NLP-OSS
   - Defining and managing NLP-OSS project scope
   - Issues in API design for NLP
   - NLP-OSS software interoperability
   - Analysis of the NLP-OSS community
<br>
 - **Scientific Contribution**
   - Surveying OSS for specific NLP task(s)
   - Demonstration, introductions and/or tutorial of NLP-OSS
   - Small but useful NLP-OSS
   - NLP components in ML OSS
   - Citations and references for NLP-OSS
   - OSS and experiment replicability
   - Gaps between existing NLP-OSS
   - Task-generic vs task-specific software
<br>
 - **Case studies**
   - Case studies of how a specific bug is fixed or feature is added
   - Writing wrappers for other NLP-OSS
   - Writing open-source APIs for open data
   - Teaching NLP with OSS
   - NLP-OSS in the industry

## Submission information

Authors are invited to submit a

- Full paper up to 8 pages of content or
- Short paper up to 4 pages of content

Submissions can be non-archival and be presented in the NLP-OSS workshop, but we would still require at least a 4-page submission so that reviewers have enough information to make the acceptance/rejection decision. This non-archival option is helpful for author(s) who wants to publish or had published the work elsewhere and would like to present/discuss pertinent NLP-OSS related work to the workshop PCs and attendees.

All papers are allowed unlimited but sensible pages for references. Final camera-ready versions will be allowed an additional page of content to address reviewers' comments.

Due to the nature of open source software, we find it a bit tricky to "anonymize" "open source". For this reason, we don't require your publication to be anonymous. However, if you prefer your paper to be anonymized, please mask any identifiable phrase with REDACTED. 

Submission should be formatted according to the EMNLP 2023 LaTeX or MS Word templates at [https://2023.emnlp.org/calls/style-and-formatting/](https://2023.emnlp.org/calls/style-and-formatting/)
<br><br>
Submissions should be uploaded to OpenReview conference management system at [https://openreview.net/group?id=EMNLP/2023/Workshop/NLP-OSS](https://openreview.net/group?id=EMNLP/2023/Workshop/NLP-OSS)

<!-- **Note:** Paper can be [dual-submitted](https://2023.emnlp.org/call-for-papers) to both EMNLP 2023 and the NLP-OSS workshop. -->

## Important dates

The 3rd NLP-OSS workshop will be co-located with the EMNLP 2023 conference.

- Paper submission: 09 August, 2023
- Paper Reviews Starts: 25 August 2023
- Paper Reviews Due: 01 October 2023
- Notification of Acceptance: 10 October 2023
- Camera-Ready Version: 25 October 2023
- Workshop: 6 Dec 2023

## Invited Speakers

<br><br>
<h3><strong>trlX: A Framework for Large Scale Open Source RLHF</strong> </h3>
<h3><a href="https://www.louiscastricato.com/">Louis Castricato</a> </h3>
<br>
Reinforcement learning from human feedback (RLHF) utilizes human feedback to better align large language models with human preferences via online optimization against a learned re- ward model. Current RLHF paradigms rely on Proximal Policy Optimization (PPO), which quickly becomes a challenge to implement and scale up to large architectures. To address this difficulty we created the <i><a href="https://github.com/CarperAI/trlx">trlX library</a></i> as a feature-complete open-source framework for RLHF fine-tuning of models up to and exceeding 70 billion parameters. This talk presents the trlX implementation that supports for multiple types of distributed training including distributed data par- allel, model sharded, as well as tensor, sequential, and pipeline parallelism.
<br><br>
<p>
<img src="https://static.wixstatic.com/media/f27bfa_22c58165c6eb4eac9a166487c54c0fd2~mv2.png/v1/crop/x_46,y_0,w_661,h_960/fill/w_625,h_960,al_c,q_90,enc_auto/coffee.png" align="left" style="margin-right: 32px; margin-bottom: 16px;" width=120px height=159px >
</p>
<h4> Bio </h4>
<p>Louis Castricato is a research scientist at EleutherAI, working on RLHF infrastructure and engineering. Previously, Louis was head of LLMs at Stability AI and team lead at CarperAI, the largest open source RLHF group, as well as a PhD student at Brown University.</p>
<br><br><br><br>


<h3><strong></strong>Southeast Asia LLMs: SEA-LION and Wangchan-LION</h3>
<h3> <a href="https://www.linkedin.com/in/david-ong-tw">David Tat-Wee Ong</a> and <a href="https://www.linkedin.com/in/peerat-limkonchotiwat">Peerat Limkonchotiwat</a> </h3>
<br>
<i><a href="https://github.com/aisingapore/sealion">SEA-LION</a></i>i> (Southeast Asian Languages In One Network) is a family of multilingual LLMs that is specifically pre-trained and instruct-tuned for the South- east Asian (SEA) region, incorporating a custom SEABPETokenizer which is specially tailored for SEA languages. The first part of this talk will cover our design philosophy and pre-training methodology for SEA- LION. The second part of this talk will cover <i><a href="https://github.com/PyThaiNLP/pythainlp">PyThaiNLP's</a></i>i> work on Wangchan-LION, an instruct-tuned version of SEA-LION for the Thai community.
<br><br>
<p>
<img src="https://avatars.githubusercontent.com/u/13075447?v=4" align="left" style="margin-right: 32px; margin-bottom: 16px;" width=160px height=159px >
</p>
<h4> Bio </h4>
<p>David is presently the Head of Engineering in AI Singapore’s (AISG) Products pillar, managing a team of software engineers to support AISG’s Products research implementation. David Tat-Wee holds a M.Sc in Computer Science and a M.Sc in Financial Engineering from NUS.</p>
<br><br>
<p>
<img src="https://media.licdn.com/dms/image/D5603AQHZy00zzEXLpw/profile-displayphoto-shrink_800_800/0/1696914036130?e=1706745600&v=beta&t=z6VWv5M84ITmdjL6UMba3ekyveEqnQzaCcTVhln2tZU" align="left" style="margin-right: 32px; margin-bottom: 16px;" width=160px height=159px >
</p>
<h4> Bio </h4>
<p>Peerat Limkonchotiwat is a Ph.D. student in information science and technology (IST) at VIS-TEC, Thailand. He contributes to the WangchanX project, a Thai NLP group developing applications, that comprises Thai sentence embedding benchmarks, Thai text processing datasets (VISTEC-TPTH-2021 and NNER-TH), and WangchanGLM and Wangchan-Sealion generative models.
</p>

<br><br><br><br>


<h3><strong></strong>Towards Explainable and Accessible AI</h3>
<h3> <a href="">Brandon Duderstadt</a> and <a href="">Yuvanesh Anand</a> </h3>
<br>
Large language models (LLMs) have recently achieved human-level performance on a range of professional and academic benchmarks. Unfortunately, the explainability and accessibility of these models has lagged behind their performance. State-of-the-art LLMs require costly infrastructure, are only accessible via rate-limited, geo-locked, and censored web interfaces, and lack publicly available code and technical reports. Moreover, the lack of tooling for understanding the massive datasets used to train and produced by LLMs presents a critical challenge for explainability research. This talk will be an overview of Nomic AI’s efforts to address these challenges through its two core initiatives: <i><a href="https://gpt4all.io/index.html">GPT4All</a></i>i> and Atlas.
<br><br>
<p>
<img src="https://media.licdn.com/dms/image/D4D03AQHyR6H00mNdEw/profile-displayphoto-shrink_800_800/0/1701199312557?e=1706745600&v=beta&t=EsvRjv7WhTuzYpGCjX4mlkJmG3jtNnSI6T3UUZJJqEc" align="left" style="margin-right: 32px; margin-bottom: 16px;" width=140px height=159px >
</p>
<h4> Bio </h4>
<p>Brandon Duderstadt is the founder and CEO of Nomic AI, a startup whose mission is to improve the explainability and accessibility of AI. His experiences at Rad AI and John Hopkins convinced him of both the profound impact that this new wave of AI technology would have as well as the need to improve the explainability and accessibility of AI models.</p>
<br><br>
<p>
<img src="https://media.licdn.com/dms/image/D4E03AQFiEOmDyOcyWw/profile-displayphoto-shrink_800_800/0/1681391146445?e=1706745600&v=beta&t=Yx3fT6V6rwqiiNVEvo5tnsd2X3c2-ebPLsRffzf7ihs" align="left" style="margin-right: 32px; margin-bottom: 16px;" width=140px height=159px >
</p>
<h4> Bio </h4>
<p>Yuvanesh Anand is a freshman computer science student at the Virginia Institute of Technology with broad interests in natural language processing and open-source software development. While still in high school, Yuvanesh joined Nomic AI as a software engineering intern, where he led the data collection and early development of the GPT4All project. </p>

<br><br><br><br>

## Workshop Program

The timezone for the program schedule below are in **Singapore Time (GMT +8)**.

<p>09:00 - 09:15 &nbsp;&nbsp; <strong> Opening Remarks </strong> </p>
<p>09:15 - 10:15 &nbsp;&nbsp; <strong> Invited Talk  - trlX: A Framework for Large Scale Open Source RLHF </strong><br>
<em>Louis Castricato</em></p>
<p>10:30 - 11:00 &nbsp;&nbsp; <strong> Coffee Break </strong> </p>

<p>11:00 - 11:30 &nbsp;&nbsp; <strong> Lightning Session 1 </strong> </p>
<p>11:30 - 12:15 &nbsp;&nbsp; <strong> Poster Session 1 </strong> </p>

<p>An Open-source Web-based Application for Development of Resources and Technologies in Underresourced Languages<br>
<em>Siddharth Singh, Shyam Ratan, Neerav Mathur and Ritesh Kumar</em></p>

<p>AWARE-TEXT: An Android Package for Mobile Phone Based Text Collection and On-Device Processing<br>
<em>Salvatore Giorgi, Garrick Sherman, Douglas Bellew, Sharath Chandra Guntuku, Lyle Ungar and Brenda Curtis </em></p>

<p>Beyond the Repo: A Case Study on Open Source Integration with GECToR<br>
<em>Sanjna Kashyap, Zhaoyang Xie, Kenneth Steimel and Nitin Madnani</em></p>

<p>calamanCy: A Tagalog Natural Language Processing Toolkit<br>
<em>Lester James Validad Miranda</em></p>

<p>Deepparse: A State-Of-The-Art Library for Parsing Multinational Street Addresses<br>
<em>David Beauchemin</em></p>

<p>EDGAR-CRAWLER: Finding Needles in the Haystack of Financial Documents<br>
<em>Lefteris Loukas, Manos Fergadiotis and Prodromos Malakasiotis</em></p>

<p>Jina Embeddings: A Novel Set of High-Performance Sentence Embedding Models<br>
<em>Michael Günther, Georgios Mastrapas, Bo Wang, Han Xiao and Jonathan Geuter</em></p>

<p>Kani: A Lightweight and Highly Hackable Framework for Language Model Applications<br>
<em>Andrew Zhu, Liam Dugan, Alyssa Hwang and Chris Callison-Burch</em></p>

<p>nanoT5: Fast & Simple Pre-training and Fine-tuning of T5 Models with Limited Resources<br>
<em>Piotr Nawrot</em></p>

<p>PyThaiNLP: Thai Natural Language Processing in Python<br>
<em>Wannaphong Phatthiyaphaibun, Korakot Chaovavanich, Charin Polpanumas, Arthit Suriyawongkul, Lalita Lowphansirikul, Pattarawat Chormai, Peerat Limkonchotiwat, Thanathip Suntorntip and Can Udomcharoenchaikit</em></p>

<p>Rumour Detection in the Wild: A Browser Extension for Twitter<br>
<em>Andrej Jovanovic and Björn Ross</em></p>

<p>SOTASTREAM: A Streaming Approach to Machine Translation Training<br>
<em>Matt Post, Thamme Gowda, Roman Grundkiewicz, Huda Khayrallah, Rohit Jain and Marcin Junczys-Dowmunt</em></p>

<p>Zelda Rose: a tool for hassle-free training of transformer models<br>
<em>Loïc Grobol</em></p>

<p>12:15 - 13:45 &nbsp;&nbsp; <strong> Lunch Break </strong> </p>
<p>13:45 - 14:45 &nbsp;&nbsp; <strong> Invited Talk - SEA-LION (Southeast Asian Languages In One Network): A Family of Southeast Asian Language Models </strong> <br>
<em>David Ong and Peerat Limkonchotiwat</em></p>

<p>14:45 - 15:15 &nbsp;&nbsp; <strong> Lightning Session 2 </strong> </p>
<p>15:15 - 15:30 &nbsp;&nbsp; <strong> Coffee Break </strong> </p> 
<p>15:30 - 16:15 &nbsp;&nbsp; <strong> Poster Session 2 </strong> </p>

<p>Antarlekhaka: A Comprehensive Tool for Multi-task Natural Language Annotation<br>
<em>Hrishikesh Terdalkar and Arnab Bhattacharya</em></p>

<p>DeepZensols: A Deep Learning Natural Language Processing Framework for Experimentation and Reproducibility<br>
<em>Paul Landes, Barbara Di Eugenio and Cornelia Caragea</em></p>

<p>GPT4All: An Ecosystem of Open Source Compressed Language Models<br>
<em>Yuvanesh Anand, Zach Nussbaum, Adam Treat, Aaron Miller, Richard Guo, Benjamin M Schmidt, Brandon Duderstadt and Andriy Mulyar</em></p>

<p>GPTCache: An Open-Source Semantic Cache for LLM Applications Enabling Faster Answers and Cost Savings<br>
<em>Fu Bang</em></p>

<p>Improving NER Research Workflows with SeqScore<br>
<em>Constantine Lignos, Maya Kruse and Andrew Rueda</em></p>

<p>LaTeX Rainbow: Open Source Document Layout Semantic Annotation Framework from LaTeX to PDF<br>
<em>Changxu Duan and Sabine Bartsch</em></p>

<p>nerblackbox: A High-level Library for Named Entity Recognition in Python<br>
<em>Felix Stollenwerk</em></p>

<p>News Signals: An NLP Library for Text and Time Series<br>
<em>Chris Hokamp, Demian Gholipour Ghalandari and Parsa Ghaffari</em></p>

<p>PyTAIL: An Open Source Tool for Interactive and Incremental Learning of NLP Models with Human in the Loop for Online Data<br>
<em>Shubhanshu Mishra, Jana Diesner</em></p>

<p>The Vault: A Comprehensive Multilingual Dataset for Advancing Code Understanding and Generation<br>
<em>Dung Nguyen Manh, Nam Le Hai, Anh T. V. Dau, Anh Minh Nguyen, Khanh Nghiem, Jin Guo and Nghi D. Q. Bui</em></p>

<p>Two Decades of the ACL Anthology: Development, Impact, and Open Challenges<br>
<em>Marcel Bollmann, Nathan Schneider, Arne Ko ̈hn and Matt Post</em></p>

<p>torchdistill Meets Hugging Face Libraries for Reproducible, Coding-free Deep Learning Studies: A Case Study on NLP<br>
<em>Yoshitomo Matsubara</em></p>

<p>Using Captum to Explain Generative Language Models<br>
<em>Vivek Miglani, Aobo Yang, Aram H. Markosyan, Diego Garcia-Olano and Narine Kokhlikyan</em></p>

<p>16:15 - 17:15 &nbsp;&nbsp; <strong> Invited Talk - Towards Explainable and Accessible AI </strong><br>
<em>Brandon Duderstadt and Yuvanesh Anand</em></p>

<p>17:15 - 17:30 &nbsp;&nbsp; <strong> Closing Remarks</strong></p>

<strong>Note:</strong> Please to <a href="">Hybrid In-Person & Virtual Workshop Format"</a> section for instructions on how to access the both in-person and virtual workshop content.


## Organizers

 - [Geeticka Chauhan](https://www.csail.mit.edu/person/geeticka-chauhan), Massachusetts Institute of Technology
 - [Dmitrijs Milajevs](http://zest.id.lv/), Grayscale AI
 - [Elijah Rippeth](https://erip.github.io/), University of Maryland
 - [Jeremy Gwinnup](https://www.linkedin.com/in/jgwinnup), Air Force Research Laboratory
 - [Liling Tan](http://alvations.com/), Amazon

## Programme Committee

 - Aakanksha Naik, Allen Institute for Artificial Intelligence
 - Abhinav Arora, Meta AI
 - Aitor Soroa, HiTZ Center, University of the Basque Country UPV/EHU
 - Akintunde Oladipo, University of Waterloo
 - Alexander Rush, Cornell / Hugging Face
 - Aline Paes, Universidade Federal Fluminense
 - Amittai Axelrod, Apple AI
 - Anish Mohan, NVIDIA
 - Arun Balajiee Lekshmi Narayanan, University of Pittsburgh
 - Atnafu Lambebo Tonja, University of Colorado
 - Atul Kr. Ojha, University of Galway
 - Cassandra Jacobs, University at Buffalo
 - Christoph Teichmann, Bloomberg L.P.
 - Daniel Braun, University of Twente
 - David M. Howcroft, Edinburgh Napier University
 - Fabio Kepler, Unbabel
 - Flammie a Pirinen, UiT The Arctic University of Norway
 - Francis Bond, Palacký University Olomouc
 - Gérard Dupont, Mavenoid
 - Guillaume Becquin, Bloomberg L.P.
 - Ignatius Ezeani, Lancaster University
 - Jana Götze, University of Potsdam
 - Jack Morris, Cornell University
 - John X. Morris, Cornell University
 - Jörg Tiedemann, University of Helsinki
 - Kamile Lukosiute, Anthropic
 - Karin Sim, Language Weaver
 - Kevin Cohen, University of Colorado
 - Lane Schwartz, University of Alaska Fairbanks
 - Leo Boytsov, Amazon
 - Lucy Park, Upstage
 - Maarten van Gompel, Radboud University
 - Maheshwar Ghankot, Indian Space Research Organization
 - Mallika Singh, Boston Children's Hospital - Harvard Medical School
 - Marcel Bollmann, Linköping University
 - Marco Cognetta, Tokyo Institute of Technology, Google
 - Marzieh Fadaee, Cohere for AI
 - Matt Post, Microsoft
 - Micah Shlain, Allen Institute for Artificial Intelligence
 - Michael Wayne Goodman, LivePerson Inc.
 - Mohd Sanad Zaki Rizvi, University of Edinburgh
 - Nelson F. Liu, Stanford University
 - Nitin Madnani, Educational Testing Service
 - Ogundepo Odunayo, University of Waterloo
 - Pasquale Lisena, EURECOM
 - Philipp Koehn, Johns Hopkins University
 - Phu Mon Htut, AWS AI Labs
 - Raeid Saqur, Princeton University
 - Raphael Tang, Comcast
 - Sagnik Ray Choudhury, University of Michigan
 - Shilpa Suresh, Boston Children's Hospital - Harvard Medical School
 - Shubhanshu Mishra, Shubhanshu.com
 - Sina Ahmadi, George Mason University
 - Steve DeNeefe, Language Weaver - RWS Group
 - Steven Bethard, University of Arizona
 - Sudhakar Singh, NVIDIA
 - Taha Zerrouki, Bouira University Algeria
 - Tenzin Singhay Bhotia, Georgia Institute of Technology
 - Thomas Kober, Zalando
 - Tomas Mikolov, Czech Institute of Informatics
 - Tommaso Teofili, Roma Tre University
 - Vijay Murari Tiyyala, Johns Hopkins University
 - Vlad Niculae, University of Amsterdam
 - Won Ik Cho, Samsung Advanced Institute of Technology
 - Zaid Alyafeai, King Fahad University of Petroleum and Minerals
 - Ziv Litmanovitz, University of Haifa


## Previous Workshops

[**Second Workshop for Natural Language Processing Open Source Software** (NLP-OSS 2020)](../2020) <br>
\[[Proceedings](https://aclanthology.org/volumes/2020.nlposs-1/)\]

[**First Workshop for Natural Language Processing Open Source Software** (NLP-OSS 2018)](../2018) <br>
\[[Proceedings](https://www.aclweb.org/anthology/volumes/W18-25/)\]


## Hybrid In-Person & Virtual Workshop Format

The most <strong>up-to-date and canonical schedule for the workshop</strong> will be https://nlposs.github.io/2023/index.html#workshop-program All sessions will listed at in Singapore (GMT +8) time. 

To access the <strong>virtual conference</strong>, 

 - Attendees should have at least one author signed up on the EMNLP registration https://2023.emnlp.org/registration/
 - The main page to access the virtual conference is https://virtual2023.emnlp.org/
 - The main page to access the content of the NLP-OSS workshop is https://underline.io/events/431/sessions?searchGroup=lecture&eventSessionId=16447


During the workshop, <strong>all live in-person sessions will be streamed</strong> through the zoom link on https://underline.io/events/431/sessions?searchGroup=lecture&eventSessionId=16447 (through the “Join Live Session” button).

Live sessions includes (i) opening and closing remarks, (ii) invited talks (presenter will be in person but streamed live), and (iii) lightning sessions. To keep our schedule on-time, we’ll try keep a strict max 5 mins to the lightning sessions.

Then during the <strong>poster sessions</strong>, 

 - In-person presenters will proceed to the poster boards assigned by the workshop organisers.
 - Virtual presenters will login to their individual channels in https://underline.io/events/431/sessions?searchGroup=lecture&eventSessionId=16447 and interact through chat our video call (we are seeing that the video call option on underline.io isn’t working yet, we’ll reconfirm with the conference admin asap)


Thank you everyone again for the various procedures considerations taken to make sure that both in-person and virtual attendees get the most of our the workshop. This is our first time organising a mix-hybrid mode workshop, we ask for your understanding for any inconvenience caused.
