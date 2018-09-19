#Airbnb


The project is to perform a topic analysis on customer reviews for Amazon Echo. This is to understand what major factors drive positive vs. negative experience. The end goal is to use the insights to help business enhance self-awareness and make better decisions. The modeling from this project can be applied to any reviews of any product or service for insight extraction. 

### Project Design: 
Step 1: Clean up datasets and combine two datasets for analysis
Step 2: Break down reviews into positive (>3 rating) and negative sentiment (<3 rating) groups based on ratings 
Step 3: Performed cluster analysis on positive and negative sentiment groups 
Step 4: If limited information extracted from step 3, perform topic modeling on positive and negative sentiment groups 

### Tools: 
- Pandas for data manipulation
- Pickle for data storage
- SVD for dimension reduction
- KMeans for cluster analysis
- LDA for Topic analysis
- Word Cloud for visualization
 
### Data: 
- Dataset #1: Listings of apartmnets (name, host, apartment related information) - 10k+ listings
- Dataset #2: Listing prices for a year - 240k+ prices
- Dataset #3: Customer Reviews - 150K+ reviews


### Algorithms:
- Linear Regression Analysis
- Non-linear Regression Analysis
- Topic Modeling

### Learning and Recommended Next Steps:
- Build a recommender system based on users' selection


