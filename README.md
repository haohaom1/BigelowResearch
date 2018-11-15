# BigelowResearch
> Modelling the effect of Kelp on Ocean Chemistry and Mussel Growth

This is the research I did for Bigelow Laboratory for Ocean Sciences, working closely with Professor Bruce Maxwell and Dr. Nichole Price

> Summary

Rising atmospheric CO2 has caused increased levels of CO2 in seawater, which can damage the strength of shellfish shells during the growth phrase. It has been hypothesized that by planting kelp in the vicinity of the shellfish, photosynthetic activity will create a halo of lower CO2 levels around the kelp farm, which can help the mussels grow at a faster pace. My job is to model the data collected from boating trips to evaluate the change.

> The Data

Data was collected from Bigelow labs from several boating trips around the kelp farm over a course of two years. There were many features that were collected, but we chose to focus on the following features:


| Variable Name   | Role          | Type        | Units   |
|:---------------:|:-------------:|:-----------:|:-------:|
| pCO2 / fCO2     | Response      | Numerical   |µatm     |
| O2              | Explanatory   | Numerical   |µmol / L |
| Salinity        | Explanatory   | Numerical   |Practical Salinity Unit (PSU)        |
| Water Temp      | Explanatory   | Numerical   |Cº       |
| Chlorophyll a   | Explanatory   | Numerical   |mg/m3    |
| Omega Aragonite | Explanatory   | Numerical   |unitless |


> Example Visualizations

<div style="display: block; float: left">
<img src="PCA%20and%20Clustering/PCA%20with%20Clustering%20(n=4)/2017_12_19_cluster.png" width="300" height="300"> 
<img src="PCA%20and%20Clustering/Boat%20Paths%20with%20Clustering%20from%20PCA%20Space/2017_12_19_boat_path.png" width="300 height="300">
<div class="clear"></div>
</div>

      

Animations to display change of CO2 over time and more visualizations can be found in the 

> Results and Analysis

These visualizations have helped biologists and ecologists at Bigelow Laboratory understand the effect of a kelp farm in the vicinity of a mussels. It is clear from the heatmaps that the kelp has an impact on the mussel growth, but whether the impact is positive or negative is yet to be determined. Therefore, definite conclusions on the effects of the kelp farm cannot be drawn yet.

> Tools and Packages

I made my plots and visualizations using Matplotlib in Python. Data cleaning and processing was done using Pandas.
