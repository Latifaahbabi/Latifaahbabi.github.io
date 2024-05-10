---
title: "Assignment 3 Spatial Data"
date: 2024-05-08T15:34:30-04:00
---

# Introduction

The objective of this assignment was to visualize and analyze the geographical distribution of enterprises listed in the **1995 Kazakhstan Defense Enterprise Directory**. This directory provides a comprehensive overview of defense-related enterprises, which have shifted towards civilian production post-Cold War era, indicating the economic transition of Kazakhstan from military to diversified industrial focus.

# Methodology
![list](/assets/images/list.png)
The [list](https://docs.google.com/spreadsheets/d/1Pp1_PEqnPTMCT6I07ZCb2itLZ4Ki79T1qVKGhh5KKKU/edit?usp=sharing) of enterprises was derived directly from the 1995 Kazakhstan Defense Enterprise Directory. This directory was chosen as it represents a unique period in Kazakhstan's economic development, focusing on industries converting from military to civilian purposes.

**Geocoding Process:**
To determine the geographical distribution of the listed enterprises, their addresses were geocoded to convert street addresses into geographic coordinates. This was accomplished using [BatchGeo](https://www.batchgeo.com/), an online geocoding service. BatchGeo was selected for its user-friendliness and ability to handle batch processing efficiently, making it ideal for converting multiple addresses at once. I inserted a copy of the list i have created manually then I let Batchgeo do the rest.

**Mapping Tool Selection:**
The geocoded data was then visualized using BatchGeo for mapping. BatchGeo was particularly suited for this task as it offers tools for easy integration of data sets and rendering them into interactive maps. This tool allows for quick visualization and provides interactive features, which are instrumental for a deeper analysis and presentation.

# Visualization

![map](/assets/images/map.png)
The map generated in BatchGeo visually represents the locations of all the enterprises across Kazakhstan. The visual spread of these [locations](https://batchgeo.com/map/419186e7ef523cf92be0d002ce43ae7c) can be seen in the attached screenshots, which illustrate clusters and isolated enterprises in various regions of the country.

![zoomed](/assets/images/zoomed.png)
![zoomed2](/assets/images/zoomed2.png)
![zoomed3](/assets/images/zoomed3.png)
**Above are 3 zoomed in pictures of the areas which had locations that were clustered and closer together**

**Color Categories and Interactive Features:**
The map uses color categories to distinguish between different types of enterprises based on their industry sectors such as aerospace, electronics, and heavy machinery, reflecting the diversification from their original military focus. Interactive features on the map include tooltips that appear when hovering over a location, providing additional information about each enterprise, such as the name, address, and primary industry. This interactivity enhances the usability of the map, allowing for an explorative approach to understanding the geographical and industrial landscape of the data.

Through these methods and tools, the assignment provides a clear visualization of the defense enterprises' distribution, offering insights into the economic restructuring of Kazakhstan post-Cold War through the lens of industrial geography.

# Data Analysis and Interpretation

**Source and Data Types:**
The source for this analysis, the 1995 Kazakhstan Defense Enterprise Directory, is a specialized directory that lists enterprises, primarily from the defense industry, which were transitioning to civilian production post-Soviet Union dissolution. The data provided includes enterprise names, addresses, and occasionally industry type, giving a snapshot of the industrial landscape during a significant period of economic transition.

Data Communication:
The data was directly communicated through the directory listings. No assumptions were necessary for the basic mapping of addresses; however, assumptions were needed when categorizing enterprises into industry types due to some listings lacking detailed descriptions. New columns such as "Industry Type" were inferred based on the enterprise names and known historical contexts.

Use of ChatGPT:
ChatGPT was utilized to help formulate the methodology and structure the analysis efficiently. For example, prompts were created to guide the extraction and interpretation of data, such as "Explain how to convert addresses into geographic coordinates using BatchGeo" or "Identify patterns in the distribution of Kazakhstan enterprises on a map."

Patterns and Clusters:
The mapped data revealed several interesting patterns. There was a significant concentration of enterprises in major urban centers such as Almaty, Astana, and Oskemen, reflecting the urban industrial focus of Kazakhstan's economy. The absence of enterprises in more rural or less economically developed regions highlights the uneven industrial development across the country. No additional columns like profession or gender were mapped in this analysis due to the nature of the source data.

Significant Findings:
A notable finding was the clustering of enterprises around Almaty and Astana, which are economic hubs of Kazakhstan. This pattern indicates that despite the economic diversification efforts post-independence, industrial development remains heavily urban-centric.

Scalability and Further Research
Implications of Scaled Data:
If the data were scaled to include more enterprises or cover different regions over multiple years, we might observe trends in the geographic expansion or contraction of certain industries. This could provide valuable insights into the economic development patterns and policy impacts over time.

Future Research Suggestions:
For future projects, an ideal source would be a comprehensive national business registry that includes all types of enterprises with detailed industry classifications and operational data such as employment figures and revenues. Analyzing a broader geographic area, including neighboring countries in Central Asia, would provide a comparative view of regional economic development.

Conclusion
This analysis has provided key insights into the industrial and economic landscape of Kazakhstan in the mid-1990s, highlighting significant urban-industrial concentrations and the beginning of a transition from military-focused to diversified industries. The use of geocoding and interactive mapping tools like BatchGeo has proven effective in visualizing complex geographic data in an accessible format.

Reflections and Limitations:
A limitation of this project was the reliance on the accuracy and completeness of the directory data. Future projects could enhance accuracy by integrating multiple data sources and utilizing more advanced geographic analysis tools.

References
Kazakhstan Defense Enterprise Directory, 1995.
BatchGeo https://www.batchgeo.com - Tool used for geocoding and mapping.
