# Prediction-of-likeliness-of-cardiovascular-disease-using-machine-learning-algorithms

# Abstract -------------------------------------------------------------------------------
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

# Introduction -----------------------------------------------------------------
The name "Cardiovascular" is derived from the combination of two terms,
"Cardio" and "Vascular." The term "cardio" refers to the heart, whereas the term
"vascular" refers to all veins in the body. Cardiovascular diseases (CVD) are the
most well-known and deadly infections in the world, killing the majority of people
each year. Illness (CVD) than any other illness. In today's fast-paced society,
cardiovascular illness is on the rise. According to the World Health Organization
(WHO), 17 million people will die each year as a result of cardiovascular
illnesses, including respiratory failure and strokes [1]. In big populations, most
cardiovascular diseases (CVD) are caused by fundamental risk factors such as
cigarette smoking, a poor eating routine, weight, physical lethargy, and
hazardous alcohol use. Individuals with Cardiovascular disease (CVD) or high
levels of Cardiovascular risk (due to the existence of at least one risk factor, such
as hypertension, hyperlipidemia, diabetes, or well managed illness) require an
introduction and instruction using brief prescriptions, as seen below. In general,
cardiovascular disease (CVD) is characterised by the formation of fatty deposits
[5] inside the pipes (atheroscoria) as a result of blood accumulations. It has also
been related to organ damage, including brain, heart, kidney, and eye
impairment. Strokes and coronary events are typically triggered by stressful
conditions and are caused, for the most part, by a blockage that stops blood from
flowing to the heart or brain [13]. The combination of several risk factors, such as
cigarette smoking, a poor diet, and being overweight, is a common cause of
cardiovascular failure and strokes. Heart disease is a potentially fatal ailment that
should not be underestimated. According to Harvard Health Publishing [4], males
are more likely than women to develop cardiac disease. Males are roughly twice
as likely as women to suffer a heart attack over their lives, according to research.
Stroke is the third leading cause of death globally; hence, stroke prediction is an
important metric that, if done early, can save many lives. Several research
comparing the efficacy of predictive data mining approaches and other machine
learning technologies to forecast various illnesses have been conducted [3]. In
recent years, several experts have been working on cardiovascular illness and
determining the best approach to anticipate the condition. However, more
research and patient data from hospital records become available as time
passes. Many open sources of access to patient data and examinations may be
utilised to make the proper diagnosis of patients and detect this disease before it
becomes fatal using various computer technologies [2]. We all know that data
mining and machine learning technologies are the greatest predictors of
cardiovascular disease. In our study, we have also used a variety of machine
learning techniques to increase the accuracy of our predictions [17].

# Dataset Description
We worked on the heart disease dataset, which was received from the UCI
(University of California at Irvine) repository; this data set has 14 attributes with
303 instances, including age, gender, cp, trestbps, cho, fbs, restecg, thalach,
exang, oldpeak, slope, ca, thal, and target. We worked on 10 attributes. We
remove less impactful attributes like exang, oldpeak, slope and thal. The target
field describes heart disease in the patient. The patient's heart problem is
described in the target field. This is an integer value, with 0 indicating no heart
disease and 1 indicating heart disease.
