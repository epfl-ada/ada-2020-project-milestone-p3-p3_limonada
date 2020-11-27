# Project Milestone P3

Authors:

* Alessandro Bianchi
* Davide Rosso
* Giorgio Savini

# Title
Influence of oil on wellbeing and peace in a country

# Abstract
Observing the plot of variable importance by mean decrease in Gini score in the paper (Figure 4), we noticed that the model developed by the authors does not show oil to be an influential factor for the outburst of a civil war. In contemporary history, however, oil has been perceived to be at the centre of many important geopolitical conflicts. We will therefore shift the focus from civil wars to any conflict in a country's territory. In our analysis, we will focus not only on the influence of oil in conflicts, but we will also try to evaluate its impact (or lack thereof) on the wellbeing of a country in general. To do this, we will look at economic indicators, such as income inequality and GDP per capita, as well as social ones like illiteracy rate, life expectancy, etc.
The final goal is to assess whether the common perception of oil as a major player in the stability and wellbeing of a country is mirrored by our findings.





# Research Questions
**NOTE**: by "presence of war in a country" or "involvement of a country in a war" we mean that a war was fought on the country's territory, whether it was a civil war, or a foreign invasion, etc.

1. Is there a correlation between abundance/high exports of oil in a country and its population's wellbeing? For example, some of the variables we would like to consider are:
    * Income inequality
    * GDP
    * Child mortality
    * Illiteracy rate
    * Life expectancy
1. Which variables are influential when trying to predict the presence of war in a country? Is oil among these?
1. Given a treatment and a control group matched on influential variables and based on the findings of the previous point, try to find whether or not the treatment (abundance of oil) influences presence of war in a country.

# Proposed Datasets
1. The main dataset that we will use is the one provided to us and used in the paper.
1. When possible, we will try to integrate data from the World Inequality Database (https://wid.world/) to evaluate how wealth is distributed across the population (to answer research question 1).
1. Finally, we will also use the UCDP/PRIO (https://ucdp.uu.se/) dataset to collect data on the presence of war in a country.


# Methods
To begin with, we will perform some data exploration to verify whether the data is unbalanced and correct it if necessary (e.g. by downsampling as in the paper).

For the proposed research questions (1, 2, 3):
1. Statistical tests to determine correlation (Spearman, Pearson, etc). Sensitivity analysis to determine if causation is likely.
1. We can replicate the analysis performed in the paper with Random Forests and rank the most influential features for the involvement in war, as in Figure 4.
1. We can perform a similar analysis to the one in HW2, with a propensity score matching on the most influential variables and use the ATE to assess the influence of oil on involvement in a war.

# Proposed Timeline

* **30/11 - 6/12**
    * Data exploration/visualization
    * Data wrangling
    * First sketch of data analysis task
* **7/12 - 13/12**: 
    * Bulk of data analysis: the goal is to complete all tasks in order to be able to  revise them the following week.
    * Start writing report.
    * If necessary, adjust data wrangling
* **14/12 - 18/12**:
    * Full revision/refinement of 3 tasks
    * Interpretation of results
    * Complete deliverables
* **18/12 - 23/12**: 
    * Preparing, recording and editing the video


# Organization Within the Team
As we have already done for the 2 homeworks, we will use a "pair programming style" collaboration, where we all work on the assignment at the same time and explore the project together and provide feedback. We have taken this decision knowing that it might increase the overall time needed to complete the project. However, we think that the trade-off is worth it. We have seen that this method offers a very effective opportunity for us to all learn and practice at the same pace while playing on each others' strengths. 

