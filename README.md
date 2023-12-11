# SpaceX Data Analysis and Predictive Modeling

<div align="center">
    <img src="https://github.com/Ilhamshuu/Launch-Rocket-Prediction-IBMDataScience/assets/130891104/1cd8061f-c3ee-41ea-b390-2ef62eb55b6a" alt="Rocket">
</div>

## Summary
An analysis of SpaceX data, utilizing machine learning models like Logistic Regression, Support Vector Machine, Decision Tree Classifier, and K Nearest Neighbors, revealed an average accuracy rate of 83.33% in classifying successful landings. However, these models consistently over-predicted success.

Key insights suggest a need for more comprehensive data to refine model accuracy and prevent biased predictions. Enhancing the dataset with diverse features could greatly improve model performance.

In essence, while the initial models achieved decent accuracy, they tended to overestimate successful landings. Further data augmentation is crucial to develop more reliable and balanced predictive models.

## Background
### Commercial Space Age is Here
- SpaceX offers the best pricing ($62 million vs. $165 million USD) due to its ability to recover part of the rocket (Stage 1).
- Competitor Space Y aims to compete with SpaceX.

## Problem
Space Y tasks us to train a machine learning model to predict successful Stage 1 recovery.

## Methodology
### Data Collection Methodology
- Combined data from SpaceX public API and SpaceX Wikipedia page.
- Data wrangling and classification of true landings as successful and unsuccessful.
### Exploratory data analysis (EDA)
- Exploratory data analysis (EDA) using visualization and SQL.
- Interactive visual analytics using Folium and Plotly Dash.
### Modeling
- Predictive analysis using classification models.
- Tuning models using GridSearchCV.

## Conclusion
Our task: to develop a machine learning model for Space Y aiming to compete against SpaceX.
The goal of the model is to predict when Stage 1 will successfully land to save ~$100 million USD.
- Used data from a public SpaceX API and web scraping SpaceX Wikipedia page.
- Created data labels and stored data into a DB2 SQL database.
- Developed a dashboard for visualization.
- Achieved a machine learning model accuracy of 83%.
- Allon Mask of Space Y can use this model to predict with relatively high accuracy whether a launch will have a successful Stage 1 landing before the launch to determine whether the launch should proceed.
- Recommending further data collection to enhance machine learning model accuracy.

## Want More Details?
For more detailed information, view the [PowerPoint presentation here](https://github.com/Ilhamshuu/Launch-Rocket-Prediction-IBMDataScience/blob/7f226c68fb44d858ca4d5c7d426fd649fddc8eab/Final_Project_PPT.pptx).

