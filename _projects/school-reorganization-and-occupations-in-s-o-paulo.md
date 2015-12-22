---
layout: project-page
title: School "Reorganization" and Occupations in São Paulo
linkname: school-reorganization-and-occupations-in-s-o-paulo
author: Bernardo Loureiro
tagline: This project maps the massive reorganization of public schools in São Paulo, highlighting the impacts of 94 schools that are being closed.
location:
    - place: São Paulo, Brazil
project-link:
    - href: https://bernardol.cartodb.com/viz/0ecf075a-9d1e-11e5-b8eb-0e31c9be1b51/public_map
    - href:  https://bernardol.cartodb.com/viz/3d07b49c-9d1d-11e5-b07a-0e5db1731f59/public_map
    - href:  https://bernardol.cartodb.com/viz/9ff09a66-9628-11e5-8f0f-0e674067d321/public_map
    - href:  https://bernardol.cartodb.com/viz/593b7c54-9d25-11e5-9244-0ecd1babdde5/public_map
tags:
    - tag: education
    - tag: schools
    - tag: social justice
thumbnail-path: img/school-reorganization-and-occupations-in-s-o-paulo/m8LHHEp.png
img-folder: ../../img/school-reorganization-and-occupations-in-s-o-paulo/
timestamp: 12/17/2015 18:41:15
---
In October 2015, the São Paulo State government in Brazil announced it was "reorganizing" the state's public schools, starting beginning of 2016. As a result of this reorganization, almost 300,000 students would have to compulsorily change schools; more than 1,400 schools would be affected; and 94 schools would be closed.

![]({{ page.img-folder }}m8LHHEp.jpg)

The reasons offered for these changes were "pedagogical," although the government made no public outreach or consultation, and did not show the studies on which the changes were based. In the following weeks, students began occupying schools in protest, eventually occupying more than 200.

![]({{ page.img-folder }}chusuBs.png)

Since there was no map of the schools being closed or reorganized, and with little open data available on the subject, I decided to make my own map.

I began by using a spreadsheet available on the Education Department website, which contained all schools in the state. There was no latitude and longitude data, so I had to geocode more than 5,100 addresses.

![]({{ page.img-folder }}nZVwFMM.png)

After that I had a shapefile of all the schools in the state.

![]({{ page.img-folder }}BTYVVjq.png)

To find out which schools were being closed I used a list from a news article. The names of the schools matched the names on the Education Dept spreadsheet, so it was easy to join both. But to get the data of the schools being "reoganized" but not closed, I had to do some web scraping. I scraped the Education Dept's website, which had a search query to look up the status of a school. Luckily, the school all had unique IDs shared in the Education Dept's master spreadsheet.

![]({{ page.img-folder }}HXuwzRB.png)

![]({{ page.img-folder }}rj66Qz2.png)

With this data, I produced two maps, showing the schools that were being closed and the ones being closed and reorganized. I also calculated the averages of students per class in each school, to show how currently the schools are already overcrowded.

<iframe width="100%" height="520" frameborder="0" src="https://bernardol.cartodb.com/viz/0ecf075a-9d1e-11e5-b8eb-0e31c9be1b51/embed_map" allowfullscreen webkitallowfullscreen mozallowfullscreen oallowfullscreen msallowfullscreen></iframe>

<iframe width="100%" height="520" frameborder="0" src="https://bernardol.cartodb.com/viz/3d07b49c-9d1d-11e5-b07a-0e5db1731f59/embed_map" allowfullscreen webkitallowfullscreen mozallowfullscreen oallowfullscreen msallowfullscreen></iframe>

I tried to find correlations between demographics and the schools being closed, to understand the reasons why these particular schools were being closed. For this, I imported census data and layered it into the maps, this time only for the city of São Paulo, not the state, because of the size of the datasets. I produced two more maps, trying to find a pattern in relation to population income and population in school age.

<iframe width="100%" height="520" frameborder="0" src="https://bernardol.cartodb.com/viz/9ff09a66-9628-11e5-8f0f-0e674067d321/embed_map" allowfullscreen webkitallowfullscreen mozallowfullscreen oallowfullscreen msallowfullscreen></iframe>

<iframe width="100%" height="520" frameborder="0" src="https://bernardol.cartodb.com/viz/593b7c54-9d25-11e5-9244-0ecd1babdde5/embed_map" allowfullscreen webkitallowfullscreen mozallowfullscreen oallowfullscreen msallowfullscreen></iframe>


Though no discernible pattern seems to emerge from these maps in relation to the school closings, it is interesting to see the social disparity in the city of São Paulo manifested spatially. As many authors have argued in the past, São Paulo is a city in which high income population is concentrated in the city center, and income falls as distance increases from the center. Another interesting aspect revealed was that age seems to fall a similar pattern, in which there are more school age population towards the periphery of the city.
