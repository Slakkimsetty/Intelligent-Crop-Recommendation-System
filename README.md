# Intelligent-Crop-Recommendation-System
Project to implement the Crop Recommendor System to help farmers selecting crop.

---
## Problem Statement
* Crop prediction is an important agricultural problem. The Agricultural  primarily depends on weather conditions, pesticides.
* Accurate information about crop yield history is critical for making decisions about agricultural risk management and future predictions.
* The **main objective** project is to predict crop, which can be extremely useful to farmers in planning for harvest and sale of grain harvest.

---
## Dataset 
- This dataset was build by augmenting datasets of rainfall, climate and fertilizer data available for India, found on Kaggle :
   https://www.kaggle.com/atharvaingle/crop-recommendation-dataset
   
**Attributes used :** 
* N - ratio of Nitrogen content in soil 
* P - ratio of Phosphorous content in soil
* K - ratio of Potassium content in soil
* temperature - temperature in degree Celsius
* humidity  - relative humidity in %
* ph - ph value of the soil
* rainfall - rainfall in mm

**Dataset Sample :**

![image](https://user-images.githubusercontent.com/95501767/147553568-231e326b-f144-49c4-90d4-06c1efb29683.png)

---
## Project Roadmap
*	Understand the problem statement<br />
*	Import Necessary Dependencies<br />
*	Read and Load the Dataset<br />
*	Exploratory Data Analysis<br />
*	Data Pre-processing<br />
* Missing values<br/>
* Encoding & Statistical Analysis<br />
* Checking Outliers<br />
*	Data Visualization<br />
*	Splitting our data into Train and Test Subset<br />
*	Model Building<br />

## Model Building 
In this Problem Statement we have used Five differernt models respectively :
  1. Decision Trees
  2. Random Forest
  3. Multilayer Percptron 
  4. Naïve Bayes
  5. KNN Classifier

---

## Conclusion
Upon evaluating all the models we can conclude the following details i.e.
#### Accuracy: 
As far as the accuracy of the model is concerned Random Forest Classifier performs better than all the orther algorithms.
