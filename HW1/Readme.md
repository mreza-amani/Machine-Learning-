📊 Machine Learning Regression Models

This repository contains a Jupyter Notebook implementation of machine learning techniques for regression analysis. It covers dataset preprocessing, feature engineering with sliding windows and polynomial transformations, and training multiple regression models including Linear Regression, Ridge, and ElasticNet.

🚀 Features

Data preprocessing with pandas and scaling via MinMaxScaler

Time-series feature extraction using a sliding window function

Polynomial feature generation for non-linear regression

Implementation of custom regression models with:

fit and predict methods

Mean Squared Error (MSE) evaluation

Training history visualization (plot_mse_history)

Benchmarking against scikit-learn regression models

Visualizations with matplotlib

📂 Project Structure
.
├── Amani_Taheri_MP1_Q1.ipynb   # Main Jupyter Notebook
├── README.md                   # Project documentation

🛠️ Installation

Clone this repository and install dependencies:

git clone https://github.com/yourusername/your-repo-name.git
cd your-repo-name
pip install -r requirements.txt

Requirements

Python 3.8+

NumPy

Pandas

Matplotlib

Scikit-learn

tqdm

You can install them with:

pip install numpy pandas matplotlib scikit-learn tqdm

📖 Usage

Open the notebook in Jupyter:

jupyter notebook Amani_Taheri_MP1_Q1.ipynb


Run the cells step by step to:

Load and preprocess the dataset

Generate features using sliding windows / polynomial transformation

Train regression models

Evaluate performance with Mean Squared Error

Visualize results

📊 Example Output

Sliding window processed dataset

Regression model predictions vs. ground truth

Training loss (MSE) plots

Comparison of models (Linear Regression, Ridge, ElasticNet)

📝 License

This project is licensed under the MIT License. Feel free to use and modify for your own work.
