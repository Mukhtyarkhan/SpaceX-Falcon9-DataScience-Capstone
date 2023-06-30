## IBM Data Science Professional Certificate
The completion of the IBM Data Science Professional Certificate on Coursera marked a significant milestone in my educational journey. This comprehensive program provided me with the necessary knowledge and skills to excel in the field of data science. You can learn more about the certification program on Coursera here.\n
Now, let's delve into a fascinating project I worked on as part of the certification:
## Project Overview
The project aimed to address a crucial question related to SpaceX rocket launches. SpaceX offers Falcon 9 rocket launches at a significantly lower cost compared to other providers. One of the key factors contributing to this cost reduction is SpaceX's ability to reuse the first stage of the rocket. The objective of the project was to predict the success of the first-stage landing of the Falcon 9 rocket. This information could be valuable for companies interested in competing with SpaceX for rocket launch contracts
## Problem Statement
1. Identify the factors that influence the success of landing the Falcon 9 rocket's first stage.\n
2. Examine the relationships between variables that impact the success rate of the first-stage landing.\n
## Methodology
To tackle this problem, the following methodology was employed:\n

1. Data collection from the Spacexdata API and Wikipedia web scraping.
2. Data wrangling and preparation.
3. Exploratory data analysis (EDA) utilizing visualization techniques and SQL.
4. Interactive visual analytics using tools such as Folium and Plotly Dash.
5. Predictive analysis employing classification models.
## Key Findings
Through the project, several significant findings were uncovered:\n

The success rate of the Falcon 9 first stage landing improves with a larger flight number and a lower payload mass at launch sites.
The overall success rate of rocket launches exhibits a positive trend between 2013 and 2020, with a minor negative trend observed in 2017-2018.
The orbit types associated with the highest success rates are ES-L1, GEO, HEO, SSO, and VLEO.
The most successful launch site identified during the analysis is KSC LC-39A.
All launch sites are located far from railways, highways, and cities, while being in close proximity to coastlines.
Based on the project's results, the decision tree classification model proved to be the most suitable for predicting the success of the first stage landing. The optimal parameters for this model were criterion: gini, max_depth: 6, max_features: auto, min_samples_leaf: 2, min_samples_split: 5, and splitter: random.
