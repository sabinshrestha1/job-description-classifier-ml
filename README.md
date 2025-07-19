# AI-Powered Job Description Classifier

## 🧠 Objective
To develop a machine learning model that classifies job descriptions into predefined job categories such as IT, Marketing, Finance, etc.

## 📌 Problem Statement
Job portals and HR software receive thousands of job descriptions that need to be categorized for search and filtering. Manual classification is time-consuming and error-prone. This project aims to automate the classification process using NLP and supervised machine learning.

## 📂 Dataset
- Source: [Kaggle - US Jobs on Monster.com](https://www.kaggle.com/datasets/PromptCloudHQ/us-jobs-on-monstercom)
- Fields Used: `job_title`, `job_description`
- Custom label: `job_category` (derived from job_title)

## ⚙️ Tools & Tech
- Python, Pandas, Numpy
- Scikit-learn
- Google Colab
- Matplotlib / Seaborn for visualization
- (Later: Streamlit for deployment)

## 📈 Expected Outcome
- A trained classifier that can accurately predict the category of a given job description.
- An end-to-end pipeline with data cleaning, feature extraction, training, and evaluation.

## 📁 Directory Structure
job-classifier/
├── data/
├── notebooks/
├── src/
├── outputs/
└── README.md
