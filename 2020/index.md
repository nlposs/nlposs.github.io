---
title: NLP-OSS 2020
layout: default
---

# 2nd Workshop for Natural Language Processing Open Source Software (NLP-OSS) <br>

### 19 Nov 2020 @ [EMNLP 2020](https://2020.emnlp.org/) (Virtual Workshop)

<br><br>

With great scientific breakthrough comes solid engineering and open communities. The Natural Language Processing (NLP) community has benefited greatly from the open culture in sharing knowledge, data, and software. The primary objective of this workshop is to further the sharing of insights on the engineering and community aspects of creating, developing, and maintaining NLP open source software (OSS), which we seldom talk about in scientific publications. Our secondary goal is to promote synergies between different open source projects and encourage cross-software collaborations and comparisons.

We refer to Natural Language Processing OSS as an umbrella term that not only covers traditional syntactic, semantic, phonetic, and pragmatic applications; we extend the definition to include task-specific applications (e.g., machine translation, information retrieval, question-answering systems), low-level string processing that contains valid linguistic information (e.g. Unicode creation for new languages, language-based character set definitions) and machine learning/artificial intelligence frameworks with functionalities focusing on text applications.

In the earlier days of NLP, linguistic software was often monolithic and the learning curve to install, use, and extend the tools was steep and frustrating. More often than not, NLP OSS developers/users interact in siloed communities within the ecologies of their respective projects. In addition to the engineering aspects of NLP software, the open source movement has brought a community aspect that we often overlook in building impactful NLP technologies.

