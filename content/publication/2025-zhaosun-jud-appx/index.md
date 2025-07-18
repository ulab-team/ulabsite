---
title: "Appendix for Push, Pull, or Network? Government Public Engagement Strategies in Pandemic-Induced Street Experiments"
authors:
- kjtzhao
- gbsun

author_notes:
- ""
- "Corresponding Author"

date: "2025-07-18T00:00:00Z"
# doi: "10.1016/j.eist.2025.101007"

# Schedule page publish date (NOT publication's date).
publishDate: "2025-07-27T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: "__Urban Infrastructure Transition Lab__"
publication_short: "uLab"

# Summary. An optional shortened abstract.
summary: This set of appendices complements the article 'Push, Pull, or Network? Government Public Engagement Strategies in Pandemic-Induced Street Experiments' by elaborating the data collection and analysis processes. The first is the pseudocode for social media comment collection, the second includes the queries used for the collection, the third appendix supplements programme details and interview data collection, and the fourth table shows the intermediary results of the public engagement tactics.  

tags:
- street experiment

featured: false

# links:
# - name: ""
#   url: ""
url_project: ''


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
<!-- image:
  caption: 'Conceptual framework for experiential learning in tactical urbanism'
  focal_point: ""
  preview_only: false -->

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: 
- global-street-experiment

---

## Appendix 1. Pseudocode for social media collection

The social media data collection involved two rounds. The first round involved establishing customised search queries based on the programme’s keywords and searching for relevant original tweets, and the second round involved searching for direct replies by official accounts in the relevant posts identified in the first round.

```python
# Example of code highlighting
From accounts > 
    request all original tweets that include programme keywords between 	
    2020-03-11 ~ 2023-03-11 > 
    in returned tweets > 
    request all tweets replied to by official accounts
From first-round data > 
    identify conversation threads >
    search all replies by the official accounts
```
## Appendix 2. Comment collection queries
Table A1. Typical queries used to search results

| **    City/Region, Country   **       | **    Search query: username, not a retweet, (keywords)   **                                                                                                                                              |
|---------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|     Victoria State,   Australia       |     'from:vicgovdtp -is:retweet -is:reply   ("pop-up bike lanes" OR #popup OR #popupbikelane OR #pop-up OR   #pop-up-bikelane OR "bike lane" OR "cycle lane")'                                            |
|     Vienna, Austria                   |     'from:stadt_wien -is:retweet -is:reply ("temporäres   Radnetz" OR Pop-Up-Fahrradspur OR Begegnungszonen OR #popup OR   #popupradweg OR "pop-up radwege")'                                             |
|     Milan, Italy                      |     'from:comunemi -is:retweet -is:reply   ("strade aperte" OR "open streets" OR "open   square" OR "Piazze Aperte" OR "piste ciclabili")'                                                                |
|     Barcelona, Spain                  |     '(from:bcn_ajuntament OR from:barcelona_cat OR from:BCN_Mobilitat)   -is:retweet -is:reply ("Una nova mobilitat sostenible en un nou espai   public" OR tactica OR bicicletes)'                       |
|     Chicago, United   States          |     'from:chicagodot -is:retweet -is:reply   ("shared street" OR "shared streets" OR "outdoor   patios" OR "outdoor dining")'                                                                             |
|     Los Angeles, United   States      |     'from:ladotofficial -is:retweet -is:reply ("slow street"   OR "slow streets")'                                                                                                                        |
|     New York City,   United States    |     'from:nyc_dot -is:retweet -is:reply   ("open street" OR "open streets" OR "open   restaurants" OR "open restaurant" OR "outdoor   dining" OR "outdoor dinings")'                                      |
|     Mexico City, Mexico               |     'from:lasemovi -is:retweet -is:reply ("Ciclovías   Emergentes" OR #popupbikelane OR "Espacios peatonales   emergentes" OR "conversion de espacios" OR "urbanismo   tactico" OR #tacticalurbanism)'    |
|     Vancouver, Canada                 |     'from:cityofvancouver -is:retweet   -is:reply ("slow streets" OR "pop-up plazas" OR   "temporary road closures" OR "reallocate" OR   "temporary patios" OR "temporary plazas")'                       |
