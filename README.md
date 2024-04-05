# Winning Space Race with Data Science

## Project background and context:

SpaceX advertises Falcon 9 rocket launches on its website, with a cost of 62 million dollars; other providers cost upward of 165 million dollars each, much of the savings is because SpaceX can reuse the first stage.
Therefore, if we can determine if the first stage will land, we can determine the cost of a launch. This information can be used if an alternate company wants to bid against SpaceX for a rocket launch. The goal of
this project is to develop a machine learning pipeline which will predict if the rocket will pass the first stage successfully.

## Problem statements:
❑ Major factors/features to determine the landing of first stage of the rocket successfully.
❑ The operating conditions to ensure a successful landing of the rocket launch.

## Executive Summary:
• Data collection methodology: Data was collected using SpaceX API and web scraping from Wikipedia.
• Perform datawrangling: One-hot encoding for categorical features of the machine learning, data cleaning of null values and irrelevant columns.
• Perform exploratory data analysis (EDA) using visualization andSQL: EDA using python libraries (Matplotlib, Seaborn) and using SQL, feature engineering.
• Perform interactive visual analytics using Folium andPlotlyDash: Applied Folium to view previously observed correlations interactively.
• Perform predictive analysis using classification models: Classification models (Logistic regression, Support vector machine, K-nearest neighbor and Decision Tree) have been built and evaluated using GridSearch 
  for the best classifier.

  ## Conclusion:
 
• KSC LC-39A had the most successful launches of any sites.
• The larger the flight amount at a launch site, the greater the success rate at a launch site.
• Launch success rate started to increase in 2013 till 2020.
• Most successful launch outcomes are observed in the payload range of 2000 – 5300 kg.
• FT Booster version had the most successful launch outcomes with success rate of around 71% in the 2000 – 5300 kg payload range and around 64% success rate in the 500 – 9500 kg payload range.
• Orbits ES-L1, GEO, HEO, SSO, VLEO had the most success rate.
• Both Logistic Regression and Decision tree classifiers had shown the optimal machine learning algorithms for the provided dataset with test accuracy of 94.44%.
