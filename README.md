# SWMM_Hoboken
SWMM model used for multiple studies based in Hoboken, NJ, USA.

Articles using the model include:
1. Liu, T., Su, X., & Prigiobbe, V. (2018). Groundwater-sewer interaction in urban coastal areas. Water, 10(12), 1774. https://doi.org/10.3390/w10121774
2. Su, X., Liu, T. (equally contributed), Beheshti, M., & Prigiobbe, V. (2020). Relationship between infiltration, sewer rehabilitation, and groundwater flooding in coastal urban areas. Environmental Science and Pollution Research, 27(13), 14288-14298. https://doi.org/10.1007/s11356-019-06513-z
3. Kriebel, M., Liu, T. (equally contributed), Noordhoek R., Staas L.S., Ramirez-Marquez, J. E., & Prigiobbe, V. (2025). Modeling green infrastructure as a flood mitigation strategy in an urban coastal area. Urban Ecosystems, 28:9. https://doi.org/10.1007/s11252-024-01660-9

The build of the base model (folder /Scenario_0) without green infrastructure implementation is reported in Article 1. Descriptions of the other green infrastructure scenarios can be found in Article 3 (Table 1):

| Scenario | Type of Measure                                                           | Implementation                                                                                 | Potential Water Storage                                  |
|----------|---------------------------------------------------------------------------|------------------------------------------------------------------------------------------------|----------------------------------------------------------|
| 0        | No action (baseline scenario)                                             |                                                                                                |                                                          |
| 1        | Stormwater infiltration planters and street trees (i.e. Right-of-ways)    | 41 ROWs within the study area, following Hoboken’s Green Infrastructure Strategic Plan (City of Hoboken 2013; Dewberry 2017b) | 44 m³                                                    |
| 2        | Right-of-ways (ROWs)                                                      | ROWs at every street corner in the study area below the median elevation of H1 and H3           | 837 m³                                                   |
| 3        | Right-of-ways (ROWs)                                                      | ROWs at every street corner and on wide pavements in the study area                             | 1,425 m³                                                 |
| 4        | Resiliency parks (designed wetlands, basins, and ponds)                   | Block 10 site and NJ Transit site (City of Hoboken 2013; Dewberry 2017b)                        | 2,271 m³ (Block 10 site) and 5,300 m³ (NJ Transit site)  |
| 5        | Green roofs                                                               | On 25% largest flat roofs in the study area                                                    | 3,098 m³                                                 |
| 6        | Green roofs                                                               | On all flat study area roofs                                                                   | 6,653 m³                                                 |

