# Prediction-of-likeliness-of-cardiovascular-disease-using-machine-learning-algorithms

# Abstract 
A cardiovascular disease (CVD) is a disorder that affects the heart or blood
vessels. Cardiovascular illnesses include heart attacks, heart failure, arrhythmia,
coronary heart disease, and many others. Smoking, blood pressure, cholesterol
level, diabetes, and being overweight all increase the risk of various
cardiovascular illnesses. Age, gender, nutrition, and alcohol consumption can all
be important risk factors for cardiovascular disease. Cardiovascular disorders are
the leading cause of mortality all over the world. According to the 2019 study,
almost 18 million individuals died from Cardiovascular illnesses, with heart
attacks and stroke accounting for 85 percent of these deaths. In India, the
projected number of CVD deaths in 1990 was 2.26 million, and the number of
fatalities is expected to rise to 4.77 million by 2020. CVD increased from 1.6
percent to 7.4 percent in the rural region and from 1% to 13.2 percent in the
urban area. Many researchers have worked on stroke prediction in recent years,
employing various machine learning techniques such as Logistic Regression
(LR), Random Forest (RF), Decision Tree (DT), K-Nearest Neighbour (KNN),
Artificial Neural Network (ANN), Support Vector Machine (SVM), Xgboost (XGB),
Naive Bayes, and others. In this paper, we describe a model that combines data
preprocessing and scaling approaches to clean the dataset, different classifiers
applied to this dataset, and obtained the highest accuracy of 88.52 percent and
Roc AUC of 88.74 percent by applying Random forest over the test data.


# Dataset Description
We worked on the heart disease dataset, which was received from the UCI
(University of California at Irvine) repository; this data set has 14 attributes with
303 instances, including age, gender, cp, trestbps, cho, fbs, restecg, thalach,
exang, oldpeak, slope, ca, thal, and target. We worked on 10 attributes. We
remove less impactful attributes like exang, oldpeak, slope and thal. The target
field describes heart disease in the patient. The patient's heart problem is
described in the target field. This is an integer value, with 0 indicating no heart
disease and 1 indicating heart disease.
