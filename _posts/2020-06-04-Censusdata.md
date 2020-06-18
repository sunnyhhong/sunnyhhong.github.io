---
layout: post
title: Random Forest & KNN & Folding 
subtitle: Using data from 1994 United States Census data base to predict income
tags: [Machine Learning, Knn, Random Forest, Folding, Prediction, Analysis]
comments: true
---

#### Our research question : What socioeconomic qualities lead to a higher income in US adults? What qualities influence economic outcome the most?



The data was extracted by Barry Becker from the 1994 Census database. The records follow these following conditions : ((AAGE>16) && (AGI>100) && (AFNLWGT>1)&& (HRSWK>0)). With this dataset obtained from UCI datasets source, we will model to predict the income whether a person makes over 50K or not. There are 32,561 observations and 15 columns in total. Our response variable is “Income”. Income is a binary variable with values “<=50K” and “>50K”, indicating whether a person makes an annual income less than or equal to 50K or makes an annual income of more than 50K. The rest of the 14 variables will be determined to be used as an explanatory value or not. The following are the 14 variables : “age”, “workclass”, “fnlwgt”,“education”,“education_num”,“marital_status”,“occupation”, “relationship”, “race”,“sex”,“capital_gain”,“capital_loss” ,“hours_per_week” and “native_country”.There are 6 continuous/numerical predictor variables and 8 categorical variables. According to the table of values, there are missing data on the observation’s workclass, occupation, and native class. To summarize, missing data occurs when no data value is stored in an observation either with intent or not. These missing data can either have a big or small significant effect on the conclusion that can be drawn from the data. Because they are explanatory variables we will either be omitting or treat them as another category depending on the results.
