# week-8
Project Overview
This project is a data analysis and reporting notebook (or app) that tracks global COVID-19 trends. It provides insights into cases, deaths, recoveries, and vaccinations across different countries and time periods using Python data tools.

By the end of the project, you will have a data analysis report with visualizations and narrative insights, suitable for presentation or publishing.

Objectives ✅
Import and clean COVID-19 datasets from Our World in Data or Johns Hopkins University

Analyze trends for cases, deaths, recoveries, and vaccinations

Compare COVID-19 metrics across countries

Visualize insights with charts and maps

Communicate findings through a structured Jupyter Notebook or PDF Report

Tools & Libraries Used 🛠️
Data Processing: pandas

Visualizations: matplotlib, seaborn, plotly

Geospatial Analysis (Optional): geopandas

Notebook Interface: Jupyter Notebook or VS Code with Jupyter extension

How to Run the Project 🚀
1️⃣ Install dependencies:

pip install pandas matplotlib seaborn plotly geopandas
2️⃣ Download the dataset:

Recommended: owid-covid-data.csv from Our World in Data

Place the file in your working folder 3️⃣ Run the Jupyter Notebook:

jupyter notebook
4️⃣ Follow the analysis steps inside the notebook.

Project Workflow 🔎
1️⃣ Data Collection
Obtain COVID-19 data from Our World in Data and Johns Hopkins University

Load dataset using pandas.read_csv()

2️⃣ Data Cleaning & Processing
Handle missing values (fillna() or interpolation)

Convert date format (pd.to_datetime())

Filter countries of interest (Kenya, USA, India, etc.)

3️⃣ Exploratory Data Analysis (EDA)
Plot total cases & deaths over time

Compare daily new cases between countries

Calculate death rate (total_deaths / total_cases)

Visualizations: Line charts, bar charts, heatmaps

4️⃣ Visualizing Vaccination Progress
Analyze vaccination rollouts over time

Compare % vaccinated population per country

5️⃣ Optional: Choropleth Map for Geographic Analysis 🌍
Map cases or vaccination rates per country

Tools: plotly or geopandas

6️⃣ Insights & Reporting
Write key insights based on the data (e.g., "X country had the fastest vaccine rollout")

Summarize findings using markdown cells in Jupyter Notebook

Deliverables: ✅ Jupyter Notebook with documented analysis ✅ Optional PDF or PowerPoint export

Project Contributors 👥
Developed as part of the PLP Academy Software Development Cohort

Contributions and feedback welcome!
