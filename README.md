🧠 Machine Learning & Data Analysis – Notebook Collection

This repository is a collection of Jupyter Notebooks showcasing machine learning algorithms, data preprocessing, and model evaluation across multiple domains.
It combines both practical projects (real datasets, regression/classification, decision trees, air pollution analysis) and theoretical implementations (perceptron, McCulloch-Pitts neurons).

The goal of this repo is to serve as a learning hub covering regression, classification, decision trees, perceptrons, and exploratory data analysis.

📘 Notebooks Overview
🔹 Regression Models (Amani_Taheri_MP1_Q1.ipynb)

Focus: Regression analysis with feature engineering.

Techniques:

Sliding windows for time-series

Polynomial feature generation

Custom regression models (fit/predict, MSE)

Benchmarking against Linear Regression, Ridge, ElasticNet (scikit-learn)

Visualization of training history & predictions

🔹 Classification Models (Amani_Taheri_Q1Q2.ipynb)

Focus: Text and numerical data classification.

Techniques:

Feature scaling (StandardScaler, MinMaxScaler)

PCA for dimensionality reduction

Bag-of-Words & TF-IDF text vectorization

Models: Naive Bayes (Gaussian, Multinomial), KNN

Metrics: Accuracy, Confusion Matrix, Precision, Recall, F1

🔹 Decision Trees (Sales_DT.ipynb)

Focus: Entropy & Information Gain for decision trees.

Features:

Custom calculate_entropy and info_gain functions

Sklearn DecisionTreeClassifier with GridSearchCV

Tree visualization and confusion matrix reporting

🔹 Air Pollution Data Analysis (MP3_AmaniTaheri.ipynb)

Focus: Exploratory Data Analysis (EDA) on Beijing PM2.5 dataset.

Tasks:

Data preprocessing and missing value detection

Descriptive statistics & correlation heatmaps

Visualizations of environmental features vs. PM2.5

🔹 Perceptron & Neural Models (5ef00ad2-2866-40f4-b5de-1800196dd903.ipynb)

Focus: Foundational neural network models from scratch.

Tasks:

Manual perceptron decision boundary

Binary classification with perceptron

Triangle region classification using McCulloch-Pitts neurons

📂 Project Structure
.
├── Amani_Taheri_MP1_Q1.ipynb               # Regression models
├── Amani_Taheri_Q1Q2.ipynb                 # Classification models
├── Sales_DT.ipynb                          # Decision Tree classifier
├── MP3_AmaniTaheri.ipynb                   # Air Pollution EDA
├── 5ef00ad2-2866-40f4-b5de-1800196dd903.ipynb   # Perceptron & McCulloch-Pitts
├── README.md                               # General documentation

🛠️ Installation

Clone the repo and install dependencies:

git clone https://github.com/your-username/ml-notebook-collection.git
cd ml-notebook-collection
pip install -r requirements.txt

Requirements

Python 3.8+

NumPy

Pandas

Matplotlib

Seaborn

Scikit-learn

tqdm

gdown (for Sales_DT notebook)

pip install numpy pandas matplotlib seaborn scikit-learn tqdm gdown

📖 Usage

Open any notebook in Jupyter:

jupyter notebook notebook_name.ipynb


For example:

jupyter notebook Amani_Taheri_MP1_Q1.ipynb


Run the cells step by step to explore data preprocessing, model training, evaluation, and visualization.

📊 Example Outputs

Regression model predictions vs. ground truth

PCA-transformed datasets

Confusion matrices and classification reports

Decision tree visualizations

PM2.5 correlation heatmaps and pollution trends

Perceptron decision boundaries

📜 License

This repository is for educational purposes under the MIT License.
You are welcome to use, modify, and share for your own learning.
