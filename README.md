# Portfolio Projects

## [Coffee Sales Analysis with Microsoft Excel](./CoffeeSales.md)
[<img src="./assets/images/coffee.jpg" width="150" />](./CoffeeSales.md)
  
### [Link to Excel Dashboard](https://1drv.ms/x/s!At-IyApyKjDLbOI1SX85VkTJqE8?e=8i18eX)

### Objective
This project revolves around analyzing a comprehensive dataset comprising customer transactions, including order details, product specifics, and customer profiles. The primary objective is to leverage data visualization techniques to investigate the relationship between customer loyalty, purchase sizes, and their impact on overall sales dynamics.

### Central Challenge
Understanding how customer loyalty influences purchase sizes and subsequently affects sales performance. Looking for patterns within customer behaviors and purchase trends is crucial to formulating targeted strategies for increasing engagement and optimizing sales strategies.

### Analytical Strategy
The strategy involves employing various data visualization tools and techniques to explore the dataset thoroughly. Analyzing sales trends and loyalty status against purchase sizes to reveal correlations and patterns. By visualizing these relationships, the project seeks to derive actionable insights that can inform tailored marketing approaches and product offerings, ultimately enhancing customer engagement and driving sales growth.


## [Predicting Absenteeism from work](./absenteeism.md)
[<img src="./assets/images/Employee-Absenteeism.jpg" width="150" />](./absenteeism.md)

### [Link to Notebook](./Absenteeism_Final.ipynb)
### [Link to Tableau Dashboard](https://public.tableau.com/app/profile/divyansh.jain6314/viz/AbsenteeismDashboard_16996027924110/AbsenteeismDashboard)


**Central Challenge:**  
The primary challenge addressed in this project is to explore whether specific known reasons for absence can be predictive of excessive absenteeism from work. The goal is to develop a model that can help organizations identify patterns and factors contributing to absenteeism, ultimately supporting proactive measures for workforce management.

**Analytical Strategy:**  
The analytical strategy revolves around leveraging logistic regression to build a predictive model. The dataset is preprocessed and engineered to enhance the features used in the model. Key steps include encoding reasons for absence, extracting temporal features, and defining a target variable for excessive absenteeism. A custom scaler is applied to standardize the input features, and the dataset is split into training and testing sets.

The logistic regression model is trained on the training set and evaluated on the test set to assess its predictive performance. Coefficients are analyzed to understand the influence of each feature on absenteeism. The trained model is then saved for future use, and a dedicated class is created for easy loading, cleaning, and making predictions on new data.

**Results**   
This analytical strategy allows for a comprehensive exploration of the dataset, feature engineering to enhance model performance, and the application of a logistic regression model to predict absenteeism based on known reasons. The outcome is a practical tool that organizations can utilize to gain insights into potential excessive absenteeism and make informed decisions for workforce planning and management.    
By visualizing the age-related trends, reasons for absence, and the relationship between transportation expenses and children, the Tableau dashboard effectively communicates the project's key findings. It empowers users to interactively explore and grasp the insights derived from the absenteeism prediction model, fostering a better understanding of absenteeism patterns within the dataset and their implications for workforce management.


Certainly! Here's the Medication Risks project formatted for your GitHub README page:

---

## Medication Risks Project(./MedicationAdverseEffects.md)
[<img src="./assets/images/Employee-Absenteeism.jpg" width="150" />](./MedicationAdverseEffects.md)
### Link to Tableau Dashboard(https://public.tableau.com/app/profile/divyansh.jain6314/viz/AstoryaboutadverseeffectsofdrugsinCanada/AdverseEffectsofDrugsStory?publish=yes)

### Central Challenge:
Understanding and analyzing adverse drug reactions in Canada over the years to uncover critical patterns and provide valuable insights for healthcare professionals and researchers.

### Analytical Strategy:
1. **Word Cloud Visualization:**
   - Created a word cloud showcasing the top 50 adverse reactions by reaction count, offering a quick and intuitive overview of prevalent drug risks.

2. **Age-wise Analysis:**
   - Implemented age-wise analysis with bins in 10-year increments.
   - Unveiled distinct patterns, highlighting higher adverse reactions for individuals in the 40-50 and 50-60 age groups.
   - Visualized the top 5 adverse reactions for each age category, providing a detailed exploration of demographic-specific risks.

3. **BMI and Weight Categorization:**
   - Developed a comprehensive BMI categorization system based on height and weight.
   - Incorporated gender details for a nuanced understanding of adverse reactions in different weight categories.
   - Visualized the top 5 adverse reactions for each BMI and weight category, adding depth to the analysis.

### Results:
- **Insightful Visualizations:**
  - Created compelling visuals, including word clouds, bar charts, and line charts, offering clear insights into adverse drug reactions.
  
- **Demographic-specific Trends:**
  - Uncovered age-specific patterns, emphasizing heightened risks in the 40-50 and 50-60 age groups.
  - Revealed correlations between adverse reactions, BMI categories, and gender, contributing to a comprehensive understanding.

- **Accessible Exploration:**
  - Made the project accessible and user-friendly for healthcare professionals and researchers to explore and derive actionable insights.
