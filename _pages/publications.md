---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can also find my publications on my <u><a href="{{author.googlescholar}}"> Google Scholar</a></u> profile.

**2024**
* Scalable Safe Policy Improvement for Factored multi-agent MDPs.
* Developing safe and explainable autonomous agents: from simulation to the real world.

**2023**
* [Scalable Safe Policy Improvement via Monte Carlo Tree Search]()
* [Monte Carlo Tree Search Planning for continuous action and state space]()
* [Safe and Efficient Reinforcement Learning for Environmental Monitoring]()
  
**2021**
* [XM HeatForecast: Heating Load Forecasting in Smart District Heating Networks]()
* [Convolutional Neural Network and Stochastic Variational Gaussian Process for Heating Load Forecasting]()
  
**2020**
* [Predictive model generation for load forecasting in district heating networks]()
* [Load Forecasting in District Heating Networks: Model Comparison on a Real-World Case Study]()
  
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
