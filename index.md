---
title       : AESO EMMO Shiny app
subtitle    : Data Science Specialization - Developing Data Products
author      : Malcolm MacRae
job         : Course Project
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---



##  Pool Price

The price of electricity in the Alberta market can be extremely volatile. Hourly prices can range between $0 and $1000/MWh. 

<iframe src = 'http://ets.aeso.ca/ets_web/ip/Market/Reports/ActualForecastWMRQHReportServlet?contentType=html' height='600px'></iframe>

---

##  Stable Pool Price

In some days, pool price may remain low and stable in all hourly intervals.

![plot of chunk unnamed-chunk-2](assets/fig/unnamed-chunk-2.png) 

---

##  Volatile Pool Price

In other days, pool price may vary by hundreds of dollars between hourly intervals.

![plot of chunk unnamed-chunk-3](assets/fig/unnamed-chunk-3.png) 

---

##  Energy-Market Merit Order

The energy-market merit order provides insight into the system demand and participant offer behaviour that determines pool price in each hour. The Shiny application permits a user to view the EMMO in each hourly interval, and interpret the market conditions that influenced pool price.

[![Launch Shiny app](13Jul2014_HE16.png)](https://mmacrae.shinyapps.io/emmo/)

Click the picture to launch the app.
