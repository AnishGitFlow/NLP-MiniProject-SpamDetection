**Spam Detection using TensorFlow in Python** project:

# 📧 Spam Detection using TensorFlow in Python

This repository demonstrates a machine learning solution for detecting spam messages using **TensorFlow** and **Natural Language Processing (NLP)**. The model classifies text messages as **spam** or **ham (not spam)** by learning patterns in labeled text data.

## 📂 Project Structure

- `Spam_Detection_using_TensorFlow_in_Python.ipynb`: Jupyter Notebook containing the full implementation.
- `README.md`: Project overview and setup instructions.

## 🚀 Features

- Text preprocessing (tokenization, padding)
- Deep learning model built with TensorFlow/Keras
- Binary classification (spam vs. ham)
- Model evaluation using accuracy and loss metrics

## 📊 Dataset

The project uses a publicly available SMS Spam Collection dataset. This dataset contains a set of SMS labeled messages that have been collected for mobile phone spam research.

- Classes: `spam`, `ham`
- Format: CSV (two columns - label and message)

> Dataset Source: [UCI Machine Learning Repository – SMS Spam Collection](https://github.com/AnishGitFlow/NLP-MiniProject-SpamDetection/blob/main/emails.csv)

## 🛠️ Tech Stack

- Python 3.x
- TensorFlow 2.x
- Keras
- NumPy
- Pandas
- scikit-learn
- Matplotlib (optional for visualization)

## 🧪 Model Workflow

1. **Data Cleaning & Label Encoding**
2. **Tokenization & Padding of SMS text**
3. **Model Architecture**: Embedding → LSTM/Dense layers → Sigmoid output
4. **Training & Validation**
5. **Evaluation & Accuracy Reporting**

## 📈 Results

The model achieves high accuracy in distinguishing spam from ham messages after training, demonstrating the effectiveness of deep learning for text classification.

## 💡 Future Improvements

- Incorporate attention mechanism for improved context understanding
- Use pre-trained word embeddings like GloVe or Word2Vec
- Deploy the model using Flask or FastAPI

## 📌 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/AnishGitFlow/spam-detection-tensorflow.git
   cd spam-detection-tensorflow
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Launch the notebook:
   ```bash
   jupyter notebook Spam_Detection_using_TensorFlow_in_Python.ipynb
   ```

## 📜 License

This project is licensed under the MIT License.
