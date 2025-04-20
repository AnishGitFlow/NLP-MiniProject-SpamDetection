# Spam Email Detection Using TensorFlow

This project demonstrates how to detect spam emails using a deep learning model built with TensorFlow and Keras in Python.

## Overview

Spam emails are unsolicited messages sent in bulk. Automatically detecting them helps in filtering unnecessary content from users' inboxes. This project walks through the steps of creating a machine learning pipeline to classify emails as **Spam** or **Ham (Not Spam)**.

## Steps Involved

### 1. Import Required Libraries
Essential Python libraries like TensorFlow, Pandas, NumPy, NLTK, Seaborn, and WordCloud are used for data processing, visualization, and model building.

### 2. Load and Explore Dataset
- Dataset: `Emails.csv`
- Total entries: 5171
- Initial exploration and label distribution visualized using Seaborn.

### 3. Balance the Dataset
- The dataset is imbalanced with more Ham emails.
- Ham emails are downsampled to match Spam email count for a balanced dataset.

### 4. Text Cleaning
- Removal of punctuation and stopwords.
- Text is preprocessed for input into the neural network.

### 5. Visualization
- Word clouds are generated for Ham and Spam emails to visualize frequently occurring terms.

### 6. Tokenization and Padding
- Tokenization converts text to sequences.
- Padding ensures uniform input length for the model.

### 7. Model Definition
- A Sequential LSTM model with embedding, LSTM, and dense layers is used.
- Final output layer uses sigmoid activation for binary classification.

### 8. Training the Model
- The model is trained with callbacks for EarlyStopping and ReduceLROnPlateau.
- Validation data used to monitor overfitting.

### 9. Evaluation and Accuracy
- The model achieves about 97% accuracy on the test set.
- Accuracy trends are visualized using Matplotlib.

## Dependencies

- Python 3.x
- TensorFlow
- Keras
- Pandas
- NumPy
- Seaborn
- Matplotlib
- WordCloud
- NLTK

Install dependencies using pip:

```bash
pip install tensorflow pandas numpy seaborn matplotlib wordcloud nltk
```

## Dataset

You can download the dataset from: [Emails.csv](https://www.kaggle.com/datasets/balaka18/email-spam-classification-dataset-csv)

## Results

- **Test Accuracy**: ~97%
- Visualization of training and validation accuracy shows good learning trends.

## License

This project is licensed under the MIT License.

## Author

Developed as a part of a hands-on project using deep learning with TensorFlow.
