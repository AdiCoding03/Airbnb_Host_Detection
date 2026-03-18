# Airbnb_Host_Detection
This application helps identify whether an Airbnb host is **New or Experienced** by analyzing listing, host, and location data using a machine learning–based classification approach.   It enables **better onboarding, pricing strategy, and risk assessment** for short-term rental platforms.

# Project Title
AIRBNB HOST EXPERIENCE PREDICTION

# Problem Statement
To identify and classify Airbnb hosts as new or experienced using host and listing attributes to better understand host behavior on the platform.

# Dataset
Source: Maven Analytics – Airbnb Listings & Reviews
Size: 279,712 rows × 33 columns

# Tech Stack
Python
Pandas, NumPy
Scikit-learn
Matplotlib
Seaborn
Streamlit

# ML Models Used
Decision Tree Classifier
Decision Tree Classifier (Tuned)
Random Forest Classifier
Random Forest Classifier (Tuned)
AdaBoost Classifier
XGBoost Classifier (Tuned)
KNN Classifier

# Evaluation Metrics & Model Performance
Built and compared 10+ machine learning models
XGBoost emerged as the best-performing model
Achieved ~80% test accuracy and ~0.88 ROC-AUC
Accuracy: 0.797
F1-Score: 0.816 (best balance between precision and recall)
Recall: 0.835 (high effectiveness in identifying New Hosts, critical for the business use case)
Tree boosting and built-in regularization captured complex non-linear patterns while reducing overfitting
Outperformed all single models and tuned ensemble variants
Final model deployed via a Streamlit app for real-time host experience prediction

# Key Insights
Fast and consistent host responses significantly improve performance, as response rate and response time are strong indicators of host experience and success.
Location plays a major role in demand, with listings in popular cities and neighborhoods receiving higher booking activity.
Higher acceptance rates and complete identity verification help build guest trust and positively influence host performance.
Maintaining a well-optimized host profile and aiming for Superhost-level quality increases credibility, bookings, and long-term success.

# App Link
https://detecthostlifecycle-5nppdndcczdbyqyggkkdem.streamlit.app/

### Source Link
https://mavenanalytics.io/data-playground/airbnb-listings-reviews
