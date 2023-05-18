# Tornado Injuries Final Project
### An Analysis of Injuries Compared to Magnitude from Tornados
![tornado_cover](https://github.com/amiecostello22/Tornado_Alley/blob/main/images/tornado_cover.png)

## Purpose
The purpose of this analysis is to use a Linear Regression Model to identify, and then predict, injuries from tornados compared to the magnitude of the tornado. Our goal in analyzing the injuries from the tornado dataset is to determine if there is a trend in the reported injuries compared to the magnitude of the tornado. We can assume that a higher tornadic magnitude is likely to result in higher injuries. However, we want to see if other factors that can raise, or lower,  the injury rate. For example, does the starting location of the tornado, such as a specific state, seem to produce more tornadoes of a higher magnitude or tornados that stay on the ground for longer than other states? Will a lower magnitude tornado with a long path cause more injuries than a higher magnitude tornado that has a shorter path?

This analysis was completed as part of a final group project done by Matthew Baskette, Amie Costello, and Merabu Nagwandala. 


## Machine Learning Models
### Random Forest Model
Our first choice was a Neural Network using the Random Forest Regressor model. After several variations of the neural network we found that there was not enough data to run this model. When we tried to use the Random Forest Model we saw no change and we were not able to achieve the results we wanted. This was due to the fact that our dataset, while full of useable data, was too small to render a successul model.

### Multiple Liner Regression Model
Because of the multiple features we were using to predict our target, we chose a Multiple Linear Regression model for our second attempt. We were trying to predict the number of injuries and not just if an injury would happen, yes or no, so we knew we need to use a regression machine learning model. While it did perform better then our previous attempt it still didn’t hit the accuracy level we needed to prove our concept. This only gave us an accuracy of 55%.

![MLR](https://github.com/amiecostello22/Tornado_Alley/blob/main/images/multiple_linear_regression.png)

### Decision Tree Regressor
Not knowing at the time this was the best we were going to get we decided to try a third model. Again, because of our multiple features, we needed to choose a model that could handle that. We decided on a Decision Tree Regressor Model. This model did not perform as well as the Multiple Linear regression with an accuracy of only 47%.

![DT](https://github.com/amiecostello22/Tornado_Alley/blob/main/images/decision_tree.png)

### Linear Regression
We used a Linear Regression Model to create a plot to show the coorelation between magnitude and injuries. Our plot shows that as magnitude increases, the number of injuries also increases.

![LM](https://github.com/amiecostello22/Tornado_Alley/blob/main/images/linear.png)

#### Results
Each model showed us that there was no true regression to be found in this dataset that could predict the amount of injuries with any certainty. However, we did find several other interesting things in our investigation of this data. When we visualized our data, we were able to see clear coorelations between the number of tornados and the number of injuries. Same with the tornadic magnitude. You could also clearly observe spikes in the data during specific years where both the number of tornados and the number of injuries both spiked. Two of these spikes are in 1974 and 2011, both years notorious for having tornadic super outbreaks.


## Our Visualization Dashboard
Our group chose to use Tableau for our visualization dashboard. We've included a preview of our current dashboard draft.
- [Costello_Dashboard](https://public.tableau.com/app/profile/amie.costello/viz/Tornado_Data_Dashboard/Dashboard2)

![Dashboard](https://github.com/amiecostello22/Tornado_Alley/blob/main/images/dashb.png)

## Dataset Source
For our source, we used the US Tornado Dataset from [Kaggle.com](https://www.kaggle.com/datasets/danbraswell/us-tornado-dataset-1950-2021). 
This dataset has over 67,000 rows of tornado data in the United States from the years 1950 to 2021. The dataset also includes columns for the magnitude as well as the number of injuries for each tornado.
 
 
 ### Segment One Requirements
- [x] Create an ER diagram and setup database for your data (if applicable)
- [x] Create an rough outline of your visualization dashboard
- [x] Create a paper based mockup of your machine learning model
- [x] Continue to use Github for all the data
 
 ### Segment Two Requirements
- [x] A detailed README.md file that includes the project status, images, description, and results
- [x] First attempt of a machine learning model, including a confusion matrix and accuracy score
- [x] First attempt of a working dashboard
- [x] Draft of presentation

 ### Segment Three Requirements
- [x] A detailed README.md file that includes the project status, images, descriptions, and results
- [x] At least 12 total commits per team member
- [x] A machine learning model and an accuracy score
- [x] A dashboard that has at least one interactive element
 
 ## Presentation Plan
 - Greeting - Welcome, introduce team members
 - Introduction - Discuss purpose, dataset
 - Main Body 1 - Coding specifics
 - Main Body 2 - Coding specifics
 - Main Body 3 - Coding specifics
 - Tableau Dashboard
 - Static Images - Starting Location, Ending Locations
 - Static Images - Average Magnitude per Year
 - Static Images - Injuries per Year
 - Conclusion
 - Invite Questions


