# phonepe_project1


phonepe-insight-transactions/
│── README.md                # Overview of the project
│── requirements.txt         # Python dependencies
│── data/
│   ├── raw/                 # Raw PhonePe Pulse JSON/CSV data
│   └── processed/           # Cleaned & transformed datasets
│── notebooks/
│   ├── EDA.ipynb            # Exploratory data analysis
│   ├── Transactions.ipynb   # Transaction analysis by state/district
│   ├── Insurance.ipynb      # Insurance adoption analysis
│── src/
│   ├── __init__.py
│   ├── data_loader.py       # Load & preprocess raw data
│   ├── data_cleaner.py      # Data cleaning & transformation
│   ├── analysis.py          # Core analytical functions
│   ├── visualization.py     # Charts, maps, and dashboards
│── dashboards/
│   ├── app.py               # Streamlit dashboard main file
│   └── components/          # Custom plots/widgets
│── database/
│   ├── schema.sql           # MySQL schema definition
│   └── loader.py            # Scripts to load data into MySQL
│── reports/
│   ├── PhonePe_Insights.pdf # Final report / presentation
│   └── figures/             # Exported plots & visualizations
│── .gitignore

------------

# 📊 PhonePe Transaction Insights  

This project analyzes **PhonePe Pulse transaction data** to uncover digital payment trends across Indian states & districts.  

## 🔑 Key Features
- State & district-level transaction analysis  
- User registrations & device dominance  
- Insurance growth trends  
- Interactive dashboards using **Streamlit**  
----------
## 🛠️ Tech Stack
- **Python** (pandas, matplotlib, seaborn, plotly)  
- **MySQL** (data storage & queries)  
- **Streamlit** (dashboard visualization)  
-----------
## 🚀 Quick Start
```bash
git clone https://github.com/your-username/phonepe-insight-transactions.git
cd phonepe-insight-transactions
pip install -r requirements.txt
streamlit run dashboards/app.py





