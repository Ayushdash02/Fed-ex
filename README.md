# FedEx Logistics Operations Analysis

### Exploratory Data Analysis (EDA) | Logistics & Supply Chain Analytics

<p align="center">
  <img src="preview/Fed-ex-logo.png" alt="FedEx Logo" width="240">
</p>

<p align="center">
  <strong>Transforming Supply Chain Data into Actionable Logistics Insights</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Project-Exploratory%20Data%20Analysis-blue" alt="Project">
  <img src="https://img.shields.io/badge/Python-Data%20Analysis-yellow" alt="Python">
  <img src="https://img.shields.io/badge/Google%20Colab-Notebook-orange" alt="Google Colab">
  <img src="https://img.shields.io/badge/Status-Completed-brightgreen" alt="Status">
</p>

---

## 📌 Project Overview

The **FedEx Logistics Operations Analysis** project explores supply chain and shipment data to understand logistics performance, freight costs, shipment modes, destination-country patterns, vendor contributions, manufacturing-site activity, and data quality.

Using **Python in Google Colab**, this project applies exploratory data analysis (EDA), statistical summaries, and visualizations to uncover patterns and generate actionable insights for logistics and supply chain decision-making.

## 🎯 Objectives

- Analyze shipment volumes across destination countries.
- Compare shipment activity by shipment mode.
- Identify leading vendors and manufacturing sites by shipment count.
- Examine freight-cost and shipment-weight distributions.
- Investigate relationships between shipment weight and freight cost.
- Compare average freight costs across destination countries and shipment modes.
- Explore correlations among key logistics variables.
- Assess missing values and summarize numerical features.

## 🧰 Tools & Technologies

- **Python**
- **Google Colab**
- **Pandas** — data manipulation and analysis
- **NumPy** — numerical computing
- **Matplotlib** — plotting
- **Seaborn** — statistical visualization
- **Plotly** — interactive visualization

## 📊 Visualizations

The following visualizations are included in this repository. The image paths below assume the images are stored in a folder named `visualizations/` in the repository root. If you keep them in the root directory, remove `visualizations/` from each image path.

### Shipment Destinations & Operations

| Visualization | Preview |
|---|---|
| Top 10 Destination Countries by Shipments | ![Top 10 Destination Countries by Shipments](visualizations/01-top-10-destination-countries-by-shipments.png) |
| Shipment Distribution by Mode | ![Shipment Distribution by Mode](visualizations/02-shipment-distribution-by-mode.png) |
| Top 10 Vendors by Shipments | ![Top 10 Vendors by Shipments](visualizations/03-top-10-vendors-by-shipments.png) |
| Top 10 Manufacturing Sites by Shipments | ![Top 10 Manufacturing Sites by Shipments](visualizations/04-top-10-manufacturing-sites-by-shipments.png) |
| Top 10 Destination Countries by Average Freight Cost | ![Top 10 Destination Countries by Average Freight Cost](visualizations/09-top-10-destination-countries-by-average-freight-cost.png) |
| Top 15 Destination Countries by Shipment Count | ![Top 15 Destination Countries by Shipment Count](visualizations/10-top-15-destination-countries-by-shipment-count.png) |

### Freight Costs & Shipment Weight

| Visualization | Preview |
|---|---|
| Freight Cost Distribution (USD) | ![Freight Cost Distribution USD](visualizations/05-freight-cost-distribution-usd.png) |
| Shipment Weight Distribution (kg) | ![Shipment Weight Distribution kg](visualizations/06-shipment-weight-distribution-kg.png) |
| Freight Cost by Shipment Mode | ![Freight Cost by Shipment Mode](visualizations/07-freight-cost-by-shipment-mode.png) |
| Shipment Weight vs. Freight Cost | ![Shipment Weight vs Freight Cost](visualizations/08-shipment-weight-vs-freight-cost.png) |
| Shipment Weight Distribution by Mode | ![Shipment Weight Distribution by Mode](visualizations/11-shipment-weight-distribution-by-mode.png) |
| Shipment Weight vs. Freight Cost Analysis | ![Shipment Weight vs Freight Cost Analysis](visualizations/12-shipment-weight-vs-freight-cost-analysis.png) |

### Statistical & Data Quality Analysis

