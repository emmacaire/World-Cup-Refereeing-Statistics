# World Cup Refereeing Statistics
**Blog:** Law5 - The Referee | **Article:** Refereeing Stats at World Cup

## 📋 Summary
A few weeks before the start of the 2026 World Cup, I conducted this analysis to explore the evolution of refereeing at the previous tournament editions and confirm patterns and trends with numbers and empirical evidence. 
The analysis mostly focused on referee appointments and disciplinary aspects (yellow and red cards), surrounded by a set of explanatory variables such as referee/team confederations, tournament stage, tournament year, minute of play and player role.
Source data was extracted from a comprehensive dataset including all games at World Cup since 1930, but most of the analysis focuses on the latest 30 years, from 1986 onwards.

## 📊 Key Deliverables & Artifacts
* 📂 **[Interactive Analysis Notebook](./notebooks/Classification_data_mining_2.ipynb):** 
Python code including EDA, data cleaning, model training and comparison.
* 📄 **[Chapter 1: Referee appointments and experience]([https://law5-theref.blogspot.com/2026/06/refereeing-stats-at-world-cup-chapter-1.html]):** 
A synthetic report explaining the methodologies, challenges and summarizing the academic conclusions.
* 📄 **[Chapter 2: Card distribution and timing](https://law5-theref.blogspot.com/2026/06/refereeing-stats-at-world-cup-chapter-2.html):** 
A synthetic report explaining the methodologies, challenges and summarizing the academic conclusions.
* 📄 **[Chapter 3: Individual referee and team statistics]([./report/Classification_report_DM2.pdf](https://law5-theref.blogspot.com/2026/06/refereeing-stats-at-world-cup-chapter-3.html)):** 
A synthetic report explaining the methodologies, challenges and summarizing the academic conclusions.

## 🛠️ Tech Stack & Methodology
* **Language:** 
Python (Pandas, Scikit-Learn, Matplotlib, Seaborn, NumPy, SciPy)
* **Concepts:** 
Outlier detection (winsorization), handling missing values (one-hot encoding, average target encoding), feature selection (RFE), model training (logistic regression, Naive Bayes, KNN, Random Forest, Extra Trees, Adaboost, Gradient Boosting, MLP), confusion matrix evaluation and metrics (accuracy, precision, recall, F1-score, ROC AUC).
