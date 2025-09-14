🧠 Machine Learning Projects

This repository contains two Jupyter Notebooks showcasing machine learning algorithms and techniques for classification and decision trees. Each notebook demonstrates data preprocessing, model training, evaluation, and visualization.

📂 Project Structure
.
├── Amani_Taheri_Q1Q2.ipynb   # Classification models (Naive Bayes, KNN, PCA, Text vectorization)
├── Sales_DT.ipynb            # Decision Tree classifier with entropy & information gain
├── README.md                 # Project documentation

📘 Notebooks Overview
🔹 1. Amani_Taheri_Q1Q2.ipynb

Focus: Text and numerical data classification

Preprocessing with scaling (StandardScaler, MinMaxScaler)

Feature engineering: PCA for dimensionality reduction

Text vectorization: Bag-of-Words & TF-IDF

Models:

Naive Bayes (GaussianNB, MultinomialNB)

K-Nearest Neighbors (KNN)

Evaluation metrics:

Accuracy

Confusion Matrix & Classification Report

Precision, Recall, F1

🔹 2. Sales_DT.ipynb

Focus: Decision Trees for classification

Dataset loading (via gdown)

Custom functions:

calculate_entropy

info_gain

Modeling:

Decision Tree Classifier (sklearn)

Hyperparameter tuning with GridSearchCV

Visualization:

Decision tree plots (plot_tree)

Confusion Matrix display

🛠️ Installation

Clone the repository and install dependencies:

git clone https://github.com/yourusername/your-repo-name.git
cd your-repo-name
pip install -r requirements.txt

Requirements

Python 3.8+

NumPy

Pandas

Matplotlib

Seaborn

Scikit-learn

gdown

Install them with:

pip install numpy pandas matplotlib seaborn scikit-learn gdown

📖 Usage

Open a notebook in Jupyter:

jupyter notebook Amani_Taheri_Q1Q2.ipynb


or

jupyter notebook Sales_DT.ipynb

📊 Example Outputs

PCA-transformed datasets

Confusion matrices with performance metrics

Decision tree visualizations

Accuracy and classification reports

📝 License

This project is licensed under the MIT License. Feel free to use, modify, and share.
