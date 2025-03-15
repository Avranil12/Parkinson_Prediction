# Parkinson_Prediction
A machine learning model that analyzes vocal patterns to detect Parkinson's disease. By studying voice features like pitch, tone, and variation, the model identifies early signs of the disease. This technology could help doctors diagnose Parkinson’s faster and more accurately, leading to earlier treatment and better patient outcomes.

# Input: A dataset containing various biomedical voice measurements from 31 individuals, 23 of whom have Parkinson's disease (PD). Each row represents one of 195 voice recordings, with each column corresponding to a specific vocal feature (excluding the "name" column).

# Model: A trained machine learning model (best_model.pkl) used for prediction.

# Normalization: Voice features are standardized using a pre-trained normalizer (normalizer.pkl).

# Output: The model predicts whether an individual is Healthy or has Parkinson's Disease based on their voice characteristics.
