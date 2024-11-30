# Capstone Project: Predictive Maintenance for Swire Coca-Cola

## **Business Problem:**  
Swire Coca-Cola is experiencing significant financial losses due to unplanned machine downtimes across its production facilities, amounting to an estimated $60 million annually. These unexpected disruptions lead to production inefficiencies and revenue loss. Addressing this challenge is critical to maintaining operational efficiency and reducing the financial impact of unplanned breakdowns.

## **Project Objective:**  
The goal of this project was to develop predictive models that identify key drivers of machine downtimes and estimate the likelihood and duration of major breakdowns. By leveraging historical data, we aimed to provide actionable insights that allow Swire Coca-Cola to implement proactive maintenance strategies, improving production continuity and reducing downtime-related losses.

---

## **Group's Solution:**  
Our team utilized advanced statistical and machine learning methods, including Random Forest, Logistic Regression, and Linear Regression models, to analyze downtime patterns and predict machine failures. Key achievements include:  
- **Random Forest Model:** Achieved an Out-of-Bag error rate of 6.93% and a test accuracy of 89.59%, effectively identifying high-risk equipment.  
- **Linear Regression Model:** Estimated the duration of downtime events, enabling better scheduling and resource allocation for planned maintenance.  
- **Key Insights:**  
  - **Minor Breakdown Events:** Machines with frequent minor breakdowns (<60 minutes) were at higher risk for major breakdowns (>60 minutes).  
  - **Machine Age:** Equipment aged 0–5 years exhibited the most planned maintenance activity, suggesting gaps in tracking and preventive strategies.  

These models prioritize high-risk equipment and provide data-driven recommendations to optimize maintenance efforts.

---

## **Individual Contribution:**  
**Hunter Nilsen**  
My contributions focused on the development and interpretation of the **Linear Regression Model**:
1. **Model Building and Feature Engineering:**  
   - Built a linear regression model to predict the duration of maintenance events based on features such as machine age, maintenance type, and functional location.  
   - Engineered variables, including machine age and downtime categories, to improve the model's predictive power.
2. **Insights and Interpretations:**  
   - Interpreted the regression coefficients to identify significant predictors of downtime durations.  
   - Synthesized findings into actionable recommendations for improving scheduling and resource allocation.  
3. **Collaborative EDA:**  
   - Assisted in the early stages of data exploration, visualizations, and preparation for model inputs.  

---

## **Business Value:**  
By implementing these predictive insights, Swire Coca-Cola can achieve:  
- **Reduced Downtime Losses:** Cutting major breakdowns by 20% could save approximately $3.8 million annually, representing a 6.4% reduction in overall downtime-related losses.  
- **Enhanced Maintenance Planning:** Insights from the regression model enable better alignment of maintenance schedules with predicted durations, minimizing disruptions.  
- **Improved Data Tracking:** Addressing gaps in machine-specific metrics, such as age and usage patterns, will enhance future predictive capabilities and streamline maintenance operations.

---

## **Difficulties Encountered:**  
1. **Data Gaps:**  
   - Approximately 98% of unplanned maintenance events were missing critical time-based metrics, complicating feature engineering and model training.  
   - Addressed this by imputing missing values where feasible and focusing on available data for actionable insights.  
2. **Imbalanced Data:**  
   - The dataset showed a significant imbalance between major and minor breakdowns, which required careful handling to avoid bias in predictions.  
   - Sampling techniques and alternative metrics helped improve model performance.  
3. **Variable Selection:**  
   - Features like `ORDER_ID` and `PLANT_ID` were removed to reduce noise and enhance interpretability.  

---

## **What Was Learned:**  
This project highlighted several important lessons:  
1. **The Importance of Data Quality:**  
   - Cleaning and preparing real-world data is essential to ensuring accurate and reliable model outputs.  
2. **The Value of Feature Engineering:**  
   - Thoughtfully engineered features, such as categorizing breakdowns and tracking machine age, significantly enhance model performance and business relevance.  
3. **Modeling Challenges:**  
   - Balancing predictive accuracy and interpretability is critical when working with stakeholders. Data-driven recommendations must align with business goals to drive actionable change.  

---  

## **Next Steps:**  
1. **Real-Time Tracking:**  
   - Implement real-time machine age and usage tracking to improve predictive accuracy for future models.  
2. **Root Cause Analysis:**  
   - Conduct root cause analysis on frequent minor breakdowns to prevent escalation into major issues.  
3. **Deployment:**  
   - Integrate the predictive models into operational workflows to continuously monitor and flag high-risk machines for proactive maintenance.  
