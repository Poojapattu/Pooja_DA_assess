# Pooja_DA_assess
# 🚘 Uber Transportation Data Analysis  
**Author:** Pooja Pattu  
**Domain:** Transportation  
**Internship Round 1 – Data Analyst Assignment**

---

## 🧭 **Project Overview**
This project analyzes **Uber transportation data** to uncover key insights about ride demand, trip patterns, and route efficiency.  
The goal is to provide **data-driven recommendations** that help improve driver allocation, scheduling, and overall operational performance.

---

## 📊 **Dataset Information**
- **Source:** [Uber Pickups Dataset (Kaggle)](https://www.kaggle.com/datasets/fivethirtyeight/uber-pickups-in-new-york-city)  
- **Records:** 1,100+ Uber rides  
- **Attributes:** Start/End date, Category (Business/Personal), Start–Stop locations, Miles, Purpose, Duration, Day, and Hour  

---

## ⚙️ **Project Structure**

Uber-Transportation-Analysis/
│
├── data/
│ ├── raw/ # Original dataset (UberDataset.csv)
│ └── cleaned and preprocessed data/
│ ├── UberDataset_Cleaned.csv
│ └── UberDataset_Preprocessed.csv
│
├── scripts/
│ ├── 02_cleaning.py # Data cleaning script
│ └── 03_preprocessing.py # Data preprocessing script
│
├── notebooks/
│ └── uber_analysis.ipynb # Analysis & visualization notebook
│
├── reports/
│ ├── Dataset_Selection.md
│ ├── Analysis_Report.pdf
│ └── Presentation.pptx # Optional 5-slide presentation
│
├── requirements.txt # Python dependencies
├── README.md # Setup instructions and overview
└── .gitignore

yaml
Copy code

---

## 🧩 **Setup Instructions**

### **1️⃣ Clone this repository**
```bash
git clone https://github.com/Poojapattu/data-analyst-intern-assignment-poojapattu.git
cd data-analyst-intern-assignment-poojapattu
2️⃣ Create a virtual environment
bash
Copy code
python -m venv venv
venv\Scripts\activate    # On Windows
# OR
source venv/bin/activate # On macOS/Linux
3️⃣ Install dependencies
bash
Copy code
pip install -r requirements.txt
4️⃣ Run cleaning and preprocessing scripts
bash
Copy code
python scripts/02_cleaning.py
python scripts/03_preprocessing.py
Both cleaned and preprocessed datasets will be saved in:
data/cleaned and preprocessed data/

5️⃣ Launch the analysis notebook
bash
Copy code
jupyter notebook notebooks/uber_analysis.ipynb
Run all cells to generate the insights and visualizations.

🧠 Key Insights Summary
#	Insight	Business Impact
1	Evening peak ride demand (5–9 PM)	Optimize driver scheduling
2	Weekday–Weekend travel pattern	Balance fleet deployment
3	Fort Pierce is the top pickup zone	Create regional driver hubs
4	Strong distance–duration correlation	Predictive ETA accuracy
5	Meeting/Customer visits dominate	Target corporate travel plans

💼 Business Recommendations
Deploy more drivers during evening hours

Create micro-hubs in high-demand pickup areas

Offer weekend promos to increase personal trips

Build predictive scheduling systems for future planning

🧰 Technologies Used
Python 3.11+

Pandas – Data cleaning and transformation

NumPy – Numerical analysis

Matplotlib / Seaborn – Visualizations

Scikit-learn – Encoding and scaling

Jupyter Notebook – Exploratory analysis and reporting

📈 Results
The analysis identified actionable insights that can reduce wait times, enhance fleet utilization, and improve user satisfaction in the transportation domain.
All findings are supported by reproducible scripts and clear visual evidence.

🧾 Author
👩‍💻 Pooja Pattu
B.Tech in Artificial Intelligence & Data Science
Aspiring Data Analyst

📧 Contact: poojadhangam@gmail.com
