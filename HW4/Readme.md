# Machine Learning & Data Analysis Projects

This repository contains two Jupyter notebooks that demonstrate different aspects of **machine learning** and **data analysis**.  
The projects showcase both **practical data exploration** on real-world datasets and **theoretical implementations** of classic neural models.

---

## 📌 Notebooks Included

### 1. Air Pollution Data Analysis (`MP3_AmaniTaheri.ipynb`)
- **Focus:** Exploratory Data Analysis (EDA) on Beijing air quality dataset.  
- **Key Tasks:**
  - Load and preprocess the **PRSA dataset** (`PRSA_data_2010.1.1-2014.12.31.csv`).  
  - Perform **descriptive statistics, correlation analysis, and missing value detection**.  
  - Visualize environmental variables and their impact on **PM2.5 pollution**.  

---

### 2. Perceptron & Neural Models (`5ef00ad2-2866-40f4-b5de-1800196dd903.ipynb`)
- **Focus:** Foundational neural network models implemented from scratch.  
- **Key Tasks:**
  - Implement a **manual perceptron decision boundary**.  
  - Perform **binary classification using a simple perceptron**.  
  - Explore **triangle region classification with McCulloch-Pitts neurons**.  

---

## 📂 Dataset

For the **Air Pollution notebook**:

- **File:** `PRSA_data_2010.1.1-2014.12.31.csv`  
- **Description:** Hourly PM2.5 and meteorological data from Beijing (2010–2014).  
- **Source:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Beijing+PM2.5+Data)

The **Perceptron notebook** does not require external datasets (uses synthetic data).

---

## 🛠️ Requirements

Both notebooks require Python 3.8+ and the following libraries:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn

🚀 How to Run

Clone this repository:

git clone https://github.com/your-username/MachineLearning-Projects.git
cd MachineLearning-Projects


For the Air Pollution notebook, place the dataset file in the same directory:

PRSA_data_2010.1.1-2014.12.31.csv


Launch Jupyter Notebook:

jupyter notebook


Open and run either:

MP3_AmaniTaheri.ipynb (Air Pollution Analysis)

5ef00ad2-2866-40f4-b5de-1800196dd903.ipynb (Perceptron & Neural Models)

📊 Contents Overview

Air Pollution Analysis Notebook

Data preprocessing

Summary statistics

Correlation heatmaps

Visualizations of pollution trends

Perceptron & Neural Models Notebook

Manual perceptron boundary calculation

Simple perceptron classification

McCulloch-Pitts neuron examples

📜 License

This repository is for educational purposes.
Feel free to fork and adapt it for your own learning.


---

👉 Do you want me to merge both notebooks under **one project theme** (like *"ML Coursework"*) or keep the
