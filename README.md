# Renewable-Modelling-Ireland
## A repository that will contain interesting results and visuals while analysing Ireland renewable energy resources

This Redme contains a sample of the data we hope to work with, along with some charts. This dataset was provided to us by a homeowner with two installed sets of solar panels, one south West facing, and one north east facing. The dataset contains a time stamp (at 30 second intervals) and the power production for that 30 second interval.
In these images the hourly average is shown for four different months of the year (A full year is available, but four sample months are selected for ease of visualisation. 

For individual homes this allows us to look at specific patterns and forecasts their specific energy use. 
One interesting pattern in these is for the afternoon period, instead of the average showing a smooth trend, there are sharp jumps, which perhaps may be due to a partial obstacles blocking the sun at those times.

![NE Hourly Averages](https://user-images.githubusercontent.com/57291414/234742406-da7ca2fd-da44-4d3c-b089-902e4d84a4ae.png)
![South West Hourly Average](https://user-images.githubusercontent.com/57291414/234742421-a32d726d-b1cc-460e-aa7e-dfd6e91d1610.png)

We can also view the range of likely values over the duration of the month, these charts show for two sample months for the south facing panels, the average hourly production and a standard deviation either side.
![September Averages](https://user-images.githubusercontent.com/57291414/234743853-d07a6671-a105-43e1-b63e-a59e3de52d06.png)
![June With Range](https://user-images.githubusercontent.com/57291414/234742840-21bbdcdb-df5f-47b7-8bb4-1c84c2bda657.png)

Along with studying the typical production we will hope to forecast and predict solar production, both for panels at new locations, and also predicting hours/days ahead in time. For this we will be comparing production value to a range of measuremetns regarding weather/environmental/local topology. For example, using the above the data, I compared it to Solar Irridiance values provided by met eireann, which are often used as the indication of solar potential (I don't have a location for these panels, therefore I used a Met station in the midlands which may not be the closest). While there is a generally upward trend and the low values are correctly predicted (correlation = 0.6) , there is a wide range of variability on higher levels of solar irridiance, therefore being able to study the variation will be an important part of this.
![image](https://user-images.githubusercontent.com/57291414/234743758-0c9945ba-6e3d-4c59-b665-9234f28eb8f7.png)
