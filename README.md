# Anson's Data Science Profolio
The website is intended to post my data science projects inspired form Kaggle, IBM AI Engineering and IBM Data Science Certificate, covering:

&emsp;&emsp; 1) &emsp;  LSTM with Time Series Analysis of Traction Power Substation Loading  <br/>
&emsp;&emsp; 2) &emsp;  The Prediction of Voltage at the Pantograph for Passenger Trains  <br/>
&emsp;&emsp; 3) &emsp;  Household Electric Power Consumption by LSTM  <br/>
&emsp;&emsp; 4) &emsp;  Prediction of Stock Price using LSTM  <br/>
&emsp;&emsp; 5) &emsp;  Health Insurance Cross Sell Prediction  <br/>
&emsp;&emsp; 6) &emsp;  Google Play Store Apps  <br/>
&emsp;&emsp; 7) &emsp;  Capstone Project - The Battle of Neighborhoods 

<br/><br/><br/><br/>



## 1. Real Work Experience- LSTM with Time Series Analysis of Traction Power Substations Loading

<img width="706" alt="Brig2" src="https://user-images.githubusercontent.com/63663095/130985018-a273b0ab-a98c-4d83-848a-9f010c88e0cd.jpg">

It is my another real work experience for the time series analysis of all traction power substation loading in LRT3. The use of LSTM can be effective to predict the forward value of power consumption in the network. Two LSTM layers and 480 seconds look back time have been adopted and give the accurate prediction.

The result of loss for the model is **0.0186**

