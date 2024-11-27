# Car Crash Survival Prediction using Logistic Regression and Linear Discriminant Analysis

## Executive Summary:
This project aims to predict car crash survival outcomes using Logistic Regression and Linear Discriminant Analysis. By analyzing the impact of various factors such as airbag status, seatbelt usage, and crash severity, the model helps derive recommendations to improve vehicle safety standards.

## Introduction:
The goal is to predict whether a person survives a car crash based on data such as airbag deployment, seatbelt usage, crash impact type, and more. Logistic Regression and Linear Discriminant Analysis were applied for prediction. The performance was evaluated using accuracy, confusion matrices, and ROC curves.

## Data Description:
The dataset contains 15 features, including categorical (e.g., airbag, sex) and continuous (e.g., age, weight) variables, and is used to predict the **Survived** outcome (binary).

## Exploratory Data Analysis:
- Missing values handled and outliers detected.
- Descriptive statistics and correlations were analyzed.
- Visualizations (heatmaps, pair plots, box plots) were used to explore relationships between variables.

## Models & Performance Metrics:
- **Logistic Regression:** Achieved 99.1% accuracy on the training set and 98.8% on the test set.
- **Linear Discriminant Analysis:** Achieved 99% accuracy on the training set and 98.8% on the test set.
- Both models were evaluated using confusion matrices, accuracy scores, and ROC AUC.

## Recommendations & Insights

Based on the results from the **Logistic Regression** and **Linear Discriminant Analysis (LDA)** models, the following insights and actionable recommendations have been derived to help improve road safety and car design:

### 1. **Frontal Impacts & Driver Behavior**
   - **Insight:** A significant number of accidents in the dataset involve frontal impacts, which suggests a correlation with poor driver attention or vehicle control.
   - **Recommendation:** 
     - **Driver Training Programs:** Implement mandatory training programs focusing on defensive driving and alertness.
     - **Sleep Alerts:** Introduce driver fatigue detection systems that alert drivers when they are at risk of falling asleep, especially on long journeys.
     - **Outcome Estimate:** A 10-15% reduction in frontal impact accidents could be achieved through better driver behavior.

### 2. **Airbag Deployment**
   - **Insight:** The data reveals that many cars involved in crashes did not have airbags deployed, which is critical in preventing fatalities.
   - **Recommendation:** 
     - **Mandate Airbags in All Vehicles:** Airbags should be mandatory in all vehicles, regardless of their model or price range. This would drastically reduce fatalities and serious injuries in accidents.
     - **Outcome Estimate:** Making airbags a standard feature could potentially reduce crash fatalities by up to 30%, based on studies showing their life-saving effectiveness.

### 3. **Seatbelt Usage**
   - **Insight:** The analysis shows that seatbelt use is crucial in reducing fatalities during car crashes.
   - **Recommendation:** 
     - **Enforce Strict Seatbelt Laws:** Governments should implement stricter regulations and penalties for drivers and passengers not wearing seatbelts.
     - **Outcome Estimate:** Enhanced seatbelt use enforcement could save thousands of lives annually. Seatbelts can reduce the risk of fatal injury by 45% and moderate injury by 50%.

### 4. **Enhancement of Vehicle Safety Features**
   - **Insight:** Vehicles with more advanced safety features, including airbags, tend to show higher survival rates.
   - **Recommendation:** 
     - **Incorporate Advanced Driver Assistance Systems (ADAS):** The government should incentivize manufacturers to include features such as automatic emergency braking, lane-keeping assistance, and adaptive cruise control to improve safety.
     - **Outcome Estimate:** These systems could reduce accidents by up to 40%, according to studies conducted on their effectiveness in preventing collisions.

### 5. **Improved Crash Data Collection & Transparency**
   - **Insight:** The dataset revealed the importance of robust and comprehensive crash data in making accurate predictions.
   - **Recommendation:** 
     - **Public Access to Crash Data:** Create a centralized database accessible to the public, researchers, and manufacturers to help in understanding crash patterns and improving vehicle designs.
     - **Outcome Estimate:** This could lead to continuous improvement in vehicle safety features, with a potential 5-10% reduction in accidents annually.

### 6. **Comprehensive Analysis for Vehicle Manufacturers**
   - **Insight:** The models showed that the type of vehicle and its crashworthiness significantly affect survival rates.
   - **Recommendation:** 
     - **Strengthen Regulations for Vehicle Design:** Governments should impose stricter safety standards on manufacturers, especially for frontal crashworthiness and airbag systems.
     - **Outcome Estimate:** This could lead to a 20-25% improvement in overall vehicle safety across all models.

