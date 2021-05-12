---
layout: project-page
title: "86'ed: New York City's Restaurant during the Pandemic"
linkname: 86-ed-new-york-city-s-restaurant-during-the-pandemic
author: "Shaheryar Manzar"
tagline: "Public data on restaurants, labour, federal support, and news sites is used to map the impact of COVID19 on New York City restaurants."
location:
    - place: New York, NY, USA
project-link:
    - href: https://shmanzar.github.io/adv-gis/
tags:
    - tag: food
    - tag:  restaurants
    - tag:  covid19l
    - tag:  urban
thumbnail-path: img/86-ed-new-york-city-s-restaurant-during-the-pandemic/SEUJTXP.png
img-folder: ../../img/86-ed-new-york-city-s-restaurant-during-the-pandemic/
timestamp: 5/9/2021 23:47:18
---
The hospitality industry has always been a critical component of New York City’s economic and cultural significance, employing hundreds of thousands, attracting millions of visitors who spend around $46 billion annually, and contributing to its image as a cultural powerhouse.

The New York City restaurant industry accounted for about 1 in 12 private sector jobs and establishments citywide in 2019. Most of the labour which the industry relies upon is largely undocumented and therefore, unprotected. This labour is also predominantly made up of minority populations with relative lower average wages compared to the rest of the city
In March 2020, when the COVID-19 lockdown began, the industry suffered a dual burden of having lost the customer flow on which it depended on for survival but also now being termed as “essential”. Many businesses shut down, some permanently. Most significantly reduced service operations.There is a need to understand and document the changes in the hospitality industry because they are fundamentally changing their own streets and neighbourhoods, and in doing so transforming the city as a whole.

In my project, public data on restaurants, labour, federal support, and data collected and ‘scrapped’ from the news sites will be used to chart out and map the significance of the industry to New York City, the damage done by the pandemic, and finally, the attempted recovery efforts.

![]({{ page.img-folder }}upgxZF0.png)

First, I looked towards the city’s historical restaurant/storefront designs to try and capture relevant aesthetics.

![]({{ page.img-folder }}IJGzOPJ.png)

I settled on the old diners’ neon aesthetic (New York City diners being another slowly disappearing aspect of the city) and used that to style the typography, and map layers of the project.

![]({{ page.img-folder }}rYqUXoc.png)

I initially planned the project to be a single page application with relevant graphs on the left side and responsive map on the right. Then I iterated with one large basemap with layers being triggered via a slider. Finally, I settled on using a “scrolly-telling” map to both convey a narrative, and to give the viewers a walk-through of toggling different layers so that in the end they can choose to explore the map via their own preferred layers. I added an input field to quickly jump to the users own neighborhood.

![]({{ page.img-folder }}vv6H4DL.png)

The data collating, and cleaning was perhaps the largest component of the project. I used the Annual Census Survey (ACS) data to gather relevant information about occupation and race demographics of different New York City neighbourhoods. I scraped the ‘obituaries’ of the many restaurants which shutdown in the pandemic from websites like Eater, and the New York Magazine and often geo-coded them by hand. Finally, I used the Mapbox GL JS library to implement the collected geo-data layers as an interactive webmap. 

Finally, it came together as scrolly-telling map which introduces users to a story about the city’s restaurant industry and then allows users to take control of the map completely to view their own neighborhoods.

![]({{ page.img-folder }}B1jcZ7D.png)