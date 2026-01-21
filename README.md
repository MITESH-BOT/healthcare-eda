# 🩺 Heart Disease Analytics: From Data Cleaning to AI Prediction

## 🌟 The Big Picture
Can we predict heart disease before it becomes a crisis? This project takes raw clinical data and transforms it into a predictive tool. I built a pipeline that cleans messy medical records, performs deep exploratory analysis, and trains an AI model with **80% diagnostic accuracy**.

## 🧠 What the AI Discovered
I used a **Random Forest Classifier** to look for patterns. While age is a factor, the AI prioritized these markers as the most important:
1. **Cholesterol**: The strongest anchor for prediction.
2. **Max Heart Rate (thalch)**: Lower heart rate capacity strongly correlated with disease.
3. **Oldpeak**: Exercise-induced stress markers.


## 🛠️ The Technical Journey
* **Phase 1 & 2 (The Foundation)**: Handled missing values (ca, thal) and capped extreme cholesterol outliers.
* **Phase 3 (Exploration)**: Found that heart disease risk "crosses over" healthy levels after **age 53**.
* **Phase 4 (Machine Learning)**: Achieved **87% precision** for positive cases, minimizing false alarms.
* **Phase 5 (Business Intelligence)**: Created an interactive Tableau Dashboard for healthcare providers.

## 📊 Interactive Dashboard
I built a Tableau dashboard to make these insights interactive.
👉 **[Link to my Tableau Public Dashboard]** *(https://public.tableau.com/views/Heart_Disease_Analysis_Dashboard/Sheet3?:language=en-GB&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)*

## 🚀 How to Run
1. `pip install -r requirements.txt`
2. Run `notebooks/01_data_audit.ipynb`
