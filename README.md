# 📊 Statistical Analysis of Determinants Influencing Tourist Arrivals and Revenue in Sri Lanka

This project aims to analyze the impact of multiple factors on tourism revenue in Sri Lanka over the past decade, utilizing official SLTDA data. Key variables include tourist arrivals, average stay duration, daily spending, source markets, accommodation capacity, flight availability, investment projects, and policy influences such as ETA delays. Using Python, we will apply statistical techniques like probability distribution fitting, confidence interval estimation, hypothesis testing, correlation, and linear regression. The objective is to identify significant predictors of tourism revenue, make data-driven predictions, and offer insights into optimizing tourism policy and infrastructure. 

---

## 🎯 Objectives
- Identify factors significantly affecting tourist arrivals and tourism revenue.
- Fit probability distributions to tourism data (e.g., daily expenditure).
- Construct confidence intervals for key tourism metrics (e.g., average stay).
- Test hypotheses on seasonal and regional tourism differences.
- Model relationships using correlation and regression.
- Predict future tourism revenue based on historical trends and influencing variables.

---

## 📂 Repository Structure
sri-lanka-tourism-stats/</br>
├── 📄 README.md # Project overview & instructions</br>
├── 📄 LICENSE # License (MIT)</br>
├── 📄 .gitignore # Git ignore rules</br>
├── 📄 requirements.txt # Python dependencies</br>
│</br>
├── 📂 data/ # Datasets</br>
│ ├── 📂 raw/ # Original SLTDA datasets (keep untouched)</br>
│ └── 📂 processed/ # Cleaned & transformed datasets</br>
│</br>
├── 📂 src/ # Source code</br>
│ ├── 📓 eda.ipynb # Exploratory data analysis</br>
│ ├── 📓 models.ipynb # Regression & forecasting</br>
│ └── 🛠️ utils.py # Helper functions</br>
│</br>
├── 📂 reports/ # Reports & presentations</br>
│ ├── 📂 paper/ # Final paper</br>
│ │ ├── 📄 main.tex # LaTeX main file</br>
│ │ ├── 📄 refs.bib # References</br>
│ │ └── 📂 figs/ # Figures for paper</br>
│ └── 📂 presentation/ # Slides</br>
│ ├── 📄 slides.tex # Beamer slides (or PPTX)</br>
│ └── 📂 figs/ # Figures for slides</br>
│</br>
├── 📂 notebooks/ # Experimental Jupyter notebooks</br>
│ └── 📓 data_exploration.ipynb</br>
│</br>
└── 📂 docs/ # (Optional) Extra documentation</br>

---

## 📊 Data Source
- **Sri Lanka Tourism Development Authority Annual Reports**  
  Website: [https://www.sltda.gov.lk/](https://www.sltda.gov.lk/)  

Data includes:
- Tourist arrivals (monthly/annual)
- Tourism revenue
- Average length of stay
- Daily expenditure
- Flight and accommodation capacity
- Policy changes/events

---
