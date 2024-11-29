# SpaceX Falcon 9 Landing Prediction Project

This project focuses on predicting the landing success of SpaceX Falcon 9's first-stage rockets. By analyzing key mission data, we aim to identify patterns and develop predictive models that contribute to more efficient resource allocation and mission planning.

---

## Project Workflow
1. **Data Collection**: Collected data from SpaceX API and web scraping to compile a comprehensive dataset.
2. **Data Cleaning**: Processed missing or inconsistent values to ensure the dataset's reliability.
3. **Exploratory Data Analysis (EDA)**: Analyzed trends and relationships between key variables such as payload weight, launch site, and success rate.
4. **Modeling**: Developed machine learning models (Logistic Regression and Random Forest) to predict landing outcomes.
5. **Evaluation**: Assessed model performance using metrics like accuracy and F1-score.

---

## Dataset Overview
The dataset is a combination of SpaceX API data and historical mission information from web scraping. Key columns include:

| Column Name       | Description                                                           |
|--------------------|-----------------------------------------------------------------------|
| mission_id        | Unique identifier for the mission.                                   |
| launch_site       | Launch site for the mission.                                         |
| payload_mass      | Payload weight in kilograms.                                         |
| orbit             | Target orbit for the payload.                                        |
| booster_version   | Version of the rocket booster.                                       |
| landing_success   | Boolean indicating the success of the first-stage landing.           |

---

## Steps and Methods

### **1. Data Collection**
- **API Integration**: Used SpaceX API to fetch mission data, including payload details, booster versions, and landing outcomes.
- **Web Scraping**: Extracted additional historical data to supplement the dataset.

### **2. Data Cleaning**
- Missing and inconsistent values were handled as follows:
  - **Payload Mass**: Replaced missing values with the column mean.
  - **Booster Version**: Standardized naming conventions.
  - **Landing Success**: Excluded missions with no recorded landing outcomes.

### **3. Exploratory Data Analysis (EDA)**
- Investigated the relationship between payload mass and landing success.
- Analyzed launch site distribution and success rates.
- Explored the impact of booster technology advancements on landing outcomes.

### **4. Modeling**
- **Logistic Regression**: A simple baseline classifier for predicting landing success.
- **Random Forest**: A more complex model that accounts for non-linear relationships.
- **Feature Engineering**: Extracted temporal features from launch dates.

### **5. Evaluation**
- Models were evaluated using:
  - **Accuracy**: Percentage of correctly predicted outcomes.
  - **F1-Score**: Harmonic mean of precision and recall, suitable for imbalanced datasets.

---

## Results and Insights

### **EDA Findings**
1. **Launch Site Performance**: Kennedy Space Center showed the highest landing success rates.
2. **Payload Constraints**: Missions with payloads exceeding 8,000 kg had lower success probabilities.
3. **Booster Advancements**: Newer booster versions significantly increased landing success rates.

### **Model Performance**
| Model              | Accuracy   | F1-Score |
|---------------------|------------|----------|
| Logistic Regression | 85.6%      | 0.83     |
| Random Forest       | 92.3%      | 0.91     |

The Random Forest model demonstrated superior performance, effectively capturing the complex relationships in the data.

---

## Key Results
- **Random Forest Predictions**: The model achieved a 92.3% accuracy rate, making it a reliable predictor of landing success.
- **Feature Importance**: Payload weight, launch site, and booster version were identified as the most influential features.
- **Reusable Rocket Success**: The analysis confirms that advancements in reusable rocket technology have significantly increased landing success rates.

Sample predictions from the Random Forest model:

| Mission ID | Predicted Success |
|------------|-------------------|
| 1100       | True              |
| 1205       | False             |
| 1234       | True              |

---

## Future Work
1. **Feature Expansion**: Include external data such as weather conditions and mission duration to improve predictive accuracy.
2. **Advanced Models**: Experiment with gradient boosting techniques like XGBoost and LightGBM.
3. **Deployment**: Create a web-based application for real-time landing success predictions.
4. **Hyperparameter Tuning**: Optimize model parameters for better performance.

---

## How to Use

### Prerequisites
- Python 3.x
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `folium`, `dash`, `plotly`, `requests`, `beautifulsoup4`

### Steps to Reproduce
1. Clone the repository:
   ```bash
   git clone https://github.com/myslyurt/SpaceX-s-Falcon-9-Prediction-Data-Scientist-Professional-certificate-project-IBM.git
   cd SpaceX-s-Falcon-9-Prediction-Data-Scientist-Professional-certificate-project-IBM
   

### **Contact**
If you have any questions or suggestions, please contact:
- **Name**: Murat Yesilyurt
- **Email**: myesilyurtdsc@gmail.com
- **Linkedin**: [Murat Yesilyurt](https://www.linkedin.com/in/yesilyurt-murat/)
