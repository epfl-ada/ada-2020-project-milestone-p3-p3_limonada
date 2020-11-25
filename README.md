# Project Milestone P3

Authors:

* Alessandro Bianchi
* Davide Rosso
* Giorgio Savini

# Title
Influence of oil on the wellbeing of a country

# Abstract
Observing the plot of variable importance by mean decrease in Gini score in the paper (Figure 4), we noticed that the model developed by the authors does not show oil to be an influential factor for the outburst of a civil war. In contemporary history, however, oil has been perceived to be at the centre of many important geopolitical conflicts. We will therefore shift the focus from civil wars to wars in general. In our analysis, we will focus not only on the influence of oil on conflicts, but we will also try to evaluate its influence (or lack thereof) on the wellbeing of a country in general. To do this, we will look at economic indicators, such as income inequality and GDP per capita, as well as social ones like illiteracy rate, life expectancy, etc.
The final goal is to assess whether the common perception of oil as a major player in the stability and wellbeing of a country is mirrored by our findings.





# Research Questions
1. Is there a correlation between abundance/high exports of oil in a country and its population's wellbeing? For example, some of the variables we would like to consider are:
    * Income inequality
    * GDP
    * Child mortality
    * Illiteracy rate
    * Life expectancy
1. Which variables are influential when trying to predict the involvement of a country in a war? Is oil among these?
1. Given a treatment and a control group matched on influential variables and based on the findings of the previous point, try to find whether or not the treatment (presence of oil in the country) influences involvement in a war.

# Proposed Datasets
1. The main dataset that we will use is the one provided to us and used in the paper.
1. When possible, we will try to integrate data from the World Inequality Database (https://wid.world/) to evaluate how wealth is distributed across the population.

# Methods
To begin with, we will perform some data exploration to verify whether the data is unbalanced and correct it if necessary (e.g. by downsampling as in the paper).
1. [TODO]
1. We can replicate the analysis performed in the paper with Random Forests and rank the most influential features for the involvement in war, as in Figure 4.
1. We can perform a similar analysis to the one in HW2, with a propensity score matching on the most influential variables and use the ATE to assess the influence of oil on involvement in a war.

# Proposed Timeline

* **30/11 - 6/12**
    * Data exploration/visualization
    * Data wrangling
* **7/12 - 13/12**: 
* **14/12 - 18/12**:  
* **18/12 - 23/12**: Video


# Organization Within the Team

# Questions for TAs
