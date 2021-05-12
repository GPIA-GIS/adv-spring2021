---
layout: project-page
title: "Put Out the Fire!"
linkname: put-out-the-fire-
author: "Moja Robinson "
tagline: "Visualizing the correlation between EJ community health and US trash incinerators"
location:
    - place: USA
project-link:
    - href: https://mojarobinson.github.io/incinerators/
tags:
    - tag: Environmental Justice, Social Justice, Trash, Incinerators, Health, Sacrifice Zones
thumbnail-path: img/put-out-the-fire-/pGnS8IJ.gif
img-folder: ../../img/put-out-the-fire-/
timestamp: 5/2/2021 20:47:26
---
About:

This project transpired from a previous report and map I did with Tishman Environment and Design Center (TEDC) for the Global Alliance for Incineration Alternative (GAIA). In that project, I researched how the cost of burning trash in municipal incinerators is significant to human and ecological health, and expensive for community members and municipalities. I then went on to visualize my findings per state with a static map. 

For this project, I wanted to show the relationship of incinerators to environmental justice communities (EJC). Thus, how sacrifice zones correlate to health issues with BIPOC or low-income communities. I wanted to tell this story to EJCs. However, I was aware of my educational privilege, which might make my project hard to understand. So throughout the project, I tried to simplify the user experience and explanations.

Data Process: 

To start I researched and used data from the Census Bureau, CDC, Energy Recovery Council, and the EPA. I then defined the EJ Community by each state’s definition, which was heavily influenced by race and income. Next, I did a 3-mile buffer for each incinerator to see which census block groups were EJC to define if the incinerator was in an EJC. Lastly, I had to combine the CDC health data with the Census boundary to create unique polygons to show the health information. I then gathered my data into two excel sheets, one for point data (incinerators) and one for polygons (health data).

Code Process:

I used a split-screen Glitch template to start my webpage. I then displayed my two excel sheets via Carto. I then added a legend using another template and created a unique gradient bar animation to display my health data ramp. Next, I added pop-up data to each point, followed by a check-box feature to display my polygons. This was the hardest part of this project, but Sook helped out a lot! Then, I did a modal pop-up I learned from my Myspace days to show my methodologies and sources. Lastly, I added general information and additional sources, followed by linking my Glitch page to Github. 

Critiques:

I would have liked to have information on “joining the fight” to shut down incinerators on the point pop-up feature, however, it was difficult finding and compiling that information especially with the time I had.

Snap Map:

![]({{ page.img-folder }}OolFZgu.jpg)

