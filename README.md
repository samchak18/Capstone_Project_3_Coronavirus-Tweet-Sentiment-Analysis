# Capstone_Project_3_Coronavirus-Tweet-Sentiment-Analysis

This challenge asks to build a classification model to predict the sentiment of COVID-19 tweets. The tweets have been pulled from Twitter and manual tagging has been done then.



![image](https://user-images.githubusercontent.com/114379464/234481406-6e25bbc9-93ec-40df-b5d1-28aae1b7d175.png)




📋 INTRODUCTION :


The coronavirus disease 2019 (COVID-19) pandemic has influenced the everyday life of people around the globe. In general and during lockdown phases, people worldwide use social media network to state their viewpoints and general feelings concerning the pandemic that has hampered their daily lives. Twitter is one of the most commonly used social media platforms, and it showed a massive increase in tweets related to coronavirus, including positive, negative, and neutral tweets, in a minimal period. The researchers move toward the sentiment analysis and analyze the various emotions of the public toward COVID-19 due to the diverse nature of tweets. Meanwhile, people have expressed their feelings regarding the vaccinations' safety and effectiveness on social networking sites such as Twitter. As an advanced step, in this paper, our proposed approach analyzes COVID-19 by focusing on Twitter users who share their opinions on this social media networking site. The proposed approach analyzes collected tweets' sentiments for sentiment classification using various feature sets and classifiers. The early detection of COVID-19 sentiments from collected tweets allow for a better understanding and handling of the pandemic. Tweets are categorized into positive, negative, and neutral sentiment classes. We evaluate the performance of machine learning (ML) and deep learning (DL) classifiers using evaluation metrics.




📋 PROBLEM STATEMENT:

This challenge asks you to build a classification model to predict the sentiment of COVID-19 tweets. The tweets have been pulled from Twitter and manual tagging has been done then. 


🎯 OBJECTIVE:

The CoVid-19 pandemic has shaken the very foundation of society wherein people were forced to live inside their houses because of the lockdown being imposed and also the livelihood of almost every section of the society was impacted.

The objective of our analysis revolved around knowing the sentiments of people from their tweets on Twitter as Twitter is one of the prime means of expression over social media.


APPROACH:

Text Preprocessing

Exploratory Data Analysis

Model Preprocessing

Model Training


📘 ALGORITHMS USED:

Logistic Regression with Grid Search CV

Decision Tree Classifier

XG Boost

KNN

SVM Classifier for both Count Vector and TF ID Vectorization techniques.


PROBLEM FACED:

Text preprocessing.

Vectorization.

Model Training and performance improvement


CONCLUSION:

Since the outbreak of the COVID-19 pandemic and with a new normal of staying at home, working from home, and “isolation time,” social networking media has been extensively used to share news, opinions, emotions, advice; however, most of the data on social media are irrelevant and do not belong to the actual scenario. This study proposed an approach to deal with the Twitter sentiment using the COVIDSenti dataset. We evaluate ML and DL classifiers using novel feature extracting methods that automatically learn features without human interference. We observed that people follow government policies and Standard Operating Procedures (SOPs) and began to favor lockdown and keep social distancing in March 2020, but the order by the government is in February 2020. There is much misinformation on social media; therefore, health organizations need to develop a stable system for detecting coronavirus precisely to preclude the spread of fake news. The proposed approach performed very well on the given dataset and showed higher accuracy when compared to similar state-of-the-art studies. In future work, we plan to analyze public sentiments toward other essential topics, such as government response to the pandemic situation, healthcare facilities by government, offline examination, and mental health by using DL algorithms to increase their performance on the dataset. One limitation of this work is that it is specific and does not look at the mood and emotions of the people. Further work can be done on the detection of mood-based sentiment analysis.

We conclude that the machine is generating the best results for the Logistic Regression with Grid Search CV (count vectorizer) model with an Accuracy of 78.28% followed by the Logistic Regression with Grid Search CV (TF/ID vectorizer) model with an Accuracy of 77.43%.

Also, we observed that no overfitting is seen for the data, and we can deploy this model.

Even being in the unprecedented situation of CoVid-19, people's positive sentiments outnumbered negative sentiments.

However, negative sentiments also has a significant chunk which various Government agencies, NGOs, etc can use to help boost the morale of the people and then

In the future ,we can repeat the analysis and compare it with the present sentimental analysis to gauge the impact of the initiatives on the ground.



![image](https://user-images.githubusercontent.com/114379464/234481449-d70f19fa-6311-46c4-a482-ae2603613af8.png)




📚 References:


Random Forest Regressor - https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestRegressor.html

Gradient Boosting Documentation - https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.GradientBoostingClassifier.html

https://www.frontiersin.org/articles/10.3389/fpubh.2021.812735/full#B1
