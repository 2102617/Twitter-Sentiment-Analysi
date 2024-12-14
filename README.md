# Twitter Sentiment Analysis

This project performs sentiment analysis on a dataset of tweets to classify them into categories like Positive, Negative, Neutral, and Irrelevant. It uses natural language processing techniques and machine learning to analyze and extract insights from public opinions on social media platforms like Twitter.

## Features

- **Sentiment Classification:** Classify tweets into sentiment categories: Positive, Negative, Neutral, and Irrelevant.
- **Data Visualization:** Visualize sentiment distribution across trends using bar charts, pie charts, and stacked bar charts.
- **Machine Learning Model:** A logistic regression model for sentiment classification.
- **Performance Metrics:** Evaluate the model using accuracy, precision, recall, and F1-score.

## Requirements

To run the project, you need:

- Python 3.x
- Libraries:
  - pandas
  - numpy
  - sklearn
  - matplotlib
  - seaborn

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/TwitterSentimentAnalysis.git
    ```
2. Navigate to the project directory:
    ```bash
    cd TwitterSentimentAnalysis
    ```
3. Install the required libraries:
    ```bash
    pip install -r requirements.txt
    ```

## Dataset

The dataset contains 73,996 cleaned tweets with the following features:

- **UserID:** Unique identifier for each user.
- **Trend:** Topic associated with the tweet.
- **Sentiment:** Label assigned to the tweet (Positive, Negative, Neutral, or Irrelevant).
- **Text:** The content of the tweet.

## Process Overview

1. **Data Collection:** 74,682 tweets were initially collected and cleaned to remove duplicates and missing values.
2. **Data Preprocessing:** The text data was transformed into numerical vectors using TF-IDF.
3. **Model Building:** A logistic regression model was trained on the preprocessed data.
4. **Evaluation:** The model's performance was evaluated using a classification report and accuracy metrics.

## Results

- **Accuracy:** 77.95%
- **Precision, Recall, F1-Score:** Detailed classification report:

  | Sentiment   | Precision | Recall | F1-Score |
  |-------------|-----------|--------|----------|
  | Irrelevant  | 0.81      | 0.67   | 0.73     |
  | Negative    | 0.78      | 0.86   | 0.82     |
  | Neutral     | 0.78      | 0.75   | 0.76     |
  | Positive    | 0.76      | 0.79   | 0.78     |

## Usage

1. Run the script for data preprocessing and model training:
    ```bash
    python preprocess_and_train.py
    ```
2. Visualize the results using the visualization scripts:
    ```bash
    python visualize_data.py
    ```

## Applications

- Marketing: Analyze public opinions on products or campaigns.
- Customer Service: Understand customer feedback.
- Social Research: Gauge public sentiment on trending topics.

## Contribution

Contributions are welcome! Feel free to fork the repository, make improvements, and submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

## Contact

For inquiries, reach out to the project authors:

- **Harshil Amin**

