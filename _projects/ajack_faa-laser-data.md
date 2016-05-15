---
layout: project-page
title: "Aircraft Cockpit Laser Illumination Incidents 2010–2015"
linkname: FAA Laser Incidents-project
author: "ac jack"
tagline: "This map looks at the number of Laser-pointer cockpit illumination by state."
location:
    - place: United Sates
project-link:
    - href: http://acj9117.github.io
tags:
    - tag: FAA, Laser, Pointer, Aircraft
timestamp: 05/15/2015 16:30:00
---

Interactive Map of Aircraft Cockpit Laser Illuminations (2010–2015)

While looking for police arrest record data involving prohibited drone and laser-pointer usage verse manned FAA aircraft, I found a small dataset compiled by the FAA. This dataset focused on the use of laser-pointers and US aviation crafts. The FAA provided data is a “.xlsx” file with several internal sheets.

In order to utilize the FAA’s data in a map performed some light cleaning to the file:
	Merged all sheet into a single xlsx file sorting by date.
	Merged FAA’s “City” and “State” data fields to a “Location”.
	Geo-coded for latitude and longitude based on the new Location field using a Google-Sheets geo-coding plug-in. Geo-coding was run over several day as one is limited to 1000 sever calls per day.
	Created TimeStamp via concatenation of the FAA’s Date and Time fields.

Data is housed in CartoDB (via DropBox csv), and used to create this Leaflet map.

I used “Turf.js” in creating the thematic layer indication the states’ incident count.
The incident count is at the city level and not a specific airport or lat-lng. 
Laser incidents are clustered (via a Leaflet plug-in).



