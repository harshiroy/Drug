# 💊 Drugs, Side Effects & Medical Conditions Analysis

A **data analysis and visualization project** exploring relationships between drugs, their side effects, medical conditions, and user ratings.  
Includes a **Python backend** for data cleaning & analysis and a **Streamlit frontend dashboard** for interactive exploration.

---

## 📌 Features
- 🔎 Clean and preprocess real drug dataset  
- 📊 Perform Exploratory Data Analysis (EDA) with charts & descriptive stats  
- 📂 Generate CSV summaries (conditions, side effects, drug classes)  
- 🌐 Launch an interactive Streamlit dashboard with filters and visualizations  

---

## 📂 Project Structure
├── main.py # Backend analysis & data cleaning
├── app.py # Streamlit frontend dashboard
├── drugs_side_effects_drugs_com.csv # Original dataset
├── cleaned_drugs_dataset.csv # Cleaned dataset (generated)
├── medical_condition_counts.csv # Summary output (generated)
├── side_effect_counts.csv # Summary output (generated)
├── drug_classes_counts.csv # Summary output (generated)
├── ratings_distribution.png # Visualization (generated)
├── top_conditions.png # Visualization (generated)
├── top_side_effects.png # Visualization (generated)
├── ratings_by_class.png # Visualization (generated)
├── correlation_heatmap.png # Visualization (generated)
└── README.md


---

## 🧭 Dashboard Highlights
### 🎯 Interactive Features
- Filter by **medical condition** and **drug class**  
- View **ratings distribution** and **drug class comparisons**  
- Explore **top conditions** and **most common side effects**  
- Interactive **data table** for deeper insights  

---

## 📸 Sample Visualizations

| Visualization | Description |
|----------------|-------------|
| ![ratings_distribution](ratings_distribution.png) | **Drug Ratings Distribution** |
| ![top_conditions](top_conditions.png) | **Top Medical Conditions** |
| ![top_side_effects](top_side_effects.png) | **Most Common Side Effects** |
| ![correlation_heatmap](correlation_heatmap.png) | **Correlation Heatmap of Features** |

---

## 🛠️ Tech Stack
| Component | Technology |
|------------|-------------|
| **Language** | Python 3.13 |
| **Data Manipulation** | Pandas, NumPy |
| **Visualization** | Matplotlib, Seaborn |
| **Preprocessing** | Scikit-learn |
| **Web Dashboard** | Streamlit |

---

## 🚀 Future Enhancements
- 🔮 Predict drug ratings using ML models (Regression / XGBoost)  
- 💡 Build a **drug recommendation system** based on side effects & conditions  
- ☁️ Deploy dashboard on **Streamlit Cloud / Heroku / Render**  

---

## ⚙️ How to Run Locally
```bash
# Clone this repository
git clone https://github.com/yourusername/drugs-sideeffects-analysis.git
cd drugs-sideeffects-analysis

# Install dependencies
pip install -r requirements.txt

# Run backend analysis
python main.py

# Launch Streamlit dashboard
streamlit run app.py
📦 requirements.txt
pandas
numpy
matplotlib
seaborn
scikit-learn
streamlit
