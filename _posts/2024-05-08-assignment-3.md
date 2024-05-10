---
title: "Assignment 3 Spatial Data"
date: 2024-05-08T15:34:30-04:00
---

# Introduction

The objective of this assignment was to visualize and analyze the geographical distribution of enterprises listed in the **1995 Kazakhstan Defense Enterprise Directory**. This directory provides a comprehensive overview of defense-related enterprises, which have shifted towards civilian production post-Cold War era, indicating the economic transition of Kazakhstan from military to diversified industrial focus.

# Methodology
<img src="/assets/list.png" style="zoom:50%"/>
The list of enterprises was derived directly from the 1995 Kazakhstan Defense Enterprise Directory. This directory was chosen as it represents a unique period in Kazakhstan's economic development, focusing on industries converting from military to civilian purposes.

**Geocoding Process:**

To determine the geographical distribution of the listed enterprises, their addresses were geocoded to convert street addresses into geographic coordinates. This was accomplished using "[BatchGeo](https://www.batchgeo.com/)", an online geocoding service. BatchGeo was selected for its user-friendliness and ability to handle batch processing efficiently, making it ideal for converting multiple addresses at once. I inserted a copy of the list i have created manually then I let Batchgeo do the rest.

**Mapping Tool Selection:**

The geocoded data was then visualized using BatchGeo for mapping. BatchGeo was particularly suited for this task as it offers tools for easy integration of data sets and rendering them into interactive maps. This tool allows for quick visualization and provides interactive features, which are instrumental for a deeper analysis and presentation.

# Visualization

![map](/assets/images/map.png)
The map generated in BatchGeo visually represents the locations of all the enterprises across Kazakhstan. The visual spread of these "[locations](https://batchgeo.com/map/419186e7ef523cf92be0d002ce43ae7c)" can be seen in the attached screenshots, which illustrate clusters and isolated enterprises in various regions of the country.

![zoomed](/assets/images/zoomed.png)
![zoomed2](/assets/images/zoomed2.png)
![zoomed3](/assets/images/zoomed3.png)
**Above are 3 zoomed in pictures of the areas which had locations that were clustered and closer together**

**Color Categories and Interactive Features:**

The map uses color categories to distinguish between different types of enterprises based on their industry sectors such as aerospace, electronics, and heavy machinery, reflecting the diversification from their original military focus. Interactive features on the map include tooltips that appear when hovering over a location, providing additional information about each enterprise, such as the name, address, and primary industry. This interactivity enhances the usability of the map, allowing for an explorative approach to understanding the geographical and industrial landscape of the data.

Through these methods and tools, the assignment provides a clear visualization of the defense enterprises' distribution, offering insights into the economic restructuring of Kazakhstan post-Cold War through the lens of industrial geography.

