# Data Visualization 

> Scott Shriver

## Mini-Project 1

For this project I chose to work with the Metro Interstate Traffic Volume Data Set, which contains data on traffic volume on I-94 Westbound.

The features of this dataset include:

- holiday: Categorical US National holidays plus regional holiday, Minnesota State Fair
- temp: Numeric Average temp in kelvin
- rain_1h: Numeric Amount in mm of rain that occurred in the hour
- snow_1h: Numeric Amount in mm of snow that occurred in the hour
- clouds_all: Numeric Percentage of cloud cover
- weather_main: Categorical Short textual description of the current weather
- weather_description: Categorical Longer textual description of the current weather
- date_time: DateTime Hour of the data collected in local CST time
- traffic_volume: Numeric Hourly I-94 ATR 301 reported westbound traffic volume

I wanted to create charts seeing how the various features in this dataset impact the volume of traffic on I-94.

## Weather and Traffic Volume

The first chart created was a bar chart seeing what traffic volumes were for the various weather conditions recorded. The results seemed to show that traffic was the most congested when there were no weather events or it was cloud. Traffic volume was lower when there was mist, rain, or snow. Traffic was the lowest during weather events that would cause the worst visibility like fog, haze, and smoke.

## Percentage Cloud Cover and Traffic Volume

The second chart is a line graph comparing the percentage of cloud cover versus traffic volume. Traffic volume was relatively consistent regardless of coverage, which seems to line up with the previous chart. Most people are probably going onto I-94 because they have to, so the weather being overcast is unlikely to discourage them from driving.

## Amount of Snow and Traffic Volume

The last chart is a scatter plot comparing traffic volume versus the amount of snow occuring in an hour. The overwhelming majority of data points were for 0 snow recorded, so I limited the x-axis to instead focus on data points for when there was snow. The traffic volume seemed to not have a strong correlation to any amount of snow, which somewhat surprised me. Unlike with the cloud coverage, I had thought higher levels of snow might lead to less people driving.