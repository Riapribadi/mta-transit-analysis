## IDENTIFIED PROBLEM
NYC transit suffers from common criticisms about their subway system which revolves around timeliness and crowdedness of trains, that could be greatly affected by weather condition. 

## BUSINESS IMPACT
We are interested in finding the relationship between weather conditions and train timeliness and ridership volume, which will allow us to provide MTA with a better prediction of train volume and accurate timeline, which could increase public transportation usage, improve reliability, and enhance service for their clients.

## PROJECT CHALLENGES
The collected weather data encompassed NYC as a whole and was not segmented by boroughs/districts.
Hard to quantify the amount of rainfall in a particular area of NYC and link it to a subway line.
Other variables in addition of weather might also impact subway turnstile usage
Limited amount of historical data availability and storage
Limited amount of API requests due to costs concern

## HIGHLIGHTS
Our data model combines weather data with MTA turnstile and subway location data, that processes over 10 GB of data stored in S3 and Redshift data warehouse. The visualizations and analysis are based on the data obtained from 2015-2022.

Data collected from Wunderground weather website and MTA website.

