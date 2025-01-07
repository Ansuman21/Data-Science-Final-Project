# **Analyzing and Forecasting Restaurant Inspection Grades in NYC**

---

## **Introduction**
This project focuses on analyzing and predicting restaurant inspection outcomes in New York City by integrating historical inspection data with business acceleration metrics. Through data preprocessing, exploratory analysis, machine learning, and time series forecasting, the project provides actionable insights into trends and compliance patterns.


## **Dataset Details**

### **Sources**
1. **Restaurant Inspection Data:** Publicly available dataset containing inspection grades, violations, and related attributes.
2. **Business Acceleration Data:** Data capturing metrics like employee count, cuisine type, and establishment category.

### **Key Features**
- **Restaurant Name**
- **Inspection Date**
- **Inspection Score**
- **Grade**
- **Violation Description**
- **Employee Count**
- **Cuisine Type**
- **Borough**


## **Steps Taken to Solve the Problem**

### **1. Data Preprocessing**
- Removed missing values and handled outliers.
- Merged restaurant inspection data with business acceleration data to form a comprehensive dataset.
- Standardized numerical features using `StandardScaler`.

### **2. Exploratory Data Analysis (EDA)**
- Visualized inspection scores over time and across boroughs.
- Identified seasonal patterns and borough-specific trends.
- Highlighted correlations between business metrics and inspection outcomes.

### **3. Machine Learning Models**
- Built and evaluated multiple classification models to predict inspection outcomes:
  - **Random Forest** (Best performer with 99.79% accuracy)
  - Decision Tree
  - Logistic Regression
  - Support Vector Machine
  - XGBoost
- Performed hyperparameter tuning for optimization.

### **4. Explainability with LIME**
- Used LIME to explain predictions of the Random Forest model.
- Identified feature importance and localized explanations for individual predictions.

### **5. Time Series Forecasting**
- Modeled inspection scores over time using ARIMA (1, 1, 1).
- Forecasted inspection scores for the next 12 months.
- Visualized the declining trend in inspection scores, suggesting systemic issues.


## **Business Case Addressed**

1. **Regulatory Compliance:**
   - Identified patterns in compliance to guide public health interventions.
2. **Resource Allocation:**
   - Forecasted inspection scores to optimize allocation of inspection resources.
3. **Business Development:**
   - Highlighted business metrics influencing success and compliance.
4. **Customer Confidence:**
   - Helped businesses improve practices to enhance customer trust.
5. **Operational Improvements:**
   - Provided actionable insights for targeted operational enhancements.


## **Observations**
- **Trends:** Borough-specific and seasonal variations in inspection scores were evident.
- **Machine Learning Models:** Random Forest achieved the highest accuracy (99.79%), effectively predicting inspection grades.
- **Time Series Forecasting:** Forecasted scores exhibited a gradual decline over 12 months, indicating potential systemic issues.
- **Explainability:** LIME explanations provided insights into feature contributions, enabling better understanding of model predictions.


## **Recommendations**

1. **Address Declining Inspection Scores:**
   - Investigate and resolve systemic issues contributing to declining scores.
2. **Enhance Business Practices:**
   - Focus on features with high influence on compliance outcomes.
3. **Optimize Resource Allocation:**
   - Utilize forecast data to plan proactive inspections.
4. **Integrate Additional Data Sources:**
   - Include customer reviews and environmental factors to enrich analysis.
5. **Continuous Monitoring:**
   - Deploy dashboards for real-time tracking of inspection outcomes and forecasts.


## **Conclusion**
This project effectively combined data science techniques to analyze and forecast restaurant inspection outcomes. Insights from the analysis and predictive models provided valuable recommendations for maintaining compliance, improving operational practices, and enhancing public trust.

---

### **Author**

**Ansuman Patnaik**  
MS in Data Science & Analytics, Yeshiva University  
Email: ansu1p89k@gmail.com

