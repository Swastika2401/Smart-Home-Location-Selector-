# 🏠 Smart-Home-Location-Selector-

A Machine Learning–enabled, data-driven recommendation system that helps users identify the most suitable residential locations in major Indian metro cities based on budget, safety, accessibility, environment, and lifestyle preferences.

# 📌 Project Overview

Choosing a residential location in a metro city is a complex decision involving multiple factors such as price, safety, pollution, transportation access, and availability of essential services.
The Smart Home Location Selector simplifies this decision-making process by combining data preprocessing, exploratory data analysis, rule-based filtering, and machine learning to generate personalized location recommendations.

# 🎯 Objectives

Analyze residential location data across Indian metro cities

Preprocess and normalize multi-criteria features

Perform exploratory data analysis (EDA) to understand trends

Apply constraint-based filtering for user requirements

Use Machine Learning to predict a suitability score

Rank and recommend the best residential locations

# 🏙️ Supported Cities

Bengaluru

Mumbai

Delhi NCR

Hyderabad

Chennai

Pune

# 📊 Dataset Information

File: smart_home_location_dataset_20000.csv

Records: 20,000

Attributes: 23 features per location

Data Type: Clean, synthetic but realistic metro-city residential data

Key Feature Categories

Economic: price per sqft, monthly rent, maintenance cost

Safety & Environment: safety score, crime rate, pollution index, noise level

Accessibility: distance to metro, bus stop, hospital, school

Infrastructure: internet speed, road connectivity, power backup

Lifestyle: green space score, shopping mall distance

# 🛠️ Technologies Used

Python

Jupyter Notebook

Pandas & NumPy – Data handling

Matplotlib & Seaborn – Visualization (EDA)

Scikit-learn – Preprocessing & Machine Learning

# 🧠 Methodology

### 1️⃣ Data Loading & Inspection

Dataset loaded using Pandas

Initial inspection using shape, info(), and describe()

### 2️⃣ Data Preprocessing

Encoding categorical variables (binary & one-hot encoding)

Min–Max normalization of numerical features

Classification of features into positive and negative impact categories

### 3️⃣ Exploratory Data Analysis (EDA)

City-wise rent comparison

Safety vs pollution analysis

Transportation accessibility distribution

Infrastructure comparison across cities

### 4️⃣ Rule-Based Filtering

Budget constraints

Minimum safety threshold

Maximum pollution and distance limits

### 5️⃣ Machine Learning Integration

Creation of a synthetic suitability score

Training a Random Forest Regressor

Learning feature importance automatically

Predicting suitability scores for all locations

### 6️⃣ Recommendation Engine

Ranking locations based on predicted suitability score

Selecting top-N recommendations

Exporting results to CSV

# 🤖 Machine Learning Model

Model Used: Random Forest Regressor

Reason:

Handles non-linear relationships

Robust for tabular data

Easy to interpret and explain

Output: Predicted suitability score (0–1)

# 📁 Project Structure

Smart-Home-Location-Selector/
│
├── notebooks/
│   └── Smart_Home_Location_Selector.ipynb
│
├── data/
│   └── smart_home_location_dataset_20000.csv
│
├── outputs/
│   └── recommendations.csv
│
├── README.md
└── requirements.txt

# ▶️ How to Run the Project

Clone or download the repository

Install required dependencies

pip install -r requirements.txt

Open Jupyter Notebook

jupyter notebook

Run Smart_Home_Location_Selector.ipynb cell by cell

# 📝 Sample Output

Top-ranked residential localities

Suitability score (%)

Pricing details

Safety and pollution indicators

Accessibility metrics

Results can be exported as a CSV file for further analysis.

# 🔮 Future Enhancements

Real-time data integration

User feedback–based learning

Web interface using Streamlit or Flask

API for third-party integration

Expansion to more cities

Deep learning–based recommendation models

# 🎓 Academic Relevance

This project demonstrates:

End-to-end data science workflow

Practical application of preprocessing & EDA

Integration of Machine Learning in recommendation systems

Real-world problem-solving using data-driven techniques
