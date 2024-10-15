# HARVESTIFY
Abstract

Agriculture is a major source of income and employment in India. The most prevalent problem faced by Indian farmers is that they do not select the appropriate crop for their land and do not use the appropriate fertilizer. They will experience a significant drop in production as a result of this. Precision agriculture has been used to solve the farmers' difficulty. Precision agriculture is a modern farming strategy that employs research data on soil properties, soil types, and crop yield statistics to recommend the best crop to farmers as well as fertilizer recommendations based on site-specific features. This decreases the number of times a crop is chosen incorrectly and increases productivity.

Acknowledgments
We extend our deepest gratitude to our project supervisor, Ms. Shruti Agarwal, for her invaluable guidance and support throughout the development of Harvestify. We are also thankful to our team members, Arya Chavan and Yash Newalkar, for their collaborative efforts. Special thanks to our families and friends for their unwavering support, encouragement, and motivation during the course of this project.

List of Abbreviations
1. AI : Artificial Intelligence
2. NPK : Nitrogen, Phosphorus, Potassium
3. ML : Machine Learning

List of Symbols

1. N : Nitrogen
2. P : Phosphorus
3. K : Potassium
4. pH : Potential of Hydrogen (Soil Acidity Level)


1.	Introduction

1.1	Introduction

In most cases, a farmer's decision on which crop to cultivate is influenced by his intuition as well as other irrelevant factors such as generating quick money, being unaware of market demand, overestimating a soil's ability to support a specific crop, and so on. The farmer's financial situation could be severely strained if he makes a poor judgement. Perhaps this is one of the numerous factors contributing to the innumerable farmer suicide cases that we hear about in the news on a daily basis. Such an incorrect judgement would have bad consequences not only for the farmer's family, but for the entire economy of a region in a country like India, where agriculture and allied sectors account for around 20.4 percent of the country's Gross Value Added (GVA). As a result, we consider a farmer's decision on which crop to plant during a given season to be quite serious. The need of the hour is to create a system that can provide Indian farmers with predictive insights, allowing them to make better decisions about which crops to produce. With this in mind, we propose a system, an intelligent system that would consider environmental parameters (temperature, rainfall, geographical location in terms of state) and soil characteristics (N, P, K, pH value, soil type and nutrients concentration) before recommending the most suitable crop to the user. In addition to that a fertilizer suggestion is also made which is based on the optimum nutrients of the crops grown.







1.2	Motivation  

Agriculture is that the backbone for developing countries like India as quite 70% of population depends on agriculture. Agriculture in India plays a predominant role in economy and employment. The common problem existing among the Indian farmers are they don’t choose the proper crop supported their soil requirements and also which fertilizer to be used for his or her crop. thanks to this they face a heavy setback in productivity. This problem of the farmers has been addressed through precision agriculture




1.3	Problem Statement & Objectives  

The problem addressed by Harvestify is the inefficiency in crop and fertilizer selection, often leading to suboptimal yields. The objective is to build a system that uses AI to predict crops and fertilizers based on real-time data inputs. The system aims to increase productivity, improve resource management, and provide farmers with accurate crop disease predictions.

1.4 Organization of the Report  

This report is organized into five sections. Section 1 introduces the project, its motivation, and objectives. Section 2 discusses the existing literature and similar systems. Section 3 presents the proposed system, including architecture and algorithms. Section 4 outlines the experiments and results, while Section 5 concludes with future work.



2.	Literature Survey

2.1 Survey of Existing/Similar System

Various AI and machine learning-based systems exist in agriculture, focusing on tasks such as pest control, irrigation, and yield prediction. Systems like Precision Agriculture and Smart Farming utilize IoT devices and data analytics to optimize farming operations. While effective, most existing systems lack integration of real-time data with predictive crop and fertilizer recommendations.


2.2 Limitations of Existing Systems & Research Gap
  
Most current solutions do not account for the comprehensive inputs that Harvestify uses, such as the combination of NPK levels, rainfall, and pH for crop prediction, as well as location-specific recommendations. There is also a gap in combining predictive analytics with disease detection, a feature Harvestify aims to address.

2.3	Mini Project Contribution 

Harvestify contributes to the field by offering a novel integration of AI-driven crop and fertilizer recommendations, based on a Random Forest model, and the addition of a disease prediction feature. This system uniquely combines environmental factors, soil health, and real-time data to provide a holistic solution for farmers.



3.	Proposed System

3.1 Introduction  

