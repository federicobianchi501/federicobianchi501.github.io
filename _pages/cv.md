---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

**Education**
======

* Ph.D. in Computer Science (Artificial Intelligence), University of Verona, 2025  
  Industry-funded Ph.D. program in collaboration with [Leonardo S.p.A.](https://www.leonardo.com/en/home)

* M.S. in Computer Science and Engineering, University of Verona, 2018  
  Final grade: 110/110 cum laude

* B.S. in Computer Science, University of Verona, 2016

**Research and Professional Experience**
======

* **Researcher in Artificial Intelligence and Reinforcement Learning**, Department of Computer Science, University of Verona, 2024 - Present  
  Research on reinforcement learning, planning, offline and model-based RL, safe policy improvement, uncertainty quantification, and reliable machine learning. Current work includes calibrated safe policy improvement for continuous offline reinforcement learning and planning under model and data uncertainty.

* **Industrial Research Collaboration - Pharmaceutical Machine Learning**, University of Verona / Newchem, 2024 - Present  
  Applied machine learning research for pharmaceutical spray-drying processes. Development of ETL and data-processing pipelines, predictive models, process characterization, and data-driven optimization using methods including Random Forests, Gaussian Processes, and Support Vector Machines.

* **Ph.D. Researcher in Artificial Intelligence**, Department of Computer Science, University of Verona / Leonardo S.p.A., 2021 - 2025  
  Research on safe policy improvement, reinforcement learning, model-based planning, Monte Carlo Tree Search, and uncertainty-aware learning. The research focused on improving baseline policies while controlling the risks associated with policy deviations under uncertainty.

* **Research Fellow**, Department of Computer Science, University of Verona, 2020 - 2021  
  Research within the European-funded [SAFEPLACE - IoT systems for healthy and safe living environments](https://www.ict4ssl.com/en/progetto-safe-place-en/) project. Developed model-based methods for prediction, planning, and optimization of thermal systems using real-world sensor and operational data.

* **Research Fellow**, Department of Computer Science, University of Verona, 2018 - 2020  
  Research within the European-funded [GHOTEM - Global House Thermal and Electrical Energy Management](https://www.di.univr.it/?ent=progetto&id=5233&lang=en) project. Developed machine-learning and time-series methods for predictive modeling of district-heating networks and intelligent energy-management systems.

**Selected Research Projects**
======

* **Calibrated Safe Policy Improvement for Continuous Offline Reinforcement Learning**, 2024 - Present  
  Development of statistically calibrated mechanisms for deciding when an offline reinforcement-learning policy can safely deviate from a baseline. The work combines model-based reinforcement learning, Monte Carlo Tree Search, ensemble uncertainty estimation, and statistical calibration.  
  Selected outcome: *Calibrated Safe Policy Improvement for Continuous Offline Reinforcement Learning*, accepted at **NeurIPS 2026**.

* **Pharmaceutical Process Modeling**, 2024 - Present  
  Machine-learning research for spray-drying processes, including experimental-data integration, predictive modeling, process characterization, and optimization in data-constrained industrial settings.

* **Safe Policy Improvement and Planning**, 2021 - 2025  
  Research on scalable safe policy-improvement methods using reinforcement learning, model-based planning, Monte Carlo Tree Search, and baseline-relative improvement mechanisms.

* **SAFEPLACE - IoT systems for healthy and safe living environments**, 2020 - 2021  
  Researcher and Software Engineer, Department of Computer Science, University of Verona. Development of predictive, planning, and optimization algorithms for intelligent thermal systems.

* **GHOTEM - Global House Thermal and Electrical Energy Management**, 2018 - 2020  
  Researcher and Software Engineer, Department of Computer Science, University of Verona. Development of machine-learning and time-series models for district-heating networks and energy-management applications.

**Research Interests**
======

* Reinforcement Learning
* Offline and Model-Based Reinforcement Learning
* Safe Policy Improvement
* Planning and Monte Carlo Tree Search
* Uncertainty Quantification and Calibration
* Reliable and Data-Efficient Machine Learning
* Predictive Modeling
* Time-Series Analysis
* Machine Learning for Industrial Applications

**Selected Funding and Fellowships**
======

* Industry-funded Ph.D. fellowship, [Leonardo S.p.A.](https://www.leonardo.com/en/home), 2021
* Research fellowship associated with the [SAFEPLACE](https://www.ict4ssl.com/en/progetto-safe-place-en/) project, 2020
* Research fellowship associated with the [GHOTEM](https://www.di.univr.it/?ent=progetto&id=5233&lang=en) project, 2018

**Publications**
======

<ul>{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>
