# KICKSTARTER_PROJECT

## Abstract: 
Kickstarter is a popular crowdfunding platform that has enabled many individuals and organizations to bring their creative projects to life. Understanding the success factors of Kickstarter projects is crucial for both creators and investors, as it can help them make better decisions and increase their chances of success. Our study takes a step towards achieving this goal by exploring the effectiveness of different models in predicting the outcome of Kickstarter projects. Through this analysis, we aim to provide a comprehensive evaluation of the models and predictors that are most effective in predicting the success of Kickstarter projects.

## Objective of this project:

The purpose of this project is to develop a multiclass classification model for Kickstarter projects using features such as project duration, number of backers, year of release, pledged amount, and others. The model will predict the outcome of a Kickstarter project as a success, failure, or cancellation. To achieve this objective, we will utilize various machine learning techniques including decision trees, random forests, gradient boosting machines (GBMs), XGBoost, and Logistic regression. The goal is to identify the most accurate and robust model for the prediction task.
 
## Dataset:
The dataset consists of various features that describe each project, such as the total number of backers, the unique ID assigned to each project, the name of the project, the category it falls under, the country of origin, the start and end dates, the goal amount requested, and the state of the project. Each project is also assigned values for several other variables, such as whether it has been spotlighted, whether it is staff-picked, and the total amount pledged. All of these variables are critical in determining the success of a project and understanding what factors contribute to success. By analyzing these variables, we hope to gain a better understanding of the Kickstarter platform and what makes a project successful. While training, Hyperparameter tuning will be applied to the models to optimize their performance, and regularization techniques will be used to improve the performance of the multinomial logistic regression model. 

## Conclusion:
Upon assessment, it was determined that Random Forest had the highest accuracy. However, if the minority class "cancelled" is excluded, Catboost would become the leading model.The current model is great for considering all classes (Random Forest). However, if the stakeholder's mission is to get the highest number of TPs and TN, then we suggest using CatBoost. 

Companies can use this model to predict the success or failure of a project for business purposes with an expected accuracy of 98% to 99%. It is important to treat "canceled" as a separate case and the model may need to be refined in the future to account for changing trends.



