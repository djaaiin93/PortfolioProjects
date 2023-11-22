# PortfolioProjects

## [Coffee Sales Analysis with Microsoft Excel](./CoffeeSales.md)
[<img src="./assets/images/coffee.jpg" width="150" />](./CoffeeSales.md)

## [Predicting Absenteeism from work](./absenteeism.md)
[<img src="./assets/images/Employee-Absenteeism.jpg" width="150" />](./absenteeism.md)

**Central Challenge:**  
The primary challenge addressed in this project is to explore whether specific known reasons for absence can be predictive of excessive absenteeism from work. The goal is to develop a model that can help organizations identify patterns and factors contributing to absenteeism, ultimately supporting proactive measures for workforce management.

**Analytical Strategy:**  
The analytical strategy revolves around leveraging logistic regression to build a predictive model. The dataset is preprocessed and engineered to enhance the features used in the model. Key steps include encoding reasons for absence, extracting temporal features, and defining a target variable for excessive absenteeism. A custom scaler is applied to standardize the input features, and the dataset is split into training and testing sets.

The logistic regression model is trained on the training set and evaluated on the test set to assess its predictive performance. Coefficients are analyzed to understand the influence of each feature on absenteeism. The trained model is then saved for future use, and a dedicated class is created for easy loading, cleaning, and making predictions on new data.

**Results**   
This analytical strategy allows for a comprehensive exploration of the dataset, feature engineering to enhance model performance, and the application of a logistic regression model to predict absenteeism based on known reasons. The outcome is a practical tool that organizations can utilize to gain insights into potential excessive absenteeism and make informed decisions for workforce planning and management.    
By visualizing the age-related trends, reasons for absence, and the relationship between transportation expenses and children, the Tableau dashboard effectively communicates the project's key findings. It empowers users to interactively explore and grasp the insights derived from the absenteeism prediction model, fostering a better understanding of absenteeism patterns within the dataset and their implications for workforce management.
