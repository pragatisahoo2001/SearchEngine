## Algozenith Hackathon Project

This project is part of the Algozenith Hackathon of Summer'23. The objective of this project is to create a search engine that allows users to find coding problems from popular coding platforms like Leetcode, CodeChef, and Codeforces using TF-IDF.

## Features

- Scrapes LeetCode, CodeChef and code forces question data using Selenium
- Trains a TF-IDF model on the question dataset
- Performs NLP processing to filter relevant words based on user queries
- Matches the top 20 results from the dataset based on the filtered words
- Provides a web interface for users to enter their queries and view the results
- Deployed on the Render platform for free hosting

## Technologies Used

- Python
- Selenium
- Flask
- scikit-learn (for TF-IDF implementation)
- HTML/CSS (for the web interface)
