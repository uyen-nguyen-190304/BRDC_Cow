# GiveSmart: Predictive Donor Analytics - 2025 Big Red Data Challenge

Team: Minh Le, Uyen Nguyen, Viet Nguyen, Lewis Nguyen

## 🔍 Overview
This project uses behavioral analytics and statistical modeling to help Sam’s Fans, a nonprofit supporting music therapy for seriously ill children, identify high-value donor segments and optimize fund allocation. By analyzing over 8,000 donation records, we surfaced key patterns that inform personalized outreach and strategic growth.

## 🗂 Project & Structure
```
.
├── data/                                       # Cleaned and raw data files
├── presentations/                              # Project slides and graphics
├── summary/                                    # Executive Summary
├── notebook/                                   # Jupyter Notebook for analysis
│   ├── RFManalysis.ipynb                       # K-means clustering on RFM scores
│   ├── Time_Series_Survival_Analysis.ipynb     # Kaplan-Meier, Weibull AFT, STL, SARIMA models
│   ├── Unmet_Demand_Analysis.ipynb             # OLS regression to identify funding gaps
├── requirements.txt                            # Python package requirements
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
- Seasonal donation grows strong over the years but regular donor engagement in 2024 underperformed compared to the growing trend of the previous years.

- Sam’s Fans is predicted to earn ~$300,000 in donation revenue in this upcoming peak donation month (October 2025).

- Donors of Sam’s Fans can be split into five groups by decreasing value and frequency of engagement: Star Donors, Committed Contributors, Emerging Partners, At-Risk Donors, and Inactive Donors.

- 80% of donation revenue came from the 20% Star Donors.

- Committed Contributors and Emerging Partners have very similar donating patterns, so a low-hanging fruit would be to convert the latter to the former.

- Annual engagement is a key component of donor retention for Committed Contributors and Emerging Partners.

- There are 12 statistical significant predictors (p < 0.05) for unmet needs in providing therapy programs across 8 hospitals.

## ✨ Reccomendations
- Star Donors: Executive-level, ongoing, personalized rapport to maintain engagement at a deep level with Sam’s Fans

- Committed Contributors & Emerging Partners: Focus on community-building and a personalized approach within 9–10 months after donation. Allow donors to see the impact of their contributions!

- At-Risk Donors: Low-stake outreach within a short time span of within 3 months post-donation to transform At-Risk Donors into new Emerging Partners.

- Program Investments: Allocate FY2025 budget to expand art/music therapy, scale group sessions, diversify inpatient services, and launch gender-inclusive outreach to address high-impact unmet needs.


## 🛠 Setup & Installation

To get started with this project, follow these steps:

1. **Clone the repository**

   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
   ```

2. **Create and activate a virtual environment (optional but recommended)**

   ```bash
   python -m venv venv
   source venv/bin/activate    # On Windows: venv\Scripts\activate
   ```

3. **Install the required packages**

   ```bash
   pip install -r requirements.txt
   ```

## 📚 References
- [Sam’s Fans – Nonprofit Partner](https://www.samsfans.org/)

- [Denison Data Analytics Program](https://www.linkedin.com/company/denison-data-analytics-program/)

## 📬 Contact
- Minh Le: le_m2@denison.edu
- Uyen Nguyen: nguyen_u1@denison.edu
- Viet Nguyen: nguyen_v5@denison.edu
- Lewis Nguyen: nguyen_h10@denison.edu