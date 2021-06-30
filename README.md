# Providentia
 
## ----Summary----
The COVID-19 pandemic has had different impacts in different regions of the world. As part of the is to perform a comparative analysis of the pandemic’s economic impacts in the USA, Asia, and Europe using data from the Earth Observing (EO) Dashboard.
Presentation: 
Dashboard MVP/POC:

### The Challenge
The COVID-19 pandemic has had different impacts in different regions of the world, and these impacts depend on a number of different factors. The challenge is to perform a comparative analysis of the pandemic’s economic impacts in urban areas for the USA, Asia, and Europe using the EO Dashboard. 
 
The goal of this challenge is to develop 2-3 globally applicable “proxies” that characterize the impact of the pandemic on air quality and/or economic activities and answer the question: How can you integrate different proxies into an integrated economic indicator? The challenge also required using  Earth observation data from at least two of the three regions for the developed proxies, ensuring the same assessment can be performed in the USA/Europe/Asia.
 
Additional information about the challenge - Introduction to "A Comparative Analysis": 
* [https://www.youtube.com/watch?v=ywd-W9O9W4c&list=PLO2yB4LGNlWoWP2ZzBo9jcc7_rEzP-AXX&index=5](https://www.youtube.com/watch?v=ywd-W9O9W4c&list=PLO2yB4LGNlWoWP2ZzBo9jcc7_rEzP-AXX&index=5)
* [https://www.eodashboardhackathon.org/challenges/interconnected-earth-system-impact/comparative-analysis/details](https://www.eodashboardhackathon.org/challenges/interconnected-earth-system-impact/comparative-analysis/details)
 
### The Solution
Providentia is an integrated dashboard enhancement of the original EO Dashboard and provides insights into the environmental and economic impacts of Covid-19, which are presented using proxies and interactive visualizations. 

 
***How We Addressed This Challenge 
# Project Demo
 
## Presentation
<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vTs4qEYVoHzCXkBtswyI9V0vcy9NsR1nVr9vOMf6ScXjH3vvMlGdNn3_at9InVbEmN8gS2UGy5M9fKe/embed?start=false&loop=false&delayms=10000" frameborder="0" width="480" height="299" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>
 
https://docs.google.com/presentation/d/152ykl3PLpPjZ5JOUMqkXIuALZaXDmnRQoxmeYfY5Zp8/edit#slide=id.ge384a17372_0_0
 
<iframe src="https://yuad-my.sharepoint.com/personal/jennifer_shin_yu_edu/_layouts/15/Doc.aspx?sourcedoc={ffb1f5b1-f5b2-4926-9999-fe2610f03082}&amp;action=embedview&amp;wdAr=1.7777777777777777" width="350px" height="221px" frameborder="0">This is an embedded <a target="_blank" href="https://office.com">Microsoft Office</a> presentation, powered by <a target="_blank" href="https://office.com/webapps">Office</a>.</iframe>
 
## Dashboard MVP/POC:
 
 
 
***
# How I Addressed This Challenge

COVID-19 has undoubtedly had an effect on both the environment and society, but identifying the right variables to measure this effect is a complex problem. Showing the impact of covid-19 requires finding data that is consistent, accurate and comparable across regions. The data also had to cover a minimum of 2 periods, primarily before and during the pandemic, and across the regions of interest. 

Initial Tasks:
**Task 1**: To identify potential variables that would contribute to a proxy for air pollution or socioeconomic impact of covid 19.
Specifically, identifying the variables that measures the air quality (i.e. greenhouse gas, GHG, and NO2) and/or socioeconomic impact by using simple proxy indicators derived from EO data.  
** Task 2:** Specify a model using these variables
** Task 3**  Find data that can be used in the model 
** Task 4**: Calculate measurements for a representative and strategically selected sample of areas-of-interest, comparing the impact between two continents

TASK 1
As a first step, we began by analyzing the United Nations Sustainability Development Goals, which currently has been widely adopted and includes measurements relevant for this project, specifically economic, socioeconomic and environmental variables.

GOAL 1: End poverty in all its forms everywhere
GOAL 2: End hunger, achieve food security and improved nutrition and promote sustainable agriculture
GOAL 3: Ensure healthy lives and promote well-being for all at all ages
GOAL 4: Ensure inclusive and equitable quality education and promote lifelong learning opportunities for all
GOAL 5 Achieve gender equality and empower all women and girls
GOAL 6: Ensure availability and sustainable management of water and sanitation for al
GOAL 7  Ensure access to affordable, reliable, sustainable and modern energy for all
GOAL 8: Promote sustained, inclusive and sustainable economic growth, full and productive employment and decent work for all
GOAL 9: Build resilient infrastructure, promote inclusive and sustainable industrialization and foster innovation
GOAL 10: Reduce inequality within and among countries
GOAL 11: Make cities and human settlements inclusive, safe, resilient and sustainable
GOAL 12: Ensure sustainable consumption and production patterns
GOAL 13: Take urgent action to combat climate change and its impacts
GOAL 14: Conserve and sustainably use the oceans, seas and marine resources for sustainable development
GOAL 15:  Protect, restore and promote sustainable use of terrestrial ecosystems, sustainably manage forests, combat desertification, and halt and reverse land degradation and halt biodiversity loss
GOAL 16: Promote peaceful and inclusive societies for sustainable development, provide access to justice for all and build effective, accountable and inclusive institutions at all levels
GOAL 17:  Strengthen the means of implementation and revitalize the Global Partnership for Sustainable Development
Given the limited amount of time available, including all 17 UN SDG was infeasible and would present a risk to being able to make progress on the project. Instead the list was reviewed to identify the goals that are the most relevant to our objective. Goals that did not seem achievable in the short term (ie SDG 1: end poverty…) or vague and thereby difficult to quantify (Eg SDG 16) were not included.

TASK 2 
The selected SDG, specifically SDG 3, SDG 4, SDG 6, SDG 7, SDG 12, were used to develop an initial model  to represent the empirical relationship, specifically:
econ = f(H, EDUC, ERG, ENV, PROD, WS)
Where 
H represents variables that measure access to or impact on health, 
EDUC represents variables that can be used to measure the access or impact of educational systems or programs, 
ENG represents variables that measure energy production or consumption, 
ENV represents variables that can be used to measure changes in the environment,  
PROD represents variables that measure production and consumption patterns, and 
WS represents variables that can be used to measure access to or quality of water management or sanitation
An alternative model, which directly capture the variables of interest outline in the challenge, was also specified as follows: 
ECON = F(ENV, SOCIO, COVID) where ENV, ECON, SOCIO, and COVID represent the environment, economic, socioeconomic, and covid-19 variables.



TASK 3 
How can you develop an integrated economic composite indicator by integrating air quality / air pollution and/or the developed proxies comparatively across the  regions in the US, Europe, and Asia. Including Japan?

Developing a proxy for this challenge required finding datasets that would be able to meet the requirements, specifically (1) identifying variables that could serve as a proxy for air pollution or socioeconomic factor (2) finding longitudinal data that was collected collected on at least 2 points in time, ie before and during the pandemic, (3) geographic regions had to include a minimum of 2 out of 3 regions, i.e. United States, Europe and Asia.
Finding the appropriate datasets proved to be more challenging than originally anticipated for several reasons, including:
*Data is not available for every country and in most cases, coverage of a geographic region, ie the US/Europe/Asia, was spotty
*Economic data is typically not used in real-time and therefore update information is not readily available  
*Data for Government statistics is typically aggregated by year, which presents a challenge to use since many of the stay at home orders began well into 2020

Over 30 potential datasets were considered for this project, but most did meet at least one of the following requirements: 
 (1) the dataset contains variables of interest
(2) the dataset contains the dates of interest
(3) the dataset contains the regions of interest 
(4) the dataset is of sufficient quality

A few of these datasets have been selected to illustrate these issues 

econ = f(H, EDUC, ERG, ENV, PROD, WS)
ECON = F(ENV, SOCIO, COVID) where ENV, ECON, SOCIO, and COVID represent the environment, economic, socioeconomic, and covid-19 variables.
 
## Potential Variables : Environmental Factor
### ENV - Environment: Air Pollution - Nitrogen Dioxide
Nitrogen Dioxide (NO2) is a pollutant, the primary sources being the burning of fossil fuels, automobiles, and industry.
Aerosol Index, 
Carbon Monoxide
  https://github.com/owid/co2-data


 https://sedac.ciesin.columbia.edu/data/collections/browse 
Data publisher's source	United Nations Educational, Scientific, and Cultural Organization (UNESCO) Institute for Statistics.
Link	http://data.worldbank.org/data-catalog/world-development-indicators
M


## Potential Variables : Economic Factors
Assessing the economic impact will be dependent on the national statistics that is made available by governments.Measuring the impact of covid-19 on the economy would be a relatively straight forward process in a world with perfect information (ie if the financial transactions of individuals and businesses were publicly available or known), but this information is typically considered private and unavailable to researchers.  Hence,  traditional economic measures, i.e. GDP, were considered for the development of the proxies. 
GDP, which represents the amount of goods and services produced in a country during a certain period of time, is commonly used to evaluate the performance of economy. GDP can be useful for describing patterns in the economy historically (eg whether an economy is in boom or bust or evaluating whether debts are higher or lower than other periods) , but this variable may not be an optimal choice for meeting the objective. Specifically gdp has not historically been evaluated for its accuracy in capturing economic patterns, particularly  in relation to other factors, or socioeconomic factors, such as issues of inequality or happiness (e.g. https://www.worldfinance.com/strategy/why-gdp-is-no-longer-the-most-effective-measure-of-economic-success). Furthermore, GDP is a generalized measured that relies on other proxies of economic performance, which could present an issue when developing a statistical model. However, given  the time limitations and difficulty finding data that meet the requirements outlined above, GDP was the most feasible economic indicator to validate the performance of the proxy.  



### Potential Variables: Socioeconomic Factors
Environmental factors can directly and indirectly impact our economy and society. Natural disasters can destroy crops in the short terms and influence food production in the long term depending on the damage sustained by land and infrastructure. 
Other variables are harder to pin down and in many cases, the direction of the relationship may not be discernable. In particular, we may have data that 
The data could show that as environmental variables changed, socioeconomic variables changed as well. Covid-19 related variables, such as business closures and government policies, may have occurred just prior to other changes, but we cannot assume that the former led to the latter. For instance, if we include government policies in 

### H
Food and Agriculture: Crop Yields
Organization of the United Nations (FAO) (2020): Crop statistics are recorded for 173 products, covering the following categories: Crops Primary, Fibre Crops Primary, Cereals, Coarse Grain, Citrus Fruit, Fruit, Jute Jute-like Fibres, Oilcakes Equivalent, Oil crops Primary, Pulses, Roots and Tubers, Treenuts and Vegetables and Melons. Data are expressed in terms of area harvested, production quantity and yield. The main data source is official statistics from FAO member countries, collected either through annual production questionnaires (APQ) distributed to countries, from national publications (Yearbooks and Pocketbooks) or from official country websites. The source data can originate from surveys, administrative data and estimates based on expert observations.  http://www.fao.org/faostat/en/?#data/
[ISSUE: Data only available up to 2019]

### WS
Water Management & Sanitation
* WHO/UNICEF Joint Monitoring Programme (JMP) for Water Supply and Sanitation: https://washdata.org/data
Safely managed sanitation is improved facilities which are not shared with other households and where excreta are safely disposed in situ or transported and treated off-site. Improved sanitation facilities are designed to hygienically separate excreta from human contact. They include flush to piped sewer system, septic tanks or pit latrines; ventilated improved pit latrines, composting toilets or pit latrines with slabs.
[ISSUE: Data is not available for 2021 ]

 ###EDUC
Data on education presented a challenge due to the variability in schools systems, schools year, reporting requirement and overall  data collection across regional. Given that this information is  typically available by year, rather than monthly or daily, using this variable raised concerns regarding how it may change the accuracy or reliability of the model. Hence, this was not included in the model.
[ISSUE: Data is not available for 2021 ]

### ENG
Due to time constraints, this variable was not included in the model. Given that energy consumption is tied to other activities captured in the model, removing this variable could  increase the reliability of the overall model. In addition, due to the time constants, excluding the variable allowed more time to be spent on other important aspects of this effort, specifically reporting the results and revising the code. 
[ISSUE: potential risks to reliability of the model & time constraints ]

### PROD 
Industrial Production: https://tradingeconomics.com/country-list/industrial-producti
 

 ###Covid19
OxCGRT collects publicly available information on indicators of government response. These indicators take policies such as school closures, travel bans, etc. and record them on an ordinal scale; the remainder are financial indicators such as fiscal or monetary measures.
Stringency, which represents the government response during the pandemic, was used as a proxy for the impact of covid19


### Other Indicators

Industrial Production: https://tradingeconomics.com/country-list/industrial-production
SDG Indicators Database: https://unstats.un.org/sdgs/indicators/database/
* Black Marble Night-time Imagery: https://viirsland.gsfc.nasa.gov/Products/NASA/BlackMarble.html


—————————
*** TASK 4 ***
 ## Proxies
 A composite indicator is formed when individual indicators are compiled into a single index, on the basis of an underlying model of the multidimensional concept that is being measured (OECD, Glossary of Statistical Terms.
To account for the lack of data available for developing the proxy, the enhanced EO Dashboard incorporates a standard composite (quantitative) proxy, an alternative comprehensive (mobility metric) proxy, and proposes a combined solution for future development. 
 
## PROXY 1: Model

Variable Selection: 
Environmental Factors:  
Economic Factors: GDP
Covid-19 Factors:  OxCGRT

 
The performance of the proxy was evaluated using a linear regression model with economic performance as the dependent variable. 

## PROXY 2: Mobility Based Metric
Given the number of obstacles and limited amount of data available for selecting variables for our proxy calculation, a single data source was selected to create the second proxy, which presents the individual measurements visually.
By selecting the variables in the proxy calculation from a single dataset, specifically the Community Mobility Report, reduces the varying amount of bias that can exist when data is collected differently for each variable. The Community Mobility Reports aim to provide insights into what has changed in response to policies aimed at combating COVID-19. The reports chart movement trends over time by geography, across different categories of places such as retail and recreation, groceries and pharmacies, parks, transit stations, workplaces, and residential.
Hence, the data covers a range of locations, which meets the requirements stated above and captures the impact  both individuals and businesses during covid-19. Specifically, we can reasonable assume  that covid motivated factors, such as stay at home orders, would be captured in the report . For instance, if an employee were to stay at home, then this information   would appear under residential whereas if the employee were to go to work, we would expect this to appear under workplaces)
In addition to displaying then different variables from the mobility data, a composite metric was calculated using the following formula: Average(retail, grocery, parks)/Average(transit, workplace, residential) 


retail_and_recreation_percent_change_from_baseline
grocery_and_pharmacy_percent_change_from_baseline
parks_percent_change_from_baseline
transit_stations_percent_change_from_baseline
workplaces_percent_change_from_baseline
residential_percent_change_from_baseline

## Tableau

## PROXY 3: Visual Proxy
Due to the limited amount of data available, the proposed solution incorporates visual representations that show the level of air pollution as well as changes in society, including economic and societal impacts of the pandemic.
The maps were created using Google Earth Engine for several environmental variables for air pollution, specifically Aerosol Index, Carbon Monoxide, Nitrogen Dioxide, 

In addition to being able to see the changes in air pollution, the maps offer the  ability to see changes in the environment, specifically changes in vegetation,

Given more time, the map would be 


* Black Marble Night-time Imagery: https://viirsland.gsfc.nasa.gov/Products/NASA/BlackMarble.html
 
## Google Earth Engine
 SP5 NO2

### Economic Factors
https://sedac.ciesin.columbia.edu/data/collections/browse 
Data publisher's source	United Nations Educational, Scientific, and Cultural Organization (UNESCO) Institute for Statistics.
Link	http://data.worldbank.org/data-catalog/world-development-indicators






 https://jshin.users.earthengine.app/view/forest
 https://brandeis.box.com/s/48tl03r1i8kgihxtrf6qvrbdptgvzegg



***
# How I Developed This Project
## Software & Tools: 
Excel
Tableau
R
Python
Google Earth Engine


* United States is a country in North America at latitude 41°09′00.00″ North, longitude 96°30′00.00″ West: https://wiki.openstreetmap.org/wiki/United_Statesc
Google Earth:  Map.setCenter(-65.27, 24.11, 4);
* Europe is a continent on Earth at latitude 60°00′00.00″ North, longitude 15°00′00.00″ East: https://wiki.openstreetmap.org/wiki/Europe Google Earth:  Map.setCenter(-99.229, 40.413, 5);
* Asia is a continent on Earth at latitude 53°00′00.00″ North, longitude 108°00′00.00″ East: https://wiki.openstreetmap.org/wiki/Asia
 Google Earth:  Map.setCenter(88, 55, 3);
 
***
# How I Used Space Agency Data in This Project

## Environmental Variables were selected from EO data, specifically: 
* Health and Air Quality Data Pathfinder: https://earthdata.nasa.gov/learn/pathfinders/health-and-air-quality-data-pathfinder
* Water Quality Data Pathfinder: https://earthdata.nasa.gov/learn/pathfinders/water-quality-data-pathfinder
* NASA Air Quality Data: https://earthdata.nasa.gov/learn/pathfinders/health-and-air-quality-data-pathfinder
	• The TROPOspheric Monitoring Instrument (TROPOMI) aboard Sentinel-5P, is a European Space Agency (ESA) Mission, The ESA TROPOMI NO2 provides additional information this Level 2 data  product.


## Agricultural Variables were selected from EO data, specifically: 
* Agricultural and Water Resources Data Pathfinder: https://earthdata.nasa.gov/learn/pathfinders/agricultural-and-water-resources-data-pathfinder
* Agriculture - Vegetation: https://earthdata.nasa.gov/learn/pathfinders/agricultural-and-water-resources-data-pathfinder/vegetation-data


COVID-19 Data Pathfinder: https://earthdata.nasa.gov/learn/pathfinders/covid-19
 
  
 

***
# Data and Resources
Although I successfully incorporate my work into the original dashboard, I ran into  a number of issues when I tried to launch the application on AWS and this prevented me from including a full description of the project on the official submission page.
First, running the dashboard locally required working past a number of glitches and ignoring a number of error messages regarding depreciated packages. Eventually I was able to  run the dashboard locally, I came across a number of obstacles trying to run the application on AWS and  in the end, I was unable to run the application on the server. 
Although the code are available in the GitHub repository,  I assumed that the judges would not have time to run the code for each individual submission and therefore I felt compelled to get the code to run.
In the future, I hope the organizers will test and optimIze the core prior to running this type of challenge as it negatively impacts the participants experience. Alternatively, I recommend  not including the integration section of the final submission form unless the code is up to date or at the very least does not require troubleshoot error messages. 

***
# Data and Resources

## Other Data Sources

* World Bank – World Development Indicators:  https://databank.worldbank.org/home.aspx

* WHO/UNICEF Joint Monitoring Programme (JMP) for Water Supply and Sanitation: https://washdata.org/data
 
*  Long Term Unemployment Rate | America: 
https://tradingeconomics.com/country-list/long-term-unemployment-rate?continent=america

* The WHO/UNICEF Joint Monitoring Programme (JMP) is the custodian of global data on Water Supply, Sanitation and Hygiene (WASH): https://washdata.org/data

* Black Marble Night-time Imagery: https://viirsland.gsfc.nasa.gov/Products/NASA/BlackMarble.html
   
 https://raw.githubusercontent.com/owid/owid-datasets/master/datasets/Attainable%20yields%20(Mueller%20et%20al.%202012)/Attainable%20yields%20(Mueller%20et%20al.%202012).csv
 
 Tsai YH, Stow D, Chen HL, Lewison R, An L, Shi L. Mapping Vegetation and Land Use Types in Fanjingshan National Nature Reserve Using Google Earth Engine. Remote Sensing. 2018; 10(6):927. https://doi.org/10.3390/rs10060927
 
Tsai, Yu H., Douglas Stow, Hsiang L. Chen, Rebecca Lewison, Li An, and Lei Shi. 2018. "Mapping Vegetation and Land Use Types in Fanjingshan National Nature Reserve Using Google Earth Engine" Remote Sensing 10, no. 6: 927. https://doi.org/10.3390/rs10060927

Robinson NP, Allred BW, Jones MO, Moreno A, Kimball JS, Naugle DE, Erickson TA, Richardson AD. A Dynamic Landsat Derived Normalized Difference Vegetation Index (NDVI) Product for the Conterminous United States. Remote Sensing. 2017; 9(8):863. https://doi.org/10.3390/rs9080863
## Literature 
 
B. Beckerman,  M. Jerrett, J. R Brook, D. K Verma, M. A Arain, M. M Finkelstein, Correlation of nitrogen dioxide with other traffic pollutants near a major expressway, Atmospheric Environment, Volume 42, Issue 2, 2008, Pages 275-290, ISSN 1352-2310, https://doi.org/10.1016/j.atmosenv.2007.09.042.
 
C.L. Archer, G. Cervone, M. Golbazi et al. Changes in air quality and human mobility in the USA during the COVID-19 pandemic. Bull. of Atmos. Sci.& Technol. 1, 491–514 (2020).
 
E. Pepe et al., COVID-19 outbreak response: A first assessment of mobility changes in Italy following national lockdown. medRxiv:2020.03.22.20039933 (7 April 2020).
 
J. Jiang, Jianying Zhang, Yangwei Zhang, Chunlong Zhang, Guangming Tian, Estimating nitrogen oxides emissions at city scale in China with a nightlight remote sensing model, Science of The Total Environment, Volume 544, 2016, Pages 1119-1127, ISSN 0048-9697.
 
K. Chen, M. Wang, C. Huang, P. L. Kinney, P. T. Anastas, Air pollution reduction and mortality benefit during the COVID-19 outbreak in China. Lancet Planet. Health 4, e210–e212 (2020).
 
M. Viana, P. Hammingh, A. Colette, Xavier Querol, Bart Degraeuwe, Ina de Vlieger, John van Aardenne, Impact of maritime transport emissions on coastal air quality in Europe, Atmospheric Environment, Volume 90, 2014, Pages 96-105.
 
M.O. Román, Z. Wang, Q. Sun, V. Kalb, S.D. Miller, A. Molthan, L.  Schultz, J. Bell, E.C. Stokes, B. Pandey and K.C. Seto et al. 2018. NASA's Black Marble nighttime lights product suite. Remote Sensing of Environment, 210, pp.113-143.
 
N. G. G. Domingo, S Balasubramanian, S. K. Thakrar, M. A. Clark, P J. Adams, J D. Marshall, N Z. Muller, S. N. Pandis, S. Polasky, A. L. Robinson, C. W. Tessum, D. Tilman, P. Tschofen, J. D. Hill, Proceedings of the National Academy of Sciences May 2021, 118 (20) e2013637118; DOI: 10.1073/pnas.2013637118
 
P. Sicard et al., Amplified ozone pollution in cities during the COVID-19 lockdown. Sci. Total Environ. 735, 139542 (2020).
 
S. Muhammad, X. Long, M. Salman, COVID-19 pandemic and environmental pollution: A blessing in disguise?, Science of The Total Environment, Volume 728, 2020, 138820, ISSN 0048-9697, https://doi.org/10.1016/j.scitotenv.2020.138820.
 
S. Chowdhury et al., Indian annual ambient air quality standard is achievable by completely mitigating emissions from household sources. Proc. Natl. Acad. Sci. U.S.A. 116, 10711–10716 (2019).
 
T. Hale, S. Webster, A. Petherick, T. Phillips, B. Kira, Oxford COVID-19 Government Response Tracker. https://www.bsg.ox.ac.uk/research/research-projects/coronavirus-government-response-tracker#data. 
 
X. Zhang, Wuting Zhang, Xuehe Lu, Xuejun Liu, Dongmei Chen, Lei Liu, Xianjin Huang, "Long-term trends in NO2 columns related to economic developments and air quality policies from 1997 to 2016 in China", Science of The Total Environment, Volume 639, 2018, Pages 146-155,ISSN 0048-9697
 
Z. Venter, K. Aunan, S. Chowdhury & J. Lelieveld. (2020, August 11). COVID-19 lockdowns cause global air pollution declines. Proceedings of the National Academy of Sciences Aug 2020, 117 (32) 18984-18990
 
Changes in air quality and human mobility in the USA during the COVID-19 pandemic: https://link.springer.com/article/10.1007/s42865-020-00019-0
 
Black Marble Night-time Imagery.  Retrieved June 26, 2021, https://viirsland.gsfc.nasa.gov/Products/NASA/BlackMarble.html

OECD, Glossary of statistical terms. Retrieved June 26, 2021, from http://stats.oecd.org/glossary/index.htm

Air pollution. (n.d.). Retrieved June 26, 2021, from https://www.who.int/news-room/air-pollution
 
NASA's Black Marble - Advancing the Science of Earth at Night.  Retrieved June 26, 2021, https://blackmarble.gsfc.nasa.gov/
 
Changes in air quality and human mobility in the USA during the COVID-19 pandemic: https://link.springer.com/article/10.1007/s42865-020-00019-0
https://ghrp.biomedcentral.com/track/pdf/10.1186/s41256-020-00167-y.pdf*

 
 
## Data Resources

* https://developers.google.com/earth-engine/datasets/catalog
* https://race.esa.int/
* https://eurodatacube.com/
* https://sentinel.esa.int/web/sentinel/user-guides/sentinel-1-sar/applications/maritime-monitoring
* https://labo.obs-mip.fr/multitemp/visualizing-shipping-lanes-from-sentinel-1/
* https://cockpit.hub.eox.at/storage/uploads/edc-editor/Euro_Data_Cube_summary_brochure.pdf
* https://docs.sentinel-hub.com/api/latest/data/sentinel-5p-l2/#available-bands-and-data
* https://docs.sentinel-hub.com/api/latest/data/sentinel-3-olci-l1b/
 * https://tradingeconomics.com/country-list/industrial-production
* https://earthdata.nasa.gov/learn/pathfinders/covid-19
* https://sedac.ciesin.columbia.edu/data/collections/browse
* https://data.worldbank.org/indicator

Data on CO2 and Greenhouse Gas Emissions by Our World in Data: https://github.com/owid/co2-data

https://sedac.ciesin.columbia.edu/data/collections/browse

