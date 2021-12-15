# **Recommendation Engine Problem**

## **Problem Description**

Netflix is all about connecting people to the movies they love. To help customers find those movies, they developed world-class movie recommendation system: CinematchSM. Its job is to predict whether someone will enjoy a movie based on how much they liked or disliked other movies. Netflix use those predictions to make personal movie recommendations based on each customer’s unique tastes. And while Cinematch is doing pretty well, it can always be made better.

Now there are a lot of interesting alternative approaches to how Cinematch works that netflix haven’t tried. Some are described in the literature, some aren’t. We’re curious whether any of these can beat Cinematch by making better predictions. Because, frankly, if there is a much better approach it could make a big difference to our customers and our business.

Credits: https://www.netflixprize.com/rules.html

## **Problem Statement**

Netflix provided a lot of anonymous rating data, and a prediction accuracy bar that is 10% better than what Cinematch can do on the same training data set. (Accuracy is a measurement of how closely predicted ratings of movies match subsequent actual ratings.)

## **Sources**

- https://www.netflixprize.com/rules.html

- https://www.kaggle.com/netflix-inc/netflix-prize-data

- Netflix blog: https://medium.com/netflix-techblog/netflix-recommendations-beyond-the-5-stars-part-1-55838468f429

- Surprise library: http://surpriselib.com/ 

- Surprise library doc: http://surprise.readthedocs.io/en/stable/getting_started.html 

- Installing surprise: https://github.com/NicolasHug/Surprise#installation

- Research paper: http://courses.ischool.berkeley.edu/i290-dm/s11/SECURE/a1-koren.pdf 

- SVD Decomposition : https://www.youtube.com/watch?v=P5mlg91as1c


## **Real world/Business Objectives and constraints**

### **1. Objectives:**

Predict the rating that a user would give to a movie that he ahs not yet rated.
Minimize the difference between predicted and actual rating (RMSE and MAPE).

### **2. Constraints:**

Some form of interpretability.

## **Authors**

- Sagar Gupta





