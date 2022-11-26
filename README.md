## Predicting-Insurance-charges

Using Linear regression (and Feature Engineering) to predict insurance charges from a small dataset with features such as age, sex, BMI, number of children, smokers, and region

## Description
- Downloaded from Kaggle, this dataset is small in size - with 1338 rows and 7 columns containing information collected by an insurance company.
- This dataset was selected to showcase the concepts of linear regression and how sticking to the basics can transform the model to outperform expectations.
- Prediction analysis has been done to predict the target - Insurance charges.
- Further analysis paved the way for feature engineering that elevated the model performance.

## Workflow 

```mermaid
flowchart LR
  A[Imports] --> B[Data Exploration]
  B --> C[Visualization]
  C --> D[Feature Engineering]
  D --> E[Splitting/Encoding/Scaling]
  E --> F[Modelling and Evaluation]
  F --> G[Residual Analysis]
```

## Inference

- Though the dataset size was small, simple Linear Regression gave decent results with less overfitting.
- Analysis revealed patterns in the dataset that resulting in engineering a new feature that increased the model performance (r2 score from 0.75 to 0.96!)
- But adding the new feature might have increased overfitting(5% increase)
- Residual analysis further supports the creation of a new feature.
