# Project-2
### Breakdown of how different factors help predict whether the person in US make more than 50K or not yearly.
Jake Cho

The project aims to explore how few factors can help us determine whether the subject in United States makes more than 50K yearly or not. The project involves data preprocessing, exploratory data analysis, modeling. 

## Dataset

Original source: https://www.kaggle.com/datasets/wenruliu/adult-income-dataset

There are 15 columns and 48,842 rows.


## Data Dictionary
![Screenshot 2023-05-12 062242](https://github.com/jakecho1108/Project-2/assets/61045591/1fcc2659-aee3-421c-b243-1f40ea3fc373)

#### To prepare for analysis, data was cleaned by dealing with missing data points and inconsistent categorization 

## Exploratory Visuals
![pic1](https://github.com/jakecho1108/Project-2/assets/61045591/577004cd-cecb-4406-b945-c5ba435896fb)
![download](https://github.com/jakecho1108/Project-2/assets/61045591/f240583d-b5ab-40fb-be4f-7831f7c7387d)

## Modeling results

Using both K Nearest Neighbors and decision tree, experiment tries to determine which is the better model to determine their income. Furthermore, I used PCA and GridSearchCV to improve the models.
![image](https://github.com/jakecho1108/Project-2/assets/61045591/d56c8099-13d5-4b67-9dc8-761a08a72725)

Best result ended up being this Decision Tree model with GridSearch. 

## Conclusion and Recommendation

Out of all the models, the best one is Decision Tree with GridSearchCV. It had the highest accuracy and highest precision score. For cases like this, ability to get the true positives is the most important factor therefore, I value the precision score the most. I would recommend this model if the pure goal of the problem asked if we can help predict whether the person makes more than $50,000 yearly and believe the results if the model predicts that the person made more than 50K salary. To improve this problem and take this question to the next level, 
