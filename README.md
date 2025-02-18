# PFG Bank Credit Card Solicitation Campaign Optimization

## Project Description
This case study involved developing a data-driven strategy for PFG Bank's direct mail credit card solicitation campaign, targeting up to 750,000 prospects with various product offers. The objective was to maximize profits through strategic customer segmentation and targeted solicitation, utilizing uplift and propensity modeling techniques with Logistic Regression, Random Forest, and XGBoost algorithms. The project included comprehensive model training, evaluation, and interpretation to pinpoint the most lucrative customer segments for the campaign.

## Technology Stack
- **Data Handling and Analysis**: Python, pandas, pyrsm
- **Machine Learning Models**: Logistic Regression, Random Forest, XGBoost
- **Modeling Tools**: GridSearchCV for hyperparameter tuning, sklearn for pipelines
- **Visualization**: Matplotlib for data visualization and performance comparison

## Key Accomplishments

### 1. Data Preparation and Segmentation
- **Dataset Integration**: Merged multiple datasets into a single comprehensive dataset for uplift analysis.
- **Sampling Strategy**: Utilized stratified sampling to create balanced training and test splits, ensuring representative coverage of key variables.
- **Variable Enhancement**: Introduced new variables including a treatment flag and computed uplift scores for each prospect.

### 2. Model Training and Tuning
- **Logistic Regression**: Developed models for control and treatment groups to predict conversion probabilities and calculated uplift scores.
- **Random Forest**: Optimized Random Forest models with GridSearchCV, adjusting hyperparameters like `n_estimators` and `max_features` for enhanced performance.
- **XGBoost**: Applied XGBoost for its gradient boosting capabilities, fine-tuning parameters such as `max_depth` and `n_estimators` for superior accuracy and uplift.

### 3. Performance Evaluation and Comparison
- **Model Metrics**: Assessed models based on AUC, incremental uplift, and total incremental profit.
- **Model Comparison**: Analyzed and compared the efficacy of uplift models versus propensity models using various metrics.
- **Visualization**: Employed incremental uplift plots and bar charts to visualize performance and identify the most responsive customer segments.

### 4. Profit Optimization
- **Profit Calculation**: Estimated incremental profits derived from uplift models to determine the optimal targeting percentage.
- **Targeting Recommendations**: Showed that uplift modeling typically offers higher profits than propensity modeling, informing strategic targeting decisions for the campaign.

## Key Outcomes

### Optimized Targeting Strategy
- **Logistic Regression**: Achieved a total incremental profit of approximately $6,658 by targeting 20% of the customer base using the uplift model.
- **Random Forest**: Recommended targeting 30% of the customer base, resulting in a total incremental profit of $6,444.
- **XGBoost**: The most effective approach, recommending targeting 30% of the customer base, generating the highest incremental profit of about $12,132.

### Enhanced Model Performance
- Demonstrated the superior performance of uplift models over propensity models in generating incremental profit.
- The XGBoost uplift model notably outperformed Logistic Regression and Random Forest, showcasing the effectiveness of advanced ensemble methods in predictive analytics.

### Actionable Insights
- Provided strategic recommendations on customer segmentation and targeting tactics for PFG Bank to optimize ROI from their credit card solicitation campaigns.
- Highlighted the importance of focusing on highly responsive segments to avoid negative campaign impacts.

## Conclusion
This project exemplifies the effective use of uplift modeling and machine learning techniques to optimize marketing campaigns. By leveraging sophisticated methods like Random Forest and XGBoost, I delivered actionable insights that significantly influence PFG Bank's financial outcomes, demonstrating the impact of data-driven decision-making in the financial services industry.
