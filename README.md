# SMS-classification-dl
Deep learning-based SMS spam detection using TensorFlow and NLP preprocessing


## Project Summary
- **Dataset:** `spam.csv` (expected in the repository root or uploaded to Colab)
- **Approach:** Text cleaning → Tokenization → Padding → Embedding → Bidirectional LSTM → Dense (binary classification)
- **Evaluation:** Accuracy, Confusion Matrix, Classification Report
  
## Features
- Text preprocessing (tokenization, padding)
- Embedding + Bidirectional LSTM classifier
- Evaluation using accuracy, confusion matrix, classification report
- Visualizations: wordclouds, class distributions, training history plots

## Files
- `SMSClassificationDeeplearning.ipynb` — main notebook (Colab-compatible)
- `README.md` — this file


## 🛠 Requirements
- Python 3.8+
- TensorFlow
- scikit-learn
- pandas, numpy, matplotlib

## 🚀 How to Run
1. Open the notebook `SMSClassificationDeeplearning.ipynb` in Google Colab.
2. Upload the dataset (if not linked).
3. Run all cells to train and test the model.

## 📊 Results
Achieved high accuracy for SMS spam detection using deep learning methods.

---
