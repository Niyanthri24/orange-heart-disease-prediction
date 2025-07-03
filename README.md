# orange-heart-disease-prediction
Visual data mining project using Orange for heart disease prediction and COVID-19 trend analysis.

This project demonstrates how **visual data mining** can be used to analyze and derive insights from **health-related datasets**, focusing on:
1. **Heart Disease Prediction**
2. **COVID-19 Trend Analysis**

Built entirely in **Orange (v3.36)** — a GUI-based data mining and machine learning tool — this project visually illustrates the power of analytics in real-world health scenarios.

---

## 📌 Project Highlights

| Module | Description |
|--------|-------------|
| **Heart Disease Prediction** | Uses the UCI Heart Disease dataset and applies data preprocessing and **Random Forest classification** to predict the risk of heart disease. |
| **COVID-19 Trend Analysis** | Analyzes time-series data from WHO to visualize **pandemic waves**, infection rates, and recovery trends using Orange's interactive charts. |

---

## 🔧 Tools & Technologies

- 🟧 Orange v3.36  
- 📊 Visual Widgets: Scatter Plot, Box Plot, Line Chart, Bar Chart  
- 🧠 ML Models: Random Forest  
- 📁 Datasets:
  - UCI Heart Disease Dataset
  - WHO COVID-19 Global Dataset

---

## 🚀 How to Run

1. Download and install [Orange Data Mining](https://orangedatamining.com/download)
2. Open Orange and go to **File > Open**
3. Select:
   - `heart_disease_prediction.ows` to view the heart disease workflow
   - `covid19_trends_analysis.ows` to view COVID-19 trend workflow

---

## 📊 Key Features Used

### Heart Disease Prediction
- **Widgets**: File, Select Columns, Normalize, Random Forest, Test & Score, Confusion Matrix, ROC Analysis
- **Insights**: Identifies key predictors such as age, cholesterol, chest pain type

### COVID-19 Trend Analysis
- **Widgets**: File, Group By, Aggregate, Line Plot, Bar Chart
- **Insights**: Identified pandemic waves, daily trends, and recovery patterns

---

## 🌐 Applications

- **Clinical Diagnosis Support**: Identifies high-risk individuals for heart disease
- **Pandemic Surveillance**: Visualizes COVID-19 wave patterns
- **Public Health Policy**: Supports resource allocation and intervention planning
- **Education**: Demonstrates ML and data mining concepts visually

---

## ⚠️ Limitations

- Static datasets; real-time integration not implemented
- Limited hyperparameter tuning in Orange GUI
- COVID-19 module is focused on trend visualization, not prediction
- Performance depends on data quality and preprocessing

---

## 🧠 Future Enhancements

- Integrate real-time data (e.g., via API)
- Add predictive modeling for COVID-19 (e.g., forecasting)
- Deploy interactive dashboards (e.g., with Streamlit or Dash)
- Add support for mobile viewing of visualizations

---

## 📚 References

- [UCI Heart Disease Dataset](https://archive.ics.uci.edu/ml/datasets/heart+disease)  
- [WHO COVID-19 Dashboard](https://covid19.who.int)  
- [Orange Data Mining Docs](https://orangedatamining.com)

---

## 📢 License

This project is for educational and academic use only.  
---

📫 For queries, feel free to reach out or open an issue in this repo.
