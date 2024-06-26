# Happy-Customers
Apziva Project 1 - goal of this project is to create a model that predicts if a customer is happy or not given data from customer responses to a survey

### Background:
The company this project is based on is a company in the logistics and delivery domain. They specialize in making on-demand delivery to customers.
During the COVID-19 pandemic, this company faced several different challenges and was steadfast in addressing them.
Their goal is to make the customers happy. The only way to do that is to measure how happy each customer is and then work to predict what exactly makes their customers happy or unhappy. 
The company recently surveyed a cohort of customers, and we have been given a subset of this survey data to use at the training data for this project.

### Data Codebook:
Y = target attribute, integer values of 0 (unhappy customer) or 1 (happy customer)  
X1 = "My order was delivered on time"; one integer value from 1 to 5 where 1 is "Strongly Disagree" and 5 is "Strongly Agree".  
X2 = "Contents of my order were as I expected"; integer value from 1 to 5 where 1 is "Strongly Disagree" and 5 is "Strongly Agree".  
X3 = "I ordered everything I wanted to order"; integer value from 1 to 5 where 1 is "Strongly Disagree" and 5 is "Strongly Agree".  
X4 = "I paid a good price for my order"; integer value from 1 to 5 where 1 is "Strongly Disagree" and 5 is "Strongly Agree".  
X5 = "I am satisfied with my courier"; integer value from 1 to 5 where 1 is "Strongly Disagree" and 5 is "Strongly Agree".  
X6 = "The app makes ordering easy for me"; integer value from 1 to 5 where 1 is "Strongly Disagree" and 5 is "Strongly Agree".  

### Goal: 
- Using python, create a model that predicts if a customer is happy or not based on the answers they give to questions asked.
- This model must reach at least a 73% accuracy score, OR convince why your solution is superior. Write down any insights gained, we are interested in every solution and insight you can provide.

### Bonus Goals:
- Using a feature selection approach show what is the minimal set of attributes/features that would preserve the most information about the problem while increasing predictability of the data we have.
- Could any of the question variables be removed from the company's next survey?
