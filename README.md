# Renewable-Modelling-Ireland
## A repository that will contain interesting results and visuals while analysing Ireland's renewable energy resources

This Redme contains a sample of the data we hope to work with, along with some charts. This dataset was provided to us by a homeowner with two installed sets of solar panels, one south West facing, and one north east facing. The dataset contains a time stamp (at 30 second intervals) and the power production for that 30 second interval. Here is a sample day averaged hourly, showing the variable nature of it.
![Single Day](https://github.com/EamonnO22/Renewable-Modelling-Ireland/assets/57291414/7f6bfd37-00de-4141-9e88-0ce716882571)

In these images the hourly average is shown for four different months of the year (A full year is available, but four sample months are selected for ease of visualisation. 

For individual homes this allows us to look at specific patterns and forecasts their specific energy use. 
One interesting pattern in these is for the afternoon period, instead of the average showing a smooth trend, there are sharp jumps, which perhaps may be due to an obstacle partially blocking the direct sun at those times.

![image](https://github.com/EamonnO22/Renewable-Modelling-Ireland/assets/57291414/07c41f95-57d6-451c-9c18-81c46e9a8ea5)

We can also view the range of likely values over the duration of the month, these charts show for two sample months for the south facing panels, the average hourly production and a standard deviation either side.
![image](https://github.com/EamonnO22/Renewable-Modelling-Ireland/assets/57291414/16693673-9d17-4d08-b5dd-353c79c517aa)

Along with studying the typical production we will hope to forecast and predict solar production, both for panels at new locations, and also predicting hours/days ahead in time. For example we will work towards produce accurate forecasts at a high time resolution, similar to this:
![image](https://github.com/EamonnO22/Renewable-Modelling-Ireland/assets/57291414/1c4bb8c2-b8bc-44f7-b03c-68abe049b24f)


For this we will be comparing production value to a range of measuremetns regarding weather/environmental/local topology. For example, using the above the data, I compared it to Solar Irridiance values provided by met eireann, which are often used as the indication of solar potential (I don't have a location for these panels, therefore I used a Met station in the midlands which may not be the closest). While there is a generally upward trend and the low values are correctly predicted (correlation = 0.6) , there is a wide range of variability on higher levels of solar irridiance, therefore being able to study the variation will be an important part of this.
![image](https://user-images.githubusercontent.com/57291414/234743758-0c9945ba-6e3d-4c59-b665-9234f28eb8f7.png)
