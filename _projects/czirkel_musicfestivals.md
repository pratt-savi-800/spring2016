---
layout: project-page
title: "Music Festivals of 2016"
linkname: FinalPresentation
author: "C. Zirkel"
tagline: "The map identifies the music festivals around the world in 2016."
location:
    - place: Worldwide
project-link:
    - href: http://czirkel.github.io/FinalPresentation/
tags:
    - tag: music festival, music, festival
thumbnail-path: img/festivals_all.png
img-folder: ../../img/czirkel_musicfestivals
timestamp: 05/17/2016 10:23:15
---

The purpose of this map is to show the locations of music festivals around the world.  As a self proclaimed music junkie, I thought it would be interesting to see where the festivals were held, as well as to see if I could find a pattern in genres in a certain area.  What I didn't realize was how time confusing this project.  When I was originally looking for information on this subject I never found any maps about just lists (or I would later find that if there was a map, the coordinates would be embedded in code not a spreadsheet that I could use).
I had started this project before but by using a GeoJSON.  Currently the GeoJSON is still embedded but data is being pulled from CartoDB for two other layers (one being a standard layer, the other pointing out music festivals that permitted camping).  In the future I would like to eliminate the GeoJSON but adjust the CartoDB layer to mimic what I had.  I decided to use Mustache for my popups which was simple yet efficient to get my information across.  The only "struggle" I have with Mustache is that I still cannot get my Hyperlinks to work.
I also included a time slider.  I feel that this is my most important aspect to my map.  This gives the user more interaction and can narrow down their search options to certain times of the year when looking for a music festival.  If I were to adjust this further, I would make so that all of the dates are selected at first so that the user wont be blindly searching for data.
