# Olympic Medal Prediction using Regression Analysis
### Overview
This project contains two Jupyter Notebooks for predicting Olympic medal counts using regression analysis:
1. medal_prediction (by country).ipynb – Predicts medal counts based on country-level data.
2. medal_prediction (by country and sport).ipynb – Predicts medal counts with an additional breakdown by sport.

### Hypothesis
Countries with a higher number of participating athletes, greater historical success, and consistent participation in various events are more likely to win more medals in the Olympics.

### Data Exploration
The dataset includes Olympic medal data for various countries across multiple years. We explored:

1. Number of athletes participating per country
2. Event participation
3. Past medal performance
4. Sports categories (for the second model)
5. Avg age of contestants
6. Avg weight of contestants

### Data Reshaping & Cleaning
1. Removed irrelevant or missing data
2. Created new variables such as previous medal counts and rolling averages of past performance
3. Ensured data consistency and formatted it for machine learning models

### Model Training

1. Split the data into training and testing sets.
2. Trained regression models using historical Olympic data.
3. Evaluated model accuracy based on Mean Absolute Error (MAE).

### Conclusion

1. The model using only country-level data performed well in predicting general trends but lacked sport-specific insights.
2. The country and sport model provided a more granular view, improving predictions for sports with consistent participation patterns.
3. Further improvements could be done by including additional features such as training facilities, funding per sport, athlete experience etc.
   
