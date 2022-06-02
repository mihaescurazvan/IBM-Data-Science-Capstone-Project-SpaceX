# IBM-Data-Science-Capstone-Project-SpaceX

##  Project background and context

Space X advertises Falcon 9 rocket launches on its website with a cost of 62 million dollars; 
other providers cost upward of 165 million dollars each, much of the savings is because Space 
X can reuse the first stage. Therefore, if we can determine if the first stage will land, we can 
determine the cost of a launch. This information can be used if an alternate company wants to 
bid against space X for a rocket launch. This goal of the project is to create a machine learning 
pipeline to predict if the first stage will land successfully.


## Problems you want to find answers
  * What factors determine if the rocket will land successfully?
  * The interaction amongst various features that determine the success rate of a successful 
landing.
  * What operating conditions needs to be in place to ensure a successful landing program?
  
## Project Summary

  * Summary of methodologies
      * Data Collection through API
      * Data Collection with Web Scraping
      * Data Wrangling
      * Exploratory Data Analysis with SQL
      * Exploratory Data Analysis with Data Visualization
      * Interactive Visual Analytics with Folium
      * Machine Learning Prediction
  * Summary of all results
      * Exploratory Data Analysis result
      * Interactive analytics in screenshots
      * Predictive Analytics result

## Executive Summary
  * Data collection methodology:
    * Data was collected using SpaceX API and web scraping from Wikipedia.
  * Perform data wrangling
    * One-hot encoding was applied to categorical features
  * Perform exploratory data analysis (EDA) using visualization and SQL
  * Perform interactive visual analytics using Folium 
  * Perform predictive analysis using classification models
    * How to build, tune, evaluate classification models
  
## Training models 

  * Logistic Reggression 
  * Decision Trees
  * Support Vector Machines
  * KNN
  * Grid Search

## Code and Resources Used 
**Python Version:** 3.7  
**Packages:** pandas, numpy, sklearn, folium, seaborn, sql

**Check the specialization:** [IBM Data Science Specialization](https://www.coursera.org/professional-certificates/ibm-data-science?utm_source=gg&utm_medium=sem&campaignid=2087860785&utm_campaign=10-IBM-Data-Science-ROW&utm_content=B2C&adgroupid=79675709271&device=c&keyword=ibm%20data%20science&matchtype=b&network=g&devicemodel=&adpostion=&creativeid=489197596485&hide_mobile_promo&gclid=CjwKCAjwv-GUBhAzEiwASUMm4r7RmgEdw47TtLkxoXDQwDN9-0BGJq8gz8bESq0N2slU4m3v46c5pBoCV1IQAvD_BwE)

## Conclusions

We can conclude that:
  * The larger the flight amount at a launch site, the greater the success rate at a 
  launch site.
  * Launch success rate started to increase in 2013 till 2020.
  * Orbits ES-L1, GEO, HEO, SSO, VLEO had the most success rate.
  * KSC LC-39A had the most successful launches of any sites.
  * The Decision tree classifier is the best machine learning algorithm for this task.




