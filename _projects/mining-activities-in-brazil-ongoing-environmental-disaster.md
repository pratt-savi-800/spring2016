---
layout: project-page
title: "Mining activities in Brazil - ongoing environmental disaster"
linkname: mining-activities-in-brazil-ongoing-environmental-disaster
author: "Silvia Xavier"
tagline: "Two maps document mining in Brazil - one depicts the impact of a dam burst, another investigates overlaps of mining and preservation areas. "
location:
    - place: Minas Gerais, Brazil
project-link:
    - href: https://silviaresendexavier.cartodb.com/viz/46eb6dc8-9d2c-11e5-8a42-0e5db1731f59/public_map
    - href:   https://silviaresendexavier.cartodb.com/viz/a8783b46-9d2e-11e5-bbb2-0ecfd53eb7d3/public_map
tags:
    - tag: Mining
    - tag:  environmental disaster
    - tag:   environmental justice
    - tag:  Rio Doce
thumbnail-path: img/mining-activities-in-brazil-ongoing-environmental-disaster/8S9TbPm.jpg
img-folder: ../../img/mining-activities-in-brazil-ongoing-environmental-disaster/
timestamp: 12/22/2015 17:28:38
---
On 05 November 2015 a dam that held residue from Samarco’s (Vale + BHP Billiton) mining operations collapsed. The mud took over Bento Rodrigues Village and flowed through rivers Carmo, Gualaxo and Doce until it reached the sea. This path marks one of Brazil’s largest environmental and social disasters.
![]({{ page.img-folder }}QUPt7gv.jpg)
In addition to the damaged caused in the village where 15 people died and many lost their houses, the fauna along the rivers died and the livelihood of the communities living in the rivers’ margins is disrupted.
![]({{ page.img-folder }}DG2bqDE.jpg)   
The disaster has been slowly unfolding as the dense mud traveled throughout the river, reaching the sea only 17 days after the dam collapsed. The situation has been widely covered in the media and has been monitored by satellite images and forecasts for the mud trajectory. The disaster will be unfolding long in the future as no reparation is made and the impacts are long lasting. I decided to make a map that provides a picture of the geographical and temporal scale of this ongoing disaster and depicts its human scale, plugging in stories of the communities along the river.
I started by mapping the mud trajectory compiling the daily reports that the Brazilian Geological Service released. With this compilation I made an animation of the mud progression and a static image of mud location each day.
![]({{ page.img-folder }}EO5tPYY.gif)
In QGIS I was able to geocode the image and edit the river’s shapefile to include the dates when the mud reached each section. This allowed me to animate the interactive map, which has a timeline and shows the progression day by day. To have a context for the environment around the river, and the importance of this ecosystem, I included the Rio Doce drainage basin shapefile, the preservation areas and the indigenous reserves that exist in the surroundings. Through research in various media I was able to gather images, videos and stories about the affected areas, which are plugged to the map and accessible in the infowindows.

<iframe width="100%" height="520" frameborder="0" src="https://silviaresendexavier.cartodb.com/viz/46eb6dc8-9d2c-11e5-8a42-0e5db1731f59/embed_map" allowfullscreen webkitallowfullscreen mozallowfullscreen oallowfullscreen msallowfullscreen></iframe>

Parallel to this research, I investigated another controversial aspect of mining activities in Brazil - due to some legal frameworks, mining can be authorized in preservation areas and indigenous reserves, which compromises communities and natural areas. For this investigation I had to understand the legal regimes for mining license in Brazil. Moreover, I had to gather and combine data from different governmental institutions - National Department for Mining Production, Indigenous National Foundation and Environment Ministry, (DNPM, FUNAI and MMA are the acronyms in Portuguese).
![]({{ page.img-folder }}CFebvqQ.jpg)
Having this data together I was able to use spatial analysis tools to create a shapefile with the  existing intersections between protection areas and mining activities. In the interactive map I layered the variables - mining areas, protection areas and an intersection areas - so users can turn layers on and off to visualize each area distribution separately. The base map is formed by satellite imagery which allows for a closer investigation on the shape of mining activities on the ground when zooming in. Each are have diverse information about the institutions and companies managing them.

<iframe width="100%" height="520" frameborder="0" src="https://silviaresendexavier.cartodb.com/viz/a8783b46-9d2e-11e5-bbb2-0ecfd53eb7d3/embed_map" allowfullscreen webkitallowfullscreen mozallowfullscreen oallowfullscreen msallowfullscreen></iframe>
