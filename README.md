![cover_1_CTBt1pB-thumbnail-1200x1200-90](https://user-images.githubusercontent.com/63875409/88484439-10a76b80-cf8c-11ea-978e-e44c2b5c7c32.jpg)

## 1. Problem Definition
> We need to daetermine the outcome of the harvest season, i.e. whether the crop would be healthy (alive), damaged by pesticides or damaged by other reasons.

## 2. Data
> The data is downloaded from the analytics vidhya's weekend hackathon JanataHack: Machine Learning in Agriculture Hackathon : https://datahack.analyticsvidhya.com/contest/janatahack-machine-learning-in-agriculture/#ProblemStatement

There are 2 main datasets 
* train.csv 
* test.csv

## 3. Evaluation
> The evaluation metric for this hackathon is Accuracy Score.

## 4. Features

#### Data Dictionary

1. ID  :-                        UniqueId
2. Estimated_Insects_Count  :-   Estimated insects count per square meter
3. Crop_Type  :-	                Category of Crop(0,1)
4. Soil_Type  :-                Category of Soil (0,1)
5. Pesticide_Use_Category	 :-    Type of pesticides uses (1- Never, 2-Previously Used, 3-Currently Using)
5. Number_Doses_Week  :-	        Number of doses per week
6. Number_Weeks_Used  :-	        Number of weeks used
7. Number_Weeks_Quit  :-	        Number of weeks quit
8. Season  :-	                    Season Category (1,2,3)
9. Crop_Damage  :-	              Crop Damage Category (0=alive, 1=Damage due to other causes, 2=Damage due to Pesticides)
