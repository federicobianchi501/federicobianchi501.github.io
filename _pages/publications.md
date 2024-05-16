---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my publications on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

**2024**
* Scalable Safe Policy Improvement for Factored multi-agent MDPs. Federico Bianchi, Edoardo Zorzi, Alberto Castellini, Thiago D. Simão, Matthijs T. J. Spaan, Alessandro Farinelli. In Proceedings of the 41th International Conference on Machine Learning (ICML 2024), pages 22. PMLR, 2024
* Developing safe and explainable autonomous agents: from simulation to the real world. Federico Bianchi, Alberto Castellini, Alessandro Farinelli1, Luca Marzari, Daniele Meli, Francesco Trotti, Celeste Veronese. The 4th National Conference on Artificial Intelligence (Ital-IA)

**2023**
* [Scalable Safe Policy Improvement via Monte Carlo Tree Search](https://federicobianchi501.github.io/files/ICML2023.pdf). Alberto Castellini, Federico Bianchi*, Edoardo Zorzi*, Thiago D. Simão, Alessandro Farinelli, Matthijs T. J. Spaan. In Proceedings of the 40th International Conference on Machine Learning (ICML 2023), pages 3732–3756. PMLR, 2023
* [Monte Carlo Tree Search Planning for continuous action and state space](https://federicobianchi501.github.io/files/AIxIA2023.pdf). Federico Bianchi, Lorenzo Bonanni, Alberto Castellini, Alessandro Farinelli. In Proceedings of the 9th Italian Workshop on Artificial Intelligence and Robotics (AIRO 2022), AI*IA 2022, volume 3417 of CEUR Workshop Proceedings, pages 38–47. CEUR-WS.org, 2023
* [Safe and Efficient Reinforcement Learning for Environmental Monitoring](https://federicobianchi501.github.io/files/AIxIA2023.pdf). Federico Bianchi, Davide Corsi, Luca Marzari, Daniele Meli, Francesco Trotti, Maddalena Zuccotto, Alberto Castellini, Alessandro Farinelli. The 3rd National Conference on Artificial Intelligence (Ital-IA)

**2022**
* [Generation and interpretation of parsimonious predictive models for load forecasting in smart heating networks](https://federicobianchi501.github.io/files/IntelligentSystems2022.pdf). Alberto Castellini, Federico Bianchi, Alessandro Farinelli. Applied Intelligence, Springer Nature, 2022
  
**2021**
* [XM HeatForecast: Heating Load Forecasting in Smart District Heating Networks](https://federicobianchi501.github.io/files/LOD2020a.pdf). Federico Bianchi, Francesco Masillo, Alberto Castellini, Alessandro Farinelli. LOD 2020 - The Fifth International Conference on Machine Learning, Optimization, and Data Science, July 19-23, 2020 - Certosa di Pontignano, Siena, Italy, Lecture Notes in Computer Science, volume 12514, pages 581-592, Springer-Verlag, 2021
* [Convolutional Neural Network and Stochastic Variational Gaussian Process for Heating Load Forecasting](https://federicobianchi501.github.io/files/LOD2020b.pdf). Federico Bianchi, Pietro Tarocco, Alberto Castellini, Alessandro Farinelli. LOD 2020 - The Fifth International Conference on Machine Learning, Optimization, and Data Science, July 19-23, 2020 - Certosa di Pontignano, Siena, Italy, Lecture Notes in Computer Science, volume 12514, pages 235-246, Springer-Verlag, 2021
  
**2020**
* [Predictive model generation for load forecasting in district heating networks](https://federicobianchi501.github.io/files/IEEE2020.pdf). Alberto Castellini, Federico Bianchi, Alessandro Farinelli. IEEE Intelligent Systems, IEEE, 36(4):86-95, 2020
* [Load Forecasting in District Heating Networks: Model Comparison on a Real-World Case Study](https://federicobianchi501.github.io/files/LOD2019.pdf). Federico Bianchi, Alberto Castellini, Pietro Tarocco, Alessandro Farinelli. In LOD 2019 - The Fifth International Conference on Machine Learning, Optimization, and Data Science, September 10-13, 2019 - Certosa di Pontignano, Siena, Italy, Lecture Notes in Computer Science, volume 11943, pages 553-565, Springer-Verlag, 2020


{% for yr in site.data.publist %}
<h3>{{ yr.year }}</h3>
-----
{% for publi in yr.pubs %}

{% if publi.team=="NA" %}
  <b style="color:blue;"> <u> [{{ publi.link.display }}] </u> </b> &nbsp;
  <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.title }}</a> <br /> {{ publi.description }} 
{% else %}
 <b>[{{ publi.link.display }}] </b> &nbsp;
  <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.title }}</a> <br /> {{ publi.description }}
{% endif %}

{% endfor %}
{% endfor %}
  
