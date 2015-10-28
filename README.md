# OneBusAway

Shows how to configure [OneBusAway](https://github.com/OneBusAway) using [Miami-Dade Transit](http://www.miamidade.gov/transit) data.  

### Refer to the [wiki](../../wiki) for the instructions.

## Overall Goal

Integrate all transportation options in South Florida into a real-time open source system from MDT to BCT, Metrorail and trolleys.

## What
Combine all the transportation options in South Florida. We have Miami-Dade Transit buses, Metrorail, Metromover, Tri-Rail, Broward County buses, and Palm Tran buses. Every city has trolleys and only some have live tracking. We will deploy an open source system (OneBusAway) with real-time tracking built on top of open tools developed by Google and other US cities that combines the entire South Florida transportation network. The real-time tracking data will be shared with Google Maps and other systems. This will increase public transportation ridership and satisfaction. Startups and developers will use the open data to build amazing transportation apps.

### Status
Prototype

### Screenshots
OneBusAway Android app with Miami-Dade Transit and Broward County transit data:  
![OneBusAway Android app](https://slack-files.com/files-tmb/T02CRU2SU-F0D4B8FGQ-cb0bf99dee/screenshot_2015-10-24-00-09-44_720.png)  


OneBusAway Android app showing upcoming bus arrivals:  
![OneBusAway Android app trip updates delay](https://github.com/qtrandev/OneBusAway/blob/master/images/android-gtfs-realtime.png)  

## Why
The transportation system in South Florida is a mess. Real-time tracking is greatly lacking and every county and city has their own system. Systems don’t integrate with each other. Each system have their own app that takes years and millions of dollars to build then become outdated. Real-time and schedule data is stuck in each proprietary system. We need to change that. We need to open up the data so popular services like Google Maps can access the data. We are behind other cities such as NYC, San Francisco, and Seattle where real-time bus and train arrivals are common.

## Who
Our team is led by Quyen Tran and is composed of volunteers of Code for Miami and Code for Fort Lauderdale. We are advised by Ernie Hsiung of Code for America and Adam Old of TrAC Miami. The OneBusAway open source project is supported by many developers and has been deployed in NYC, Seattle, Atlanta, and Tampa. We have been able to deploy our own OneBusAway server on Amazon Web Services (AWS) and have been able to combine data from multiple agencies such as MDT and BCT. Our team is diverse and passionate, and our work is completely open source.

## How
### Dependencies
[OneBusAway](http://onebusaway.org) ([GitHub](https://github.com/OneBusAway/onebusaway/wiki))  
[GTFS zip files of transit agencies](../../wiki/Transit-Agencies)  
GTFS-realtime feeds of transit agencies  

### Install

#### Refer to the [wiki](../../wiki) for the instructions.
