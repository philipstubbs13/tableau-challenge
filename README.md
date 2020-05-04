# Citi Bike Analytics and Insights

A data visualization project that helps publicize and share information about the New York Citi Bike program from March 2019 to March 2020. Built using Tableau.

## Overview

The New York Citi Bike program is the largest bike sharing program in the United States. Since 2013, the Citi Bike program has implemented a robust infrastructure for collecting data on the program's utilization. Through the team's efforts, each month bike data is collected, organized, and made public on the Citi Bike webpage. For more information about the program, see <https://en.wikipedia.org/wiki/Citi_Bike>.

## About the Tableau story board

Link to Tableau story board: <https://public.tableau.com/profile/phil.stubbs#!/vizhome/CitiBikeAnalytics_15879541754520/NewYorkCitiBikeAnalyticsandInsights>

Despite all the data that is available on the program, there are still many unanswered questions regarding the direction in which the program should go. To help answer some of those questions, a Tableau story board was put together. The purpose of this storyboard is to not only help publicize the data but also to help find ways to improve the bike program in the future. Each section of the story board starts with a brief analysis followed by a dashboard that includes visualizations related to the analysis.

The story board analyzes and visualizes Citi bike data from March 2019 to March 2020.

## Analysis and Insights for the Data

An analysis on the phenomenons uncovered by the data is available within the Tableau story board. Each dashboard is accompanied by a short analysis.

### Tableau Dashboards

Each section of the story board includes a dashboard.

Here are links to each of the individual Tableau dashboards created for this project:

* [Most Popular Ride Times Dashboard](https://public.tableau.com/profile/phil.stubbs#!/vizhome/CitiBikeAnalytics_15879541754520/MostPopularRideTimesDashboard)
* [Start Station Popularity Dashboard](https://public.tableau.com/profile/phil.stubbs#!/vizhome/CitiBikeAnalytics_15879541754520/StartStationPopularityDashboard)
* [End Station Popularity Dashboard](https://public.tableau.com/profile/phil.stubbs#!/vizhome/CitiBikeAnalytics_15879541754520/EndStationPopularityDashboard)
* [Rider Demographics Dashboard](https://public.tableau.com/profile/phil.stubbs#!/vizhome/CitiBikeAnalytics_15879541754520/RiderDemographicsDashboard)
* [Customers vs Subscribers Dashboard](https://public.tableau.com/profile/phil.stubbs#!/vizhome/CitiBikeAnalytics_15879541754520/CustomersvsSubscribersDashboard)

### Visualizations

Each dashboard consists of a group of related visualizations.

Here are links to each of the individual Tableau visualizations created for this project:

* [Bike Trips By Gender](https://public.tableau.com/profile/phil.stubbs#!/vizhome/CitiBikeAnalytics_15879541754520/BikeTripsbyGender)
* [Bike Trips By Rider Type](https://public.tableau.com/profile/phil.stubbs#!/vizhome/CitiBikeAnalytics_15879541754520/BikeTripsByRiderType)
* [Most Popular Start Stations](https://public.tableau.com/profile/phil.stubbs#!/vizhome/CitiBikeAnalytics_15879541754520/MostPopularStartStations)
* [Avg Trip Duration by Age](https://public.tableau.com/profile/phil.stubbs#!/vizhome/CitiBikeAnalytics_15879541754520/AvgTripDurationbyAge)
* [Most Popular End Stations](https://public.tableau.com/profile/phil.stubbs#!/vizhome/CitiBikeAnalytics_15879541754520/MostPopularEndStations)
* [Most Used Bikes (due for repair or inspection)](https://public.tableau.com/profile/phil.stubbs#!/vizhome/CitiBikeAnalytics_15879541754520/MostUsedBikes)
* [Map - Most Popular Start Stations](https://public.tableau.com/profile/phil.stubbs#!/vizhome/CitiBikeAnalytics_15879541754520/Map-MostPopularStartStations)
* [Map - Most Popular End Stations](https://public.tableau.com/profile/phil.stubbs#!/vizhome/CitiBikeAnalytics_15879541754520/Map-MostPopularEndStations)
* [Bike Trips by Month and Gender](https://public.tableau.com/profile/phil.stubbs#!/vizhome/CitiBikeAnalytics_15879541754520/BikeTripsbyMonthandGender)
* [Bike Trips by Month and Rider Type](https://public.tableau.com/profile/phil.stubbs#!/vizhome/CitiBikeAnalytics_15879541754520/BikeTripsbyMonthandRiderType)
* [Peak Summer Hours (June 2019 - August 2019)](https://public.tableau.com/profile/phil.stubbs#!/vizhome/CitiBikeAnalytics_15879541754520/PeakSummerHoursJune2019-Aug2019)
* [Peak Winter Hours (December 2019 - February 2020)](https://public.tableau.com/profile/phil.stubbs#!/vizhome/CitiBikeAnalytics_15879541754520/PeakWinterHoursDecember2019-February2020)
* [End Station Popularity Over Time](https://public.tableau.com/profile/phil.stubbs#!/vizhome/CitiBikeAnalytics_15879541754520/EndStationPopularityOverTime)
* [Start Station Popularity Over Time](https://public.tableau.com/profile/phil.stubbs#!/vizhome/CitiBikeAnalytics_15879541754520/StartStationPopularityOverTime)

## About the data

The data used to build the Tableau visualizations comes from the Citi Bike webpage and is available from the webpage as csv files. For more information about the data used to build the visualizations, see <https://www.citibikenyc.com/system-data>.

The csv files are stored in a zip file inside the [Resources](./Resources) folder of this repository.

## Cleaning the data

To clean the data, a python package called pandas was used.

The steps to clean the data are captured and documented in the [citi_bike_data_cleaning.ipynb](./citi_bike_data_cleaning.ipynb) jupyter notebook file in this repository.

To get the final csv file that was used in Tableau to create the visualizations, run through all of the cells in the jupyter notebook file.
