---
layout: project-page
title: "NYC Subway Entrances Map"
linkname: nyc-subway-entrances-map
author: "jeanpan"
tagline: "A map shows all the subway entrances in NYC and provides nearby entrances search."
location:
    - place: Brooklyn, NY, USA
project-link:
    - href: http://jeanpan.github.io/nyc-subway-entrances-map/
tags:
    - tag: map, subway, entrances, nyc,
thumbnail-path: img/nyc-subway-entrances-map/nyc-subway-entrances-map.png
img-folder: ../../img/nyc-subway-entrances-map/
timestamp: 05/15/2016 09:35:15
---

There are many subway entrances in NYC. However, these entrances are not shown in Google Map. Google Map only shows station location. Therefore, I made a leaflet responsive map showing all the entrances in NYC, and this map also provides the function of nearby entrances search.

![]({{ page.img-folder }}nyc-subway-entrances-map.png)

After typing an address in the search box, the map shows all the nearby entrances (entrances within 2km). Clicking on an entrance, the information of the entrance shows on the left content box, including the location of entrance, type of entrance, line, route ... etc. The 'GET DIRECTION' link will redirect user to the google map and locate the exact location in google map.

![]({{ page.img-folder }}search.png)

Below the search box, there are four buttons to provide filtering. First one (subway icon) is showing all the subway entrances. Second one (wheelchair icon) showing entrances providing ADA. Third one (dollar icon) is showing entrances having vending machine. And the last one (help icon) is showing entrances having full-time staff. User can click two or more to have multiple filtering, for example, clicking on the dollar icon and help icon shows entrances having vending machine and full-time staff. Mouseover for two seconds will give some hint about what this icon for.

![]({{ page.img-folder }}filtering.png)

This is a responsive map. For mobile device, because the screen is smaller, I remove some function so user can focus on the function of search.

![]({{ page.img-folder }}mobile.png)

That map is [here](http://jeanpan.github.io/nyc-subway-entrances-map/), and the code is on [GitHub](https://github.com/jeanpan/nyc-subway-entrances-map).
