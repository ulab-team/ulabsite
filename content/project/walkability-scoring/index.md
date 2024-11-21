---
title: Walkability scoring in high-density cities
subtitle: Data empower urban analytics

authors: 
- kjtzhao
- gbsun
- cwebster

author_notes:
- ''
- ''
- ''

tags: 
- walkability
- methodology

# Listing view
# view: compact

date: 2024-11-18
lastmod: 2024-11-18
featured: true
draft: false
show_related: true
pager: false
show_date: true
share: true
profile: true

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: Walkability score differences measured by pedestrian network vs. road network
  focal_point: ""
  preview_only: false

---

A standardised measurement makes walkability easily studied analytically and across various disciplines. Attempts to create walkability measures started in the 1990s, with increasingly sophisticated composite walkability indices being proposed in the past decade. One that gained wide attention is Walk Score, which is developed by a group of planners and urbanists and provides standardised walkability evaluations. Leveraging on web and amenities data, Walk Score evaluates a great number of cities in the USA, Canada, Australia and New Zealand. The ready-to-use scoring data and algorithms permit extensive evaluation by practitioners and researchers without their own modelling capacity. 

However, Walk Score data are not available to Asian cities. Superimposing its default algorithm to unsupported regions would yield inaccurate and unreliable measures, as Asian cities tend to be denser, and pedestrian networks differ from road networks. We constructed a walkability scoring system using amenities data and a 3D digital pedestrian network for Hong Kong. The same algorithm was applied to the regular road network in order to analyse how the scoring was underestimated. 

Our results show that streets were considered twice as walkable if rated by the pedestrian network rather than the road network. Walkability scores were 92% higher on average. 


![](workflow.jpg "Analysis Workflow")


### Project Outputs

- [Walkability Scoring: Why and how does a 3D pedestrian network matter?]({{< ref "/publication/2020-zhaosunwebster-epb/index" >}} "academic publication")

This work received 2021 **RTPI Commendation Award for Research Excellence**.
![](RTPI_Research_Award_logo_COMMENDED.jpg '')

_This project is funded by HKU Seed Fund for Basic Research, **Walkability and Housing Price in High-Density Cities of China** (2017.11-2019.11)._ 
{style="color: grey"}