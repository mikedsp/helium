The MyDocuments folder is a place to share my Helium learnings

The following documents are in this repository:

20200831_TBHV110 data.xlsx - Data collected from a TBHV110 temp/humidity/co2/VO sensor, 100 measurements collected over 2 days
20201008_TBHV110data.xlsx - Data collected from a TBHV110 temp/humidity/co2/VO sensor, 3200 measurements collected between Aug 29 - Oct. 8, 2020

20201016_TempHumidity-SensorCompare.xlsx - Data collected from a radio bridge and a browan termp and humidity sensor from Oct 12 - Oct 16, 2020. Sensors are co-located so you can compare performance with the data. 

20201020_RBS305data.xlsx - Data collected from a Radio Bridge RBS305-ATH-US temperature and humidity sensor between Oct. 12 - 20, 2020. THe sensor was in a living room most of the time, but placed in a freezer for a short period of time.

BrowanTBHV110_HeliumQuickStart-SHARE.pdf - walks through getting a Browan TBHV110 (Health Home Indoor Air Quality) Sensor connected to the Helium network, connected to Cayenne, and capturing data to a Google Sheet via a Pipedream workflow

HowTo_BrowanTBHH100_to_GoogleSheet-SHARE.pdf - describes how to get data from a Browan TBHH100 temperature and humidity sensor to flow in real time to a Google Sheet.
The end-to-end data flow is as follows: TBHH100 > Helium Hotspot > Helium Network > Pipedream > Google Sheet

HowTo_ReverseGeoCode_in_Pipedream-SHARE.pdf - how to build a Step in a Pipedream workflow to take a set of GPS latitude and longitude coordinates and return the nearest address using an API from the HERE.com location platform. At the end of this document is a Bonus section that shows 2 different Pipedream steps to calculate the distance between 2 sets of GPS coordinates. 

PipeDreamBootstrap - TweetToGoogleSheet-SHARE.pdf - goes through a step-by-step analysis and copy of a 4 minute Pipedream YouTube video demonstrating how to Analyze Twitter Sentiment in Real-Time and to save the results to a Google Sheet. If you follow the steps in this document, you should have your own working solution for Twitter-to-Google Sheets.

RBS305-ATH-US_HeliumQuickStart.pdf - Document walks through the steps to get a Radio Bridge Indoor Temperature and Humidity Sensor (RBS305-ATH-US) connected to the Helium network, connected to Cayenne myDevices, and capturing data in a Google Sheet via a Pipedream workflow. The document also covers how to change the mode of the sensor from the default mode (triggering on temperature or humidity crossing a threshold) to triggering on a change in temperature or humidity.

RBS305-ATH-US_payloadAnalysis.pdf - This document walks through a manual decoding of some Radio Bridge RBS305-ATH-US temp/humidity sensor payloads received in the Helium Console Debugger. 
