Basics of a Recommendation Systems
A recommendation system is an information filtering system that provides personalized suggestions to users based on their preferences, behaviors and contextual data. It is widely used in allications like e-commerce, social media and streaming platforms.

Types of Recommendation Systems
1. Collborative Filtering
Relies on user system interactions like rating and clicks
Types:
    User-based filtering: Recommends items based on similarities bewteen users.
    Item-based filtering: Recommends items similar to items that the users have interacted with.
Algorithms
    k-nearest neighbors
    matrix factorization (svd)

2. Content based filtering
    Recommends items similar to what the user has interacted with based on the item features.
    Example: If a user watches scifi movie system recommends similar genre.
3. Hybrid Recommendation Systems
    Combines collaborative an dcontent based approaches to leverage their strengths and mitigate weaknesses.
    Example: Netflix's recommendation engine combines vieweing history (collaborative) with movie genres (content-based)


Key components:
1. Data collection
    Explicit data: Direct and intentional input like User rating and reviews
    Implicit data: Indirect behavioral data derived from user actions like watch histor, clicks, purchase history, time spent on a page, adding items in the cart or wishlist

2. Preprocessing and feature engineering
Data cleaning, normalization, handling misisng values
Feature engineering to extract meanigful singnals from raw data

3. Candidate Generation
    Narrow down a large set of items to a smaller set of relevant items
    Techniques Approximate Nearest Neighbors (ANN), Two Tower models

4. Ranking model
    Assigns relevance scores to retrieved items using ML models
    Techniques: Logistic Regression, Gradient Boosting, Deep Learning

5. Evaluation Metrics
    Precision, Recall, F1-Score, Mean Average Precision
    Business metrics: Click through Rate, Conversion Rate

    
