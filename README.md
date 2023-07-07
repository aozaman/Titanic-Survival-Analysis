# Titanic-Survival-Analysis
Analyzing factors that influenced passenger survival through data wrangling, visualization, and machine learning techniques.

This project delves into the famous Titanic dataset, examining details such as economic status, gender, age, and the ultimate fate of individuals. 

Steps involved:
1. Data Exploration:

- Identify missing values in the "Age," "Cabin," and "Embarked" columns.
- Calculate the proportion of missing values in each column.
- Plot a histogram for the "Age" column and replace the missing values with the average age of passengers.

2. Feature Engineering:

- Add a new variable called "Fare per person" by calculating the fare divided by the number of persons on the ticket.

3. Data Encoding:

- Encode categorical variables, such as "Sex" and "Embarked," into numerical representations using appropriate encoding techniques.

4. Model Building:

- Build three different models to predict survival using logistic regression, k-nearest neighbors (kNN), and support vector machines (SVM).
- Select the independent variables "Age," "Sex," "Fare per person," "Pclass" (passenger class), and "Parch" (number of parents/children aboard) as predictors.
- Define the response variable as "Survived" (indicating whether a passenger survived or not).

5. Model Evaluation:

- Compare the performance of the three models by assessing their accuracy, precision, recall, and F1-score.
- Determine which model performed the best based on the evaluation metrics.

The findings can help understand the impact of various variables on passenger survival and may provide valuable information for future disaster preparedness and safety measures. The project is implemented using Python and popular libraries such as pandas, numpy, and matplotlib.

