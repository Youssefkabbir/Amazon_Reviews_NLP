# Amazon_Reviews_NLP

Table of Contents
=================
  * [Introduction](#Introduction)
    * [Check available plugins](#check-available-plugins)

    * [Activate/deactivate environment](#activatedeactivate-environment)
      * [Activating in a new shell](#activating-in-a-new-shell)
  * [How to add a plugin?](#how-to-add-a-plugin)
    * [Mandatory elements](#mandatory-elements)

# Introduction
Dataset Overview
This project uses an [Amazon Product Reviews dataset ](https://www.kaggle.com/datasets/arhamrumi/amazon-product-reviews/data), which contains customer reviews and ratings for a wide variety of products available on Amazon. The dataset is valuable for performing several Natural Language Processing (NLP) tasks, such as Sentiment Analysis, Topic Modeling, Named Entity Recognition (NER), and Text Summarization.

**Dataset Fields**
Each row in the dataset represents an individual review. Below are the key columns included:

**Id**: A unique identifier for each review entry.

**ProductId**: A unique identifier for the product being reviewed.

**UserId**: A unique identifier for the customer who wrote the review.

**ProfileName**: The name associated with the customer’s profile.

**HelpfulnessNumerator**: The number of users who found the review helpful.

**HelpfulnessDenominator**: The total number of users who rated the review for helpfulness.

**Score**: The rating given by the customer, typically ranging from 1 (very bad) to 5 (excellent).

**Time**: A Unix timestamp indicating when the review was posted.

**Summary**: A brief summary or title of the review.

**Text**: The full text of the customer review, which contains detailed feedback about the product.
**Dataset Characteristics**
This dataset contains detailed customer feedback, including star ratings and free-text reviews, making it ideal for text-based analyses such as:

- Sentiment Analysis: Understanding the positive, negative, or neutral sentiments expressed by customers.
- Topic Modeling: Identifying recurring themes across customer feedback.
- Named Entity Recognition (NER): Extracting entities such as product names, brands, and features.
- Text Summarization: Summarizing lengthy reviews to provide concise overviews.

**Data Size**
With thousands of reviews, this dataset provides a rich resource for exploring how customers perceive products, offering insights into quality, satisfaction, and areas for improvement.
