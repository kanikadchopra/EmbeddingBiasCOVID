# Ethnic Bias in COVID-19 Related Articles
This project leverages word embeddings to quantify the ethnic biases in COVID-19 related articles. 

## Goals
This exploration includes investigating the associated bias for Asians in comparison to White ethnicities. This analysis is broken into the following sections:
1. Association with COVID-19 terms
2. Assocation with Hate Crimes
3. Association with Outsider Adjectives
4. Sentiment of Most Associated Adjectives

## Data 
The data was collected using AYLIEN's COVID News dataset. Data is presented in JSONL file format with one line per story object. To access the origina AYLIEN dataset, you can sign up to download it for free here: https://aylien.com/blog/free-coronavirus-news-dataset

Word lists were collected through a compilation of news articles and papers for COVID-19 and Hate Crime terms. Outsider adjectives and the larger list of general adjectives were used from the SI of _Word Embeddings Quantify 100 Years of Gender and Ethnic Stereotypes_.

## Analysis
To re-run all of the analyses: 
* Download the word lists from the data section
* Download the embedding models from the `models` folder
* Run the code in `embeddings_ethnicCategories.ipynb`, `embeddings_wordCategories.ipynb` and `embeddings_largeAdjectives.ipynb` to generate all of the analyses and plots 
 

These notebooks are categorized into the three computational methods, first analyzing embedding bias with group vectors representing categories, secondly with group vectors representing categories and then lastly the sentiment analysis with a larger list of adjectives 

