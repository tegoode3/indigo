---
title: "Forecasting Ambulance Demand with Complex Seasonality"
layout: post
date: 2017-05-11 22:10
tag:
- Modeling
- Time Series
- Forecasting
- R
- EMS
image: /assets/images/pgh_ems_m1.jpeg
headerImage: true
projects: true
hidden: true # don't count this post in blog pagination
description: "This is a simple and minimalist template for Jekyll for those who likes to eat noodles."
category: project
author: tommy
externalLink: false
---

---


"How many emergencies are there going to be today?" "How many ambulances are needed to cover the city?" "How should I position those ambulances?"

These are common questions for any urban EMS chief, public safety manager, or emergency operations administrator. While no two days are identical and medical emergencies occur spontaneously, trends in existing public safety data can support the resource allocation of public safety assets. During my undergraduate studies in statistics at Carnegie Mellon University, I explored the application of a modern time series forecasting method on ambulance demand in an urban environment with my research advisor, <a href="http://www.stat.cmu.edu/~pfreeman/">Dr. Peter Freeman</a>. While existing models forecast similar types of ambulance demand, the goal of my work was to show that a newer model, (the Trigonometric Exponential Smoothing State Space Model with Box-Cox Transformation, ARMA Errors, Trend and Seasonal Components, or "TBATS" model) could also be a suitable candidate for modeling ambulance demand by virtue of the model's ability to model time series with multiple seasonalities (a prominent feature of ambulance demand time series data). 

Initial results appeared promising, though the research was limited and there is potential for significant evolution of the methodology. I am excited to advise current undergraduate students at Carnegie Mellon University who are working to improve upon this approach and incorporate additional data, like geospatial information, to better support EMS administrators and managers in their resource allocation and operational planning.
 
---

<iframe src="//www.slideshare.net/slideshow/embed_code/key/4AuDx2foOjmDPH" width="595" height="485" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" style="border:1px solid #CCC; border-width:1px; margin-bottom:5px; max-width: 100%;" allowfullscreen> </iframe> <div style="margin-bottom:5px"> <strong> <a href="//www.slideshare.net/secret/4AuDx2foOjmDPH" title="CMU Meeting of the Minds 2017" target="_blank">CMU Meeting of the Minds 2017</a> </strong> from <strong><a href="https://www.slideshare.net/TomGoode10" target="_blank">Tom Goode</a></strong> </div>

---

Header image source: <a href="http://www.code3firetrucks.com/co3pif11.html">Code 3 Fire Trucks</a>.
