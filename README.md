# 🚀 CognoRise InfoTech Data Science Internship 🚀

Welcome to my GitHub repository for the **CognoRise InfoTech Data Science Internship**! Here, I'll be documenting my journey and progress through various tasks aimed at enhancing my skills in data science.

---

## 📅 Overview 📅

This internship program spans 30 days, from **March 20, 2024**, to **April 20, 2024**. Throughout this period, I'll be engaging in hands-on tasks designed to deepen my understanding of key concepts in data science and machine learning.

---

Before using the project, ensure you have the necessary API credentials from Kaggle to download datasets. Follow these steps to set up your Kaggle API credentials:

- Place your `kaggle.json` file in the `~/.config/kaggle/` directory (Linux/Mac) or `C:\Users\<YourUsername>\.kaggle\` (Windows). Refer to [Kaggle API documentation](https://www.kaggle.com/docs/api) for more details.

## 🎯 Tasks I will be involved in 🎯

Note: each notebook takes approximately 10 minutes to run completely, depending on your machine's performance.

- **Task 2: Credit Card Fraud Detection** 🕵️‍♂️
  
  In this task, I'll develop a machine learning model to detect fraudulent credit card transactions. This involves preprocessing and normalizing transaction data, handling class imbalance, training classification algorithms, and evaluating the model's performance using metrics such as precision, recall, and F1-score. The notebook for this task can be found at [task2_transactions-fraud-detection/credit-card-fraud-detection.ipynb](notebooks/task2_transactions-fraud-detection/credit-card-fraud-detection.ipynb).

- **Task 7: Shopper Sentiments** 🛍️
  
  Task 7 involves analyzing the ShopperSentiments dataset, which contains over 250,000 customer reviews on TeePublic. Using this data, I'll explore sentiment analysis, geospatial patterns, temporal trends, and review categorization to gain insights into customer preferences in online fashion retail. The notebook for this task can be found at [task7_shopper-sentiments/shopper-sentiments.ipynb](notebooks/task7_shopper-sentiments/shopper-sentiments.ipynb).

- **Task 8: Fake News Prediction** 📰
  
  In Task 8, I'll work with the Fake News Prediction Dataset to build predictive models capable of identifying fake news articles. By analyzing features such as title and text, I aim to contribute to efforts in combating misinformation and promoting media literacy. The notebook for this task can be found at [task8_fake-news-prediction/fake-news-prediction.ipynb](notebooks/task8_fake-news-prediction/fake-news-prediction.ipynb).

---

## 📁 Repository Structure 📁

- `data/`: This directory contains all the datasets used in the tasks. The raw data can be found in the `raw/` subdirectory. Due to size constraints, the raw data is not displayed in this repository, but the code is automated to save the data in this folder.
- `models/`: This directory is for storing trained machine learning models. Due to size constraints, the models are not saved in this repository, but the code is automated to save the models in this folder.
- `notebooks/`: This directory contains Jupyter notebooks for each task.
- `reports/`: This directory contains reports generated from the tasks, these are data profiling reports and task reports made using ydata_profiling Python library.
- `requirements.txt`: This file lists the Python dependencies required to run the notebooks.

---

## 🚀 Getting Started 🚀

To get started with the project, clone the repository and install the required dependencies:

```bash
git clone https://github.com/estivengrx/CognoRise_Infotech
cd CognoRise_Infotech
pip install -r requirements.txt
```

Then, navigate to the `notebooks/` directory and launch Jupyter Notebook:

```bash
cd notebooks
jupyter notebook
```

You can now open the notebook for each task and start exploring my work!