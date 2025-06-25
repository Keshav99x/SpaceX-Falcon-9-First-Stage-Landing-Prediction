
# 🚀 SpaceX Falcon 9 First Stage Landing Prediction

This project aims to **predict the landing success of SpaceX's Falcon 9 rocket's first stage** using real-world launch data. The analysis covers everything from data collection and wrangling to interactive dashboards and machine learning modeling.

## 📁 Project Structure

| File | Description |
|------|-------------|
| `Data Collection API.ipynb` | Collected SpaceX launch data using RESTful APIs. |
| `Data Collection with Web Scraping.ipynb` | Supplemented launch data using web scraping from Wikipedia. |
| `Data Wrangling.ipynb` | Cleaned and merged datasets into structured format. |
| `EDA with Data Visualization.ipynb` | Performed exploratory data analysis using Matplotlib & Seaborn. |
| `Interactive Visual Analytics with Folium.ipynb` | Mapped launch sites with Folium for geospatial analysis. |
| `Machine Learning Prediction.ipynb` | Built classification models to predict landing success. |
| `spacex_dash_app.py` | Dash application for interactive visual exploration. |
| `spacex_launch_dash.csv` | Dataset used for Dash app development. |
| `spacex_launch_geo.csv` | Launch site geolocation data for Folium maps. |
| `ds-capstone-presentation final.pdf` | Final report and presentation deck. |
| `jupyter-labs-eda-sql-coursera_sqlite.ipynb` | SQL-based data analysis and visualization. |

## 🔍 Objective

- Analyze Falcon 9 launches to understand patterns behind successful landings.
- Build predictive models to forecast landing success using features like payload, orbit, launch site, and booster version.

## 🛠️ Technologies Used

- **Languages & Libraries**: Python, Pandas, NumPy, Seaborn, Matplotlib, Scikit-learn, XGBoost
- **Web Technologies**: Dash, Plotly
- **Geospatial Analysis**: Folium
- **Data Sources**: SpaceX API, Wikipedia, Kaggle

## 📈 Machine Learning

Trained several classification models:
- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)
- XGBoost

**Evaluation Metrics**:
- Accuracy
- Precision / Recall
- Confusion Matrix

## 🌐 Interactive Dash App

A Plotly Dash application was developed to:
- Visualize launch outcomes across sites
- Explore payload and orbit correlations with landing success

## 📊 Sample Visualizations

- Launch Success Distribution
- Payload vs Landing Success
- Launch Site Map with Outcomes

## 📌 How to Run

1. Clone this repo:
   ```bash
   git clone https://github.com/Keshav99x/SpaceX-Falcon-9-First-Stage-Landing-Prediction.git
   cd SpaceX-Falcon-9-First-Stage-Landing-Prediction
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the Dash App:
   ```bash
   python spacex_dash_app.py
   ```
