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
* B.S. in Statistics, Carnegie Mellon University, 2021
* M.S. in Statistical Science, Duke University, 2023
* Ph.D in Computer Science, Dartmouth College, 2028 (expected)

Work experience
======
* Summer 2022: Research Assistant
  * Atriumn Health
  * Duties included: Implement averaging images algorithm on patients Hernia CT image and build a 7 layered mixed value CNN to successfully identify symptomatic and non-symptomatic hernia with .74 AUC. Build a 5 layer CNN with a pre-trained 4 layer FNN and learnable linear interpolation to predict on recurrence rate of Hernia using pre-operative CT images, arguing that some basic demographic information is more meaningful than the CT scan itself when predicting the recurrence rate. 
  * Supervisor: Todd Heniford

* Summer 2021: Machine Learning Intern
  * Blep Analytics
  * Duties included: Using public API to gather the historical daily price, open value, and the trading volume of Bitcoin 
 Performed ACF, PACF, and Ljung-Box test to determine the suitable model for the volatility of Bitcoin daily log return. Conducted Model comparison and diagnostics to choose the suitable parameters for the ARMA-GARCH model 
Used the suitable ARMA-GARCH model to make prediction on the future Bitcoin volatility 
Confirm the prediction on volatility with the Long Short-Term Memory Model
Collaborated with colleagues to finish a report on the volatility of Bitcoin daily log return
  * Supervisor: Allie Zhang
  
Publications 
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
