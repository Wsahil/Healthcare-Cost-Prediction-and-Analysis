# Healthcare-Cost-Prediction-and-Analysis
This project aims to predict healthcare costs for individuals based on various factors such as age, BMI, smoking habits, exercise routine, and more. The analysis was performed on a dataset containing information about patients from seven states in the United States.

## Project Overview

The main goal of this project is to provide actionable insights to Health Management Organizations (HMOs) on how to lower healthcare costs for their customers. By analyzing the factors that contribute to higher healthcare expenses, we can identify potential areas for cost reduction and preventive measures.

## Dataset

The dataset used for this analysis contains the following variables:

- Age
- Location (state)
- Location type (urban or rural)
- Exercise routine (active or not active)
- Smoking status
- Body Mass Index (BMI)
- Yearly physical checkup (yes or no)
- Hypertension (yes or no)
- Gender
- Education level
- Marital status
- Number of children
- Total cost of healthcare for the past year

## Analysis and Modeling

We performed exploratory data analysis and data visualization to understand the relationships between the variables and healthcare costs. Various machine learning models, including linear regression, random forest regression, generalized linear models, and support vector machines, were trained and evaluated to predict whether an individual would have expensive healthcare costs or not.

Analyzing our data variables

![image](https://github.com/Wsahil/Healthcare-Cost-Prediction-and-Analysis/assets/71370836/d1d498d9-3449-435f-97e3-862f50f1841e)
![image](https://github.com/Wsahil/Healthcare-Cost-Prediction-and-Analysis/assets/71370836/7d642e59-57eb-492c-8edf-9c7d8bc8c660)
![image](https://github.com/Wsahil/Healthcare-Cost-Prediction-and-Analysis/assets/71370836/be3d2045-8bbd-45e2-a27f-dbb08d3917dc)
![image](https://github.com/Wsahil/Healthcare-Cost-Prediction-and-Analysis/assets/71370836/0fa69715-db48-40ed-b54b-305f2eafcd4a)
![image](https://github.com/Wsahil/Healthcare-Cost-Prediction-and-Analysis/assets/71370836/790d93d4-60eb-4c6a-94b5-10190e4127e1)



The key findings from our analysis include:

- Age is a significant factor, with older adults (over 59 years) more likely to have higher healthcare costs.
- Regular exercise contributes to a healthier lifestyle and lower healthcare costs.
- Smoking is a major contributor to expensive healthcare costs.
- Hypertension and stress can lead to serious health problems and higher healthcare expenses.
- BMI outside the ideal range (18.5-25) is associated with higher healthcare costs, with overweight and obese individuals being most affected.
- Families with two or more children tend to spend more on healthcare, suggesting that pediatric care contributes significantly to healthcare expenditure.

Cart model decision tree:

![image](https://github.com/Wsahil/Healthcare-Cost-Prediction-and-Analysis/assets/71370836/793e6152-9d9a-4ac7-8e97-5d5dc4df6390)


Published Shinyapp can be accessed here:- https://matthewpenn.shinyapps.io/Group1_Project/


## Recommendations

Based on our analysis, we recommend the following strategies for HMOs to reduce healthcare costs:

- Encourage and support young adults in cultivating an active lifestyle to prevent future health complications.
- Invest in campaigns and resources to educate people about the dangers of smoking and provide accessible rehabilitation programs.
- Promote healthy lifestyle choices, such as maintaining a healthy BMI and managing stress levels, to prevent or mitigate chronic conditions like hypertension.


## Usage

To reproduce the analysis and results, please refer to the provided code and documentation in this repository.
