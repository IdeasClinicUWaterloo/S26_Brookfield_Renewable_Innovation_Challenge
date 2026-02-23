# Sustainable Energy
The mission is to improve and find more sustainable energy sources in a worldwide effort to help counter the negative effects of global warming such as climate change, loss of natural habitats, decay of the ozone layer, and many more. As various institutions look towards more sustainable and renewable sources of energy due to the fear of non-renewable energy sources becoming scarcer and in turn more expensive to use. 

Campus power usage has been rising continuously. It is important to both reduce this growth and find cleaner sources of energy. The University of Waterloo aims to further advance objective 2 of UW’s sustainability goals which is to Implement cost-effective and practical strategies to reduce or minimize growth in energy use on campus. 

## The Challenge 
Develop a feasible strategy to improve the sustainability of heating and electricity systems at the University of Waterloo. Teams will analyze how campus energy use varies with weather, and assess opportunities to integrate renewable energy sources such as geothermal and solar. The challenge evaluates how these systems can reduce emissions, manage peak demand, and improve energy efficiency within existing campus infrastructure. Teams must also consider cost, implementation timelines, and operational constraints when proposing solutions. 

Teams may present their solutions in a variety of formats, including but not limited to slide presentations, interactive websites/dashboards, physical prototypes, or simulations. 

## Potential Solutions
|Solution|Description|Resources|
|:---|:---|:---|
|Energy forecasting & load prediction|Analyze historical energy consumption and weather data to forecast peak loads and optimize energy use.|<ul><li>Energy consumption data</li><li>Weather data</li><li>Academic Calendar Archives</li><li>Website framework</li></ul>|
|Low-Emission Electricity Options Assessment|Assess low-emission electricity sources (e.g. solar, wind, hydro) by comparing cost, emissions, reliability, scalability, and campus suitability.|<ul><li>Energy consumption data</li><li>Energy data – Sustainability | University of Waterloo</li><li>System Advisor Model (SAM)</li><li>PyPSA</li><li>Interactive maps/dashboards (HTML, CSS, JavaScript)</li></ul>|
|Solar PV analysis|Evaluate potential solar PV installations across campus.|<ul><li>Map of Shade</li><li>PVWatts / pvlib</li><li>ArcGIS Pro</li></ul>|
|Geothermal & alternative heating|Evaluate renewable heating solutions for campus heating and cooling.|<ul><li>Geothermal infrastructure tour</li><li>Weather data</li><li>GHEDesigner</li></ul>|
|Scavenging energy|Reuse waste heat from wastewater, data servers, or other campus processes to supplement heating needs.|<ul><li>Facility infrastructure information</li><li>Energy Consumption data</li></ul>|

## Resources
- [University of Waterloo Campus Plan](https://uwaterloo.ca/campus-plan/university-waterloo-campus-plan)
- [Energy data | Sustainability | University of Waterloo](https://uwaterloo.ca/sustainability/our-progress/energy-data)
- [Eric D. Soulis Weather Station Value Archive](https://www.civil.uwaterloo.ca/weatherstation/data-archives/?utm_source=chatgpt.com)
- [Generator Output and Capability](https://reports-public.ieso.ca/public/GenOutputCapability/)
- [MATLAB and Simulink for Renewable Energy and Energy Storage](https://www.mathworks.com/solutions/electrification/renewable-energy-energy-storage.html)
- [ArcGIS Pro](https://www.esri.com/en-us/arcgis/products/arcgis-pro/overview)
- [Map of Shade](https://shademap.app/@43.47173,-80.54087,15.84043z,1770822733107t,0b,0p,0m)
- [Pvlib python](https://github.com/pvlib/pvlib-python)
- [PyPSA - Python for Power System Analysis](https://github.com/PyPSA/PyPSA)
- [System Advisor Model](https://sam.nlr.gov/)
- [Machine Learning Guide](https://github.com/IdeasClinicUWaterloo/Technologies-Utilized-for-Idea-s-Clinic-Challenges/blob/main/Machine_Learning/Getting_Started_with_Machine_Learning.md)

## Datasets
The following datasets are provided inside the data folder and may be useful for sustainability studies.

### Academic Calendar
This dataset contains daily academic calendar indicators used to model campus occupancy and energy demand patterns.

| Columns | Definition |
|:----------|:------------|
| Date | Calendar date of the observation (YYYY-MM-DD) |
| Weekend | Indicates whether the date falls on a weekend |
| Holiday | Indicates whether the date is a university recognized holiday |
| Lecture Day | Indicates whether lectures are scheduled on this date |
| Lecture Days in Month | Total number of lecture days in the corresponding month |

### Electricity Consumption Monthly
This dataset provides monthly electricity consumption for following campus buildings:
•	Columbia Icefield (CIF)
•	East Campus 1 (EC1)
•	East Campus 2 (EC2)
•	East Campus 3 (EC3)
•	East Campus 4 (EC4)
•	East Campus 5 (EC5)
•	East Campus Hall (ECH)
•	Research Advancement Centre 2 (RA2)
•	Research Advancement Centre (RAC)
•	UW Place (UWP)
The data may represent meter level electricity consumption rather than strictly whole building usage.

| Column | Definition |
|:-------|:-----------|
| Start Date | First day of the month for the consumption record (YYYY-MM-DD) |
| End Date | Last day of the month for the consumption record (YYYY-MM-DD) |
| Building Code | Identifier for the building (e.g., CIF, EC1, RA2) |
| Consumption (kWh) | Total electricity consumption in kwh |

### Eric D. Soulis Weather Station
This dataset contains hourly weather observations from the Eric D. Soulis Weather Station.

| Column | Definition |
|:-------|:-----------|
| Year | Year of the observation |
| Month | Month of the observation |
| Day | Day of the observation |
| Hour | Hour of the observation (0–23) |
| Temperature | Air temperature in °C |
| Solar - Incoming | Incoming solar radiation in W/m² |
| Wind Speed - Average 2.0 | Average wind speed at 2 m height in m/s |
| Wind Speed - Gust 2.0 | Wind gust at 2 m height in m/s |
| Wind Direction | Wind direction in degrees |
| RH | Relative humidity in % |