# Flight-Price-EDA
Flight Price EDA with data preprocessing, feature engineering, and visualization.
# ✈️ Flight Price Exploratory Data Analysis (EDA)

## 📌 Project Overview

This project focuses on performing Exploratory Data Analysis (EDA) on a flight price dataset to uncover patterns and factors affecting airline ticket prices. The analysis includes data cleaning, feature engineering, data visualization, and business insights using Python.

---

## 🎯 Objectives

- Clean and preprocess the flight dataset.
- Explore the distribution of flight prices.
- Analyze the impact of airlines, source, destination, duration, and total stops on ticket prices.
- Identify trends, correlations, and outliers.
- Generate meaningful business insights through visualizations.

---

## 📂 Dataset

The dataset contains information about airline flights, including:

- Airline
- Date of Journey
- Source
- Destination
- Route
- Departure Time
- Arrival Time
- Duration
- Total Stops
- Additional Information
- Price

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- OpenPyXL
- Jupyter Notebook

---

## 🧹 Data Cleaning

The following preprocessing steps were performed:

- Checked for missing values
- Removed unnecessary columns
- Converted journey date into separate day, month, and year columns
- Extracted departure hour and minute
- Extracted arrival hour and minute
- Converted flight duration into total minutes
- Converted total stops into numerical values
- Verified and corrected data types

---

## 📊 Exploratory Data Analysis

The following analyses were performed:

- Price Distribution
- Number of Flights by Airline
- Number of Flights by Source
- Number of Flights by Destination
- Flight Duration Distribution
- Airline vs Price
- Source vs Price
- Destination vs Price
- Total Stops vs Price
- Correlation Heatmap
- Outlier Analysis

---

## 📈 Key Insights

- Jet Airways has the highest number of flights in the dataset.
- Delhi is the most common departure city.
- Flights with more stops generally have higher ticket prices.
- Longer flight durations tend to have higher fares.
- Source and destination significantly influence ticket prices.
- Total Stops and Flight Duration show the strongest positive correlation with ticket price.

---

## 📁 Project Structure

```
Flight-Price-EDA/
│
├── Flight_Price_EDA.ipynb
├── flight_price.xlsx
├── README.md
└── requirements.txt
```

---

## ▶️ How to Run

### 1. Clone the repository

```bash
git clone https://github.com/your-username/Flight-Price-EDA.git
```

### 2. Navigate to the project folder

```bash
cd Flight-Price-EDA
```

### 3. Install the required libraries

```bash
pip install -r requirements.txt
```

### 4. Open Jupyter Notebook

```bash
jupyter notebook
```

### 5. Open the notebook and run all cells

---

## 📌 Future Improvements

- Build a Flight Price Prediction model using Machine Learning.
- Perform feature selection and feature engineering.
- Deploy the model using Streamlit or Flask.
- Develop an interactive dashboard using Power BI or Tableau.

---

## 📚 Learning Outcomes

Through this project, I learned:

- Data cleaning and preprocessing using Pandas
- Feature engineering techniques
- Exploratory Data Analysis (EDA)
- Data visualization using Matplotlib and Seaborn
- Correlation analysis and interpretation
- Extracting business insights from data

---

## 👤 Author

**Ashna**

Computer Engineering Student | Aspiring Data Analyst

---
