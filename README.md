# Heart Disease Prediction Software

## Project Description
This software has been developed as a tool to help doctors and the general public in predicting the risk of having heart-related diseases, the development of this project started in relation to the 2019 .NET Conf MSP Hackathon - and has been, duly, submitted for the hackathon.

## Problem Statement
The problem (that this solution has been created to address) is centered around developing an ASP.NET Core MVC Web application that will predict the presence of heart disease based on 14 attributes i.e age, sex, and cp etc. given by the user of the software. 

In order to solve this problem, we built an ML model that takes 14 columns of data from the user - as inputs, 13 of these columns are independent, while the remaining 1 column - the 'Label' column - is what is being predicted, and as well gives the predicted result. 

## Dataset
To every ML project, there is always a dataset to build upon. And for this project, we have used a '[Training Data](https://github.com/bashirk/Heart_Disease_Prediction/blob/master/Heart_Disease_Prediction/ML_Model/Data/HeartTraining.csv)' downloaded from the open [UCI ML Repository](https://archive.ics.uci.edu/ml/datasets/Heart+Disease) - which contains real-life data from 300+ patients.

## Solution

How did we go ahead in solving this problem? 

- First, we created an ASP.NET Core MVC Web application via Visual Studio 2019. 
- Then we installed prerequisite packages from NuGet manager. 
- Next, we built an ML model for Heart Disease Prediction. 
- Thereafter, we trained the model on existing data using the dataset above. 
- Lastly, we consumed the model in our .NET Core application to predict if the heart disease is present for any given data by the user.
 
### How to setup this project locally

Prerequisites
Visual Studio (I'm using VS2019)
.NET Core 2.1 or > 2.1 SDK
Basic understanding of ASP.NET MVC or ASP.NET Core MVC
