# Review_Analysis
Analyzing e-commerce reviews  to extract insights using sentiment analysis, topic modeling, and text classification for strategic decision-making.

# E-Commerce Sentiment Analysis Project

## Problem Statement
This project aims to analyze customer reviews from an e-commerce platform to extract valuable insights and improve overall customer satisfaction. The project involves performing sentiment analysis, topic modeling, and text classification on the reviews to understand customer sentiments, identify key themes, and categorize reviews into relevant topics. The insights gained from this analysis will guide strategic decision-making and enhance the company's product offerings and customer experience.

## Key Objectives
1. Perform sentiment analysis on customer reviews to gauge overall customer sentiment towards the products.
2. Utilize topic modeling techniques to identify prominent themes and topics discussed in the reviews.
3. Develop a text classification model to categorize reviews as Positive or negative.

## Dataset
The dataset consists of 23,486 rows and 10 feature variables. Each row corresponds to a customer review and includes the following variables:
- Clothing ID: Integer categorical variable referring to the specific piece being reviewed.
- Age: Positive integer variable representing the reviewer's age.
- Title: String variable for the title of the review.
- Review Text: String variable for the review body.
- Rating: Positive ordinal integer variable for the product score granted by the customer from 1 (worst) to 5 (best).
- Recommended IND: Binary variable indicating whether the customer recommends the product (1 for recommended, 0 for not recommended).
- Positive Feedback Count: Positive integer documenting the number of other customers who found this review positive.
- Division Name: Categorical name of the product high-level division.
- Department Name: Categorical name of the product department.
- Class Name: Categorical name of the product class.

## Technologies Used
- Python
- Natural Language Processing (NLP) libraries such as NLTK, spaCy
- Machine Learning libraries such as sci-kit-learn, TensorFlow
- Topic modeling techniques (e.g., Latent Dirichlet Allocation)
- Text classification algorithms (e.g., Naive Bayes, SVM)
- Data visualization libraries (e.g., Matplotlib, Seaborn)

## Usage
To use this project, you can follow these steps:
1. Download the dataset and preprocess it as necessary.
2. Run the sentiment analysis, topic modeling, and text classification scripts provided in the project.
3. Explore the insights from the analysis and make strategic decisions based on the findings.

