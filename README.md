# Starbucks
Reward analysis for the Starbucks mobile app

### Installation:
This project does not require any libraries outside Anaconda. Python 3 was used for this project.
    
### Project Motivation:
In this project, we look at the simulated data that mimics customer behavior on the Starbucks rewards mobile app.

We aimed to answer 3 main questions,

1. Can we reasonably predict whether or not someone will respond to a particular offer?
2. What are the most predictive features in the data that helps us determine whether or not someone will respond to an offer?
3. Certain individuals do not need an offer sent to them to complete the conditions required on an offer, and in such cases, we shouldn’t send them an offer. What are the characteristics of these customers?

### File Descriptions:		
	- Starbucks Project.ipynb # The Jupyter notebook has all the code and the explanation of the flow necessary for this project

	- data.zip
	|- portfolio.json  # contains offer ids and meta data about each offer (duration, type, etc.)
	|- profile.json  # demographic data for each customer
	|- transcript.json # records for transactions, offers received, offers viewed, and offers completed

### Instructions:
Running the Jupyter notebook will answer the questions posted above, and you can read the post about my findings [here](https://medium.com/@araman520/reward-analysis-for-the-starbucks-mobile-app-7d9b6c32d25b).
    
### Results:
These were the conclusions of this analysis,

1. We can reasonably predict the response of a user to an offer. We trained several machine learning models which gave an 80% accuracy and F beta score.
2. The top 5 features in predicting a user’s response to an offer are, the reward for completing, the date when the customer joined, the fact that the offer is informational, the time for which the offer would be open, and the minimum required spend to complete an offer.
3. We clustered the customers, and the major proportion of the customers that complete offers without even viewing the offer are aged between 50 and 70 years, and earn around $100,000.
    
### Licensing, Authors, Acknowledgements:
The data used for this project is in the data.zip folder. Anyone is allowed to use the code used in this project as they please.
