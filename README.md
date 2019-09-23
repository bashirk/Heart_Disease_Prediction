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
 
# How to setup this project locally

### Prerequisites
    Visual Studio (We used VS2019)
    .NET Core 2.2 or > 2.2 SDK
    Web Browser (We used Microsoft Edge)
    
## Setup Instructions

    1. Clone this repository
    2. Open Visual Studio, click "Open" and locate the folder of the cloned repository.
    3. Next, you should see a folder - with the project name "Heart_Disease_Prediction" - and a file as well, 
       named "Heart_Disease_Prediction.sln" (notice the file extension .sln), this is the backbone of the .NET project.
    4. Then, click on this .sln file, and click 'Open'. This would import the entire project into Visual Studio.
    5. The build process for the project would start immediately.
    6. When this build process is completed, click the Play icon to rebuild and run the project.
    7. When this is done, VS2019 will automatically trigger another tab activity in your default browser - and eventually load        up the project.
    8. If this isn't done by VS, you can manually type in the localhost address to access the project in your browser.

#### Localhost address

http://localhost:5001/

# Team HackSaw
Below are the team members behind this project:

## Team Members
- Korede Bashir
- Oluwaseyi Ayodele
- Ayobami Ogunlade
