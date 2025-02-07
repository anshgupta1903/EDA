Based on your GitHub repository [anshgupta1903/EDA](https://github.com/anshgupta1903/EDA), here's a detailed `README.md` template for your project:

---

# Exploratory Data Analysis (EDA) Project

## Overview

This project involves performing Exploratory Data Analysis (EDA) on two datasets:

1. **Google Play Store Apps Dataset**
2. **HR Analytics Dataset**

The primary objectives are to clean the data, handle missing values, identify key patterns, and visualize significant trends to derive meaningful insights.

## Datasets

### 1. Google Play Store Apps Dataset

- **Filename:** `googleplaystore.csv`
- **Description:** Contains information about various apps on the Google Play Store, including details like app name, category, rating, reviews, size, installs, type, price, content rating, genres, last updated, current version, and Android version.

### 2. HR Analytics Dataset

- **Filename:** `HRDataset_v14.csv`
- **Description:** Comprises employee data with attributes such as employee name, employee number, marital status, gender, date of hire, date of termination, reason for termination, employment status, department, position, pay rate, manager name, performance score, and more.

## EDA Process

The EDA was conducted using Jupyter Notebooks:

1. **Google Play Store Apps Analysis:** `EDA_GooglePlay.ipynb`
2. **HR Analytics Analysis:** `EDA_HRAnalytics.ipynb`

### Key Steps:

- **Data Cleaning:**
  - Handled missing values using NumPy and Pandas.
  - Converted data types (e.g., objects to integers/floats) for accurate analysis.
  - Removed duplicate entries to ensure data integrity.

- **Data Exploration:**
  - Analyzed distributions of key features.
  - Identified correlations between variables.
  - Detected outliers and anomalies.

- **Data Visualization:**
  - Utilized Seaborn and Matplotlib to create insightful visualizations, including histograms, box plots, scatter plots, and heatmaps.

## Key Insights

### Google Play Store Apps:

- **Rating Distribution:** Observed the distribution of app ratings to understand overall user satisfaction.
- **Category-wise Analysis:** Identified which app categories have the highest number of installs.
- **Price vs. Installs:** Analyzed the relationship between app pricing and the number of installs.

### HR Analytics:

- **Employee Tenure:** Examined the tenure of employees to identify retention patterns.
- **Performance Scores:** Analyzed the distribution of performance scores across departments.
- **Termination Reasons:** Investigated common reasons for employee termination.

## Tools and Libraries

- **Programming Language:** Python
- **Libraries:**
  - Data Manipulation: Pandas, NumPy
  - Data Visualization: Matplotlib, Seaborn
  - Jupyter Notebook for interactive analysis

## How to Use

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/anshgupta1903/EDA.git
   cd EDA
   ```

2. **Install Dependencies:**

   Ensure you have Python installed. Install the required libraries using pip:

   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
   ```

3. **Run the Notebooks:**

   Launch Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

   Open `EDA_GooglePlay.ipynb` or `EDA_HRAnalytics.ipynb` to explore the analyses.

## Visualizations

Here are some key visualizations from the analysis:

## Future Work

- **Google Play Store Apps:**
  - Analyze user reviews to gain sentiment insights.
  - Investigate the impact of app size on user ratings.

- **HR Analytics:**
  - Explore the relationship between pay rates and performance scores.
  - Analyze the impact of employment status on termination reasons.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your proposed changes.
