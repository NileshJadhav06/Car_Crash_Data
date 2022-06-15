# Car_Crash_Data
You are hired by the Government to do an analysis of car crashes. 
You are provided details  of car crashes, among which some people survived and some didn't. 
You have to help the government in predicting whether a person will survive or not on the basis of 
the information  given in the data set so as to provide insights that will help the government to make 
stronger laws for car manufacturers to ensure safety measures. Also, find out the important factors  
on the basis of which you made your predictions.


1) Data Ingestion: Read the dataset. Do the descriptive
statistics and do null value condition check, write an
inference on it. Perform Univariate and Bivariate Analysis. Do
exploratory data analysis. (8 marks)
2) Encode the data (having string values) for Modelling.
Data Split: Split the data into train and test (70:30). Apply
Logistic Regression and LDA (linear discriminant analysis).
3) Performance Metrics: Check the performance of
Predictions on Train and Test sets using Accuracy, Confusion
Matrix, Plot ROC curve and get ROC_AUC score for each
model. Compare both the models and write inferences, which
model is best/optimized.
4) Inference: Based on these predictions, what are the
insights and recommendations.


1. dvcat: factor with levels (estimated impact speeds) 1-
9km/h, 10-24, 25-39, 40-54, 55+
2. weight: Observation weights, albeit of uncertain accuracy,
designed to account for varying sampling probabilities. (The
inverse probability weighting estimator can be used to
demonstrate causality when the researcher cannot conduct a
controlled experiment but has observed data to model)
3. Survived: factor with levels Survived or not_survived
4. airbag: a factor with levels none or airbag
5. seatbelt: a factor with levels none or belted
6. frontal: a numeric vector; 0 = non-frontal, 1=frontal impact
7. sex: a factor with levels f: Female or m: Male
8. ageOFocc: age of occupant in years
9. yearacc: year of accident
10. yearVeh: Year of model of vehicle; a numeric vector
11. abcat: Did one or more (driver or passenger) airbag (s)
deploy? This factor has levels deploy, nodeploy and unavail
12. OCCRole: a factor with levels driver or pass: passenger
13. deploy: a numeric vector: 0 if an airbag was unavailable
or did not deploy; 1 if one or more bags deployed.
14. injSeverity: a numeric vector; O: none, 1: possible injury,
2: no incapacity, 3: incapacity, 4: killed; 5: unknown, 6: prior
death
15. caseid: character, created by pasting together the
populations sampling unit, the case number, and the vehicle
number. Within each year, use this to uniquely identify the
vehicle.
