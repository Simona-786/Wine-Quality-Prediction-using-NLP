#  Wine Quality Prediction using NLP

##  Overview
This project uses Natural Language Processing (NLP) to classify wine reviews as high-quality or normal based on textual descriptions.

##  Problem Statement
Predict whether a wine is high quality (points ≥ 90) using its review description.

##  Tech Stack
- Python
- TensorFlow
- TensorFlow Hub
- Pandas, NumPy
- Matplotlib

##  Approach
- Data cleaning and preprocessing
- Label creation (binary classification)
- Model 1: TensorFlow Hub embedding + Dense layers
- Model 2: LSTM-based deep learning model

##  Results
- Achieved ~84% accuracy using LSTM model

##  Future Improvements
- Add more features like price, country
- Try transformer-based models

##  Dataset
Wine Reviews Dataset (129k rows)
https://www.kaggle.com/datasets/zynicide/wine-reviews
