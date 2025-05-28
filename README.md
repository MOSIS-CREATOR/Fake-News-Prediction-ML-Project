# Fake-News-Prediction-ML-Project
Fake news prediction using text analysis and machine learning. It processes news data, applies stemming and TF-IDF vectorization, and trains a Logistic Regression model to classify news as real or fake.

## Project Overview

The notebook contains:

1. Import libraries for data processing (numpy, pandas), text processing (nltk, sklearn.feature_extraction.text).

2. Data Preprocessing: Loading and cleaning a dataset of news articles, handling missing values, and combining author and title into a single feature (content).

3. Text Processing: Applying stemming to reduce words to their root form and using TF-IDF vectorization to convert text data into numerical features.

4. Model Training: Training a Logistic Regression model to classify news articles as real (0) or fake (1).

5. Evaluation: Assessing model performance using accuracy scores on training and test datasets.

6. Prediction System: Implementing a predictive system to classify new articles as real or fake based on the trained model.


## Dataset

Dataset is included in Data/fake_news.csv


## Technologies Used

- Python: Core programming language.
- Pandas: For data manipulation and analysis.
- NumPy: For numerical operations.
- NLTK: For text processing, including stopwords and Porter Stemming.
- Scikit-learn: For TF-IDF vectorization, train-test split, Logistic Regression, and accuracy evaluation.
- Regular Expressions (re): For text cleaning.

## ML Models Used

- Logistic Regression: A binary classification model used to predict whether a news article is real (0) or fake (1).

## Results

- Training Data Accuracy: 97.19%
- Test Data Accuracy: 95.50%
- The model successfully classifies news articles with high accuracy, as demonstrated by evaluating a sample from the test set (e.g., correctly predicting a real news article at index 3).                        |


## How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/MOSIS-CREATOR/Fake-News-Prediction-ML-Project
   ```
2. Navigate to the project directory:
   ```bash
   cd Fake-News-Prediction-ML-Project
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Open the notebook:
   ```bash
   jupyter notebook Fake_News_Prediction.ipynb
   ```

## License

This project is licensed under the GNU General Public License v3.0.