---
title: "Visualizing Prehospital Cardiac Arrest Data"
layout: post
date: 2016-08-28 16:45
tag:
- Visualization
- R
- Shiny
- EMS
image: /assets/images/cpr.png
headerImage: true
projects: true
hidden: true # don't count this post in blog pagination
description: "This is a simple and minimalist template for Jekyll for those who likes to eat noodles."
category: project
author: tommy
externalLink: false
---

---

During the summer of 2016, I interned as a data analyst with <a href="https://www.emergencymedicine.pitt.edu/people/leonard-weiss">Dr. Leonard Weiss</a> at the University of Pittsburgh's <a href="https://www.shrs.pitt.edu/em">Department of Emergency Medicine</a>. Dr. Weiss'  <a href="https://www.ahajournals.org/action/doSearch?ContribAuthorStored=Weiss%2C+Leonard+S">research</a> is primarily in the field of prehospital cardiac arrest treatment. Using a large dataset of patient care reports from local paramedics and emergency medical technicians (EMTs), I identified and investigated metrics capable of enhancing understanding of emergency medical services' responses to cardiac arrests using traditional hypothesis testing, time series analysis, and autoregressive integrated moving average models. After identifying key metrics and trends, I presented the results presented to physicians, faculty, and researchers via an interactive application built using <a href="https://www.r-project.org/"R</a> and <a href="https://shiny.rstudio.com/">Shiny</a>. This approach allowed audience members to easily explore the visualized conclusions and trends themselves, rather than inundate members with static bar charts.

---

## Application Screenshots

While the interactive Shiny application contains protected health information and therefore cannot be shared publically, below are screenshots of the application using notional data. Please note that all instances and trends presented in the screenshots below are based on entirely simulated data and are not reflective of real patient care or EMS operations.

![Cardiac Arrest Outcomes]({{site.base_url}}/assets/images/ca_outcomes.png)

![Cardiac Arrest Bystander CPR]({{site.base_url}}/assets/images/ca_bystander_cpr.png)

![Cardiac Arrest Locations]({{site.base_url}}/assets/images/ca_location.png)

![Cardiac Arrest Response Times]({{site.base_url}}/assets/images/ca_response_times.png)

---

Header image source: <a href="http://pluspng.com/cpr-png-pictures-7816.html">PlusPNG.com</a>.
