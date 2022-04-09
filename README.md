# Titanic-Survival-Prediction
This project explores the Titanic dataset to find some insights on survival. I did the following:
1. Dropped the columns that are not useful to predicting survival and also the ones that had high number of missing values
2. Data understands by plotting both continous and categorical variables and identified skewness in certain fields
3. Filled the missing data for age with the mode of age
4. Encoded male to '1' and female to '0' for the sex column
5. Created multiple classification models - a) Bernoulli Naive Bayes b) Gaussian Naive Bayes c) Random Forest d) Decision Tree e) Logistic Regression f) Supported Vector Machine

The following are the inisights observed
1. There were around 2 times more males than females aboard.
2. Around 4 times more males died compared to surviving ones.
3. Around 3 times more females survived compared to the ones who didn't.
4. Disproportionately more males passengers were in Pclass 3 and it looks like most of them died in the accident.
5. Most people were in the range between 20 and 40 years and, as already observed, most of them were male.
6. SVC was the best performing model, with a accuracy of 82.51%.
