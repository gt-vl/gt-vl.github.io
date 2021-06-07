---
layout: default
title: Journées GDR-GPL 2021
---

Le GT VL organise une session en parallèle des journées du GDR-GPL le **18 juin 2021** de 13h30 à 15h30.

## Inscription et connexion

## Programme

* 13:30--13:35<br>**Introduction**<br>*Djamel E. Khelladi, Thomas Degueule*
* 13:35--14:05<br>**An approach and benchmark to detect behavioral changes of commits in continuous integration** \\
*Benjamin Danglot*, Martin Monperrus, Walter Rudametkin, Benoit Baudry \\
When a developer pushes a change to an application’s codebase, a good practice is to have a test case specifying this behavioral change. Thanks to continuous integration (CI), the test is run on subsequent commits to check that they do no introduce a regression for that behavior. In this paper, we propose an approach that detects behavioral changes in commits. As input, it takes a program, its test suite, and a commit. Its output is a set of test methods that capture the behavioral difference between the pre-commit and post-commit versions of the program. We call our approach DCI (Detecting behavioral changes in CI). It works by generating variations of the existing test cases through (i) assertion amplification and (ii) a search-based exploration of the input space. We evaluate our approach on a curated set of 60 commits from 6 open source Java projects. To our knowledge, this is the first ever curated dataset of real-world behavioral changes. Our evaluation shows that DCI is able to generate test methods that detect behavioral changes. Our approach is fully automated and can be integrated into current development processes. The main limitations are that it targets unit tests and works on a relatively small fraction of commits. More specifically, DCI works on commits that have a unit test that already executes the modified code. In practice, from our benchmark projects, we found 15.29% of commits to meet the conditions required by DCI.

* 14:05--14:35<br>**Deep Software Variability: Towards Handling Cross-Layer Configuration** \\
*Luc Lesoil*, Mathieu Acher, Arnaud Blouin, Jean-Marc Jézéquel \\
Configuring software is a powerful means to reach functional and performance goals of a system. However, many layers (hardware, operating system, input data, etc.), themselves subject to variability, can alter performances of software configurations. For instance, configurations’ options of the x264 video encoder may have very different effects on x264’s encoding time when used with different input videos, depending on the hardware on which it is executed. In this vision paper, we coin the term deep software variability to refer to the interaction of all external layers modifying the behavior or non-functional properties of a software. Deep software variability challenges practitioners and researchers: the combinatorial explosion of possible executing environments complicates the understanding, the configuration, the maintenance, the debug, and the test of configurable systems. There are also opportunities: harnessing all variability layers (and not only the software layer) can lead to more efficient systems and configuration knowledge that truly generalizes to any usage and context.

* 14:35--15:05<br>**Expanding the Number of Reviewers in Open-Source Projects by Recommending Appropriate Developers** \\
*Aleksandr Chueshev*, Julia Lawall, Reda Bendraou, Tewfik Ziadi \\
Code review is an important part of the development of any software project. Recently, many open source projects have begun  practicing  lightweight  and  tool-based  code  review  (a.k.a modern  code  review) to  make  the  process  simpler  and  more efficient. However, those practices still require reviewers, of which there  may  not  be  sufficiently  many  to  ensure  timely  decisions. In this paper, we propose a recommender-based approach to be used by open-source projects to increase the number of reviewers from  among  the  appropriate  developers.  We  first  motivate  our approach  by  an  exploratory  study  of  nine  projects  hosted  on GitHub and Gerrit. Secondly, we build the recommender system itself,  which,  given a  code  change,  initially searches  for  relevant reviewers  based  on  similarities  between  the  reviewing  history and the files affected by the change, and then augments this set with developers who have a similar development history as these reviewers but have little or no relevant reviewing experience. To make  these  recommendations,  we  rely  on  collaborative  filtering, and more precisely, on matrix factorization. Our evaluation shows that  all  nine  projects  could  benefit  from  our  system  by  using  it both to get recommendations of previous reviewers and to expand their  number  from  among  the  appropriate  developers.


* 15:05--15:35<br>**Empirical Study of Restarted and Flaky Builds on Travis CI** \\
*Thomas Durieux*, Claire Le Goues, Michael Hilton, Rui Abreu \\
Continuous Integration (CI) is a development practice where developers frequently integrate code into a common codebase. After the code is integrated, the CI server runs a test suite and other tools to produce a set of reports (e.g., the output of linters and tests). If the result of a CI test run is unexpected, developers have the option to manually restart the build, re-running the same test suite on the same code; this can reveal build flakiness, if the restarted build outcome differs from the original build. In this study, we analyze restarted builds, flaky builds, and their impact on the development workflow. We observe that developers restart at least 1.72% of builds, amounting to 56,522 restarted builds in our Travis CI dataset. We observe that more mature and more complex projects are more likely to include restarted builds. The restarted builds are mostly builds that are initially failing due to a test, network problem, or a Travis CI limitations such as execution timeout. Finally, we observe that restarted builds have an impact on development workflow. Indeed, in 54.42% of the restarted builds, the developers analyze and restart a build within an hour of the initial build execution. This suggests that developers wait for CI results, interrupting their workflow to address the issue. Restarted builds also slow down the merging of pull requests by a factor of three, bringing median merging time from 16h to 48h.
