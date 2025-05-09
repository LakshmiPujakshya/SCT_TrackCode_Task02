# 🧠 Titanic Dataset - Exploratory Data Analysis (EDA)

This project performs a detailed **Exploratory Data Analysis (EDA)** on the famous **Titanic dataset** from Kaggle. The goal is to understand the data, identify patterns and correlations, and draw insights that can inform predictive modeling.

## 📁 Dataset

The dataset contains passenger information such as name, age, sex, ticket fare, class, and whether they survived the Titanic disaster.

- Source: [Kaggle - Titanic: Machine Learning from Disaster](https://www.kaggle.com/c/titanic/data)

## 📊 Objectives

- Understand the structure and distribution of the dataset.
- Handle missing values and clean the data.
- Visualize key relationships (e.g., survival rate vs sex, age, class).
- Derive insights to guide future model building.

## 📌 Key EDA Highlights

- Distribution of numerical and categorical features.
- Correlation heatmap to identify relationships.
- Survival analysis based on:
  - Gender
  - Passenger class
  - Age groups
  - Family size
  - Embarkation point
- Missing value handling using pandas.

## 🛠️ Tools Used

- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## 📁 File Structure

📦 Titanic-EDA
┣ 📄 README.md
┣ 📄 titanic_eda.ipynb
┗ 📁 data
┗ 📄 train.csv

markdown
Copy
Edit

## 📷 Sample Visualizations

- Countplots for survival distribution by gender and class
- Boxplots and histograms for age distribution
- Heatmap showing feature correlations

## ✅ How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/titanic-eda.git
   cd titanic-eda
Install the requirements:

bash
Copy
Edit
pip install -r requirements.txt
Launch the notebook:

bash
Copy
Edit
jupyter notebook titanic_eda.ipynb
📌 Conclusion
This EDA provides a strong foundation for feature engineering and model building. Key insights show gender and passenger class are strong indicators of survival on the Titanic.