My Code is sharing as follows: <br/>
Code in Github: [Code](https://nbviewer.jupyter.org/github/ansonlalu/Anson-Data-Science-Portfolio/blob/bae149e7db10a634b3220ce99a1f9dcbe2ac39f8/6.1_20210704_LSTM%20with%20Time%20Series%20of%20TPSS%20Loading.ipynb)
<br/><br/><br/><br/>




## 2. Real Work Experience- The Prediction of Voltage at the Pantograph for Passenger Trains

<img width="706" alt="Real Work Experience- The Prediction of Voltage at the Pantograph for Passenger Trains" src="https://user-images.githubusercontent.com/63663095/129641302-008ab2e3-7b66-4d15-9a32-4f91e14391be.jpg">

It is my real work experience for the prediction of Voltage at the Pantograph for Passenger Trains. The use of Random Forest and XGBoost have been adopted for the regression analysis. The input of parameters are used for the prediction.

&emsp;&emsp; 1. LinePosition <br/>
&emsp;&emsp; 2. Train Speed <br/>
&emsp;&emsp; 3. Propulsion in Force <br/>
&emsp;&emsp; 4. Train Efficiency for Conversion <br/>
&emsp;&emsp; 5. Electrical Power of Rolling Stock <br/>
&emsp;&emsp; 6. Phase Angle in Pantograph <br/>
&emsp;&emsp; 7. Mechancial Power of Rolling Stock <br/>


The result of best score for Random Forest, XG Boost and LightXGM are **0.857**, **0.849** and **0.847** respectively.

My Code is sharing as follows: <br/>
Code in Github: [Code](https://github.com/ansonlalu/Anson-Data-Science-Portfolio/blob/054582e74f144564a9aa727336ca9084965b948a/6.2_20210822_Power%20Consumption%20for%20Rolling%20Stock.ipynb)
<br/><br/><br/><br/>




## 3. Household Electric Power Consumption by LSTM 

<img width="706" alt="4_Kaggle_Household Electric Power Consumption_LSTM" src="https://user-images.githubusercontent.com/63663095/106499078-16fa3f80-64fb-11eb-820f-8ef5d60ea03a.jpg">

This work is to predict the Household Electric Power Consumption by using LSTM. The features are used to forecast the active power used in the future and listed below.

&emsp;&emsp; 1. Active Power <br/>
&emsp;&emsp; 2. Reactive Power <br/>
&emsp;&emsp; 3. Voltage <br/>
&emsp;&emsp; 4. Global_intensity <br/>
&emsp;&emsp; 5. Sub_metering_1 <br/>
&emsp;&emsp; 6. Sub_metering_2 <br/>
&emsp;&emsp; 7. Sub_metering_3 <br/>

The result is briefly listed, loss: 0.0103,  val_loss: 0.0088

My Code is sharing as follows: <br/>
Code in Github: [Code](https://github.com/ansonlalu/Anson-s-Data-Sceience-Profolio/blob/master/4_Kaggle_Household_Electric_Power_Consumption_LSTM.ipynb)
<br/><br/><br/><br/>




## 4. Prediction of Stock Price using LSTM

<img width="706" alt="Prediction of Stock Price using LSTM" src="https://user-images.githubusercontent.com/63663095/125904308-6823f306-1e32-40e6-953e-f611ccbbb231.jpg">



This is my preliminary work is to predict the stock price of Nvidia by using LSTM. Different features gathered from Yahoo Finance, covering: 

&emsp;&emsp; 1. Open Price                 <br/>
&emsp;&emsp; 2. High Price                 <br/>
&emsp;&emsp; 3. Low Price                  <br/>
&emsp;&emsp; 4. Volume                     <br/>
&emsp;&emsp; 5. Close Price                <br/>
&emsp;&emsp; 6. Closing Price of UPP       <br/>
&emsp;&emsp; 7. Closing Price of GDX       <br/>
&emsp;&emsp; 8. Closing Price of QQQ       <br/>

Those are used for the prediction of the closing price. The work will be amended from time to time for better accuracy.

My Code is sharing as follows: <br/>
Code in Github: [Code](https://nbviewer.jupyter.org/github/ansonlalu/Anson-Data-Science-Portfolio/blob/6c2dc97ece1ce02e179055e63b4d2872017bbdbb/5.1_20210704_LSTM%20with%20the%20Multivariables%20of%20Nvidia.ipynb)

<br/><br/><br/><br/>


## 5. Health Insurance Cross Sell Prediction- Best Score: 0.87735 for XG Boost

<img width="706" alt="1_Google Play Sore Apps" src="https://user-images.githubusercontent.com/63663095/102711005-7b699280-42f1-11eb-9fe2-5d6c74921c09.jpg">


This work is to predict customers whether they are really interested in the new product of Vehicle Insurance provided by the client of Insurance Company in this project. This project includes the topic commonly appear in data science, covering: <br/>

&emsp;&emsp; 1.	Exploratory Data Analysis (Count Plot, Distribution Plot, Correlation Matrix, etc.) <br/>
&emsp;&emsp; 2.	The Use of Random Forest Classifier <br/>
&emsp;&emsp; 3.	The Use of Feature Importance <br/>
&emsp;&emsp; 4.	The Use of Randomized Search for Random Forest <br/>
&emsp;&emsp; 5.	The Use of Randomized Search for XG Boost <br/>
&emsp;&emsp; 6.	Reference <br/>

My Code is sharing as follows: <br/>
Code in Github: [Code](https://github.com/ansonlalu/Anson-s-Data-Sceience-Profolio/blob/master/3_Kaggle_Health_Insurance_Cross_Sell_Prediction.ipynb)

<br/><br/><br/><br/>



## 6. Google Play Store Apps 

<img width="706" alt="1_Google Play Sore Apps" src="https://user-images.githubusercontent.com/63663095/96374444-7e3af080-11a5-11eb-9e75-7819bbe0ba36.png">


The project uses the data to perform data analysis utilizing different tree-based models, covering Decision Tree, Random Forest, XGBoost, LightGBM to identify the accuracy of R2 score for the rating of the App over 10000 mobile apps in the Google Play Store Apps.

Meanwhile, the train test split and cross-validation will be also adopted for model evaluation.

Code in Kaggle: [Code](https://www.kaggle.com/ansonlo/prediction-of-rating)<br/>
Code in GIthub: [Code](https://github.com/ansonlalu/Anson-s-Data-Sceience-Profolio/blob/master/2_Prediction-of-Rating.ipynb)


<br/><br/><br/><br/>


## 7. Capstone Project - The Battle of Neighborhoods

<img width="506" alt="2_The Battle of Neighborhoods" src="https://user-images.githubusercontent.com/63663095/97613707-f92cc280-1a53-11eb-9c2a-bbbf9306938c.jpg">


The project is to investigate the comprehensive data analysis shall be implemented in order to understand the capability, price, categories (Japanese food restaurant or sushi restaurant) and rating for the Japanese Restaurant in New York City. The assessment can help understand what business strategy of Japanese restaurant shall be made (e.g. pricing strategy, decision for the acquisition of higher rating, location, etc.) before its new launch. 

<br/>

Code: [Code](https://github.com/ansonlalu/Anson-s-Data-Sceience-Profolio/blob/master/1_Capstone%20Project%20-%20The%20Battle%20of%20Neighborhoods%20(Latest)%20(1).ipynb)<br/>
PowerPoint: [PPT](https://github.com/ansonlalu/Anson-s-Data-Sceience-Profolio/blob/master/1_Capstone%20Project%20-%20The%20Battle%20of%20Neighborhoods_PPT.pdf)<br/>
Study Report: [Report](https://github.com/ansonlalu/Anson-s-Data-Sceience-Profolio/blob/master/1_Capstone%20Project%20-%20The%20Battle%20of%20Neighborhoods%20(Week%202)_Report%20(1).pdf)

<br/><br/>

