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

#References 
1)https://www.ijeat.org/wp-content/uploads/papers/v9i3/B3986129219.pdf
2)https://www.hindawi.com/journals/cin/2021/8387680/
3)https://dl.acm.org/doi/pdf/10.1145/1835804.1835830
4)Harvard Health. (2016, November 8). Throughout life, heart attacks are twice
as common in men than women.
https://www.health.harvard.edu/heart-health/throughout-life-heart-attacks-are-twic
e-as-common-in-men-than-women.
5) Poirier, Paul, et al. "Obesity and cardiovascular disease:pathophysiology,
evaluation, and effect of weight loss: an update of the 1997 American Heart
Association Scientific Statement on Obesity and Heart Disease from the Obesity
Committee of the Council on Nutrition, Physical Activity, and Metabolism."
Circulation 113.6 (2006): 898-918.
6) N. K. Kumar, G. S. Sindhu, D. K. Prashanthi and A. S. Sulthana, "Analysis and
Prediction of Cardiovascular Disease using Machine Learning Classifiers," 2020
6th International Conference on Advanced Computing and Communication
Systems (ICACCS), Coimbatore, India, 2020,pp. 15-21, doi:
10.1109/ICACCS48705.2020.9074183.
7) S. Ismaeel, A. Miri and D. Chourishi, "Using the Extreme Learning Machine
(ELM) technique for heart disease diagnosis," 2015 IEEE Canada International
Humanitarian Technology Conference (IHTC2015), Ottawa, ON, Canada, 2015,
pp. 1-3, doi: 10.1109/IHTC.2015.7238043.
8) N. Prentzas, A. Nicolaides, E. Kyriacou, A. Kakas and C. Pattichis,
"Integrating Machine Learning with Symbolic Reasoning to Build an Explainable
AI Model for Stroke Prediction," 2019 IEEE 19th International Conference on
Bioinformatics and Bioengineering (BIBE), Athens, Greece, 2019, pp. 817-821,
doi: 10.1109/BIBE.2019.00152.
9) S. Bashir, Z. S. Khan, F. Hassan Khan, A. Anjum and K. Bashir, "Improving
Heart Disease Prediction Using Feature Selection Approaches," 2019 16th
International Bhurban Conference on Applied Sciences and Technology
(IBCAST), Islamabad, Pakistan, 2019, pp.619-623, doi:
10.1109/IBCAST.2019.8667106.
10) D. Tiwari, M. Ashish, N. Gangwar, A. Sharma, S. Patel and S. Bhardwaj,
"Potato Leaf Diseases Detection Using Deep Learning," 2020 4th International
Conference on Intelligent Computing and Control Systems (ICICCS), 2020, pp.
461-466, doi: 10.1109/ICICCS48265.2020.9121067.
11) https://www.ijraset.com/fileserve.php?FID=27198
12) M. Bhatia and D. Motwani, "Use of Ensemble Learning for Prediction of
Heart Disease," 2020 4th International Conference on Trends in Electronics and
Informatics (ICOEI)(48184), 2020, pp. 1016-1023, doi:
10.1109/ICOEI48184.2020.9142964.
13) M. Gjoreski, M. Simjanoska, A. Gradišek, A. Peterlin, M. Gams and G.
Poglajen, "Chronic Heart Failure Detection from Heart Sounds Using a Stack of
Machine-Learning Classifiers," 2017 International Conference on Intelligent
Environments (IE), 2017, pp. 14-19, doi: 10.1109/IE.2017.19.
14) R. S. Jeena and S. Kumar, "Stroke prediction using SVM," 2016 International
Conference on Control, Instrumentation, Communication and Computational
Technologies (ICCICCT), Kumaracoil, India, 2016, pp. 600-602, doi:
10.1109/ICCICCT.2016.7988020.
15) S. K. J. and G. S., "Prediction of Heart Disease Using Machine Learning
Algorithms.," 2019 1st International Conference on Innovations in Information
and Communication Technology (ICIICT), Chennai, India, 2019, pp. 1-5, doi:
10.1109/ICIICT1.2019.8741465.
16) T. Obasi and M. Omair Shafiq, "Towards comparing and using Machine
Learning techniques for detecting and predicting Heart Attack and Diseases,"
2019 IEEE International Conference on Big Data (Big Data), Los Angeles, CA,
USA, 2019, pp. 2393-2402, doi: 10.1109/BigData47090.2019.9005488.
17) M. S. Singh and P. Choudhary, "Stroke prediction using artificial intelligence,"
2017 8th Annual Industrial Automation and Electromechanical Engineering
Conference (IEMECON), Bangkok, Thailand, 2017, pp. 158-161, doi:
10.1109/IEMECON.2017.8079581.
18) C. Hung, W. Chen, P. Lai, C. Lin and C. Lee, "Comparing deep neural
network and other machine learning algorithms for stroke prediction in a
large-scale population-based electronic medical claims database," 2017 39th
Annual International Conference of the IEEE Engineering in Medicine and
Biology Society (EMBC), Jeju, Korea (South), 2017, pp. 3110-3113, doi:
10.1109/EMBC.2017.8037515.
