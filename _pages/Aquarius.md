---
title: "AQUARIUS"
permalink: /Aquarius/
header:
  image: "/images/LotusFlower.jpg"
---

I have worked extensively to customize the St. Johns River Water Management District's implementation of [Aquatic Informatics](https://aquaticinformatics.com/products/aquarius/) products AQUARIUS Time-Series and WebPortal.  These projects illustrate some of these customizations and may be of use to others in their AQUARIUS implementations.

### Data Wrangling
[Preparing HydroCycle-PO4 Data for AQUARIUS Time-Series](https://mguyette.github.io/Aquarius_Cycle/) [R]{: .btn .btn--info} <span style="background-color: royalblue; text-color: white; padding: 4px;" box-sizing=border-box>R</span>\
We deploy instruments to record phosphate data, and the telemetry files must be modified before they can be uploaded into AQUARIUS Time-Series.  This project walks through the steps I took to set up this workflow.

### Data Processing
[Preparing Drift Correction End Points for USGS Multi-Point Corrections in AQUARIUS Time-Series](https://mguyette.github.io/Aquarius_Drift_Corrections/) <span style="background-color: royalblue; text-color: white; padding: 4px;" box-sizing=border-box>R</span>\
We are unable to directly utilize the automatic corrections built into AQUARIUS Time-Series.  This projects explains why we had to think outside the box, and how we perform our corrections.

### Dashboards
[Creating AQUARIUS WebPortal Dashboards to show Water Quality Station Status](https://mguyette.github.io/Aquarius_StatusDashboards/)
<span style="background-color: maroon; text-color: white; padding: 4px;" box-sizing=border-box>HTML</span> <span style="background-color: darkgreen; text-color: white; padding: 4px;" box-sizing=border-box>SQL</span> <span style="background-color: firebrick; text-color: white; padding: 4px;" box-sizing=border-box>JavaScript</span>\
I designed a dashboard that allows field and office staff to assess the status of each sonde and probe deployed at a water quality station at a glance.

### Time Series Repair
[Creating JSON objects for AQUARIUS Acquisition API overwriteappend](https://mguyette.github.io/Aquarius_OverwriteAppendPrep/) <span style="background-color: royalblue; text-color: white; padding: 4px;" box-sizing=border-box>R</span> <span style="background-color: darkslategray; text-color: white; padding: 4px;" box-sizing=border-box>JSON</span>\
On rare occasions the wrong parameter gets uploaded into a time series.  This is the process I designed to allow us to easily fix this problem.
