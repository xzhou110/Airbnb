# Airbnb


The project is to help Airbnb hosts to maximize income on Airbnb. Rental income is primarily driven by two factors: Apartment Listing Price and Occupancy Rate. Analysis was performed on those two aspects. The end goal is to use the insights to help hosts make better decisions and increase income.

### Project Design: 

Firstly, we need to predict appropriate pricing for hosts to list their apartments. This is to enhance earning potential. Secondly, in order to improve occupancy rate, we need to get an understanding of customers' needs. This is to better serve customers, leading to improved word-of-mouth marketing and customer return rate. 

Step 1: Clean up datasets and perform regression on listings. Perform feature selection to drill down to features with statistical significance 
Step 2: Clean up datasets and identify apartments that have prices available in last 12 months. Add day of weeks and months as additional features. Perform price analysis and modeling.
Step 3: Perform topic modeling on customer reviews. Extract major topics that customers discuss about for  positive experience.  

### Tools: 
- Pandas for data manipulation
- Pickle for data storage
- SVD for dimension reduction
- KMeans for cluster analysis
- LDA for Topic analysis
- Word Cloud for visualization
 
### Data: 
- Dataset #1: Listings of apartmnets (name, host, apartment related information) - 10k+ listings
- Dataset #2: Listings of prices for a year - 240k+ prices
- Dataset #3: Customer Reviews - 150K+ reviews


### Algorithms:
- Linear Regression Analysis
- Non-linear Regression Analysis
- Topic Modeling

### Learning and Recommended Next Steps:
- Build a recommender system based on users' criteria


