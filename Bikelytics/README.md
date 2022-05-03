<p align="center">
  <a href="https://github.com/srikanthsista/Bikelytics/tree/master/Bikelytics"><img src="https://images.ctfassets.net/p6ae3zqfb1e3/3yrGaUpEy1CGdcqVuxibpk/2447292b8bcbf3afe3a080e254c01b75/Divvy-Watson-Meet-The-Bikes-Header_2.png"width="150"></a>
</p>

<h3 align="center">Bikelytics</h3>

<p align="center">
  Bikelytics is a highly-interactive dashboard that visualizes the trends and statistics in the usage of the Divvy Bike Sharing Service in the city of Chicago. It uses a variety of charts like line charts, bar charts, scatter map, flow map, etc. to depict the overall story behind the trips recorded in the year 2021.
</p>

## Preview
Bikelytics Dashboard visualizes the following charts/graphs/maps in an attempt to answer the questions that the bike service operator may face:

1. The Overall Performance of the System in the form of important metrics - Ridership Change, Customer and Subscriber Change, and Revenue Growth/Decline. (Image 1)
2. Ridership trend for the entire year correlated with the city's weather data. (Image 1)
3. Spatio-temporal Patterns using the Flowmap.blue ([1]) (Image 2)
4. Least Popular Routes and Stations
5. Revenue Trend
6. Stations Map
7. Summarized hourly incoming and outgoing stats for the station selected in the map.
8. Ridership Trend at the selected station.
9. Station Usage with respect to type and time of the day using Heat Map.
10. Distribution of the Demographics and their trends as per the ridertype, gender, and the age-group.

To see the detailed analysis, view the [demo](https://rutgersconnect-my.sharepoint.com/:v:/g/personal/rkg63_scarletmail_rutgers_edu/EfJPJp6Qy0xIj9CH_0jk71kBfxZIrWh52k7a09-2h8KC4g?e=V4Byfj) and refer to the [report]() and [slides]().

### Image 1
<img src="https://github.com/srikanthsista/Bikelytics/raw/913815b3a5060c2b3e0a62fc133ce33e9a812603/Bikelytics/screenshots/preview4.png" alt="Bikelytics Dashboard">

### Image 2
<img src="https://raw.githubusercontent.com/srikanthsista/Bikelytics/master/Bikelytics/screenshots/preview7.png" alt="Flowmap">

## Dataset
1. The trips dataset was obtained from the [Divvy Bike System Website](https://divvy-tripdata.s3.amazonaws.com/index.html). They release the ridership data on the monthly basis. It is present in the path ./rawData/ridershipData of this project.
2. The station information is available on the [Divvy Bike System Website](https://gbfs.divvybikes.com/gbfs/en/station_information.json). It is present in the path ./rawData/stationData of this project.
3. The weather data for the city of Chicago is available on the [Chicago's City Admin Website](https://data.cityofchicago.org/Parks-Recreation/Beach-Weather-Stations-Automated-Sensors/k7hf-8y75/data). It is present in the path ./rawData/weatherData of this project.
4. Some preprocessed data is already present in .static/data. This data can be created using the Python Notebook present in the root folder of the project.
## Running the Demo

After downloading the project, ```cd``` into this folder and simply run the following command:
```sh
npm start
```
The webapp will launch on the address [localhost:8080]() of your system.

## Preparing your own data
For the sake of having a running prototype, we have already preprocessed the data and loaded it into the .static/data folder.
In case you have your own data, you can put the data files into the following folders based on the dataset:
1. Ridership Data: ./rawData/ridershipData
2. Station Information: ./rawData/stationData
3. Weather Dataset: ./rawData/weatherData

Then, delete the data in the ./static/data folder, but make sure the internal folder structure is maintained.
Finally, run the Python notebook and wait for it to finish. Once done, refresh the application page, and you will see the charts created using your own data.

## Browser Support

Fully responsive and compatible with any browser on any device.

##Developer Contact

1. Rishikesh Gawade: [rishikesh.gawade@rutgers.edu](mailto:rishikesh.gawade@rutgers.edu)
2. Srikanth Sista: [srikanth.sista@rutgers.edu](mailto:srikanth.sista@rutgers.edu)
3. Dheeraj Goli: [dheeraj.goli@rutgers.edu](mailto:dheeraj.goli@rutgers.edu)

or you can raise issues on the [project repository](https://github.com/srikanthsista/Bikelytics/tree/master/Bikelytics/).

## Github Link

[Bikelytics](https://github.com/srikanthsista/Bikelytics/tree/master/Bikelytics/): https://github.com/srikanthsista/Bikelytics/tree/master/Bikelytics/

## References

[1][Flowmap.Blue for Spatio-temporal Pattern Visualization](https://flowmap.blue/)
