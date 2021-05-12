---
layout: project-page
title: "India's Farmer-Laborer Struggle"
linkname: india-s-farmer-laborer-struggle
author: "Puneet Singh"
tagline: "A project explaining and documenting the spatial distribution of the Farmer-Laborer Struggle in India."
location:
    - place: India
project-link:
    - href: https://farmer-3.glitch.me/
tags:
    - tag: Farmer's protests
    - tag:  Punjab
    - tag:  Haryana
    - tag:  Delhi
    - tag:  BJP
    - tag:  Hindutva
    - tag:  farm bills
    - tag:  agriculture
    - tag:  neoliberalism
    - tag:  digital humanities
    - tag:  fascism
    - tag:  India
    - tag:  MSP
thumbnail-path: img/india-s-farmer-laborer-struggle/K92CrKD.png
img-folder: ../../img/india-s-farmer-laborer-struggle/
timestamp: 5/11/2021 1:34:39
---
Many farmers in India rely on government run mechanisms to say financially viable. The Central government passed Three Farm Bills in the Summer of 2020 when India was on lockdown during the COVID-19 pandemic that would annihilate these and in response a series of protests began that have spread across the country.

![]({{ page.img-folder }}Eft7HfJ.png)

There have been protests in many districts, though the reason for protests in each province are different. There have also been Mahapanchayats, large gatherings of farmers headed by a group of five elders to make decisions for a body of people. 

![]({{ page.img-folder }}KV8qxjW.png)

I gathered a bunch of data over a long period of time. I had a Word Document with a running list of URLs organized by province, in addition to a list of Mahapanchayat locations. 

![]({{ page.img-folder }}ymacwfT.png)

I created my own shapefile of Mahapanchayats in QGIS using the longitude and latitude coordinates to plot points. I then used SQL to select districts with documented protests to create an initial shapefile to start my project. 

![]({{ page.img-folder }}5xP1Pnu.png)

I then embedded both of these layers into maps in Carto!

<iframe width="100%" height="520" frameborder="0" src="https://thenewschool.carto.com/u/singp618/builder/c12e784f-bebf-4a51-a6b0-83895aa67af1/embed" allowfullscreen webkitallowfullscreen mozallowfullscreen oallowfullscreen msallowfullscreen></iframe>

<iframe width="100%" height="520" frameborder="0" src="https://thenewschool.carto.com/u/singp618/builder/cc2ac65f-0aa7-447e-8ad9-77f16c44111a/embed" allowfullscreen webkitallowfullscreen mozallowfullscreen oallowfullscreen msallowfullscreen></iframe>

I then ensured my website would give accurate information about how protests varied province to province. 

![]({{ page.img-folder }}YKTEzOk.png)
