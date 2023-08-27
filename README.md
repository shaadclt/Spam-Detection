# Spam Detection 

## Overview
This project is a simple spam classifier that uses the Multinomial Naive Bayes algorithm to classify messages as either spam or not spam (ham). It also provides some data visualizations and metrics to evaluate the classifier's performance.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Data](#data)
- [Model](#model)
- [Evaluation](#evaluation)
- [Visualizations](#visualizations)
- [Examples](#examples)
- [Contributing](#contributing)
- [License](#license)

## Installation
1. Clone this repository:
   ```
   git clone https://github.com/shaadclt/Spam-Detection.git
   ```

2. Install the required Python packages:
   ```
   pip install numpy pandas seaborn matplotlib scikit-learn wordcloud
   ```

3. Download the spam dataset (e.g., `spam.csv`) and place it in the project directory.

## Usage
1. Open a terminal and navigate to the project directory.

2. Open the spam detection notebook in Jupyter Notebook:
   ```
    spam_detection.ipynb
   ```

## Data
The dataset used for this project is in the CSV format (`spam.csv`). It contains two columns: `labels` (ham or spam) and `data` (message content). The data was preprocessed to remove unnecessary columns.

## Model
The spam classifier uses the Multinomial Naive Bayes algorithm for text classification. It utilizes the `CountVectorizer` from scikit-learn to convert text data into numerical features for model training and prediction.

## Evaluation
- **Accuracy**: The model's accuracy on both the training and testing datasets.
- **F1 Score**: The F1 score on both the training and testing datasets.
- **AUC (Area Under the ROC Curve)**: The AUC score on both the training and testing datasets.
- **Confusion Matrix**: Visual representation of the model's performance.

## Visualizations
- **Histogram of Labels**: A histogram showing the distribution of spam and ham labels in the dataset.
- **Word Clouds**: Word clouds generated from the most common words in spam and ham messages.

## Examples
- The classifier correctly identifies spam messages.
- The classifier fails to identify spam messages (false negatives).
- The classifier incorrectly classifies non-spam messages as spam (false positives).

## Contributing
Contributions are welcome! If you'd like to contribute to this project, please open an issue or submit a pull request.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