An example of precious OSS knowledge comes from SpaCy developer [Montani (2017)](https://ines.io/blog/spacy-commercial-open-source-nlp), who shared her thoughts and challenges of maintaining commercial NLP-OSS, such as handling open issues on the issue tracker, model release and packaging strategy and monetizing NLP OSS for sustainability.

More recently, the [Transformers library](https://github.com/huggingface/transformers) created by Hugging Face, has gathered much interest from the community by open sourcing implementations to use pretrained weights of BERT-like models, in a clean and well-organized structure. The interoperability of various pretrained models trained with different tools in one library enables quick benchmarking across the models, as well as developing best practices for reading/saving serialized interoperable models.

We hope that the NLP-OSS workshop becomes the intellectual forum to collate various open source knowledge beyond the scientific contribution, announce new software/features, promote the open source culture and best practices that go beyond the conferences.

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

 - **Scientific Contribution**
   - Surveying OSS for specific NLP task(s)
   - Demonstration, introductions and/or tutorial of NLP-OSS
   - Small but useful NLP-OSS
   - NLP components in ML OSS
   - Citations and references for NLP-OSS
   - OSS and experiment replicability
   - Gaps between existing NLP-OSS
   - Task-generic vs task-specific software


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

Due to the nature of open source software, we find it a bit tricky to "anonymize" "open source". For this reason, we don't require your publication to be anonymous. However, if you prefer your paper to be anonymized, please mask any identifiable phrase with REDACTED. We have an option setup in softconf so that you can explicitly opt-in / opt-out of anonymity. 

Submission should be formatted according to the EMNLP 2020 LaTeX or MS Word templates at [https://2020.emnlp.org/files/emnlp2020-templates.zip](https://2020.emnlp.org/files/emnlp2020-templates.zip).

Submissions should be uploaded to Softconf conference management system at [https://www.softconf.com/emnlp2020/nlposs/](https://www.softconf.com/emnlp2020/nlposs/).

**Note:** Paper can be [dual-submitted](https://2020.emnlp.org/call-for-papers) to both EMNLP 2020 and the NLP-OSS workshop.

## Important dates

The 2nd NLP-OSS workshop will be co-located with the EMNLP 2020 conference.

- Paper submission: ~~05 August 2020~~ 19 August 2020
- Paper Reviews Starts: ~~07 August 2020~~ 20 August 2020
- Paper Reviews Due: ~~07 September 2020~~ 20 September 2020
- Notification of Acceptance: ~~10 September 2020~~ ~~22 September 2020~~ **25 September 2020**
- Camera-Ready Version: ~~05 October 2020~~ ~~10 October 2020~~ **09 Oct 2020**
- Workshop: 19 November 2020

## Invited Speakers
<br><br>

<h3><strong>Principles of Good Machine Learning Systems Design</strong> </h3>
<h3> <a href="https://huyenchip.com">Chip Huyen</a>, Snorkel AI / Stanford University </h3>
<br>
This talk covers what it means to operationalize Machine Learning (ML) models. It starts by analyzing the difference between ML in research vs. in production, ML systems vs. traditional software, as well as myths about ML production. It then goes over the principles of good ML systems design and introduces an iterative framework for ML systems design, from scoping the project, data management, model development, deployment, maintenance, to business analysis. It covers the differences between DataOps, ML Engineering, MLOps, and data science, and where each fits into the framework. The talk ends with a survey of the ML production ecosystem, the economics of open source, and open-core businesses.
<br><br>
<p>
<img src="https://huyenchip.com/assets/profile.jpg" alt="Chip Huyen" align="left" style="margin-right: 32px; margin-bottom: 16px;" width=160px height=159px >
</p>
<h4> Bio </h4>
<p>Chip Huyen is an engineer who develops tools and best practices for machine learning production. She’s currently with Snorkel AI and she’ll be teaching Machine
Learning Systems Design at Stanford. Previously, she was with Netflix, NVIDIA, Primer. She’s also the author of four bestselling Vietnamese books.</p>
<br><br><br><br>

<h3><strong>On Typing: Historical and Potential Interactions in Word-processing</strong> </h3>
<h3> <a href="https://spencermounta.in/">Spencer Kelly</a>, Freelance Developer </h3>
<br>
People love typing, in a surprising and universal way. In this talk we look at the development of word-processing, and the design-decisions in this historic interface. Can NLP contribute to word-processing, without making it worse? What would a text-centered computer really look like? We look at the history of punctuation, keyboards, and markup languages. We look at Wikipedia, text-editors, and data structures - with the goal of authoring usable data in text.
<br><br>
<p>
<img src="https://avatars2.githubusercontent.com/u/399657?s=460&u=afb7798f372f34b144511ebfd0895ccfef8c9536&v=4" alt="Spencer Kelly<" align="left" style="margin-right: 32px; margin-bottom: 16px;" width=160px height=159px >
</p>
<h4> Bio </h4>
<p>Spencer Kelly is the author of <i><a href="http://compromise.cool/">compromise</a></i>, - a small natural language processing library for the browser. He is a web developer, and maintainer of open-source libraries. His background is in the semantic web and Wikipedia. Today his work focuses on creating infographics. His open-source work is funded by freelance web development. He is from Toronto, Canada.</p>
<br><br><br><br>

<h3><strong>An Introduction to Transfer Learning in NLP and HuggingFace</strong> </h3>
<h3> <a href="https://thomwolf.io/">Thomas Wolf</a>,  Huggingface</h3>
<br>
In this talk I’ll start by introducing the recent breakthroughs in NLP that resulted from the combination of Transfer Learning schemes and Transformer architectures. The second part of the talk will be dedicated to an introduction of the open-source tools released by HuggingFace, in particular our Transformers, Tokenizers and Datasets libraries and our models.
<br><br>
<p>
<img src="https://thomwolf.io/images/Thom_photo_circle.jpg" alt="Thomas Wolf<" align="left" style="margin-right: 32px; margin-bottom: 16px;" width=160px height=159px >
</p>
<h4> Bio </h4>
<p>Thomas Wolf is co-founder and Chief Science Officer of HuggingFace. His team is on a mission to catalyze and democratize NLP research. Prior to HuggingFace, Thomas gained a Ph.D. in physics, and later a law degree. He worked as a physics researcher and a European Patent Attorney.
</p>
<br><br><br><br>

## Workshop Program
<br><br>

The timezone for the program schedule below are in **Pacific Time (Los Angeles)**. 

<p>0500 - 0530	&nbsp;&nbsp; <strong>Opening Remarks</strong> [Click here for Zoom](https://mit.zoom.us/j/96463506487) </p> 

<p>0530 - 0630	&nbsp;&nbsp; <strong>Invited Talk 1: Spencer Kelly</strong> [Click here for Zoom](https://mit.zoom.us/j/96463506487)</p> 

<p>0630 - 0730 &nbsp;&nbsp; <strong>Invited Talk 2: Thomas Wolf</strong> [Click here for Zoom](https://mit.zoom.us/j/96463506487)</p> 

<p>0730 - 0900 &nbsp;&nbsp; <strong>Talks Session 1 </strong> (Watch on your own, authors encouraged to mend their slidelive chat but not complusory)</p>

<p>A Framework to Assist Chat Operators of Mental Healthcare Services <br>
<em>Thiago Madeira, Heder Bernardino, Jairo Francisco De Souza, Henrique Gomide, Nathália Munck Machado, Bruno Marcos Pinheiro da Silva and Alexandre Vieira Pereira Pacelli</em></p>

<p>ARBML: Democritizing Arabic Natural Language Processing Tools <br>
<em>Zaid Alyafeai and Maged Al-Shaibani </em></p>

<p>CLEVR Parser: A Graph Parser Library for Geometric Learning on Language Grounded Image Scenes <br>
<em>Raeid Saqur and Ameet Deshpande </em></p>

<p>End-to-end NLP Pipelines in Rust <br>
<em>Guillaume Becquin</em></p>

<p>Fair Embedding Engine: A Library for Analyzing and Mitigating Gender Bias in Word Embeddings <br>
<em>Vaibhav Kumar, Tenzin Bhotia and Vaibhav Kumar</em></p>

<p>Flexible retrieval with NMSLIB and FlexNeuART <br>
<em>Leonid Boytsov and Eric Nyberg</em></p>

<p>fugashi, a Tool for Tokenizing Japanese in Python <br>
<em>Paul McCann</em></p>

<p>Going Beyond T-SNE: Exposing whatlies in Text Embeddings <br>
<em>Vincent Warmerdam, Thomas Kober and Rachael Tatman</em></p>

<p>Howl: A Deployed, Open-Source Wake Word Detection System <br>
<em>Raphael Tang, Jaejun Lee, Afsaneh Razi, Julia Cambre, Ian Bicking, Jofish Kaye and Jimmy Lin</em></p>

<p>iNLTK: Natural Language Toolkit for Indic Languages <br>
<em>Gaurav Arora</em></p>

<p>0900 - 1430 &nbsp;&nbsp; <strong>Long Break</strong></p>

<p>1430 - 1600 &nbsp;&nbsp; <strong>Talks Session 2 </strong> (Watch on your own, authors encouraged to mend their slidelive chat but not complusory)</p>

<p>iobes: A Library for Span-Level Processing<br>
<em>Brian Lester</em></p>

<p>jiant: A Software Toolkit for Research on General-Purpose Text Understanding Models <br>
<em>Yada Pruksachatkun, Phil Yeres, Haokun Liu, Jason Phang, Phu Mon Htut, Alex Wang, Ian Tenney and Samuel R. Bowman </em></p>

<p>KLPT -- Kurdish Language Processing Toolkit <br>
<em>Sina Ahmadi</em></p>

<p>Open Korean Corpora: A Practical Report <br>
<em>Won Ik Cho, Sangwhan Moon and Youngsook Song</em></p>

<p>Open-Source Morphology for Endangered Mordvinic Languages <br>
<em>Jack Rueter, Mika Hämäläinen and Niko Partanen</em></p>

<p>Pimlico: A toolkit for corpus-processing pipelines and reproducible experiments <br>
<em>Mark Granroth-Wilding </em></p>

<p>PySBD: Pragmatic Sentence Boundary Disambiguation <br>
<em>Nipun Sadvilkar and Mark Neumann </em></p>

<p>SacreROUGE: An Open-Source Library for Using and Developing Summarization Evaluation Metrics	<br>
<em>Daniel Deutsch and Dan Roth</em></p>

<p>TextAttack: Lessons learned in designing Python frameworks for NLP <br>
<em>John Morris, Jin Yong Yoo and Yanjun Qi</em></p>

<p>TOMODAPI: A Topic Modeling API to Train, Use and Compare Topic Models <br>
<em>Pasquale Lisena, Ismail Harrando, Oussama Kandakji and Raphael Troncy</em></p>

<p>User-centered & Robust NLP OSS: Lessons Learned from Developing & Maintaining RSMTool <br>
<em>Nitin Madnani and Anastassia Loukina</em></p>

<p>WAFFLE: A Graph for WordNet Applied to FreeForm Linguistic Exploration <br>
<em>Berk Ekmekci and Blake Howald</em></p>

<p>1600 - 1730 &nbsp;&nbsp; <strong>Gather-town (Live) + Poster QnA</strong></p>

<p>1730 - 1800 &nbsp;&nbsp; <strong>Short Break</strong></p>

<p>1800 - 1900 &nbsp;&nbsp; <strong>Invited Talk: Chip Huyen</strong> [Click here for Zoom](https://mit.zoom.us/j/97792084996)</p> 

<p>1900 - 1930	&nbsp;&nbsp; <strong>Closing Remarks</strong> [Click here for Zoom](https://mit.zoom.us/j/97792084996)</p> 

<br><br>
To check out the events in your own time zone, we find that it's easiest to click on each of the item on the agenda and add them to your Google calendar.

<iframe src="https://calendar.google.com/calendar/embed?height=600&amp;wkst=1&amp;bgcolor=%233F51B5&amp;ctz=America%2FLos_Angeles&amp;src=N2ppbGF2c2dlNWMyb3RuOGZoczE1dWkyc29AZ3JvdXAuY2FsZW5kYXIuZ29vZ2xlLmNvbQ&amp;color=%23D81B60&amp;showNav=0&amp;showDate=0&amp;showCalendars=1&amp;showTabs=1&amp;showPrint=1&amp;showTitle=0&amp;showTz=1&amp;mode=AGENDA" style="border:solid 1px #777" width="800" height="600" frameborder="0" scrolling="no"></iframe>



## Organizers

 - [Lucy Park](https://github.com/e9t), Upstage

     Lucy is a NLP/ML engineer at [Upstage](https://upstage.ai). She has participated in some open source projects, particularly [KoNLPy](http://konlpy.org) which is a tool for Korean NLP, and is also interested in open data. She received her Ph.D. in Data Mining from Seoul National University in 2016, where she has pursued various studies on text mining in the fields of manufacturing, political science, and multimedia. After her studies, she joined NAVER, a South Korea based search-engine company and worked on machine translation.

 - [Masato Hagiwara](http://masatohagiwara.net/), Octanove Labs LLC

     Masato Hagiwara is an independent NLP/ML engineer and researcher at Octanove Labs. He received his Ph.D. degree in Information Science from Nagoya University in 2009. During his Ph.D., he worked at Google and Microsoft Research as an intern, and thereafter at Baidu Japan and Rakuten Institute of Technology, focusing on search engine-related language processing research. Most recently he was working as a Senior Machine Learning Engineer at Duolingo, focusing on educational applications of NLP. He received several paper awards from Japanese domestic conferences for his work on knowledge acquisition and transliteration. He also co-organized several workshops and shared tasks, including NLP-OSS 2018.

 - [Dmitrijs Milajevs](http://zest.id.lv/), KPMG LLP.

     Dmitrijs Milajevs is a data scientist at KMPG. Previously, he evaluated information retrieval systems at National Institute of Standards and Technology (NIST). He has defended a Ph.D. thesis on evaluation of compositional models in distributional semantics.

 - [Nelson Liu](https://cs.stanford.edu/~nfliu/),  Stanford University

     Nelson Liu is a computer science Ph.D. student at Stanford, where he works in the Stanford NLP Group. He has contributed to the AllenNLP, torchtext, and scikit-learn projects at various points in time.

 - [Geeticka Chauhan](https://www.csail.mit.edu/person/geeticka-chauhan), Massachusetts Institute of Technology

    Geeticka Chauhan is a Ph.D. student at MIT, working on NLP for healthcare advised by Prof. Peter Szolovits. Her master thesis focused on revealing the reproducibility and generalizability problems in Relation Extraction, and experimentally showed the importance of streamlining evaluation methods in NLP challenges.


 - [Liling Tan](https://github.com/alvations), Amazon

     Liling is a machine learning scientist at Amazon building machine translation and language technologies. Previously, he is a research scientist at Rakuten Institute of Technology and before that an early stage researcher at Saarland University. He has been actively involved in corpora creation/maintenance, Asian NLP and machine translation. He co-organized the [Workshop on NLP for Similar Languages, Varieties and Dialects (VarDial 2014-16)](http://ttg.uni-saarland.de/vardial2016/).


## Programme Committee

 - Aline Paes, Universidade Federal Fluminense
 - Amandalynne Paullada, University of Washington
 - Amittai Axelrod, DiDi Chuxing (Los Angeles)
 - Anca Dumitrache,	FD Mediagroep
 - Arwen Twinkle Griffioen, Zendesk Inc.
 - Carolina Scarton, University of Sheffield
 - Chris Hokamp, AYLIEN
 - Christian Federmann, Microsoft Research
 - Dan Simonson, BlackBoiler, LLC
 - Daniel Braun, TU Muchen
 - Dave Howcroft, Heriot-Watt University
 - David Przybilla, Idio
 - Delip Rao, AI Foundation
 - Denny Britz, Prediction Machines
 - Ehsan Khoddammohammadi, Elsiever
 - Eleftherios Avramidis,	German Research Center for Artificial Intelligence
 - Elijah Rippeth, MITRE Corporation
 - Emiel van Miltenburg,	Vrije Universiteit Amsterdam
 - Emily Dinan, Facebook AI
 - Eric Schles,	New York University / Sema4
 - Fabio Kepler, Unbabel
 - Francis Bond, Nanyang Technological University
 - Fred Blain, University of Sheffield
 - Gerard Dupont, Airbus
 - Ian Soboroff, NIST
 - Ignatius Ezeani, Lancaster Uni
 - Ines Montani, Explosion AI
 - James Bradbury, Google
 - Joel Nothman, University of Sydney
 - Karin Sim Smith, Lingo24
 - Kevin Cohen,	University of Colorado Boulder
 - KhengHui Yeo, Institute for Infocomm Research
 - Laura Martinus, Explore AI
 - Madison May,	Indico Data Solutions
 - Marcel Bollmann, University of Copenhagen
 - Marcos Zampieri, University of Wolverhampton
 - Mary Ellen Foster, University of Glasgow
 - Marzieh Fadaee, University of Amsterdam
 - Matthew Honnibal, Explosion AI
 - Micah Shlain, Allen Institute for Artificial Intelligence
 - Michael Wayne Goodman, Nanyang Technological University
 - Mohd Sanad Zaki Rizvi, Microsoft Research India
 - Moshe Wasserblat,	Intel
 - Muthu Kumar Chandrasekaran, NUS, SG
 - Nahid Alam, Ople Inc
 - Paul P Liang, Carnegie Mellon University
 - Philipp Koehn, Johns Hopkins University
 - Sandya Mannarswamy , Independent Researcher
 - Shamil Chollampatt, Rakuten Institute of Technology
 - Sharat Chikkerur, Microsoft
 - Shilpa Suresh, Singapore Managment University
 - Shubhanshu Mishra, Twitter
 - Steve DeNeefe, SDL Research Labs
 - Steve Sloto,	AWS AI
 - Steven Bethard, University of Arizona
 - Steven Bird, Charles Darwin University
 - Sung Kim, NAVER Corp.
 - Svitlana Vakulenko, University of Amsterdam
 - Tareq Al-Moslmi, University of Bergen
 - Thomas Kober, Rasa Technologies GmbH
 - Tilahun Abedissa, Addis Ababa University
 - Tommaso Teofili, Roma Tre University / Red Hat
 - Tommi A Pirinen, University of Hamburg
 - Varun Kumar, Amazon Alexa
 - Vlad Niculae, Instituto de Telecomunicações
 - Yves Peirsman, NLP Town

<!--
## Workshop Structure

To promote closer interaction, all accepted publications will be presented in the poster format and be required to give a 1 slide (90 seconds) introduction of their work at the beginning of the session. For the rest of the workshop, invited talks will be given by developers and maintainers of prominent NLP-OSS projects and we plan to close the workshop with a panel session with the invited speakers and the audience of the workshop.
-->


## Previous Workshop

[**First Workshop for Natural Language Processing Open Source Software** (NLP-OSS 2018)](../2018) <br>
\[[Proceedings](https://www.aclweb.org/anthology/volumes/W18-25/)\]
