# Sentiment-Analysis-of-Tweets-Predicting-and-Visualizing-Public-Opinion
This is a project which focuses on analyzing the sentiment of tweets to gain insights into public opinion.

# Sentiment Analysis of Tweets: Predicting and Visualizing Public Opinion

Welcome to the "Sentiment Analysis of Tweets: Predicting and Visualizing Public Opinion" project repository!

## Overview
This project focuses on analyzing the sentiment of tweets to gain insights into public opinion. It leverages machine learning techniques and state-of-the-art natural language processing (NLP) models to classify tweets into positive, negative, or neutral sentiments. The sentiment analysis is performed using the "ProsusAI/finbert" model, which is fine-tuned specifically for financial sentiment analysis.

## Features
- Perform sentiment analysis on tweet data using the "ProsusAI/finbert" model.
- Utilize GPU optimization for faster processing of large-scale tweet datasets.
- Preprocess tweet data and extract relevant features.
- Visualize sentiment trends over time using scatter plots, line plots, and bar charts.
- Compare predicted sentiments with actual labels to measure model accuracy.

## Installation
1. Clone the repository:
git clone https://github.com/RaghavSrivastava25/sentiment-analysis-tweets.git
cd sentiment-analysis-tweets


2. Set up the Python environment:
- Create a virtual environment (recommended):
  ```
  python -m venv env
  source env/bin/activate   # For Linux/Mac
  .\env\Scripts\activate    # For Windows
  ```
- Install the required dependencies:
  ```
  pip install -r requirements.txt
  ```

## Usage
1. Prepare your tweet dataset in a CSV format with columns: 'tweet_text', 'tweet_date', 'tweet_for'.

2. Perform sentiment analysis on the tweets and store the results in a new column 'sentiment':

3. Visualize the sentiment trends over time:

4. Explore the Jupyter notebooks in the `notebooks` directory for detailed examples and advanced analysis techniques.

## Contributing
Contributions are welcome! If you find any issues or have ideas for improvements, please open an issue or submit a pull request.

## License
This project is licensed under the [MIT License](LICENSE).

## Credits
- The "ProsusAI/finbert" model: [Link to the model repository](https://github.com/ProsusAI/finbert)
- Twitter logo: [Link to source](https://www.freepik.com)

## Contact
For any questions or inquiries, please contact [mr.tachyon25@gmail.com](mailto:mr.tachyon25@gmail.com).


