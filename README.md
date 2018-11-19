# BigelowResearch
> Modelling the effect of Kelp on Ocean Chemistry and Mussel Growth

This is the research I did for Bigelow Laboratory for Ocean Sciences, working closely with Professor Bruce Maxwell and Dr. Nichole Price

### Summary

Rising atmospheric CO2 has caused increased levels of CO2 in seawater, which can damage the strength of shellfish shells during the growth phrase. It has been hypothesized that by planting kelp in the vicinity of the shellfish, photosynthetic activity will create a halo of lower CO2 levels around the kelp farm, which can help the mussels grow at a faster pace. My job is to model the data collected from boating trips to evaluate the change.

### The Data

Data was collected from Bigelow labs from several boating trips around the kelp farm over a course of two years. There were many features that were collected, but we chose to focus on the following features:


| Variable Name   | Role          | Type        | Units   |
|:---------------:|:-------------:|:-----------:|:-------:|
| pCO2 / fCO2     | Response      | Numerical   |µatm     |
| O2              | Explanatory   | Numerical   |µmol / L |
| Salinity        | Explanatory   | Numerical   |Practical Salinity Unit (PSU)        |
| Water Temp      | Explanatory   | Numerical   |Cº       |
| Chlorophyll a   | Explanatory   | Numerical   |mg/m3    |
| Omega Aragonite | Explanatory   | Numerical   |unitless |


### Example Visualizations

<div style="display: block; float: left">
      <img src="PCA%20and%20Clustering/PCA%20with%20Clustering%20(n=4)/2017_12_19_cluster.png" width="250" height="250"> 
      <img src="PCA%20and%20Clustering/Boat%20Paths%20with%20Clustering%20from%20PCA%20Space/2017_12_19_boat_path.png" width="250" height="250">
      <img src="Visualization/Bilateral%20Filter/Single%20Frame%20Estimation/CO2/2018-03-28%20Corrected%20fCO2_single_frame.png" width="250 height="250">      
<div class="clear"></div>
</div>

      

Animations to display change of CO2 over time and more visualizations can be found in the <b>visualization</b> folder

### Results and Analysis

These visualizations have helped biologists and ecologists at Bigelow Laboratory understand the effect of a kelp farm in the vicinity of a mussels. My heatmaps have spotted an interesting anomaly: in some months, such as March 2018, the kelp seemed to have a negative effect on the surrounding. However, in other months, such as May 2017, the kelp seems to lower surrounding CO_2 levels. Therefore, a definitive conclusion cannot be established at this time, but it is clear that the kelp has an effect in its surroundings.

### Tools and Packages

I made my plots and visualizations using Matplotlib in Python. Data cleaning and processing was done using Pandas in Python. Some techniques I used were Bilateral Filtering and Gaussian Process for heatmaps.
