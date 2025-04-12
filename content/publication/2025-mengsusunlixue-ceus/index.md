---
title: "From 3D pedestrian networks to wheelable networks: An automatic wheelability assessment method for high-density urban areas using contrastive deep learning of smartphone point clouds"

authors:
- Siyuan Meng
- Xian Su
- gbsun
- Maosu Li
- Fan Xue

author_notes:
- ""
- ""
- ""
- ""
- "Corresponding Author"

date: "2025-04-12T00:00:00Z"
doi: "10.1016/j.compenvurbsys.2025.102255"

# Schedule page publish date (NOT publication's date).
publishDate: "2025-01-23T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "_Computers, Environment and Urban Systems, 117_"
publication_short: ""

# Summary. An optional shortened abstract.
summary: This paper presents a contrastive deep learning-based wheelability assessment method bridging street-scale smartphone point clouds and a city-scale 3D pedestrian network (3DPN). We reinforced the city-scale 3DPN using smartphone point clouds, a promising data source for supplementing fine-grain details and temporal changes due to the centimeter-level accuracy, vivid color, high density, and crowd sourcing nature. 

tags:
- urban analytics

featured: false

# links:
# - name: ""
#   url: ""
url_project: ''


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Publication Cover Page'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: 
- ""

---

## Abstract

This paper presents a contrastive deep learning-based wheelability assessment method bridging street-scale smartphone point clouds and a city-scale 3D pedestrian network (3DPN). 3DPNs have been studied and mapped for walkability and smart city applications. However, the city-level scale of 3DPN in the literature was incomplete for assessing wheelchair accessibility (i.e., wheelability) due to omitted pedestrian paths, undetected stairs, and oversimplified elevated walkways; these features could be better represented if the mapping scale was at a micro-level designed for wheelchair users. In this paper, we reinforced the city-scale 3DPN using smartphone point clouds, a promising data source for supplementing fine-grain details and temporal changes due to the centimeter-level accuracy, vivid color, high density, and crowd sourcing nature. The three-step method reconstructs pedestrian paths, stairs, and slope details and enriches the city-scale 3DPN for wheelability assessment. The experimental results on pedestrian paths demonstrated accurate 3DPN centerline position (mIoU = 88.81 %), stairs detection (mIoU = 86.39 %), and wheelability assessment (MAE = 0.09). This paper contributes an automatic, accurate, and crowd sourcing wheelability assessment method that bridges ubiquitous smartphones and 3DPN for barrier-free travels in high-density and hilly urban areas.