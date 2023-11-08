## What is a Stroke?

* A stroke is a medical emergency, and prompt treatment is crucial. Early action can reduce brain damage and other complications.
* A stroke happens when the blood supply to part of the brain is interrupted or reduced, preventing brain tissue from getting oxygen and nutrients. Brain cells begin to die in minutes. As a result, someone who has had a stroke may have trouble speaking, thinking, or walking.
* According to the Singapore Stroke Registry Annual Report 2020, the number of stroke episodes increased from 5,890 episodes in 2010 to 8,846 episodes in 2020. However, the age-standardised mortality rate and the 30-day case fatality rate both declined significantly during this period. Ischaemic stroke was the most common type of stroke, accounting for about 80% of the cases. Hyperlipidemia and hypertension were the two most common risk factors among stroke patients, affecting more than 80% of them.
* Stroke risk increases with age, but strokes can — and do — occur at any age. The good news is that most strokes can be prevented, and early signs of a stroke can help reduce the severity of the stroke.

## Research Objective
* Different machine learning models have been developed to predict the likelihood of a stroke occurring in the brain.
* This project intends to use machine learning algorithms to develop and train a model for reliable prediction and study analysis, hence making it possible to anticipate the onset of a stroke such that patients can be treated promptly to avoid irreversible damage or death.

Source of Dataset : https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset

## Data Visualization
<img width="1000" alt="image" src="https://github.com/leowmc/Stroke-detection-with-ML/assets/144865130/79a934bb-0121-4389-8903-50cfd53839d1">

* For the gender attribute, 0 means male and 1 means female. There are more female samples than male samples in this dataset.
* Based on the age distribution, the sample's average age is in the 40s, and the upper limit is approximately 60.
* For hypertension, 0 means the individual does not have it, while 1 means the person has it.
* The total number of individuals who are healthy and have no history of heart disease is achieved in this dataset.

  <img width="500" alt="image" src="https://github.com/leowmc/Stroke-detection-with-ML/assets/144865130/ad340395-1009-4ad2-93dd-2a123be49b42">

<img width="800" alt="image" src="https://github.com/leowmc/Stroke-detection-with-ML/assets/144865130/a2c81e30-212d-46dc-8194-38c2025119a5">

* Age, heart disease, glucose level, hypertension, ever_married, and bmi showed positive correlation with stroke, the target feature.

## Data Modeling
The machine learning algorithms to be explored in this project are :
 - Logistic Regression
 - Random Forest
 - Decision Tree
 - Support Vector Machine
 - k-Nearest Neighbor (KNN)

<img width="333" alt="image" src="https://github.com/leowmc/Stroke-detection-with-ML/assets/144865130/552432c4-4ce4-4f16-8ba7-f0f2986524f8">
<img width="326" alt="image" src="https://github.com/leowmc/Stroke-detection-with-ML/assets/144865130/40881a2e-40f5-4296-bb99-abf15b693cc1">
<img width="319" alt="image" src="https://github.com/leowmc/Stroke-detection-with-ML/assets/144865130/a83446da-0477-4e72-b272-1637a6dbd339">
<img width="323" alt="image" src="https://github.com/leowmc/Stroke-detection-with-ML/assets/144865130/7ab04bdd-7892-4376-954f-4749ddd4f5d8">
<img width="316" alt="image" src="https://github.com/leowmc/Stroke-detection-with-ML/assets/144865130/ca94b308-d2cd-44f3-8347-20cceefbea97">

## Model Performance Evaluation
* The accuracy of logistic regression model is: 79.6%
* The accuracy of Random Forest model is: 90.2%
* The accuracy of Decision Tree model is: 88.6%
* The accuracy of Support Vector Machine model is: 70.8%
* The accuracy of KNN model is: 79.2%

## Conclusion
Random Forest model achieved the highest accuacy of 90% as this model outperforms the other methods tested. Therefore, the development of machine learning model can help in early detection of stroke and saving lives.


