<p align="center">
  <img width="1001" height="300" src="https://github.com/vcai01/know_before_you_go/blob/master/Vancouver-landing-size-banner.jpg">
</p>
<div align="right"><font color=grey size=2>Image © The City of Vancouver</font></div>

[**_Work in Progress_**](https://github.com/vcai01/know_before_you_go/issues/1)

# know_before_you_go
Analysis of accommodation and job landing in Vancouver

## Motivation and Purpose
Moving to a new city is exciting as well as challenging. As a data analyst and a volunteer in peer support, I have been exploring various ways to help newcomers and contribute my value to the society.

I intend to use my analytical toolkits and statistical knowledge to develop an analysis as a guide for newcomers to find accommodation and getting jobs in Vancouver, which is not only a wrap-up of my immigration experience, but also an initiative of my participation and civic engagement to give back to the community.

## Target Audience
The client for this project is those newcomers planning a relocation to Vancouver who wants a second opinion on accomodation, housing, crime and job landing here. To be specific, a newcomer is defined here as the one with household members less than five persons (six in total including him/herself). Newcomers will be able to use the analysis to determine the community where they would like to live in the short/long term, and what jobs they plan to seek.

Though not the primary client, an alternate client would be the staff working in settlement service organizations and the municipal government that want to better help newcomers settle and integrate in Vancouver.

## Data
The primary sources of data for this ongoing project are the open data from Airbnb, the City of Vancouver, The Vancouver Police Department, and Public Library InterLINK as well as the scraped data from the Government of Canada and Indeed/Glassdoor etc.

The datasets are listed corresponding to two basic needs of newcomers:

1. Finding accommodation
* Short term
  -  `listings_09Nov2019.csv`: detailed Airbnb listings data of Vancouver which was compiled on November 9, 2019.

* Long term
  - `property_tax.csv`: pending
  - `Crimedata.csv`: pending

2. Landing jobs

For detailed attribute information, please check the corresponding file.

## Approach
I followed the CRISP-DM methodology for the project, which stands for Cross-Industry Standard Process for Data Mining. CRISP-DM provides an overview of the data mining life cycle, which consists of six phases with arrows indicating the most important and frequent dependencies between phases. The sequence of the phases is flexible and not strict.

<p align="center">
  <img width="350" height="349" src="https://github.com/vcai01/know_before_you_go/blob/master/crisp_process.gif">
</p>
<div align="center"><font color=grey size=2>Image © IBM Knowledge Center</font></div>


* Business Understanding
* Data Understanding (EDA)
* Data Preparation
* Modeling
* Evaluation
* Deployment

## Dependencies
* beautifulsoup4 (version 4.8.2)
* Jupyter (version 4.4.0)
* numpy (version 1.18.1)
* pandas (version 0.25.3)
* matplotlib (version 3.1.2)
* plotnine (version 0.6.0)
* sklearn (version 0.22.1)
* shapely (version 1.6.4)
* Geopandas (version 0.6.1)

## Credits and Appreciation
1. http://insideairbnb.com/ 
