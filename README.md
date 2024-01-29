# PREDICTING PRODUCT RELIABILITY IS BASED ON EMOTIONAL ANALYSIS OF COMMENTS OF THE FASHION INDUSTRY ON SHOPEE E-COMMERCE

##ABOUT THE PROJECT
This project aims to analyze the sentiments expressed in comments of fashion products on the e-commerce platform - Shopee. By utilizing natural language processing (NLP) techniques and machine learning, we seek to gain deeper insights into the opinions, thoughts and emptions of consumers towards products on Shopee and then, we conduct products' reiability assessment.
Especially, we processed Vietnamese comments, a language that currently has quite few resources. In this project, we used PhoBERT to solve this problem.

##GOALS
* Sentiment Analysis: Identify and classify emotions in comments into groups included postitive, negative and neutral.
* Opinion Understanding: Determine the main opinions and evaluations of users towards products
* Reliability Assessment: Assess the reliability of products based on the ratio of comment score to star rating.

##TECHNOLOGY
1. Programming language: Python
2. Libraries:
   * NLTK (Natural Language Toolkit) for natural language processing
   * Scikit-learn and TensorFlow for machine learning and modeling

##USAGE
1. <b>Data collection</b>: Use the Shopee API to retrieve comments from fashion products.
2. <b>Data preprocessing</b>: Remove punctuation, convert to lowercase, replace slangs and perform other preprocessing to prepare the data for analysis.
3. <b>Consensus evaluation</b>: Use Fleiss Kappa to evaluate consistency in comment labeling.
4. Sentiment and Opinion Analysis: Utilize 6 trained models to analyze sentiment and extract opninions from comments.
5. Display Results: Visualize results.

<hr>

<i><b>Note:</b>This project is for research and educational purposes only. We do not take responsibility for the use of data from Shopee without their permission.</i>

