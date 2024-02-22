# KICKSTARTER_PROJECT

## Abstract: 
Kickstarter is a popular crowdfunding platform that has enabled many individuals and organizations to bring their creative projects to life. Understanding the success factors of Kickstarter projects is crucial for both creators and investors, as it can help them make better decisions and increase their chances of success. Our study takes a step towards achieving this goal by exploring the effectiveness of different models in predicting the outcome of Kickstarter projects. Through this analysis, we aim to provide a comprehensive evaluation of the models and predictors that are most effective in predicting the success of Kickstarter projects.

 
## Introduction:
The objective of this study is to evaluate the performance of different machine learning models, including Decision Tree, Random Forest, Gradient Boosting, XGBoost, and CatBoost, in predicting the outcome of Kickstarter projects. Additionally, we will also implement multinomial logistic regression to predict the success, failure, or cancellation of Kickstarter projects, utilizing multiple predictors such as backer count, pledged amount, project duration, funding goal, and year. The results of this analysis will be evaluated through a confusion matrix and ROC and AUC metrics, and the impact of different predictors will be analyzed.

Hyperparameter tuning will be applied to the models to optimize their performance, and regularization techniques will be used to improve the performance of the multinomial logistic regression model. The objective of this study is to determine the most effective model in predicting the success of Kickstarter projects and provide insights into the features that are most important in determining the outcome of a project.

This study provides valuable insights into the performance of different machine learning models in predicting the outcome of Kickstarter projects, and the results will help individuals make informed decisions when launching or investing in a Kickstarter project.

## Dataset:
The dataset consists of various features that describe each project, such as the total number of backers, the unique ID assigned to each project, the name of the project, the category it falls under, the country of origin, the start and end dates, the goal amount requested, and the state of the project. Each project is also assigned values for several other variables, such as whether it has been spotlighted, whether it is staff-picked, and the total amount pledged. All of these variables are critical in determining the success of a project and understanding what factors contribute to success. By analyzing these variables, we hope to gain a better understanding of the Kickstarter platform and what makes a project successful.

## Data Preparation:
To begin with, we undertook an initial examination of the data to check for any duplicates, which were subsequently removed. 
Regarding entropy, there were removed features that are unique and can't be separated. These features will complicate our computation, and based on the model, can cause negative impact on prediction.
Furthermore, to bring dataset to model readable format or effective, the was applied manipulation on the listed features [day_duration, week_duration, Year, Month, Project_category].
Using the Start date and end date we used the epoch values and calculated the total time taken to complete the project by calculating the difference between them in order to get the day_duration and week_duration. Moreover, since the original data in the category contains multiple features which is not only the category itself. So, we created a new field called project category to return only the project’s category.
Regarding the presence of missing or null values in the dataset, it was already sufficient and complete, so we proceeded with our analysis without any further adjustments or modifications.
