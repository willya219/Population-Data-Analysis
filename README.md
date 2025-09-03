# 📊 Analyse exploratoire et statistique d’un dataset de population

# 📊 Exploratory and Statistical Analysis of a Population Dataset

---

## 📌 Description

**FR**  
Projet personnel de **Data Analysis** sur un dataset de ~32 000 individus (Titanic) mise à disposition via un lien personnel (Google Drive).  
L’objectif est d’explorer les caractéristiques sociodémographiques et économiques d’une population en utilisant **Python**.

Le projet comprend :

- Nettoyage et préparation des données
- Étude exploratoire (valeurs manquantes, distributions)
- Statistiques descriptives (moyennes, médianes, variances)
- Corrélations entre variables (âge, éducation, salaire)
- Tests d’hypothèses (z-tests sur les heures travaillées et salaires)

**EN**  
Personal **Data Analysis** project on a dataset of ~32,000 individuals (Titanic) made it accessible through a personal (Google Drive) link to ensure project reproducibility.  
The goal is to explore socio-demographic and economic characteristics of a population using **Python**.

The project includes:

- Data cleaning and preprocessing
- Exploratory Data Analysis (missing values, distributions)
- Descriptive statistics (means, medians, variances)
- Correlation analysis between variables (age, education, salary)
- Hypothesis testing (z-tests on working hours and salaries)

---

## 📊 Exemple de résultats / Sample Results

**FR**

- Variance des âges (jeu complet) : **186.06**
- Corrélation salaire ↔ âge : **0.210**
- Corrélation salaire ↔ années d’éducation : **0.345**
- Femmes avec maîtrise et salaire >50K : **67.61%**
- Hommes avec maîtrise et salaire >50K : **90.90%**

**EN**

- Variance of ages (full dataset): **186.06**
- Correlation salary ↔ age: **0.210**
- Correlation salary ↔ years of education: **0.345**
- Women with Master’s degree and salary >50K: **67.61%**
- Men with Master’s degree and salary >50K: **90.90%**

---

## 🛠️ Technologies utilisées / Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- SciPy / Statsmodels
- Jupyter Notebook

---

## ▶️ Exécution / How to Run

**FR**  
Clonez le dépôt et installez les dépendances :

```bash
git clone https://github.com/willya219/Population-Data-Analysis.git
cd Population-Data-Analysis
pip install -r requirements.txt
jupyter notebook notebooks/book.ipynb
```

**EN**
Clone the repository and install dependencies:

```bash
git clone https://github.com/willya219/Population-Data-Analysis.git
cd Population-Data-Analysis
pip install -r requirements.txt
jupyter notebook notebooks/TP1_Code.ipynb
```

## 📂 Structure du dépôt / Repository Structure

Population-Data-Analysis/
│── notebooks/
│ └── book.ipynb # Jupyter Notebook with full analysis
│── report/
│ └── Rapport d'analyse.pdf # Full written analysis
│── README.md
│── requirements.txt

## 📢 Note

**FR**
Ce projet est à visée pédagogique et pratique. Il illustre des compétences en data cleaning, statistiques et visualisation applicables dans des contextes professionnels.

**EN**
This project is intended for educational and practical purposes. It demonstrates skills in data cleaning, statistics, and visualization that can be applied in professional contexts.
