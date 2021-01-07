---
title: "If you can't count it, it doesn't count"
date: 2021-01-06T18:09:41+13:00
author: "Alex Tilley"
draft: true
description: "A new paper out in PLoS One detailing the design and piloting of the PeskAAS fisheries monitoring system"
tags: [ "architecture", "tech", "fisheries", "ICT4SSF", "ICT4Fisheries" ] 
ShowToc: false 
TocOpen: false 
mermaid: false
---

A new paper is now out in PLoS One which details the design and piloting of Peskas in East Timor.
[Have a look here](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0234760)
Global coverage of ocean issues typically links IUU with overfishing without emphasizing that much of this not necessarily **I**llegal, but also **U**nreported. 
This is true for many small-scale fisheries around the world. 
Recent global research suggests that where data are routinely collected and used for fisheries management, fisheries are sustainable or increasing.
The adage **"If you can't count it, it doesn't count"** is particularly fitting in Timor-Leste, a half-island nation north of Australia. 
Timor has one of the highest rates of malnutrition in the world, yet despite the importance of fish for micronutrients, there has traditionally been very little investment in the fisheries sector. 
Around 80% of coastal households rely on marine resources to some degree. 
WorldFish has been working with the Government of East Timor since 2010, yet had very few fisheries data on which to base recommendations. **This is why we created PeskAAS**
We set out to build a system with the government but were keen to avoid common pitfalls with tech interventions. 
Often apps and platforms are developed in funded projects and by private companies, but when those projects end and the funding stops, the system typically fails, or the data remain behind a paywall, and you need to pay the company to make any changes or updates to the software.
We wanted a system that was digital, lightweight, responsive, and transparent but we were also aware that to be maintained and used past the end of external funding support,  it should be cheap and open source.
__PeskAAS is a data pipeline__. 
An R script pulls data together from the catch form and vessel trackers, combines them, organizes and analyses those data, then summarises them on a public webpage.
We established a network of enumerators to record catch from fishers when they land using a simple XForm.  
Through a partnership with Pelagic Data Systems, we installed a few hundred of their solar-powered vessel trackers on canoes and motorboats. They provide very high-resolution positions compared to traditional VMS. 
Pelagic tracking is not free, but an optional extra that integrates with PeskAAS to provide spatial data for effort and CPUE. 
The summary data and plots of CPUE over time are displayed on a **webpage dashboard** built using R Shiny. You can visit this page and take a look [here](https://worldfish.shinyapps.io/peskAAS/), it is public. 
The interface and analytics are still simple because this is an ongoing process and more sophisticated production models are not relevant at present. In other locations and contexts, we are working to automate models of biomass surplus production, to use and test in adaptive management of community fisheries.
**PeskAAS was introduced in 2017**, and was quickly adopted by the Timorese government. It has brought new insights into fishing patterns, enabled more engagement with fishers and guided new fisheries policy, but there is still much work to improve its contribution to inclusive governance.
We believe its success is thanks to the strong local partnerships and trust we built through consultations and co-design with end-users. 
