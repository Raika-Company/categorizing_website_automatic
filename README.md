# Website Classification Model

## Introduction

This project aims to develop a machine learning model capable of classifying websites based on their content and structure. The model predicts the categories and tags relevant to each website, facilitating tasks such as content filtering, search engine optimization, and website recommendation systems.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Technology Stack](#technology-stack)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features

- Accurate classification of websites into predefined categories.
- Detection of relevant tags for content analysis.
- Has multiple languages such as : Persian-English

## Technology Stack

- Python 3.8
- Scikit-Learn for machine learning models
- BeautifulSoup for web scraping
- Selenium for web scraping
- NFstream

## Dataset

The first version of model was trained on a dataset comprising over 1000 websites, categorized into 16 main categories such as News, Education, Games, etc. The dataset was curated from publicly available sources and preprocessed for noise removal, normalization, and feature extraction.
For collecting more datasets and information I used two different technologies which they are NFstream for analyzing the packets which they are in network and Selenium for webscraping.

## Model Architecture

The classification model uses a different algorithms, because I want to check the accuracy and perfomance of them. For first step of training I check classification of algorithms like Random Forest , Decision Tree. You can find the Random Forest implementation is NFstream.ipynb file that is our first version of training model. In later research, I find the BERT model which is for NLP machine learning programs due to,
I work with that which is in bert.ipynb file and I put comments for each block code.

# Set up a virtual environment

`python -m venv bert`

`bert\Scripts\activate`

# Install the dependencies

`pip install -r requirements.txt`
