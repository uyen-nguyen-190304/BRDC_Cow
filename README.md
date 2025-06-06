# GiveSmart: Predictive Donor Analytics - 2025 Big Red Data Challenge

Team: Minh Le, Uyen Nguyen, Viet Nguyen, Lewis Nguyen

## 🔍 Overview
This project uses behavioral analytics and statistical modeling to help Sam’s Fans, a nonprofit supporting music therapy for seriously ill children, identify high-value donor segments and optimize fund allocation. By analyzing over 8,000 donation records, we surfaced key patterns that inform personalized outreach and strategic growth.

## 🗂 Project & Structure
```
.
├── data/                                       # Cleaned and raw data files
├── presentations/                              # Project slides and graphics
├── RFManalysis.ipynb                           # K-means clustering on RFM scores
├── Time_Series_Survival_Analysis.ipynb         # Kaplan-Meier, Weibull AFT, STL, SARIMA models
├── Unmet_Demand_Analysis.ipynb                 # OLS regression to identify funding gaps
├── README.md                                   # Project summary and documentation
└── .gitignore
```

## ⚙️ Methodology
1. Donor Segmentation:

- Applied RFM analysis (Recency, Frequency, Monetary)

- Used K-means clustering to classify donors into 5 behavioral segments

2. Time-Series & Survival Analysis

- Modeled retention using Kaplan-Meier and Weibull AFT

- Detected seasonal giving patterns via STL decomposition

- Forecasted donation trends using SARIMA

3. Regression Modeling

- Ran an OLS model to identify unmet demand in therapy programs

- Pinpointed 5+ key areas to strengthen support (e.g., Art/Music Therapy, Group Sessions)

## 📈 Key Findings
- Helped Sams Fans identifiying “Star Donors” and "Commited Contributors" clusters for future retention strategies

- Donation engagement spikes in Q4; risk of churn if no contact within 9–10 months

- Regression insights guided data-backed investment in underserved program areas

## 📚 References
- [Sam’s Fans – Nonprofit Partner](https://www.samsfans.org/)

- [Denison Data Analytics Program](https://www.linkedin.com/company/denison-data-analytics-program/)

## 📬 Contact
- Minh Le: le_m2@denison.edu
- Uyen Nguyen: nguyen_u1@denison.edu
- Viet Nguyen: nguyen_v5@denison.edu
- Lewis Nguyen: nguyen_h10@denison.edu