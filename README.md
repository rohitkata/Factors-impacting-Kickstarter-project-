# rohitkata.github.io_1

Problem statement: 
Crowdfunding has become one of the most popular funding techniques that start-ups utilize. However the probability of successfully raising funds through crowdfunding is still quite uncertain. If the start-ups can know the factors that impact the probability of successfully collecting the goal amount, they could tweak their campaign or business model and in turn increase their chances of success. That is what we aim to do through this project. We want to understand what factors impact the success and if we can come up with a model that can be used to predict the probability of success
Summary and Conclusion

•	After performing the exploratory data analysis, I realized the following factors to have an impact on probability of a project successfully receiving funds via Kickstarter:
     o	The month of launch of the campaign; the campaign has a higher success rate in February, March and April and have a lesser success rate in July and December.
     o	The main category of the product; some of the categories have a higher success rate.
     o	Country of the campaign; US seems to have a higher success rate than other countries
•	Used linear regression and correlation plots to establish a relationship between number of backers, goal amount and pledged amount. We were able to come with a strong relation between log of number of backers and log of pledged amount.
•	Used simulations to predict the probability of success by changing the goal amount.
•	Came up with a prediction model using logistic regression that could be used in the future to predict success rate given a particular category, country, goal and month of launch.
