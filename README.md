**Business Problem:**\
Swire Coca-Cola is experiencing significant losses due to unplanned machine downtimes across its production facilities. These disruptions, stemming from unexpected equipment breakdowns, lead to an estimated $60 million in annual losses. Addressing this challenge is critical for improving production efficiency and safeguarding revenue.

**Project Objective:**\
The objective of this project was to develop predictive models capable of identifying key drivers of machine downtimes and predicting major breakdowns. By leveraging data, we aim to provide actionable insights that enable Swire Coca-Cola to proactively address maintenance issues and reduce financial losses.

**Group's Solution:**\
Our team utilized advanced machine learning techniques, including Random Forest and Logistic Regression models, to analyze downtime patterns and predict major breakdowns. The Random Forest model achieved an impressive Out-of-Bag error rate of 6.93% and an accuracy of 89.59%, identifying critical predictors such as:
- **Minor Breakdown Events:** Machines with frequent minor breakdowns (<60 minutes) were found to be at higher risk for major breakdowns (>60 minutes).
- **Machine Age:** Equipment aged between 0-5 years accounted for the majority of planned maintenance activities, highlighting a key opportunity for better tracking and planning.

Our solution prioritizes data-driven decision-making by flagging high-risk machines and offering targeted maintenance recommendations.

**Individual Contribution:**\
My primary contributions to this project included:
1. **Data Cleaning and Feature Engineering:**  
   - Curating the dataset by addressing data gaps, including converting downtime thresholds into distinct categories (minor and major breakdowns).  
   - Introducing variables such as machine age and past downtime trends to enhance predictive power.
2. **Model Building and Evaluation:**  
   - Leading the development of the Random Forest model and optimizing hyperparameters to achieve high accuracy.  
   - Analyzing feature importance to identify key drivers of machine breakdowns.
3. **Insights and Recommendations:**  
   - Synthesizing findings into actionable recommendations for root cause analysis and preventative maintenance strategies.  
   - Creating visualizations that effectively communicated the impact of downtime predictors to stakeholders.

**Business Value:**\
By leveraging predictive maintenance insights, Swire Coca-Cola can:
- **Reduce Downtime Losses:** Cutting major breakdowns by 20% could save approximately $3.8 million annually, representing a 6.4% reduction in overall downtime-related losses.  
- **Enhance Maintenance Planning:** Insights into minor breakdowns and machine age allow for proactive scheduling of repairs and maintenance, minimizing disruptions.  
- **Improve Data Tracking:** Addressing gaps in machine-specific metrics, such as age and usage patterns, will bolster future predictive capabilities and streamline operations.

**Technical Difficulties:**\
During the project, we encountered several challenges:
1. **Data Gaps:** Approximately 98% of unplanned maintenance events were missing time-centric values, complicating model training and requiring careful feature engineering.  
2. **Imbalanced Data:** The dataset exhibited a significant imbalance between major and minor breakdown events, necessitating sampling techniques to improve model performance.  
3. **Variable Selection:** Identifying redundant or less-informative features (e.g., order ID) was critical to reducing noise and enhancing the model’s interpretability.

**What Was Learned:**\
This project reinforced several key lessons:
1. **Importance of Data Quality:** Addressing missing values and inconsistencies is essential for building reliable predictive models.  
2. **Feature Engineering:** Thoughtful creation of variables, such as categorizing downtime and tracking machine age, can significantly improve model performance and business relevance.  
3. **Actionable Insights:** Predictive models are most valuable when coupled with clear, data-driven recommendations that align with business goals.

**Next Steps:**\
To build on this project, Swire Coca-Cola should consider:
1. Implementing real-time machine age tracking to better capture the lifecycle of equipment.  
2. Establishing processes for root cause analysis of minor breakdowns to prevent escalation into major issues.  
3. Deploying the predictive models into production to continuously monitor and flag high-risk machines for targeted maintenance.
