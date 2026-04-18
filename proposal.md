---
layout: default
title: Proposal
---

# Proposal
*This proposal was written for ENC3241: Writing for the Technical Profession at the University of Central Florida. It outlines a research project to develop a heat-aware walkability index for the UCF campus using LiDAR scanning and spatial data analysis. The content reflects my knowledge as a Data Science undergraduate and my interest in laser scanning applications, which I am exploring in Laser Scanning America's Past (AMH 4594H).*

## Developing a Heat-Aware Walkability Index Using Spatial and Environmental Data
 
**Andrea Ritter** — Data Science
 
---
 
### Background
 
Walkability is a key component of urban planning, influencing public health, environmental sustainability, and overall quality of life (Ewing and Cervero, 2010). Residents and urban developers alike often strive to increase their areas' walkability, though this can be challenging with gaps in the data needed to fully understand an area. A popular way to define cities, campuses, and other urban areas is with a walkability index. The most commonly used and accessible walkability index is developed by the US EPA and is calculated using the following variables: intersection density, proximity to transit stops, and diversity of land uses (U.S. Environmental Protection Agency, 2021). However, in hot climates like Florida, other factors contributing to a location's heat exposure should be considered for a more accurate measure of the ability to walk from place to place within an area. Research has shown that excessive heat and lack of shade can discourage pedestrian activity and contribute to negative health outcomes (Shashua-Bar et al., 2011). There is evidence of a cooling effect from not only tree shade but also short vegetation (Bowler et al., 2010), meaning green space in general should be considered when determining a heat-aware walkability index.
 
---
 
### Methodology
 
We will query publicly available spatial datasets and combine them with primary data collection. The data to be collected from public sources will include: Geographic Information System (GIS) data for roads, sidewalks, and land use; tree canopy and green space data; and weather and temperature data. The primary data to be collected will use LiDAR scanning technology to capture shade coverage from trees and built structures within the UCF main campus pedestrian corridors, which we will designate as the study area.
 
After collection, we will process the data. Data will be cleaned and integrated using Python and GIS software. Four factors will be developed: percentage of shade coverage along walking paths, distance between shaded areas, estimated heat exposure based on environmental conditions, and traditional walkability features such as connectivity and proximity to destinations.
 
Finally, a heat-aware index will be developed for the study area. The index will be calculated using a weighted scoring system or a regression-based model. The final approach will be selected based on the distribution and correlation of the collected data. If relationships between factors are relatively linear and interpretable, a weighted scoring system will be used; if the data has more complex interactions, a regression-based model will be applied. The final index will be compared to the current area's US EPA Walkability index.
 
---
 
### Anticipated Outcomes
 
This research will result in a newly developed heat-aware walkability index, which could be further tested and applied to other areas. Findings will be shared through three primary products: a final written report documenting the methodology and results, a presentation submitted to a relevant regional or national conference, and a publicly accessible project website summarizing the index, key findings, and recommendations for practitioners. This project will lead to data-driven recommendations for improving pedestrian infrastructure and will provide a more robust understanding of walkability in warm climates, highlighting areas where improvements are most needed.
 
---
 
### Significance
 
This work will highlight an overlooked factor (heat) when considering an area's walkability. This research can be used to guide the work of local government, city planners, infrastructure departments, and environmental organizations. The development of a heat-aware walkability index will be a more accurate measure of walkability to be used in any hot climate.
 
---

### References
 
Bowler, D. E., Buyung-Ali, L., Knight, T. M., & Pullin, A. S. (2010). Urban greening to cool towns and cities: A systematic review of the empirical evidence. *Landscape and Urban Planning, 97*(3), 147–155. https://doi.org/10.1016/j.landurbplan.2010.05.006
 
Ewing, R., & Cervero, R. (2010). Travel and the built environment: A meta-analysis. *Journal of the American Planning Association, 76*(3), 265–294. https://doi.org/10.1080/01944361003766766
 
Shashua‐Bar, L., Pearlmutter, D., & Erell, E. (2011). The influence of trees and grass on outdoor thermal comfort in a hot‐arid environment. *International Journal of Climatology, 31*(10), 1498–1506. https://doi.org/10.1002/joc.2177
 
U.S. Environmental Protection Agency. (2021, June). National walkability index user guide and methodology [Reports and Assessments]. https://www.epa.gov/smartgrowth/national-walkability-index-user-guide-and-methodology

---
 
### Timeline
 
| Dates | Tasks |
|-------|-------|
| Jan 1, 2027 – Feb 1, 2027 | Conduct LiDAR scanning sessions at the UCF main campus. Use the UCF lab drone and laser scanner; process raw point cloud data into shade coverage measurements using LiDAR processing software. |
| Feb 1, 2027 – March 1, 2027 | Combine shade and heat exposure data with GIS layers. Calculate the four index factors, develop and apply the weighted scoring model to produce the heat-aware walkability index. |
| March 1, 2027 – April 1, 2027 | Analyze index results and compare to EPA walkability scores. Write final report, build project website, and prepare conference presentation materials. |
 
---
 
### Budget
 
| Item | Units and Cost | Total |
|------|---------------|-------|
| Local travel (gas for laser scanning) | Est. 10 miles × $0.445/mile (UCF reimbursement rate) | $4.45 |
| Laser scanning equipment (Drone + Laser scanner) | Borrowed from the UCF lab | $0 |
| Printing and materials | Estimated | $50 |
| Laser scanning software license (processing LiDAR/point clouds) | 1 license | $120 |
| Drone rental/operator fee (optional, for aerial scans) | 1 full day of scanning | $300 |
| Software/tools (QGIS, Python) | Free | $0 |
| **Total** | | **$474.45** |
