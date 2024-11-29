# SpaceX's Falcon 9 Prediction: Data Science Professional Certificate Projects (IBM)

This repository contains a series of projects completed as part of the **IBM Professional Data Scientist Certificate**. The main focus is on applying data science methodologies to predict the landing outcomes of SpaceX Falcon 9 first-stage rockets, using exploratory data analysis, visualization, web scraping, API usage, data wrangling, and machine learning techniques.

## Table of Contents
- [Introduction](#introduction)
- [Project Descriptions](#project-descriptions)
- [Key Findings](#key-findings)
- [Setup and Requirements](#setup-and-requirements)
- [Usage](#usage)
- [Contributing](#contributing)
- [Contact](#contact)
- [License](#license)

---

## Introduction

SpaceX's Falcon 9 program has revolutionized space travel through reusable rockets, drastically cutting costs. The goal of these projects is to analyze and predict Falcon 9's first-stage landing success, leveraging tools and techniques from the data science domain.

This repository showcases various aspects of the data science lifecycle:
- Data collection via APIs and web scraping.
- Data cleaning and transformation.
- Exploratory data analysis (EDA).
- Data visualization using interactive tools.
- Machine learning model development for prediction.

---

## Project Descriptions

### 1. **Exploratory Data Analysis (EDA) with Data Visualization**
- **Objective:** Perform data exploration and create meaningful visualizations.
- **Highlights:**
  - Insights into SpaceX's mission data.
  - Identification of patterns in launch success rates.

### 2. **EDA with SQL**
- **Objective:** Analyze SpaceX data using SQL queries.
- **Highlights:**
  - Load datasets into a relational database.
  - Extract insights using SQL commands.

### 3. **Web Scraping Falcon 9 Launches**
- **Objective:** Scrape historical launch data from SpaceX's website.
- **Highlights:**
  - Collect structured data about launches.
  - Prepare the dataset for further analysis.

### 4. **Interactive Visual Analytics with Folium**
- **Objective:** Visualize launch sites on an interactive map.
- **Highlights:**
  - Use geospatial data to analyze launch success rates.
  - Display key locations interactively.

### 5. **SpaceX Data Collection with APIs**
- **Objective:** Gather live launch data using SpaceX's API.
- **Highlights:**
  - Fetch and structure data programmatically.
  - Prepare data for downstream processing.

### 6. **SpaceX Data Wrangling**
- **Objective:** Clean and organize raw data for analysis.
- **Highlights:**
  - Handle missing data and inconsistencies.
  - Prepare datasets for machine learning.

### 7. **Building an Interactive Dashboard with Plotly Dash**
- **Objective:** Develop a dashboard for dynamic data visualization.
- **Highlights:**
  - Allow users to explore data interactively.
  - Build and deploy using Plotly Dash.

### 8. **Machine Learning for Falcon 9 Prediction**
- **Objective:** Predict landing outcomes using machine learning.
- **Highlights:**
  - Develop classification models with scikit-learn.
  - Evaluate performance using metrics like accuracy and precision.

---

## Key Findings

After completing the analysis and machine learning models, the following insights were derived:

1. **Historical Trends in Falcon 9 Launches**:
   - The success rate of Falcon 9 launches has improved significantly over time.
   - Key factors influencing success include payload weight, launch site, and booster version.

2. **Interactive Mapping of Launch Sites**:
   - Using Folium, geographic visualizations revealed the importance of specific launch sites.
   - Cape Canaveral and Kennedy Space Center were the most frequently used sites.

3. **Machine Learning Predictions**:
   - Classification models achieved high accuracy in predicting landing outcomes.
   - Gradient Boosting and Random Forest classifiers performed the best among tested models.

4. **Cost Implications of Reusability**:
   - Reusable rockets dramatically reduce costs, making the prediction of successful landings crucial for SpaceX's business model.

5. **API and Web Scraping Effectiveness**:
   - The SpaceX API provided up-to-date data, while web scraping was useful for historical launches.
   - Combined, these methods enriched the dataset for analysis.

---

## Setup and Requirements

### Prerequisites
- Python 3.x
- Jupyter Notebook
- Required libraries are listed in `requirements.txt`.

### Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/myslyurt/SpaceX-s-Falcon-9-Prediction-Data-Scientist-Professional-certificate-project-IBM.git
   cd SpaceX-s-Falcon-9-Prediction-Data-Scientist-Professional-certificate-project-IBM
