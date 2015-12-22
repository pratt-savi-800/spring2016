---
layout: project-page
title: "Bushwick's Historic Theaters & Performance Access Equity"
linkname: bushwick-s-historic-theaters-performance-access-equity
author: "Drew Vanderburg"
tagline: "The locations of historic theaters in Bushwick opened from 1895 - 1928.

AND

The locations of performing arts venues in Brooklyn, 2015."
location:
    - place: Brooklyn, NY, USA
project-link:
    - href: https://mrlomaloma.cartodb.com/viz/8f145e02-a074-11e5-ba3e-0ecd1babdde5/public_map
    - href: https://mrlomaloma.cartodb.com/viz/f079ac86-a210-11e5-9b4c-0e3ff518bd15/public_map
    - href: https://mrlomaloma.cartodb.com/viz/9245d6d0-a21a-11e5-9d7d-0ecd1babdde5/public_map
tags:
    - tag: theater
    - tag: theatre
    - tag: theaters
    - tag: theaters
    - tag: cinemas
    - tag: silent film
    - tag: performance
    - tag: Bushwick
    - tag: Brooklyn
    - tag: NYC
    - tag: abandoned
    - tag: vacant
    - tag: demolished
    - tag: vaudeville
thumbnail-path: ../../img/bushwick-s-historic-theaters-performance-access-equity/VqsVNbD.png
img-folder: ../../img/bushwick-s-historic-theaters-performance-access-equity/
timestamp: 12/21/2015 21:35:15
---
Because I believe that the performing arts can strengthen communities by generating democratic participation and a sense of place, I decided to map "Performance Access Equity" in New York City.  I define this as the opportunity for EVERYONE to be able to access quality performing arts in their neighborhood.  This would require AMPLE AFFORDABLE LOCAL performing arts venues, relative to the population and average income of their neighborhoods.

To map this, I compiled a data set of as many performing arts venues in Brooklyn that I could find.  (I decided to focus on Brooklyn because I live there, and any citywide data would have been drastically skewed by the high concentration of huge expensive theaters in midtown Manhattan.)
The main sites for my data sourcing were https://nycopendata.socrata.com, http://www.cinematreasures.org and http://nyc.spacefinder.org.  I also found an API at http://platform.seatgeek.com which returned me these crazy results:

![]({{ page.img-folder }}dtje2Vw.png)

After processing this data with Microsoft Excel, I generated some static maps:

![]({{ page.img-folder }}t41Q0CD.png)

![]({{ page.img-folder }}vON2eMP.png)

![]({{ page.img-folder }}Pt9NloZ.png)

To theorize the Performance Access Equity, I mixed the venue data with census data. 

![]({{ page.img-folder }}4Nlq2OA.png)

![]({{ page.img-folder }}cHr6gTK.png)

![]({{ page.img-folder }}e7SmqzT.png)

<b>I discovered that THE AREAS WITH THE HIGHEST DENSITY OF POOR PEOPLE ARE ALSO THE AREAS WITH THE LOWEST DENSITY OF PERFORMING ARTS VENUES.  Why?!?! </b>

![]({{ page.img-folder }}BG6QgK9.png)

Thus, theoretically, the performing arts venues in the neighboring census tracts have the largest opportunities to improve Brooklyn's Performance Access Equity, (and draw large crowds in the process.)

![]({{ page.img-folder }}Fi15wbP.png)

After this, I shifted my focus to interactive maps, and zoomed in on the neighborhood of Bushwick.  Using NYC's Automated City Register Information System (http://a836-acris.nyc.gov/CP/), PLUTOMap shapefiles, and http://cinematreasures.org, I mapped 49 theaters in Bushwick opened between 1895 and 1928, with "then and now" photos of the locations.  Most of these venues opened as Vaudeville theaters or silent film cinemas and were converted to "talkies."  Eventually, single-screen cinemas fell out of style.  Most of these venues met their demise during the Great Depression, or after WWII when Bushwick's industries began to decline and its middle-class European immigrant families moved to suburbia.  Any of these venues that remained open until the 1970's had become a pornographic cinema.  As of 2015, 0 of these spaces are functioning as theaters.

<iframe width="100%" height="520" frameborder="0" src="https://mrlomaloma.cartodb.com/viz/8f145e02-a074-11e5-ba3e-0ecd1babdde5/embed_map" allowfullscreen webkitallowfullscreen mozallowfullscreen oallowfullscreen msallowfullscreen></iframe>

To practice my CartoDB skills further, I supplemented this map with two more: a map of the venues categorized by their current uses and a torque map of the venues that shows their opening dates.

<iframe width="100%" height="520" frameborder="0" src="https://mrlomaloma.cartodb.com/viz/9245d6d0-a21a-11e5-9d7d-0ecd1babdde5/embed_map" allowfullscreen webkitallowfullscreen mozallowfullscreen oallowfullscreen msallowfullscreen></iframe>

<iframe width="100%" height="520" frameborder="0" src="https://mrlomaloma.cartodb.com/viz/f079ac86-a210-11e5-9b4c-0e3ff518bd15/embed_map" allowfullscreen webkitallowfullscreen mozallowfullscreen oallowfullscreen msallowfullscreen></iframe>

I even made a map of the old theaters with dots sized according to seating capacity:

![]({{ page.img-folder }}VjkrWNQ.png)

And a final map showing the location of movie theaters in proximity to Bushwick today:

![]({{ page.img-folder }}0kxU2UW.png)

If you have any questions, comments, or critiques regarding this project, feel free to e-mail me at drew.vanderburg@gmail.com.
