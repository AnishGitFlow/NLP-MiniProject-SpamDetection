# NLP-MiniProject-SpamDetection

## Overview
This project focuses on building a spam detection system using Natural Language Processing (NLP) techniques. The goal is to classify SMS messages as either "ham" (legitimate) or "spam" based on their content. The project follows a structured pipeline from data cleaning and exploratory data analysis (EDA) to model building and evaluation.

## Features
- **Data Cleaning**: Handling missing values, removing duplicates, and renaming columns for clarity.
- **Exploratory Data Analysis (EDA)**: Visualizing the distribution of spam and ham messages, and analyzing text characteristics like word count and sentence length.
- **Text Preprocessing**: Utilizing NLTK for tokenization and other text processing steps.
- **Model Building**: Implementing machine learning models to classify messages.
- **Evaluation**: Assessing model performance using appropriate metrics.

## Dataset
The dataset used is `spam.csv`, which contains SMS messages labeled as "ham" or "spam". The dataset has the following columns:
- `target`: Label indicating whether the message is ham (0) or spam (1).
- `text`: The content of the SMS message.

## Dependencies
- Python 3.x
- Libraries:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - nltk
  - scikit-learn

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/AnishGitFlow/NLP-MiniProject-SpamDetection.git
   cd NLP-MiniProject-SpamDetection
   ```
2. Install the required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn nltk scikit-learn
   ```
3. Download NLTK data (if not already installed):
   ```python
   import nltk
   nltk.download('punkt')
   ```

## Usage
1. Ensure the dataset `spam.csv` is placed in the project directory.
2. Run the Jupyter notebook `sms-spam-detection.ipynb` to execute the project step-by-step.

## Project Structure
- `sms-spam-detection.ipynb`: Jupyter notebook containing the complete code and analysis.
- `spam.csv`: Dataset used for training and evaluation.
- `README.md`: This file, providing an overview of the project.

## Results
The project includes visualizations and metrics to evaluate the performance of the spam detection model. Key insights from EDA and model evaluation are documented in the notebook.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request for any improvements or bug fixes.

## License
This project is open-source and available under the MIT License.

## Contact
For any questions or feedback, please reach out to me.
