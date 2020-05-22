# Objective
To build a recommendation system to recommend products to customers based on the their previous ratings for other products
# Dataset
https://drive.google.com/file/d/1ClBptsK3V5KgKXtK2GSRzFNAW7GnTPDW/view?usp=sharing
# Data Description
For this model, we are using the Electronics dataset from Amazon Reviews data repository.
# Domain
E- Commerce
# Context
Online E-commerce websites like Amazon, Flipkart uses different recommendation models to provide different suggestions to different users. Amazon currently uses item-to-item collaborative filtering, which scales to massive data sets and produces high-quality recommendations in real-time.
# Attribute Information
userId: Every user identified with a unique id
productId: Every product identified with a unique id
Rating: Rating of the corresponding product by the corresponding user
timestamp: Time of the rating ( ignoring this column for our experiment)
# Learning Outcomes
●Exploratory Data Analysis
●Creating a Recommendation system using real data
●Collaborative filtering
# Steps Followed
1.Read and explore the given dataset.  
2.Take a subset of the dataset to make it less sparse/ denser. 
3.Split the data randomly into train and test dataset. 
4.Build Popularity Recommender model. 
5.Build Collaborative Filtering model. 
6.Evaluate both the models.
7.Get top -K ( K = 5) recommendations. Since our goal is to recommend new products foreach user based on his/her habits, we will recommend 5 new products. 
8.Summarise your insights.
