# The-Titanic-Story
## Introduction
The sinking of the RMS Titanic is one of the most infamous shipwrecks in history.  On April 15, 1912, during her maiden voyage, the Titanic sank after colliding with an iceberg, killing 1502 out of 2224 passengers and crew. This sensational tragedy shocked the international community and led to better safety regulations for ships. One of the reasons that the shipwreck led to such loss of life was that there were not enough lifeboats for the passengers and crew. Although there was some element of luck involved in surviving the sinking, some groups of people were more likely to survive than others, such as women, children, and the upper-class passengers.

## Objective
This project aims to provide a complete analysis of what sorts of people were likely to survive.

## Methodology
### Data Understanding
The data understanding phase starts with an initial data collection and proceeds with activities in order to get familiar with the data, to identify data quality problems, to discover first insights into the data, or to detect interesting subsets to form hypotheses for hidden information.

### Check Data Quality
Most common checks in this case is to check missing values, some basic data cleaning like cleaning up currency field, checking for null values, converting the currency column to a float datatype and removing '$' from the fare column.

 ### Exploratory Data Analysis - EDA
EDA is an approach to analyzing data sets to summarize their main characteristics, often with visual methods. This approach is used in this case to identify the main characteristics of the dataset that will be necessary for the analysis.

#### Types Of Features
##### Categorical Features:
A categorical variable is one that has two or more categories and each value in that feature can be categorised by them.For example, gender is a categorical variable having two categories (male and female). Now we cannot sort or give any ordering to such variables. They are also known as Nominal Variables.

Categorical Features in the dataset: Sex,Embarked. The project analyses Survived as a univariant, determining the relationship between Sex and Survival, Embarked and Survival. A bar chart is used to demonstrate these relationships.

##### Continous Feature:
A feature is said to be continous if it can take values between any two points or between the minimum or maximum values in the features column.

Continous Features in the dataset: Fare. The project plots the continuous features using a histogram.

### Data Visualization
Here, we look at the various plots that were created for the analysis.
#### Plot Perished vs Survived.
Plot bar chart for Survived column. Survived=0 means Perished, Survived=1 means Survived.

#### Plot for the Number of Male and Female Passengers

#### Plot to find Survival rate of Male and Female Passengers
This is done by grouping the survival column by sex.

#### Plot Perished vs Survived for Male and Female
In this case, use seaborn countplot() but set argument `hue` to 'Survived'.

#### Plot Survival Rate of each Pclass

#### Plot Perished vs Survived for each Pclass

#### Plot histogram for Age
The project uses pandas series hist() function which handles missing values.

#### Stack Age histogram of Survived on top of overall Age histogram
This plots histogram for Age, then filters out survived passengers and plot histogram for Age on same axis but sets different color and label.

##### This is a concise summary of activities carried out in the project.

## Appreciation
I highly recommend Azubi Africa for their comprehensive and effective programs. Read More articles about [Azubi Africa here](https://medium.com/@azubiafrica) and take a few minutes to visit this link to learn more about Azubi Africa life-changing [programs](https://bit.ly/41CGCwK)

## Tags
[Azubi Data Science](https://bit.ly/3ARq742)