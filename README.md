
# 🦠 COVID-19 Clinical Trials – Exploratory Data Analysis (EDA)

This repository contains an Exploratory Data Analysis (EDA) project on global **COVID-19 clinical trials**, aimed at understanding patterns, trends, and gaps in the research efforts conducted during the pandemic.

## 📌 Project Overview

The COVID-19 pandemic triggered an unprecedented wave of clinical research across the globe. This project explores a publicly available dataset of global clinical trials to extract meaningful insights around:

- Trial statuses and phases  
- Geographic spread of trials  
- Enrollment size and distributions  
- Age and gender inclusivity  
- Time-series trends and more  

The analysis includes thorough data cleaning, preprocessing, univariate and bivariate visualizations, and key findings backed by graphs.

## 📂 Project Structure

```
.
├── COVID 19 - EDA Project.ipynb     # Jupyter Notebook with full EDA
├── COVID clinical trials.csv        # Dataset used for analysis
├── report/                          # Project report in PDF format
│   └── COVID 19 - EDA Project.pdf
├── images/                          # Exported EDA plots used in report
│   └── *.png
├── cover_page/                      # Cartoon-style cover illustrations
│   └── cover.png
└── README.md                        # This file
```

## 🧪 Dataset Information

- **Source**: [Provided CSV file - COVID clinical trials.csv]
- **Records**: ~4100+
- **Key Columns**:
  - `Status`: Trial status (Completed, Recruiting, Withdrawn, etc.)
  - `Phase`: Clinical trial phase (Phase 1, 2, 3, etc.)
  - `Enrollment`: Number of enrolled participants
  - `Country`, `Gender`, `Age`, `Study Type`, `Conditions`, etc.

## 🔧 Technologies Used

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Jupyter Notebook
- PDF and image editors for report visualization

## 📊 Key Insights

- **Recruiting and Completed** were the most common trial statuses.
- Majority of trials were conducted in the **United States**, followed by **European countries**.
- Enrollment sizes were highly **skewed**, with a few trials involving tens of thousands of participants.
- Several entries lacked **location** and **phase** information, highlighting gaps in data reporting.
- Age and gender fields showed inclusive approaches, though often recorded as “All.”

## 📈 Visuals

You’ll find graphs and charts in the `images/` folder, categorized by:
- Trial status distribution
- Country-wise trial participation
- Enrollment size outliers
- Gender and age-wise inclusivity
- Monthly trial registration trends

## 📚 Report

A detailed project report is available in the `report/` folder, including:
- Abstract
- Problem Statement
- Objectives
- Dataset Description
- Data Cleaning & Preprocessing
- EDA (Univariate, Bivariate, Time-Series)
- Observations and Graphical Insights
- Key Findings
- Challenges & Limitations
- Conclusion

## 🙋‍♂️ Author
**Yuvraj Singh Bhadauria**  

## 💡 Future Work

- Predictive modeling using cleaned data  
- NLP-based topic modeling on `Conditions` and `Study Description`  
- Dashboard creation using Streamlit or Power BI

## 📜 License

This project is open-source and available under the [MIT License](LICENSE).

## ⭐️ Give it a Star!

If you found this project helpful or insightful, feel free to ⭐ the repo and share your feedback!
