---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Engineering Master (with high honors), Computer science, Modelling and Optimization,  CNAM Paris, 2012
* Research Master (with honors), [Information processing and data exploitation](https://formation.cnam.fr/rechercher-par-discipline/master-sciences-technologies-sante-mention-informatique-parcours-traitement-de-l-information-et-exploitation-des-donnees-813201.kjsp), CNAM Paris, 2013
* Ph.D elasticity of business processes execution, Université de Lorraine, 2019

Work experience
======
* 2022-2023: Post-doc (2 years)
  * Université Catholique de Louvain (Belgium)
  * Subject: elastic and predictive management of containers for IA and data science
  * Achievements
    * WIP capacity planning for stream processing engines- [preprint submitted at ICDE'23](/publication/2023-08-01-streambed)
    * WIP fine-grained scheduling for stream processing engines
    * WIP transparent sharding using service meshes
    * WIP high performance networking using service meshes - [Master thesis'23](https://dial.uclouvain.be/memoire/ucl/object/thesis:40653)
* 2019-2021: Post-doc (2.5 years)
  * Université Catholique de Louvain (Belgium)
  * Subject: innovative middleware for high-assurance cloud applications in geographically distributed infrastructures
  * Achievements 
    * privacy-enforcing proxies for recommendation systems using SGX - [Middleware'21](/publication/2021-11-01-middleware)
    * highly available stream processing engines using active replication - [SRDS'21](/publication/2021-09-01-srds)
    * live migration strategies using Foreign Data Wrappers [DAIS'21](/publication/2021-06-01-dais)
    * chaos engineering and benchmarking of blockchain platforms [EDCC'22](/publication/2022-09-01-edcc)
    * blockchain for Machine-as-a-Service [Engineering reports'22](/publication/2022-06-01-engineering)
* 2014-2019: PhD student (4 years)
  * Université de Lorraine (France)
  * Achievements
    * Optimization models for BPM tools elasticity in the cloud : our heuristic goal is to optimize the cost of the infrastructure of multi tenant BPMS, considering BPM task throughput as a QoS metric for customers and resources, and live migrations quantity limitation.
      * reactive bicriteria time slot heuristic approach [Cloud'16](/publication/2016-06-01-cloud)
      * proactive multiple time slots heuristic and model [BPM'17](/publication/2017-09-01-bpm)
      * enhancement of previous algorithm using genetic algorithms and alternative model [ICSOC'18](/publication/2018-11-01-icsoc)
    * Generic benchmarking approaches and frameworks, and metrics justification preparation and implementation of benchmarking approaches
      * cloud resource capacity automated and reproductible framework based on Docker [CloudCom'16](/publication/2016-12-01-cloudcom)
      * live migrations effects benchmarking approach and framework [CoopIS'18](/publication/2018-10-01-coopis)
    * Security in BPM tools evaluation model [Computers in industry'19](/publication/2019-01-01-industry)
    * Collaboration with the Software Institute team of the University of Lugano on the subject of BPM engine benchmarking.

* 2011-2014: Lead developer (3 years)
  * Company: Cintel (France)
  * Architecture of the solution for telephonic operator Traceis, technical management of development team, technological monitoring, training, software development
    * Migration of the solution from a 2-tier architecture (Delphi, JSP) to a 3-tier architecture based on Java EE 6 and a REST architecture (stack JPA 2, EJB 3.1, JSF2, Ext JS) on a Jboss 7 server: developers, technological choices, development
    * Selection and development of an Android application focusing the technicians with the Xamarin tool (C#)
    * Integration of a BPM tool (jBPM) in the Traceis solution
    * Generalization of unit and integration testing (jUnit, Arquilian, Selenium) and continuous integration (Jenkins, Maven)
    * Team management: planning, support, implementation of project tools (Redmine)
  * Used tools: DBSchema, Visio, Project, Netbeans, Redmine, Mantis BT, Subersion, jUnit, Selenium, Xamarin

* 2010-2011: Engineer intern (1 year)
  * LOCEAN Laboratory (UPMC University)
  * Development of new features in the variation assimilation software Yao - [Master thesis](/publication/2012-09-01-master-yao)
    * Development of dual and quasi-static algorithms in the Yao softare
    * Refactoring of the generator, optimisation of performance, parallelisation with OpenMP
  * Used tools: gcc, db, Boost library, BouML, vi, Matlab, OpenMP

* 2006-2010: Developer (4 years)
  * Company: Cintel (France)
  * Development of Amira module (management of work orders for telecommunications technicians) of the Traceis solution, technical support
  * Development of internal modules for data import, database structure
  * Used tools: Delphi 2006, Eclipse, BouML, Project, Subversion, Mantis BT, Java

* 2005-2006: Developer (1 year)
  * Company: ABL Infosoft (France)
  * Development of interfaces between the Anabio software and medical analysis robots using serial ports (RS232),
FTP
  * Installation and deployment in medical laboratories, technical support
  * Used tools: Delphi 3, 6 and 2006, Paradox 10, Async Pro 4 library, MSXML

* 2001-2003: Developer (2 years)
  * Company: ABL Infosoft (France)
  * Development of new features on business applications for small companies, technical support
  * Used tools: Abal, Screener, Twin Server

Skills
======
* Software development
  * Rust, C++, Java, Python
* Devops
  * Kubernetes, Docker, Istio
  * AWS, Azure, Grid5000, IOT-Lab
* Optimization
  * CPlex, Gurobi, SkOpt
* Machine Learning
  * Sklearn

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
 
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* 11/2023 WoC'23 International Workshop on Container Technologies and Container Clouds - PC member
* 09/2023 CloudNet 2023 - TPC Member
* 12/2022 OPODIS 2022 Conference on Principles of Distributed Systems - Publication chair
* 11/2022 23rd ACM/IFIP International Middleware Conference - Industry track PC member
* 04/2022 Eurosys 2022 - Shadow PC member
* 11/2021 WoC'21 International Workshop on Container Technologies and Container Clouds - PC member
* 05/2021 Transactions on Parallel and Distributed Systems - Reviewer
* 12/2020 WoC'20 International Workshop on Container Technologies and Container Clouds - PC Member
* 03/2020 IEEE Transactions on Computers - Reviewer
* 05/2019 International Journal of Computational Intelligence Systems - Reviewer

Grants
=====
* 01/2022-12/2023 Funding: 560000 € (participation to preparation of the project) - Win2Wal - Subject: Elastic and predictive management of containers for IA and data science - *current funding*.
* 11/2017-12/2018 Funding: 20000 $ - Microsoft Azure Sponsorship - Subject: elasticity of BPMaaS and SaaS, used for PhD work.
* 10/2015-10/2017 Funding: 2000 $ - AWS in Education Research Grant - Subject: elasticity of BPMaaS, used for PhD work.

Languages
=====
* Native in French
* Operational in English
* Beginner in 中文 (Mandarin Chinese, 2 years)