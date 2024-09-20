# Using Machine Learning to Understand and Address Employee Turnover
## Leveraging Data-Driven Insights to Enhance Employee Retention and Reduce Attrition using Machine Learning Algorithms 
### Issue:
Salifort Motors has been experiencing higher-than-expected employee turnover rates, leading to increased recruitment costs and reduced organizational efficiency. Understanding the drivers of employee attrition is critical for developing strategies that improve retention and overall workplace satisfaction.
### Project Overview:
To address this challenge, using employee survey data provided by the company, a comprehensive Exploratory Data Analysis (EDA) was conducted to identify trends and drivers of employee turnover, then a machine learning predictive model was developed using employee data to identify key factors contributing to employee turnover.
### Impact:
Implementing the predictive model will enable the company to:
- Identify at-risk employees and intervene early.
- Tailor retention strategies to the specific needs of different employee segments.
- Optimize resource allocation in HR efforts, reducing the costs associated with high turnover rates.


### Conclusion
The model effectively identifies key factors contributing to employee turnover and provides actionable insights to improve retention. The below plot shows that tenure,  satisfaction, number of projects, and evaluation were the Top 4 most important factors in determining a which employees would quit. The overall XGBoost model achieved very good metrics with an F1 score of 96.25%, a recall of 93.38%, a precision of 99.30%, and an accuracy of 98.69%

The champion model (XGBoost) effectively identifies key factors contributing to employee turnover, offering actionable insights for improved retention. As visualized in the plot below, tenure, satisfaction, number of projects, and evaluation emerged as the Top 4 most influential factors in predicting employee attrition. The model demonstrated strong performance, achieving an F1 score of 96.25%, recall of 93.38%, precision of 99.30%, and an accuracy of 98.69%. These metrics underscore the model's capability in accurately identifying employees at risk of leaving, enabling organizations to proactively address retention challenges.

![feature_importances](https://github.com/user-attachments/assets/e2f838c6-fec7-425e-8bd9-5f628d2be75f)

### Recommendations
1. **Focus on Improving Job Satisfaction**: Regular surveys and recognition programs can help identify and address dissatisfaction, especially between mid-tenure employees.
2. **Ensure Balanced Workloads and Fair Compensation**: Balanced workloads and fair compensation can help retain employees.
3. **Investigate High Turnover Departments**: Conduct department-specific engagement surveys to understand and address unique challenges.
4. **Implement Robust Safety Protocols**: Enhance safety protocols and provide support for employees involved in accidents.

### Next Steps
1. **Implement Recommendations**: Start with the most impactful recommendations, such as improving job satisfaction for mid -tenure employees.
2. **Monitor and Evaluate**: Continuously monitor the effectiveness of the implemented strategies and make adjustments as needed.
3. **Enhance the Model**: Incorporate additional features such as employee engagement scores, managerial support ratings, and career growth opportunities to further improve the model's predictive power.
4. **Conduct Further Analysis**: Investigate the primary reasons for dissatisfaction, effective retention strategies for mid-tenure employees, and the impact of workload distribution on engagement and satisfaction. **We can also refine our analysis by excluding variables that don’t lead to actionable insights, such as satisfaction and tenure, and refit the model with more targeted factors.**
