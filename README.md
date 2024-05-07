
# Heart Disease Classification

The purpose of this project is to build a machine learning model to predict the presence or absence of heart disease based on 11 different features related to medical parameters. Utilizing the [Heart Disease Dataset](https://www.kaggle.com/datasets/mexwell/heart-disease-dataset/data) from Kaggle, which combines five popular heart disease datasets.

![Heart Image](/images/Heart_Disease.jpg "Heart Logo")


## Methods Used

 - Machine Learning
 - Predictive Modeling
 - Data Visualization


## Technologies

- Python3
- Numpy
- Pandas
- Seaborn
- Missingno
- Scikit Learn


## Needs of this project

- Data processing/cleaning
- Data exploration/descriptive statistics
- Statistical modeling

## Conclusions

In conclusion, after preprocessing the dataset and training the random forest and extra trees models considering different numbers of trees, we find that the best out-of-bag score is achieved for the extra trees model with 500 decision trees. This model provides us with a recall score for the test subset of 96% for target 1, as we can see in the figure. Which within the context of the problem is a good result, because only 4% of the people who had a target 1 were diagnosed with a target 0. 

![Confussion Matrix](/images/Confussion_Matrix.png "Confussion Matrix")

## Challenges

This project did not present many challenges. Therefore, the main challenge of this work was determining how to replace the spurious values in the dataset, because a significant portion of the data contained atypical values or input errors for different features. Besides, if these values were used to train the model, they would significantly worsen the resulting prediction.

## What else i might have done?

Although the obtained result is quite satisfactory, something that could improve this outcome could be applying standardization or normalization of the numerical variables. This would aim to improve the results for atypical values, as well as scale the values for each features more effectively.

## Authors

- [@JavierValladaresCo](https://www.github.com/JavierValladaresCo)


