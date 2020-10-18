# Weather_induced_hazards_and_COVID-19

A decision support tool to help governments plan for how to respond to the impact of an extreme weather event on the severity of COVID symptoms within affected populations. 


#Description of the solution developed; 
We have developed an AI model of future risk levels of severe Covid-19 cases with a lead time of 4-5 days based on air pollution forecasts from Copernicus Atmosphere Monitoring Service.  Risk assessment will be based on the definition provided in IPCC [2012]:
Risk = Hazard x Vulnerability x Exposure

We translate the variables specific to a defined location as follows:
Hazard: Number of infected people
Exposure: Number of people living in that area (population)
Vulnerability: Particulate matter smaller than 2.5µm (PM2.5)

Research has shown that air pollution, in particular elevated PM2.5 levels are linked to the severity and thus death rate of Covid-19 cases [e.g. Wu et al., 2020].

