---
title: "AQUARIUS"
permalink: /Aquarius/
header:
  image: "/images/LotusFlower.jpg"
classes: wide
---

I have worked extensively to customize the St. Johns River Water Management District's implementation of [Aquatic Informatics](https://aquaticinformatics.com/products/aquarius/) products AQUARIUS Time-Series and WebPortal.  These projects illustrate some of these customizations and may be of use to others in their AQUARIUS implementations.

### Data Wrangling
[Preparing HydroCycle-PO4 Data for AQUARIUS Time-Series](https://mguyette.github.io/Aquarius_Cycle/) [R](/Languages#r){: .btn .btn--info}  
We deploy instruments to record phosphate data, and the telemetry files must be modified before they can be uploaded into AQUARIUS Time-Series.  This project walks through the steps I took to set up this workflow.

<!--
### Data Processing
[Preparing Drift Correction End Points for USGS Multi-Point Corrections in AQUARIUS Time-Series](https://mguyette.github.io/Aquarius_Drift_Corrections/) [R](/Languages#r){: .btn .btn--info}  
We are unable to directly utilize the automatic corrections built into AQUARIUS Time-Series.  This projects explains why we had to think outside the box, and how we perform our corrections.
-->
### Dashboards
[Creating AQUARIUS WebPortal Dashboards to show Water Quality Station Status](https://mguyette.github.io/Aquarius_StatusDashboards/) [SQL](/Languages#sql){: .btn .btn--success} [HTML](/Languages#html){: .btn .btn--warning} [JavaScript](/Languages#javascript){: .btn .btn--danger}  
I designed a dashboard that allows field and office staff to assess the status of each sonde and probe deployed at a water quality station at a glance.

### Time Series Repair
[Creating JSON objects for AQUARIUS Acquisition API overwriteappend](https://mguyette.github.io/Aquarius_OverwriteAppendPrep/) [R](/Languages#r){: .btn .btn--info} [JSON](/Languages#json){: .btn .btn--primary}  
On rare occasions the wrong parameter gets uploaded into a time series.  This is the process I designed to allow us to easily fix this problem.
