# BBC News Recommendation System

This project implements a content-based recommendation system using the BBC News dataset. The system suggests news articles to users based on their descriptions, categories, and similarity scores.

## Introduction
Recommender systems are vital in filtering vast amounts of information to provide users with personalized content. This project implements a content-based approach to recommend news articles from the BBC News dataset by analyzing their descriptions and matching them to user-provided input.

## Dataset

The dataset used is the BBC News dataset, download from [Kaggle](https://www.kaggle.com/datasets/hgultekin/bbcnewsarchive). Save it as `bbc-news-data.csv` in the root directory. For this demonstration, I randomly randomly samples 500 articles used to improve efficiency.

The dataset consists of BBC News articles categorized into topics such as:

* business
* entertainment
* politics
* sport
* tech
  
Each entry includes:

* title: The article headline.
* content: The content of the news.
* category: The article's topic classification.


## Setup

* Python 3.8+
* Jupyter Notebook

## Methodology


The recommendation process involves:

1. Data Loading: Reading and preprocessing the dataset.
2. TF-IDF Vectorization: Converting article descriptions into numerical representations.
3. Cosine Similarity Calculation: Measuring the similarity between user input and article descriptions.
4. Recommendation Generation: Ranking and displaying the top 5 similar articles.



## Example Usage and Output (within the Notebook)



- User Query: "current political events in the UK"
- Output:
  ```
  Top 5 Recommended News:
    -> Online games play with politics (Category: tech, Similarity: 0.24)
   After bubbling under for some time, online games broke through onto the political arena in 2004...
    -> 'Debate needed' on donations cap (Category: politics, Similarity: 0.11)
   A cap on donations to political parties should not be introduced yet, the elections watchdog has said...
    -> Navratilova hits out at critics (Category: sport, Similarity: 0.1)
   Martina Navratilova has defended her decision to prolong her tennis career at the age of 48...
    -> UK firms 'embracing e-commerce' (Category: politics, Similarity: 0.09)
   UK firms are embracing internet trading opportunities as never before...
    -> Britons fed up with net service (Category: tech, Similarity: 0.08)
   A survey conducted by PC Pro Magazine has revealed that many Britons are unhappy with their internet service...
  ```
  
#### Input

Enter a news topic or description: current political events in the UK

#### Results

Top 5 Recommended News:
-> Online games play with politics (Category: tech, Similarity: 0.24)
   After bubbling under for some time, online games broke through onto the political arena in 2004...
-> 'Debate needed' on donations cap (Category: politics, Similarity: 0.11)
   A cap on donations to political parties should not be introduced yet, the elections watchdog has said...
-> Navratilova hits out at critics (Category: sport, Similarity: 0.1)
   Martina Navratilova has defended her decision to prolong her tennis career at the age of 48...
-> UK firms 'embracing e-commerce' (Category: politics, Similarity: 0.09)
   UK firms are embracing internet trading opportunities as never before...
-> Britons fed up with net service (Category: tech, Similarity: 0.08)
   A survey conducted by PC Pro Magazine has revealed that many Britons are unhappy with their internet service...


## Video Demo 



## Salary expectation per month

My salary expectation is $2500-3000 / month.

