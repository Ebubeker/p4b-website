---
title: Isochrones
permalink: "/tutorials/isochrone/"
weight: 10
sections:
- training
description: Possible use cases and step-by-step tutorials for exemplary planning
  cases for the GOAT isochrone feature.


---
#### Description of the feature

[Isochrones](/docs/alphashape/ "Documentation on isochrones") are isolines connecting all points that can be reached from a specific starting point within a certain time interval. GOAT allows the calculation of isochrones that take factors such as speed, infrastructure network, and traveling time into account. This can be adjusted automatically by choosing between the modes “Walking”, “Bike”, “Pedelec”, “Transit” or “Car”. Isochrones can be used as an indicator of accessibility in one specific location.

#### Possible use cases (planning questions)

* How many supermarkets can be reached from a certain point in a 10-minute walk?
* How many people can access a public transport station within 5 minutes of cycling?
* How good is public transport accessibility in comparison to car accessibility?

#### Step-by-step tutorials for exemplary planning tasks

#### 1 Accessibility to supermarkets

##### 1.1 Planning question

How many supermarkets can be reached from a certain point in 10 minutes walking?

##### 1.2 Step-by-Step guide

1. Display all supermarkets by enabling the amenity "Supermarket" in the Thematic Data Filter under the category "Shop".

<img src="/images/tutorials/Isochrone/amenity_supermarket_en.webp" alt="amenity supermarket" style="max-height:400px;"/>

2. Zoom in into the area where you want to calculate the isochrone.

3. Select the the routing profile and the desired walking speed.

<img src="/images/tutorials/Isochrone/Isochrone_1.2_select_eng.webp"  alt="choose isochrone range" style="max-height:175px;"/>

4. Place the starting point for the isochrone.

<img src="/images/tutorials/Isochrone/starting_point_isochrone_en.webp"  alt="set starting point" style="max-height:150px;"/>

5. After the calculation has been carried out, a window with the results opens automatically. From this window you can see the number of supermarkets that can be reached within 10 minutes.

<img src="/images/tutorials/Isochrone/results_supermarkets_en.webp"  alt="results"/>

6.	 In the result window that opens, the results can be analyzed by the use of different graphs. Therewith it can be seen how the supermarkets are spacial distributed. 

<img src="/images/tutorials/Isochrone/results_supermarkets_2_en.webp"  alt="results"/>

#### 2 Bicycle Routing

##### 2.1 Planning question

How many people can reach the train station within 5 minutes by bike?

##### 2.2 Work steps

1. Change the routing mode to "cycling" and choose the desired speed.
   
<img src="/images/tutorials/Isochrone/Isochrone_2.2_select_eng.webp"  alt="Routing mode cycling" style="max-height:220px;"/>

2. Place the starting point for the isochrone calculation on the station.

<img src="/images/tutorials/Isochrone/starting_point_isochrone_en.webp"  alt="set starting point" style="max-height:150px;"/>

3. After the calculation has been carried out, a window with the results opens automatically. From this window you can see the population that can reach the train station within 10 minutes of cycling.

<img src="/images/tutorials/Isochrone/Isochrone_2.3_10minutes_eng.webp"  alt="result"/>

4. The travel time can interactively be adjusted to 5 minutes by moving the slider. 
   
<img src="/images/tutorials/Isochrone/Isochrone_2.3_5minutes_eng.webp"  alt="result"/>

5. Besides the table, the population count can be visualized in a graph.

<img src="/images/tutorials/Isochrone/Isochrone_2.result_different_graph_Eng.webp"  alt="download" style="max-height:300px;"/>

6. By clicking on the download button you can download the isochrones as GeoJSON, Shapefile or XML and the result table as Excel file.

<img src="/images/tutorials/Isochrone/Isochrone_2.4_export_eng.webp"  alt="download" style="max-height:230px;"/>




