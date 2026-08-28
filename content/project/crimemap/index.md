---
title: CrimeMap
summary: Interactive R Shiny dashboard visualising police-recorded crime statistics across North Rhine-Westphalia's districts.
tags:
  - Clinical Research
date: "2024-01-01"
external_link: "https://axelbudde.shinyapps.io/CrimeMap/"
links:
  - icon: globe
    icon_pack: fas
    name: Open Dashboard
    url: https://axelbudde.shinyapps.io/CrimeMap/
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""
---

**CrimeMap** (PKS NRW) is an interactive R Shiny dashboard visualising police-recorded crime data across the districts (Kreise) of North Rhine-Westphalia, Germany, sourced from the **Bundeskriminalamt's Polizeiliche Kriminalstatistik (PKS)**.

### Features

- Interactive choropleth map of districts, coloured by crime frequency (Häufigkeitszahl per 100,000 inhabitants)
- Selectable offence types, reporting years (2013–2024), and reporting criteria
- Time-series bar chart tracking the selected offence and district across all reporting years
- District-level detail on hover, with instant recalculation of statistics and map colouring

### Technical

Data pipeline consolidates multiple years of BKA and state-level PKS releases (Excel/CSV) into a unified spatial dataset, joined to district shapefiles for mapping. Built and deployed as a standalone R Shiny application.
