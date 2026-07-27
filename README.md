# Understanding Drivers of Protective Behaviours in Infectious Disease Outbreaks

## Dataset
This project uses multiple publicly available datasets:

**YouGov COVID-19 Behaviour Tracker**  
https://github.com/YouGov-Data/covid-19-tracker/tree/master/data

**Oxford COVID-19 Government Response Tracker (OxCGRT)**  
https://github.com/OxCGRT/covid-policy-dataset/tree/main/data

**Our World in Data (OWID) COVID-19 Dataset**  
https://github.com/owid/covid-19-data/tree/master/public/data

**Note:** The datasets are included as a ZIP file in this repository. The original data sources can be accessed through the links provided above.

---

## Introduction
Protective health behaviours such as mask wearing, hand washing, avoiding crowded areas, and self-isolation play an important role in reducing the spread of infectious diseases. These behaviours are influenced by several factors, including government policies, epidemiological conditions, and individual perceptions.

This study investigates how protective behaviours changed over time during the COVID-19 pandemic in Australia by integrating behavioural survey data, government policy measures, and epidemiological indicators. Machine learning and time-series modelling techniques are used to identify key behavioural drivers and analyse temporal changes.

---

## Objective
● Analyse how protective health behaviours evolve over time during an infectious disease outbreak.

● Evaluate the influence of demographic, behavioural, policy, and epidemiological factors on protective behaviours.

● Develop a unified framework by integrating behavioural, policy, and epidemiological datasets.

● Identify the key predictors of protective behaviours using the LightGBM classifier.

● Compare SARIMAX and Bayesian Structural Time Series (BSTS) models for modelling behavioural changes over time.

● Investigate delayed behavioural responses using lagged policy and epidemiological variables.

---

## Results and Discussion
● Behavioural intensity, age, individual perceptions, and government policy measures were identified as important drivers of protective behaviours.

● LightGBM effectively identified the most influential predictors for each behavioural outcome.

● Both SARIMAX and BSTS successfully modelled temporal changes in protective behaviours.

● BSTS generally achieved lower forecasting errors than SARIMAX across the four behavioural outcomes.

● Combining machine learning with time-series modelling provides a comprehensive framework for understanding behavioural responses during infectious disease outbreaks.

---

## Report
The complete project report, including the Overleaf source files, is provided as an **Overleaf ZIP: Understanding_Drivers_of_Protective_Behaviour_-_B** in this repository.
