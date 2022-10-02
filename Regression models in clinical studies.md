# Regression Models in Clinical Studies

![image](https://user-images.githubusercontent.com/101681195/193463655-ff87be5a-4531-4466-94cb-73a84dd7e304.png)

Image adapted from [3]

## Introduction
Clinical research is increasingly using regression models. These models are effective analytical tools that produce reliable predictions and allow for studying of statistical inferences. Regression models make two different kinds of assumptions about the response variable's distribution and the form or structure of the connection between the predictors and the answer. In the past medical authors generally used simple linear regression to summarize the data or to calculate the correlation between an independent variable (such as bone mineral density) and a dependent variable (such as aging) but now machine learning helps them to build a complicated model based on much larger sample size and more features. These models use to assess therapeutic efficacy, study risk factors, explore prognostic patterns and derive predictions for individual patients. Multiple regression, logistic regression, effects regression, and regression splines models are common regression models that have been used in clinical studies. In the following, a number of researches in this field will be discussed. 

## Multiple Regression Model
Multiple regression is a statistical technique that can be used to analyze the relationship between a single dependent variable and several independent variables. The objective of multiple regression analysis is to use the independent variables whose values are known to predict the value of the single dependent value. Jaccard et al. [1]  the application of multiple regression methods with considering  controlling covariates, evaluation of predictor relevance, comparing predictors, analysis of moderation, analysis of mediation, assumption violations, outliers, limited dependent variables, and directed regression and its relation to structural equation modeling. For instance they described the analyses using the below schematic mediations. 


![image](https://user-images.githubusercontent.com/101681195/193467427-a6675f3f-f994-467e-8a58-003b6af0446e.png)




## Logistic Regression Model
In statistics, a logistic regression model describes and estimates the relationship between one binary dependent variable and one or more independent variables.  Logistic regression models are versatile and have been used to describe phenomena in diverse areas of medical and nonmedical research. Zabor et al. (2022) [2] in a recent review discussed the application of the logistic regression model in clinical studies. They concluded that logistic regression is powerful to evaluate although some significant errors might present. The assessments and other decisions made during model building must be thoroughly described in the final report. The choice of variables is also important. In a study, Aoyama et al. [3] developed a multivariable logistic regression model to study the risk of developing an intracranial hemorrhage because of pregnancy-induced hypertension in patients. They concluded that: 'The importance of choosing appropriate variables for a regression model
is highlighted, underscoring the need to ensure that the baseline assumptions of a selected model are correct and to assess model performance and your confidence in the results as derived from regression analyses'. In another study, Alaka et al.[4] studied on predicting functional outcomes in acute ischemic stroke patients after endovascular treatment. They examine the predictive performance of ML algorithms for predicting a 90-day functional impairment risk after acute ischemic stroke and compare it with regression-based risk prediction models. ML and logistic regression model showed that age and stroke severity (measured by NIHSS) were the most important predictor variables of 90-day functional outcome. 


## Effect Regression Model
The effect Model is a statistical model in which some of the parameters that define systematic components of the model exhibit some form of variations that can be conducted in three forms. In random-effects models, some of these systematic effects are considered random. In fixed-effects models, the systematic effects are considered fixed or non-random. And,  models that include both fixed and random effects may be called mixed-effects models.
In a recent study, Arsène et al. (2022) [5] developed an epidemiological model of respiratory tract infection (RTI) coupled to a mechanistic description of viral RTI episodes in a silico clinical trial based on the effects model. The model advocates reporting a variety of metrics for benefits assessment, using adaptive trial design and adapted statistical analyses. 

## Regression splines Model
In order to overcome the disadvantages of polynomial regression, the regression splines model instead of building one model for the entire dataset divides the dataset into multiple bins and fits each bin with a separate model. This model was used to estimate the relative survival and model the effects of potential prognostic factors in cancer. Remontet et al. [6] In their model the mortality hazard observed after diagnosis in cancer patients are split up into two components: the
mortality hazard due to cancer and the expected mortality hazard due to other causes. Their model yielded smooth and reliable estimates of the mortality hazard. 

## Reference
[1] Jaccard, James, et al. "Multiple regression analyses in clinical child and adolescent psychology." Journal of Clinical Child and Adolescent Psychology 35.3 (2006): 456-479.
[2] Zabor, Emily C., et al. "Logistic regression in clinical studies." International Journal of Radiation Oncology* Biology* Physics (2021).
[3] Aoyama, Kazuyoshi, et al. "Determining associations and estimating effects with regression models in clinical anesthesia." Anesthesiology 133.3 (2020): 500-509.
[4] Alaka, Shakiru A., et al. "Functional outcome prediction in ischemic stroke: a comparison of machine learning algorithms and regression models." Frontiers in neurology 11 (2020): 889.
[5] Arsène, Simon, et al. "Modeling the disruption of respiratory disease clinical trials by non-pharmaceutical COVID-19 interventions." Nature communications 13.1 (2022): 1-10.
[6] Remontet, Laurent, et al. "An overall strategy based on regression models to estimate relative survival and model the effects of prognostic factors in cancer survival studies." Statistics in medicine 26.10 (2007): 2214-2228.

