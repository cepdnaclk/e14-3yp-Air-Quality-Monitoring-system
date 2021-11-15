---
layout: home
permalink: index.html
repository-name: e14-3yp-Air-Quality-Monitoring-system
title: Air Quality Monitoring system
---

# Air Quality Monitoring system

---
	
## Team
-  E/14/049, KASUN VIMUKTHI, [e140494@ce.pdn.ac.lk](mailto:e14049@ce.pdn.ac.lk)
-  E/14/037, BANDARA M.K.G.E.S.P., [e14037@ce.pdn.ac.lk](mailto:e14037@ce.pdn.ac.lk)

## Table of Contents
1. [Introduction](#introduction)
2. [Solution Architecture](#solution-architecture )
3. [Hardware & Software Designs](#hardware-and-software-designs)
4. [Links](#links)

---

## Introduction
Monitoring and maintaining air quality and sound quality are most important aspects of city management. A significant proportion of the population lives in cities, where air quality index has exceeded limits for several air pollutants like - particulate matter (PM), ozone, nitrogen dioxide.The Noise pollution can cause hypertension, high stress levels, tinnitus, hearing loss, sleep disturbances, and other harmful effects.These pollution pose serious health and environment risks. Therefore air and sound quality monitoring system is an important component of any smart city.

So in this unified project we develop a system to monitor , forecast and reducing air pollution in a city through actionable data. the data will be received from gas sensors and the sound sensor. we are trying measure the data using this module in urban areas.

All those data taken from those sensors, are sent to a central server and processed there.if the permit levels are exceed Regulatory agencies or pollution control boards will be informed.and also person can see whether the city is suitable for living and what will be the future. they can get the information about Pollution Awareness.


## Solution Architecture
Sense the quantities using

5pcs LM393 sound detection sensor DC 3.3 -%v sound sensor module sound detector for sound quality measurements.
CO2 Carbon Dioxide Sensor Module MG811 for mesuring the co2 content.
2PCS Winsen ZE05 H2S/CO/NO2/SO2 Electrochemical Detection Module UART Output.
MQ-136 H2S Hydrogen Sulfide MQ-137 NH3 Ammonia Gas Sensor Module Detection.
1pc ORIGINAL New ZE03-O2 winsen Electrochemical Oxygen Sensor Module DHL FEDEX.
Key Features

GPRS based solution, no need of laying communication cables.
Monitors H2O, CO2, CO, SO2, NO2, NH3.
Keeps automatic record of above parameters.
Alarms over email or SMS
Manage all your plants on a single platform form anywhere.
API to Upload data to regulatory agencies server.
Data available for public awareness with comparisons.

## Hardware and Software Designs

milestone 2: infrastructure
 Quentities that we are going to measure are as follows

different air and sound levels in environment:

co percentages
Hydrocarbonic air percentages
nox and sox percentages
sound level percentages
 but there are many more polluted airs in the environment. such as O3,CO2 etc.we are considering the airs which are giving  higher impact for the climate changes and other victims.

 co percentages measures from MQ7 sensor. Hydrocarbonic air measures from MQ3 sensor.nox and sox measurements will be measuring using suitable sensors.(didn't buy them yet)

 A GSM module in each node will be sent the date to the server.Data from each node will be sent as JSON obejct and catch them in  the server.

 In the back end ;

1).MySQL
2).Node.js

 Angular.js will use the for the front end.

 

 sensitive data in this system are as follows;

1) Data which are coming from the factories should be protected.for example: owner may want to earn profits without considering damage to the environment. this can achieve only by maintaining the desired standards and the levels.therefore ,they might tend to change these value in to standards values in illegal ways.

 2).Information that are stored in the servers.


## Links

- <a href = "https://github.com/cepdnaclk/e14-3yp-Air-Quality-Monitoring-system" target = "_blank"> Project Repository </a>
- <a href = "https://cepdnaclk.github.io/e14-3yp-Air-Quality-Monitoring-system/" target = "_blank">Project Page</a>
- <a href = "http://www.ce.pdn.ac.lk/" target = "_blank">Department of Computer Engineering</a>
- <a href = "https://ce.pdn.ac.lk/" target = "_blank">University of Peradeniya</a>



[//]: # (Please refer this to learn more about Markdown syntax)
[//]: # (https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
