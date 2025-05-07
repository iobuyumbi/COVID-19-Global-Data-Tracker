# 🦠 COVID-19 Global Data Tracker 📊

This project analyzes global COVID-19 trends using data from **Our World in Data**. It explores case counts, deaths, and vaccination rollouts across selected countries with visualizations and descriptive insights.

---

## 📁 Dataset

- **Source**: [Our World in Data - COVID-19](https://ourworldindata.org/covid-cases)
- **File used**: `owid-covid-data.csv`

---

## 📌 Project Goals

- Import and clean real-world COVID-19 data.
- Analyze trends in total cases, deaths, and vaccinations.
- Compare country-wise metrics.
- Visualize findings using line charts and bar charts.
- Summarize key insights in a Jupyter Notebook.

---

## 🛠️ Tools Used

- Python (pandas, matplotlib, seaborn, plotly)
- Jupyter Notebook
- Visual Studio Code (with Jupyter extension)

---

## 📊 Visualizations

- 📈 Total cases over time for Kenya, USA, and India
- 📊 Bar charts for country comparisons
- 📉 Trends in daily new cases and deaths
- 💉 Vaccination progress over time
- 🌍 Choropleth map showing COVID-19 cases across countries

---

## ✅ Setup Instructions

### 1. Clone the repository

```bash
git clone https://github.com/iobuyumbi/COVID-19-Global-Data-Tracker.git
cd COVID-19-Global-Data-Tracker
```

### 2. Create and activate a virtual environment

On Windows:

```bash
python -m venv venv
venv\\Scripts\\activate
```

On macOS/Linux:

```bash
python3 -m venv venv
source venv/bin/activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

## 📊 Project Features

- 📥 Load and clean global COVID-19 datasets
- 🔍 Perform descriptive and exploratory data analysis (EDA)
- 📈 Visualize trends in cases, deaths, and vaccinations
- 🌍 Choropleth map for country-wise visual comparison
- 📄 Generate summary insights with markdown reporting
- 🧠 Optional extensions: forecasting, clustering, dashboards

## 🔍 Insights & Findings

### Key Takeaways:

- United States reported the highest cumulative COVID-19 cases and deaths globally.
- India experienced sharp waves with spikes in daily new cases, especially during 2021.
- Kenya had relatively lower case numbers, with slower but steady vaccine rollout.
- Vaccination trends show large disparities: high coverage in wealthy nations, low in others.
- Death rate (deaths / cases) varied by country, possibly due to differences in testing, healthcare, and reporting.

## 📌 Data Sources

- Our World in Data - COVID-19
- Kaggle COVID-19 Datasets
- Johns Hopkins CSSE GitHub Repository

## 🙋 Author

**Innocent Obuyumbi Nyongesa**  
[GitHub](https://github.com/your-username) | [Email](mailto:iobuyumbi@gmail.com)

## 📤 Output Formats

Final output is available as:

- 📝 Jupyter Notebook (interactive)
- 📄 PDF or HTML report (optional export)

## 🚀 Stretch Goals (Optional)

- Add country/date filter for user input
- Interactive dashboard using Streamlit
- Incorporate ICU or hospitalization data

## 📚 License

This project is for educational and non-commercial use. Attribution appreciated.
