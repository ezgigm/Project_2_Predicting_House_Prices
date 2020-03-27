README helps navigate the repository

README outlines the business problem and project goals

README explains findings succinctly

README discusses the metrics used, with some explanation of why those metrics were used to evaluate models

README explains the final model and how it compares to an initial baseline

README outlines some recommendations and lists out future improvements and potential weaknesses in data/models

Both the original data and the version used for analysis are available in the repository






# The Sale Price Of Houses

**The Goal:**
 The goal of this project is to predict the the sale price of homes based off of the zipcode the home is located in.
 
 **The Problem:**
 
 During our daily commute we tend to drive past homes that are either appealing to the eye or homes that just need a bit of work. After that moment of admiration or of making plans on how you would fix up a home, you drive on and forget about it. 
 
 But what if you didn't forget about it, what if you actually followed through with your idea and bought a brand new home, or even a fixer upper? Where would you even begin to bring such a thought to life? Most importantly, how much would it be to make it happen? 

Once those questions are answered you will see that the more research you do the more the prices vary depending on the area you decide to purchase in. Not to mention the other factors that play a role in a homes price i.e. water front view and a basement. So now the price you had set for a budget begins to increase due to the lack of knowledge when looking into the value of the home you want to purchase.

**The Solution:** 

 Here at DS Borg Homes our team has spent the last year developing a model that will be able to tell how much a home is actually  worth by just simply typing in the zipcode! Voilà!! No more long nights of scouring through papers, websites, or phone numbers trying to find the answers you need. With our model, DS Borg Homes will help you find the perfect price for the perfect home.   
 
 
**The Data:**
 The data used to acheive our goal is from the King County House Sales dataset. 

**The Plan:** 
 The way we plan on tackling this is by doing the following:
 
1. Cleaning the data
2. Exploring the data
3. Modeling the data

# Cleaning & Exploring The Data:

 The first thing we did was look at the data while keeping in mind the following questions:
 
 1. What information do we have?
 2. What information are we missing?
 3. What information do we need to get rid of?
 
From viewing the data we found that we had 22 columns which consisted of information on a list of homes that played a role in its price for the years 2014 and 2015; size of the home, the year it was built, the year it was renovated, number of batherooms and bedrooms, etc. 

The missing values were represented with a *?* or a *NaN*, this was the issue we decieded to deal with first. After the missing values were taken care of we continued viewing the data for anything that would interfere with the modeling proccess. This included changing outliers and dropping coolumns. Afterwards the clean data was saved to a csv file.

 The following csv file is where the cleaned data of the needed columns are found **(insert csv file link here)** 
 
 The following notebook shows the cleaning & exploring of the data  **(insert notebook link here)**
 
 
 # Modeling The Data 
graphed a heatmap to view the correlation between each column vs the price column, with this we would be able to determine which columns were important and which columns were not. 
 
 Now that we had clean data and the list of clumns we needed to model the data it was time to create a new dataset saving all of the work that was done. 
