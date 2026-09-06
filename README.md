# StadioCare 30-day hospital readmission prediction
## Motivation
STADIOcare Group operates a large private healthcare network in South Africa, serving approximately 3.1 million patients each year across 44 acute and day hospitals. With increasing pressure from older and sicker patients, rising operating costs, and a decline in operating margin from 15.9% to 13.8% over the past two years, the organisation needs to find ways of improving patient outcomes while using its existing resources more effectively.
One of STADIOcare’s key priorities for 2030 is to keep patients out of hospital when hospital care is not necessary and to support patients who are likely to deteriorate or return to hospital within a month. This creates an opportunity to use data to identify patients who may be at higher risk of a 30-day readmission after discharge. Early identification could allow healthcare teams to provide appropriate follow-up, primary care or virtual support to patients who may need additional assistance.
A data science solution could therefore support both patient care and operational efficiency. By using information from previous hospital encounters and patient characteristics to predict readmission risk, STADIOcare could better target its available resources rather than applying the same level of follow-up to every patient. This project is also aligned with the organisation’s broader goal of becoming more data-led and making better use of the information generated across its fragmented healthcare systems.
## Problem Statement
STADIOcare Group needs a reliable way to identify patients who are at increased risk of returning to hospital within 30 days of discharge, some patients return to hospital within 30 days of discharge, creating additional pressure on hospital capacity, healthcare resources and operating costs.Currently, it may be difficult to determine which patients require additional support after leaving hospital, particularly across a large and diverse healthcare network.
The problem this project will address is whether patient and hospital encounter characteristics can be used to predict the likelihood of a 30-day readmission. A data science model could help STADIOcare identify higher risk patients earlier, allowing healthcare teams to prioritise appropriate follow-up and support. This could contribute to better patient outcomes while supporting the organisation’s goal of reducing unnecessary hospital use and making more effective use of its healthcare resources.
## Project Structure
The repository is organised according to the main stages of the data science project.
data:contains raw and processed datasets.
Preprocessing:contains data quality checks and preprocessing activities.
feature-extraction: contains the creation and preparation of features for modelling.
Modelling:contains the development of models for predicting 30-day readmission risk.
evaluation: contains model evaluation and comparison results.
visualisation:contains scripts and notebooks used to create project visualisations.
utils:contains statistical helper functions and reusable supporting scripts.
Experiments:contains information about experimental setup and experimental results.