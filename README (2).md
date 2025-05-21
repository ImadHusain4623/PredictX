
# 🚀 SpaceX Launch Analysis & Prediction

## 📌 Objective

The objective of this project is to analyze SpaceX launch records to:
- Explore historical trends and patterns.
- Visualize spatial and temporal launch data.
- Predict successful landings using machine learning classification models.
- Provide actionable insights to improve SpaceX’s future mission success rates.

---

## 📖 Project Description

This end-to-end data science project leverages APIs, web scraping, SQL, interactive visualizations, and classification models to:
- Retrieve, process, and analyze SpaceX launch data.
- Visualize launch outcomes and geographic patterns using Folium and Plotly.
- Perform Exploratory Data Analysis (EDA) using SQL and charts.
- Build, tune, and evaluate various classification models (Logistic Regression, SVM, KNN, Decision Tree) to predict landing success.

---

## 📂 Datasets Used

1. **Launch Data** via REST API: Collected from the SpaceX API using Python `requests`.
2. **Scraped Data**: Booster and landing outcome data scraped from Wikipedia.
3. **Processed Dataset**: Merged and cleaned data used for modeling.
4. **Classification Dataset**:
   - `dataset_part_2.csv`
   - `dataset_part_3.csv`

---

## 🧪 Methodology

### Data Collection
- SpaceX API REST calls for launch details.
- Web scraping of supplementary booster data.

### Data Wrangling
- Merging API and scraped data.
- Handling nulls, duplicates, and conversions.

### EDA (Exploratory Data Analysis)
- SQL queries for insights on launch patterns, payloads, and booster performance.
- Visualization using seaborn, matplotlib, and plotly.

### Interactive Analytics
- Folium maps showing global launch sites and outcome patterns.
- Plotly Dash for dynamic visual dashboards.

### Predictive Modeling
- Feature scaling and standardization.
- Splitting datasets into training and test sets.
- Model building with Logistic Regression, SVM, KNN, and Decision Tree.
- Hyperparameter tuning using GridSearchCV.
- Evaluation using accuracy score and confusion matrix.

---

## 📊 Slide Overview

- **Executive Summary**: High-level overview of the project.
- **Project Background**: Motivation and questions addressed.
- **Methodology**: Visual process flows for collection, wrangling, modeling.
- **EDA Findings**: Charts, maps, and SQL queries explaining insights.
- **Modeling Results**: Performance of models, accuracy comparison.
- **Conclusion**: Key takeaways and recommendations.
- **Appendix**: Assets, screenshots, and code snippets.

---

## 📌 Key Visualizations

- Scatter plots (Payload vs Launch Site, Flight No vs Orbit)
- Bar charts (Success rates by orbit)
- Folium map (Launch site markers & landing outcomes)
- Confusion matrix and accuracy chart for all models

---

## 🏆 Results

- Best model: [Model Name] with [Accuracy]%
- Most used launch site: [Site]
- Success rate trends increase over years
- Ground pad landings show higher success

---

## 📎 External References

- 📓 [Colab Notebook: SpaceX API Calls](https://colab.research.google.com/drive/16xTk91Z-v4vzHs6764YVAoJL6qJxMdsd)
- 📓 [Web Scraping Notebook](#)
- 📓 [Data Wrangling Notebook](#)
- 📓 [EDA Visualization Notebook](#)
- 📓 [EDA SQL Notebook](#)
- 📓 [Folium Map Notebook](#)
- 📓 [Predictive Modeling Notebook](#)

---

## 🧩 Technologies Used

- Python (Pandas, Numpy, Seaborn, Matplotlib, Scikit-learn)
- SQL (via SQLite3)
- Jupyter/Colab Notebooks
- Plotly Dash
- Folium
- Web scraping with BeautifulSoup
- REST APIs with `requests`

---

## 🧠 Conclusion

- Logistic Regression and Decision Trees performed well in predicting landing success.
- Payload mass and orbit type significantly affect success probability.
- Launch success has improved with newer booster versions and better landing infrastructure.

---

## 📁 Repository Structure

```
📦SpaceX-Launch-Analysis
 ┣ 📂notebooks/
 ┃ ┣ SpaceX_API_Calls.ipynb
 ┃ ┣ Web_Scraping.ipynb
 ┃ ┣ Data_Wrangling.ipynb
 ┃ ┣ EDA_Visualization.ipynb
 ┃ ┣ EDA_SQL.ipynb
 ┃ ┣ Folium_Map.ipynb
 ┃ ┗ Predictive_Modeling.ipynb
 ┣ 📂assets/
 ┃ ┣ images/
 ┃ ┗ screenshots/
 ┣ README.md
 ┣ presentation.pdf
 ┗ requirements.txt
```

---

## ✅ License

This project is for educational purposes under the [MIT License](LICENSE).
