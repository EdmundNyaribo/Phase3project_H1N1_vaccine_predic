<!-- #region -->
# Phase3project_H1N1_vaccine_predict

![H1N1Image](https://github.com/EdmundNyaribo/Phase3project_H1N1_vaccine_predict/blob/main/images/H1N1.jpeg)


## Business Overview
Vaccination, is a key public health measure used to fight infectious diseases. Vaccines provide immunization for individuals, and enough immunization in a community can further reduce the spread of diseases through "herd immunity" - the indirect protection from an infectious disease.
A survey was initiated that asked respondents whether they had received the H1N1 and seasonal flu vaccines. In addition to the questions about themselves, more questions covered their social, economic, and demographic background, opinions on risks of illness and vaccine effectiveness, and behaviors towards mitigating transmission.

The project is initiated by the 'USE Department of Health and Vaccination Services' to gain more insights and a better understanding of how these characteristics are associated with personal vaccination patterns can provide guidance for future public health efforts.

## Business Understanding 
The primary goal of the client is to create a platform that delivers above average accurate predictions of the receptance of the H1N1 vaccine flu shot. This will help the Health insitution to know how which methodology to use in order to increase the receptance rate of the vaccines they intend to give to the public. To achieve this objective we need to develop a model that can predict if a person is willing to take the H1N1 vaccine based on some certain features that were provided. To effectively train this model the client requires precise and representative data related to the personal, social, opinion data that is collected.

Once trained successfully the model will be capable of providing predictions of vaccine rate acceptance based on the features. It can then be integrate into the health platform offering reliable predictions about the future vaccine acceptance rate by the community.

This information derived from the model will help the health sector to make informed decisions regarding vaccination procedures. By leveraging technology to provide a dependable and precise platform for achieving effecient vaccination to most of the population.

## OBJECTIVE

1. To predict the acceptance rate of the H1N1 vaccine
<!-- #endregion -->

# DATA UNDERSTANDING
We are provided with three datasets which were sourced from the DrivenData website;specifically the 'H1N1 and Seasonal Flu Vaccines' Competition.
* training_set_features
* training_set_labels
* test_set_features 

Some limitations of the data that may have implications for the project are:

* The data may not reflect the current conditions as it was collected from a survey in 2009.

* The data may not capture all the factors that affect the population to be receptive of the vaccine.

# MODELLING
The following models were used in order to make predictions about the data
* Logistic Regression
* Decision Trees classifier
* Random Forest Classifier
* K-Nearest Neighbor

The Random Forest Classifier deemed to be the most effective model with a high accuracy in both the train and test data in making the prediction of the acceptance rate of the vaccine.

These models also have been fine-tuned to have better results

# EVALUATION 
The evaluation metrics used to measure the performance of the models are
* Accuracy - How well did the model predict the target variable classes
* precision - ratio of the true positives over the total predicted positives
* Recall - Ratio of the True Positives over the total actual positives
* F1-score
* ROC_AUC - Area under the curve

## Conclusion
From the evaluation step above we  can derive the conclusion that The Random Forest Classifier having an overall accuracy of 80% proved to be the best model. This means that the model's output is accurate by 80% based on the used features.

	precision => 54%
    recall => 70%
    f1-score => 61%
    accuracy => 80%
    

```python

```
