**Salary Prediction Using Simple Linear Regression**

**Hypothesis:** Predicting Salary Based On Employee Grade

\- Null Hypothesis (H0): There is no relationship between employee grade and salary.

\- Alternative Hypothesis (H1): There is a relationship between employee grade and salary.


**Data Collection:**

\- The data was collected from the ‘Employees Salaries Analysis’ dataset posted by SAHIR MAHARAJ on Kaggle website

\- [Link to dataset](https://www.kaggle.com/datasets/sahirmaharajj/employee-salaries-analysis/data)

**Data Cleaning and Preprocessing**

\- The data was alphanumeric issues in the ‘Grade’ column was handled by removing all the alphabets.

\- The missing values in the ‘Grade’ column were predicted using a simple linear regression model.

\- The values in both columns were rounded off to zero decimal places and turned into integers and avoid discrepancies and enable the model to make accurate predictions.

**Exploratory Data Analysis**

**1. Summary Statistics:** to understand the central tendency, spread, and range of the dataset.

Central Tendency:

\- The mean salary of $90,312.17 and the median salary of $87,328 indicate that the data is roughly symmetrically distributed around these central values. This suggests that the salaries are fairly evenly distributed across the dataset.

\- The mean employee grade of 12.72 and the median grade of 14 also suggest that the distribution of employee grades is relatively balanced, with no extreme outliers affecting the central tendency significantly.

Spread:

\- The standard deviation for salary is $31,240.84, indicating that the salary data points are spread out around the mean salary of $90,312.17. This suggests that there is a noticeable variability in salaries among the employees.

\- The standard deviation for employee grade is 9.23, showing that the employee grade data points have less spread around the mean grade of 12.72. This implies that there is less variability in the employee grades compared to the salary values.

Range:

\- The range of the salary data, from $11,147 to $292,000, shows the entire span of salary values in the dataset. It gives insight into the minimum and maximum salary values present, highlighting the diversity in pay levels among the employees.

\- Similarly, the range of employee grades from 0 to 40 indicates the full extent of grade values within the dataset, suggesting a broad range of roles or seniority levels among the employees.


**More Insights from central tendency, spread, and range of the dataset:**

\- The data shows a moderately wide range of salaries, from $11,147 to $292,000, indicating diversity in pay levels among the employees.

\- The distribution of employee grades is more concentrated within a range of 0 to 40, with a mean grade of 12.72, suggesting a relatively balanced distribution of employee seniority levels.

\- The majority of salaries fall between $70,023 (25th percentile) and $108,084 (75th percentile), indicating that most employees earn within this range.

\- The median salary of $87,328 falls below the mean salary of $90,312.17, suggesting a slightly skewed distribution towards higher salaries.

\- The middle 50% of employee grades lie between 3 and 21, illustrating the spread of seniority levels among the employees without extreme outliers.

Overall, the summary statistics reveals a diverse range of salaries and employee grades within the dataset, with no apparent outliers impacting the central tendency measures significantly.


**2. Distribution of Base Salary:**

`   `- Visualized the distribution of 'Base Salary' using histogram to see how salaries are distributed across different ranges.

**3. Explored Employee Grade:**

`   `- Examined the distribution of 'Employee Grade' values to understand the frequency of each grade and identify any patterns or trends.

**4. Relationship Between Base Salary and Employee Grade:**

`   `- Created a scatter plot to visualize the relationship between 'Base Salary' and 'Employee Grade'. 

**5. Correlation Analysis:**

\- Calculated the correlation coefficient between 'Base Salary' and 'Employee Grade' to quantify the strength of the relationship between the two variables.

Result: a correlation coefficient of -0.008 signified a very weak linear relationship between 'Base Salary' and 'Employee Grade', suggesting that the two variables are not linearly related in a meaningful way for predictive modeling purposes.

**6. Recommendation:**

Based on the analysis and findings regarding the relationship, as well as the weak correlation identified, here are some recommendations to consider:

i. Feature Engineering:

`   `- Include Additional Features: Since 'Employee Grade' alone shows a weak relationship with 'Base Salary', consider incorporating other relevant features or variables from the dataset that could have a more significant impact on determining salary levels. This may involve factors such as education level, years of experience, performance ratings, or department.

ii. Advanced Modeling Techniques:

`   `- Polynomial Regression: If the relationship between 'Employee Grade' and 'Base Salary' is not linear, consider exploring polynomial regression or other non-linear regression techniques to capture the complexity of the relationship more effectively.

`   `- Feature Scaling and Selection: Utilize techniques like feature scaling to normalize data and feature selection methods to identify the most relevant variables for building an accurate prediction model.

iii. Ensemble Methods:

`   `- Random Forest or Gradient Boosting: These ensemble learning methods can handle complex relationships and interactions between features, potentially improving the predictive performance compared to a simple linear regression model.

iv. Cross-Validation:

`   `- Use cross-validation techniques to assess the model's performance and generalizability across different subsets of the data. This will help in evaluating the model's predictive ability and identify potential overfitting issues.

v. Model Evaluation:

`   `- Evaluate the model using appropriate metrics such as Mean Squared Error (MSE), Root Mean Squared Error (RMSE), or R-squared to quantify the accuracy of salary predictions. Compare different models to determine which one performs best.

vi. Continuous Improvement:

`   `- Iteratively refine the model by testing and incorporating feedback. This could involve revisiting feature selection, exploring interactions between variables, or refining model hyperparameters.

vii. Collaboration and Domain Knowledge:

`   `- Engage with domain experts or stakeholders to gain insights into factors that may influence salary decisions within the organization. Their expertise can provide valuable context for feature selection and model development.

vii. Data Quality Check:

`   `- Double-check the data quality, ensuring that any anomalies or outliers are addressed appropriately. Clean, accurate data is essential for training robust and reliable predictive models.

ix. Documentation and Interpretation:

`   `- Document the entire modeling process, including data preprocessing steps, feature selection, model training, and evaluation metrics. Also, interpret the model outcomes to provide actionable insights for decision-making.

By implementing these recommendations and strategies, you can enhance the predictive accuracy of the model and gain a deeper understanding of the factors influencing salary levels within the dataset. Continuous learning and adaptation based on model performance and domain insights will help in building a robust salary prediction model that aligns with the organizational needs and goals.
