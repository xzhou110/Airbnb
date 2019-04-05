# Airbnb Host Income Enhancement


The project is to help Airbnb hosts to maximize income on Airbnb. Rental income is primarily driven by two factors: listing price and occupancy Rate. The analysis was performed on those two aspects, with the end goal to help hosts optimize pricing decisions, improve user experience for occupancy rate improvement, and eventually increase overall income.

### Project Design: 

Firstly, we need to predict appropriate pricing to list apartments, which can help maximize earning potential. Secondly, in order to improve occupancy rate, we need to gain an understanding of customers' needs. This is to improve customer experience, leading to enhanced word-of-mouth marketing and customer returning rate. 

Step 1: Data retrieval and exploration. Performed initial linear and non-linear regression models on pricing data
Step 2: Added timing and seasonality information. Updated pricing model with seasonality information. Selected features based on future importance.
Step 3: Performed topic modeling on customer reviews. Identified major drivers of customer experience.  

### Tools: 
- Data Manipulation: Python, Pandas
- Data Storage: Pickle
- NLP: NLTK
- Topic Modeling: LDA
- Visualization: Word Cloud
 
### Data: 
- Dataset #1: Listings of Apartments (name, host, apartment related information) - 10k+ listings
- Dataset #2: Listing Prices of Apartments for Entire Year - 240k+ prices
- Dataset #3: Customer Reviews - 150K+ reviews


### Algorithms:
- Linear Regression
- Non-linear Regression
- Topic Modeling

### Slides:
https://docs.google.com/presentation/d/1QiGoTwe4R6iVrAJ_zYK4TZFYHTBL-LhNMNycr35jxSA/edit?usp=sharing

### Learning and Recommended Next Steps:
- Build a recommender system based on users' selected criteria
