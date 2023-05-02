# Outbreak detection of COVID-19 epidemic: Machine Learning approach

This is the code used in 

'Outbreak detection of COVID-19 epidemic: Machine Learning approach'  

Giphil Cho, Jeong Rye Park, Yongin Choi, Hyeonjeong Ahn, Hyojung Lee

[link]()



### Abstract

**Background:** The rapid spread of the coronavirus disease (COVID-19) pandemic has necessitated the development of predictive models to help healthcare providers prepare and respond to outbreaks more quickly and effectively, ultimately leading to better patient care. Detecting outbreaks early and having warning systems in place are crucial for preventing and controlling the spread of epidemics.

**Objective:** This study aimed to propose a machine learning-based method to predict the transmission trend of COVID-19 and propose a new approach for detecting the start time of new outbreaks by analyzing epidemiological data in the Republic of Korea.

**Methods:** We developed a risk index to measure the change in the transmission trend. ML is applied to predict COVID-19 transmission trends, categorized into three labels (decrease (L0), maintain (L1), increase (L2)). We utilized Support Vector Machine (SVM), Random Forest (RF), and XGBoost (XGB) as machine learning (ML) techniques. To determine the optimal hyperparameters for these three models, we employed grid search methods. We proposed a new method for detecting the start time of new outbreaks based on Label 2, which was sustained for at least 14 days (i.e., the duration of maintenance). We compared the performance of different ML models to identify the most accurate approach for outbreak detection. We conducted sensitivity analysis for the duration of maintenance between 7 days and 28 days.

**Results:** ML methods demonstrated high accuracy (over 93%) in estimating the classification of the transmission trends. Our proposed method was successful in accurately predicting the start time of new outbreaks, enabling us to detect a total of seven estimated outbreaks, while there were five reported outbreaks between March 2020 and October 2022 in Korea. It means that proposed method could detect minor outbreaks. Among the ML models, the RF and XGB classifier exhibited the highest accuracy in outbreak detection.

**Conclusions:** The study highlights the strength of the method in accurately predicting the timing of an outbreak using an interpretable and explainable approach. It could provide a standard for predicting the start time of new outbreaks and detect future transmission trends. This method can contribute to the development of targeted prevention and control measures and enhance resource management during the pandemic.




