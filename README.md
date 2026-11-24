# Swynex Task 2: Healthcare Exploratory Data Analysis (EDA)

## Dataset
- Cleaned Dataset: `swynex_healthcare_hospital_cleaned.csv` (850 rows × 16 columns)
- Notebook and Chart: `task2_healthcare_eda.ipynb` and `task2_healthcare_eda.png`

## Key Summary Statistics
- Age: Mean `50.11`, Median `49.00` (Min: `18`, Max: `85`)
- Billing Amount: Mean `₹60,898.64`, Median `₹55,471.12` (Min: `₹20,561.31`, Max: `₹1,75,766.59`)
- Length of Stay: Mean `4.82` days, Median `4.00` days (Min: `1` day, Max: `157` days)
- Satisfaction Score: Mean `3.77`, Median `4.00` (Scale: `1`–`5`)
- Overall Readmission Rate: `22.59%`

## 5 Key Insights and Anomalies
1. High Average Billing in Pneumonia and Cardiac Care: Pneumonia (`₹73,251.66`) and Cardiac Care (`₹71,785.28`) show higher average billing than other conditions such as Arthritis (`₹53,999.56`) and Diabetes (`₹54,609.08`).
2. Longer Average Stay in Hypertension: Hypertension patients stay the longest on average (`6.05` days), whereas Diabetes patients have the shortest average stay (`4.41` days).
3. Readmission Rate Variation: Overall readmission rate is `22.59%`, with Asthma (`26.03%`) and Pneumonia (`24.14%`) showing relatively higher readmission shares than Hypertension (`19.86%`).
4. Monthly Admissions Trend: Admissions fluctuate across 2025, peaking in August (`2025-08` with `97` patients) and dipping lowest in March (`2025-03` with `56` patients).
5. Stay Duration Outliers and Anomalies: Most stays range between `1` and `15` days, while `5` records show extended stays (`22` to `157` days) that should be reviewed for clinical complexity or data accuracy.
