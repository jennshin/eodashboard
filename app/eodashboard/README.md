# Providentia

The COVID-19 pandemic has had different impacts in different regions of the world. As part of the is to perform a comparative analysis of the pandemic’s economic impacts in the USA, Asia, and Europe using data from the Earth Observing (EO) Dashboard.


## Demo
Presentation: 
POC: 



## Summary
Additional information about the challenge - Introduction to "A Comparative Analysis": 
https://www.youtube.com/watch?v=ywd-W9O9W4c&list=PLO2yB4LGNlWoWP2ZzBo9jcc7_rEzP-AXX&index=5
https://www.eodashboardhackathon.org/challenges/interconnected-earth-system-impact/comparative-analysis/details

The purpose of Providentia is to investigate whether 
Investigate whether encicormrtn  proxies 
predict areas of the U.S. (and globally, in the future) that will be most affected by Coronavirus via utilizing machine learning tools. By forecasting future severity rates (via our "Hotspot Index"), the model points us towards a better balance of government intervention and economic activity to minimize the negative impact to communities.


## How We Addressed This Challenge
Developing a proxy for this challenge required finding datasets that would be able to meet the requirements, specifically (1) identifying variables that could serve as a proxy for air pollution or socioeconomic factor (2) longitudinal data that was collected before and during the pandemic, (3) geographic regions had to include a minimum of 2 out of 3 regions, ie United States, Europe and Asia.


### Proxies
To identify potential variables that would contribute to a proxy for air pollution or socioeconomic impact of covid 19, 

Finding the appropriate datasets proved to be more challenging than originally anticipated for several reasons, including:
- Data was not available for every country and in most cases, coverage of a geographic region, ie the US/Europe/Asia, was spotty 
- Factors considered included: Mobility, transportation, workforce. Energy Consumption 
- A simple model was specified to determine the empirical relationship: 
E = f(NO2, CO2, PM2, MOB, TRAN, WF, EC)

### Maps
https://wiki.openstreetmap.org/wiki/United_States
Europe is a continent on Earth at latitude 60°00′00.00″ North, longitude 15°00′00.00″ East: https://wiki.openstreetmap.org/wiki/Europe
Asia is a continent on Earth at latitude 53°00′00.00″ North, longitude 108°00′00.00″ East: https://wiki.openstreetmap.org/wiki/Asia


# Research




## Data Sources

Changes in air quality and human mobility in the USA during the COVID-19 pandemic: https://link.springer.com/article/10.1007/s42865-020-00019-0
https://ghrp.biomedcentral.com/track/pdf/10.1186/s41256-020-00167-y.pdf*




## Literature
S. Chowdhury et al., Indian annual ambient air quality standard is achievable by completely mitigating emissions from household sources. Proc. Natl. Acad. Sci. U.S.A. 116, 10711–10716 (2019).
Zander S. Venter, Kristin Aunan, Sourangsu Chowdhury, Jos Lelieveld

COVID-19 lockdowns cause global air pollution declines: https://www.pnas.org/content/117/32/18984

Venter, Z., Aunan, K., Chowdhury, S., & Lelieveld, J. (2020, August 11). COVID-19 lockdowns cause global air pollution declines. Retrieved March 05, 2021, from https://www.pnas.org/content/117/32/18984

Air pollution. (n.d.). Retrieved March 06, 2021, from https://www.who.int/news-room/air-pollution

COVID-19 lockdowns cause global air pollution declines Zander S. Venter, Kristin Aunan, Sourangsu Chowdhury, Jos Lelieveld Proceedings of the National Academy of Sciences Aug 2020, 117 (32) 18984-18990; DOI: 10.1073/pnas.2006853117

Xiuying Zhang, Wuting Zhang, Xuehe Lu, Xuejun Liu, Dongmei Chen, Lei Liu, Xianjin Huang, "Long-term trends in NO2 columns related to economic developments and air quality policies from 1997 to 2016 in China", Science of The Total Environment, Volume 639, 2018, Pages 146-155,ISSN 0048-9697, https://doi.org/10.1016/j.scitotenv.2018.04.435.

Bernardo Beckerman, Michael Jerrett, Jeffrey R Brook, Dave K Verma, Muhammad A Arain, Murray M Finkelstein, Correlation of nitrogen dioxide with other traffic pollutants near a major expressway, Atmospheric Environment, Volume 42, Issue 2, 2008, Pages 275-290, ISSN 1352-2310, https://doi.org/10.1016/j.atmosenv.2007.09.042.

Jianhui Jiang, Jianying Zhang, Yangwei Zhang, Chunlong Zhang, Guangming Tian, Estimating nitrogen oxides emissions at city scale in China with a nightlight remote sensing model, Science of The Total Environment, Volume 544, 2016, Pages 1119-1127, ISSN 0048-9697, https://doi.org/10.1016/j.scitotenv.2015.11.113.

Sulaman Muhammad, Xingle Long, Muhammad Salman, COVID-19 pandemic and environmental pollution: A blessing in disguise?, Science of The Total Environment, Volume 728, 2020, 138820, ISSN 0048-9697, https://doi.org/10.1016/j.scitotenv.2020.138820.

Mar Viana, Pieter Hammingh, Augustin Colette, Xavier Querol, Bart Degraeuwe, Ina de Vlieger, John van Aardenne, Impact of maritime transport emissions on coastal air quality in Europe, Atmospheric Environment, Volume 90, 2014, Pages 96-105, ISSN 1352-2310, https://doi.org/10.1016/j.atmosenv.2014.03.046.



## Resources
* https://race.esa.int/
* https://eurodatacube.com/
* https://sentinel.esa.int/web/sentinel/user-guides/sentinel-1-sar/applications/maritime-monitoring
* https://labo.obs-mip.fr/multitemp/visualizing-shipping-lanes-from-sentinel-1/
* https://cockpit.hub.eox.at/storage/uploads/edc-editor/Euro_Data_Cube_summary_brochure.pdf
* https://docs.sentinel-hub.com/api/latest/data/sentinel-5p-l2/#available-bands-and-data
* https://docs.sentinel-hub.com/api/latest/data/sentinel-3-olci-l1b/