| Visualization | Preview |
|---|---|
| Shipment Mode Distribution | ![Shipment Mode Distribution](visualizations/13-shipment-mode-distribution.png) |
| Correlation Heatmap of Logistics Variables | ![Correlation Heatmap of Logistics Variables](visualizations/14-correlation-heatmap-logistics-variables.png) |
| Pair Plot of Logistics Variables | ![Pair Plot of Logistics Variables](visualizations/15-pair-plot-logistics-variables.png) |
| Missing Values by Feature | ![Missing Values by Feature](visualizations/16-missing-values-by-feature.png) |
| Statistical Summary — Numerical Features | ![Statistical Summary Numerical Features](visualizations/17-statistical-summary-numerical-features.png) |

## 🔎 Analysis Workflow

1. Load the supply chain dataset into Google Colab.
2. Inspect dataset dimensions, column names, data types, and sample records.
3. Assess data quality, including missing values and duplicate records.
4. Prepare relevant numerical and categorical features for analysis.
5. Perform descriptive statistical analysis.
6. Explore shipment, vendor, destination, manufacturing-site, freight-cost, and weight patterns.
7. Create visualizations to communicate findings.
8. Summarize business implications and potential areas for operational improvement.

## 💡 Business Value

The analysis can help logistics stakeholders explore:

- Shipment concentration by destination and mode.
- Freight-cost variation across shipment modes and destinations.
- Relationships between shipment weight and freight cost.
- Vendor and manufacturing-site shipment contributions.
- Data-quality gaps that may affect reporting and operational analysis.

*These are analytical areas explored by the project; any business conclusions should be based on the results observed in the notebook.*

## 📁 Repository Structure

```text
Fed-ex/
├── README.md
├── FedEx_Logistics_Operations_Analysis.ipynb
├── Fed-ex-logo.png
├── requirements.txt
└── visualizations/
    ├── 01-top-10-destination-countries-by-shipments.png
    ├── 02-shipment-distribution-by-mode.png
    ├── 03-top-10-vendors-by-shipments.png
    ├── 04-top-10-manufacturing-sites-by-shipments.png
    ├── 05-freight-cost-distribution-usd.png
    ├── 06-shipment-weight-distribution-kg.png
    ├── 07-freight-cost-by-shipment-mode.png
    ├── 08-shipment-weight-vs-freight-cost.png
    ├── 09-top-10-destination-countries-by-average-freight-cost.png
    ├── 10-top-15-destination-countries-by-shipment-count.png
    ├── 11-shipment-weight-distribution-by-mode.png
    ├── 12-shipment-weight-vs-freight-cost-analysis.png
    ├── 13-shipment-mode-distribution.png
    ├── 14-correlation-heatmap-logistics-variables.png
    ├── 15-pair-plot-logistics-variables.png
    ├── 16-missing-values-by-feature.png
    └── 17-statistical-summary-numerical-features.png
```

> **Important:** GitHub image links are case-sensitive. Keep the filenames and folder names in this README exactly aligned with the files you upload. If your current image names differ, rename the files or update the paths above.

## ▶️ Run the Notebook

1. Open the notebook file in GitHub.
2. Select **Open in Colab** if you have configured the notebook with a Colab badge/link, or upload the `.ipynb` file to [Google Colab](https://colab.research.google.com/).
3. Upload or mount the dataset required by the notebook.
4. Run the cells in order.

## 📦 Requirements

Create a `requirements.txt` containing the libraries used by the notebook:

```text
pandas
numpy
matplotlib
seaborn
plotly
```

Google Colab already includes many common data-analysis packages. Install any missing package with `pip` inside the notebook.

## 👤 Project Information

- **Project:** FedEx Logistics Operations Analysis
- **Project Type:** Individual Project
- **Domain:** Logistics & Supply Chain Analytics
- **Notebook Environment:** Google Colab
- **Author:** Ayush Dash

## 🚀 Future Improvements

- Add a reproducible data-cleaning pipeline.
- Include validated KPI calculations and a concise findings section.
- Compare shipment modes and destinations using appropriate statistical tests.
- Add interactive Plotly charts where they improve exploration.
- Develop a dashboard for monitoring logistics KPIs over time, if the dataset includes suitable date fields.

## 📄 License

Add a license file if you want to define how others may use, modify, and distribute this project. If you choose the MIT License, include the full license text in a `LICENSE` file.

---

<p align="center">
  <strong>FedEx Logistics Operations Analysis</strong><br>
  Exploratory Data Analysis for Supply Chain Insights
</p>
