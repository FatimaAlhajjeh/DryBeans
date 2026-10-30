# DryBeans
## Problem Statement
The problem addressed in this project is the classification of dry beans using machine learning 
techniques. The aim is to develop a model capable of accurately assigning each dry bean to one 
of seven distinct classes based on 16 different features. The challenge lies in creating a reliable 
and efficient machine learning model that can learn patterns from these features and make 
accurate predictions regarding the class to which each dry bean belongs.  
## Dataset Description
The dataset contains 13,612 samples, each representing a unique dry bean, with some 
characteristics. Before doing some preprocessing, we took a close look at the data in what we 
call Exploratory Data Analysis (EDA). Luckily, we didn't find any missing values.  
As we can see, some features in the datasets seemed to be highly correlated, and that could 
cause problems like multicollinearity and data sensitivity. To handle that, we used a 
dimensionality reduction technique called Principal Component Analysis (PCA) where we will 
discuss the process later, to simplify things without losing important information, and when we 
performed the PCA we reduced the features from 16 to 8.
