---
layout: default
title: Journées 2020
---

La journée 2020 du [groupe de travail Vélocité Logicielle](https://gdrgpl.myxwiki.org/xwiki/bin/view/Main/GTs/GT%20Rimel/) se tiendra le **mercredi 16 décembre** en visioconférence.

### Informations pratiques

La visioconférence utilise l'outil BigBlueButton (BBB). La connexion se fait via le lien suivant :

**[https://webconf.u-bordeaux.fr/b/tho-mkk-k4p](https://webconf.u-bordeaux.fr/b/tho-mkk-k4p)**

*En cas de problème*, nous utiliserons la réunion Zoom suivante :

[https://univ-rennes1-fr.zoom.us/j/95149843716](https://univ-rennes1-fr.zoom.us/j/95149843716)\
ID de réunion : 951 4984 3716\
Code secret : 300173

### Programme de la journée

Les exposés et questions sont de préférence en français, ou en anglais si l'orateur·rice le souhaite. Chaque exposé dure 20 minutes + 10 minutes de questions.

**09:30-9:45** Accueil et introduction -- *Djamel E. Khelladi, Thomas Degueule*

**09:45-10:15** Architecture autocicatrisante à base de microservices avec la gestion de versions -- *Yuwei Wang*\
**10:15-10:45** About Adversarial Configurations for SPLs -- *Paul Temple*

**10:45-11:00** Pause

**11:00-11:30** A Tree-Matching Algorithm to Compare Webpages -- *Sacha Brisset*\
**11:30-12:00** Asset-Oriented Threat Modeling -- *Nan Messe*

**12:00-14:00** Pause  Repas

**14:00-14:30** Bug Identification Among Issue-Tracking Systems: a Preliminary Study -- *Quentin Perez*\
**14:30-15:00** VaryMinions: Leveraging RNNs to Learn Variability in Business Processes -- *Sophie Fortz*

**15:00-15:15** Pause

**15:15-15:45** Identification automatique d'implémentations de variabilité orientée objet -- *Johann Mortara*\
**15:45-16:15** Improving Practices in a Small French Company: First Step -- *Honore Houekpetodji*

**16:15-16:30** Discussions et conclusion -- *Djamel E. Khelladi, Thomas Degueule*

### Résumés

**Architecture autocicatrisante à base de microservices avec la gestion de versions**
There is a migration from monolithic architectures to microservices architectures. One of the benefits of microservices is their independent deployment and evolution driven by different development and operations teams.  However, not all the microservices will be evolving and upgraded at the same rate. Every microservice can change at any time or even in a way breaking the system. This is where microservices versioning for evolution becomes more important but more complex in microservices architectures. A PhD project has been launched to propose a self-healing microservices architecture for versioning problem. In our work, we firstly present the first results of the state of the art
for microservices versioning: we propose a taxonomy framework for microservices versioning based on the "Five Ws and How" method. We use this taxonomy to analyse and compare the current research and industry work. Then, we identify challengesand some special attentions for future work on microservices versioning. The current work ongoing is to
propose a first prototype to automatize the versioning processus during deployment and execution of microservices.

**About Adversarial Configurations for SPLs**
Software product line (SPL) engineering allows the derivation of products tailored to stakeholders’ needs through the setting of a large number of configuration options. Unfortunately, options and their interactions create a huge configuration space which is either intractable or too costly to explore exhaustively. Instead of covering all products, machine learning (ML) approximates the set of acceptable products out of a training set . But ML techniques can make prediction errors. We apply adversarial machine learning to the world of SPLs to craft new configurations fakling to be acceptable while being not and vice-versa. It allows to diagnose prediction errors and take appropriate actions.

**A Tree-Matching Algorithm to Compare Webpages**
Tree matching techniques have been investigated in many fields, including web data mining and extraction, as a key component to analyze the content of web pages. However, when applied to existing web pages, traditional tree matching approaches, covered by algorithms likeTree-Edit Distance(TED) or XyDiff, either fail to scale beyond a few hundreds nodes or exhibit a relatively low accuracy. In this paper, we therefore propose a novel algorithm, named Similarity-based Flexible Tree Matching (SFTM), which enables high accuracy tree matching on real-life web pages, with practical computation times. Interestingly, we approach tree matching as an optimisation problem and we leverage node labels and local topology similarity in order to avoid any combinatorial explosion. Our practical evaluation demonstrates that SFTM significantly improves the state of the art in terms of accuracy, while allowing computation times significantly lower than the most accurate solutions. By gaining on these two dimensions, SFTM therefore offers an affordable solution to match complex trees in practice.

**Asset-Oriented Threat Modeling**
Threat modeling is recognized as one of the most important activities in software security. It helps to address security issues in software development. Several threat modeling processes are widely used in the industry such as the one of Microsoft SDL. In threat modeling, it is essential to first identify assets before enumerating threats, in order to diagnose the threat targets and spot the protection mechanisms. Asset identification and threat enumeration are collaborative activities involving many actors such as security experts and software architects. These activities are traditionally carried out in brainstorming sessions. Due to the lack of guidance, the lack of a sufficiently formalized process, the high dependence on actors’ knowledge, and the variety of actors’ background, these actors often have difficulties collaborating with each other. Brainstorming sessions are thus often conducted sub-optimally and require significant effort. To address this problem, we aim at structuring the asset identification phase by proposing a systematic asset identification process, which is based on a reference model. This process structures and identifies relevant assets, facilitating the threat enumeration during brainstorming. We illustrate the proposed process with a case study and show the usefulness of our process in supporting threat enumeration and improving existing threat modeling processes such as the Microsoft SDL one.

**Bug Identification Among Issue-Tracking Systems: a Preliminary Study**
During software development, maintenance activities represent an important part of the life cycle. Development teams often use Issue-Tracking Systems (ITSs) like Jira or Bugzilla to manage maintenance and development activities. These tools manage backlogs of issues to be solved to develop or maintain software. Software maintenance and development cover a wide range of activities (bug fixing, new feature development, architecture refactoring...) and each of these can be the subject of issue. However few means are proposed to identify and classify automatically these different kinds of issues, except for non mandatory labels that can be manually associated to them. This may lead to a lack of issue classification or to issue misclassification leading to a drift in software metrics or in project management (planning, assignment, financial costs). Therefore, automated solutions are needed to help developers classify issues correctly. Basic solutions like textual pattern matching are not accurate due to the free natural language used in issues: detecting buzzwords (e.g., “bug”) is not enough to obtain an efficient classifier. Designing a robust classifier requires both natural language processing and machine learning techniques. This presentation proposes a binary classification solution that separates bug and non-bug related issues. This solution is a combination of natural language processing (TF-IDF) and classification (multi-layer perceptron) methods. A fine tuning optimization is performed on classifier hyper-parameters thanks to a genetic algorithm. The obtained results are compared to state of the art using benchmarks. They show significant improvements on the F1-measure for all datasets. A demonstration of a prototype bug issue writer assistant using this work is also proposed during the presentation.

**VaryMinions: Leveraging RNNs to Learn Variability in Business Processes**
Software reuse imposed itself as a development paradigm, allowing to tailor software applications to customer needs through the configuration of some options. Similarly, configurable business processes offer the possibility to model variability (e.g., different patient routes in a hospital depending on their disease) in a single model. However, reuse is often opportunistic: traceability between behaviour and variability is barely present from the onset. In this paper, we assess the ability of Recurrent Neural Networks (RNNs) to correctly map each trace to its corresponding process variant. In particular, we trained Long Short Term Memory (LSTMs) and Gated Recurrent Units (GRUs) on two datasets respectively modelling configurable municipality and travel expenses workflows. While we achieve high accuracy on these datasets (> 87%), we explain the challenges of learning more entangled variants and provide perspectives linked to hyper-parameter variability and labelling of variants.

**Identification automatique d'implémentations de variabilité orientée objet**
Une majorité de grands systèmes logiciels sont naturellement variables et utilisent plusieurs mécanismes pour implémenter cette variabilité. Ces systèmes n’étant pour la plupart pas structurés comme des lignes de produits logiciels, assurer leur maintenabilité implique de pouvoir identifier ces implémentations de variabilité dans le code pour ensuite les relier aux fonctionnalités du domaine. Dans le cas de systèmes orientés objets, cette variabilité est souvent gérée au sein d’une unique
base de code et implémentée à l’aide des mécanismes objets (héritage, surcharge de constructeurs et de méthodes, patrons de conception). Ces mécanismes étant identiques à ceux permettant d’implémenter les fonctionnalités du système, l’identification de la variabilité est complexe. Nous proposons donc une approche qui permet d’identifier automatiquement les implémentations de variabilité présentes dans une unique base de code écrite en s’appuyant sur la notion de symétrie dans les mécanismes orientés objets et sur l’hypothèse que la densité de ces symétries représente des zones d’implémentation de la variabilité. Les potentiels points de variation et variantes ainsi identifiés peuvent ensuite être automatiquement reliés à des fonctionnalités du domaine lorsqu’elles sont disponibles, et sont représentés visuellement sous la forme d’un graphe permettant une identification des zones denses en variabilité. L’approche est outillée par une chaı̂ne d’extraction et de visualisation pour les langages Java et C++, symfinder , qui a été appliquée à plusieurs grands projets open source.

**Improving Practices in a Small French Company: First Step**
Legacy systems are old software that still does useful tasks. In industrial software companies, legacy systems are often crucial for the company business model and represent a long-term business investment. Legacy systems are known to be hard to maintain. This is the case in a french company whose main product is twenty years old software written in PowerBuilder. Our long-term goal is to help it re-engineer this system. But how to validate our intervention? Little data is available on the system and specifically, past versions of the source code are not easy to recover. This constrained us on the metrics we could use. In this paper, we present a lightweight model to characterize the situation of the system and allow us to monitor it in the future.
