# Stress Detection with Machine Learning

## Overview
This project focuses on detecting stress levels from social media posts using Machine Learning. It involves processing text data, cleaning it, and building a binary classification model to predict whether a user is stressed or not based on their text input.

---

## Features
- **Text Data Cleaning**: Removes unnecessary elements like links, punctuation, and stopwords.
- **Word Cloud Visualization**: Highlights the most common words used in posts.
- **Binary Classification Model**: Predicts stress levels using the Bernoulli Naive Bayes algorithm.
- **Custom Input Testing**: Allows users to test the model with their own text.

---

## Dataset
The dataset contains labeled data from subreddit posts related to mental health. It includes:
- `text`: The content of the post.
- `label`: Indicates stress (1) or no stress (0).

### Dataset Source
The dataset used in this project is publicly available on Kaggle.

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/stress-detection.git
   cd stress-detection
   ```
2. Install the required libraries:
```bash
pip install -r requirements.txt
```
3. Download the dataset and place it in the root folder as stress.csv.

---

## Usage

### Running the Project
1. Open the `stress_detection.py` file in your IDE or terminal.
2. Run the script:
   ```bash
   python stress_detection.py
   ```
3. To test the model, enter custom text when prompted.

---

## Project Workflow

### 1. Data Preprocessing
- Checks for missing values.
- Cleans text data by removing stopwords, links, and special characters.

### 2. Visualization
- Generates a word cloud to visualize the most frequently used words.

### 3. Model Training
- Uses `CountVectorizer` to convert text into numerical data.
- Trains a Bernoulli Naive Bayes classifier for binary classification.

### 4. Model Testing
- Allows users to input custom sentences for prediction.

---

## Results

- **Stress Detection Accuracy**: The model performs well on the test data and provides accurate predictions for stress and no-stress cases.

### Examples:
- **Input**: "Sometimes I feel overwhelmed with everything."  
  **Output**: `Stress`
- **Input**: "I feel happy and content today!"  
  **Output**: `No Stress`

---

## Dependencies

- Python 3.7+
- Pandas
- NumPy
- NLTK
- Matplotlib
- WordCloud
- Scikit-learn

---

## Contributing

Contributions are welcome! Feel free to submit a pull request or open an issue to suggest improvements or fixes.

---

## License

This project is licensed under the [MIT License](LICENSE).




