# Overview

This folder contains the following datasets and R code required for estimating district-level vaccination coverage against yellow fever in Ghana using a cohort state-transition model.

# R code

* **YF_vaccination_coverage_model.Rmd** - contains R code for model creation and map visualization.
* **YF_vaccination_coverage_model.html** - presents R code knitted in HTML format.

# Datasets

* **optimistic1970.csv** - contains all data pertaining to Ghana district-level population estimates and routine/supplementary immunization. Its contents include the following:
  * Population estimates
     * ‘_infants_’ column – number of infants per district per year
     * ‘_non-infants_’ column – number of non-infants per district per year
     * ‘_total_pop_’ column – number of infants and non-infants per district per year
  * Vaccination data
     * ‘_routine_’ column - % of infants vaccinated through routine immunization (RI) per district per year
     * ‘_supplementary_’ column - % of previously non-vaccinated infants and non-infants vaccinated through supplementary immunization activities (SIA) per district per year
     * ‘_shearer_opt_’ column – baseline vaccination coverage of population per district in 2000  
* **coverage_by_district_year_opt2000.csv** - district-level vaccination coverage estimates generated from running the model code; included as one of several covariates in the manuscript.
* **261_Districts.shp**/**.shx**/**.dbf** - .shp files needed for producing district-level maps of Ghana.

# Data sources

The sources for the datasets above include the following (see <u>References</u> section below for full list of citations):

* Population estimates
  * Annual age-structured population: United Nations Department of Economic and Social Affairs, Population Division (2024)<sup>1</sup>
  * Population distribution by district: WorldPop<sup>2</sup>
*	Vaccination data
  * Baseline coverage: Shearer et al. (2017)<sup>3</sup>
  * Routine immunization: Ghana Health Service (2026)<sup>4</sup>
  * Supplementary immunization activities:
     * Agbenu et al. (2014)<sup>5</sup>
     * Amponsa-Achiano et al. (2022)<sup>6</sup>
     * Appiah et al. (2025)<sup>7</sup>
     * Domingo et al. (2019)<sup>8</sup>
     * Garske et al. (2014)<sup>9</sup>
     * Shearer et al. (2017)<sup>3</sup>
     * World Health Organization (2008)<sup>10</sup>
     * World Health Organization (2020)<sup>11</sup>
     * World Health Organization (2021)<sup>12</sup>
     * World Health Organization (2023)<sup>13</sup>
*	Geospatial vector data: United Nations Office for the Coordination of Humanitarian Affairs (UNOCHA) (2025)<sup>14

# Figure(s)

* **ghana_coverage_facets_2005_2025opt_landscape.png** - maps showing Ghana's vaccination coverage from 2005 to 2025 generated using coverage estimates; included in the manuscript appendix.

# References

1. United Nations Department of Economic and Social Affairs, Population Division. World Population Prospects. _World Population Prospects 2024_ https://population.un.org/wpp/ (2024).
2. WorldPop (www.worldpop.org - School of Geography and Environmental Science, University of Southampton; Department of Geography and Geosciences, University of Louisville; Departement de Geographie, Universite de Namur) & Center for International Earth Science Information Network (CIESIN), Columbia University (2018). Population Density - Unconstrained individual countries 2000-2020 (1km resolution). https://hub.worldpop.org/geodata/listing?id=76 (2020) doi:https://dx.doi.org/10.5258/SOTON/WP00674.
3. Shearer, F. M. et al. Global yellow fever vaccination coverage from 1970 to 2016: an adjusted retrospective analysis. _Lancet Infect. Dis._ 17, 1209–1217 (2017).
4. Ghana Health Service. Yellow Fever Data Trends. (2026).
5. Agbenu, E. et al. Use of hub cutters and the volume of sharp waste and occurrence of needle-stick injuries during 2011 mass immunization campaigns against yellow fever in Ghana: a cohort study. _Int. J. Occup. Environ. Med._ 5, 9–17 (2014).
6. Amponsa-Achiano, K., Frimpong, J. A., Barradas, D., Bandoh, D. A. & Kenu, E. Leveraging Lessons Learned from Yellow Fever and Polio Immunization Campaigns during COVID-19 Pandemic, Ghana, 2021. _Emerg. Infect. Dis._ 28, S232–S237 (2022).
7. Appiah, G. A., Babason, J. J., Dziworshie, A. Y., Abankwa, A. & Bonney, J. H. K. Is Ghana Prepared for Another Arboviral Outbreak? Evaluating the 2024 Dengue Fever Outbreak in the Context of Past Yellow Fever, Influenza, and COVID-19 Outbreaks. _Trop. Med. Infect. Dis._ 10, 196 (2025).
8. Domingo, C. et al. Long-term immunity against yellow fever in children vaccinated during infancy: a longitudinal cohort study. _Lancet Infect. Dis._ 19, 1363–1370 (2019).
9. Garske, T. et al. Yellow Fever in Africa: estimating the burden of disease and impact of mass vaccination from outbreak and serological data. _PLoS Med._ 11, e1001638 (2014).
10. World Health Organization. Weekly Epidemiological Record, 2008, vol. 83, 08 [full issue]. _Wkly. Epidemiol. Rec. Relevé Épidémiologique Hebd._ 83, 69–76 (2008).
11. World Health Organization. Global yellow fever update, 2019 – Mise à jour sur la fièvre jaune dans le monde, 2019. _Wkly. Epidemiol. Rec. Relevé Épidémiologique Hebd._ 95, 15 (2020).
12. World Health Organization. Global yellow fever update, 2020 – Mise à jour sur la fièvre jaune dans le monde, 2020. _Wkly. Epidemiol. Rec. Relevé Épidémiologique Hebd._ 96, 16 (2021).
13. World Health Organization. _Mid-Term Evaluation of the Global Strategy to Eliminate Yellow Fever Epidemics (‎EYE)‎ 2017–2026: Lessons Learned and Best Practices on the Planning and Implementation of Yellow Fever Vaccination Campaigns: Ghana Country Case Study._ 25 https://iris.who.int/server/api/core/bitstreams/452843c5-54fa-48ee-94f8-12b83224e2e5/content (2023) doi:WHO/DGO/EVL/2023.5.
14. United Nations Office for the Coordination of Humanitarian Affairs (UNOCHA). Ghana - Subnational Administrative Boundaries. _Humanitarian Data Exchange_ https://data.humdata.org/dataset/cod-ab-gha (2025).
