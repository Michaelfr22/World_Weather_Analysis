# World_Weather_Analysis

## Purpose
The objective of World Weather Analysis was to assist users in automating a Vacation Itinerary. The steps of this process includes the creation of a Weather Database of potential travel destinations and a Vacation Search of destinations that fit within user-inputted parameters. Steps are as follows:

## Weather Database
1. Generating a list of Cities (between 500-1000) closest to 2000 random coordinates on the globe.
2. Making an API that pulls current weather data for the corresponding list of cities, such as:
 - Latitiude and Longitude
 - Max Temperature
 - Percent Humidity
 - Percent Cloudiness
 - Wind Speed
 - Current Description (clear sky, overcast, etc.)

## Vacation Search
3. Considering user input commands regarding the Minimum and Maximum Temperature he/she would be comfortable traveling to at this time.
4. Updating the list of cities with those that fit within the Max and Min Temp parameters.
5. Constructing a marker-layered Map of the updated City list:

![WeatherPy_vacation_map](https://user-images.githubusercontent.com/102773052/170090736-f7971cf1-c15c-4ed4-8be3-28ac88724bbe.png)

## Vacation Itinerary
5. Presenting a sample route between four cities chosen by the user:

![WeatherPy_travel_map](https://user-images.githubusercontent.com/102773052/170091651-364e2671-51f2-4344-b0ac-4f8439e6fef0.png)

## Statistical Analysis
Using Scatter Plots, global city weather data was analyzed to represent the relationships between the variables below:
 - Latitude and Max Temperature

![Fig1](https://user-images.githubusercontent.com/102773052/170092754-df69750d-2631-4c4c-9686-2de421a3c766.png)

 - Latitude and Percent Humidity

![Fig2](https://user-images.githubusercontent.com/102773052/170092794-a521395c-df8b-41a0-898b-c39ee9680f85.png)

 - Latitide and Percent Cloudiness

![Fig3](https://user-images.githubusercontent.com/102773052/170092826-74b19592-bc4e-4416-9e5e-6eb0380dc637.png)

 - Latitude and Wind Speed

![Fig4](https://user-images.githubusercontent.com/102773052/170092880-282d3fd7-ca51-4618-8ed2-a2bbca12db26.png)

## Linear Regression
Linear Regression was implemented to compare the relationships listed above between the Northern and Southern Hemispheres:

![northern_hemi_max_temp](https://user-images.githubusercontent.com/102773052/170095989-708682b7-661c-4993-8714-15102ad41045.png) ![southern_hemi_max_temp](https://user-images.githubusercontent.com/102773052/170096016-55d0772d-fcff-4c59-89f7-1b28ee571faf.png)

![northern_hemi_humid](https://user-images.githubusercontent.com/102773052/170096239-614131ea-5e27-46df-8550-186df995dc28.png)  ![southern_hemi_humid](https://user-images.githubusercontent.com/102773052/170096283-631b05e1-c0cd-4295-b4b3-f47c579a7928.png)

![northern_hemi_cloud](https://user-images.githubusercontent.com/102773052/170096337-b88c2b31-1ac1-4ec4-bedd-037ee3658133.png)  ![southern_hemi_cloud](https://user-images.githubusercontent.com/102773052/170096363-58b47c3e-bc63-49aa-b55f-264c50930b54.png)

![northern_hemi_wind](https://user-images.githubusercontent.com/102773052/170096402-35cc347f-e214-45a7-9bfd-96e54d486669.png) ![southern_hemi_wind](https://user-images.githubusercontent.com/102773052/170096423-f71ac2c1-1d20-4425-9ed3-ece448d42c9b.png)

## Heat Map
Heat Maps were helpful when assisting users visualize the intensity of temperature across the world:

![global_heatmap](https://user-images.githubusercontent.com/102773052/170095859-bafdc25f-23ba-44f3-bb34-995851e54f75.png)



