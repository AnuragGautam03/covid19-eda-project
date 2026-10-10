#  COVID-19 Data Analysis — Exploratory Data Analysis (EDA)

A beginner-friendly **Exploratory Data Analysis (EDA)** project on COVID-19 global data. This project covers data cleaning, descriptive statistics, and insightful visualizations.

---

##  Project Structure

```
covid19-eda-project/
│
├── data/
│   └── covid19_data.csv          # Dataset used for analysis
│
├── covid19_eda.ipynb             # Main Jupyter Notebook
├── requirements.txt              # Python dependencies
├── README.md                     # Project documentation
└── .gitignore                    # Files to ignore in Git
```

---

##  What This Project Covers

-  **Loading & Exploring** the dataset (shape, dtypes, head/tail)
-  **Data Cleaning** — handling missing values, formatting dates
-  **Descriptive Statistics** — mean, median, std, etc.
-  **Top countries** by confirmed cases, deaths, recoveries
-  **Time-series analysis** of global COVID-19 spread
-  **Visualizations** using Matplotlib & Seaborn
-  **Key Insights & Conclusions**

---

##  Technologies Used

| Tool | Purpose |
|------|---------|
| Python 3.8+ | Core language |
| Pandas | Data loading & manipulation |
| NumPy | Numerical operations |
| Matplotlib | Basic plotting |
| Seaborn | Statistical visualizations |
| Jupyter Notebook | Interactive analysis |

---

##  How to Run This Project

### 1. Clone the repository
```bash
git clone https://github.com/YOUR_USERNAME/covid19-eda-project.git
cd covid19-eda-project
```

### 2. Create a virtual environment (recommended)
```bash
python -m venv venv
venv\Scripts\activate        # Windows
# source venv/bin/activate   # Mac/Linux
```

### 3. Install dependencies
```bash
pip install -r requirements.txt
```

### 4. Launch Jupyter Notebook
```bash
jupyter notebook
```

Then open `covid19_eda.ipynb` and run the cells!

---

##  Dataset

The dataset used is the **COVID-19 Global dataset** containing:
- `Date` — Date of record
- `Country/Region` — Country name
- `Confirmed` — Total confirmed cases
- `Deaths` — Total deaths
- `Recovered` — Total recovered cases
- `Active` — Active cases (Confirmed - Deaths - Recovered)

> **Source:** [Johns Hopkins University CSSE GitHub](https://github.com/CSSEGISandData/COVID-19)

---

##  Key Findings

-  The **USA, India, and Brazil** consistently had the highest confirmed case counts.
-  Global cases grew exponentially through **early 2021**.
-  The **Case Fatality Rate (CFR)** varied significantly across countries.
-  Countries with high recovery rates had relatively **lower active case burdens**.

---

##  Author

**Anurag Gautam**  
GitHub:(https://github.com/Anuraggautam03)  

---
