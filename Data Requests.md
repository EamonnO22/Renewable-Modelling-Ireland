## Data Needs

The primary data we are looking for is solar production values, the finer the timescale the better, but ideally if it’s at least sub hourly. (The first dataset we got used to analyse had a value every 30 seconds, see sample below, nulls being no production). 
 ![image](https://github.com/EamonnO22/Renewable-Modelling-Ireland/assets/57291414/060cbcb1-9e29-4960-9833-b123b8eb7038)


Along with this the number of panels, theoretical max power, and the direction they are facing (just approximately south/south-west etc) will all be useful.
The next thing we need is the location of panels (as we are trying to build up a map of power production), ideally this would be an address/Eircode (The address/Eircode itself isn’t something we’d actually be storing or using long term, it’s just a means to get a location, i.e. a longitude and latitude). If you’d prefer not to link an address, an accurate approximation of the location such as street, or CSO census small area would be sufficient. We’ll also 
The small areas are used as part of the census statistics and consist of areas of approx. 100 houses. You can find the code for your small area in this link by entering EirCode:
https://visual.cso.ie/?body=entity/ima/cop/2016&boundary=C03736V04484 (Sample Image Below)

 ![image](https://github.com/EamonnO22/Renewable-Modelling-Ireland/assets/57291414/a1d4ce97-1b09-413e-a496-a6db22e1bdd2)


Along with the data and a location, other Nice to have pieces of information would be:
•	Angle/slope of the panels
•	Any obvious physical obstacles 
