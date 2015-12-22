---
layout: project-page
title: "New York City is Built on Trash"
linkname: new-york-city-is-built-on-trash
author: "Darcy Bender"
tagline: "New Yorkers have always struggled with their trash. This map traces the rich history of landfills in the city."
location:
    - place: New York, NY, USA
project-link:
    - href: http://bl.ocks.org/anonymous/raw/f496e5590e43fa0f3429/
    - href:  https://bendd165.cartodb.com/viz/261cbc84-9c6c-11e5-b311-0ea31932ec1d/public_map
tags:
    - tag: trash
    - tag:  waste
    - tag:  landfills
    - tag:  history
thumbnail-path: ../../img/new-york-city-is-built-on-trash/RG0jpMq.jpg
img-folder: ../../img/new-york-city-is-built-on-trash/
timestamp: 12/22/2015 0:48:35
---
In the last three centuries, unwanted excavation material, construction and demolition debris and solid waste has been dumped and covered, creating landfills throughout the city. However, few records exist of this activity and many New Yorkers are unaware that they are walking on waste everyday. 

The map I made shows the sites of major landfills from 1844 to present. My hope is that by seeing the amount of land that is made of waste, people might further investigate the social, political and technical systems of waste in their lives. Ultimately, I would like to see people understand that our waste is in fact always with us even if we burn it, bury it or let it dissolve into the atmosphere.

In order to make the map, I first conducted research on former landfills. Luckily, I came across a paper written in 1995 that surveyed historical documents and photos and included comprehensive maps for four time periods.

![]({{ page.img-folder }}2KRHo7I.jpg)

source: https://info.ngwa.org/GWOL/pdf/952061791.PDF

In order to create an interactive version of this map, I first had to georeference the raster images from the pdf.

![]({{ page.img-folder }}pRn8JJQ.jpg)

Once I had an overlay of the raster information, I traced the outlines of the former landfills as polygons. This process had varying levels of success because of the low resolution of the original file.

![]({{ page.img-folder }}6cGg4gd.jpg)

Once I had all of the polygons traced, I was able to create an interactive map in CartoDB.

<iframe width="100%" height="520" frameborder="0" src="https://bendd165.cartodb.com/viz/261cbc84-9c6c-11e5-b311-0ea31932ec1d/embed_map" allowfullscreen webkitallowfullscreen mozallowfullscreen oallowfullscreen msallowfullscreen></iframe>

The map of polygons is interesting, but I felt that qualitative information about the landfills and historical context would help convey my story of New Yorkers living with their waste. I was able to find many historical photos on the New York Public Library Digital Collections website of former landfill sites. The most difficult part was choosing which photos to include.

![]({{ page.img-folder }}IZCJjQ0.jpg)

Finally, in order to include more written information and a cohesive narrative, I used Odyssey.js to create a scrolling map-based story. The final map walks the viewer through time, tracing the history of landfills in New York City from 1844 to the present day. 

