# Google Advanced Data Analytics Capstone

Course seven of seven in the Google Advanced Data Analytics Professional Certificate

The final course in the program provides participants with the opportunity to complete an optional capstone project that combines the key concepts learned in the previous six courses. Learners apply their newly developed skills to solve a specific business problem using data-driven insights. Guided by Google experts, participants work on practical tasks that replicate real-world scenarios, honing their data analytics skills and preparing for career growth. Upon finishing this course, participants will enhance their resumes and professional portfolios, demonstrating proficiency in data framing, visualization, statistical analysis, regression modeling, and machine learning techniques using Python. This course serves as the culmination of the certificate program, equipping learners with the essential skills needed to pursue careers in data science and advanced data analytics.

Course 7: [Link](https://www.coursera.org/learn/google-advanced-data-analytics-capstone?specialization=google-advanced-data-analytics)

## Modules Overview
### Module 1: Capstone Project
In this module, you’ll be introduced to the optional capstone project. You’ll learn about its objectives and how it differs from the end-of-course projects in previous courses. The module provides useful suggestions and guidance to help you successfully complete the project. Additionally, you’ll learn how to incorporate your completed capstone project into your professional portfolio, showcasing your skills and accomplishments.

### Module 2: Data-Focused Career Resources
This module offers a range of data-focused career resources to support your journey into the job market. You’ll receive tips on how to polish your resume and prepare for interviews, ensuring you’re well-equipped to land your next role in data analytics.

### Module 3: Put Your Advanced Data Analytics Certificate to Work
The final module involves completing the last tasks to earn your Google Advanced Data Analytics Certificate badge. Once you finish this module, you’ll have the certification and skills necessary to start applying for roles in the data analytics field, demonstrating your proficiency in key areas like data framing, visualization, statistical analysis, regression modeling, and machine learning.

## Capstone Project: Predicting Employee Turnover
In the capstone project, you will apply your data analytics skills to solve a business challenge at a fictional company, Salifort Motors, a global leader in alternative energy vehicles. You’ll use data from an employee survey to predict employee turnover, providing actionable insights to help increase retention.

### Background
Salifort Motors has a workforce of over 100,000 employees. The company is facing a high employee turnover rate, which is costly in terms of recruitment, training, and lost productivity. Senior leadership has tasked you with designing a model to predict which employees are likely to leave the company based on data such as department, number of projects, average monthly hours, and other variables.

### Key Insights and Recommendations

  * Refine Workload Management: The predictive models indicate a link between high average monthly hours and turnover. Balancing workloads across teams could help reduce this risk.
  * Foster Professional Growth: Lack of promotion is strongly linked to turnover. Strengthening career advancement opportunities could improve retention.
  * Boost Job Satisfaction and Performance: Developing programs to increase job satisfaction and address performance-related issues will be key.
  * Project Allocation Scrutiny: The number of projects assigned to employees correlates with turnover risk, suggesting that project distribution should be monitored more carefully.

### Clustering Analysis: K-Means
Using K-means clustering, employees were divided into clusters to reveal further patterns:

  * Green Cluster: Balanced in terms of hours and performance but dissatisfied. Enhancing workplace conditions or offering professional development could improve satisfaction.
  * Pink Cluster: Overworked employees with high performance but low satisfaction. Reducing workloads or offering more flexibility could prevent burnout.
  * Blue Cluster: Employees with high hours but varying performance levels. This suggests imbalances in work distribution. Optimizing task allocation could improve both performance and job satisfaction.
  * Gold Cluster: High performers with mixed satisfaction levels. Offering career growth opportunities or recognition could further boost satisfaction.

### Predictive Model
Using XGBoost with hyperparameter tuning, the most effective model for predicting employee turnover was created. The metrics for the model's success on the test set are as follows:

  * Precision: 90.1%
  * Recall: 87.8%
  * F1 Score: 89.0%
  * Accuracy: 96.4%
  * AUC: 97.0%

The key features influencing turnover included: number of projects, tenure, last evaluation, work accident, overworked, and salary.

### Conclusion
The decision tree, random forest, and XGBoost models all provide valuable insights into the key predictors of employee turnover. The comparative analysis highlights that a multi-faceted retention strategy is necessary, focusing on workload management, career advancement, job satisfaction, and performance. Additionally, the models suggest that integrating quantitative insights with qualitative feedback will provide a more comprehensive approach to improving employee retention.

### Final Feedback
The capstone project has allowed you to apply your data analytics and machine learning skills to a real-world business problem, preparing you for future roles in data science and advanced analytics. The experience gained from analyzing and interpreting complex datasets will enhance your ability to contribute to business decision-making processes in any data-driven organization.
