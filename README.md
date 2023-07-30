# YouTube Sentiment Analysis Project

## Introduction
This is a YouTube Sentiment Analysis project that aims to analyze the sentiment of top comments on a given YouTube video. The project uses the YouTube Data API to retrieve the comments and then performs sentiment analysis to classify them as positive or negative.

## Requirements
- Python 3.x
- Google API Client library (`google-api-python-client`)
- Natural Language Toolkit (`nltk`)
- scikit-learn
- pandas
- matplotlib
- seaborn
- wordcloud

## Getting Started
1. Install the required libraries mentioned above 

2. Obtain a YouTube Data API key by following the instructions provided in the Google Developers Console.

3. Store your API key in a `config.py` file as `API_KEY = 'your_api_key_here'`. Ensure that you don't share your API key publicly.

## Project Structure
- `youtube_sentiment_analysis.ipynb`: The Jupyter Notebook containing the main code and analysis steps of the project.
- `model_building.ipynb`: Python script for model training and evaluation.
- Pickle files containing the trained models using TF-IDF and CountVectorizer are not included in this repsitory to save bloating, you may create them while training models(code already present to generate pkl files in `model_building.ipynb`

## How to Use
1. Run the Jupyter Notebook `youtube_sentiment_analysis.ipynb`. This notebook provides step-by-step instructions on how to extract top comments from a YouTube video and perform sentiment analysis using various machine learning models.

2. Ensure that you have set up your API key and other configurations in `config.py`.

3. The notebook will guide you through data preprocessing, model training, and evaluation. You can visualize the results and analyze the performance of each model.

## Model Comparison
The notebook includes a model comparison bar plot that displays the accuracy of each model on the test set. You can use this plot to compare the performance of different models.



## Limitations and Future Improvements
- The project focuses on analyzing top comments only. Further analysis can be done to include more comments and consider the sentiments of replies to comments.
- Improving the data preprocessing steps can enhance the model's accuracy and performance.
- Exploring other machine learning models and fine-tuning hyperparameters could lead to better results.

## Contributions
Contributions to this project are welcome! Feel free to submit pull requests or open issues to suggest improvements or report any bugs.
