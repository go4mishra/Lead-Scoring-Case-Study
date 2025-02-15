# Lead Scoring Case Study
**Problem Statement**
X Education aims to optimize its lead conversion process by identifying the most promising leads—those most likely to convert into paying customers.
To achieve this, we need to develop a lead scoring model that assigns a score to each lead, helping the company prioritize follow-ups.

**Key requirements:**
- Assign a lead score between 0 and 100 based on conversion probability.
- Ensure that high-scoring leads have a higher likelihood of conversion, while low-scoring leads have a lower likelihood.
- Target a lead conversion rate of approximately 80%, as specified by the CEO.

**Goals and Objectives**
The primary goal of this case study is to build a logistic regression model that helps X Education efficiently target potential leads.
**Specific Objectives:**
- Develop a predictive model using logistic regression to assign a lead score.
- Ensure that the model is adaptable to future changes in business requirements.
- Identify key features influencing lead conversion and provide data-driven recommendations.
- Use the model’s insights to improve lead nurturing strategies and optimize marketing efforts.

Additionally, a separate document outlines additional business challenges that the model should accommodate. This document, along with the final PowerPoint presentation, will include the necessary insights and recommendations.

**Approach & Steps Followed**
The analysis was carried out in a structured manner using the following steps:
- Data Acquisition & Reading – Importing the dataset for analysis.
- Data Cleaning – Handling missing values, duplicates, and inconsistencies.
- Exploratory Data Analysis (EDA) – Understanding data distributions and relationships.
- Feature Engineering & Dummy Variable Creation – Converting categorical variables into numerical form.
- Train-Test Split – Splitting the dataset into training (70%) and testing (30%) subsets.
- Model Building – Implementing logistic regression to predict lead conversion probability.
- Making Predictions – Applying the trained model to test data.
- Model Evaluation – Assessing model performance using:
    - Confusion Matrix
    - Accuracy, Sensitivity, Specificity
    - Precision-Recall Analysis
    - ROC-AUC Curve
- Optimizing the Model – Selecting the optimal cutoff score for lead conversion predictions.
- Final Predictions & Business Insights – Interpreting results and providing actionable recommendations.

**Key Findings & Business Insights**
Based on the analysis, the most critical factors influencing lead conversion include:
- Total time spent on the website – Higher engagement correlates with higher conversion.
- Total number of visits – More visits indicate greater interest.
- Lead Source – Leads from Referrals, Olark Chat, and the Welingkar website have higher conversion probabilities.
- Last Activity – Leads with recent interactions such as Phone Calls, SMS Sent, or Olark Chat have better chances of conversion.
- Current Occupation – Working professionals are the most likely to enroll in courses.
- By leveraging these insights, X Education can enhance its lead nurturing strategy and improve its overall conversion rates.

**Files Provided**
  File Name	                                           Description
1. Lead Score Case Study.ipynb	                       Python notebook with code and data analysis
2. Leads.csv	Dataset                                  containing lead information
3. Leads Data Dictionary.xlsx	                         Explanation of dataset columns and values
4. Assignment Subjective Questions.pdf	               Subjective business questions and responses
5. Lead Score Case Study.pdf	                         Final presentation with model insights and recommendations
6. Summary.pdf	                                       Overview of the entire analysis and key findings

**Next Steps & Recommendations**
To maximize lead conversion success, X Education should:

✅ Prioritize leads from the Welingkar website as they have the highest conversion rate.

✅ Actively engage referral-based leads, as they are strong potential customers.

✅ Follow up with customers whose last activity was a phone call or SMS to improve conversion rates.

✅ Focus on working professionals, as they form the largest customer segment seeking upskilling opportunities.

✅ Allocate more resources to Mumbai-based leads, as they show the highest conversion rates.

🚫 Avoid contacting leads who opted for "Do Not Email," have an unspecified specialization, or listed their occupation as "Other", as they have the lowest conversion potential.

By implementing these data-driven recommendations, X Education can improve its marketing efficiency, enhance customer engagement, and boost lead conversion rates.
