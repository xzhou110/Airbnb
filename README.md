# Airbnb Host Income Enhancement


The project is to help Airbnb hosts to maximize income on Airbnb. Rental income is primarily driven by two factors: listing price and occupancy Rate. The analysis was performed on those two aspects. The end goal is to use the insights to help hosts make better pricing decisions, improve user experience to boost occupancy rate, and eventually increase income.

### Project Design: 

Firstly, we need to predict appropriate pricing to list apartments, which can help maximize earning potential. Secondly, in order to improve occupancy rate, we need to gain an understanding of customers' needs. This is to improve customer experience, leading to enhanced word-of-mouth marketing and customer return rate. 

Step 1: Data retrieval and exploration. Perform linear and non-linear regression models on pricing data. Select features based on importance of features 
Step 2: Add timing and seasonality information. Updated pricing model with seasonality information. 
Step 3: Perform topic modeling on customer reviews. Identify major topics that drive positive experience.  

### Tools: 
- Data Manipulation: Python, Pandas
- Data Storage: Pickle
- Dimension Reduction: SVD
- Cluster Analysis: K-means
- Topic Modeling: LDA
- Visualization: Word Cloud
 
### Data: 
- Dataset #1: Listings of Apartments (name, host, apartment related information) - 10k+ listings
- Dataset #2: Listing Price for Entire Year - 240k+ prices
- Dataset #3: Customer Reviews - 150K+ reviews


### Algorithms:
- Linear Regression Analysis
- Non-linear Regression Analysis
- Topic Modeling

### Learning and Recommended Next Steps:
- Build a recommender system based on users' criteria
