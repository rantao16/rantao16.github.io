---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
Email: rantao16 [at] umd [dot] edu

I am a 5th-year Ph.D. student in the Department of Mathematics at the [University of Maryland, College Park](https://www-math.umd.edu/). I’m fortunate to be advised by [Yu Gu](https://www.math.umd.edu/~ygu7/). Previously, I got my B.S. degree from the School of Mathematical Sciences at Fudan University in 2019.

My research is in Probability and Stochastic analysis. I am interested in the random dynamics in stochastic partial differential equations. Currently, I am working with some stochastic heat equations and KPZ equations. 

Preprints and Publications:
======
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