In most cases, a farmer's decision on which crop to cultivate is influenced by his intuition as well as other irrelevant factors such as generating quick money, being unaware of market demand, overestimating a soil's ability to support a specific crop, and so on. The farmer's financial situation could be severely strained if he makes a poor judgement. Perhaps this is one of the numerous factors contributing to the innumerable farmer suicide cases that we hear about in the news on a daily basis. Such an incorrect judgement would have bad consequences not only for the farmer's family, but for the entire economy of a region in a country like India, where agriculture and allied sectors account for around 20.4 percent of the country's Gross Value Added (GVA). As a result, we consider a farmer's decision on which crop to plant during a given season to be quite serious. The need of the hour is to create a system that can provide Indian farmers with predictive insights, allowing them to make better decisions about which crops to produce. With this in mind, we propose a system, an intelligent system that would consider environmental parameters (temperature, rainfall, geographical location in terms of state) and soil characteristics (N, P, K, pH value, soil type and nutrients concentration) before recommending the most suitable crop to the user. In addition to that a fertilizer suggestion is also made which is based on the optimum nutrients of the crops grown.

3.2 Architecture/Framework
 
The architecture of Harvestify consists of a data collection layer, a machine learning model for prediction, and a user-friendly interface for farmers. Drones, IoT sensors, and satellite imagery are used for data collection, while the prediction model is built using Random Forest algorithms.

 


3.3	Algorithm and Process Design  

Harvestify uses a Random Forest algorithm to predict the crop based on inputs like NPK, rainfall, and pH. For fertilizer recommendation, the model analyzes the NPK levels and the selected crop to provide optimal fertilizer suggestions. The disease prediction model uses a classification algorithm to identify potential threats based on environmental conditions.

3.4	Details of Hardware & Software  

Hardware includes drones for field imagery and IoT sensors for collecting soil and environmental data. The software stack involves Python for model development, TensorFlow and scikit-learn for machine learning algorithms, and Gradio for the UI. Google Colab is used for training and testing models.

3.5	Experiments and Results

Experiments conducted with real-world data show that Harvestify’s predictions improve decision-making for crop and fertilizer selection. The addition of disease prediction helps farmers mitigate risks early, resulting in better crop health and higher yields.


3.6	Conclusion and Future Work
  
     All This system helps the farmer to choose the right crop by providing insights that ordinary farmers don't keep track of thereby decreasing the chances of crop failure and increasing productivity. It also prevents them from incurring losses. The system can be extended to the web and can be accessed by millions of farmers across the country. We could achieve an accuracy of 90 percent from the Decision Trees, an accuracy of 70.6 percent from the Support Vector Machine, an accuracy of 94.30 percent from the Logistic Regression and an accuracy of 99.09 percent from the Random Forest model. Further development is to integrate the crop recommendation system with another subsystem, yield predictor that would also provide the farmer an estimate of production if he plants the recommended crop.
 


 


 

Reference

[1] 2019, 10th International Conference on Computing, Communication and Networking Technologies, “Low-cost IOT+ML design for smart farming with multiple applications”, Fahad Kamraan Syed, Agniswar Paul, Ajay Kumar, Jaideep Cherukuri. 
[2] 2019  IEEE  “ Smart Management of Crop Cultivation using IoT and Machine Learning”   Archana Gupta,  Dharmil Nagda,  Pratiksha Nikhare,  Atharva Sandbhor
[3] Radhika, Narendiran, “Kind of Crops and Small Plants Prediction using IoT with Machine Learning,” International Journal of Computer & Mathematical Sciences, 2018.
[4] “Crop Recommendation on Analyzing Soil Using Machine Learning” Anguraj.Ka, Thiyaneswaran.Bb, Megashree.Gc, Preetha Shri.J.Gd, Navya.Se, Jayanthi. Jf, 2020.
[5] “Classification of Soil and Crop Suggestion using Machine Learning Techniques”, A. Mythili , IEEE 2019.
[6] Mehta, P., Shah, H., Kori, V., Vikani, V., Shukla, S., & Shenoy, M.,2018. “Survey of unsupervised machine learning algorithms on precision agricultural data”, IEEE
[7] “IOT based Crop Recommendation, Crop Disease Prediction and Its Solution” Rani Holambe, Pooja Patil, Padmaja Pawar, Saurabh Salunkhe , Mr. Hrushikesh Joshi, 2019 IRJET



DATASET:
https://www.kaggle.com/datasets/atharvaingle/crop-recommendation-dataset

