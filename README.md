# Click Masters Inc.
![mouse click](https://media-public.canva.com/MADoO1Ck2Y0/1/thumbnail_large.png)

**The Project:** For our Module 4 project we were given the freedom to choose our own dataset. For that dataset we would then create a model that will solve a problem we have assigned as our focus.

**The Goal:** The goal of this project is to show my knowledge of the data science process.

**The Problem:** The company TalkingData has reached out to us for help! The ads for  mobile apps are getting clicks and downloads at an alarming rates, something just isn't adding up. So they have hired us to determine if the downloads are fraudulent or not. It's binary classification problem!


**The Data:** Two years ago the TalkingData AdTracking Fraud Detection Challenge was brought to Kaggle, along with provided data of "200 million clicks over 4 days". See repository to be guided to the data as well as the competition.   


**The Process**

1. Explore The Data 

2. Clean & Preprocess The Data

3. Model The Data

**The Model**

1. Light Gradient Boost


# Conclusion
With the selected parameters you will see in the notebook with the final version of the model, I was able to get a 95.5 % AUC Score.

# Future Recommendations 
After reviewing the competition results closely, I would look deeper into the click_time series and see if I can extract more features from it. I would also look into trying a Neuro Net Model to see how it does with such a large and imbalanced dataset. Lastly, I would like to obtain more data. More data is always a good thing when it comes to teaching your model!

**Feature importance:** As you can see, the hour column has potential to be broken down into a simpler form. My assumption is that, this will assist the performance of the model. 
![Feature importance bar graph](https://media-private.canva.com/J4UzY/MAD7aZJ4UzY/1/tl.png?response-expires=Thu%2C%2011%20Jun%202020%2008%3A39%3A11%20GMT&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20200611T060808Z&X-Amz-SignedHeaders=host&X-Amz-Expires=9062&X-Amz-Credential=AKIAJWF6QO3UH4PAAJ6Q%2F20200611%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=3d1ba0fbc05e71cde2c8244209c38fdb8a2c8a830386f2fd12b9adda72aa3ee5)

# Repository Guide 

***Link to Data and Competition:***  https://www.kaggle.com/c/talkingdata-adtracking-fraud-detection/overview
With this link you will find where you can download the data. Unfortunately the csv file is too large for github to upload. But I did provide a sample size of the data for those who are interested. 

***Link to Sample Data:*** https://github.com/bmor2552/ClickFraud/blob/master/Notebooks/sample_csv.csv

***Notebooks:*** In each notebook you will find links to resources used to obtain the code needed to perform data analysis.

***Data Exploring, Cleaning, & Preprocessing Notebook:*** https://github.com/bmor2552/ClickFraud/blob/master/Notebooks/Step1_DataCleaning_Exploration.ipynb


***Modeling Notebook:*** https://github.com/bmor2552/ClickFraud/blob/master/Notebooks/Step2_BaselineModel_FinalModel.ipynb


***Presentation:***
https://www.canva.com/design/DAD69f2bz0Q/KXjeazl5gguuD3G3D_uRvQ/view
