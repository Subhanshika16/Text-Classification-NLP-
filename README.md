
# 📧 Email Spam Detection with Machine Learning
# 📌 Project Overview
Spam emails—often containing fraudulent schemes, phishing attempts, or irrelevant advertising—are a significant nuisance in our inboxes. This project aims to create a machine learning-based email spam detection system that can classify incoming emails as spam or ham (legitimate).
By leveraging Python along with libraries like scikit-learn, NLTK, Matplotlib, and Seaborn, we train a model to automatically detect and filter unwanted messages, helping keep inboxes safe and organized.

# 🎯 Goal of the Project
Build a system that can classify emails as spam or ham with high accuracy.Apply a standard data science workflow:
Data acquisition
Preprocessing
Feature extraction
Model training
Model evaluation
Predictions & visualizations

# ⚙️ How the Project Was Developed
1. Data Acquisition
Used the Spam CSV Dataset from Jayanti Bhanushali's GitHub repository.
2. Data Preprocessing
Removed unnecessary columns.
Renamed dataset columns (v1 → Category, v2 → Message).
Encoded categories:
spam → 0
ham → 1
Checked for missing values and data types.
3. Data Visualization
Count plots for category distribution.
Pie charts for spam vs. ham percentage.
Word frequency analysis for most common spam words.
4. Feature Extraction
Used TF-IDF Vectorizer to convert email text into numerical features.
Removed English stopwords and applied lowercase transformation.
5. Model Selection & Training
Chose Logistic Regression for classification.
Trained the model on 80% training data and tested on 20% testing data.
6. Model Evaluation
Achieved 96.2% accuracy on test data.Created a confusion matrix for performance analysis.
7. Testing & Predictions
Tested with custom email messages to verify real-world functionality.

# 🌟 Important Features of the Project
Comprehensive Visualization Techniques
1.Count plots, pie charts, and bar graphs for spam analysis.
2.Heatmaps for confusion matrix visualization.
3.Customization Applied themes, colors, and labels for professional-quality plots.

Data Insight Demonstration
Top 7 most common words in spam emails.
Spam vs. ham distribution analysis.

Educational Value
Demonstrates how to use NLTK,TF-IDF, and Logistic Regression for NLP tasks.
Serves as a complete machine learning workflow example.

# 📊 Model Performance
Metric	Value
Accuracy (Training)	96.6%,
Accuracy (Testing)	96.2%,
Model	Logistic Regression

# 📂 Technologies Used
Python Pandas, NumPy (Data Handling),
NLTK (Text Preprocessing),
scikit-learn (Machine Learning),
Matplotlib, Seaborn (Data Visualization)
