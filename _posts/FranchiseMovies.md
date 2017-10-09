
---

title: Project Franchise Movies Box Office Predicition
---
*Data Science aiding Movie Investment Decisions*
---
  

### Objective  
Predicting World Wide Gross of a Franchise Movie on the basis of its **sequence** in the Franchise


### Data Sources 
Scrapped the following websites:
* **Box Office Mojo**  
* **The Numbers** 

### Web Scrapping Tools Used:
* Scrapy
* Selenium
* Beutiful Soup
 
### Statistical Tools Used for Modeling:
* Ordinary Least Sqaure(OLS)
* Lasso Reqularization
* Ridge Regularization
* Lasso Cross Validation

### Some Interesting Findings:
* The model can predict 57% of the variance in WorldWide Gross.
  * Adjusted r2 of 0.573
  * Model was regularized and cross validated using Lasso Cross Validation
* Franchise Sequence & interaction between Franchise Sequence & Widest Release are good predictors of Worldwide Gross
* Surprisngly the Franchise Sequence has a negative impact on Worldwide Gross. However, the interaction between Franchise Sequence & Widest Release impacts worldwide Gross positively
* Other important and obvious features were the Movie's Budget and Run Time
* Interestingly the movies that the model underpredicted by 10% or more of their actual World Wide gross were mostly from Horror genre and a few were cult movies like Indian Jones and the Temple of Doom. And what is even more interesting is that some of these horror flicks  are regardes as the most profitable movies of all time as these movies were made independently at extremely low budgets and later on boughtby big movie production houses.
* On the other hand, the model over predicted a handful of movies that had a combination of extremely low budgets and very low widest release.
* Although as per the model's prediction it udnderpredicted certain Genres don’t have a significant impact on predicting Worldwide Gross

 
### Next Steps:
Acquire data on World Wide Gross for all the movies in a Franchise  
Re-investigate the prediction basis Worldwide Gross of the previous movie in the Franchise

   
  
 
 
