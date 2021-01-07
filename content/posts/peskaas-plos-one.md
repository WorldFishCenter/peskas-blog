---
title: "New Peskas paper now out in PLoS One"
date: 2021-01-06T18:09:41+13:00
author: "Alex Tilley"
draft: true
description: "A new paper out in PLoS One detailing the design and piloting of the PeskAAS fisheries monitoring system"
tags: [ "architecture", "tech", "fisheries", "ICT4SSF", "ICT4Fisheries" ] 
ShowToc: false 
TocOpen: false 
mermaid: false
---

A new paper is now out in PLoS One which details the design and piloting of Peskas in East Timor. [Read and download it here](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0234760).

<h2>Unreported doesn't mean illegal</h2>

Global coverage of ocean issues typically links IUU with overfishing without emphasizing that much of this not necessarily Illegal, but may merely be Unreported. This is true for many small-scale fisheries around the world as they are often remote and informal and very hard to track. However, recent global research suggests that where data are routinely collected and used for fisheries management, fisheries are sustainable or increasing [(Hilborn et al., 2020)](https://www.pnas.org/content/117/4/2218). Furthermore, small-scale fisheries stakeholders are generally excluded from decision making around their resources and livelihoods due to this same lack of quantifiable evidence.

The adage **"If you can't count it, it doesn't count"** is particularly fitting in East Timor, a half-island nation north of Australia. 
Timor has one of the highest rates of malnutrition in the world, yet despite the importance of fish for micronutrients, there has traditionally been very little investment in the fisheries sector. Around 80% of coastal households rely on marine resources to some degree. 

<h2>Why we created PeskAAS</h2>

WorldFish has been working with the Government of East Timor since 2010 and initially there were very few fisheries data on which to base recommendations. We set out to build a system with the government but were keen to avoid common pitfalls with tech interventions. Often apps and platforms that gather and display data are developed in funded projects and by private companies, but when those projects end and the funding stops, the system typically fails, or the data remain behind a paywall, and you need to pay the company to make any changes or updates to the software. We wanted a system that was **digital, lightweight, responsive, and transparent** but we were also aware that to be maintained and used past the end of external funding support,  it should be **cheap and open source**.

<h2>PeskAAS is a data pipeline</h2> 

An R script pulls data together from the catch form and vessel trackers, combines them, organizes and analyses those data, then summarises them on a public webpage. We established a network of enumerators to record catch from fishers when they land using a simple XForm. Through a partnership with [Pelagic Data Systems](www.pelagicdata.com), we installed a few hundred of their solar-powered vessel trackers on canoes and motorboats. They provide very high-resolution positions compared to traditional VMS. 
Pelagic tracking is not free, but an optional extra that integrates with PeskAAS to provide spatial data for effort and CPUE. 
The summary data and plots of CPUE over time are displayed on a **webpage dashboard** built using R Shiny. You can visit this page and take a look [here](https://worldfish.shinyapps.io/peskAAS/), it is public. 

<h2>Outcomes</h2>

The interface and analytics are still simple in PeskAAS East Timor because this is an ongoing process of building and capacity development. In other locations and contexts, we are working to automate models of biomass surplus production, to use and test in the adaptive management of community fisheries. PeskAAS was introduced in 2017, and was quickly adopted by the Timorese government. It has brought new insights into fishing patterns, enabled more engagement with fishers and guided new fisheries policy, but there is still much work to improve its contribution to inclusive governance.

The process of co-design with end users and continuous feedback and consultations with local partners is crucial to the sustainability of information and communication technologies for small-scale fisheries [(FAO & WorldFish 2020)](http://www.fao.org/documents/card/en/c/cb2030en). We believe the rapid uptake and early policy successes are thanks to the strong local partnerships and trust with our local partners. 
