# Mobile-Price-Range-Prediction
# Problem Statement
In the competitive mobile phone market companies want to understand sales data of mobile phones and factors which drive the prices. The objective is to find out some relation between features of a mobile phone (eg:- RAM, Internal Memory, etc) and its selling price. In this problem, we do not have to predict the actual price but a price range indicating how high the price is
# Features Information
•	Battery_power - Total energy a battery can store in one time measured in mAh
•	Blue - Has bluetooth or not
•	Clock_speed - speed at which microprocessor executes instructions
•	Dual_sim - Has dual sim support or not
•	Fc - Front Camera mega pixels
•	Four_g - Has 4G or not
•	Int_memory - Internal Memory in Gigabytes
•	M_dep - Mobile Depth in cm
•	Mobile_wt - Weight of mobile phone
•	N_cores - Number of cores of processor
•	Pc - Primary Camera mega pixels
•	Px_height - Pixel Resolution Height
•	Px_width - Pixel Resolution Width
•	Ram - Random Access Memory in Mega
•	Touch_screen - Has touch screen or not
•	Wifi - Has wifi or not
•	Sc_h - Screen Height of mobile in cm
•	Sc_w - Screen Width of mobile in cm
•	Talk_time - longest time that a single battery charge will last when you are
•	Three_g - Has 3G or not
•	Wifi - Has wifi or not
•	Price_range - This is the target variable with value of 0(low cost), 1(medium cost), 2(high cost) and 3(very high cost).
# Introduction
I have implemented a Mobile Price Prediction using different Machine Learning Algorithms. This project will classify the price range of the mobile price. The price ranges from 0-3. We’ll discuss the price range in the dataset. It's a classification problem. Now I have trained a mobile price classification using 4 ML algorithms. This model classifies the range of the mobile based on the different parameters like from camera, touch screen, cores, battery, clock speed, internal memory, battery capacity, etc. After training the model using 4 algorithms.
# Data Pipeline
Exploratory Data Analysis (EDA): In this part we have done some EDA on the features to see the trend. Data Processing: In this part we went through each attributes and encoded the categorical features. Model Creation: Finally in this part we created the various models. These various models are being analysed and we tried to study various models so as to get the best performing model for our project.
# Comparison
Implemented various classification algorithms, out of which the Logistic Regression
algorithm gave the performance with 94% train accuracy and 94% test accuracy.

Implemented various classification algorithms, out of which the Random Forest algorithm
gave the best performance with 100% train accuracy and 88% test accuracy.

Implemented various classification algorithms, out of which the Decision Tree algorithm
gave the best performance with 87% train accuracy and 80% test accuracy.

Implemented various classification algorithms, out of which the XGBooster Classifier
algorithm gave the best performance with 98% train accuracy and 90% test accuracy.
# Conclusion
From EDA we can see that here are mobile phones in 4 price ranges. The number of elements is almost similar.

  Half the devices have Bluetooth, and half don’t.

  There is a gradual increase in battery as the price range increases.

  Ram has continuous increase with price range while moving from Low cost to Very high cost.

  Costly phones are lighter.

  RAM, battery power, pixels played more significant role in deciding the price range of mobile phone.

  Form all the above experiments we can conclude that logistic regression and, XGboosting with using hyperparameters we got the best results.


